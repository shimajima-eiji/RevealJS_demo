# RevealJS_demo

## 閲覧できない環境について
同じchromium系のブラウザでも見れたり見れなかったりしたので、閲覧環境に指定がある可能性が高い。  
おそらく拡張機能？か何かの都合でうまく表示できなくなっている事があると考えられる。

## 作り方
1. VSCodeにvscode-revealを入れる
2. 所定のフォーマットでマークダウンを作成する
3. 「Shift+Ctrl(Command)+P」キー：「Export in HTML」でファイルを作成する

### 所定のフォーマット
最もシンプルな例は[sample.md](https://github.com/shimajima-eiji/RevealJS_demo/blob/main/sample.md)を参照。

- [公式](https://github.com/hakimel/reveal.js/)
- [参考](https://zatsugaku-engineer.com/html-css-javascript/reveal-js)

## 注意
revealJSはいろいろな方法で使われるが、環境によっては動いたり動かなかったりする。  
たとえば、当方の環境ではreveal-ckはうまく使えなかったため、作り方の方法で作成している。
