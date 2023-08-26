# 芝生祭実行委員会2023総務課

ツール・リポジトリ・メモなどのリンク集です。
index.htmlはこのMarkDownファイルにリンクされています。

## リンク

一部のGoogle関連サービスへのリンクには、学校Googleアカウントでログインする必要があります。  
GASのバージョン管理には、[clasp](https://github.com/google/clasp)を使っています。便利です。

- [議事録管理ツール-閲覧サイト](https://tsukasatakahashi-z8.github.io/shibafufes2023-somu/jump.html)
- 企画書管理ツール(未公開)
- 活動申請システム(未公開)
- [来場者カウンタrepo](https://github.com/TsukasaTakahashi-z8/shibafes2023-visitors-counter)
- [QRコードリーダv1 repo](https://github.com/TsukasaTakahashi-z8/shibafes2023QR)
- 混雑情報提供システム(未公開)
- 来場者投票システム(未公開)

## TOC

## 議事録管理ツール

指定のGoogleSpreadSheetに記入されたMarkDown形式の議事録を、WEB上でまとめて見ることができます。  
GASで、編集スプレッドシートに溜まった議事録から議事内容を取得し、表示させています。

| TOPページ | 議事録閲覧ページ | 編集スプレッドシート |
|---|---|---|
|![image](https://github.com/TsukasaTakahashi-z8/shibafufes2023-somu/assets/127503211/365d0434-3a51-46a4-8e1f-97feed2b0f4d)|![image](https://github.com/TsukasaTakahashi-z8/shibafufes2023-somu/assets/127503211/76ee80da-2fcc-4c73-bb6f-eb8b6c371c5d)|![image](https://github.com/TsukasaTakahashi-z8/shibafufes2023-somu/assets/127503211/a6b6dd22-9025-4416-bf83-5ee06e53e111)|

- [閲覧サイト](https://tsukasatakahashi-z8.github.io/shibafufes2023-somu/jump.html)
- 議事録入力スプレッドシート(非公開)

## 企画書管理ツール

芝生祭の各出展団体が記入する企画書を管理します。

- 企画書の生成
- 企画書をほぼリアルタイムで一覧表示
- 企画書のロック、集計
- 企画書の顧問署名機能

## 活動申請システム

実行委員会の各課が、活動を顧問に申請するときに使う、GAS入スプレットシートです。  
申請すると、申請リストに追加され、顧問の先生にメールが飛びます。
| 申請フォーム | 申請一覧 |
| --- | --- |
| ![image](https://github.com/TsukasaTakahashi-z8/shibafufes2023-somu/assets/127503211/e8129cb1-e54f-48a0-a71f-613807e47bd9) | ![image](https://github.com/TsukasaTakahashi-z8/shibafufes2023-somu/assets/127503211/b279e18a-bfe4-4407-a7d8-028ab9d9bb36) |

## 来場者カウンタ

ゲートで来場者に押してもらったボタンを基に、来場者をカウントし、巨大7セグに表示させるものです。  
本当は、人感センサ使ったりカメラで顔認識したりしてやりたかったですが、予算やその他諸々の事情により、没になりました。
- [リポジトリ](https://github.com/TsukasaTakahashi-z8/shibafes2023-visitors-counter)

## QRコードリーダ

各出展企画で、来場者のQRコードを読み取るためのWEBページです。  
次で紹介する混雑情報提供システムに、QR情報を送信します。また、混雑情報提供システムが乗ってるサーバで公開します。

- [QRコードリーダのリポジトリ](https://github.com/TsukasaTakahashi-z8/shibafes2023QR)

## 来場者投票システム

来場者が、企画投票を行うときに使います。2023年度は、混雑情報提供システムと相乗りサーバで提供し、アクセスの際も同じQRコードを利用します。  

