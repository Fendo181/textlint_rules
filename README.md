## textlint_rule

### Getting Started

既に`npm`、`node`、`textlint`がインストールされている方は以下のコマンドだけで大丈夫です。

```
npm install --save-dev
npx textlint ./text/index.md
```

#### Setup

```
npm init --yes
npm install --save-dev textlint
npm install --save-dev textlint-rule-no-todo
npx textlint --init
```

セットアップが完了後は以下のコマンドを実行してtextlintで文章を校正してください。

```
npx textlint ./text/index.md
```

### Rules

- [hata6502/textlint-rule-ja-simple-user-dictionary](https://github.com/hata6502/textlint-rule-ja-simple-user-dictionary)
  - シンプルなユーザー辞書をもとに校正するtextlintルール。
- [ textlint-ja/textlint-rule-preset-ja-spacing](https://github.com/textlint-ja/textlint-rule-preset-ja-spacing/tree/master/packages/textlint-rule-ja-space-around-code)
  - インラインコードの周りをスペースで囲むかどうかを決めるtextlintルール
- [textlint-ja/textlint-rule-preset-ja-technical-writing](https://github.com/textlint-ja/textlint-rule-preset-ja-technical-writing#%E3%83%AB%E3%83%BC%E3%83%AB%E4%B8%80%E8%A6%A7)
  - 技術文書向けのtextlintルールプリセット



### 参考

- [textlint · The pluggable linting tool for text and markdown](https://textlint.github.io/)
- [Collection of textlint rule · textlint/textlint Wiki](https://github.com/textlint/textlint/wiki/Collection-of-textlint-rule#rules-japanese)
