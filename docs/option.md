# 設定

mkdocs.yml内で[様々な設定](https://squidfunk.github.io/mkdocs-material/setup/changing-the-colors/)が可能。

## テーマ
検索を有効にするため、languageを設定すること。  
patteのprimaryで基本色を指定。
[公式ページ](https://squidfunk.github.io/mkdocs-material/setup/changing-the-colors/)  参照

	theme:
	  name: material
	  language: 'ja'
	  icon:
	    logo: material/book-open
	    repo: fontawesome/brands/git-alt 
	  features:
	    - tabs 
	  palette:
	    primary: green

## ページ順の変更
上のタブに表示するには、index.md以外は階層構造を作らないと表示されない。

    nav:
    - MkDocs: index.md
    - 導入:
      - インストール: intro.md
      - 設定: option.md
    - 書き方:
      - 書き方: cont.md


## フッタのSNSアイコン

	extra:
	  social:
	    - icon: fontawesome/brands/twitter
	      link: https://twitter.com/skohara
	    - icon: fontawesome/brands/facebook
	      link: https://www.facebook.com/dicre
	    - icon: fontawesome/brands/github
	      link: https://github.com/dicreltd


## その他

	site_name: サイト名
	site_url: サイトURL
	site_description: サイト説明（meta description）
	site_author: skohara'@dicre.com'（フッタに表示）
	site_favicon: favicon.ico
	copyright: 著作権表示（フッタに表示）
	google_analytics: GOOGLEアナリティクス
