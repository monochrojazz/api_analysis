# api_analysis
Cuckooの出力jsonのAPI部分をタイムラインで可視化、全体のおおよその概略を掴むためのツール。

## requirement
Python3のJupyter notebook。  
networkx, matplotlibを要する。  
$ pip install networkx matplotlib  
などでインストールが必要。  

## functions
APIの集約時間間隔、表示時間範囲は調節可能。  
APIのフィルタリングも可能。  
APIの付加情報  
- LdrGetProcedureAddressで呼ばれた関数名
- APIが呼び出すファイル名
- APIが呼び出すレジストリキー
はMODE切り替えによって表示される。  

具体的な設定方法はipynbのコメント参照。  
