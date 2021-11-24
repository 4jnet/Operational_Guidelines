契約から4JNET Tokenを購入する方法
====

 
#### 1.bscscan.comからPancakerouterスマートコントラクトを開きます：0x10ED43C718714eb63d5aA57B78B54704E256024E
  または、Webブラウザで、次のようにWebリンクを入力します。
  https://bscscan.com/address/0x10ED43C718714eb63d5aA57B78B54704E256024E#writeContract
 

#### 2.ウォレット（MetaMaskなど）に接続し、
  「Web3に接続」をクリックします
  ![Image text](https://raw.githubusercontent.com/4jnet/Operational_Guidelines/main/images/ScreenShot1.jpg)

 
#### 3.「swapExactETHForTokensSupportingFeeOnTransferTokens」関数を呼び出して4JNETをBNBと交換します。この関数のパラメーターは、次のとおりです。
    （1）関数と同じ名前のパラメーターを使用してBNBの量を交換します
        ユーザーが使いたいもの（デフォルトでは小数点以下18桁は省略されています）。例えば、
        0.01を入力できます（金額はアカウントのBNB残高より少なくなければなりません。
        ガス代が必要なため）。
            4JNET転送の上限は10兆に加えて、手数料の影響があるため、
        トランザクションが開始された後、最初の4JNETは最大で約1BNBと交換できます。後で、
        4JNETの価格が上がると、より多くのBNBを交換に使用できます。

    （2）ユーザーは4JNETの最小出力量を受け入れることができます。スリッページの変更により十分な4JNETが得られない場合は、
        トランザクションは失敗します。成功を確実にするために、0を入力することをお勧めします。

    （3）交換パス、WBNB-> 4JNET（BscScanまたはブラウザーによる、
        リスト内のアドレスは二重引用符で囲む必要がある場合があります）
        [0xbb4cdb9cbd36b01bd1cbaebf2de08d9173bc095c、0xbfb1a68962fb4ed040fd3a0a71dc2c2015bcc667]

    （4）4JNET受信アドレスは、ユーザーのウォレットのBscアドレスです。

    （5）期限については、現在の時刻よりも大きいUnixタイムスタンプを入力する必要があります。たとえば、1703310977と入力できます。

![Image text](https://raw.githubusercontent.com/4jnet/Operational_Guidelines/main/images/ScreenShot2.jpg)
