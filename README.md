# keras_cnn
## 使い方
白背景の画像一覧を指定の場所におく（カテゴリ毎にフォルダ分けしておく）
以下のコマンドで、画像内のオブジェクトを抽出し、正方形に切り出す
>python3 tranImages.py

上記で生成した画像を元にCNNモデルを作成する
>python3 createModel.py