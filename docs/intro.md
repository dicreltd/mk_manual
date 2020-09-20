# mkdocsインストール

pipenvで仮想環境を作る場合。

## インストール

    pipenv shell
    
    # 基本のmkdcosなら
    pipenv install mkdocs
    
    # マテリアル対応mkdcosなら
    pipenv install mkdocs-material
    
    # プロジェクト作成
    mkdocs new プロジェクト名
    cd プロジェクト名

## HTML生成（公開前など）
    mkdocs build

## 試したいとき（ローカルサーバ）
    mkdocs serve

