# Dockerに手動でWordPressをインストール

## URL
http://localhost:8080

## 注意点
- WordPressのインストール時のデータベースのホスト名はMySQLのコンテナ名

## WordPressのダウンロード
```bash
wget https://ja.wordpress.org/wordpress-6.1.1-ja.zip
# curl -OL https://ja.wordpress.org/wordpress-6.1.1-ja.zip
unzip wordpress-6.1.1-ja.zip
```

## 参考サイト
- [DockerでApache+PHP+MySQLの環境を構築してみる - Qiita](https://qiita.com/me-654393/items/1ed212cb33eafe734835)
- [【開発環境構築】DockerでWordpressの開発環境構築をして「Error establishing a database connection」で繋がらないときはwp-config.phpを確認！ - Qiita](https://qiita.com/wallkickers/items/1e7af73dfd75d441dc0c#%E5%8E%9F%E5%9B%A02wp-configphp%E3%81%AEdb_host%E3%81%AFdb%E3%82%B3%E3%83%B3%E3%83%86%E3%83%8A%E5%90%8D)
- [docker-compose を用いて Apache・PHP・MySQL の開発環境を構築してみた](https://zenn.dev/ikuraikura/articles/d166724f2c123d1db312)
- [【PHP】Docker環境にphpMyadminを導入する](https://zenn.dev/yuyaamano23/articles/ffdf58a6409367)
