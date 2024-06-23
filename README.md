# アプリ開発

■サービス概要
日記アプリ。
下記物語の老魔法使い、アルディアスがユーザーが記載した日記に返答してくれます。

↓↓↓↓↓↓↓↓↓↓↓↓↓↓↓↓↓↓↓↓↓↓↓↓↓↓↓↓↓↓↓↓↓↓↓↓↓↓↓↓↓↓↓↓↓↓↓↓↓↓↓↓↓↓↓↓↓↓↓↓↓↓↓↓↓↓↓↓↓↓↓↓↓↓↓↓↓↓↓
物語の背景:
魔法の力で本に閉じ込められた魔法使い、名前は「アルディアス」。彼はかつて栄華を誇った魔法学院の教授であり、深い知識と力を持っていたが、ある試みが失敗し、その結果自らの身体を本に封じ込めざるを得なくなった。しかし、彼の知識や精神は依然として本の中に生き続け、魔法を使う者と交流することができる。

物語の展開:
かつてアルディアスが教え子たちに語っていた「知識の収穫」という魔法がある。この魔法は、知識という実りを育むために日々の成長や経験を記録することで、その知識が豊かになるというものだ。しかし、アルディアスが本に閉じ込められてからは、彼の知識は停滞してしまった。

そこで、ある冒険者が偶然にもその本を手に入れ、その魔法の秘密を知ることとなった。彼は自身の冒険や学びの記録を日記として本に書き込み始めた。すると、不思議なことが起こった。本の中からアルディアスの声が聞こえ、彼の知識が更新されていくのだ。

冒険者は驚きながらも、この珍しい体験を楽しむようになり、日記には日々の冒険や学び、疑問や挑戦を綴っていった。アルディアスはその度に古代の魔法や哲学、そして人間の心理について深く語り、冒険者の理解を深めていった。

やがて、冒険者はこの本を他の人々と共有することを決意する。彼は本の魔法を使って、世界中の知識欲旺盛な人々にこの本の存在を伝えることにした。これによって、さまざまなユーザーがこの本に自分の日記を書き込み、アルディアスとの対話を楽しむことができるようになった。

結果として、アルディアスの知識は再び成長し始め、多くの人々の学びや冒険の道標となった。彼の魔法は、閉じ込められた一冊の本を通じて世界中に広がり、無限の可能性を秘めた交流の場となったのである。

↑↑↑↑↑↑↑↑↑↑↑↑↑↑↑↑↑↑↑↑↑↑↑↑↑↑↑↑↑↑↑↑↑↑↑↑↑↑↑↑↑↑↑↑↑↑↑↑↑↑↑↑↑↑↑↑↑↑↑↑↑↑↑↑↑↑↑↑↑↑↑↑↑↑↑↑↑↑↑

■ このサービスへの思い・作りたい理由
昔からハリーポッターや魔法使いの弟子（ディズニー）の雰囲気が好きで、何度も映画を見ました。ユニバのハリーポッターコーナーやハリーポッタースタジオにも行きました。
ファンタジーの世界を少しでも味わいたいと常に考えました。
今回は、本の中に閉じ込められた魔法使いが返答をしてくれる日記が作成することで、魔法の世界を体験出来るのではないかと考えこのアプリを作成しようと思いました。

■ ユーザー層について
自分と同じようにハリーポッターなど魔法の世界観や最近流行りの異世界のの世界観に少しでも浸かりたいと思っている人がいると思うので、魔法のような世界観が好きな人に向け作成を考えています。

■サービスの利用イメージ
ファンタジーな世界観を楽しみながら日記を投稿することで、普通の日記では継続できない方でも、日記を継続することができるきっかけを与えることができます。

■ ユーザーの獲得について
Twitter、Instagram、TikTokなどでハリー・ポッターや異世界、魔法に関連するコンテンツを投稿し、ハッシュタグキャンペーンを行う。

■ サービスの差別化ポイント・推しポイント
他の日記アプリとは違い、架空のキャラがその日記に対してコメントを行って来れます。

■ 機能候補（MVPリリース）
・ユーザー管理機能（ログイン機能）
ユーザー登録、ユーザー編集、ログイン、ログアウト、パスワードリセット
Gem：devise・・・ ユーザー認証、登録、パスワードリセットなどの機能
Gem：carrierwave・・・プロフィール画像のアップロード機能

・日記投稿機能
日記の作成・編集・削除（CRUD)、一覧表示、詳細表示
投稿内容：日付、日記内容、写真（もしくはGif,動画)
Gem: carrierwave・・・日記画像のアップロード機能

・日記画像のグレースケール
日記画像アップデート時、画像をグレースケール加工を行い表示する機能
Gem: mini_magick

・ChatGPTによる日記への返信機能
ChatGPTがトム・リドルを装い日記に対し返信を行う機能
使用ツール: ChatGPT API

・一文字ずつ文字出力
自分の投稿や、トムリドルの返答を見るときに一文字ずつ文字が出力される機能
Gem：特になし

■ 機能候補（本リリース）
・友達追加機能
友達リクエストの送信と承認
Gem：特になし

・日記公開機能
日記の公開設定をユーザーが管理できる機能
1.トムリドルとの日記（ユーザー閲覧のみ＆ChatGPTの返信機能）
2.フレンドオンリー
3.一般公開
Gem：特になし

・コメント機能
他ユーザーの日記に対し、コメントができる機能
Gem：turbo-rails

・日記動画のグレースケール＆GIF化
日記動画アップデート時、動画をグレースケール加工を行い表示する機能
容量削減のためGIFに変換する。
使用ツール：OpenCV,moviepy

■ 機能の実装方針予定
RubyOnRailsをもとにアプリの作成
動画の加工のみ、Pythonを使用（System()での呼び出し）

・動画のGIF変換および画像編集
概要:
動画ファイルをアップロードし白黒に編集を行ったあと、GIFに変換する機能。
1.SystemコマンドからPythonスクリプトを呼び出す。
2.OpenCVとmoviepyを使用し動画のグレースケール加工、GIF化
画像、動画アップロード先：AWS-S3
使用するライブラリ/ツール:
Python-OpenCV
moviepy

2.ChatGPTによる返答機能
概要：
ユーザーが投稿した内容に対して、ChatGPTがトム・リドルに模して返答を行う機能
コントローラーより、ユーザーが投稿した内容をChatGPT APIに送信し返答を受け取る
ビューに表示する際は、一文字ずつ文字を出力を行う。 
使用するライブラリ/ツール：
OpenAIのChatGPT API
