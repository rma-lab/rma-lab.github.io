# rma-lab.github.io

rma-lab の玄関ページ https://rma-lab.github.io/ 。takayuki1997.github.io と同じ作り（Jekyll、GitHub Actions でビルド）。

- 内容の編集は `index.md`。サイト名・説明は `_config.yml`。
- 検索エンジン・AI 向け: `jekyll-seo-tag`（meta/JSON-LD）・`jekyll-sitemap`（sitemap.xml 自動生成）・`robots.txt`・`llms.txt`。
- ローカル確認: `bundle install && bundle exec jekyll serve`（無くても push すれば Actions がビルドする）。
