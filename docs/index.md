# MkDocsマニュアル

Python製静的サイトジェネレータ MkDocsの使い方

## 静的サイトジェネレータとは？

Wordpressのようなアクセス時にHTMLを生成するのが動的なサイトジェネレータ。

それに対し、静的サイトジェネレータはあらかじめマークダウンファイルなどからHTMLを生成しておくもの。

生成される物は通常のHTMLファイルなので、サーバに負荷も掛けずセキュリティの問題も無い。

ただし、ファイルを更新したときにツールを使ってHTMLを生成しなければならない。


## 生成の自動化
GitHub ActionsやNetlifyなどの、CI（Continuous Integration、継続的インテグレーション）CD（Continuous Delivery、継続的デリバリー）機能によってHTML生成を自動化することができる。

具体的にはGitHubにプッシュするだけで生成できる。

[導入](./intro/)

[設定](./option/)

[書き方](./cont/)

