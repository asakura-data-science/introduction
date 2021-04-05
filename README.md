# データの前処理 （Pythonによるビジネスデータサイエンス 第1巻）

---

本リポジトリは朝倉書店発行書籍『[データサイエンス入門](http://www.asakura.co.jp/books/isbn/978-4-254-12911-3/)』
（[Pythonによるビジネスデータサイエンス](http://www.asakura.co.jp/G_11.php?sreiesname=349) 第1巻）のサポートサイトです。


## サンプルコード

### ファイル構成

サンプルコードの解説については本書籍をご覧ください．
各章に対応したサンプルコードとデータがChapter_x というフォルダに入っています．

| フォルダ名  | 説明                                                                                                 |
|:----------- |:---------------------------------------------------------------------------------------------------- |
| `Chapter_2` | 2章「データを要約すると何が見えてくる？」で使用するデータと`.ipynb`形式のノートブック                |
| `Chapter_3` | 3章「関係性を調べる」で使用するデータと`.ipynb`形式のノートブック                                    |
| `Chapter_4` | 4章「より高度な分析1: 日本人の米離れは本当か？」で使用するデータと`.ipynb`形式のノートブック         |
| `Chapter_5` | 5章「より高度な分析2: 気温から売り上げを予測する」で使用するデータと`.ipynb`形式のノートブック       |
| `Chapter_6` | 6章「より高度な分析3: 食べ物の好みで都道府県を分類する」で使用するデータと`.ipynb`形式のノートブック |


## 実行環境の構築と実行方法

### 1. Anacondaのインストール
Pythonの実行環境の構築は，本書付録A.「本書のプログラムを実行する環境の構築」を参考にAnacondaをインストールください．
また，


### 2. 本リポジトリのサンプルコードのダウンロード
[こちら](https://github.com/asakura-data-science/introduction/archive/refs/heads/main.zip)から本リポジトリのサンプルコード一式をzip形式でダウンロードできます．ダウンロード後，ダウンロードしたzipファイルを作業用のフォルダに移動し，解凍してください．

### 3. Jupyter Notebookの起動
本書付録A.を参考に，Jupyter Notebookを起動し，先ほど解凍したファイルがあるフォルダから，サンプルプログラムを実行したいフォルダの中にある *.ipynb ファイルを開き実行ください．

### 4. japanize-matplotlibのインストール
本書サンプルコードでは，グラフの描画に日本語を用いるために`japanize-matplotlib`というライブラリを使用します．インストール方法は， `Chapter_2/DataScienceBook_2_Asakura.ipynb`をJupyter Notebookから開き，そこに記載されてあるコードを実行してください．
