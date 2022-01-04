# studyHTMLAndCSS

## CSSセレクターについて
- CSSセレクターの種類

```
* {}    全ての要素
p {}    特定のタグ
.class {}
#id {}
[type="text"] {}    特定の属性 ※ a[href="https;//example.org"] => hrefが"https;//example.org"と一致する<a>要素
.container p {} HTMLの階層で指定
.container > span {}    階層が直下のもののみ
h1 ~ p {}   同じ親を持つ要素
h1 + p {}   隣り合っている要素
```