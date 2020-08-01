# markdown記法

## 強調

*hoge*  
**hoge**  
***hoge***  
~hoge~  
~~hoge~~

## リスト

* Item1
* Item2
* Item3

1. Item1
1. Item2
1. Item3

* [ ] Item1
* [x] Item2
* [ ] Item3

## 画像

![画像1](/img/image.png)

## リンク

[リンク](https://b1tblog.com/2019/10/08/vscode-markdown1/)

## ライン

---

## ブロッククォート

> hoge  
> fuga  
> piyo

## テーブル

|header1|header2|header3|
|:--|:-:|--:|
|hoge|fuga|piyo|
|hoge|fuga|piyo|

## インラインコード

This is `code` .

## コード

```javascript
const number = 123
console.log(number)
```

## 行番号

```javascript {.line-numbers}
const number = 123
console.log(number)
```

## 行強調

```javascript {highlight=2}
const number = 123
console.log(number)
```
