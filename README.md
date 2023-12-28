# lamp-docker

## 各ソフトの情報

- Linux：OS
- Apache 2.4系：Webサーバ
- MySQL 5.7系：データベースシステム
- PHP 7.4.系：プログラム言語

## ディレクトリ構造

```:text
.
├── db_data/ ## ローカル環境用でのDBの中身
├── docker/ ## 各コンテナ用のDockerfile
│   ├── mysql/
│   └── php-apache/
│       └── Dockerfile
├── htdocs/ ## phpのソースコードはここに配置する
│   └── index.php
├── php/ ## phpやapacheの設定ファイルはここに配置
│   ├── httpd.conf
│   └── php.ini
├── LICENSE
├── README.md
└── docker-compose.yml
```
