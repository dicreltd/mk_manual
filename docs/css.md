# カスタムCSS

## 設定

docs内にcssフォルダを作り、custom.cssを作成。

mkdocs.yml 内

	extra_css:
	    - css/custom.css

## CSS例

	.md-header {
	    background-color: #006633;
	    color: #fff;
	}
	.md-tabs__inner {
	    background-color: #006633;
	}
	nav.md-tabs {
	    background-color: #006633;
	}
	.md-typeset h1 {
		color:black;
	}
