# Home_Workout_Lovers
# 宅トレマニア

## サービス概要
宅トレが大好きな人や、これから宅トレをやってみたいと思う人に、
楽しく宅トレが続けられる場所を提供する
宅トレ愛好家サービスです。

## メインのターゲットユーザー
- メインは主に20代〜40代の社会人男女で、運動、ボディメイク、ダイエットに興味関心のある人
- 上記に興味はあるけれど、何から始めていいかわからない人
- 宅トレをたまに行うけど、習慣化しない人

## ユーザーが抱える問題
- １度はジムの会員になった事があるものの、行くまでの準備（ウェアの用意など）が面倒で、結局幽霊会員になってしまった。
- 仕事や家事、育児が忙しく、そもそもジムに行く時間がない。
- 一緒に出来る仲間がいないとモチベーションが続かない。
- 目に見える効果がすぐに現れないので3日坊主になりがち。

## 解決方法
- ジムへ行く準備がいらない、すっぴん部屋着で24時間好きな時に気軽に行える宅トレ動画メニューの提供。
- 時間やお金をかけずに、運動、ダイエットが出来る。
- ユーザー同士でお勧めの宅トレメニュー動画をシェア、コメント出来る機能を実装し、宅トレ仲間を作る事が出来る。
- 動画を1つやり終えると、自分を褒めてくれる言葉が表示され、運動を続けるモチベーションを維持する事が出来る。

## 実装予定の機能
- ゲストユーザー
  - ユーザー登録しなくても、沢山のメニューからトレーニングを行う事が出来る。
  - 初期のメニューとして、時間別、部位別（脚、お腹、二の腕など）、気分別（ハードモード、ゆったりモードなど）の選択肢を設定し、見合った動画が表示される。

- 登録ユーザー
  - お勧めの宅トレメニューを他の会員へシェア出来る、また他のユーザーのおすすめを動画を見る事が出来る。
  - 自分のお気に入りの動画を組み合わせて、自分だけの宅トレメニュープログラムを作ることが出来る。
  - 1日〜7日で自由に設定してプログラムが作れる。
  - 初心者向けのメニューや、忙しい人向けの5分〜10分程度のメニュー、足音の気になるマンションの人向けのメニューなど、多彩なメニュー動画を設定。
  - 動画を1つやり終えると、様々な褒め言葉が表示される。

- 管理ユーザー
  - 登録しているユーザーのCRUD
  - 動画メニューのCRUD
  - 動画の最後に現れる褒め言葉のCRUD
  - 管理ユーザーのCRUD

- 順次導入していきたい機能
  - 会員同士でお勧めの宅トレグッズやプロテインの紹介をし、実際に購入できるページへのリンクなども貼りたい。

## なぜこのサービスを作りたいのか？
私自身が昨年夏から宅トレを行い、体重-6kg、腹筋が割れ、開脚して胸が付くくらい柔軟性も向上しました。
特別な事はしておらず、自宅で週5、6日10分程度の宅トレを行なっただけです。
今まで運動をしようと思っても、ジムを続けられなかったり、（上記の幽霊会員とは正に自分自身の事で、1年弱幽霊会員だった時もありました。）ランニングなども3日坊主どころか1日坊主だったりしました。
宅トレは自宅で気軽に行う事ができ、動画以外は用意も何もいらないため、ズボラな自分にはピッタリでした。
ただ、宅トレは非常に多くのメニューがあるため、どのメニューが本当に効果があるのかなとか、他の人はどんなメニュー動画を使ってトレーニングをしているのかなと気になるようになりました。
YouTubeなどのコメント欄は基本的に動画製作者と視聴者の1対多の交流のため、実際にトレーニングを行なっている視聴者同士でもっと交流が出来るサービスを作りたいと思いました。
全く運動を続ける事が出来なかった私が宅トレを行うことで、明らかに見た目が変わり、気持ちも前向きになり、仕事、勉強などの集中力もアップしました。
良いこと尽くしの宅トレの世界を多くの皆様に広めていきたいと思い、このサービスを作りました。

### 画面遷移図
[画面遷移図](https://www.figma.com/file/bFF4781q086iQTe1bIdAYO/%E5%AE%85%E3%83%88%E3%83%AC%E3%83%9E%E3%83%8B%E3%82%A2?node-id=18%3A10)

### ER図
[ER図](./er.drawio.png)