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

🌸4/18(6ポモ,3H)　Rails基礎
☞学習：ユーザー登録の理解
　感想：コードの理解度確認にAIを活用したが見込みが凡そあっており達成感○
　　　　しかし、英語を知っていることありきだなと改めて実感。

🌸4/19(15ポモ,7.5H +HR1.5H)　WEB技術入門
☞学習：WEB技術入門の復習
　感想：スクールのHRでの学習に紐づく内容復習
　　　　WEBについて無知を実感。明日も復習を予定

🌸4/20(0ポモ,0H)　いちご狩り🍓
☞感想：Web予約対応されているのに、当日50組ほどの予約内容を全て紙に手書き転記されていた。せっかくのWeb対応も現場の使い手が
追いつかなければ効率化に繋がらないのか…

🌸4/21(8ポモ,4H)　WEB技術入門
☞学習：WEB技術入門の復習
　感想：前日をリフレッシュにあてたので、4:00起床で学習＋夜寝かしつけ後の学習。(HTTP通信について学習）

🌸4/22(3ポモ,1.5H)　WEB技術入門
☞学習：本日は4:50起床。早起き型にシフトしたいがなかなか起きれない…

🌸4/23(4ポモ,2H)　WEB技術入門
☞学習：Webアプリについて
　　　　●アーキテクチャスタイル：Webアプリやシステム設計の基本方針
　　　　●３層アーキテクチャ：
　　　　　１．プレゼンテーション層(ユーザーとアプリのインターフェス)
　　　　　２．アプリケーション層(ビジネスロジック)
　　　　　３．データ層(データ保存と取得。)
　　　　●MVC：
　　　　　Model(アプリのデータとビジネスロックの管理)、View(データの表示)、Controller(ModelとViewをつなぐ)
       ●クッキーとキャッシュの違い
       　クッキー：自ら入力した情報
       　キャッシュ：閲覧したページの画像やファイルを保存

🌸4/24(8ポモ,4H)　WEB技術入門
☞学習：AM 5:00~6:30
  JSON…軽量データ交換フォーマット
  https://qiita.com/skm_bnn/items/ecf3d0fe1188e666d079
  (ex)
  {
  "user": {
    "username": "JohnDoe",
    "age": 30,
    "email": "john@example.com"
  },
  "address": {
    "postalCode": "100-0001",
    "prefecture": "Tokyo",
    "city": "Chiyoda"
  }
}

☞学習：PM 8:00~9:00
       【スクールイベント：はじめてのインフラ入門】
       ・可用性(アベイラビリティ)…システム・サービス
       を継続して利用できる度合・能力
       ・拡張性(スケーラビリティ)…サーバー台数増減や性能上げ下げ
       ・スクレイピング…ウェブサイトからデータを自動抽出
       ・SSH…遠くのサーバーから安全に遠隔操作。
             特定のIPアドレスでしかアクセスできない等も可能。
       PM 9:00~10:00
        　スクール同期アウトプット会(初回)
        ・進捗報告やGitHub共有、勉強の進め方など
        ・次回4/29(火)
       PM 10:00~10:30　WEB技術入門

🌸4/25(2.5H) スクール懇親会　＠Discord
　　　　・他期との交流(勉強方法、現状報告等)

🌸4/26(15ポモ,8H ※未計測ポモ多)AM WEB技術入門,PM Rails基礎
☞学習：セキュリティ関係
　　　　〈セキュリティの基本要素〉
　　　　・機密性：情報が許可されたユーザーだけアクセスできる
　　　　・完全性：情報が正確で安全であり、改ざんされていないことを保証
　　　　・可用性：必要な時に情報にアクセスできる
　　　　〈攻撃手法〉
　　　　・ブルートフォース攻撃：可能なパスワード全組み合わせを試す総当たり攻撃
　　　　・SQLインジェクション：悪意あるSQLコードを入力フォーム等に挿入し、DBに不正操作を行う。非公開データの閲覧等。
　　　　・XSS：悪意あるスクリプトをWebページに埋め込みユーザーのブラウザで実行。セッション情報やCookieなど盗む。
　　　　・CSRF:ユーザーに意図しないリクエストを送信させる。権限の悪用。
　　　　・セッションハイジャック：セッションIDを盗み、セッションを乗っ取る。

       ・Rails ファイルあれこれ
       　config(configure:設定する、構成する)
         ☛ Railsアプリ全体の設定管理場所(ルールや初期設定を書く)
         form_with
         ☛ 自動的なURL生成。Ajax対応(リロードせず一っ部だけ更新する技術)
         not_authenticated
         ☛ ユーザーが認証(ログイン)していない時に呼び出されるメソッド
☞Rubyイベント：急遽参加。Ruby、Railsの学び方(覚えるより調査方法を抑える)を知れたことが大収穫
☞アウトプット会予定：4/29 21:00~に決定。Railsの流れについてまとめてアウトプットしたい。

🌸4/27(5ポモ,2.5H)　片道1.5Hの遠出後のため◎
☞学習：Railsのファイル相関まとめ(Notionへ記述)　
※同期アウトプット会で報告予定
ステップ１：アプリ本体(/app)に親しむ
ステップ2：ルーティングの意味を知る
ステップ3：データベースに慣れる（db/）
ステップ4：設定ファイルに触れる
ステップ5：テストコード（spec/）とその他のサポート達

🌸4/28(6ポモ,3H) 同期イベント立ち上げ
☞学習：Rails基礎諸々
　　　　同期イベントを画策中

🌸4/29(2ポモ,4H) 同期アウトプット会(参加者8名)
☞学習：アウトプット会
　　　　・マークダウン記法について
　　　　https://www.genspark.ai/autopilotagent_viewer?id=afab9676-f374-45f5-8c2a-45d9d9549c97
　　　　・すーさん:基本情報
　　　　https://www.youtube.com/@kihonzyouhou

🌸4/30(7ポモ,3.5H)
☞学習：Rails基礎
　　　　・未ログイン画面への遷移
　　　　　久々のプルリクエスト。このREADMEをプッシュする方法と同じながらやり方が不安であったので、やはり継続して触ることが大事なんだと痛感。
　　　　・READMEでの学習日誌であるとマークダウン記法を覚えられないため、改善策も考えるべきだろうか、、、

🎏5/1(3ポモ,1.5H)
☞学習：Rails基礎　
　　　　ログアウト機能実装に苦戦中
　　　　エラー：Unable to find link or button "ログアウト"

🎏5/2(3ポモ,1.5H)
☞学習：Rails基礎　ログアウト機能実装
　　　　遂ににクリア
　　　　変更しなくて良い箇所を変更しており、関係のない箇所を追加修正していたため、エラーの連続であったことが発覚。
　　　　シンプルに試行することを心がける。

🎏5/3(7ポモ,3.5H)
☞学習：i18n 多言語化

| コマンド                     | なぜ必要か                            |
| ------------------------ | -------------------------------- |
| `bundle install`         | Gem を追加したら必須（gem をインストール）        |
| `docker compose restart` | Rails の起動時にしか読み込まれない設定・Gemの反映に必要 |
| `bin/dev`                | サーバーを起動し直すために必要（再起動後に再度立ち上げ）

`docker compose restart`の必要性について
| チェック項目                                     | 再起動が必要か？ | 補足                               |
| ----------------------------------------------- | ---------------| -------------------------------- |
| `.env` ファイルを変更した                         | ☑ 必要        | 環境変数の再読み込みのため                    |
| `config/database.yml` などの設定ファイルを変更した | ☑ 必要        | Rails などは起動時にしか読み込まない            |
| Docker コンテナがフリーズ・応答しない              | ☑ 必要        | リセットで直る場合あり                      |
| Rails や Webサーバー（Pumaなど）が反応しない       | ☑ 必要        | 再起動でプロセスを立て直す                    |
| サーバーに変更を加えたがブラウザに反映されない      | ☑ 必要        | 再起動でリロードされることがある                 |
| ファイル変更をしたのにホットリロードされない        | ☑ 必要（bind mount でない場合） | `volumes` 設定が反映されていない可能性も        |
| 新しい gem を追加した                             | 🔺 必要なこともある            | bundle install 後にサーバー再起動が必要な場合あり |
| `docker-compose.yml` の `volumes` / `environment` を変更した | ☑ 必要                   | 反映されないので再起動必須                    |
| Rails の環境設定（`config/environments/*`）を変更した| ☑ 必要                   | 再起動しないと反映されない                    |

VScode においてマークダウン記法を使えることを知ったので、今後マークダウン記法も取り入れつつ記録していく。

🎏5/4(17ポモ,8.5H) ※3ポモ計上もれもプラスしている
| 書き方      | 説明                              | 例             |
| -------- | ------------------------------- | ------------- |
| `<% %>`  | Rubyコードを実行するだけで、**HTMLに出力しない**  | ループ、条件分岐などに使う |
| `<%= %>` | Rubyコードを実行して、**その結果をHTMLに出力する** | 変数や関数の結果を表示   |

| Railsのフラッシュキー | 意味            | Bootstrapの対応クラス    | 表示色（Bootstrap） |
| ------------- | ------------- | ------------------ | -------------- |
| `:notice`     | 通常の通知         | `alert-info`       | 青（水色）          |
| `:alert`      | 警告・エラー        | `alert-danger`     | 赤              |
| `:success`    | 成功メッセージ       | `alert-success`    | 緑              |
| `:error`      | エラー（独自に使うことも） | `alert-danger`（同上） | 赤              |
| `:warning`    | 注意メッセージ       | `alert-warning`    | 黄              |

🎏5/5(7ポモ,3.5H)
☞学習：掲示板の一覧機能作成
集中力に欠けすぎていた、、、

🎏5/6(10ポモ,6H)
☞学習：掲示板の一覧機能作成

☑ Bootstrapのレスポンシブグリッド対応早見表
| クラス名        | 読み方（略称）                | 適用される画面幅       | カラム数（幅の割合）  | 具体的な例（表示幅）     |
| ----------- | ---------------------- | -------------- | ----------- | -------------- |
| `col-12`    | 省略（xs）                 | 〜576px 未満（省略可） | 全幅（100%）    | スマホの縦画面など      |
| `col-sm-6`  | small（sm）              | 576px 以上       | 半分（50%）     | 小型スマホ横向きなど     |
| `col-md-4`  | medium（md）             | 768px 以上       | 1/3幅（33.3%） | タブレットなど        |
| `col-lg-3`  | large（lg）              | 992px 以上       | 1/4幅（25%）   | ノートPCなど        |
| `col-xl-2`  | extra large（xl）        | 1200px 以上      | 1/6幅（16.6%） | デスクトップなど       |
| `col-xxl-1` | extra extra large（xxl） | 1400px 以上      | 1/12幅（8.3%） | 超大画面（大型モニターなど） |

☑ Bootstrap スペーシングユーティリティ まとめ表
| クラス  | 読み方            | 意味（プロパティ）    | 説明（指定範囲）             | 例（よく使う）           |
| ---- | -------------- | ------------ | -------------------- | ----------------- |
| `m`  | margin         | マージン全方向      | `m-0` 〜 `m-5`（上下左右）  | `m-3` = 全体に余白     |
| `mt` | margin-top     | 上にマージン       | `mt-0` 〜 `mt-5`（上だけ） | `mt-2` = 上だけ余白    |
| `mb` | margin-bottom  | 下にマージン       | `mb-0` 〜 `mb-5`（下だけ） | `mb-3` = 下に16px余白 |
| `ms` | margin-start   | 左マージン（LTR時）  | `ms-1` など            | `ms-4` = 左に余白     |
| `me` | margin-end     | 右マージン（LTR時）  | `me-2` など            | `me-2` = 右に余白     |
| `p`  | padding        | パディング全方向     | `p-0` 〜 `p-5`        | `p-4` = 中身に余白     |
| `pt` | padding-top    | 上パディング       | `pt-3` など            | `pt-1` = 上に詰める    |
| `pb` | padding-bottom | 下パディング       | `pb-3` など            | `pb-4` = 下に余白     |
| `ps` | padding-start  | 左パディング（LTR時） | `ps-2` など            | `ps-1` = 左内側に余白   |
| `pe` | padding-end    | 右パディング（LTR時） | `pe-2` など            | `pe-3` = 右内側に余白   |

☑数字とサイズ（rem単位）
| 数字  | サイズ（rem）  | ピクセル相当（約） |
| --- | --------- | --------- |
| `0` | `0rem`    | `0px`     |
| `1` | `0.25rem` | `4px`     |
| `2` | `0.5rem`  | `8px`     |
| `3` | `1rem`    | `16px`    |
| `4` | `1.5rem`  | `24px`    |
| `5` | `3rem`    | `48px`    |

☞同期懇親会

🎏5/7(7ポモ,3.5H)
☞学習：Rails基礎　掲示板の一覧機能作成
　多少エラーが読めるようになってきたことが収穫

🎏5/8(6ポモ,3H)
☞学習：Rails基礎　掲示板の一覧機能作成
       プルリクエストが通らなかった理由として、
       /RUNTEQ/rails_basic/74174_kenty-s_basic_rails_basic/app/controllers/users_controller.rb
       における誤った記述であることが判明。
       正　`t('users.create.success')`
       誤　`t('user_sessions.create.success')`
       ユーザー登録が出来なかった場合について
       `t('users.create.failure')`
       と記述していることを考えると、この発想にはすぐに至れるべきであった。
       ~~~
       def create
    @user = User.new(user_params)
    if @user.save
      session[:user_id] = @user.id
      redirect_to root_path, success: t('users.create.success')
    else
      flash.now[:danger] = t('users.create.failure')
      render :new, status: :unprocessable_entity
    end
  end
  ~~~

🎏5/9(4ポモ,2H)
☞学習：掲示板作成機能
　◎git commitを行うタイミング
　・　ファイルを生成・削除したタイミング
　・　実装が一区切り付いたタイミング
　・　正常に動くのを確認したタイミング
　・　修正したタイミング
　・　要件を満たす実装が完了したタイミング
　◎commitメッセージ
　・add：新規ファイル・新規機能追加
　・update：機能のアップデート
　・fix：バグの修正
　・remove：ファイルの削除

🎏5/10(12ポモ,6H)
☞学習：掲示板作成機能
       掲示板作成・作成ミス両面を実装する課題だが、プルリクエストが通らない(実際には実装出来ているにもかかわらず)

🎏5/11(4ポモ,2H)
☞学習：掲示板作成機能
       上記で示されていたエラー原因が分からず、スペースなどLintエラーを直すだけでプルリクが通った。謎が深まり、もやもやとする、、、

🎏5/12(6ポモ,3H)
☞学習：フォーム入力時エラー情報を個別表示
☞質問：以下ChatGPTに投げて使用
      貴方は優秀なRuby on Railsのエンジニアです。
      私はRuby on Railsを学び始めた初学者です。
      以下のコードの解説をお願いします。また、システムテストのコードであればテストコードと同様の操作を手動でも行ってチェックしたいので、ブラウザ上での操作手順を教えてください。よろしくお願いいたします。
      ==========
     （コード貼り付け）
      `render`
      ✅ 意味：コントローラーやビューで **「これを表示して！」**と指示する。
      ✅ よくある使い方：
      # コントローラーで：
      render :new       # new.html.erb を表示
      # ビューで部分テンプレートを表示：
      <%= render 'form' %>  # _form.html.erb を表示
      ✅ ここで使うぞ！が分かる方法：
      ・明示的に表示ビューを指定したいとき。
      ・部分テンプレート（パーシャル）を使いたいとき。
      ・条件によって表示を切り替えたいとき。

🎏5/13(5ポモ,2.5H)
☞学習：掲示板の画像アップロード機能
　　　　gem 'carrierwave'のGitHub読み込み
　　　　（Providing a default URL から）

🎏5/14(5ポモ,2.5H)
☞学習：掲示板の画像アップロード機能
        gem install carrierwave:2.2.2にてローカルでcarrierwaveをインストールできるが、webが起動されずDocker コンテナ内で インストールされない

🎏5/15(9ポモ,4.5H)
☞学習：掲示板の画像アップロード機能
カリキュラム上でWindowsを用いて学習を行う場合の構成としては
#Windowsの中にwslを用いてubuntuという別のOSをインストールし、そのubuntuの中にさらにDockerコンテナという"別のPCのような隔離された環境"を作成する
というようなことを行っている

       
| 項目                | `bundle install`                        | `gem install carrierwave`                        |
| -------------      | --------------------------------------- | ------------------------------------------------ |
| 対象                | `Gemfile` に書かれた全ての gem                  | 指定した gem（1つだけ）                                   |
| 反映される範囲       | プロジェクトの依存として明確化される                      | 一時的、もしくはグローバルな Ruby 環境だけ                         |
| Docker環境での使い方 | ✅ 推奨される                                 | ⚠️ 非推奨（環境の一貫性を壊す可能性）                             |
| 実行例              | `docker compose run web bundle install` | `docker compose run web gem install carrierwave` |

🎏5/16(7ポモ,3.5H)
☞学習：掲示板詳細画面の追加/コメント機能の実装
       概要、インプットフェーズ

🎏5/17(5ポモ,2.5H)
☞学習：掲示板詳細画面の追加/コメント機能の実装
       boards#index #はコントローラーとアクションの区切り記号
      
      | キー             | 内容（役割）                       |
| -------------- | ---------------------------- |
| `activerecord` | モデル名・属性名など、ActiveRecord関連の翻訳 |
| `helpers`      | `form_with` などのヘルパー関連の翻訳     |
| `views`        | 各ビュー（画面）専用の文言                |
| `errors`       | バリデーションなどで表示されるエラーメッセージ      |
| `defaults`     | 共通文言（投稿、削除、戻るなど）

🎏5/18(14ポモ,7H)
☞学習：掲示板詳細画面の追加/コメント機能の実装
(復習)よくあるエラー一覧
| エラー名                                     | 意味・説明                            | よくある原因例                                         |
| ---------------------------------------- | -------------------------------- | ----------------------------------------------- |
| `SyntaxError`                            | 文法エラー                            | - カッコの閉じ忘れ<br>- `end` の抜け<br>- `:` や `,` の書き間違い |
| `NameError`                              | 未定義の変数やメソッドを使った                  | - 変数のスペルミス<br>- 定義前に使った                         |
| `NoMethodError`                          | 存在しないメソッドを呼び出した                  | - nil に対してメソッド呼び出し<br>- クラスやオブジェクトの間違い          |
| `ArgumentError`                          | 引数の数や形式が間違っている                   | - メソッドに渡す引数の数が違う                                |
| `TypeError`                              | 型が合わない                           | - 数値に文字列を足そうとした (`1 + "a"`) など                  |
| `RuntimeError`                           | 実行時エラー（汎用）                       | - raise などで明示的に投げた場合など                          |
| `ActiveRecord::RecordNotFound`           | データが見つからなかった                     | - `Model.find(id)` で存在しない ID を指定した              |
| `ActiveModel::ForbiddenAttributesError`  | Strong Parameters で許可していない属性を渡した | - `params.require(...).permit(...)` が不足している     |
| `ActiveRecord::PendingMigrationError`    | マイグレーションが未実行                     | - `rails db:migrate` を忘れている                     |
| `RoutingError`                           | ルート（URL）が存在しない                   | - `routes.rb` に定義していない URL にアクセスした              |
| `Template::Error`                        | ビュー内のエラー（ERBなど）                  | - `<%= %>` 内の Ruby が間違っている                      |
| `Webpacker::Manifest::MissingEntryError` | JSやCSSが読み込めない                    | - `yarn build` などが必要、アセットのビルド忘れ                 |
#☆注意☆　`ActiveRecord::PendingMigrationError`はDockerでマイグレーションを行う場合`docker-compose exec web rails db:migrate`

自動レビュー実行前エラーに久しぶりにかかり、脱出できず。

🎏5/19(7ポモ,3.5H)
☞学習：掲示板詳細画面の追加/コメント機能の実装
       エラー修正

🎏5/20(9ポモ,4.5H)
☞学習：タイトルを動的に出力する
　　　　想定時間＋1H　エラー対応に時間を要した

🎏5/21(9ポモ,4.5H)
☞学習：掲示板の編集、削除機能の実装
      RailsのRESTfulなアクションの一般的な並び順
      index → show → new → create → edit → update → destroy

🎏5/22(5ポモ,2.5H)
☞学習：ブックマーク機能の追加
久々にこれ知ってるぞ、分かるぞの感

🎏5/23(1ポモ,0.5H)
☞学習：ブックマーク機能の追加

🎏5/24(21ポモ,10.5H)
☞学習：ブックマークボタンのajax化
       コメント投稿、削除機能のajax化
       掲示板のページネーション
Gemfileインストールおさらい
1️⃣ Gemfile に turbo-rails を追加
gem 'turbo-rails', '1.1.1'
2️⃣ Docker環境で bundle install
docker compose run --rm web bundle install
3️⃣ コンテナを再起動
docker compose restart
4️⃣ Railsの開発環境を起動
docker compose exec web bin/dev

###Turbo Streamの代表的なアクション
| メソッド | 日本語訳 | 役割 |
|---------|--------|------|
| **append**  | **末尾に追加** | 指定した要素の **後ろに追加** |
| **prepend** | **先頭に追加** | 指定した要素の **前に追加** |
| **replace** | **置き換え** | 既存の要素を **別のものと入れ替え** |
| **update**  | **更新** | 要素の内容を **変更・修正** |
| **remove**  | **削除** | 指定した要素を **取り除く** |
| **before**  | **前に挿入** | 特定の要素の **手前に追加** |
| **after**   | **後に挿入** | 特定の要素の **後ろに追加** |

## 🔍 Kaminari ＆ bootstrap5-kaminari-views：ドキュメント読み方ガイド

### ✅ 1. [kaminari/kaminari](https://github.com/kaminari/kaminari)

#### 📄 読むべきファイル／ディレクトリ

- [`/README.md`](https://github.com/kaminari/kaminari#readme)
  - 基本的な使い方（pageメソッド、paginateヘルパーなど）
  - インストール方法
- [`/kaminari/lib/kaminari/config.rb`](https://github.com/kaminari/kaminari/blob/master/kaminari/lib/kaminari/config.rb)
  - デフォルト設定一覧（1ページの件数、リンクの数など）
- [`/kaminari/lib/kaminari/helpers/`](https://github.com/kaminari/kaminari/tree/master/kaminari/lib/kaminari/helpers)
  - ページネーションUIを組み立てる内部ロジック（中級者向け）

---

### ✅ 2. [felipecalvo/bootstrap5-kaminari-views](https://github.com/felipecalvo/bootstrap5-kaminari-views)

#### 📄 読むべきファイル／ディレクトリ

- [`/README.md`](https://github.com/felipecalvo/bootstrap5-kaminari-views#readme)
  - `theme: 'bootstrap-5'` の使い方
  - Bootstrapに合わせたページネーションのカスタマイズ方法
- [`/views/kaminari/bootstrap-5/`](https://github.com/felipecalvo/bootstrap5-kaminari-views/tree/main/views/kaminari/bootstrap-5)
  - Bootstrap 5 対応の `paginate` ビューの実装
  - 自分のアプリにコピーしてカスタマイズする際に使う

---

### 💡 初心者におすすめの読み方手順

1. 両方の `README.md` をしっかり読む（導入と基本がわかる）
2. カスタマイズしたくなったら `views/kam

🎏5/25(8ポモ,4H)
☞学習：掲示板のページネーション
       公式ドキュメントの読み直し、解答の再確認が必要

🎏5/26(4ポモ,2H)
☞学習：kaminari公式ドキュメントREADME読み直し、掲示板の検索機能を実装

🎏5/27(2ポモ,1H)
☞学習：掲示板の検索機能を実装
       公式ドキュメントの読み方がやはり不明

🎏5/28(5ポモ,2.5H)
☞学習：
| 条件       | 説明                                     |
|-----------|----------------------------------------|
| `title_eq`   | 完全一致検索（`title = "検索ワード"`）  |
| `title_cont` | 部分一致検索（`title LIKE "%検索ワード%"`） |
| `title_start` | 前方一致（`title LIKE "検索ワード%"`）  |
| `title_end`   | 後方一致（`title LIKE "%検索ワード"`）  |

# は Railsのコントローラーアクションを表す記号
(例)`boards#index`,`boards#show`

🎏5/29(6ポモ,3H)
☞学習：
カラムを追加する＝マイグレートする

❓なぜ resources ではなく resource を使うのか？
resources は 複数のリソース（例: boards, comments）を扱う想定なので、ID付きのルーティングになる：

/profiles/1, /profiles/2/edit など

resource は 1人につき1つしか存在しないリソース（例: ユーザーのプロフィール、設定画面など）に適しており、IDを省略できる

👩‍🏫 まとめ
使うルーティング	意味	URL例
resource :profile	単一のプロフィールを対象	/profile, /profile/edit
resources :profiles	複数のプロフィールを対象	/profiles/1, /profiles/1/edit

`Zeitwerk::NameError`
…Rails の自動読み込み（autoload）機能である Zeitwerk によって、クラス名とファイルパスが一致しないときに発生
(解消方法)
1. AvatarUploader のファイルとクラス定義が一致しているか？
app/uploaders/avatar_uploader.rb

class AvatarUploader < CarrierWave::Uploader::Base
  # ...
end
2. クラス名を間違えていないか？
たとえば以下のようなミスはNG：

# ❌ class AvatorUploader と書いてしまっている
class AvatorUploader < CarrierWave::Uploader::Base
end

🎏5/30(6ポモ,3H)
☞学習：パスワードリセット機能の実装

🎏5/31(15ポモ,7.5H)
☞学習：パスワードリセット機能の実装
       GitHubの公式ドキュメントについて
       まずは一次ソースを見る(面接でも聞かれる)
       ⇒　分からなければQuiitaやZennで確認
       ※　卒業段階でも一次ソースで完璧理解までは求められない

       ###WSL上のプロジェクトディレクトリに書き込み権限がない
       ~を保存できませんでした。
       ファイル ~を書き込むことができません (NoPermissions (FileSystemError): Error:~/migrate/~)
       ###解決方法
       `sudo chown -R $(whoami):$(whoami) /RUNTEQ/rails_basic/74174_kenty-s_basic_rails_basic`

       (Sorceryでパスワードリセット機能を実装する)
       https://note.com/wattan11/n/n350a6923c4d5

## ✅ ネストとは何か？（Rails）

### 🔤 定義
**ネスト（nested routing）**とは、あるリソース（モデル）を別のリソースの中に入れ子構造で定義するルーティングの書き方。

---

### 🧩 例：掲示板にコメントを付ける場合

```ruby
resources :boards do
  resources :comments
end

☔6/1(6ポモ,3H)
☞学習：パスワードリセット機能の実装
       `token`　本人確認のためのURL

☔6/2(7ポモ,3.5H)
☞学習：パスワードリセット機能の実装

☔6/3(8ポモ,4H)
☞学習：パスワードリセット機能の実装

☔6/4(6ポモ,3H)
☞学習：
✅ layout と view の違い
項目	layout	view
役割	全体の枠組み	各ページの内容
適用範囲	アプリ全体	特定のページ
例	layouts/application.html.erb	users/show.html.erb

マイグレーションできてるか怪しい


☔6/5(6ポモ,3H)
☞学習：roleをadminへ変更できない
マイグレーションは出来ていた

☔6/6(3ポモ,1.5H)
(ここから)
URL：namespaceを使ってadminを切り出し、管理画面関連はそちらに配置する。
- アセット：管理画面用と分かるように整理・配置する。

☔6/7(0ポモ,0H)

☔6/8(5ポモ,2.5H)
☞学習：roleをadminへ変更できない/RSpecのセットアップ
roleをadminへ変更出来なかったので、別カリキュラム。
ローカルにcloneまで終了

☔6/9(16ポモ,8H)
☞学習：roleをadminへ変更
schemaと.lockは手修正NG

☔6/10(8ポモ,4H)
☞学習：[管理画面]掲示板/ユーザのCRUD機能の作成
カリキュラムの意図が分からなくなっている。CRUD機能実装くらいはできるようなりたいのだが、、、

☔6/11(3ポモ,1.5H)
☞学習：[管理画面]掲示板/ユーザのCRUD機能の作成

\\wsl.localhost\Ubuntu\RUNTEQ\rails_basic\74174_kenty-s_basic_rails_basic\app\controllers\admin\users_controller.rb
から