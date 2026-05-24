# hello-devbox

[![Built with Devbox](https://www.jetify.com/img/devbox/shield_moon.svg)](https://www.jetify.com/devbox/docs/contributor-quickstart/)

1. nixのインストール

https://github.com/DeterminateSystems/nix-installer

```sh
curl -fsSL https://install.determinate.systems/nix | sh -s -- install
```

2. devboxのインストール

https://www.jetify.com/docs/devbox/installing-devbox

```sh
curl -fsSL https://get.jetify.com/devbox | bash
```

## Start

```sh
$ devbox shell # Devboxシェル内で開発する
$ start        # startコマンドでサーバー起動できるようにdevbox.jsonで設定
$ exit         # Devboxシェルの終了
```