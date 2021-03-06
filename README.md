# Tokenomics_KaseiCoin_Crowdsale

Create a fungible token that is ERC-20 compliant and that will be minted by using a Crowdsale contract from the OpenZeppelin Solidity library

# Technologies

Solidity,
Remix,
Ganache,
MetaMask

## Import the required libraries and dependencies

import "https://github.com/OpenZeppelin/openzeppelin-contracts/blob/release-v2.5.0/contracts/token/ERC20/ERC20.sol";

import "https://github.com/OpenZeppelin/openzeppelin-contracts/blob/release-v2.5.0/contracts/token/ERC20/ERC20Detailed.sol";

import "https://github.com/OpenZeppelin/openzeppelin-contracts/blob/release-v2.5.0/contracts/token/ERC20/ERC20Mintable.sol";

import "https://github.com/OpenZeppelin/openzeppelin-contracts/blob/release-v2.5.0/contracts/crowdsale/Crowdsale.sol";

import "https://github.com/OpenZeppelin/openzeppelin-contracts/blob/release-v2.5.0/contracts/crowdsale/emission/MintedCrowdsale.sol";

# Usage

1. Go to remix.ethereum.org and upload KaseiCoin.sol and KaseiCoinCrowdsale.sol in workspace,
2. Launch Ganache and click Quickstart and save workspace,
3. Download the MetaMask extension in Chrome. Create new Network and import 2 accounts by linking Ganache private keys,
4. Compile contracts,
5. Run and Deploy contracts
6. Select Environment to be `Injected Web3`
6. Perform transactions.


# Evaluation Evidence

Compiled KaseiCoin Contract

<img width="1616" alt="Compile_KaseiCoin_Contract" src="https://user-images.githubusercontent.com/93550651/170845364-87bebe4b-0a9f-43a1-9eeb-8a87ddeea07f.png">

Compiled KaseiCoin Crowdsale Contract

<img width="1616" alt="Compiled_KSC_Crowdsale_Contract" src="https://user-images.githubusercontent.com/93550651/170845522-d46d5087-d842-4bc9-8113-621b25bdf2ce.png">

Compiled KaseiCoin Crowdsale  Deployer Contract

<img width="1616" alt="Compile_KSC_Crowdsale_Deployer" src="https://user-images.githubusercontent.com/93550651/170845580-212336f4-4e36-466f-8324-89afa0616814.png">

Connect Remix Ganach and MetaMask

<img width="1685" alt="Connect_Remix_Ganache_MetaMask" src="https://user-images.githubusercontent.com/93550651/170845767-d59cb1df-81ec-4856-8b3e-9f9ebb4f5ffb.png">

Deployer creates addresses for kasei_crowdsale_address and kasei_token_address
<img width="412" alt="Deployer_Addresses" src="https://user-images.githubusercontent.com/93550651/170845793-3f31b128-6896-40d5-ae4d-624610070df4.png">

Compiled and Connected Contracts

<img width="814" alt="Compiled_Connected_Contracts" src="https://user-images.githubusercontent.com/93550651/170845988-111fe485-e077-4036-a41e-c2daf96546f5.png">

Confirm Block Transactions

<img width="814" alt="Confirm_Block_Transactions" src="https://user-images.githubusercontent.com/93550651/170846027-548149cb-6a71-4664-a39f-c784a52b621e.png">

buyTokens

Gas estimation failed error

<img width="814" alt="Gas_estimation_failed_error" src="https://user-images.githubusercontent.com/93550651/170846139-6c1c2f8a-18a2-48bc-89ff-c84ba14c0d67.png">

Clicked Send Transaction, MetaMask Notification pops up to push transaction

<img width="378" alt="MetaMask_notification_Gas" src="https://user-images.githubusercontent.com/93550651/170846196-e1157196-5987-456a-8ab9-e4e941b30d66.png">

Transaction Error

<img width="1613" alt="transact_error_messages" src="https://user-images.githubusercontent.com/93550651/170846591-dc9b3710-6adb-4b08-a914-d558527f8901.png">

Error text reads

transact to KaseiCoinCrowdsale.buyTokens errored: [ethjs-query] while formatting outputs from RPC '{"value":{"code":-32603,"data":{"message":"VM Exception while processing transaction: revert MinterRole: caller does not have the Minter role","code":-32000,"data":{"0xaf0023eaa411a69800385b7f595596124e0f237bec19d34bc6fdf18e3bbf25f6":{"error":"revert","program_counter":1786,"return":"0x08c379a0000000000000000000000000000000000000000000000000000000000000002000000000000000000000000000000000000000000000000000000000000000304d696e746572526f6c653a2063616c6c657220646f6573206e6f74206861766520746865204d696e74657220726f6c6500000000000000000000000000000000","reason":"MinterRole: caller does not have the Minter role"},"stack":"RuntimeError: VM Exception while processing transaction: revert MinterRole: caller does not have the Minter role\n    at Function.RuntimeError.fromResults (/Applications/Ganache.app/Contents/Resources/static/node/node_modules/ganache-core/lib/utils/runtimeerror.js:94:13)\n    at BlockchainDouble.processBlock (/Applications/Ganache.app/Contents/Resources/static/node/node_modules/ganache-core/lib/blockchain_double.js:627:24)\n    at runMicrotasks (<anonymous>)\n    at processTicksAndRejections (internal/process/task_queues.js:93:5)","name":"RuntimeError"}}}}'

# Contributors
Contributor: John Batarse

Email: jbatarse@hotmail.com


 # License
Trilogy Education LLC. and UC Berkeley
