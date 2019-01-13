# vagrant_docker

## 環境

プライベートIPアドレス：`192.168.33.20`

以下にDocker・Docker Composeを追加したものです

https://github.com/carrry0209/vagrant_lamp


## How to use

※cloneした後、ディレクトリの名前をvagrantに変更して使用してください
```bash
mv vagrant_docker vagrant
```

その他立ち上げ方などは、以下の `How to use` に記載してあります

https://github.com/carrry0209/vagrant_lamp

## 動作確認

dockerコマンドは、sudo をつけなくても実行できるようにしてあります
```
docker version
```
出力例
```
Client:
 Version:           18.09.1
 API version:       1.39
 Go version:        go1.10.6
 Git commit:        4c52b90
 Built:             Wed Jan  9 19:35:01 2019
 OS/Arch:           linux/amd64
 Experimental:      false

Server: Docker Engine - Community
 Engine:
  Version:          18.09.1
  API version:      1.39 (minimum version 1.12)
  Go version:       go1.10.6
  Git commit:       4c52b90
  Built:            Wed Jan  9 19:06:30 2019
  OS/Arch:          linux/amd64
  Experimental:     false

```

docker-composeは普通に実行できます
```
docker-compose version
```
出力例
```
docker-compose version 1.23.2, build 1110ad01
docker-py version: 3.6.0
CPython version: 3.6.7
OpenSSL version: OpenSSL 1.1.0f  25 May 2017
```
