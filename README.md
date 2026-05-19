# 透過 + 白フチジェネレーター

画像をアップロードし、背景を透過して、残った被写体に白い細フチ（px指定）をつけてPNG保存できる静的サイトです。

## GitHub Pages 公開手順

1. このリポジトリのデフォルトブランチを `main` にして push します。
2. GitHub の **Settings → Pages → Build and deployment** を開きます。
3. **Source** を **GitHub Actions** に設定します。
4. `main` ブランチに push すると、`.github/workflows/deploy-pages.yml` が実行されて公開されます。

公開URLは通常以下です。

- `https://<your-user-or-org>.github.io/<repo-name>/`

## ローカル確認

`index.html` をブラウザで直接開くだけで動作します。
