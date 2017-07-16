# [第4回スタートアップAndroid勉強会 - スタートアップにおけるアーキテクチャとの向き合い方 -](https://connpass.com/event/59928/)

## @fushiroyamaさん 「はやい・やすい・うまい！スタートアップでも使える Retrofit + RxJava で瞬間APIクッキングレシピ」
https://speakerdeck.com/srym/hayaiyasuiumai-sutatoatupudemoshi-eru-retrofit-plus-rxjava-deshun-jian-apikutukinguresipi

MEMO
- [Retrofit](http://square.github.io/retrofit/)
- [RxJava+RetrofitでAPI通信周りを実装するうえで最低限の知識を30分で詰め込む](http://qiita.com/FumihikoSHIROYAMA/items/201536d9b45ef21b6bc7)
- [Retrofitを使ったOAuth再認証アプローチ](http://qiita.com/FumihikoSHIROYAMA/items/ac1beaeaa9b4baaed939)
- [ how to architect an android application using Uncle Bob's clean architecture approach.](https://github.com/android10/Android-CleanArchitecture)
- [srym/Architecture](https://github.com/srym/Architecture)
- [srym/Architecture/.../RestGitHubDataSourceTest.java](https://github.com/srym/Architecture/blob/master/app/src/test/java/us/shiroyama/android/architecture/infrastructure/repository/datasource/remote/RestGitHubDataSourceTest.java)

Twitter
- [Retrofitが生成するObservableはdispose時にOkHttpのCallをcancelしてくれるんですよ。購読を解除するだけじゃなく非同期通信もキャンセルを試みてくれる](https://twitter.com/fushiroyama/status/885824999151489024)

OTHRE
- [いらすとや](http://www.irasutoya.com/)

## 株式会社トクバイ @sys1yagi さん 「アーキテクチャとScaffolding Template」
https://speakerdeck.com/sys1yagi/akitekutiyato-scaffolding-template
- アーキテクチャを妥協せず、ボイラープレートコードを洗い出して自動化しようという話
- [Inspired: 顧客の心を捉える製品の創り方](https://www.amazon.co.jp/Inspired-%E9%A1%A7%E5%AE%A2%E3%81%AE%E5%BF%83%E3%82%92%E6%8D%89%E3%81%88%E3%82%8B%E8%A3%BD%E5%93%81%E3%81%AE%E5%89%B5%E3%82%8A%E6%96%B9-%E3%83%9E%E3%83%BC%E3%83%86%E3%82%A3-%E3%82%B1%E3%82%A4%E3%82%AC%E3%83%B3-ebook/dp/B00TCM8TB4/ref=sr_1_1?ie=UTF8&qid=1500136805&sr=8-1&keywords=inspired)
  - 正しく製品を作るコストを最小化する
- カウボーイコーディングはやばい
- [FreeMaker](http://freemarker.org/)
- [create a group of file templates](https://riggaroo.co.za/custom-file-template-group-android-studiointellij/)

Twitter
- [FreeMakerを使うとAndroid StudioのActivityなどがあるテンプレートの中に自分で追加できて、それにMVPで必要な実装を追加できる](https://twitter.com/new_runnable/status/885812226380013569)
- [ViewPagerの画面滞在時間のログ](https://twitter.com/cattaka_net/status/886483123688546305)


## ウォンテッドリー株式会社 @cattaka_netさん 「高速でトライ＆エラーをするために気をつけてること」
https://www.slideshare.net/TakaoSumitomo/ss-77872108

MEMO
- [TREASURE](https://www.treasuredata.com/jp/)
- [Fluentd](https://fluentd.treasuredata.co.jp/?gclid=Cj0KEQjw-qbLBRD79JWsjuXI784BEiQAftBCI_mVBcd0oGbFwv-PugR6Hosxl98Xq7A11dJX5xVJ7ZQaAqlO8P8HAQ)
  - セキュリティ・拡張性・信頼性を備えたログ収集ソフトウェア
- リリースをタイミングをわけてログの取り方が間違っていないか検証する
- [Androidアプリ滞在時間の計測](https://www.slideshare.net/heki1224/android-45736528)
  - [Android 向け Google アナリティクス SDK v4 に関するセッションの概要](https://developers.google.com/analytics/devguides/collection/android/v4/sessions?hl=ja)

Twitter
- [「適当に取ったログは役に立たない」
これはわかるし耳が痛い](https://twitter.com/fushiroyama/status/885816304568983553)

## @usaganikki さん 「ステークホルダーを巻き込む全体設計」
https://www.slideshare.net/shimadatatsuya/ss-77871596

MEMO
- [なんとなく流してませんか? 「ステークホルダー」の意味](http://news.mynavi.jp/news/2014/06/09/096/)


## @mootohさん 「4 Years Startup & Architecture」
https://speakerdeck.com/mootoh/4-years-startup-and-architecture

MEMO
- [Uber RIB (Architecture)](https://eng.uber.com/new-rider-app/)

Twitter
- [メルカリのアーキテクチャの変貌 MVA(独自のMVC的なやつ) -> 増築/改築して肥大化 → MVVM(Rx/DIなど) → 海外とのシングルソースをやめる → これから コンポーネント指向/UberのRIB(VIPER)などを考えている ](https://twitter.com/new_runnable/status/885822017278058496)
- [次のフェーズ。グロース。A/Bテストやりまくり。海外版も出したくなってきた。するとクーロン城のような無理な建て増し。エントロピーの増大。いろんなデザパタの混在。非常に危険な状態。統一アーキテクチャの必要性。](https://twitter.com/fushiroyama/status/885821143155785729)


## @Reyurnibleさん 「なぜ変更を検知できるDBが必要とされるのか」
https://speakerdeck.com/reyurnible/nazebian-geng-wojian-zhi-dekirudbgabi-yao-nafalseka

MEMO
- A collection of samples using the Architecture Components: https://github.com/googlesamples/android-architecture-components
- requery - modern SQL based query & persistence for Java / Kotlin / Android: https://github.com/requery/requery
- Example of how to implement an Android TODO App using Facebook Flux Architecture: https://github.com/lgvalle/android-flux-todo-app

Twitter
- [RxJava1->2の間を取り持ってくれる https://github.com/akarnokd/RxJava2Interop … というライブラリは存在しています](https://twitter.com/fushiroyama/status/885824482392199168)
- [RealmはRxJavaまだ1なんですよね… ](https://twitter.com/fushiroyama/status/885823442519375872)

## @ryugoo_さん 「チーム開発と Android アプリの構成」
https://speakerdeck.com/ryugoo/timukai-fa-to-android-apurifalsegou-cheng

MEMO
- [Riggaroo : Android Architecture Components](https://riggaroo.co.za/android-architecture-components-looking-room-livedata-part-1/)

Twitter
- [activityとかfragmentとかの単位でパッケージを切るのではなく、1画面に必要な単位でパッケージプライベートにまとめるという提案。スコープも適切だし追いやすい](https://twitter.com/fushiroyama/status/885827078330789888)
- [あとパッケージの話で個人的に思っているのは “util” の単語を使うと危険な匂いがすること。うまくコンテキストを捉えられなかったコードはだいたいそこに突っ込みまくられて肥大化していく](https://twitter.com/sho5nn/status/885827447567941632)

