# TestRepository

hello,world.

@startuml
actor Client
participant Server as "サーバー"
participant Database as "データベース"

Client -> Server: データ要求
Server -> Database: 問い合わせ
Database --> Server: 結果を返す
Server --> Client: データ
@enduml