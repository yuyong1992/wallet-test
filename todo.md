1. install truffle.js
    1. npm install truffle
2. initialize truffle project
    1. truffle init
3. install ganache
    1. 官网下载地址：https://www.trufflesuite.com/ganache
    2. 安装 ganache
    3. 创建 工作区，连接truffle项目
4. 安装MetaMask Chrome插件
    1. 地址：metamask.io/
    2. MetaMask 设置密码、记录12个助记词
    3. 创建本地区块链网络
        RPC URL：http://localhost:7545
        chain id ： 1337
        符号：ETH
    4. 导入本地账户
    5. MetaMask 操作本地账户转账
5. 安装OpenZeppelin
    1. npm install @openzeppelin/contracts
6. contracts 文件夹下创建合约文件：date.sol
    1. 指定 solidity 版本
    2. 合约内容
7. migrations 文件夹下创建迁移文件：2_token_migration.js
    1. 
    2. 
8. 执行编译
    1. truffle compile
9. 执行迁移
    1. truffle migration
