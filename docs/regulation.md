---
layout: default
title: コーディング規約
---

# コーディング規約

コードを書く上で最低限守るべきコーディング規約を挙げました。  
課題を提出するときはこの規約を守るようにしてください。

## JavaScript

* インデントはスペース2つにしてください
* 文字列を表す引用符はシングルクォートを使用してください
* 変数宣言には必ずvarを付けて宣言するようにしてください
* 文末には必ずセミコロンを付けてください

```javascript
// 良い例
var foo = 'テキストデータ';

// 悪い例
bar = "テキスト"
```

* 変数名、メソッド名はキャメルケースを使用してください

```javascript
// 良い例
var selectedText;
function getEncodeUrl(){
  //
}

// 悪い例
var selectedtext;
get_encode_url();
```

* ソースコードの意図がわかるようにコメントを記述してください  
プログラムを見ただけでわかるコメントや他人から見て意味がわからないコメントはつけないようにしましょう

```javascript
// 良い例

// 割引率を算出する
discountRate = (price - díscounPrice / price) * 100;


//悪い例
// 値を代入する　　
var count = max - 1;
// 配列を宣言する
var array = [];
// とりあえず代入しておく
var newText = text;
```

* `document.write`は使用しないでください

---
その他の規約や、なぜ規約を守らないといけないか、については[Google JavaScript Style Guide 和訳 — Google JavaScript Style Guide 和訳](http://cou929.nu/data/google_javascript_style_guide/)に載っていますので一読することをお薦めします

## HTML

* HTML5のドキュメントタイプ宣言を使用してください
* metaタグのcharsetには必ずUTF-8を使用してください

例

```html
<!DOCTYPE html>
<html>
<head>
  <meta charset="UTF-8">
  <title>Document</title>
</head>
<body>

</body>
</html>
```
