# ファイアーウォール



## 変更ポイント

| 項目                                         | 旧リージョン(*1)                                           | 新リージョン       |
| -------------------------------------------- | ---------------------------------------------------------- | ------------------ |
| ルール変更（FWポリシー変更）の反映タイミング | コネクションが維持されている場合は即時反映されません。(*2) | 即時反映されます。 |

(*1)ここでは東日本リージョン1、西日本リージョン1、西日本リージョン２のみです。東日本リージョン2は旧リージョンですが新リージョンと同様の仕様です。  
(*2)ファイアーウォールを経由した通信をしているときにその通信を拒否するルールを設定したとしても、即座にその通信が遮断されません。


