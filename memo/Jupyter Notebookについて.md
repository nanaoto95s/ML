# Jupyter Notebook使い方

## Jupyter Notebookとは？

**ブラウザ上で動作するプログラムの対話型実行環境**
Tensorflowなどの機械学習やディープラーニング用のライブラリも動作することができる。

## インストール

### 主な２つの方法

1.Anacondaと一緒にJupyter Notebookもインストール
**Anaconda**とは、**データサイエンスに特化したプラットフォーム**で、データサイエンスに適したライブラリや便利な機能を持っている。

2.Jupyter Notebookだけをインストール
pipを利用して、インストール

  // Python3.x
  ```
  python3 -m pip install --upgrade pip
  python3 -m pip install jupyter
  ```

  // Python2.x
  ```
  python -m pip install --upgrade pip
  python -m pip install jupyter
  ```

## 使い方

---
- セル（Cell）
  セルと呼ばれるスペースにコードを入力し実行する。
  
  - セル内のプログラムを実行：Ctrl + Enter
  - セルを実行し下にセルを追加：Shift + Enter
  - セルを再度編集可能にする：セルをダブルクリック
  - セルの削除：セルを選択＋escキー、Dを２回押す
  - Notebookの保存：command + s

  - エディットモード
    セルに対してプログラムなどを入力するモード。
    セルの回りの枠線が緑色になる。
  
  - コマンドモード
    セルの削除や追加など、セル自体に対して何らかの操作を行うモード。
    escキーを押すとセルの回りの枠線が青色になる。
  
---
- カーネル（Kernel）
  Jupterにおいてカーネルとは、**入力されたコードをインタラクティブに処理して結果を返却するプロセス**のことを指す。
  Pythonの処理を実行するカーネルはIPythonが利用されるが、その他の言語を処理したい場合には、その言語のカーネルを別途インストールする必要がある。
  
  [使用できるカーネル](https://github.com/jupyter/jupyter/wiki/Jupyter-kernels)
  
---
- ウィジェット（WIdgets）
  対話型のUIを実装する際に用いる。つまり、グラフをインタラクティブにする。
  
  - ipywidgets
  

  
## Jupyter Notebookでのファイル共有

Jupyter Notebookではファイルを**「.ipynb」**という独自の形式でダウンロード、アップロードできる。
このファイルを共有することで、共有が可能。

- 共有したいファイルを選択
- メニューが表示される
  - Duplicate：コピーの作成
  - Rename：ファイル名の変更
  - Move：保存先ディレクトリの変更
  - Download：ダウンロード
  - ゴミ箱アイコン：ファイルの削除
 