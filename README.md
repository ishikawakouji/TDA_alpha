# TDA_alpha

TDAの練習をします。

## ざっくり見るとは
watch_outline.ipynb

次元削減の手法をいくつか。

主成分分析を含む古典的？といわれる手法では、
非線形な分布にうまく対応できないらしい。
後半の紹介にある手法では、その辺りの改良が
されているとのこと。

この中に、 diffusionMap があり、 dreamtolearn の
サンプルで、よく利用されている。

## IRIS データをTDAしてみる
ATD with IRIS data.ipynb

dreamtolearn の紹介にあったもの。 IRIS は機械学習では
よく利用されているデータだが、４種類目が設定されている。

TDAのなかでよく利用されている、 persistent homology
のRパッケージ phom を利用している。

現在 phom は CRAN から外れているようなので、
アーカイブを持ってきて、インストールする。
