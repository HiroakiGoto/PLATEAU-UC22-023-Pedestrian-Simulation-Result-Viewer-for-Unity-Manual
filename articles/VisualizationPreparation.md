# 利用準備
ここでは、歩行シミュレーション結果表示アセットを利用するための準備方法について記載します。

## 歩行シミュレーション結果可視化実行準備手順
1. 「PLATEAU-UC22-023-Pedestrian-Simulation-Result-Viewer.zip」内にある、「simulation-result」内にある下記6ファイルを、「Assets」と同じディレクトリに格納してください。
![](../images/folder-copy.png)
- 平日_平常時
- 平日_イベント実施・広告設置時
- 平日_イベント実施・広告非設置時
- 土日祝日_平常時
- 土日祝日_イベント実施・広告設置時
- 土日祝日_イベント実施・広告非設置時


2. また、「simulation-result」内には「simulation-log.zip」が格納されているので同ファイルを併せて解凍してください。
![](../images/get-simulation-log.png)


3. 「simulation-log.zip」を解凍すると、下記6ファイルが含まれています。下記ファイルを1. で格納したディレクトリに格納してください。
- agent_log_平日_平常時.csv　
    （-> 「平日_平常時」直下に格納してください。）
- agent_log_平日_イベント実施・広告設置時.csv
    　（-> 「平日_イベント実施・広告設置時」直下に格納してください。）
- agent_log_平日_イベント実施・広告非設置時.csv
    　（-> 「平日_イベント実施・広告非設置時」直下に格納してください。）
- agent_log_土日祝日_平常時.csv
    　（-> 「土日祝日_平常時」直下に格納してください。）
- agent_log_土日祝日_イベント実施・広告設置時.csv
    　（-> 「土日祝日_イベント実施・広告設置時」直下に格納してください。）
- agent_log_土日祝日_イベント実施・広告非設置時.csv　
    （-> 「土日祝日_イベント実施・広告非設置時」直下に格納してください。）
![](../images/csv_copy.png)

## 歩行シミュレーション結果可視化実行手順
1. 「Assets」>「PedestrianFlowViewer」内にある「Sample Scene」を「Hierarchy」にドラッグアンドドロップします。
![](../images/set_asset.png)

2. 実行ボタンを押すと、データのロードが始まります。
![](../images/unity-execute.png)

3. 「Game」画面に移り、実行するシナリオをGame画面上部プルダウンから選択し、「Load Scenario」を押すと、シミュレーション結果データが読み込まれます。
![](../images/set_scenario.png)

なお、本アセットで実装した機能を実行ファイルで確認したい場合は、[参考：Unity実行ファイル](UnityExe.md)を参照のうえご確認ください。