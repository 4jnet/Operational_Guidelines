How to purchase 4JNET Token using the contact address.
====

 
#### 1.Open Pancakerouter smart contract for a in bscscan.com : 0x10ED43C718714eb63d5aA57B78B54704E256024E
Alternatively, click the link below or enter the link in the web browser as follows.

  https://bscscan.com/address/0x10ED43C718714eb63d5aA57B78B54704E256024E#writeContract
 

#### 2.Access to personal wallet (e.g., meta mask).Click the “Connect to Web3” and Connecting wallets.

  ![Image text](https://raw.githubusercontent.com/4jnet/Operational_Guidelines/main/images/ScreenShot1.jpg)

 
#### 3.  Use number 11 in the list below.11. "swapExactETHForTokensSupportingFeeOnTransferTokens" And Exchange 4JNET with BNB.
The parameters of the function are as follows.

(1) Parameters of the same name as the function are used to exchange the amount of BNB.
    Amount that the user wants to spend (minority 18 is basically omitted). 
For example. You can enter 0.01 (the amount must be less than the BNB balance of the account. Some gas fee is required)
Since the maximum limit of 4JNET transfers is 10 trillion and the impact of fees is added, the first 4JNET after the transaction is opened can be exchanged for up to about 1BNB.
In the future, as the price of 4JNET increases, more BNBs can be used for exchange.

(2) The user can accommodate the minimum output of 4JNET. If you don't get enough 4JNET, the transaction will fail due to changes to Slippage. It is recommended that you enter 0 to succeed.

(3) Exchange path, WBNB -> 4JNET (BscScan or browser may require addresses in the list to be grouped in double quotes.)
[0xbb4cdb9cbd36b01bd1cbaebf2de08d9173bc095c,0xbfb1a68962fb4ed040fd3a0a71dc2c2015bcc667]

(4) The 4JNET receiving address is the Bsc address of the user's wallet.

(5) You must enter a Unix timestamp greater than the current time for the deadline. (Example. Input 1703310977)
![Image text](https://raw.githubusercontent.com/4jnet/Operational_Guidelines/main/images/ScreenShot2.jpg)

