# yobimori_developer_manual

yobimori開発者のためのマニュアルです。
https://nanofreaks.github.io/yobimori_developer_manumal/

## 対象読者

- yobimoriプロダクトに関わるエンジニア
- yobimoriプロダクトを運用する人

## この資料の編集方法

### Build Setup

For detailed explanation on how things work, check out [gitbook docs](https://github.com/GitbookIO/gitbook/blob/master/docs/setup.md)

```console
git init
```

Clone nanoFreaks/yobimori_developer_manual

```console
git clone https://github.com/nanoFreaks/yobimori_developer_manumal.git

npm install gitbook-cli -g
```

Preview and serve your book using:

```console
gitbook serve
```

### 編集後、pushする前に

Github page refers ./docs.
Build the static website before push your files using:

```console
gitbook build . docs
```