### 第33回生理科学実験技術トレーニングコース

# 拡散強調MRIデータ解析による白質線維束分析入門

2022年8月2-5日に生理学研究所でWeb開催する **『第33回生理科学実験技術トレーニングコース・拡散強調MRIデータ解析による白質線維束分析入門』** の参加者を対象とした情報提供サイトです。随時、情報を追加していきますので、このサイトへ定期的にアクセスするようにして下さい。

## 新着情報

- 2022.07.05 トレーニングコース用ウェブサイトを立ち上げました


## スタッフ（運営、講師、チューター）

- 生理学研究所　感覚認知情報研究部門　竹村浩昌


## 開催案内

- Web開催です



## 当日のタイムテーブル

日程 | 内容
---- | ----
8月2日 |
08:50 | Zoomオープン・入室開始
09:00-09:10 | ガイダンス（竹村）
09:10-09:40 | 講義（１）：なぜ白質を研究するか？
09:40-10:00 | 参加者自己紹介
10:00-10:15 | 休憩
10:15-10:45 | 講義（２）：拡散強調MRIの原理、およびデータフォーマット
10:45-11:20 | データのダウンロード・Lin4Neuro設定確認
11:20-12:15 | 実習：nifiヘッダーの確認とMRViewでのデータの読み込み
12:15-13:00 | -- 昼休み --
13:00-13:30 | 研究発表：宮田季和（大阪大学大学院生命機能研究科　大学院生）
13:30-14:10 | 講義（３）：拡散強調MRIに必要なprerprocessingの解説
14:10-14:40 | 実習：Preprocessing（３〜４名ごとのブレイクアウトルーム）
14:40-14:55 | 休憩
14:55-17:00 | 実習：Preprocessing（３〜４名ごとのブレイクアウトルーム）
17:00-17:30| 質疑応答
8月3日 |
08:50       | Zoomオープン
09:00-09:40 | 講義（４）：Diffusion Tensor Modelの解説
09:40-10:15 | 実習：Tensor Model Fitting (MRTrix,３〜４名ごとのブレイクアウトルーム)
10:15-10:30 | 休憩
10:30-11:10 | 講義（５）：Model beyond tensor
11:10-12:15 | 実習：CSD(MRTrix,３〜４名ごとのブレイクアウトルーム)
12:15-13:00 | -- 昼休み --
13:00-13:45 | 講義（６）：Tractography（１）
13:45-15:10 | 実習：Streamlineの生成 (MRTrix,３〜４名ごとのブレイクアウトルーム)
15:10-15:25 | 休憩
15:25-16:05 | 講義（７）：Tractography（２）
16:35-17:00| 質疑応答
8月4日 |
08:50 | Zoomオープン
09:00-09:40 | 講義（８）：白質線維束の分類と歴史、トラクトグラフィーからの線維束の同定
09:40-10:30 | 実習：SLF I, II, IIIを求める（手動ROI,３〜４名ごとのブレイクアウトルーム）
10:30-10:45 | 休憩
10:45-11:15 | 実習の結果発表
11:15-12:15 | 実習：他の線維束を手動ROIで求める（３〜４名ごとのブレイクアウトルーム）
12:15-13:00 |  -- 昼休み --
13:00-13:30 | 実習の結果発表
13:30-14:00 | 講義（９）：Tract Profile
14:00-14:15 | MATLAB AFQの画面共有によるデモ
14:15-14:55 | 講義（１０）：Diffusion MRI：できること・できないこと＋より高度なアプローチの紹介
14:55-15:15 | デモ
15:15-15:40 | 休憩
15:40-16:00 | 質疑応答
16:00-17:00 | 外部講演（１）BabyAFQ: Mareike Grotheer先生
17:00- | オンライン全体交流会
8月5日 |
08:50 | Zoomオープン
09:00-09:20 | 昨日の講演のフォローアップセッション
09:20-10:20 | 外部講演（２）pyAFQ: John Kruper先生
10:20-10:35 | 休憩
10:35-11:05 | pyAFQについてのフォローアップセッション
11:05 | グループワーク説明
11:05-12:15 | グループワーク
12:15-13:00 |  -- 昼休み --
13:00-13:30 | グループワークまとめ
13:30-14:10 | グループワーク発表
14:10-14:30 | まとめと講評
 | |　


----

 ## パソコンの準備について

 - トレーニングコースでは、受講者にご自身でPCを準備して頂き、実際に操作しながらコマンドラインについて学んでいきます。PCのスペックについては、以下の **推奨条件** を参考にして下さい

   - OS: Windows10,11 64bit版 または macOS 10.14.6（Mojave）- 12.0.1 (Monterey）
   - CPU: Intel Core i7/i9、Intel Core i5（クロック周波数2.0GHz以上）、または AMD Ryzen 5以上の性能を有するもの **注意: 現在、Apple M1はVirtualBoxで仮想マシンを動作できないため、Lin4Neuroは動作しません。以下をご覧ください**
   - メモリ：8GB以上 (可能ならば16GB以上を推奨します)
   - ハードディスク：**<u>100GB以上の空き容量</u>** (外付けハードディスクも可)
   - 2ボタン以上のUSBマウス (必須ではありませんが、持っていると便利です)
 
  - Lin4Neuroでの受講を推奨しますが、macOS native 環境で受講したい方々のために、インストラクションを準備しました。[こちら](https://kytk.github.io/nips-web-202208/macOS_native.html)をご確認ください 

  -　Zoomは画面共有でメモリを相当消費します。そのため、Zoomで受講するための別のPCもしくはタブレットをご準備ください。解析用のPCとZoom用のPCは別々で全く支障ありません

----

## Zoomの設定

- トレーニングコースはZoomにて開催します

- Zoomは2022年7月1日現在、バージョン5.11.1になっています。こちらを入手してください
    - 以下のリンクをクリックすることで、最新版のZoomを入手できます。(すでにインストールされている方でも以下のリンクからインストーラーを入手することでアップデートできます)
    - Windows: [https://zoom.us/client/latest/ZoomInstaller.exe](https://zoom.us/client/latest/ZoomInstaller.exe)
    - macOS(Intel Core): [https://zoom.us/client/latest/Zoom.pkg](https://zoom.us/client/latest/Zoom.pkg)
    - macOS(Apple M1): [https://zoom.us/client/latest/zoomusInstallerFull.pkg?archType=arm64](https://zoom.us/client/latest/zoomusInstallerFull.pkg?archType=arm64)

- 画面の共有の設定だけ変更すると受講しやすくなります
    - Zoomを起動し、サインインをクリックします

    ![Zoom起動画面](img/zoom1.png)

    - サインインします（**メールでお知らせしたミーティングID、パスワード**を入力）

    ![Zoomサインイン](img/zoom2.png)

    - ホーム画面で右上にある歯車アイコンをクリックします

    ![Zoom設定](img/zoom3.png)

    - 左のメニューから「画面の共有」のタブをクリックし、「画面を共有している場合のウィンドウのサイズ」を「現在のサイズを保持する」に変更します。これにより、講師が画面を共有した場合に、Zoomが全画面モードにならずにすみます

    ![画面共有設定](img/zoom4.png)

    - Zoomの設定は以上で終了です

----

## Slackの設定

- チュートリアルでは Slack というツールを使って、事務連絡や当日の質疑応答を行います。以下の手順で設定してください


### ウェブブラウザでの設定

 - 受講者の皆様にメールで招待状が届きます。「今すぐ参加」をクリックしてください

 - Slackのアカウントを持っていない場合、アカウント作成画面が出てきます。"メールで続行する"をクリックしてください

 - 日本語の氏名、ご自身で決めたパスワードを入力し、"アカウントを作成する"をクリックしてください


### アプリの入手

 - 次に、[slackのダウンロードサイト](https://slack.com/downloads)にアクセスし、自分の使っているOSにあったSlackアプリをダウンロードしてください。Slackはブラウザからも利用可能ですが、アプリの方が使い勝手がいいかもしれません。スクリーンショットはMac版Slackとなっていますが、Windowsの方はWindows版をダウンロードしてください

  ![アプリのダウンロード](img/slack05.png)


 - アプリを起動すると、はじめての方の場合は、下図のような画面になりますので、"Sign In to Slack"をクリックします

  ![アプリのサインイン](img/slack06.png)

 - すでにSlackをお使いの方は、以下の3つのどれかの方法で、ワークスペースにサインインします

 - 左にある＋キーをクリックして、「他のワークスペースにサインインする」をクリックします

  ![ワークスペースの追加](img/slack12.png)

 - 左上のハンバーガーメニューをクリックし、「ワークスペースを追加」-> 「他のワークスペースにサインインする」をクリックします

  ![ハンバーガーメニュー](img/slack21.png)

 - メニューの「ウィンドウ」から「他のワークスペースにサインインする」をクリックします

  ![ウィンドウメニュー](img/slack22.png)

 - ログイン画面が出ますので、メールアドレスを入力します

  ![メールアドレス](img/slack07.png)

 - そうすると、メールアドレスにログインのためのコードが送信されますのでそれを入力します

  ![サインインコード](img/slack08.png)

 - NIPS TC dMRI 2022 をクリックします

  ![ワークスペースの選択](img/slack09.png)

 - "Slackを開きますか？"という質問が出た場合は、"Slackを開く"をクリックします

 - そうすると、第33回生理研トレーニングコース用のワークスペースに入ることができます


### チャンネルの使い分け

 - いくつかチャンネルが準備されています。以下のように使い分けていきます

 - 01_事前準備: 事前準備に関する連絡を行うチャンネルです。

 - 02_事務連絡: トレーニングコースに関する事務連絡を行うチャンネルです。

 - 03_講義への質問: 講義に関する質問を受けるチャンネルです。

 - general: 上記以外の質問を受けるチャンネルです。質問により、回答できない場合があります

### お願い

 - トレーニングコースでは、すべて実名でやりとりをしたいと思います。ニックネームではなく、ご自身の名前をフルネームで表示するようにしてください。スタッフはすべて氏名の前にS_がついています

 - テキストだけのやりとりになりますので、どうぞやわらかな言葉での発言をしていただくようにお願いいたします。



----

## 事前準備

- **トレーニングコースの準備に、約3-4時間必要となります。なお、準備が終わった方にのみ当日のZoomのリンクが送信されますので、必ず準備を行ってください。準備なしの参加はできません**

- 今回は完全オンライン開催のため、受講者専用サイトに記載されているVirtualBox＋Lin4Neuroの組み合わせによる参加を前提とします。脳画像解析の初心者の方々は受講者専用サイトに記載されている通りに事前準備を行いトレーニングコースへ参加することを強く推奨します

- **Lin4Neuroは、筑波大学の根本清貴先生が開発、配布されているLinux上に構築された脳画像解析ツール群です。根本先生のご厚意により、トレーニングコースで利用させて頂きます**
  - [Lin4Neuro](https://www.nemotos.net/?page_id=161)

- 自分自身で基礎的なトラブルシューティングが行える脳画像解析の経験が豊富な中級者以上の方々は、受講者専用サイトに記載されている以外の解析環境（例えば受講者自身が構築した解析環境など）でもトレーニングコースに参加可能ですが、原則としてチューターによるサポートの対象外とさせて頂きます。ご理解、ご協力の程、よろしくお願いします

- 今回のトレーニングコースで使用するLin4Neuroのバージョンは、L4N-2004-NIPS-20220321です。**過去のLin4Neuroは使用できませんのでご注意ください**

- ソフトウェアとデータのダウンロードで合計**30GB程度ダウンロードします**。Pocket Wi-Fiなどでは通信量にご注意下さい。**職場やご自宅のLAN環境からの作業**を強くお奨めします
　

### 1. トレーニングコース用Lin4Neuroのセットアップ

- **以下のページを参考にセットアップをして下さい**
  - [生理研トレーニングコース用Lin4Neuroのセットアップ](https://kytk.github.io/nips-web-202208)

- Lin4Neuroがセットアップできましたら、ターミナルウィンドウ上で 

mrview 

と打ち込み、MRTrixの画面が立ち上がるかについて確認をお願いします。

### 2. データの入手 (所要時間約10分)

- トレーニングコースに使うデモデータは非常に大きいため、別にダウンロードしていただきます

- データのダウンロード手順については、別途受講者の方にメールにて連絡します


### 3. Lin4Neuro への Google chrome のインストール (所要時間5分)

- Lin4NeuroにGoogle Chromeをインストールしたい方向けに、説明動画を準備しました。[こちら](https://vimeo.com/487737208)からご確認ください
 

---

## 問い合わせ

- 準備がうまくいかない時は、メールで案内した Slack の事前準備チャンネルで問い合わせ下さい。
