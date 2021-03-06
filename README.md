# 概要
RESTful APIのチュートリアルです

# 前提
- Java 11
- Spring Boot 2.6.3

# Getting Started
`$ git clone https://github.com/raisetech-for-student/banana-spring-boot-tutorial.git`

`$ cd banana-spring-boot-tutorial`

`$ ./gradlew bootRun`

起動成功時のイメージ

![RESTfulAPI](https://user-images.githubusercontent.com/97335620/159174067-befad8a3-da74-4466-b082-9dc961b4d577.png)

`http://localhost:8080/greeting`にアクセスすると`{"id":1,"content":"Hello, World!"}`が表示される

- ブラウザで更新をかけるとidの値が１ずつ増加する

`http://localhost:8080/greeting?name=hoge`アクセスすると`{"id":1,"content":"Hello, hoge!"}`が表示される

- hogeの部分には任意の値が入力可能
- ブラウザで更新をかけるとidの値が１ずつ増加する

（`./gradlew bootRun`コマンドで実行している場合）`ctrl + c`で終了する
