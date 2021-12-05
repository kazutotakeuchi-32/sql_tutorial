## Insalation

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


```


