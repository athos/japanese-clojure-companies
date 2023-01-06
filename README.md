# 日本で Clojure/ClojureScript を利用している会社一覧

(inspired by [日本でErlang/OTPやElixirを利用している会社一覧](https://github.com/voluntas/japanese-erlang-elixir-companies))

- 日本国内版
- プルリクエストください
    - 信頼性を担保するために中の人のみでお願いします
    - 後ろに付け足していってください
    - コミットログは適当で英語でも日本語でも良いです
- カテゴリー分けは後回し
- 求人情報歓迎
- まずは適当に書いて貰えると嬉しいです

こうした方が良いとかは Twitter で [@athos0220](https://twitter.com/athos0220) か GitHub Issue へお気軽にご連絡ください。

## テンプレート

```
### [会社名](会社 URL)

- 箇条書きで Clojure/ClojureScript のプロダクション利用について好きなだけ

会社のアピールや求人を好きなだけ
```

## 会社一覧

### [ニャンパス株式会社](http://nyampass.com/)

- Clojure/ClojureScript利用サービス
  - [Baasday](https://baasday.com/): Clojure製MBaaS
  - [Robip](https://robip.halake.com/): 自社製開発ボードHaLake Kit用ビジュアルプログラミング環境(ClojureScript製)

Webサービス等のバックエンドとしてClojureを、Webに限らず様々な環境向けのフロントエンド構築にClojureScriptを手広く使っています。

### [Greative.GK](https://greative.jp/)

- 自社メディア [designudge](https://designudge.org/ja/)
- 某WebサービスのAPIサーバ構築(Clojure)

その他OSSプロダクトとして、ClojureScriptベースのElectronアプリケーションの開発スターターキット[descjop](http://descjop.org/) の開発。まだまだPlay framework(Java)やReact(JavaScript)ベースな開発が多いですが、積極的にClojure/ClojureScriptを導入していく予定です。

### [株式会社テンクー](https://xcoo.co.jp)

テンクーでは、ゲノム医療のためのトータルソリューションソフトウェアChrovisの開発と、Chrovisを使った解析サービスの運営を行っています。

- [Chrovis](https://chrov.is)
  - <https://github.com/chrovis>
  - <https://github.com/xcoo>

テンクーの採用情報 https://xcoo.co.jp/recruit.html

### [株式会社シグニファイア](http://signifier.jp)

- 米国プロフェッショナルサービス業向けグローバル提携事務所検索サービスの構築... サーバーサイドはcompojure-api, buddy, java.jdbc, carmine, honeysql, incanterなど。クライアントサイドはre-frame
- 卸業向けたばこ税申告書生成サービス ... AWS Lambda, Clojure, Incanter
- たばこ小売業向け卸売B2B Eコマース ... サーバーサイドはKong, compojure-api. クライアントサイドはReagent

ビジネスアイデアを持つスタートアップ企業を対象に、アイデアをコラボレーションしながらWebサービスを構築し、運用まで行うビスポーク開発をClojure/cljsで提供しています。
弊社代表は米国証券スタートアップ企業で、預かり高200億円規模のトレーディングバックオフィスシステムをClojureで構築した経験があります。

### [トヨクモ株式会社](https://toyokumo.co.jp/)

- Clojureで開発しているサービス
  - [トヨクモ スケジューラー](https://www.toyokumo.app/scheduler): 社内の予定が見やすく社外の人とも日程調整でき、スマホでもカンタンなグループスケジューラー
    - Clojure, ClojureScript, component, aero, shadow-cljs, Reagent, re-frame, gluttony
  - [安否確認サービス2](https://anpi.toyokumo.co.jp/): 次世代型安否確認システム(2019年5月からテレビCM放映中)
    - Clojure, ClojureScript, mount-lite, aero, shadow-cljs, Reagent, re-frame, gluttony
  - [kintone連携サービス](https://kintoneapp.com/)
    - 全製品のGraphQL APIでClojureを使用しています。
    - [kMailer](https://km.kintoneapp.com/): サイボウズ社の[kintone](https://kintone.cybozu.co.jp/)と連携するWebサービス
      - Clojure, ClojureScript, component, aero, shadow-cljs, Reagent, re-frame, gluttony, tarayo, lacinia, superlifter
    - [DataCollect](https://dc.kintoneapp.com/): サイボウズ社の[kintone](https://kintone.cybozu.co.jp/)と連携するWebサービス
      - Clojure, ClojureScript, component, aero, shadow-cljs, Reagent, re-frame, gluttony, struct, instaparse, lacinia, superlifter

Clojureを使ってSaaSを提供しています。

製品だけでなく、ClojureScriptで社内向けツールを作ったり、また今後もClojure/ClojureScirptを使った新製品を開発予定です。
また、Clojureを書く人には、Intellij IDEAとCursiveのライセンスを支給しています。

通年で採用を行なっています。採用情報は[こちら](https://toyokumo.co.jp/jobs)です。

### [株式会社オプト Opt Technologies](https://opt-technologies.jp/)

- Clojure利用プロダクト
  - 広告媒体アカウント管理システム「アムズ」(GraphQL API): Duct (Integrant), Pedestal, Lacinia
  - 広告入稿Editorツール「Opt Editor」(REST API): Duct (Integrant), Pedestal
  - 社内依頼管理システム「TASK DRIVER」(バッチ): Luminus (mount), Immutant
    - cf. [Clojureをプロダクトに導入した話 - Opt Technologies Magazine](https://tech-magazine.opt.ne.jp/entry/2017/09/06/074020)

Opt Technologiesとは、株式会社オプトのエンジニアリング部門です。
企業や生活者を広告や技術でつなぐことで社会のデジタルシフトを推進し、より便利でサステナブルな社会の実現を目指します。

Opt Technologiesの採用情報は[こちら](https://opt-technologies.jp/index.html#recruit)です。

### [LiME株式会社](http://limehair.jp/corp/)

- Clojure利用プロダクト
  - 美容師向け送客WEBサービス [STEKiNA](https://stekina.com/): ClojureScript([re-frame](https://github.com/Day8/re-frame)を利用)
  - iOS/androidアプリ RiZM(仮): ClojureScript([Re-natal](https://github.com/drapanjanas/re-natal)を利用)

美容師および美容に関わる業態向けのサービスの開発・運営をしています。
他にもいくつかプロダクトがありますが、サーバーサイドはAPIやBatchすべてClojure製です。
KPI管理などの社内ツールもほとんどがClojureで作られています。

「どんな人でも美を簡単に表現できる世界を創造する」をモットーに
現役美容師が立ち上げた会社です。テクノロジーの力でこれを実現できるよう、少ないメンバーで日々奮闘中です！

### [株式会社GYAO](http://www.gyao.co.jp/jp/index.html)

- [GYAO!](https://gyao.yahoo.co.jp/)
- [GYAO! ストア](https://streaming.yahoo.co.jp/)

GYAOでは「エンターテインメントの力で、すべての人々の人生に充実した時間を提供する。」事をミッションに多種多様な公式動画を提供するサービスを運営しています。

コンテンツを早く、リッチな形で提供するために、新規のデータ統合システムをClojureで実装しました。DatomicとGraphQLを採用し、柔軟性が高く、変更に強い、スケーラブルな分散システムを実現しています。

関連するインハウスツール群もClojureScriptで実装し、CLJCでSpec等のコードをサーバー/UI間で共有できるメリットを享受しています。

#### 採用情報
ヤフー株式会社、株式会社GYAOでは、共に働いてくれるFunctionalでImmutableかつPersistentなLispエイリアンを広く募集しています！(エンジニアについてはヤフー株式会社の採用情報からご応募ください)
- https://about.yahoo.co.jp/hr/
- http://www.gyao.co.jp/jp/hr/

### [株式会社ユーザベース](https://www.uzabase.com/)

- Clojure利用API/サービス
  - pony: SQSのメッセージをトリガーとしてデータの取り込みを行います。
  - whale: Google Cloud Pub/Subをトリガーとしてデータの取り込みを行います。
  - speeda-integrity-validator: データの不整合を検知しSlackに通知します。
  - magnum: Bing APIを用いて企業名称を元に対象企業のURLを特定します。
  - bff: 複数のAPIを並列で呼び出しその結果を束ねてフロントエンドに返すAPIアグリゲーターです。

ユーザベースでは[SPEEDA](https://www.uzabase.com/service/speeda/)のマイクロサービス化を推めています。
API/サービスごとに最適なモノを選択するという方針のもと、様々な言語/フレームワークを使用しています。([JOB DESCRIPITON](https://uzabase-inc.workable.com/jobs/849108)の"＜技術スタック＞"欄)

### [Locarise株式会社](https://locarise.com/)

Physical Space Intelligenceカンパニーとして物理的な空間を情報資源として扱えるようにすることをミッションにしています。

直近では小売の店舗にWi-Fiの匿名電波をキャッチする装置を設置→AWS上で集めた情報を集計→ダッシュボードから店舗に訪ずれた人のおおよその滞在時間や店舗内のどのエリアを移動したかといったメトリクスを確認できるソリューションを提供しています。

バックエンドのコードはPython/Django/AWS Lambdaで実装し、ダッシュボード部分はre-frameを利用したClojureScriptのSPAとして実装しています。
今後バックエンド部分にもClojureを使っていきたいと考えています。

国際色豊かなチームでPythonやClojure/ClojureScriptで仕事をしたい方、Wi-Fi機器等のハードウェアやネットワークの設定等好きな方はcareers@locarise.comまでご連絡ください。

### [株式会社Catallaxy](https://catallaxy.me/)

「未来の製造業を作る」をミッションに、レガシーな製造業の分野をClojureで書き換えています。
現在は社内向けのAPIのみClojure運用で、表向きのプロダクトはRuby on Railsを使っていますが、近い将来はClojure/ClojureScriptにすべて書き換える予定です。
- [Mitsuri](https://mitsu-ri.net/): 金属加工のサプライチェーンを変革するプラットフォーム。
- [Fabit](https://fa-bit.net/): 日本一わかりやすい製造業紹介メディア

### [株式会社トレタ](https://toreta.in/jp/)

株式会社トレタは、飲食店向けの予約／顧客管理に特化したクラウド型サービスを手がけています。紙の予約台帳に置き換わるiPad予約台帳アプリ「トレタ」を中心に、最近では各社POSシステムとシームレスに連携する「POSコネクト」、様々なグルメサービスからの即時予約と予約実績管理を実現する「メディアコネクト」などの新機能を次々に開発しています。トレタは、予約管理・顧客管理の面から飲食店のIT化を牽引する「予約サービスのインフラ」を目指します。

バックエンドのコードはRails/AWS Auroraですが、分析用のデータパイプラインClojureベースでCDCを行ってほぼリアルタイムでBigQueryにデータを流し込んでおります。またMySQLのinformation schemaを使ってCDCログからデーブル構造を復元するSQLを生成するところもClojureで実装しております。

### [株式会社AGE technologies](https://age-technologies.co.jp)

相続手続きのデジタル化を皮切りに「高齢社会にテクノロジー革命を起こす」スタートアップ企業です。

Clojure/Script利用シーン

- 社内オペレーター向けUI(ClojureScript & [Rum](https://github.com/tonsky/rum))
- 会員様向けUI(ClojureScript & [Rum](https://github.com/tonsky/rum))
- APIサーバー([duct](https://github.com/duct-framework) / [honeysql](https://github.com/seancorfield/honeysql))
- 申請書自動生成システム

相続は、課題の多さ、前例の少なさ、法律に関わる、などの点でチャレンジャブルな領域です。
まずはこの領域を、Clojureで開拓していきます。

[ご応募はこちら](https://herp.careers/v1/agetechinc/C0F_OtwIrGt1)

### [株式会社スタディスト](https://studist.jp/)

「伝えることを、もっと簡単に。」をミッションに、業務効率化のためのBtoBプラットフォームを提供しています。

- Clojure利用プロダクト
  - [Teachme Biz](https://biz.teachme.jp/): 業務効率化・⼈材育成を推進するマニュアル作成・共有プラットフォーム

スタディストのメインプロダクト「Teachme Biz」はRuby on Railsで構成されていますが、新規機能開発をマイクロサービスとして開発しており、その中でも人材教育機能やSalesforce向けの連携機能などをClojureで開発しています。また、過去に[Clojure/north](https://medium.com/studist-dev/clojure-north-2019-report-f87b480b19f4)にメンバーが登壇した実績もあります。
社内ではOSSへの貢献を行っていたり、必要であれば自社でOSS開発を行った実績もあり、スタディストの名の通り学びに積極的なメンバーが集まっています。

株式会社スタディストの採用情報は[こちら](https://studist.jp/recruit/)

### [合同会社ノイマン](https://www.neumann.tokyo/)

- Clojure, Ruby, JavaScript, TypeScript などを用いた受託開発を主な業務としています。Clojure を用いた受託開発の実績も数件あります。
- 本社は静岡県三島市にありますが業務は全てリモートワークで行なっているので、他県に住んでいる社員もいます。
- また、最近ではネパールに業務の一部を委託するオフショアも行なっており、今後もグローバルな活動を続けていく予定です。
- インターンシップ制度など若手人材の教育にも力を入れています。
- 自社開発プロダクトも Clojure を用いて開発しています。
  - [Word Penne](https://word-penne-lp.neumann.tokyo/)
    - 単語帳作成アプリ
    - ClojureScript (Reagent, Re-Frame) を用いて開発して Firebase にデプロイしています

お問合せ、求人の申込などは [こちら](https://docs.google.com/forms/d/e/1FAIpQLSdHMxI-xN5SFX_XPGmmJ3dWh8P1jSwmKKSsJmiCQp1LJfgyxA/viewform) からお願いします。
