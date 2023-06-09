
# グラフィックスと視覚化 (GV)

コンピュータグラフィックスは、コンピュータによる画像の生成と操作と記述するために一般的に使用される用語です。これは、計算を通じて視覚的な対話を可能にする科学です。その使用例には、カートゥーン、映画の特殊効果、ビデオゲーム、医療画像、工学、さらには科学的、情報的、知識的な視覚化が含まれます。伝統的に、学士レベルのグラフィックスはレンダリング、線形代数、現象論的アプローチに焦点を当ててきました。最近では、物理学、数値積分、スケーラビリティ、特殊用途ハードウェアを含めるように焦点が移り始めています。学生がコンピュータグラフィックスの使用と生成に熟練するためには、ファイル形式、ハードウェアインターフェース、アプリケーションプログラムインターフェースなど、多くの実装固有の問題に対処する必要があります。これらの問題は急速に変化し、下記の説明はそれらについて過度に規範的にならないよう試みています。グラフィックスと視覚化の範囲は、いくつかの相互に関連する分野に分けられます:

* 基本原理: コンピュータグラフィックスは、人間の視覚を使った情報の知覚についてと、情報が表示デバイスにどう描画されるかについての知識に依存しています。すべてのコンピュータサイエンティストは、どのグラフィックスがどのように適用されるべきかや、画面描画に関与する基本的なプロセスについて、ある程度の理解を持つべきです。
* モデリング: 表示する情報は、コンピュータのメモリに何らかの形で符号化される必要があります。これは種類と形状の数学的な仕様の形で行われます。
* レンダリング: レンダリングは、モデルに含まれる情報を表示するプロセスです。
* アニメーション: アニメーションは、画像が動いているように見せるレンダリングと、モデルの時間変動の合成・取得です。
* 可視化: 可視化の分野では、幅広い応用領域からのデータセットの相関構造と関係を特定し、提示することを目指しています。提示の主な目的は、データセットの情報を伝えて理解を深めることです。
* 計算幾何学: 計算幾何学は、幾何学の用語で記述されるアルゴリズムの研究です。


グラフィックスと視覚化は、[知的システム (IS)](./z_appendix_A_IS.md) 知識領域に見られるマシンビジョンや画像処理、および[アルゴリズムと計算量 (AL)](./z_appendix_A_AL.md) 知識領域に見られる計算幾何学などのアルゴリズムと関連しています。仮想現実に関するトピックは、[ヒューマンコンピュータインタラクション (HCI)](./z_appendix_A_HCI.md) 知識領域にあります。

ここでは、データ表現、抽象化、プログラム実装の基本的な概念について学生が理解していることを前提としています。



**GV. グラフィックスと視覚化 (必修 2時間, 選択必修 1時間)**

| 知識単位 | 必修時間 | 選択必修時間 | 含選択科目 |
| -------- | -------- | ------------ | ---------- |
| GV/基礎概念                     | 2 | 1 | Y |
| GV/基本的なレンダリング         |   |   | Y |
| GV/幾何モデリング               |   |   | Y |
| GV/先進的なレンダリング         |   |   | Y |
| GV/コンピュータ・アニメーション |   |   | Y |
| GV/視覚化                       |   |   | Y |



## GV/基礎概念
*[必修 2 時間, 選択必修 1時間]*

ほぼ全てのコンピュータ科学者やソフトウェア開発者にとって、人間が機械とどのように対話するかを理解することは必須です。これらのトピックは、標準的な学部のグラフィックスの講座でカバーされることもありますが、初級のコンピュータ科学やプログラミングの講座でも取り扱うことがあります。即時モードと保持モードを含める動機の一部は、これらのモードがポーリングとイベント駆動プログラミングに類似しているからです。これはコンピュータ科学における基本的な問いです: ボタンオブジェクトは存在するのか、それとも画面上にボタンの表示だけが存在するのか？ このセクションでの学習到達目標のほとんどは知識レベルで、これらのトピックの多くは後のセクションでより深く再訪されます。



**トピック:**

[必修]

* ユーザーインターフェース、音声と動画の編集、ゲームエンジン、CAD、可視化、仮想現実を含むメディアアプリケーション
* アナログデータのデジタル化、解像度、人間の知覚の限界 (例えば、視覚ディスプレイのピクセル、レーザープリンターのドット、音声のサンプリングなど([HCI/基礎](./z_appendix_A_HCI.md#hci基礎)))
* UIの構築と標準メディア形式の表示のための標準APIの使用 ([HCI/インタラクションの設計](./z_appendix_A_HCI.md#hciインタラクションの設計)）
* 可逆と非可逆形式を含む標準メディア形式

[選択必修]

* 加法混色と減法混色 (CMYKとRGB) と、これらが異なる色域を提供する理由
* ベクターとラスター表現の画像に体現される、データの保存と再計算の間のトレードオフ
* 静止画の連続としてのアニメーション

[選択科目]

* ダブルバッファリング

**学習到達目標:**

[必修]

1. デジタル表示の一般的な用途を特定する（例：コンピューターグラフィックス、音声）。[知識]
2. アナログ信号がどのようにして離散的なサンプルで適切に表現できるかを一般的な言葉で説明する。(例: 画像をどうピクセルで表現するか)[知識]
3. 人間の知覚の限界がアナログ信号のデジタル表現の選択にどう影響するかを説明する。[知識]
4. 標準的なAPIを使用して単純なユーザーインターフェースを構築する。[使用]
5. 可逆と非可逆の画像圧縮技術の違いを説明する。例えば、JPG、PNG、MP3、MP4、GIFなどの一般的な画像ファイル形式にどう反映されているか。[知識]

[選択必修]

6. カラーモデルと、画像表示機器での用途について説明する。[知識]
7. 情報の単なる保存と、再現に必要最低限の情報の保存との間のトレードオフを説明します。(例: ベクターとラスター描画の違い)。[知識]

[選択科目]

* 離散的なフレームの列から連続した動きを生成する基本的なプロセスを説明します（これは時々「フリッカー融合」と呼ばれます）。[知識]
* ダブルバッファリングによってアニメーションのちらつきを除去する方法を説明します。[知識]



## GV/基本的なレンダリング
*[選択科目]*

このセクションでは、ほぼ全ての大学の画像処理の講座でカバーされ、研究を進めるにあたり必須となる基本的なレンダリングやグラフィック技術について説明します。サンプリングとアンチエイリアシングは、デジタル変換の影響と関連し、音声サンプリングなどの他のコンピューティングの領域でも登場します。

**トピック:**

* レンダリングの本質。例えば、光の放射や散乱とそれが数値積分との関連性。
* 前進レンダリングと後進レンダリング（つまり、レイキャスティングとラスタリゼーション）
* ポリゴン表現
* 基本的な放射測定、相似三角形、投影モデル
* アフィン変換と座標系変換
* レイトレーシング
* 可視性と遮蔽。解決策としての深度バッファリング、画家のアルゴリズム、レイトレーシング
* 前進レンダリング方程式と後進レンダリング方程式
* 単純な三角形ラスタリゼーション
* シェーダーベースのAPIを使用したレンダリング
* テクスチャマッピング。縮小と拡大（例えば、三線形MIPマッピング）を含む
* 空間データ構造のレンダリングへの適用
* サンプリングとアンチエイリアシング
* シーングラフとグラフィックスパイプライン

**学習到達目標:**

1. 光の伝達の問題と数値積分との関連性を議論します。光が放出され、シーン内で散乱し、目によって測定される。[知識]
2. 基本的なグラフィックスパイプラインと、それにおける前進レンダリングと後進レンダリングの役割を説明します。[知識]
3. 単純なグラフィックイメージの3Dモデルを表示するプログラムを作成する。[使用]
4. 相似三角形から透視図を導出し、点（x、y、z）を点（x/z、y/z、1）に変換する。[使用]
5. アフィン変換を適用して2次元および3次元の点を取得します。[使用]
6. 3次元座標系を適用し、2D変換操作を拡張して3Dの変換を扱うために必要な変更を行う。[使用]
7. 前進レンダリングと後進レンダリングを対比させる。[評価]
8. テクスチャマッピング、サンプリング、アンチエイリアシングの概念と応用について説明する。[知識]
9. 可視性問題に対するレイトレーシング/ラスタリゼーションの二重性を説明する。[知識]
10. 単純な2次元画像に対して変換とクリッピング操作を実行する簡単な手順を実装する。[使用]
11. 頂点バッファとシェーダーを使用したラスタリゼーションAPI（例：OpenGL）を使用して、シンプルなリアルタイムレンダラーを実装する。[使用]
12. 異なるレンダリング技術を比較対比する。[評価]
13. 解像度と色深度に基づき、必要容量を算出する。[評価レベル]
14. リフレッシュレート、ラスタリゼーション技術に基づき、必要計算時間を算出する。[評価レベル]



## GV/幾何モデリング
*[選択科目]*

**トピック:**

* 交差の計算や近接判定などの基本的な幾何学的操作
* 体積、ボクセル、頂点ベースの表現
* パラメトリック多項式曲線と曲面
* 曲線と曲面の暗黙的表現
* 多項式曲線、ベジェ曲線、スプライン曲線と曲面、非一様有理Bスプライン(NURB)、レベルセット法などの近似技術
* テッセレーション、メッシュ表現、メッシュ滑面化、ドロネー三角形分割やマーチングキューブなどのメッシュ生成技術を含む表面表現技術
* 空間分割技術
* フラクタル、生成モデリング、L-システムなどの手続き型モデル
* グラフタル（プログラミング言語と関連し、画像を生成する文法）
* 弾性変形可能モデル、自由形状変形モデル
* 細分割曲面
* 多重解像度モデリング
* 再構成
* 空間領域構成法 (CSG)

**学習到達目標:**

1. 暗黙的形式とパラメトリック形式の両方を使用して曲線と曲面を表現する。[使用]
2. 曲面のテッセレーションにより単純な多面体モデルを作成する。[使用]
3. 暗黙的な曲面からメッシュ表現を生成する。[使用]
4. 手続き型の手法を用いてフラクタルモデルまたは地形を生成する。[使用]
5. レーザースキャナーで取得したデータ点からメッシュを生成する。[使用]
6. 立方体や二次曲面などの単純な基本形状からCSGモデルを作成する。[使用]
7. 空間・時間計算量、画像の品質に関して、モデリングのアプローチを比較対比する。[評価]


## GV/先進的なレンダリング
*[選択科目]*

**トピック:**

* レンダリング方程式への解と近似。以下はその例
 * 分散レイトレーシングとパストレーシング
 * フォトンマッピング
 * 双方向パストレーシング
 * Reyes（マイクロポリゴン）レンダリング
 * メトロポリス光輸送法
* 時間（モーションブラー）、レンズ位置（フォーカス）、連続周波数（色）とそれらがレンダリングに与える影響
* シャドウマッピング
* 遮蔽カリング
* 双方向散乱分布関数（BSDF）理論とマイクロファセット
* 表面下散乱
* 面光源
* 階層的デプスバッファリング
* ライトフィールド、画像ベースレンダリング
* 非写実的レンダリング
* GPUアーキテクチャ
* 光への順応、ノイズへの感度、フリッカー融合を含む人間の視覚システム


**学習到達目標:**

1. アルゴリズムがレンダリング方程式の解をどのように推定するかを実演する。[評価]
2. レンダリングアルゴリズムの特性（例えば、完全性、一貫性、無偏性）を証明する。[評価]
3. 簡単なアルゴリズムの帯域幅と必要計算量を分析する。[評価]
4. ラスタリゼーションAPIを用いて、非自明なシェーディングアルゴリズム（例えば、トゥーンシェーディング、カスケードシャドウマップ）を実装する。[使用]
5. 特定の芸術的技術がどのようにレンダラーで実装されるかについて議論する。[知識]
6. 特定の画像を作成するために使用されたグラフィックス技術をどのように認識するかを説明する。[知識]
7. 個々のピクセルレベルの原始的なグラフィックスシステムを用いて、指定されたグラフィックス技術のいずれかを実装する。[使用]
8. 簡単な（例えば、フォンモデルの）BRDFと反射・屈折を使用して、レイトレーサーを実装する。[使用]


## GV/コンピュータ・アニメーション
*[選択科目]*

**トピック:**

* 順運動学と逆運動学
* 衝突検出と反応
* ノイズ、ルール（ボイド/群衆）、パーティクルシステムを使用した手続き型アニメーション
* スキニングアルゴリズム
* 剛体動力学、物理パーティクルシステム、布や肉体や髪のための質量+バネのネットワークを含む物理ベースの動き
* キーフレームアニメーション
* スプライン
* 四元数などの回転用のデータ構造
* カメラアニメーション
* モーションキャプチャ

**学習到達目標:**

1. 順運動学的アプローチを使用して、モデル部品の位置と向きを計算する。[使用]
2. 逆運動学的アプローチを使用して、位置と向きからモデルの関節部分の向きを計算する。[使用]
3. 回転の異なる表現におけるトレードオフを説明する。[評価]
4. 中間の位置と方向を生成するためのスプライン補間法を実装する。[使用]
5. 例えば [Witkin & Kass](https://www.cs.ait.ac.th/~mdailey/cvreadings/Kass-Snakes.pdf)、[スネークとワーム](https://dl.acm.org/doi/10.1145/54852.378508)、[シンプレクティックオイラー法](https://ja.wikipedia.org/wiki/%E3%82%B7%E3%83%B3%E3%83%97%E3%83%AC%E3%82%AF%E3%83%86%E3%82%A3%E3%83%83%E3%82%AF%E6%95%B0%E5%80%A4%E7%A9%8D%E5%88%86%E6%B3%95)、[ベレの方法](https://ja.wikipedia.org/wiki/%E3%83%99%E3%83%AC%E3%81%AE%E6%96%B9%E6%B3%95)、または中点オイラー法など、単純なニュートン力学を使用した粒子動力学的物理モデリングのアルゴリズムを実装する。[使用]
6. 飛沫・埃・火・煙などの弾道軌道のモデリングのための流体力学的手法の背後にある基本的なアイデアを議論する。[知識]
7. 一般的なアニメーションソフトウェアを使用して、メタボールと骨格構造を用いた単純な有機的形状を構築する。[使用]



## GV/視覚化
*[選択科目]*

視覚化は、[ヒューマンコンピュータインタラクション (HCI)](./z_appendix_A_HCI.md)の知識領域および[計算科学 (CN)](./z_appendix_A_CN.md)と強い関連性があります。利用人口やインターフェイスの評価に関連する追加のトピックについては、HCIおよびCNの知識領域を参照してください。

**トピック:**

* 2D/3D スカラー場の可視化: カラーマッピング、等値面
* 立体データの直接レンダリング: レイキャスティング、伝達関数、セグメンテーション
* 以下の情報の視覚化: 
 * ベクトル場と流量データ
 * 時系列データ
 * 高次元データ: 次元削減、平行座標
 * 非空間データ: 多変量、ツリー/グラフ構造、テキスト
* 視覚的抽象化のための知覚と認知の基礎
* 視覚化の設計
* 視覚化手法の評価
* 視覚化の応用

**学習到達目標:**


1. スカラーとベクトルの可視化のための基本的なアルゴリズムを説明する。[知識]
2. 正確性と性能の観点から、可視化アルゴリズムのトレードオフを説明する。[評価]
3. データの特性とアプリケーションタスクの特定の組み合わせに対して適切な可視化を設計し提案する。[評価]
4. 特定のタスクに対する与えられた可視化の効果を分析する。[評価]
5. 可視化アルゴリズムやシステムの有用性を評価するためのプロセスを設計する。[評価]
6. 科学的、医学的、数学的データの表現、流れの可視化、空間分析など、可視化のさまざまな応用を認識する。[知識]
