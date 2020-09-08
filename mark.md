

#                   <center>                  合约代码对比指南——避免恶意合约盗走您的本金



## 1.智能合约的代码安全性至关重要

部分挖矿合约存在恶意代码，能随时提走你的本金。千万不要贪图日化10%的收益，而被盗走所有本金，您一定要学会判断智能合约代码是否安全。



## 2. 如何判断合约的安全性？
### 第一步：找出已审计的合约代码，例如YFI、YFII等合约代码，此类已被各大知名机构审计，不存在任何后门。YFI矿池合约代码地址为：
https://etherscan.io/address/0x0001fb050fe7312791bf6475b96569d83f695c9f#code
 （下图中红框里所有代码即为合约源码）
![](_v_images/20200908184855362_2647.png)


### 第二步：找出您准备去挖矿的智能合约代码，对比其与YFI合约的不同之处。LFI矿池合约代码地址为： 
https://etherscan.io/address/0xe8a64280416c400d5390ac3d17eecb323cd39014#code 

     
### 第三步：打开https://www.diffchecker.com/ 将YFI与LFI代码分别粘贴到左右各框，点”Find difference”，即可看到颜色标记的不同之处。比较结果如下图所示，详见：https://www.diffchecker.com/hfsR5yta
 ![](_v_images/3.png)

### 最后，通过对比，若挖矿的合约代码只是修改了变量名称（例如YFI改成LFI）、修改代币ERC20地址、挖矿开始时间，那就是安全的。若发现合约代码增加了很多段函数，那就一定要小心。
### 下图LFI的代码安全，挖矿本金谁都无法挪用, LFI仅改动了代币名称和挖矿开始时间，确保头矿人人均有机会参与





#                   <center>                  Guide to Judge the Security of Smart Contracts



## 1.The security of smart contract is very important

Some mining contracts have malicious codes, which can withdraw your staking assets at any time. You need know how to judge whether the smart contract codes are secure for avoiding the loss of your crypto.。



## 2. How to judge the security of smart contracts？
### First step: Find audited contract codes, such as YFI, YFII token, which are audited by well-known institutions. The address of the YFI mining pool is：
https://etherscan.io/address/0x0001fb050fe7312791bf6475b96569d83f695c9f#code
 （The code in the red box is the source code of the YFI pool contract）
![](_v_images/20200908184855362_2647.png)


### Step two: Find out the smart contract code that you are going to mine and compare it with the YFI’s code.The code address of the LFI mining pool is： 
https://etherscan.io/address/0xe8a64280416c400d5390ac3d17eecb323cd39014#code 

     
### Step three: open https://www.diffchecker.com/, paste the YFI and LFI codes into the box respectively. Click on “Find Difference” and you will see the differences marked with color. You can refer to：https://www.diffchecker.com/hfsR5yta
 ![](_v_images/3.png)

### If only variable names, the address of token and the start time of mining are modified, then the codes are secure. If you find out that a lot of functions are added in the contract codes, then you must be careful.
### For instance, LFI only changes some variable names and start time of mining, so LFI mining pool is safe.
