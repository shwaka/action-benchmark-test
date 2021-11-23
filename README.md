予め `gh-pages` ブランチを用意しておく:
```bash
git checkout --orphan gh-pages
git commit --allow-empty -m "Initialize gh-pages branch" # ドキュメントには書いてなかったけど必要？
git push origin gh-pages:gh-pages
```
