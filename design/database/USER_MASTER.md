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
| 作成者 | CREATED_BY | int | - | - | Y |
| 作成日時 | CREATED_AT | timestamp | - | - | Y |
| 更新者 | UPDATED_BY | int | - | - | Y |
| 更新日時 | UPDATED_AT | timestamp | - | - | Y |

## 一意制約
* ユーザーID

## シーケンス定義
* ユーザーキー
