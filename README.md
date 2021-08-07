# pytest_cov_github_pages

## 概要

- pytest の coverage を GitHub Pages にデプロイする
  - https://yamap55.github.io/pytest_cov_github_pages/

## 注意

- GitHub Pages は設定済みであることを想定
  - [Configuring a publishing source for your GitHub Pages site](https://docs.github.com/en/pages/getting-started-with-github-pages/configuring-a-publishing-source-for-your-github-pages-site)
- `gh-pages` ブランチにはあらかじめ `index.html` を配置しておく必要がある
- 見るべきファイルは以下のみで良いと思われる
  - https://github.com/yamap55/pytest_cov_github_pages/blob/master/.github/workflows/pytest.yml
