# rs-template
Rsut Template



## Prepare

### Install cargo generate

cargo generate 是一个用于生成项目模板的工具。它可以使用已有的 github repo 作为模版生成新的项目。

```bash
cargo install cargo-generate
```

#### Example

```bash
cargo generate edvcc/rs-template
```



### Install cargo deny

Cargo deny 是一个 Cargo 插件，可以用于检查依赖的安全性。

```bash
cargo install --locked cargo-deny
```

#### Example

```bash
cargo deny init
```



### Install git cliff

git cliff 是一个生成 changelog 的工具。

```bash
cargo install git-cliff
```

#### Example

```bash
git cliff --init keepachangelog
```



### Install cargo nextest

cargo nextest 是一个 Rust 增强测试工具。

```bash
cargo install cargo-nextest --locked
```

