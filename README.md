# create-browser
作って学ぶブラウザの仕組み学習用

## サポートページ
https://lowlayergirls.github.io/wasabi-help/browser/

## メモ生成コマンド

- 目的: `memo/MEMO_TEMPLATE.md` をコピーし、`memo/{YYYYMMDD}.md` を作成します。
- 前提: Dev Container 再読み込み後、`/workspace/bin` が PATH に追加されます。

### 使い方

```bash
# 指定した日付で作成（YYYYMMDD）
memo-new 20250904

# 省略時は当日の日付で作成
memo-new
```

### 挙動
- 既に同名ファイルがある場合はエラー終了します。
- テンプレートは `memo/MEMO_TEMPLATE.md` を使用します。