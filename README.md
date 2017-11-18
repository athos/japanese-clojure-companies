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
  - (開発中)クリーニングチェーン向けレジ・工場システム

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

Opt Technologiesの[採用情報](https://open.talentio.com/1//c/opt-smc/requisitions/142)はこちらです。

### [LiME株式会社](http://limehair.jp/corp/)

事業内容

- 美容師および美容に関わる業態向けのサービスの運営

プロダクトと利用技術

- 美容師向け顧客・カルテ管理アプリ [LiME](http://limehair.jp/): Objective-C,Java
- サロン向けカルテ・予約管理Webシステム [LiMEsalon](http://limehair.jp/salon): Javascript(React.js)
- 美容師向け送客WEBサービス [STEKiNA](https://stekina.com/): ClojureScript
- 開発中新規プロダクト RiZM(仮): ClojureScript(Re-natal)
- サーバーサイドは各プロダクトにおいて、APIやBatchすべてClojureです。


現在(2017/11)、ReactNativeをClojureで扱える[Re-natal](https://github.com/drapanjanas/re-natal)で新規アプリ開発をしています！
コアな部分はすべてClojure製なので扱えるとマジ即戦力です。
iOSアプリエンジニアも大大大募集してます。

「どんな人でも美を簡単に表現できる世界を創造する」をモットーに
現役美容師が立ち上げた会社です。テクノロジーの力でこれを実現できるよう
少ないメンバーで日々奮闘中です

