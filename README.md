# ukagakasay ―伺かを喋らせるコマンド

![ukagakasay Hallo](wiki/say_hallo.png)

![ls /usr -l | ukagakasay](pipe_ls.png)

## help

```console
$ ukagakasay --help
Usage: ukagakasay [options..] [message]

Options:
  -A, --address         SSTP Address (Default localhost)
  -P, --port            SSTP Port (Default 9821)

If message is not specified, pipe stdin.
    (In terminal, send eof by `Ctrl D`.)
```

