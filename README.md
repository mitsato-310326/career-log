# Career Log

日々の技術的な学び・成果を記録するログ。
「日記」ではなく、後から自分の成長・技術スタック・問題解決力を振り返れる記録として運用している。

## 構成

- [`work/projects/`](./work/projects) — 仕事(レビュー済み・公開OKのもののみ)
- [`work/_staging/`](./work/_staging) — 仕事の下書き(**gitignore対象、絶対にpushされない**)
- [`personal/projects/`](./personal/projects) — 個人開発・自主学習(基本そのまま公開)
- [`summaries/`](./summaries) — 月次まとめ

## 運用フロー

### 個人開発(personal/)
そのまま `personal/projects/<name>/README.md` に随時追記して公開。レビュー不要。

### 仕事(work/)
公開可否の判断を挟むため、2ステップにする。

1. **下書き**: `work/_staging/<project>.md` に自由に書く(社名・機密情報含めてOK、ここはpushされない)
2. **公開判断**: 公開して問題ない内容だけを選び、社名や固有情報を書き換えつつ `work/projects/<project>/README.md` にコピーする
3. **commit & push**: `work/projects/` 配下だけがリポジトリに反映される

`work/_staging/` は `.gitignore` で除外されているので、うっかり下書きをpushしてしまう事故を防げる。

## 技術スタック(随時更新)

| カテゴリ | 技術 |
|---|---|
| 言語 | C, C++ |
| 環境 | WSL, Linux, Ghostty, Zellij |
| 分野 | レイトレーシング, 3Dグラフィックス数学(クォータニオン等) |
