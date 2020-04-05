## sequel-pro-nightly install
https://mom0tomo.github.io/post/sequel-pro-nightly/

## docker-compose up
docker-compose up -d

## dockerコンテナに入る
docker exec -it mysql_host bash -p

## mysql login
mysql -u root -p -h 127.0.0.1

## change login settings
ALTER USER 'root'@"%" IDENTIFIED WITH mysql_native_password BY 'password';

## 参考URL
https://qiita.com/TAMIYAN/items/ed9ec892d91e5af962c6
https://qiita.com/yusuke_dev/items/7f0ca12ced72363f9448
