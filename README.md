# Minecraft World Downloads

MinecraftワールドをGitHub PagesとGitHub Releasesで配布するためのリポジトリです。

現在は公開前の準備状態です。リポジトリは非公開、`v1.0.0` Releaseは下書き、GitHub Pagesは無効になっています。

## 構成

- `docs/index.html`: 配布ページ本体
- `docs/images/`: 建物プレビュー8点と背景1点
- `v1.0.0` Release: 統合版8件、Java版8件

配布ページの建物名と説明は日本語で表示し、Release AssetはURL互換性を優先した英数字名にしています。

## 公開前チェック

- `v1.0.0` Releaseの16ファイルと、配布ページの16ボタンが一致することを確認する。
- リポジトリを公開設定にし、`main` ブランチの `/docs` をGitHub Pagesの公開元に設定する。
- 下書きReleaseを公開し、実際のダウンロードを確認する。
- GitHubプロフィールの公開メールが無効で、コミットメールが `noreply` 設定であることを確認する。
- プレビュー画像、HTML、ワールドデータに個人情報やローカルパスが含まれていないことを確認する。
