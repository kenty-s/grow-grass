エンジニア学習README

日々のエンジニア学習を綴るREADME

1/24~ Udemy (HTML,CSS)
2/6~  RUNTEQ入学
4/14~ 学習README始動

R7
🌸4/14(5ポモ,2.5H)　Rails基礎、githubの草生やしを覚える
☞学習：header,footer
　課題：footerが反映されない
　原因：footerのみrender記述漏れ(application.html.erb)

🌸4/15(6ポモ,3H)　Rails基礎
☞学習：ユーザー登録機能実装(gem 'sorcery')
　課題：適切な言語、コードを理解出来ていない(浮かんでいない)
  メモ：GemはRailsのパッケージ。gem 'sorcery'はユーザー登録、ログインなどに必用な最低限のファイルを作成

🌸4/16(6ポモ,3H)　Rails基礎
☞学習：ユーザー登録機能実装(ユーザー登録、ログイン)
  参考：[Rails]ユーザ登録・ログイン　2/20
  https://zenn.dev/redheadchloe/articles/8e3b3b4eb358a2#bcrypt%E3%82%92%E3%82%A4%E3%83%B3%E3%82%B9%E3%83%88%E3%83%BC%E3%83%AB%E3%81%99%E3%82%8B

🌸4/17(7ポモ,3.5H)　GitHub/Rails基礎
☞学習：草の生やし方について。Railsの基本。
　課題：草が生えない
　原因：defaultがmainとなっていた
　メモ：
　ルーティング…URLとコントローラーをつなぐ案内係
　コントローラー…データを受け取って処理し、ビューに渡す指令係
　ビュー…ユーザーに見せるHTMLを作る
　モデル…データベースでやり取りする頭脳
  マイグレーションファイル…データベースの設計図
  (テーブル作成、カラムを追加・変更・削除等)