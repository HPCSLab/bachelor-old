



# FPGAチーム

## FPGA Team
<img src="./H29_fpga_group_photo.jpg" width=600></img>

## 研究内容

### 山口 佳樹 准教授

AI (Artificial Intelligence)、5G/IoT、BigData は、Webページやニュースなどでも、一般に利用される単語となりつつあります。これらを支える情報システムとして、膨大なデータを対象とした演算加速装置、5G/IoTを支える高速通信装置、集約されたデータを高速に取り扱うストレージ装置などがあります。では、これら全ての分野で、FPGAが注目を集めるデバイスとなっていることは知っているでしょうか？
演算加速という面では、Microsoft、IBM、Amazon、百度などがデータセンタ向けに FPGA を利用し始めています。具体的には、サーチエンジン、AI 学習、医療画像処理、遺伝子検索、流体シミュレーションなどに利用されつつあります。ネットワークという面では、GPUで有名な Nvidia が Mellanox (FPGAを利用したネットワークスイッチを製造・販売した企業）を2019年3月に買収、これに対抗して Intel が FPGA 部門とネットワーク部門の統合を2019年6月に発表しました。ストレージ装置という面では、DELL EMCや富士通などの大手メーカが FPGA の採用を決めています。このことから、FPGA は既存のITシステムを変え、ITサービスを変え、社会を変える、という人もいます。
FPGAチームは、約20年蓄積されたFPGA研究/実装/開発の経験に基づき、学術的研究に加え産業界もにらんだ実問題を対象とするハードウェア加速機構について真剣に議論します。具体的には、理化学研究所、産業技術総合研究所、高エネルギー加速器研究機構、物質材料研究機構などと共同研究を行っています。また、インターンシップや留学などの相談も可能です。興味を持った人は、研究室紹介で会いましょう。

<img src="./fpga-fig.png" width=850></img>

### FPGA (Field Programmable Gate Array) チームについて

　FPGAは、自動運転、医療/福祉、ロボット、ビッグデータ、安全・安心、航空宇宙等の分野で数多くの企業が利活用しています。そしてそこでは、画像/音声検出、認識、追尾、圧縮処理、(ビッグデータ等)高速処理、大規模科学技術計算（宇宙・海洋・風洞）、暗号処理などで更なる高性能計算が求められています。また、FPGAを本当の意味で活用するために、FPGAに加え、GPUやCPUの特徴についても研究室では学んでいきます。
　日本のFPGAに関する研究および技術は高く評価され、FPGA分野の一流の国際会議を日本に誘致できるほどになっています。興味を持った人はぜひ研究室紹介に参加しましょう。



<!--
他チームとの協力
----------------
-->


## メンバー

| <span style="display: inline-block; width: 6em;">名前</span> | <span style="display: inline-block; width: 3em;">職階</span> | 研究内容・メッセージ |
|:-----|:---|:-------------------------|
|[山口 佳樹](http://www.cs.tsukuba.ac.jp/~yoshiki/)|准教授|<font color="green">リコンフィギャラブルデバイス（FPGA、DAPDNA、DRP、など）とそれを用いたシステム。</font><br>FPGAは可能性を秘めたデバイスです。そしてチームでは、Intel CPU を初め、GPGPU、ARM、GRAPE、SuperH、Cell/B.E. などのアーキテクチャについても研究を行ってきました。つまり、FPGAをただ使うのではなく、利用のメリットやデメリットをきちんと考慮した上でシステム構築できるのが他と大きく違うところです。また、基礎をきちんと押さえているため応用の幅は広く、創薬（生化学反応、遺伝子検索）、社会道徳創発、熱流体などのシミュレーションから画像処理、音声処理、機械制御、VR、AI加速機構などの実応用に近いものまで研究対象となります。興味を持った人は研究室紹介で僕と握手っ！！|
|Firmansyah IMAN|D|Systems with heterogeneous architectures, such as field programmable gate arrays (FPGAs) and graphics processing units (GPUs), are expected to boost the throughput in high-performance computing applications. However, the user may struggle to write sophisticated programs that are performed effectively on complicated heterogeneous systems. High-level synthesis (HLS) is a solution that can reduce the development time. This study focuses on the implementation of OpenCL programming as a type of HLS design on FPGA boards. The Himeno benchmark, which is a suitable benchmark for the measurement of memory-intensive applications, is chosen as a verification program. We found that the OpenCL-based implementation achieves reasonable performance on FPGAs by demonstrating the implementation of temporal blocking combined with shift register implementation simultaneously. For Stratix V DE5-Net FPGA, our current implementation achieves 10.62 GFLOPS, or 75% of the theoretical performance. Meanwhile, for Arria 10 A10PL4 FPGA, the peak performance reaches 13.95 GFLOPS, or 76% of the theoretical performance.|
|杜昌道|D|Research interests mainly focused on High-performance Computing on FPGA-based heterogeneous platforms, especially by using the High-level Synthesis methods. Currently, try to design a reusable stream program pattern for realizing scientific applications as stencils, convolution, etc. Also interested in the portability for implementing applications on different FPGA platform.|
|Riadh Ben Abdelhamid |D|2017年4月に来日しました。|
|程嘉豪|M2||
|杜欣|M2||
|樊若冲|M2||
|原澤輝|M2||
|胡子鍵|M2|With the development of self-driving, there is an increasing need of driving asistance system. I would like to build an object detection system especially applied in darkness condition, which using Tof(Time of fight) camera with an embeded FPGA zynq-7000. An improved algorithm based on HOG is introduced in this researh, which could do human detection based on depth data captured by Tof camera. FPGA itself has the advantage of processing large-scale computing caused by HOG algorithm.I hope that this research would be helpful in the coming future.|
|譚煜希|M2||
|梅津直弥|M2||
|牛若光太|M2||
|呉思卿|M2||
|古川和輝|M1||
|伊藤瑞基|M1||
|小林駿也|M1||
|新開裕|M1||
|庭瀬稜平|M1||
|中井榛希|M1||
|程詩茹|M1||
|康博文|M1||
|張晨光|M1||
|張曦|M1||
|宋雨純|M1||
|徐棟宇|M1||
|高琦翔|M1||
|小堀泰雅|B4||
|中川諒|B4||
|謝靖函|研究生||
|顾超渊|研究生||
|陶毅寧|研究生||
|郭氷潔|研究生||
|馬文軒|研究生|||

## 研究室紹介

| <span style="display: inline-block; width: 6em;">日付</span> | <span style="display: inline-block; width: 3em;">時間</span> | 場所 |
|:-----|:---|:-------------------------|
|10/8(木)|15:15~16:30|SB1112 (MS Teamsでも実施)|
|10/15(木)|15:15~16:30|SB1112 (MS Teamsでも実施)|
|10/21(水)|15:15~16:30|SB1112 (MS Teamsでも実施)||

<!--
近年の研究成果について
----------------------

一例として，今年 (2016年) に情報処理学会HPC研究会に投稿した研究会原稿 (日本語) を紹介します．
筑波大学は情報処理学会と機関契約をしていますので，筑波大学構内のネットワークからは自由にダウンロード可能です．
-->

## 近年の活動
### 受賞
- 2019年09月　　ESS2019で、長岡が、研究奨励賞を受賞しました
- 2019年03月　　第81回情報処理学会全国大会で、紀野国が、学生奨励賞を受賞しました
- 2019年03月　　第81回情報処理学会全国大会で、敖が、学生奨励賞を受賞しました
- 2017年09月　　RECONF研究会で、中村が、優秀講演賞を受賞しました
- 2016年09月　　FIT2017で、中野が、FITヤングリサーチャー賞を受賞しました。
- 2016年09月　　FIT2017で、高山が、FIT2016奨励賞を受賞しました。
- 2016年09月　　FIT2017で、中野が、FIT2016奨励賞を受賞しました。

<!--
### 報道 ###

・07/28　　バレーボールシステムの研究が日経産業新聞様の先端技術面で紹介されました。

### 出版 ###
・04/22　　[FPGAの原理と構成](http://shop.ohmsha.co.jp/shopdetail/000000004588/)が出版されました。山口先生が第7章の応用事例紹介を担当されました。      
　　　- "FPGAの原理と構成", 第7章 PLD/FPGAの応用事例, オーム社, p.209-245, 2016年4月．
-->
