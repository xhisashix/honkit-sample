# Hintを導入する方法

## プラグインのインストール

```json
{
  "plugins": ["hint"]
}
```

## 各装飾の記述方法

### ヒント

```text
{% hint style='info' %}
ヒント：テキストテキスト
{% endhint %}
```

{% hint style='info' %}
ヒント：テキストテキスト
{% endhint %}

### tips

```text
{% hint style='tip' %}
tip: テキストテキスト
{% endhint %}
```

{% hint style='tip' %}
tip: テキストテキスト
{% endhint %}

### 警告

```text
{% hint style='danger' %}
警告: 警告メッセージ
{% endhint %}
```

{% hint style='danger' %}
警告: 警告メッセージ
{% endhint %}

### アラート

```text
{% hint style='working' %}
working: アラートメッセージ
{% endhint %}
```

{% hint style='working' %}
working: アラートメッセージ
{% endhint %}
