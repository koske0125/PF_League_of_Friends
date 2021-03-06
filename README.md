# LeagueofFriends

## サイト概要
### サイトテーマ
RiotGames社の提供するMOBAゲーム『LeagueofLegends』のフレンドを探すことができるサイトです。
フレンドを募集するという特性から大枠としてはマッチングサイトに分類できるかと思いますが
実際の機能としては、DM機能や掲示板機能も提供するためマッチングサイトとコミュニティサイトの機能を組み合わせたサイトです。

### テーマを選んだ理由
現在、LeagueofLegendsのフレンド募集はTwitter上で募集するというのが一般的ですが下記の問題があります
 * Twitterという特性上、フレンド募集ツイートが時間が経つにつれて埋もれてしまう
 * 明確なフォーマットが存在していないため、探している条件にあったフレンドを探しづらい

また次点でよくある募集方法としては『掲示板』がありますが下記の問題があります
 * 管理が行き届いていなく、本人になりすました悪意のある投稿が散見される
 * Twitter同様、明確なフォーマットが存在していないため、探している条件にあったフレンドを探しづらい

LeagueofLegendsは5人で1チームとなり、プレイするゲームとなっているためフレンドの有無はプレイヤーのゲーム体験を大きく左右する重要な要素です。
このサイトでは同じ初心者同士で遊びたい・同じぐらいのランク帯で一緒に遊べる人を探したい・上手い人に教えてもらいたいなど・・・
様々な条件で検索をすることができ、条件にあったフレンドを見つけていただきプレイヤーのゲーム体験の向上を目指しています。

### ターゲットユーザ
 * LeagueofLegendsでフレンドを探しているプレイヤー
 * 好きなチャンピオンやeSportsチームについて語りたいというプレイヤー
 * 掲示板やTwitterでの交流に不便を感じているプレイヤー

### 主な利用シーン
 * 初心者同士で集まって遊びたいとき
 * 同じぐらいの実力のプレイヤーを探して、Rankモードをプレイしたいとき
 * 実力のあるプレイヤーに指導してもらいたいとき
 * 好きなチャンピオンのビルドやコンボなどについて議論したいとき
 * 同じeSportsチームが好きなプレイヤーで集まって、応援したいとき

## 設計書
 * [ER図](https://drive.google.com/file/d/1gTU8DJgIKC0z42o7WGf7QfHHFEYuFjnG/view?usp=sharing)
 * [データベース定義書](https://docs.google.com/spreadsheets/d/1byvsqv4GgdmQdKEnWi0d9fZa3LnqF4t8oLXNo4KUT_M/edit?usp=sharing)
 * [アプリケーション詳細設計](https://docs.google.com/spreadsheets/d/1gCCfmHZJ4OCQThPaxxat-wxfRiFMT9tu/edit?usp=sharing&ouid=117394524301926319881&rtpof=true&sd=true)

## 開発環境
- OS：Linux(CentOS)
- 言語：HTML,CSS,JavaScript,Ruby,SQL
- フレームワーク：Ruby on Rails
- JSライブラリ：jQuery
- IDE：Cloud9

## 使用素材
- サイト内で使用されているRiotGames社の著作物は下記のガイドラインに基づいて利用しております。

[Legal Jibber Jabber ポリシー](https://www.riotgames.com/ja/legal) (RiotGames社のページに飛びます)

>Q: リーグ・オブ・レジェンドに関連する無償のアプリケーション又はウェブサイトを作成してもよいですか。
>
>A: 既にたくさんのファンの方々がこのような無償のアプリケーションやウェブサイトを作成してくださっています。
>
>当社はプロジェクトの支援又は公式承認はいたしませんが、このようなプロジェクトを歓迎いたします。
>
>上記のとおり、本ガイドラインをご遵守いただき、かついかなる他者の権利も侵害しない限り、リーグ・オブ・レジェンドに関連する無償のアプリケーション又はウェブサイトをご作成いただくことには、原則として問題はございません。
>
>Q: リーグ・オブ・レジェンドに関連する無償のアプリケーション又はウェブサイトを作るためにライアットゲームズの画像等の知的財産を使用してもよいですか。
>
>A: 本ガイドライン記載のとおり、画像はご利用いただけます。但し、当社ロゴはご利用いただけません。

## 重要事項

LeagueofFriendsは、ライアットゲームズが公式承認するものではなく、ライアットゲームズ又はリーグ・オブ・レジェンドの製作・管理に正式に関与したいかなる者の見解・意見に基づくものではありません。

リーグ・オブ・レジェンド及びライアットゲームズは、Riot Games, Inc.の商標又は登録商標です。

リーグ・オブ・レジェンド © Riot Games, Inc.
