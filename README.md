# 1. upki_server_all_viewer

UPKIの電子証明書自動発行支援システムから取得できるserverAll.tsvの内容を検索して表示するためのツール。

Anaconda同梱のJupyterlabで動作確認済。

# 2. 使い方

1. 本ツールと同じフォルダに serverAll.tsv を配置し、セル1を実行してTSVファイルを読み込む。
1. セル2を実行すると主体者DNの全部または一部を入力して検索可能。
1. 以後はセル2のみ実行すればよい。

# 3. 備考

読み込むファイル名を変更( serverAll.tsv → clientAll.tsv )すればクライアント証明書でも利用可能。