
# プラットフォームに依存した開発 (PBD)

「プラットフォームに依存した開発」は、特定のソフトウェアプラットフォーム上に存在するソフトウェアアプリケーションの設計と開発に関心を向けています。汎用プログラミングとは異なり、プラットフォームに依存した開発では、プラットフォーム固有の制約を考慮する必要があります。たとえば、Webプログラミング、マルチメディア開発、モバイルコンピューティング、アプリ開発、ロボット技術などでは、特定のサービス/API/ハードウェアが関連プラットフォームから提供され、これらが開発に制約を与えます。こうしたプラットフォームは、特化したAPIの使用、特異な配信/更新メカニズム、およびマシンレベルを見せない抽象化によって特徴付けられます。プラットフォームに依存した開発は、幅広いエコシステムに適用可能です。

いくつかのプラットフォーム (例: Web開発) が特出していることを認識していますが、CS2013のカリキュラムガイドラインで特定のプラットフォームを必須として指定すべきではないと認識しています。その結果、この知識領域では、人気となった多くのプラットフォームを強調していますが、コアカリキュラムにそのようなプラットフォームを含めていません。APIや制約された環境に対して開発する一般的な技術は、[ソフトウェア開発基礎 (SDF)](./z_appendix_A_SDF.md)などの他の知識りょいきでカバーされていることに注意してください。プラットフォームに依存した開発では、特定のプラットフォームの文脈内で、そのような一般的な技術をさらに強調します。


**PBD. プラットフォームに依存した開発 (選択科目)**

| 知識単位 | 必修時間 | 選択必修時間 | 含選択科目 |
| -------- | -------- | ------------ | ---------- |
| PBD/導入                      |   |   | Y |
| PBD/Web プラットフォーム      |   |   | Y |
| PBD/モバイルプラットフォーム  |   |   | Y |
| PBD/産業プラットフォーム      |   |   | Y |
| PBD/ゲームプラットフォーム    |   |   | Y |



## PBD/導入
*[選択科目]*

この知識単位では、プラットフォームに依存した開発が伝統的なソフトウェア開発とどのように異なるかを説明します。

**トピック:**

* プラットフォームの概要 (例: Web、モバイル、ゲーム、産業)
* プラットフォーム固有のAPIを介したプログラミング
* プラットフォームの言語の概要（例：Objective C、HTML5）
* プラットフォーム制約下でのプログラミング

**学習到達目標:**

1. プラットフォームに依存した開発が汎用プログラミングとどのように異なるかを説明する。 [知識]
2. プラットフォームの言語の特性をリスト化する。 [知識]
3. プラットフォームに依存した簡単なプログラムを書き、実行する。 [使用]
4. プラットフォーム制約付きのプログラミングの利点と欠点を並べる。 [知識]



## PBD/Web プラットフォーム
*[選択科目]*

**トピック:**

* Webプログラミングの言語（例：HTML5、Java Script、PHP、CSS）
* Webプラットフォームの制約
* ソフトウェア・アズ・ア・サービス（SaaS）
* Web標準

学習到達目標:

1. 簡単なWebアプリケーションの設計と実装を行う。 [使用]
2. Webが開発者に課す制約を説明する。 [知識]
3. Webプログラミングと汎用プログラミングを比較対比する。 [評価]
4. ソフトウェア・アズ・ア・サービス（SaaS）と伝統的なソフトウェア製品の違いを説明する。 [知識]
5. Web標準がソフトウェア開発にどのような影響を及ぼすかを議論する。 [知識]
6. 既存のWebアプリケーションを現行のWeb標準に照らしてレビューする。 [評価]



## PBD/モバイルプラットフォーム
*[選択科目]*

**トピック:**

* モバイルのプログラミング言語
* 可動性と無線通信の課題
* 位置情報を用いたアプリケーション
* パフォーマンスと電力のトレードオフ
* モバイルプラットフォームの制約
* 新興技術

**学習到達目標:**

1. 指定されたモバイルプラットフォームのためのモバイルアプリケーションを設計し、実装する。 [使用]
2. モバイルプラットフォームが開発者に課す制約を議論する。 [知識]
3. 性能と電力のトレードオフについて議論する。 [知識]
4. モバイルプログラミングと汎用プログラミングを比較対比する。 [評価]



## PBD/産業プラットフォーム
*[選択科目]*

この知識単位は[IS/ロボット工学](./z_appendix_A_IS.md#isロボット工学)に関連しています。

**トピック:**

* 産業プラットフォームの種類（例：数学、ロボット、産業用制御システム）
* ロボットソフトウェアとそのアーキテクチャ
* ドメイン特化型言語
* 産業プラットフォームの制約

学習到達目標:

1. 与えられたプラットフォーム (例: Lego MindstormsやMatlabを使用) で産業アプリケーションを設計し、実装する。 [使用]
2. ドメイン特化型言語と汎用プログラミング言語を比較対比する。 [評価]
3. 与えられた産業プラットフォームが開発者に課す制約を議論する。 [知識]



## PBD/ゲームプラットフォーム
*[選択科目]*

**トピック:**

* ゲームプラットフォームの種類 (例: XBox, Wii, PlayStation)
* ゲームプラットフォームの言語 (例: C++, Java, Lua, Python)
* ゲームプラットフォームの制約

**学習到達目標:**

1. ゲームプラットフォーム上で簡単なアプリケーションを設計・実装する。 [使用]
2. ゲームプラットフォームが開発者に課した制約を説明する。 [知識]
3. ゲームプログラミングと汎用プログラミングを比較対比する。 [評価]

