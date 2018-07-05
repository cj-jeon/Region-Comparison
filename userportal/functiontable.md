# ユーザーポータル機能一覧表

ユーザーポータルの新リージョン実装状況です。

|                          |                        | 一覧 | 詳細 | 作成 | 削除 |  編集   |
| ------------------------ | ---------------------- | :--: | :--: | :--: | :--: | :-----: |
| コンピュート             | 仮想サーバ             |  ✓   |  ✓   |  ✓   |  ✓   |    ✓    |
|                          | キーペア               |  ✓   |  ✓   |  ✓   |  ✓   |    -    |
|                          | イメージ               |  ✓   |  ✓   |  -   |  -   |    -    |
|                          | スケジュール           | N/A  | N/A  | N/A  | N/A  |   N/A   |
| ストレージ               | ブロックストレージ     |  ✓   |  ✓   |  ✓   |  ✓   |    ✓    |
|                          | オブジェクトストレージ | N/A  | N/A  | N/A  | N/A  |   N/A   |
|                          | スナップショット       |  ✓   |  ✓   |  ✓   |  ✓   |    ✓    |
| ネットワーク             | 仮想ネットワーク       |  ✓   |  ✓   |  ✓   |  ✓   |    ✓    |
|                          | 仮想ルータ             |  ✓   |  ✓   |  ✓   |  ✓   |    ✓    |
|                          | セキュリティグループ   |  ✓   |  ✓   |  ✓   |  ✓   |    ✓    |
|                          | グローバルIP           |  ✓   |  -   |  ✓   |  ✓   |    -    |
|                          | ファイアーウォール     |  ✓   |  ✓   |  ✓   |  ✓   |    ✓    |
|                          | DNS(*1)                |  -   |  -   |  -   |  -   |    -    |
|                          | ロードバランサー       |  ✓   |  ✓   |  ✓   |  ✓   | N/A(*2) |
|                          | VPNサービス(SSL-VPN)   |  ✓   |  ✓   |  ✓   |  -   |    ✓    |
|                          | VPNサービス(IPSecVPN)  | N/A  | N/A  | N/A  | N/A  |   N/A   |
| データベース             | データベース仮想サーバ | N/A  | N/A  | N/A  | N/A  |   N/A   |
| テンプレート             | スタック               | N/A  | N/A  | N/A  | N/A  |   N/A   |
| 監視                     | モニタリング           | N/A  | N/A  | N/A  | N/A  |   N/A   |
|                          | アラーム               | N/A  | N/A  | N/A  | N/A  |   N/A   |
| インポート・エクスポート | VMインポート           | N/A  | N/A  | N/A  | N/A  |   N/A   |
|                          | VMエクスポート         | N/A  | N/A  | N/A  | N/A  |   N/A   |
| API実行(*3)              |                        |  -   |  -   |  -   |  -   |    -    |
| ログ                     | 操作ログ               |  ✓   |  ✓   |  -   |  -   |    -    |

✓：提供  
N/A：今後提供予定  
-：旧リージョン含め提供なし  

(*1)DNSは東日本第1リージョンのみの提供です。  
(*2)新規作成時も含めルールを設定、編集する機能は今後提供予定です。  
(*3)API実行は旧リージョンと同じく実行機能の提供です。  
