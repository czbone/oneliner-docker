# 1行でDockerサーバ環境構築
サーバに`root`ログインし１行のコマンドを実行するだけでDockerのサーバ環境が構築できるスクリプトです。  

## 対象OS
- CentOS 8, CentOS 7

## ライセンス

[![MIT license](https://img.shields.io/badge/License-MIT-blue.svg)](https://lbesson.mit-license.org/)

# 内容
Ansibleのローカル実行で、Dockerに必要なモジュールを含めてDocker環境を構築します。

## 主なインストールモジュール

- docker-ce
- docker-ce-cli
- docker-compose

# 使い方
新規にOSをインストールしたサーバに`root`でログインし、構築したい環境のスクリプトを実行します。
完了後は一旦サーバを再起動してください。

