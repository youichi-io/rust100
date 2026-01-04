# rust100 🦀

Rustの基礎力を鍛えるための「Rust 100本ノック」です。

## 目的
- Rustの文法・標準ライブラリに慣れる
- 小さな問題を数多く解く
- 手を動かして理解する

## 構成

```text

rust100/
├─ README.md                  ← 全体説明・導線
├─ .gitignore
├─ problems/
│  ├─ README.md               ← 問題一覧・ナビゲーション
│  ├─ no001/
│  │  ├─ README.md            ← 問題文
│  │  ├─ explain.md           ← 解説（考え方）
│  │  ├─ Cargo.toml
│  │  └─ src/
│  │     ├─ main.rs           ← 自分の解答
│  │     └─ bin/
│  │        └─ ans.rs         ← 模範解答（cargo run --bin ans）
│  ├─ no002/
│  └─ ...

```



各ディレクトリは **独立したCargoプロジェクト**です。

## 実行方法

```bash
cd problems/no001
cargo run
```

## 各問題へのリンク

- [no001](problems/no001)
