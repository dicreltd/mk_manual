# ページのカスタマイズ

mkdocs.ymlでカスタマイズ用フォルダを指定。

	theme:
	  custom_dir: 'custom_dir'

そのフォルダ内にmain.html を配置

## 基本的なカスタマイズ

main.html でJinja2の表記を行う。base.htmlを継承し、ブロックに対しカスタマイズを行う。  
ブロック名は [公式サイト](https://www.mkdocs.org/user-guide/styling-your-docs/#overriding-template-blocks) 参照

	{% extends "base.html" %}

	{% block htmltitle %}
	  <title>Lorem ipsum dolor sit amet</title>
	{% endblock %}

## 元ソースを使ったカスタマイズ

元のhtmlは [Github内](https://github.com/squidfunk/mkdocs-material/tree/master/material/partials) にある。
このページから必要なブロックのソースをコピーしカスタマイズすると良い。

