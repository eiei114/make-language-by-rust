# make-language-by-rust

Rustで実装されたシンプルなスタックベースのプログラミング言語インタプリタです。PostScriptライクな構文を持ちます。

## 機能

- 整数の算術演算（+, -, *, /）
- 条件分岐（if）
- 変数定義（def）
- スタック操作（pop, dup, exch, index）
- 関数定義と呼び出し
- 対話型実行モードとファイル実行モード

## 使い方

### ビルドと実行

```bash
cargo build
cargo run
```

### 対話型実行

```bash
cargo run
```

### ファイル実行

```bash
cargo run -- <filename>
```