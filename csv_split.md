# csv分割

## sliceのindexを算出してcsv split

* AmazonSageMakerCourse > Introduction > notebook_5minute_intro.ipynb
* 容量算出 -> gb数+1で分割 -> スライスを複数作成して分割分読む・新規copy ※分割前との件数検証が必要

## numpyのsplitの方が楽
* https://ksomemo.github.io/contents/qiita/%E3%83%95%E3%82%A1%E3%82%A4%E3%83%AB%E3%82%92N%E8%A1%8C%E3%81%AB%E5%88%86%E5%89%B2%E3%81%99%E3%82%8B.html

* gb数 roundup(小数点切り上げ)で分割し、numpy配列分のuploadは手動で。データ作るところまでは自動化