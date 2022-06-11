# create custom devcontainer

## create

.devcontainerに移動して、build_image.shを実行すると
oracle_linuxのdevcontainer用のImageが作成され、
docker registryにpushされます。
変数の値をいじって調整してください。

```bash

docker_registry=katsutoshiotogawa
docker_image_name=oracle
variant=8.6
```

oracleやredhatなど再配布禁止のImageやソフトを使っている場合は
private レポジトリにpushすること。

if you using oracle licence

## reference

[devcontainer repo](https://github.com/microsoft/vscode-dev-containers)

[hint](https://ianmitchell.dev/blog/creating-devcontainers-for-vs-code-and-github-codespaces)
