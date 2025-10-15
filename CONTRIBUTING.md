# CONTRIBUTING

ようこそ {{PROJECT_NAME}} へ。Pull Request を歓迎します。

## ブランチ戦略
- `main`: リリース／公開用
- `feature/day-XX-title`: Dayごとの作業ブランチ（例: `feature/day-01-api-basics`）

## 新しい Day の追加手順
1. ブランチ作成: `feature/day-XX-title`
2. 対象フォルダ（例: `01_api-automation/day01`）に README とコードを追加
3. README には「目標 / 手順 / 実行方法 / 参考リンク」を記載
4. 動作確認（ログ or スクショ）を添付
5. PR 作成 → チェックリストに従ってレビュー

## PR チェックリスト
- [ ] README に手順があり、初見で再現できる
- [ ] `main.py` が動作する（最小でも `print()` など）
- [ ] 依存関係ファイル（例: `requirements.txt`）があれば追加
- [ ] {{YEAR}} / {{OWNER}} / {{REPO}} などの置換漏れがない

## ライセンス
本テンプレートは MIT ライセンスです（`LICENSE`）。
