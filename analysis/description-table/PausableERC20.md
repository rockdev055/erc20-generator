## SÅ«rya's Description Report

### Files Description Table


|  File Name  |  SHA-1 Hash  |
|-------------|--------------|
| dist/PausableERC20.dist.sol | cc5f2e92d8782ce9bb09c0cff86f4093b6193766 |


### Contracts Description Table


|  Contract  |         Type        |       Bases      |                  |                 |
|:----------:|:-------------------:|:----------------:|:----------------:|:---------------:|
|     â      |  **Function Name**  |  **Visibility**  |  **Mutability**  |  **Modifiers**  |
||||||
| **Context** | Implementation |  |||
| â | _msgSender | Internal ð |   | |
| â | _msgData | Internal ð |   | |
||||||
| **Ownable** | Implementation | Context |||
| â | <Constructor> | Public âï¸ | ð  |NOâï¸ |
| â | owner | Public âï¸ |   |NOâï¸ |
| â | renounceOwnership | Public âï¸ | ð  | onlyOwner |
| â | transferOwnership | Public âï¸ | ð  | onlyOwner |
||||||
| **IERC20** | Interface |  |||
| â | totalSupply | External âï¸ |   |NOâï¸ |
| â | balanceOf | External âï¸ |   |NOâï¸ |
| â | transfer | External âï¸ | ð  |NOâï¸ |
| â | allowance | External âï¸ |   |NOâï¸ |
| â | approve | External âï¸ | ð  |NOâï¸ |
| â | transferFrom | External âï¸ | ð  |NOâï¸ |
||||||
| **SafeMath** | Library |  |||
| â | tryAdd | Internal ð |   | |
| â | trySub | Internal ð |   | |
| â | tryMul | Internal ð |   | |
| â | tryDiv | Internal ð |   | |
| â | tryMod | Internal ð |   | |
| â | add | Internal ð |   | |
| â | sub | Internal ð |   | |
| â | mul | Internal ð |   | |
| â | div | Internal ð |   | |
| â | mod | Internal ð |   | |
| â | sub | Internal ð |   | |
| â | div | Internal ð |   | |
| â | mod | Internal ð |   | |
||||||
| **ERC20** | Implementation | Context, IERC20 |||
| â | <Constructor> | Public âï¸ | ð  |NOâï¸ |
| â | name | Public âï¸ |   |NOâï¸ |
| â | symbol | Public âï¸ |   |NOâï¸ |
| â | decimals | Public âï¸ |   |NOâï¸ |
| â | totalSupply | Public âï¸ |   |NOâï¸ |
| â | balanceOf | Public âï¸ |   |NOâï¸ |
| â | transfer | Public âï¸ | ð  |NOâï¸ |
| â | allowance | Public âï¸ |   |NOâï¸ |
| â | approve | Public âï¸ | ð  |NOâï¸ |
| â | transferFrom | Public âï¸ | ð  |NOâï¸ |
| â | increaseAllowance | Public âï¸ | ð  |NOâï¸ |
| â | decreaseAllowance | Public âï¸ | ð  |NOâï¸ |
| â | _transfer | Internal ð | ð  | |
| â | _mint | Internal ð | ð  | |
| â | _burn | Internal ð | ð  | |
| â | _approve | Internal ð | ð  | |
| â | _setupDecimals | Internal ð | ð  | |
| â | _beforeTokenTransfer | Internal ð | ð  | |
||||||
| **Pausable** | Implementation | Context |||
| â | <Constructor> | Public âï¸ | ð  |NOâï¸ |
| â | paused | Public âï¸ |   |NOâï¸ |
| â | _pause | Internal ð | ð  | whenNotPaused |
| â | _unpause | Internal ð | ð  | whenPaused |
||||||
| **ERC20Pausable** | Implementation | ERC20, Pausable |||
| â | _beforeTokenTransfer | Internal ð | ð  | |
||||||
| **IPayable** | Interface |  |||
| â | pay | External âï¸ |  ðµ |NOâï¸ |
||||||
| **ServicePayer** | Implementation |  |||
| â | <Constructor> | Public âï¸ |  ðµ |NOâï¸ |
||||||
| **PausableERC20** | Implementation | ERC20Pausable, Ownable, ServicePayer |||
| â | <Constructor> | Public âï¸ |  ðµ | ERC20 ServicePayer |
| â | pause | External âï¸ | ð  | onlyOwner |
| â | unpause | External âï¸ | ð  | onlyOwner |


### Legend

|  Symbol  |  Meaning  |
|:--------:|-----------|
|    ð    | Function can modify state |
|    ðµ    | Function is payable |
