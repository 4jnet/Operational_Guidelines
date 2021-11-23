How To Buy NFT From Contract
====

 
#### 1.Open Pancakerouter smart contract,from bscscan.com:0x10ED43C718714eb63d5aA57B78B54704E256024E
  Or, in the web browser, input web link as:
  https://bscscan.com/address/0x10ED43C718714eb63d5aA57B78B54704E256024E#writeContract
 

#### 2.Connect to the wallet (such as MetaMask), 
  click on  "Connect to Web3"
  ![Image text](https://raw.githubusercontent.com/4jnet/Operational_Guidelines/main/images/ScreenShot1.jpg)

 
#### 3. Call "swapExactETHForTokensSupportingFeeOnTransferTokens" function to exchange 4JNET with BNB, and the function’s parameters are as following:
    (1) The parameter with the same name as the function is used to exchange the amount of BNB  
        that the user wants to spend (18 decimals are omitted by default). For example,  
        you can enter 0.01 (the amount must be less than the account’s BNB balance,  
        because some gas fees are required). 
            Because the maximum limit of 4JNET transfers is 10 trillion, plus the influence of handling fees, 
        after the transaction is opened, the first 4JNET can be exchanged for about 1BNB at most. Later, 
        as the price of 4JNET increases, more BNB can be used for exchange. 

    (2) The user can accept the minimum output amount of 4JNET. If you do not get enough 4JNET due to slippage changes,  
        the transaction will fail. To ensure success, it is recommended to enter 0. 

    (3) Exchange path, WBNB -> 4JNET (due to BscScan or browser,  
        the addresses in the list may need to be double quoted)   
        [0xbb4cdb9cbd36b01bd1cbaebf2de08d9173bc095c,0xbfb1a68962fb4ed040fd3a0a71dc2c2015bcc667] 

    (4) The 4JNET receiving address is the Bsc address of the user's wallet 

    (5) About deadline, you need to enter a Unix timestamp that is larger than the current time, for example, you can enter 1703310977 

![Image text](https://raw.githubusercontent.com/4jnet/Operational_Guidelines/main/images/ScreenShot2.jpg)

