## 雰囲気メガネ Android SDK
雰囲気メガネSDK（ソフトウェア開発キット）を用いれば、ご自分で開発したアプリと〈雰囲気メガネ〉を連携させて、思いのままにメガネを光らせ、音を鳴らすことができます。
また、各種センサーのデータを活用したソフトウェアの開発も可能です。
SDKは無償であり、開発したアプリは自由に公開できます。ぜひ独創的で楽しいアプリを作ってください。  
  
※雰囲気メガネ Android SDKを使用するには、[雰囲気メガネアプリ](https://play.google.com/store/apps/details?id=com.namaemegane.fun_iki)のインストールが必要です。

## 開発環境
Android Studio 2.0以降

## 対応OS
Android 4.4以上

## SDK本体
[funiki-sdk-1.jar](https://github.com/FUNIKImegane/FunikiSDK_Android/blob/master/SDKSample/sample/libs/funiki-sdk-1.jar?raw=true)

## 雰囲気メガネSDK 1.0で使用できる機能
* LED、ブザー  
LEDの色と、その色に変わる遷移時間を指定して、光りをコントロールすることができます。  
同時にブザーの音の高さ、音の強さ、持続時間を指定して鳴らすことができます。

* 加速度、角速度センサ  
加速度と角速度の情報を取得できます。取得できる間隔は接続状況によって変化します。

* プッシュ・ボタン  
プッシュ・ボタンで発生したイベント（シングル・プッシュ、ダブル・プッシュ）を取得できます。

* バッテリー残量  
バッテリー残量を3段階で取得できます。

* アラーム設定  
曜日、時、分を指定してアラームを設定できます。

* テンポ  
BPMを設定して一定の間隔で光らせることができます。

## ドキュメント
[JavaDoc](https://funikimegane.github.io/FunikiSDK_Android/JavaDoc/)
