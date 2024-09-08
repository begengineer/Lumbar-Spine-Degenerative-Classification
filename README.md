# Lumbar-Spine-Degenerative-Classification

2024/09/03 
ベースラインの構築Notebookを参考に作成
URL
https://www.kaggle.com/code/itsuki9180/rsna2024-lsdc-training-baseline

画像を上下とかにしてかさましする

9月4日
https://www.kaggle.com/code/hugowjd/rsna2024-lsdc-training-densenet
上記を参考にしたい

こっちは簡単なベースライン？
[https://www.kaggle.com/code/hugowjd/rsna2024-lsdc-training-densenet](https://www.kaggle.com/code/itsuki9180/rsna2024-lsdc-making-dataset)

9月7日



事前学習モデル作成ガイドライン
https://www.kaggle.com/code/brendanartley/lumbar-coordinate-dataset-code/notebook#Save

・推論中にtorch.sigmoid()関数を適用する必要があるらしい
・事前学習モデルを適用するときは以下のchatGPTのコードサンプルを見てほしい。
→学習済みモデルを現在のNotebookに適用する方法とtorch.sigmoid()の適用方法

現在参考にしているベースライン
https://www.kaggle.com/code/hugowjd/rsna2024-lsdc-densenet-submission


9月8日


resnet50で試してみる

9月9日

submit20240908 Ver5でresnet50dの5fold学習モデルをsubmit
精度は0.7ちょっと下がった
次は10fold分回してみたいため、google colab上で実行できるように環境を整える
