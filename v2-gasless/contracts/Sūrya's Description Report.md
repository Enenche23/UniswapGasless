 Sūrya's Description Report

 Files Description Table


|  File Name  |  SHA-1 Hash  |
|-------------|--------------|
| /home/chris/Desktop/UniswapGasless/v2-gasless/contracts/UniswapV2Router01.sol | 0e67ac06da88be0fa56fe2fbf73be3cdd3580cb9 |
| /home/chris/Desktop/UniswapGasless/v2-gasless/contracts/UniswapV2Router02.sol | 3e7a59ed43cc9dca1c1bf21a1262ebedbb6702b9 |
| /home/chris/Desktop/UniswapGasless/v2-gasless/contracts/interfaces/IUniswapV2Router02.sol | 0d2ae53fa0c621cbc7e0e46e506c562068037f6c |
| /home/chris/Desktop/UniswapGasless/v2-gasless/contracts/interfaces/IUniswapV2Router01.sol | f150379f2a39f6d992f9a0aa35915ea1f64658d9 |
| /home/chris/Desktop/UniswapGasless/v2-gasless/contracts/libraries/UniswapV2Library.sol | 94c368ed5cbc221e5ef9be86d4021f6ef0ab1057 |
| /home/chris/Desktop/UniswapGasless/v2-gasless/contracts/libraries/SafeMath.sol | 123c932c8701c1178d049c82339bc68cd3c61d18 |
| /home/chris/Desktop/UniswapGasless/v2-gasless/contracts/interfaces/IERC20.sol | b7d011aaabd34898ee60760996cb702e7b2ca855 |
| /home/chris/Desktop/UniswapGasless/v2-gasless/contracts/interfaces/IWETH.sol | 6a25dd53c8494e3aef3a520f17e00608b529f061 |
| /home/chris/Desktop/UniswapGasless/v2-gasless/contracts/EIP712MetaTransaction.sol | e70fbfec4d8c9f4f03ee6674fccb0c53493e96c7 |
| /home/chris/Desktop/UniswapGasless/v2-gasless/contracts/libraries/EIP712Base.sol | 8b48140486b84c40a837d08f57b3dabc27fff62d |
| /home/chris/Desktop/UniswapGasless/v2-gasless/contracts/UniswapV2Migrator.sol | 2dc1b4329313afcf4a68f6f240f8908652070a26 |
| /home/chris/Desktop/UniswapGasless/v2-gasless/contracts/interfaces/IUniswapV2Migrator.sol | fe1d2218375f45b535aaed1e75809db201d7eaf6 |
| /home/chris/Desktop/UniswapGasless/v2-gasless/contracts/interfaces/V1/IUniswapV1Factory.sol | 41777838b683a6861b8f41d91a9b418eafd42526 |
| /home/chris/Desktop/UniswapGasless/v2-gasless/contracts/interfaces/V1/IUniswapV1Exchange.sol | ba992548a32038fcca1cebdcfd4b11f81f726391 |


 Contracts Description Table


|  Contract  |         Type        |       Bases      |                  |                 |
|:----------:|:-------------------:|:----------------:|:----------------:|:---------------:|
|     └      |  **Function Name**  |  **Visibility**  |  **Mutability**  |  **Modifiers**  |
||||||
| **UniswapV2Router01** | Implementation | IUniswapV2Router01 |||
| └ | <Constructor> | Public ❗️ | 🛑  |NO❗️ |
| └ | <Receive Ether> | External ❗️ |  💵 |NO❗️ |
| └ | _addLiquidity | Private 🔐 | 🛑  | |
| └ | addLiquidity | External ❗️ | 🛑  | ensure |
| └ | addLiquidityETH | External ❗️ |  💵 | ensure |
| └ | removeLiquidity | Public ❗️ | 🛑  | ensure |
| └ | removeLiquidityETH | Public ❗️ | 🛑  | ensure |
| └ | removeLiquidityWithPermit | External ❗️ | 🛑  |NO❗️ |
| └ | removeLiquidityETHWithPermit | External ❗️ | 🛑  |NO❗️ |
| └ | _swap | Private 🔐 | 🛑  | |
| └ | swapExactTokensForTokens | External ❗️ | 🛑  | ensure |
| └ | swapTokensForExactTokens | External ❗️ | 🛑  | ensure |
| └ | swapExactETHForTokens | External ❗️ |  💵 | ensure |
| └ | swapTokensForExactETH | External ❗️ | 🛑  | ensure |
| └ | swapExactTokensForETH | External ❗️ | 🛑  | ensure |
| └ | swapETHForExactTokens | External ❗️ |  💵 | ensure |
| └ | quote | Public ❗️ |   |NO❗️ |
| └ | getAmountOut | Public ❗️ |   |NO❗️ |
| └ | getAmountIn | Public ❗️ |   |NO❗️ |
| └ | getAmountsOut | Public ❗️ |   |NO❗️ |
| └ | getAmountsIn | Public ❗️ |   |NO❗️ |
||||||
| **UniswapV2Router02** | Implementation | IUniswapV2Router02, EIP712MetaTransaction |||
| └ | <Constructor> | Public ❗️ | 🛑  | EIP712MetaTransaction |
| └ | <Receive Ether> | External ❗️ |  💵 |NO❗️ |
| └ | _addLiquidity | Internal 🔒 | 🛑  | |
| └ | addLiquidity | External ❗️ | 🛑  | ensure |
| └ | addLiquidityETH | External ❗️ |  💵 | ensure |
| └ | removeLiquidity | Public ❗️ | 🛑  | ensure |
| └ | removeLiquidityETH | Public ❗️ | 🛑  | ensure |
| └ | removeLiquidityWithPermit | External ❗️ | 🛑  |NO❗️ |
| └ | removeLiquidityETHWithPermit | External ❗️ | 🛑  |NO❗️ |
| └ | removeLiquidityETHSupportingFeeOnTransferTokens | Public ❗️ | 🛑  | ensure |
| └ | removeLiquidityETHWithPermitSupportingFeeOnTransferTokens | External ❗️ | 🛑  |NO❗️ |
| └ | _swap | Internal 🔒 | 🛑  | |
| └ | swapExactTokensForTokens | External ❗️ | 🛑  | ensure |
| └ | swapTokensForExactTokens | External ❗️ | 🛑  | ensure |
| └ | swapExactETHForTokens | External ❗️ |  💵 | ensure |
| └ | swapTokensForExactETH | External ❗️ | 🛑  | ensure |
| └ | swapExactTokensForETH | External ❗️ | 🛑  | ensure |
| └ | swapETHForExactTokens | External ❗️ |  💵 | ensure |
| └ | _swapSupportingFeeOnTransferTokens | Internal 🔒 | 🛑  | |
| └ | swapExactTokensForTokensSupportingFeeOnTransferTokens | External ❗️ | 🛑  | ensure |
| └ | swapExactETHForTokensSupportingFeeOnTransferTokens | External ❗️ |  💵 | ensure |
| └ | swapExactTokensForETHSupportingFeeOnTransferTokens | External ❗️ | 🛑  | ensure |
| └ | quote | Public ❗️ |   |NO❗️ |
| └ | getAmountOut | Public ❗️ |   |NO❗️ |
| └ | getAmountIn | Public ❗️ |   |NO❗️ |
| └ | getAmountsOut | Public ❗️ |   |NO❗️ |
| └ | getAmountsIn | Public ❗️ |   |NO❗️ |
||||||
| **IUniswapV2Router02** | Interface | IUniswapV2Router01 |||
| └ | removeLiquidityETHSupportingFeeOnTransferTokens | External ❗️ | 🛑  |NO❗️ |
| └ | removeLiquidityETHWithPermitSupportingFeeOnTransferTokens | External ❗️ | 🛑  |NO❗️ |
| └ | swapExactTokensForTokensSupportingFeeOnTransferTokens | External ❗️ | 🛑  |NO❗️ |
| └ | swapExactETHForTokensSupportingFeeOnTransferTokens | External ❗️ |  💵 |NO❗️ |
| └ | swapExactTokensForETHSupportingFeeOnTransferTokens | External ❗️ | 🛑  |NO❗️ |
||||||
| **IUniswapV2Router01** | Interface |  |||
| └ | factory | External ❗️ |   |NO❗️ |
| └ | WETH | External ❗️ |   |NO❗️ |
| └ | addLiquidity | External ❗️ | 🛑  |NO❗️ |
| └ | addLiquidityETH | External ❗️ |  💵 |NO❗️ |
| └ | removeLiquidity | External ❗️ | 🛑  |NO❗️ |
| └ | removeLiquidityETH | External ❗️ | 🛑  |NO❗️ |
| └ | removeLiquidityWithPermit | External ❗️ | 🛑  |NO❗️ |
| └ | removeLiquidityETHWithPermit | External ❗️ | 🛑  |NO❗️ |
| └ | swapExactTokensForTokens | External ❗️ | 🛑  |NO❗️ |
| └ | swapTokensForExactTokens | External ❗️ | 🛑  |NO❗️ |
| └ | swapExactETHForTokens | External ❗️ |  💵 |NO❗️ |
| └ | swapTokensForExactETH | External ❗️ | 🛑  |NO❗️ |
| └ | swapExactTokensForETH | External ❗️ | 🛑  |NO❗️ |
| └ | swapETHForExactTokens | External ❗️ |  💵 |NO❗️ |
| └ | quote | External ❗️ |   |NO❗️ |
| └ | getAmountOut | External ❗️ |   |NO❗️ |
| └ | getAmountIn | External ❗️ |   |NO❗️ |
| └ | getAmountsOut | External ❗️ |   |NO❗️ |
| └ | getAmountsIn | External ❗️ |   |NO❗️ |
||||||
| **UniswapV2Library** | Library |  |||
| └ | sortTokens | Internal 🔒 |   | |
| └ | pairFor | Internal 🔒 |   | |
| └ | getReserves | Internal 🔒 |   | |
| └ | quote | Internal 🔒 |   | |
| └ | getAmountOut | Internal 🔒 |   | |
| └ | getAmountIn | Internal 🔒 |   | |
| └ | getAmountsOut | Internal 🔒 |   | |
| └ | getAmountsIn | Internal 🔒 |   | |
||||||
| **SafeMath** | Library |  |||
| └ | add | Internal 🔒 |   | |
| └ | sub | Internal 🔒 |   | |
| └ | mul | Internal 🔒 |   | |
||||||
| **IERC20** | Interface |  |||
| └ | name | External ❗️ |   |NO❗️ |
| └ | symbol | External ❗️ |   |NO❗️ |
| └ | decimals | External ❗️ |   |NO❗️ |
| └ | totalSupply | External ❗️ |   |NO❗️ |
| └ | balanceOf | External ❗️ |   |NO❗️ |
| └ | allowance | External ❗️ |   |NO❗️ |
| └ | approve | External ❗️ | 🛑  |NO❗️ |
| └ | transfer | External ❗️ | 🛑  |NO❗️ |
| └ | transferFrom | External ❗️ | 🛑  |NO❗️ |
||||||
| **IWETH** | Interface |  |||
| └ | deposit | External ❗️ |  💵 |NO❗️ |
| └ | transfer | External ❗️ | 🛑  |NO❗️ |
| └ | withdraw | External ❗️ | 🛑  |NO❗️ |
||||||
| **EIP712MetaTransaction** | Implementation | EIP712Base |||
| └ | <Constructor> | Public ❗️ | 🛑  | EIP712Base |
| └ | executeMetaTransaction | Public ❗️ |  💵 |NO❗️ |
| └ | hashMetaTransaction | Internal 🔒 |   | |
| └ | getNonce | Public ❗️ |   |NO❗️ |
| └ | verify | Internal 🔒 |   | |
| └ | msgSender | Internal 🔒 |   | |
||||||
| **EIP712Base** | Implementation |  |||
| └ | <Constructor> | Public ❗️ | 🛑  |NO❗️ |
| └ | getChainID | Internal 🔒 |   | |
| └ | getDomainSeperator | Private 🔐 |   | |
| └ | toTypedMessageHash | Internal 🔒 |   | |
||||||
| **UniswapV2Migrator** | Implementation | IUniswapV2Migrator |||
| └ | <Constructor> | Public ❗️ | 🛑  |NO❗️ |
| └ | <Receive Ether> | External ❗️ |  💵 |NO❗️ |
| └ | migrate | External ❗️ | 🛑  |NO❗️ |
||||||
| **IUniswapV2Migrator** | Interface |  |||
| └ | migrate | External ❗️ | 🛑  |NO❗️ |
||||||
| **IUniswapV1Factory** | Interface |  |||
| └ | getExchange | External ❗️ |   |NO❗️ |
||||||
| **IUniswapV1Exchange** | Interface |  |||
| └ | balanceOf | External ❗️ |   |NO❗️ |
| └ | transferFrom | External ❗️ | 🛑  |NO❗️ |
| └ | removeLiquidity | External ❗️ | 🛑  |NO❗️ |
| └ | tokenToEthSwapInput | External ❗️ | 🛑  |NO❗️ |
| └ | ethToTokenSwapInput | External ❗️ |  💵 |NO❗️ |


 Legend

|  Symbol  |  Meaning  |
|:--------:|-----------|
|    🛑    | Function can modify state |
|    💵    | Function is payable |
