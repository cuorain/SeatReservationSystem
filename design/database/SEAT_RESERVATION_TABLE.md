# カラム定義
| 論理名 | 物理名 | データ型 | 桁数 | PK | NOT NULL |
| ------ | ----- | ------- | ---- | -- | -------- |  
| 予約ID | RESERVATION_ID | int | - | Y | Y |
| ユーザーキー | USER_KEY | int | - | - | Y |
| 座席No. | SEAT_NO | int | - | - | Y |
| 予約日 | RESERVE_DATE | timestamp | - | - | Y |
| 作成者 | CREATED_BY | int | - | - | Y |
| 作成日時 | CREATED_AT | timestamp | - | - | Y |
| 更新者 | UPDATED_BY | int | - | - | Y |
| 更新日時 | UPDATED_AT | timestamp | - | - | Y |

## 一意制約
* ユーザーID, 座席No., 予約日

## インデックス定義
* 予約日
