アーキテクチャチーム
==================

研究内容
--------

アーキテクチャチームでは，GPUやメニーコアプロセッサ等の演算加速装置をより有効に大規模並列処理に活用する手法や，超高性能並列処理向けネットワーク，さらにこれらを活用する高性能並列コンパイラの研究をしています．
現在の主な研究テーマは以下の通りです．なお，朴及び小林両教員が共同で適宜指導を行いますが，研究室配属時点では主なテーマに応じてどちらかの教員を指導教員として選択して下さい．

+ FPGAを用いた演算オフローディングと高速通信の融合に関する研究
+ 大規模メニーコアシステムを用いた超並列アプリケーションの実装と最適化に関する研究（朴）
+ FPGAを用いた高速ソーティング回路に関する研究
+ GPUクラスタに向けた並列プログラミング言語に関する研究
+ 次世代スーパーコンピュータの性能予測シミュレータに関する研究

以下に，所属している学生達が行っている研究テーマについて紹介します．


### 高性能なFPGAアクセラレータとその開発方式に関する研究

    キーワード: FPGA, OpenCL, FPGAと高性能計算

近年，再構成可能ハードウェアとしてFPGAが注目され，多くの分野で使われるようになってきました．
高性能計算においてもその流れがあり，我々は現在利用されているGPUやCPUがどうしても解決できない問題について，FPGAを用いることで高性能化・高速化が行えないか検討しています．
FPGAにおいてもOpenCLプラットフォームがサポートされ，FPGAを用いたプログラミングが容易になりつつあります．

我々が提唱しているAiS (Accelerator in Switch) というコンセプトでは，再構成可能なFPGAを演算加速装置を部分的計算と高速通信の融合環境として捉え，次世代の効率的な並列処理を行う基盤技術開発を行っています．
これについてはFPGAチームとも連携を取りつつ，計算科学研究センターにおける次世代スーパーコンピュータの原型として開発を進めています．


### GPU等の演算加速装置を含む並列処理アーキテクチャ及びネットワークに関する研究と，これらのシステムを効率的に利用するための並列プログラミング言語及びコンパイラに関する研究

    キーワード: GPGPU, FPGA, 大規模並列システムとネットワーク

Graphics Processing Unit (GPU) は，演算加速装置として高く注目されており，NVIDIA社のCUDAやKhronos GroupのOpenCLなどが実行プラットフォームとしてあります．
中でも，特にNVIDIA社のCUDAは高性能計算において広く利用され，筑波大学にもGPUを用いた大規模クラスタとして[HA-PACS/TCA](https://www.ccs.tsukuba.ac.jp/research/research_promotion/project/ha-pacs)が稼働しています．
![](./hapacs_tca.png)
しかしながらGPUはその特性上，GPU単体で通信を行うことができず，CPUによる操作が必要となります．
そのため，我々はTightly Coupled Accelerators (TCA) というコンセプトの元，FPGAでGPU間直接通信機構PEACH2を開発し，性能評価を行っています．
また，ソフトウェア側のアプローチとして，GPUプログラミングを簡単化するためにGPU間セルフ通信機構を提案しています．
GPUはその特性上，CPUによる操作が必要なることは既に述べましたが，これはプログラミングが複雑化することと同義です．
そこで我々は並列プログラミングを簡単にするため，並列プログラミング言語に関する研究も行っています．
![](./peach2.png)


### 超並列アプリケーションの性能向上に関する研究

    キーワード: Xeon Phi, GPGPU, メニーコア, 大規模並列システムとアプリケーション

2016年12月，筑波大学と東京大学は2016年6月現在で日本最速のスーパーコンピュータ「京」の2.5倍の性能を持つ[大規模メニーコアシステム「Oakforest-PACS」](http://jcahpc.jp/)を導入しました．
2017年6月の時点で，[国内最高性能システムとして世界7位の性能を持っています](https://www.top500.org/lists/2017/06/)．
メニーコアシステムは，これまでアクセラレータとして利用されていたIntel Xeon Phiの最新アーキテクチャ「Knights Landing」が用いられ，日本のフラッグシップマシンとして注目されています．
しかしながら，メニーコアシステムはその特性上従来のアプリケーションを高い効率で実行することが難しく，プログラムの修正・改良が必須となっています．
我々は，筑波大学計算科学研究センターの実応用分野の研究者と共同研究を行いOakforest-PACSや次世代並列計算機に向けたアプリケーションの実装・最適化を行っています．
また，連携大学院の佐藤三久教授との共同研究の下，理化学研究所で進められている次世代超並列計算機（ポスト「京」）プロジェクトの一部としての共同研究も行い，ネットワークシミュレーション，独自開発の並列処理言語・コンパイラ等の研究を進めています


世界的な活動
----------------
朴教授は国際会議でプログラム委員長を務めるなど、世界的に活躍しています。
<iframe width="560" height="315" src="https://www.youtube.com/embed/BDPsa7AP7NA" frameborder="0" allowfullscreen></iframe>

他チームとの協力
----------------

並列プログラミング言語に関する研究は[PAチーム](pateam.md)との共同研究で，我々のPEACH2をPAチームで開発している並列言語XcalableMPの演算加速装置向け拡張XcalableACCに導入した実績もあります．
また，[FPGAチーム](fpgateam.md)とも協力しFPGAの基礎評価や並列アプリケーションの実装などを行っています．


メンバー
----------------

|名前|職階|研究内容・メッセージ|
|:---|:---|:-------------------------|
|[朴 泰祐](http://www.hpcs.cs.tsukuba.ac.jp/~taisuke/)|教授|<font color="green">アクセラレータ, ネットワーク</font><br>大規模科学技術計算（計算科学）は，最先端のサイエンスを支える重要な研究であり，我々は本学の[計算科学研究センター](http://www.ccs.tsukuba.ac.jp/)を始めとする国内外の研究者との共同研究によってこれを実施しています．GPU，FPGA等の計算リソースは今後の同分野の研究推進に重要な要素であり，これらを積極的に用いた大規模計算科学の実質的な成果を目指した研究を日夜進めています．ぜひみなさんの若い力を貸して下さい！|
|[小林 諒平](https://sites.google.com/site/ryokbya/)|助教|<font color="green">FPGA, アクセラレータ</font><br>FPGAを使って自分だけの高性能ハードウェアを作ってみたい，高性能ハードウェアを簡単に作れる素敵なツールを実装してみたい，FPGAだけじゃなく，CPU, GPUを含めたヘテロジニアスコンピューティングについて探求したいという人は間違いなく当研究室に向いているので，どうぞ見学においで下さい．当研究室は，世界の第一線で活躍されている先生方を多く抱え，かつ学外の一流の研究者とも連携することができ，研究をするにおいてこれ以上無いくらい理想的な環境が用意されています．是非一緒に世界を獲る研究を行っていきましょう！[(詳細)](kobayashi.pdf)|
|藤田 典久|研究員|<font color="green">GPU, FPGA, アクセラレータ</font>|
|廣川 祐太|D2|<font color="green">大規模メニーコアシステムを用いた超並列アプリケーションの実装と最適化</font><br />私が所属するアーキテクチャチームは，アクセラレータとネットワークについて主眼が置かれていますが，私のようにシミュレーションをしている実科学の方々と共同研究を行い，[シミュレーションコードの最適化・性能評価](http://salmon-tddft.jp/)も行っています．GPUやメニーコアなどの最新アーキテクチャでの最適化，大規模システム・スパコンでの性能について興味のある方もぜひ当チームを考えてみてください．|
|大畠 佑真|M2|<font color="green">FPGAの基礎評価および高性能計算への適用に関する調査研究</font><br>OpecCLを用いてFPGAへHPCアプリケーションを実装し、適用性を調査しています。比較的、新しい分野で、手探りで研究を行っている状態です。新しいことに挑戦したいという方は、是非研究室説明会に来てください。|
|西村 慧|M1|<font color="green">FPGA</font><br />アーキテクチャチームでは，GPUやFPGAといったアクセラレータからネットワークまで，高性能計算向けのアーキテクチャに関する研究に取り組むことができます．プログラムを効率よく実行するためには，ハードウェアの性能を最大限に引き出すことができるハードウェアとソフトウェアのインターフェースが必要となるため，ソフトウェアと高い親和性を持つアーキテクチャの研究は高性能計算に関する研究の中でも重要な位置を占めています．ハードウェアと密接に結びついたプログラミングに興味がある方，ハードウェアアーキテクチャの設計に興味がある方は，是非本研究室にお越しください．|
|阿部 昂之|B4|<font color="green">GPU，FPGA</font><br />高性能計算についての研究を行うための環境が整っている研究室です。HPCS研究室は複数のチームから構成されているため、いろいろな人と交流をすることもできます。|
|辻 大亮|B4||
|渡部 裕|B4|<font color="green">並列プログラミング言語，OpenCL，FPGA</font><br />|


近年の研究成果
----------------------

1. Implementation and Evaluation of NAS Parallel CG Benchmark on GPU Cluster with Proprietary Interconnect TCA
    - Kazuya Matsumoto, Norihisa Fujita, Toshihiro Hanawa, and Taisuke Boku.
    - Proc. of [VECPAR2016](http://vecpar.fe.up.pt/2016/), Porto, Jul. 2016.
    - <font color="green">上のVECPARのリンク先の写真で、朴先生はどこでしょう？見つかるかな？</font>
2. Electron Dynamics Simulation with Time-Dependent Density Functional Theory on Large Scale Symmetric Mode Xeon Phi Cluster 
    - Yuta Hirokawa, Taisuke Boku, Shunsuke Sato, and Kazuhiro Yabana.
    - Proc. of [PDSEC2016 (in IPDPS2016)](http://cse.stfx.ca/~pdsec16/), Chicago, 2016.
3. 電子動力学シミュレーションのステンシル計算に対するメニーコアプロセッサ向け最適化
    - 廣川 祐太，朴 泰祐，佐藤 駿丞，矢花 一浩
    - 情報処理学会論文誌コンピューティングシステム (ACS), Vol. 9, No. 4, pp. 1-14, 2016.
    - http://id.nii.ac.jp/1001/00175938/
4. 密結合並列演算加速機構TCAによるGPU対応GASNetの実装と評価
    - 佐藤 賢太，藤田 典久，塙 敏博，松本 和也，朴 泰祐，Khaled Ibrahim
    - 情報処理学会HPCS2016 <font color="red">（最優秀論文賞受賞）</font>.
    - http://id.nii.ac.jp/1001/00163660/
5. OpenCLを用いたFPGAによる宇宙輻射輸送シミュレーションの演算加速
    - 藤田 典久, 小林 諒平, 山口 佳樹, 大畠 佑真, 朴 泰祐, 他
    - 第161回IPSJ HPC研究会
    - http://id.nii.ac.jp/1001/00183479/
6. OpenCLとVerilog HDLの混合記述によるFPGA間Ethernet接続
    - 大畠 佑真, 小林 諒平, 藤田 典久, 山口 佳樹, 朴 泰祐 
    - 第160回IPSJ HPC研究会
    - http://id.nii.ac.jp/1001/00182678/
7. 電子動力学シミュレーションARTEDのKNLシステムOakforest-PACSでの全系性能評価
    - 廣川 祐太, 朴 泰祐, 植本 光治, 佐藤 駿丞, 矢花 一浩
    - 第160回IPSJ HPC研究会
    - http://id.nii.ac.jp/1001/00182693/
8. A proposal of GMPI: GPU self MPI for GPU clusters
    - Yuta Kuwahara, Toshihiro Hanawa, Taisuke Boku
    - [ACSI2016](http://acsi.hpcc.jp/2016/), Jan. 2016. <font color="red">(Outstanding Research Award)</font>
9. アクセラレータ向け並列プログラミング言語Xcalable ACCにおけるTCA/InfiniBandハイブリッド通信
    - 小田嶋 哲哉, 朴 泰祐, 塙 敏博, 村井 均, 中尾 昌広, 田渕 晶大, 佐藤 三久
    - 第150回 IPSJ HPC研究会．<font color="red">（CS領域奨励賞受賞：小田嶋 哲哉）</font>
    - http://id.nii.ac.jp/1001/00144608/
