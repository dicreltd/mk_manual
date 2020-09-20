# 公開

Netlifyでの公開例（GitHub経由）

## ファイルの作成
mkdocs.yml があるフォルダに以下のファイルを置く

### runtime.txt

Pythonのバージョン

	3.7

### requirements.txt

	mkdocs
	mkdocs-material

### netlify.toml

Netlifyでのコマンドと公開元指定（Netlyfyでの設定でも出来るが初期設定として作っておくと楽）

	[build]
	command = "mkdocs build"
	publish = "site"

## GitHubにプッシュ

siteフォルダはアップロードしないので以下を作成

### .gitignore
	site/

これらとMkDocsファイルでgitリポジトリを作り、GitHubにpushする。
あらかじめ、GitHubでリポジトリを作っておき

	git init
	git add .
	git commit -m "first"
	git remote add origin 自分のGitHubリポジトリURI
	git push -u origin master

## Netlifyで公開

- GitHubアカウントでSign Up
- New site from Gitを選ぶ
- GitHubクリック　認証し再びGitHubクリックしリポジトリ選択
- 設定確認しDeploy siteクリック
- Getting startedで「１ Your site is deployed」が終わるとアクセス可能
- 独自ドメイン設定する場合には 2 Set up custom domainをクリック（後で設定も可能）

## 更新

GitHubにプッシュすると、自動的にNetlifyで公開される。

