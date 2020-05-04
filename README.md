# 概要
- これは Gatsby + Netlify CMS によって構成されたブログサイトです

## URL
完成次第カスタムドメインにする
https://daijiroweb.netlify.app/

## ダッシュボード
https://daijiroweb.netlify.app/admin/

パスワード等は.envファイルおよび1passwordを参照。

# build コマンド

```
"clean": "gatsby clean",
"start": "npm run develop",
"build": "npm run clean && gatsby build",
"develop": "npm run clean && gatsby develop",
"format": "prettier --trailing-comma es5 --no-semi --single-quote --write \"{gatsby-*.js,src/**/*.js}\"",
"test": "echo \"Error: no test specified\" && exit 1"
```
