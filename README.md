# ukagakasay―伺かを喋らせるコマンド

## Usage example

![ukagakasay Hallo](https://raw.githubusercontent.com/wiki/TakagiY/ukagakasay/say_hallo.png)
![ls /usr -l | ukagakasay](https://raw.githubusercontent.com/wiki/TakagiY/ukagakasay/pipe_ls.png)

## What's this?

SSTP SEND 1.1を送って伺かを喋らせるコマンドです.
メッセージに含まれる改行はさくらスクリプトの改行コマンド`"\n"`に置換されます.
`"\"`および`"%"`は`"\\"`と`"\%"`にエスケープされます.

## Installation

* 必要なもの
    - [golang](https://golang.org/dl/)

* `ukagakasay`をインストールするコマンド

```console
go get github.com/TakagiY/ukagakasay
```

## Help

```console
$ ukagakasay --help
Usage: ukagakasay [options..] [message]

Options:
  -A, --address         SSTP Address (Default localhost)
  -P, --port            SSTP Port (Default 9821)
  -u, --unyuu           Speaking by partner

If message is not specified, pipe stdin.
    (In terminal, send eof by `Ctrl D`.)
```

