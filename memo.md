- index.htmlからどういう参照をしてrustの内容を表示させているのか
    1. staticのindex.html
    2. js/index.js
    3. pkg/index.js
    4. src/lib.rs
    であってる？

- .d.tsって何
    - 型定義ファイル
    - 複数ファイルで利用したい型を記述
- cargoはnpmとかyarnと同じ立ち位置？
    - Rustの公式パッケージ管理ツール
- tomlって何
    - json,yamlなどと同様の設定ファイルなどの記述に用いられるフォーマット
    - 特徴: 必要な知識が最小、簡潔に列挙する形式
- context, unwrapってなんだ
    - ?
- #[wasm_bindgen(start)]でメインのエントリポイントを作成？
    - wasm.__wbindgen_start();で呼び出す、上記ので呼び出されるがわを定義？