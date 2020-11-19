# amATO
## プレゼンテーションのもう一つの選択肢

### 要件
- Markdown**x**CSSでリッチかつお手軽にプレゼン資料を作りたい
- Markdownで書いた資料をCLIでHTMLに変換できるような
    - HTMLとは言ってもスライドめくりのUIなどは一般のプレゼンツールとほとんど変わらないよう
- 適用するCSSテンプレートを切り替えることでお手軽にデザインも切り替えたい

### 技術要素
- npmモジュールとして公開
- `npm install -g` で誰でも利用可能に
- Markdownの独自記法を作る
    - <<.hoge#fuga>>でクラスやIDが適用できたり
    - [[rocket]]とかでfontawesomeに変換されたり