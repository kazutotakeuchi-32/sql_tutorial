## Installation

### インストール

```
git clone https://github.com/kazutotakeuchi-32/sql_tutorial.git
```

## Usage 

### コンテナ構築

```
コンテナ作成

docker-compose up
```

### mysql接続

```
DBコンテナ接続

docker-compose run db /bin/bash

db接続

mysql -u root -h db --protocol=tcp

db選択

use worldcup2014 ;

```

## DB画像
<img src="http://i.imgur.com/Jjwsc.jpg" alt="DB">

## Note

[ブログ](https://tech.pjin.jp/blog/2016/12/05/sql%E7%B7%B4%E7%BF%92%E5%95%8F%E9%A1%8C-%E4%B8%80%E8%A6%A7%E3%81%BE%E3%81%A8%E3%82%81)

