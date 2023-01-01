# コードブロックの追加

## book.jsonの設定

```json
{
  "plugins": ["include-codeblock"]
}
```

以下を実行してプラグインをインストール

```bash
gitbook install
```

## 記述例

### HTML

```html
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta http-equiv="X-UA-Compatible" content="IE=edge">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Document</title>
</head>
<body>
  <h1>サンプル</h1>
  <p>テキストテキスト</p>
</body>
</html>
```


### PHP

```php
<?php

function sum($a, $b) {
   return $a + $b
}
```
