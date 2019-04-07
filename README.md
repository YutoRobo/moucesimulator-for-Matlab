# moucesimulator-for-Matlab
ROSをつかわなくて平気になりました

❶操作方法

[simulator]

・Espキー: 終了

・Spaceキー: リセット

・Enterキー: 壁の変更モード切り替え

・画面上の change cameraボタン: カメラ切り替え

[matlab]

・Wall DistanceのDisplay: 4つの距離センサからの距離データ[m]が表示される

・Left Veocity, Right Velocity: それぞれの回転速度[degree/second]を入力


❷事前準備

[matlabを使う場合]

1: このファイルをダウンロードする。

2: matlabをインストールする。

3: matlab に Instrument Toolbox を追加する。


[それ以外の方法で通信する場合]

1: このファイルをダウンロードする。

2: 自分のプログラムにudpの通信過程を実装する。
  現在、IPアドレスはlocalhostに固定しています
  ポートは、
    シミュレータの送信ポートが50001
    プログラム側の受信ポートが50002
    プログラム側の送信ポートが50003としています


❸動作手順

[matlabを使う場合]

1: MouceSimulator/ForWindows/NHK_4soku.exe を開く(Linuxの場合はforLinux)。

2: matlabを開き、MouceSimulator/udpConnector.slx を実行する。

3: udpConnectorの再生ボタンを押す。

4: 動く    
