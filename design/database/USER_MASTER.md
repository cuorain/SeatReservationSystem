# カラム定義
| 論理名 | 物理名 | データ型 | 桁数 | PK | NOT NULL |
| ------ | ----- | ------- | ---- | -- | -------- |  
| ユーザーキー | USER_KEY | int | - | Y | Y |
| ユーザーID | USER_ID | varchar | 20 | - | Y |
| ユーザー名 | USER_NAME | varchar | 20 | - | Y |
| ユーザー表示名 | USER_DISPLAY_NAME | varchar | 20 | - | Y |
| 所属 | AFFILIATION | varchar | 20 | - | - |
| ロール | ROLE_ID | varchar | 1 | - | Y |
| パスワード | PASSWORD | varchar | 256 | - | Y |

## 一意制約
* ユーザーID

## シーケンス定義
* ユーザーキー
