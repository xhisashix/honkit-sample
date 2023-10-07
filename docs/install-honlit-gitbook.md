# 導入手順

## 1. GitBook のインストール

```bash
npm install honkit
```

## 2. GitBook の初期化

```bash
honkit init
```

## 3. GitBook の起動

```bash
honkit serve
```

## 4. GitBook のビルド

```bash
honkit build
```

## gitbook.json の設定

```json
{
  "title": "HonKit",
  "author": "HonKit",
  "description": "HonKit",
  "language": "ja",
  "root": "./docs",
  "structure": {
    "readme": "README.md"
  },
  "plugins": [
    // 必要なプラグインを追加
  ],
  "pluginsConfig": {
    // プラグインの設定
  },
}
```

### プラグインの探し方

npm で公開されているプラグインは、以下のサイトで検索できます。

[https://www.npmjs.com/](https://www.npmjs.com/) の検索窓に `gitbook-plugin-` と入力すると、GitBook で利用できるプラグインが表示されます。

また、honkit 専用のプラグインは、`honkit-plugin-` で検索すると表示されます。
