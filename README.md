# Hierarchical Agglomerative Clustering
sample codes
Dataset : iris dataset (sklearn.datasets)
env : ``Python 3.5.1 :: Anaconda 2.5.0 (x86_64)``


``hac = HAC(iris.data, iris.target)``

データとラベルをNumpy形式で渡すとクラスタリング(初期パラメータはWard法)

``hac.draw_dendrogram(p=3,truncate_mode='lastp')``

デンドログラムを描画(pは上から何階層まで表示するか)

``hac.clustering(3)``
クラスタ数3で枝を切る

その他、結合したインデックスを計算、取得する``tree_structure``メソッドあり
