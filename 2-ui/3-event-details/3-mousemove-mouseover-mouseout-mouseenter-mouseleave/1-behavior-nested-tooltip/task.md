importance: 5

---

# 改善されたツールチップ動作

属性 `data-tooltip` を持つ要素にツールチップを表示する JavaScript を書いてください。

それは、タスク <info:task/behavior-tooltip> と似ていますが、ここでは注釈付き要素はネストできます。最も深くネストしたツールチップが表示されます。

例えば:

```html
<div data-tooltip="Here – is the house interior" id="house">
  <div data-tooltip="Here – is the roof" id="roof"></div>
  ...
  <a href="https://en.wikipedia.org/wiki/The_Three_Little_Pigs" data-tooltip="Read on…">Hover over me</a>
</div>
```

iframe での結果です:

[iframe src="solution" height=300 border=1]

P.S. ヒント: 同時に1つのツールチップだけ表示します。