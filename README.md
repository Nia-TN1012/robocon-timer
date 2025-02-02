# Robocon Timer by Nia T.N. Tech Lab.
Robocon Timer by Nia T.N. Tech Lab.（以下、Robocon Timer）（旧Chronoir Robocon Timer）は、ロボコンなどで使用できるタイマーです。

## Abstract
|アプリ名|Robocon Timer by Nia T.N. Tech Lab.|
|---|---|
|(読み名)|ロボコンタイマー by ニアの技術研究所|
|アプリタイプ|Windowsデスクトップアプリ（WPFアプリ）|
|作者名|智中 ニア（ Nia Tomonaka ）|
|所属名|Chronoir.net|
|バージョン|1.12.7.200|
|作成日|2015/09/14|
|更新日|2025/02/02|
|種別|フリーソフトウェア（ BSDライセンス ）|
|開発言語|C# 6.0|
|対応OS|Windows 10 / 11|
|必要ランタイム|.NET Framework 4.8以上|
|再配布|可（【再配布】欄を参照してください ）|
|転載|可|
|ホームページ|https://tech.nia-tn1012.com/|
|GitHub|https://github.com/Nia-TN1012/robocon-timer
|X（旧Twitter）|[@nia_tn1012](https://x.com/nia_tn1012)|

## ファイル構成
ファイルの構成は以下の通りになっています。

CRTimerフォルダ

|ファイル名|概要|
|:---|:---|
|ScoreSheet|スコアシートが入ったフォルダーです。|
|RoboconTimer.exe|実行ファイルです。|
|RoboconTimer.exe.config||
|teams.xml|チーム名リストファイルです。|
|settings.json|セッティング時間、試合時間を設定するファイルです。|
|Robocon Timer マニュアル.pdf|Robocon Timerのマニュアルです。|
|readme.txt|このファイルです。|
|LICENSE.txt|BSDライセンスの文です。|

## 開発環境
開発環境にはVisual Studio Community 2022を使用しました。

## 動作環境
|OS / ランタイム|種類 / バージョン|
|---|---|
|OS|Windows 10 / 11以降|
|必要ランタイム|.NET Framework 4.8以上|

* Windows 11以降では、ARMアーキテクチャーにも対応しています。
* Windows 8.1以前では動作対象外です。
* 本ソフトウェアは全画面で表示します。ディスプレイの解像度は1280×768以上を推奨します。

## ダウンロード＆インストール
「[Robocon Timer.zip](https://tech.nia-tn1012.com/wp-content/uploads/Apps/Robocon%20Timer.zip)」をダウンロードし、任意の場所に解凍します。
インストールは不要です。

## アンインストール
レジストリは使用しておりません。解凍したファイルをフォルダごと削除してください。

## 使い方
Robocon Timer マニュアル.pdfを参照してください。

## 著作権
本ソフトウェア（後述の一部の素材を除く）の著作権は 智中ニア（ Nia Tomonaka ） が所持しています。
　Copyright (C) 2014-2025 Nia T.N. Tech Lab.

## 素材について
* 試合終了時の効果音（ Finish.wav ）はポケットサウンドの素材を使用しております。  
ポケットサウンド : https://pocket-se.info/

* カウントダウン時の効果音はBeam2002で作成しました。また、効果音の加工はSound Engine Freeを使用しております。  
Sound Engine : https://soundengine.jp/

* "Nia T.N. Tech Lab."ロゴ及び、実行ファイル用のアイコンは本ソフトウェアの再配布（ 改良したものも含みます ）のための配布ができます。

## 再配布 / ライセンス
* 本ソフトウェアはフリーソフトウェアです。個人的使用範囲を超えない限り、無許可で自由に配布できます。
* 本ソフトウェアにはBSDライセンスが適用されています。ライセンス文は LICENSE.txt を参照してください。

## 免責事項
* 本ソフトウェアを使用したことにより生じたいかなる障害､損害において作者は一切責任を負わないものとします｡
* 作者はバグが発見された場合においても、その修正、バージョンアップの義務を負わないものとします｡

## 

## 謝辞
本ソフトウェアを使用している皆様に、感謝いたします。

## リリースノート

* Ver 1.12.7.200 ( 2025/02/02 )
    * 本ソフトウェアで使用しているフレームワークを.NFT Framework 4.8に変更しました。これに伴い、サポート対象はWindows 10以降になりました。
    * アプリの設定画面から、アプリ終了ボタンを押せるようにしました。
    * 試合の表記を「Play」から「Game」に変更しました。
    * settings.jsonの「PlayTime」を「GameTime」に変更しました。ただし、旧バージョンで作成したsettings.jsonは引き続き利用でき、「PlayTime」の値を読み取ります。
    * Webサイトのリニューアル及び、ドメイン変更に伴い、サイト名やロゴなどを更新しました。

* Ver 1.11.6.170 ( 2016/05/25 )  
    * チーム名リストの保存の処理を少し改善しました。

* Ver 1.10.5.164 ( 2016/05/19 )  
    * アプリの動作を多少改善しました。

* Ver 1.03.4.146 ( 2016/03/10 )  
    * アプリの設定画面にて、「グループ名ごとにソート」ボタンを押しても動作しない不具合がありましたので、修正しました。
    * ソースコードを少し最適化しました。

* Ver 1.02.3.141 ( 2016/01/06 )  
    * アプリの動作を多少改善しました。

* Ver 1.00.2.124 ( 2015/09/27 )  
    * 画面の解像度によって、一部のボタンの文字列が隠れてしまうことがありましたので修正しました。

* Ver 1.00.1.120 ( 2015/09/14 )  
    * 初版リリース

## teams.xmlのフォーマット
teams.xmlは以下のような構成にする必要があります。

---

```xml:team.xml
<?xml version="1.0" encoding="utf-8"?>
<!-- チーム名リスト -->
<teams>
  <team name="Team 1" group="Team Group" />
  <team name="Team 2" group="Team Group" />
  <team name="Team 3" group="Team Group" />
  <team name="Team 4" group="Team Group" />
  <team name="Team 5" group="Team Group" />
</teams>
```

---

* リストに登録したいチーム数だけ、teamノードをteamsタグ内に入れます。
* name属性にチーム名が入ります。
* group属性にグループ名が入ります。

## settings.jsonのフォーマット

settings.jsonは以下のような構成にする必要があります。

------------------------------------------------

```json:settings.json
/* 
    セッティング時間、試合時間を定義します。 
    VictoryMessageの値は文字列型、それ以外の値は全て数値型です。

	ReadyTimeとAutoMachineLanchTimeLimitの値はTimeSpan.FromSecondsに、
	SettingTimeとGameTimeの値TimeSpan.FromMinutesに渡します。
*/
{
    /* Victory画面に表示するメッセージ（ Def. "Congratulations !" ） */
    "VictoryMessage": "Congratulations !",
    /* 準備時間（秒） ( 3 ～ 30 / Def : 5 ) */
    "ReadyTime": 5,
    /* セッティング時間（分） ( 0.25 ～ 60.0 / Def. 1.0 ) */
    "SettingTime": 1.0,
    /* 試合時間（分） ( 0.25 ～ 60.0 / Def. 3.0 ) */
    "GameTime": 3.0,
    /* 自動機発進のタイムリミット（秒） ( 0 ～ 60 / Def. 15 ) */
    "AutoMachineLanchTimeLimit": 15
}
```

---