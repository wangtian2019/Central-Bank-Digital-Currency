# Central Bank Digital Currency
ID: Tina Wang 1701213108 

## Introduction
Central bank digital currency (CBDC) is the digital form of fiat money which is a currency established as money by government regulation or law. CDBC combines the characteristics of central bank currency and digital currency-centralization and distributed book-keeping. CBDC is only a hypothetical model till now.

![data overview](https://github.com/wangtian2019/Central-Bank-Digital-Currency/blob/master/%E5%9B%BE1.png)

CBDC was born because digital currency has some inherent defects, but it also has advantages that traditional central bank currency does not have.

## Birth defects of CBDC
Private digital currency develops rapidly in the post-financial crisis era under the background of global currency competitiveness overrun, but the inherent defects of private digital currency make it unable to become a real currency.

### 1.Instability of value
The market price of digital money is very unstable for it does not have country credit endorsement, so it cannot be used as store of value. Bitcoin prices have risen all the way since the beginning of 2017, reaching an all-time high of $19373.14 on December 16, 2017, and then began to fall, falling to $1348.02 at the lowest level, with a maximum decline of 16.72%, the biggest drop since January 2015. The price of ET coin has changed more dramatically, rising nearly 90 times in 2017. The sharp rise and fall of Bitcoin and the rapid rise of the Ethernet coin reflect the great volatility of the private digital money market.

### 2.Low transaction validation rate
The transaction validation rate of digital currency is very low, so it cannot be used as Medium of exchange. In Bitcoin system, broadcasting information transmission and hashing operations take a lot of computing power and time. As a result, the overall service processing capacity of Bitcoin system is limited. It is estimated that only seven services can be processed per second, while the average number of services processed by Visa is between 2000 and 7000.

### 3. Fixed and limited money supply
The money supply of digital currency is fixed and limited, so money policy cannot be implemented. In the Bitcoin system, the money supply increases with time, and the increased Bitcoins are acquired by the "excellent miners" who have the strongest computing power in an operation cycle. However, the total number of Bitcoins is about 21 million, and the growth mechanism is relatively stylized. The number of Bitcoins produced each time is relatively fixed and lack of controllability.

### 4. Difficult to effectively supervise
n some payment scenarios, private digital currency can replace legal currency for payment, but private digital currency is not controlled by the central bank. If the use of private digital money exceeds a certain limit, it will affect the implementation and transmission of the central bank's monetary policy. At the same time, the great volatility of the value of private digital currency makes it easy to cause market panic and risk events, and poses a threat to the stability of the financial system. In addition, private digital currency generally has the characteristics of anonymity, unregulated funds and transnational flows, which may encourage illegal traders to use private digital currency to cover up their real trading intentions, and enterprises and individuals to use private digital currency to achieve the purpose of tax evasion and tax evasion. However, in the field of private digital currency, the absence of regulation is serious, and it is difficult for relevant departments to effectively supervise private digital currency.

## Advantages of CBDC
The issuance of statutory digital currency by the central bank is based on the realistic demand of the innovation and development of the traditional banking system.

Firstly, the statutory digital currency makes the formulation and implementation of monetary policy more effective. Statutory digital currency can make full use of scientific and technological means such as block chain, big data and controllable cloud computing to provide more sufficient and accurate basis for monetary policy formulation. Meanwhile, the point-to-point payment and settlement characteristics of statutory digital currency will accelerate the currency circulation speed, thus creating high liquidity for financial market, making the term structure of interest rate more smooth and the transmission mechanism of monetary policy. More smoothly.

Second, statutory digital currency makes financial regulation more precise. At present, the small transactions of the public are mainly carried out through the third-party payment instruments. The third-party payment institutions have accumulated a considerable amount of large payment data, and the central bank has lost part of the control of currency circulation data. The legal digital currency can replace the electronic currency paid by the third party in function, and it has the support of national credit, which will return the control of the big data of currency circulation to the central bank. The big data of money circulation can provide the central bank with complete and true transaction records at different frequencies and levels, make the monitoring and management of the central bank's capital flow more effective, and provide the basis for the formulation and implementation of macro-prudential policies and micro-financial supervision measures.

Businesses and individuals will also benefit. Firstly, legal digital currency can reduce the circulation cost. If commercial banks no longer need to transport large amounts of money but can transfer money by electronic means, the loss cost and maintenance cost of the whole process will be greatly reduced. Second, statutory digital currency can improve the efficiency of fund settlement. Statutory digital currency uses block chain technology to construct point-to-point payment mode. The realization of payment and settlement process no longer requires third-party clearing institutions or payment centers. The payment and settlement activities of enterprises and individuals are more convenient, settlement costs are greatly reduced, and the efficiency of fund settlement and management is expected to be significantly improved.

## Case Study: CSCoin
RSCoin is the Bank of England's central bank digital currency program.
RSCoin introduces a degree of centralization into the two typically decentralized components of a blockchain-based ledger: the generation of the monetary supply and the constitution of the transaction ledger. 
In its simplest form, the RSCoin system assumes two structural entities:
1) the central bank, a centralized entity that ultimately has complete control over the generation of the monetary supply
2) a distributed set of mintettes that are responsible for the maintenance of the transaction ledger. 

### Running mechanism of RSCoin

![data overview](https://github.com/wangtian2019/Central-Bank-Digital-Currency/blob/master/%E5%9B%BE2.png)
The figure above shows the overall structure of RSCoin. 
Firstly, mintettes collect transactions from users and write them into blocks. These mintettes differ from traditional cryptocurrency miners: rather than performing some computationally difficult task, each mintette is simply authorized by the central bank to collect transactions. In RSCoin, this authorization is accomplished by a PKI-type functionality, meaning the central bank signs the public key of Each mintettes maintains a set of lower-level blocks, and communicates with other mintettes. At some point, the mintettes send these blocks to the central bank, which produces a higher-level block. It is these higher-level blocks that form a chain and that are visible to external users.

![data overview](https://github.com/wangtian2019/Central-Bank-Digital-Currency/blob/master/%E5%9B%BE3.png)
The figure above shows the proposed protocol for validating transactions: each mintette mi is an owner of address i. In (1), a user learns the owners of each of the addresses in its transaction. In (2), the user collects approval from a majority of the owners of the input addresses. In (3), the user sends the transaction and these approvals to the owners of the transaction identifier. In (4), some subset of these mintettes add the transaction to their blocks.

### Security features
*Most mintettes are honest;




