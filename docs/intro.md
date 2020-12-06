# MkDocsインストール

## インストール

    pip install mkdocs
    
    # マテリアル対応mkdcosなら
    pip install mkdocs-material
    
    # プロジェクト作成
    mkdocs new プロジェクト名
    
    cd プロジェクト名

## 表示してみたいとき（ローカルサーバ）

    mkdocs serve

ブラウザでhttp://127.0.0.1:8000 にアクセス

## HTML生成

本番時のHTML生成。

    mkdocs build

siteに生成される。
