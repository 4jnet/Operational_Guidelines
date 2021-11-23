계약에서 NFT를 구매하는 방법
====

 
#### 1. bscscan.com에서 Pancakerouter 스마트 계약 열기:0x10ED43C718714eb63d5aA57B78B54704E256024E
  또는 웹 브라우저에서 웹 링크를 다음과 같이 입력합니다.
  https://bscscan.com/address/0x10ED43C718714eb63d5aA57B78B54704E256024E#writeContract
 

#### 2.지갑(메타마스크 등)에 접속하고,
  "Web3에 연결"을 클릭하십시오.
  ![Image text](https://raw.githubusercontent.com/4jnet/Operational_Guidelines/main/images/ScreenShot1.jpg)

 
#### 3. "swapExactETHForTokensSupportingFeeOnTransferTokens" 함수를 호출하여 BNB와 4JNET을 교환하며, 함수의 매개변수는 다음과 같습니다.
    (1) 함수와 동일한 이름의 매개변수는 BNB의 양을 교환하는 데 사용됩니다.
        사용자가 지출하고자 하는 금액(소수점 18은 기본적으로 생략됨). 예를 들어,
        0.01을 입력할 수 있습니다(금액은 계정의 BNB 잔액보다 작아야 합니다.
        일부 가스 요금이 필요하기 때문입니다).
            4JNET 이체의 최대 한도는 10조이며 수수료의 영향을 더하기 때문에,
        트랜잭션이 열린 후 첫 번째 4JNET은 최대 약 1BNB로 교환될 수 있습니다. 나중,
        4JNET의 가격이 올라감에 따라 더 많은 BNB를 교환에 사용할 수 있습니다.

    (2) 사용자는 4JNET의 최소 출력량을 수용할 수 있습니다. 슬리피지 변화로 4JNET을 충분히 얻지 못한다면,
        거래가 실패합니다. 성공하려면 0을 입력하는 것이 좋습니다.

    (3) 교환 경로, WBNB -> 4JNET(BscScan 또는 브라우저로 인해,
        목록의 주소는 큰따옴표로 묶어야 할 수 있습니다.)
        [0xbb4cdb9cbd36b01bd1cbaebf2de08d9173bc095c,0xbfb1a68962fb4ed040fd3a0a71dc2c2015bcc667]

    (4) 4JNET 수신 주소는 사용자 지갑의 Bsc 주소입니다.

    (5) 마감 시한에 대해 현재 시간보다 큰 Unix 타임스탬프를 입력해야 합니다. 예를 들어 1703310977을 입력할 수 있습니다.

![Image text](https://raw.githubusercontent.com/4jnet/Operational_Guidelines/main/images/ScreenShot2.jpg)