## Haibin Zhang

<div class="row">
  <div class="col-md-4">
    <img src="img/haibin.png" style="width:15%">
  </div>
  <div class="col-md-4">
    Professor<br>
    <a href="https://english.bit.edu.cn/">Beijing Institute of Technology</a> <br>
    Email: bchainzhang at aliyun.com<br>
    Or: ucdhbzhang at gmail.com <br>
  </div>
</div>

Please contact me via the above two emails instead my Bit.edu email (for which I sometimes fail to receive emails properly). 



## Short Bio



I am a professor in the prestigious <a href="https://arims.bit.edu.cn/">Advanced Research Institute of Multidisciplinary Sciences</a> at Beijing Institute of Technology, China. I am also a PhD advisor in both School of Computer Science and Technology and School of Cyberspace Science and Technology. Moreover, I am a Teli Youth Fellow. 

I am interested in the intersection of distributed systems, applied cryptography, and security. 

Previously, I worked as a Chief Research Scientist at Shandong Institute of Blockchain (China), an Assistant Professor in the Department of Computer Science and Electrical Engineering at University of Maryland, Baltimore County (USA), and a postdoctoral researcher for two NSF frontier projects on cloud security: the MACS project at UConn (with Prof. Marten van Dijk) and the Project Silver at UNC Chapel Hill (with Prof. Michael K. Reiter). I received his Ph.D. from the University of California, Davis (with Prof. Matthew K. Franklin). 

I received the best paper candidate award at the 33rd IEEE International Symposium on Reliable Distributed Systems and proved the security of a NIST standard on ciphertext 
stealing. I am one of the main inventors of Norton Zone, Symantec’s scalable cloud storage, and BChain, a highly efficient BFT protocol fully implemented within Hyperledger blockchain framework and featured in more 20 media reports, including the Hyperledger whitepaper. I have received Maryland Innovation Award and research funding from NSF China, the Ministry of Science and Technology China, US NSF, US DoE, US DHS, Norway research council, etc.  




## Some BFT/permissioned blockchain systems built
ByzID (SRDS 2014, Best Paper Candidate, BFT using small trusted components)<br>

BChain (OPODIS 2014, chain-based high-throughput BFT, used in Hyperledger Iroha, featured in <a href="https://www.hyperledger.org/wp-content/uploads/2017/08/Hyperledger_Arch_WG_Paper_1_Consensus.pdf">Hyperledger white paper</a>. In fact, this is the only BFT protocol that does not rely on PBFT in the Hyperledger framework.)

CBFT (SRDS 2016, BFT with confidentiality; if you want to achieve private smart contracts without using TEEs, you may be interested in the paper)

CP-BFT (DSN 2017, BFT with causal order without using threshold cryptography)

BEAT (CCS 2018, asynchronous BFT made practical; a family of five state-of-the-art asychronous BFT protocols; open-source implementation [<a href="https://github.com/fififish/beat.git">Code</a>] See review from  <a href="https://blog.acolyer.org/2018/11/26/beat-asynchronous-bft-made-practical/">Morning Paper</a>)

EPIC (DSN 2020, asynchronous BFT with adaptive security. Prior asynchronous BFT protocols defend against static adversary, while EPIC tolerates adaptive adversary. Code to be released soon)

<a href="https://eprint.iacr.org/2022/020">PACE (CCS 2022)</a> and <a href="https://eprint.iacr.org/2022/021">WaterBear</a> are two new asynchronous BFT protocols

Recently, I am interested in building highly efficient partially synchronous BFT protocols, e.g., our DSN 2022 paper---Marlin, our Oakland 2022 Paper---Dyno, and Dashing and Star. 

I am also recently interested in designing and building systemss such as ACSS, AVSS, ADKG, and APSS, systems in synchronous settings, and MPC. 


## Openings!
I have many openings for PhDs, masters, and postdocs. 

Students/PhD students with computer science, cryptography, or security background are encouraged to send me an email!

We also welcome researchers and assistant professors to join our group and work together with us. 






## Preprints

- Haibin Zhang, Sisi Duan, Chao Liu, Boxin Zhao, Xuanji Meng, Shengli Liu, Yong Yu, Fangguo Zhang, Liehuang Zhu. 
Practical Asynchronous Distributed Key Generation: Improved Efficiency, Weaker Assumption, and Standard Model. [<a href="https://eprint.iacr.org/2022/1678">eprint</a>]

- You Zhou, Zongyang Zhang, Haibin Zhang, Sisi Duan, Bin Hu, Licheng Wang, Jianwei Liu. 
Dory: Asynchronous BFT with Reduced Communication and Improved Efficiency. 
[<a href="https://eprint.iacr.org/2022/1709">eprint</a>]

- Xiao Sui, Sisi Duan, and Haibin Zhang. BG: A Modular Treatment of Byzantine Consensus. [<a href="files/bg.pdf">PDF</a>] [<a href="https://eprint.iacr.org/2022/1433">eprint</a>] This is our new paper trying to provide a "unified" theory for BFT replication. 


- Sisi Duan, Haibin Zhang, Xiao Sui, Baohan Huang, Changchun Mu, Gang Di, Xiaoyun Wang. Dashing and Star: Byzantine Fault Tolerance Using Weak Certificates. 
[<a href="https://eprint.iacr.org/2022/625">eprint</a>]


- Haibin Zhang, Sisi Duan, Boxin Zhao, and Liehuang Zhu. WaterBear: Practical Asynchronous BFT Matching Security Guarantees of Partially Synchronous BFT. [<a href="https://eprint.iacr.org/2022/021">eprint</a>]


## Publication

- Nicolas Alhaddad, Sourav Das, Sisi Duan, Ling Ren, Mayank Varia, Zhuolun Xiang  and Haibin Zhang. 
Balanced Byzantine Reliable Broadcast with Near-Optimal Communication and Improved Computation. 
ACM Symposium on Principles of Distributed Computing (PODC), 2022. [<a href="files/podcbrb.pdf">PDF</a>][<a href="https://eprint.iacr.org/2022/776">ePrint</a>]
- Nicolas Alhaddad, Sourav Das, Sisi Duan, Ling Ren, Mayank Varia, Zhuolun Xiang  and Haibin Zhang. 
Brief Announcement: Asynchronous Verifiable Information Dispersal with Near-Optimal Communication. 
ACM Symposium on Principles of Distributed Computing (PODC), 2022. [<a href="https://eprint.iacr.org/2022/775">PDF</a>]
- Haibin Zhang and Sisi Duan. PACE: Fully Parallelizable BFT from Reproposable Byzantine Agreement. ACM CCS 2022. [<a href="https://eprint.iacr.org/2022/020">PDF</a>]
- Xiao Sui, Sisi Duan, and Haibin Zhang. Marlin: Two-Phase BFT with Linearity. DSN 2022. [<a href="files/marlin.pdf">PDF</a>]
- Sisi Duan and Haibin Zhang. Foundations of Dynamic BFT. IEEE Symposium on Security and Privacy (Oakland) 2022. [<a href="https://www.computer.org/csdl/proceedings-article/sp/2022/131600b546/1CIO7StCoZW">DOI</a>] [<a href="https://eprint.iacr.org/2022/597">PDF</a>]
-  Haibin Zhang, Chao Liu, and Sisi Duan. How to Achieve Adaptive Security for Asynchronous BFT? Journal of Parallel and Distributed Computing (JPDC), 2022. 
- Sisi Duan and Haibin Zhang. Recent Progress on BFT in the era of Blockchains. National Science Review (NSR). (This is an invited, peer-reviewed perspective which is asked to describe our own work on BFT. The maximum number of papers that the perspective can cite is 10. So the perspective can only include a rather limited number of papers and many papers end up with no citations (sorry!). If you are interested in a comprehensive survey, say our paper ACM CUSR below.)
- Xin Wang, Sisi Duan, James R. Clavin, and Haibin Zhang. BFT in Blockchains: From Protocols to Use Cases. ACM Computing Surveys, 2022. [<a href="files/bft-csur22.pdf">PDF</a>][<a href="https://dl.acm.org/doi/abs/10.1145/3503042">DOI</a>]
- Guohou Shan, Boxin Zhao, James R. Clavin, Haibin Zhang, and Sisi Duan. Poligraph: Intrusion-Tolerant and Distributed Fake News Detection System. IEEE Transactions on Information Forensics and Security 17: 28-41, 2022. [<a href="files/Poligraph_TIFS21">PDF</a>][<a href="https://ieeexplore.ieee.org/document/9627681">DOI</a>]
- Nicolas Alhaddad, Mayank Varia, and Haibin Zhang. High-threshold AVSS with optimal communication complexity. International Conference on Financial Cryptography and Data Security. Springer, Berlin, Heidelberg, 2021. [<a href="files/haven.pdf">PDF</a>]
- Chao Liu, Sisi Duan, and Haibin Zhang. EPIC: Efficient Asynchronous BFT with Adaptive Security. DSN 2020. [<a href="files/epic-dsn20.pdf">PDF</a>][<a href="https://ieeexplore.ieee.org/abstract/document/9153421">DOI</a>]
- Sisi Duan, Chao Liu, Xin Wang, Yusen Wu, Shuai Xu, Yelena Yesha, Haibin Zhang. Intrusion-Tolerant and Confidentiality-Preserving Publish/Subscribe Messaging. SRDS 2020: 319-328. [<a href="files/chios-srds20.pdf">PDF</a>][<a href="https://ieeexplore.ieee.org/document/9252069">DOI</a>]
- James R. Clavin, Sisi Duan, Haibin Zhang, Vandana P. Janeja, Karuna P. Joshi, Yelena Yesha, Lucy C. Erickson, and Justin D. Li. Blockchains for Government: Use Cases and Challenges. ACM Digital Government: Resesarch and Practice 1(3): 22:1-22:21, 2020. [<a href="files/BlockchainSurvey-DGOV20.pdf">PDF</a>][<a href="https://dl.acm.org/doi/10.1145/3427097">DOI</a>]
- Kyle Hogan, Hoda Maleki, Reza Rahaeimehr, Ran Canetti, Marten van Dijk, Jason Hennessey, Mayank Varia, Haibin Zhang. On the Universally Composable Security of OpenStack. IEEE SecDev 2019.  [<a href="https://eprint.iacr.org/2018/602">Full version (125 pages)</a>]
-  Alan Sherman, Farid Javani, Haibin Zhang, and Enis Golaszewski. On the Origins and Variations of Blockchain Technologies. 
  IEEE Security & Privacy, 2019. [<a href="https://ieeexplore.ieee.org/document/8674176">DOI</a>] 
- Sisi Duan, Michael K. Reiter, and Haibin Zhang. BEAT: Asynchronous BFT Made Practical. ACM CCS 2018. [<a href="files/beat.pdf">PDF</a>][<a href="https://dl.acm.org/citation.cfm?id=3243812">DOI</a>][<a href="https://github.com/fififish/beat.git">Code</a>]
- Siddhant Goenka, Sisi Duan, and Haibin Zhang.  A Formal Treatment of Efficient Byzantine Routing Against Fully Byzantine Adversary. NCA 2018. [<a href="files/routing-nca2018.pdf">PDF</a>][<a href="https://ieeexplore.ieee.org/abstract/document/8548163">DOI</a>]
- Sisi Duan, Michael K. Reiter, and Haibin Zhang. Secure Causal Atomic Broadcast, Revisited. DSN 2017: 61-72. [<a href="files/dsn17-cpbft.pdf">PDF</a>][<a href="http://ieeexplore.ieee.org/document/8023111/?reload=true">DOI</a>]
- Sherman S.M. Chow, Haibin Zhang, and Tao Zhang. Real Hidden Identity-Based Signatures. 
  21st International Conference on Financial Cryptography and Data Security 2017 (FC 2017). [<a href="files/hidden.pdf">PDF</a>]
- Sisi Duan, Lucas Nicely, and Haibin Zhang. Byzantine Reliable Broadcast in Sparse Networks. NCA 2016: 175-182. [<a href="files/nca16-byz.pdf">PDF</a>][<a href="http://ieeexplore.ieee.org/document/7778614/">DOI</a>]
-  Walter Bogorad, Scott Schneider, and Haibin Zhang. Norton Zone: Symantec's Secure Cloud Storage System. 
 IEEE 35th Symposium on Reliable Distributed Systems (SRDS 2016), 2016. [<a href="files/zone.pdf">PDF</a>]
- Sisi Duan and Haibin Zhang. Practical State Machine Replication with Confidentiality. SRDS 2016: 187-196. [<a href="files/srds16.pdf">PDF</a>]
- Mingqiang Wang, Tao Zhan, and Haibin Zhang. Bit Security of the CDH Problems over Finite Fields.
  Selected Area in Cryptography 2015, pages 441-461, 2015. [<a href="files/cdh.pdf">PDF</a>]
- Sisi Duan, Hein Meling, Sean Peisert, and Haibin Zhang. BChain: Byzantine Replication with High Throughput and Embedded Reconfiguration. OPODIS 2014: 91-106. [<a href="files/OPODIS_final_bchain.pdf">PDF</a>][<a href="https://link.springer.com/chapter/10.1007/978-3-319-14472-6_7">DOI</a>][<a href="https://cs.lbl.gov/news-media/news/2018/berkeley-lab-researchers-contribute-to-making-blockchains-even-more-robust/">Press</a>]
- Sisi Duan, Karl Levitt, Hein Meling, Sean Peisert, and Haibin Zhang. ByzID: Byzantine Fault Tolerance from Intrusion Detection.  SRDS 2014: 253-264. [<a href="files/byzid_SRDS_final.pdf">PDF</a>][<a href="http://ieeexplore.ieee.org/document/6983400/?arnumber=6983400">DOI</a>]  <font color="#26A0F4  "> Best Paper Candidate Award. </font>
- Tiancheng Chang, Sisi Duan, Hein Meling, Sean Peisert, and Haibin Zhang. P2S: A Fault-Tolerant Publish/Subscribe Infrastructure. DEBS 2014: 189-197. [<a href="files/p2s-2014.pdf">PDF</a>][<a href="http://dl.acm.org/citation.cfm?doid=2611286.2611305">DOI</a>]
- Sherman Chow, Matthew Franklin, and Haibin Zhang. Practical Dual-Receiver Encryption: Soundness, Complete Non-Malleability, and Applications.
  CT-RSA 2014, LNCS 8366, pages 85–105, 2014. [<a href="files/dual.pdf">PDF</a>] Also available [<a href=" https://eprint.iacr.org/2013/858">ePrint archive</a>] 
-  Matthew Franklin and Haibin Zhang. Unique Ring Signatures: A Practical Construction.
  Financial Cryptography and Data Security 2013, LNCS 7859, pages 162-170, 2013. [<a href="files/romring.pdf">PDF</a>] 
-  Matthew Franklin and Haibin Zhang. A Framework for Unique Ring Signatures. [<a href="files/ring.pdf">PDF</a>] Also available [<a href="https://eprint.iacr.org/2012/577">ePrint archive</a>]
- Phillip Rogaway, Mark Wooding, and Haibin Zhang. The Security of Ciphertext Stealing. 
  FSE 2012, LNCS 7549, pages 180-195, 2012. [<a href="files/steal.pdf">PDF</a>]
- Matthew Franklin and Haibin Zhang. Unique Group Signatures. 
  ESORICS 2012, LNCS 7459, pages 643-660, 2012. [<a href="files/group.pdf">PDF</a>] [<a href="files/group_full.pdf">Full Paper</a>] Also available [<a href="https://eprint.iacr.org/2012/204">ePrint archive</a>]
- Haibin Zhang. Length-Doubling Ciphers and Tweakable Ciphers. 
  ACNS 2012, LNCS 7341, pages 100-116, 2012. [<a href="files/doubling.pdf">PDF</a>]
- Phillip Rogaway and Haibin Zhang. Online Ciphers from Tweakable Blockciphers. CT-RSA 2011, LNCS 6558, pages 237-249, 2011. [<a href="files/online.pdf">PDF</a>]
  





### Some Other Research and Industry Impacts

- I am one of the three main inventors of <a href="https://en.wikipedia.org/wiki/Norton_Zone">Norton Zone</a>, Symantec's Commercial Cloud Storage Platform. 

- Phil and I proved the security of ciphertext stealing for a NIST addendum. M. Dworkin. Recommendation for block cipher modes of operation: three variants of ciphertext stealing for CBC mode. Addendum to NIST Special Publication 800–38A. October 2010.

- <a href="https://github.com/monero-project/urs">Unique ring signatures and Monero</a>.

- A clean definition of online cipher was introduced in our RSA 2011 paper and widely used in subsequent online encryption and online authenticated encryption schemes (including
the CAESAR competition candidates). 

- One of the state of the art ABA protocols so far: CCS 2022 (Pillar). Pillar has on average 12 steps to terminate and assumes common coins and authenticated channels only. 

- The most communication-efficient RBC so far: PODC 2022. 

- The most communication-efficient AVID so far: PODC 2022 (BA). 


## Recent conferences in which I am invovled (please consider submitting your work!): 

PETS 2024 Program Committee / PoPETs 2024 Editorial Board

<a href="https://www.ieee-security.org/TC/EuroSP2023/">IEEE EuroS&P 2023</a> 

<a href="https://fc23.ifca.ai/">Financial Cryptography and Data Security (FC) 2023</a> 

<a href="https://sites.uclouvain.be/OPODIS2022/">OPODIS 2022</a> (Please submit your papers to the prestigious conference focusing on distributed computing! Both theory and implementation aspects in all areas of distributed computing are welcome.)

<a href="https://www.ndss-symposium.org/ndss2023-call-for-papers/">NDSS 2023</a> 

<a href="https://ccsw.io/">ACM CCSW 2022</a> 

<a href="https://cis.temple.edu/~yanwang/ieee-mass-2022/Home.html">IEEE MASS 2022</a> 

<a href="https://icdcs2022.icdcs.org/">ICDCS 2022</a>    

I am happy to serve as PC members and spend time in helping review papers. 
More importantly, I really want to advertise and promote international conferences in China, 
and help exchange academic ideas and advance knowledge. (The world is somewhat more disconneted due to COVID. No?:)) 


I am certainly biased, but I am particularly interested and committed in promoting less established but high-quality conferences in China. 
Doing so may help these conferences more vigorous (e.g., by receiving 
more high-quality submissions), help researchers in China have more balanced research 
(now somewhat impacted by the CCF short list---some of those conferences not in the list, unfortunately, are ones with areas that are under-developed), 
and help researchers who published papers in these conferences get the recognization that they deserve.  






