# MkDocsインストール

pipenvで仮想環境を作る場合。

## インストール

    pip install mkdocs
    
    # マテリアル対応mkdcosなら
    pip install mkdocs-material
    
    # プロジェクト作成
    mkdocs new プロジェクト名
    
    cd プロジェクト名

## HTML生成（公開前など）
    mkdocs build

## 試したいとき（ローカルサーバ）
    mkdocs serve

ブラウザでhttp://127.0.0.1:8000 にアクセス
