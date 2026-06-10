# エンジニア向けAI活用資料

エンジニア・プログラマー向けに、AIを実務でどう使うかを整理した資料です。

一般的な「AIとは何か」ではなく、既存の開発現場で発生する仕事に沿って扱います。

- 既存コードを読む・理解する
- 開発する・変更する
- テスト・検証する
- レビュー・品質確認を見直す
- 運用保守する
- 安全に使うためのルールを決める

## この資料の位置づけ

この資料は、すべての開発をAIに任せるための資料ではありません。

AIを使った開発が増えている一方で、既存の開発現場には、顧客コード、社内ルール、レビュー、運用保守、契約、セキュリティ、責任分担などが残っています。

そのため、この資料では、現実の制約がある開発現場でAIをどう実務に入れるかを整理します。

特に想定しているのは、以下のような現場です。

- SES
- フリーランス
- 受託開発
- 既存システムの改修・保守
- 顧客環境や社内ルールに合わせて開発する現場

## まず読む資料

全体像を知りたい場合は、まず次を読んでください。

- [00_index.md](./00_index.md): 全体インデックス、資料の位置づけ、章ごとの読み方
- [08_summary_and_talk_track.md](./08_summary_and_talk_track.md): 共有会や対象者別の説明ルート

## 章一覧

| 知りたいこと | 読む資料 |
|---|---|
| AIへの頼み方を整理したい | [01_ai_request_basics.md](./01_ai_request_basics.md) |
| 既存コードの読み方を知りたい | [02_reading_existing_code.md](./02_reading_existing_code.md) |
| 実装前後やユニットテストでAIを使いたい | [03_development_workflow.md](./03_development_workflow.md) |
| テストケース作成や検証でAIを使いたい | [04_testing_workflow.md](./04_testing_workflow.md) |
| コードレビューやレビュー省略の考え方を整理したい | [05_review_redesign.md](./05_review_redesign.md) |
| 運用ログ、障害、問い合わせ調査でAIを使いたい | [06_operations_maintenance.md](./06_operations_maintenance.md) |
| 社内利用ルールや注意点を確認したい | [07_practical_rules.md](./07_practical_rules.md) |
| 許可AIが使えない環境での検索や汎化を確認したい | [07_supplement_masking_generalization.md](./07_supplement_masking_generalization.md) |
| 共有会や対象者別の説明ルートを作りたい | [08_summary_and_talk_track.md](./08_summary_and_talk_track.md) |

## 関連する資料との分け方

AIを全く知らない人向けの入門資料、説明会用スライド、個別ツールの導入手順は、別資料として扱います。

この資料では、エンジニア向けに、既存コード理解、開発、テスト、レビュー、運用保守など、実務の仕事単位でAI活用を整理します。
