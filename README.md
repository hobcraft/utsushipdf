# utsushipdf-pages（公開ページ用）

Utsushi PDF（macOS アプリ）のサポートとプライバシーポリシー。
GitHub Pages で `https://hobcraft.github.io/utsushipdf-pages/` に公開する。

- サポート: `https://hobcraft.github.io/utsushipdf-pages/support/`
- プライバシーポリシー: `https://hobcraft.github.io/utsushipdf-pages/privacy/`

**このリポジトリは公開される。アプリのソースや申請メモを入れないこと。**
ソースと内部資料は `~/Projects/utsushi-pdf/`（非公開）にある。SeiriBox と同じ構成。

## 公開の手順

GitHub 側に `hobcraft/utsushipdf-pages`（**public**。無料プランの Pages は公開リポジトリのみ）が必要。

```bash
cd ~/Projects/utsushipdf-pages
git init
git add -A
git commit -m "初回コミット"
git remote add origin git@github.com:hobcraft/utsushipdf-pages.git
git push -u origin main
```

GitHub の Settings → Pages で Source を `main` / `/ (root)` にする。公開まで数分かかる。

公開したら、2つの URL をブラウザで開いて表示されることを確認する（404 だと審査で落ちる）。
