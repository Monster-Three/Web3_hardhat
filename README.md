# Sample Hardhat Project

This project demonstrates a basic Hardhat use case. It comes with a sample contract, a test for that contract, and a Hardhat Ignition module that deploys that contract.

Try running some of the following tasks:

```shell
npx hardhat help
npx hardhat test
REPORT_GAS=true npx hardhat test
npx hardhat node
npx hardhat ignition deploy ./ignition/modules/Lock.js
```

#npm、npx的区别
nvm，全称是Node Version Manager，是用来管理node.js的版本的。
因为Node.js在不断的被完善，分版本迭代更新。
当前版本：nodejs.org/en/download…
历史版本：nodejs.org/en/download…
安装命令：nvm install 22（安装22版本）

npm，全称是Node Package Manager，是以JavaScript编写的软件包管理工具。用来安装node项目所需要的一堆依赖包。
在运行一些node项目的时候，我们经常需要在项目的根目录下先执行命令
npm install
该命令就是根据项目根目录下的package.json配置文件，通过npm工具来安装项目所需要的一堆依赖包。

