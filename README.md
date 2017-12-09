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

- [Chrovis](https://chrov.is) ゲノム医療のためのトータルソリューションソフトウェアChrovis
  - <https://github.com/chrovis> Chrovis関連のOSS
- <https://github.com/xcoo> その他のOSS

その他受託開発についても、Clojure/ClojureScriptで実装しています。

テンクーの採用情報については <https://xcoo.co.jp/recruit.html>


### [株式会社シグニファイア](http://signifier.jp)

- 米国プロフェッショナルサービス業向けグローバル提携事務所検索サービスの構築... サーバーサイドはcompojure-api, buddy, java.jdbc, carmine, honeysql, incanterなど。クライアントサイドはre-frame
- 卸業向けたばこ税申告書生成サービス ... AWS Lambda, Clojure, Incanter
- たばこ小売業向け卸売B2B Eコマース ... サーバーサイドはKong, compojure-api. クライアントサイドはReagent

ビジネスアイデアを持つスタートアップ企業を対象に、アイデアをコラボレーションしながらWebサービスを構築し、運用まで行うビスポーク開発をClojure/cljsで提供しています。
弊社代表は米国証券スタートアップ企業で、預かり高200億円規模のトレーディングバックオフィスシステムをClojureで構築した経験があります。

### [サイボウズスタートアップス](https://cstap.com/)

- Clojureで開発しているサービス
  - [安否確認サービス2](https://anpi.cstap.com/): 次世代型安否確認システム
  - (開発中)[kintone](https://kintone.cybozu.com/jp/)と連携するサービス

主にClojureを使ってWebアプリケーションを開発しています。
最近作っている新規のサービスは全てClojure/ClojureScriptを利用しています。

サイボウズスタートアップスの[採用情報](https://cstap.com/jobs/)

### [株式会社オプト Opt Technologies](https://www.opt.ne.jp/opttechnologies/)

- Clojure利用プロダクト
  - 社内依頼管理システム TASK DRIVER
    - cf. [Clojureをプロダクトに導入した話 - Opt Technologies Magazine](http://tech-magazine.opt.ne.jp/entry/2017/09/06/074020)

"Opt Technologies"とは、株式会社オプトのエンジニア仮想組織です。
エンジニア自身による自治や組織改善を大事にしながら、アドテクノロジーを中心としたプロダクトの開発を行っています。
["INNOVATION AGENCY"](http://www.opt.ne.jp/home/opt/vision/)を標榜するオプトのINNOVATIONの源泉となるべく、
様々な技術を日々追求し、新しい価値創造の実現を目指しています。

Opt Technologiesの採用情報は[こちら](https://open.talentio.com/1/c/opt-smc/requisitions/473)です。

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
API/サービスごとに最適なモノを選択するという方針のもと、様々な言語/フレームワークを使用しています。([JOB DESCRIPITON](https://uzabase-inc.workable.com/j/550B7FDB1B)の"＜技術スタック＞"欄)
