# [第4回スタートアップAndroid勉強会 - スタートアップにおけるアーキテクチャとの向き合い方 -](https://connpass.com/event/59928/)

## @fushiroyamaさん 「はやい・やすい・うまい！スタートアップでも使える Retrofit + RxJava で瞬間APIクッキングレシピ」
https://speakerdeck.com/srym/hayaiyasuiumai-sutatoatupudemoshi-eru-retrofit-plus-rxjava-deshun-jian-apikutukinguresipi

MFT
- [Retrofitが生成するObservableはdispose時にOkHttpのCallをcancelしてくれるんですよ。購読を解除するだけじゃなく非同期通信もキャンセルを試みてくれる](https://twitter.com/fushiroyama/status/885824999151489024)


## 株式会社トクバイ @sys1yagi さん 「アーキテクチャとScaffolding Template」
https://speakerdeck.com/sys1yagi/akitekutiyato-scaffolding-template
- アーキテクチャを妥協せず、ボイラープレートコードを洗い出して自動化しようという話
- [Inspired: 顧客の心を捉える製品の創り方](https://www.amazon.co.jp/Inspired-%E9%A1%A7%E5%AE%A2%E3%81%AE%E5%BF%83%E3%82%92%E6%8D%89%E3%81%88%E3%82%8B%E8%A3%BD%E5%93%81%E3%81%AE%E5%89%B5%E3%82%8A%E6%96%B9-%E3%83%9E%E3%83%BC%E3%83%86%E3%82%A3-%E3%82%B1%E3%82%A4%E3%82%AC%E3%83%B3-ebook/dp/B00TCM8TB4/ref=sr_1_1?ie=UTF8&qid=1500136805&sr=8-1&keywords=inspired)
  - 正しく製品を作るコストを最小化する
- カウボーイコーディングはやばい
- [FreeMaker](http://freemarker.org/)

MFT
- [FreeMakerを使うとAndroid StudioのActivityなどがあるテンプレートの中に自分で追加できて、それにMVPで必要な実装を追加できる](https://twitter.com/new_runnable/status/885812226380013569)


## ウォンテッドリー株式会社 @cattaka_netさん 「高速でトライ＆エラーをするために気をつけてること」
https://www.slideshare.net/TakaoSumitomo/ss-77872108

MEMO
- リリースをタイミングをわけてログの取り方が間違っていないか検証する

## @usaganikki さん 「ステークホルダーを巻き込む全体設計」
https://www.slideshare.net/shimadatatsuya/ss-77871596


## @mootohさん 「4 Years Startup & Architecture」
https://speakerdeck.com/mootoh/4-years-startup-and-architecture

MEMO
- [Uber RIB (Architecture)](https://eng.uber.com/new-rider-app/)

MFT
- [activityとかfragmentとかの単位でパッケージを切るのではなく、1画面に必要な単位でパッケージプライベートにまとめるという提案。スコープも適切だし追いやすい](https://twitter.com/fushiroyama/status/885827078330789888)
- [メルカリのアーキテクチャの変貌 MVA(独自のMVC的なやつ) -> 増築/改築して肥大化 → MVVM(Rx/DIなど) → 海外とのシングルソースをやめる → これから コンポーネント指向/UberのRIB(VIPER)などを考えている ](https://twitter.com/new_runnable/status/885822017278058496)
- [次のフェーズ。グロース。A/Bテストやりまくり。海外版も出したくなってきた。するとクーロン城のような無理な建て増し。エントロピーの増大。いろんなデザパタの混在。非常に危険な状態。統一アーキテクチャの必要性。](https://twitter.com/fushiroyama/status/885821143155785729)


## @Reyurnibleさん 「なぜ変更を検知できるDBが必要とされるのか」
https://speakerdeck.com/reyurnible/nazebian-geng-wojian-zhi-dekirudbgabi-yao-nafalseka

MFT
- [RxJava1->2の間を取り持ってくれる https://github.com/akarnokd/RxJava2Interop … というライブラリは存在しています](https://twitter.com/fushiroyama/status/885824482392199168)

## @ryugoo_さん 「チーム開発と Android アプリの構成」
https://speakerdeck.com/ryugoo/timukai-fa-to-android-apurifalsegou-cheng

MFT
- [あとパッケージの話で個人的に思っているのは “util” の単語を使うと危険な匂いがすること。うまくコンテキストを捉えられなかったコードはだいたいそこに突っ込みまくられて肥大化していく](https://twitter.com/sho5nn/status/885827447567941632)

