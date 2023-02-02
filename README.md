# 1行でDockerサーバ環境構築
サーバに`root`ログインし１行のコマンドを実行するだけでDockerのサーバ環境が構築できるスクリプトです。

## 対象OS
- CentOS Stream 9
- CentOS Stream 8
- Ubuntu 22
- Ubuntu 20
- Ubuntu 18

## ライセンス

[![MIT license](https://img.shields.io/badge/License-MIT-blue.svg)](https://lbesson.mit-license.org/)

# 内容
Ansibleのローカル実行で、Dockerに必要なモジュールを含めてDocker環境を構築します。

## 主なインストールモジュール

- docker-ce
- docker-ce-cli
- docker-compose-plugin

# 使い方
新規にOSをインストールしたサーバに`root`でログインし、以下の１行のコマンドをそのままコピーして実行します。

## 実行コマンド
```
curl https://raw.githubusercontent.com/czbone/oneliner-docker/master/script/build_env.sh | bash
```