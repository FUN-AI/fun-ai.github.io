# FUN AI Blog

## 使用テーマ

https://github.com/zwbetz-gh/cayman-hugo-theme

## 編集方法

### ブログ投稿

```
hugo new posts/nannka-post.md
```

で `content/posts` 配下にMarkdownファイルが作られるのでそれを編集する。

### 固定ページ

`content/about/index.md` や `content/recruit/index.md` を編集する。

## デプロイ方法

1. ページを追加したらmainブランチにpushする。
1. (二回目以降) publicディレクトリを削除する。
1. その後、 `publish_to_ghpages.sh` を実行する。