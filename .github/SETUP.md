
# 初期設定（SMTrustGroup Project #2 固定版）

このテンプレートは **https://github.com/orgs/SMTrustGroup/projects/2** に自動追加するよう設定済みです。

## 1. Discussions を有効化
- Settings → General → Features → Discussions にチェック
- カテゴリを `Q&A` / `アイデア` / `お知らせ` で作成

## 2. ラベル同期
- Actions → `Sync Labels` を **Run workflow**

## 3. 動作確認
- Issue を1件作成し、**SMTrustGroup Project #2** に自動追加されることを確認

> もし他の Project に切り替える場合は `.github/workflows/add-to-project.yml` の `project-url` を変更してください。
