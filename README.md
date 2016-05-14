# clustering
irisデータで階層的クラスタリング


``hac = HAC(iris.data, iris.target)``

データとラベルをNumpy形式で渡すとクラスタリング(初期パラメータはWard法)

``hac.draw_dendrogram(p=3,truncate_mode='lastp')``

デンドログラムを描画(pは上から何階層まで表示するか)

``hac.clustering(3)``
クラスタ数3で枝を切る

その他、結合したインデックスを計算、取得する``tree_structure``メソッドあり
