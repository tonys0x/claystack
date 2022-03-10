
# ClayStack - Victoria Staking ReDeFined
## How to use:

### Setting up
* git clone https://github.com/ericet/claystack.git
* cd claystack
* npm install
* mv .env.example .env
* Put your private key(keys) into KEYS field. Eg: KEYS=000000000,011111111,0222222222
* There is requests limit on the default API I provided in the .env. So it's better to get yourself a own API from https://www.alchemy.com/ or https://infura.io/ (Goerli Network and Rinkeby Network)
* You need a little bit of GETH and ETH(Rinkeby) 
## Claiming from Faucet, Staking, Unstaking and claim stake for Goerli Network
* `node victoria_goerli.js`

## Claiming from Faucet, Staking, Unstaking and claim stake for Rinkeby Network
* `node victoria_rinkeby.js`

### Check ranking
* `node victoria_ranking.js` 


If you find this script is useful to you, donation will be appreciated: **0x434DCffCF7dABd48B284860C27ebd184C91341F5**

---
## 设置
* git clone https://github.com/ericet/claystack.git
* cd claystack
* npm install
* 文件改名
  * mv .env.example .env
* 把私钥放在.env 文件里面的KEYS后面。比如：KEYS=000000000,011111111,0222222222
* GOERLI_FUNDING_KEY=后面填一个钱包的私钥，这个钱包需要有足够的Goerli的ETH测试币，当其他号的ETH低于0.01的时候，自动转账0.1 ETH过去。不填就不会自动转账
* RINKEBY_FUNDING_KEY=后面填一个钱包的私钥，这个钱包需要有足够的Rinkeby的ETH测试币，当其他号的ETH低于0.01的时候，自动转账0.1 ETH过去。不填就不会自动转账
* .env文件里面配置的API有请求限制，所以最好申请一个自己的API。你可以通过https://www.alchemy.com/ 或者 https://infura.io/ 申请API（Goerli和Rinkeby网络)
* 钱包需要一点的GETH(Goerli)和ETH(Rinbeky)才能运行脚本
## 自动领测试币(MATIC)，质押，解除质押和领取解除的质押（Goerli网络)
* `node victoria_goerli.js`

## 自动领测试币(GRT)，质押，解除质押和领取解除的质押（Rinkeby网络)
* `node victoria_rinkeby.js`

## 查看排名和积分
* `node victoria_ranking.js`



如果你觉得脚本帮助到你，可以捐献一点心意。钱包地址：**0x434DCffCF7dABd48B284860C27ebd184C91341F5**, 各链通用. 谢谢！



---
---

# ClayStack - Collect to access Malawi testnet (ENDED)
## How to use:

### Setting up
* git clone https://github.com/ericet/claystack.git
* cd claystack
* npm install
* mv .env.example .env
* Put your private key(keys) into KEYS field. Eg: KEYS=000000000,011111111,0222222222
* If you want to collect all tokens from different accounts into one single account. Put your receipient address into TO field. Eg: TO=0x9999999
* There is requests limit on the default API I provided in the .env. So it's better to get yourself a own API from https://www.alchemy.com/ or https://infura.io/ (Goerli Network)

## Register the address and start play the game
* `node register.js`

### Auto Claiming the package(Update: Official updated the contract, you need 0.2 ETH to claim each time)
* `node claim.js` 


### Collect tokens from different account into one account
* `node collectAll.js`

If you find this script is useful to you, donation will be appreciated: **0x434DCffCF7dABd48B284860C27ebd184C91341F5**

---
## 设置
* git clone https://github.com/ericet/claystack.git
* cd claystack
* npm install
* 文件改名
  * mv .env.example .env
* 把私钥放在.env 文件里面的KEYS后面。比如：KEYS=000000000,011111111,0222222222
* 如果你想把其他钱包里面的手镯归集到一个账号，TO后面填入要归集到的钱包地址。比如TO=0x9999999
* .env文件里面配置的API有请求限制，所以最好申请一个自己的API。你可以通过https://www.alchemy.com/ 或者 https://infura.io/ 申请API（Goerli网络)

## 注册钱包，开始游戏
`node register.js`

## 运行自动领取程序(更新：官方修改了合约，现在领取每次需要0.2 ETH)
node claim.js

## 运行归集程序
node collectAll.js

如果你觉得脚本帮助到你，可以捐献一点心意。钱包地址：**0x434DCffCF7dABd48B284860C27ebd184C91341F5**, 各链通用. 谢谢！
