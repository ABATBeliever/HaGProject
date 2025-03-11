# HSP at Github (HaG) for 3.6

HaGはHSPのファイルのビルドをGithub上で行うシステムです。

## 動作条件

Github上で動作するため、フォークが必要です。Githubアカウントを準備

### 実行方法

１ このプロジェクトをクローン、またはダウンロードして自分のリポジトリにアップロード

２ projectsフォルダ内にhspのファイルをいれ、buildフォルダ内にビルドされるzipに同封したいデータ(ビルドに関連しない画像データやtxtなど)を入れる

３ Actions→HaGの実行 より、GithubActionsを実行する

４ ビルドされたzipで完成

### 依存環境・ライセンス

詳細については、/docs/hag.txtをご覧ください。