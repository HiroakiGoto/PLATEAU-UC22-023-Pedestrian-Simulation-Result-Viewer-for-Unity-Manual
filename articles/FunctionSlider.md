# 時系列人流可視化機能
この機能は、時間ごとの人流をスムーズに表示するスライドバー機能です。

![](../images/visualize-slider.png)

## 機能概要
- 任意の時点の人流をスライドバーまたはスライドバー横のボックスから指定し可視化します。
- スライドバーで指定された時刻、もしくはテキストボックスで指定されたシミュレーションステップ数に対応する位置にエージェントを配置します。
- 8:00時点を0ステップとし、シミュレーション内での1秒あたり1ステップ進むようになっています。
    - すなわち、9:00時点では3,600ステップとなります。
    
## 操作方法
- スライドバーにあるボタンをスライドバー上で左右に動かすことで、確認したい時点の人流を表示できます。
![](../images/visualize-slider-button.png)

- スライドバー横にあるテキストボックスをクリックし、シミュレーションステップ数を入力することで、確認したい時点の人流を表示できます。
![](../images/visualize-slider-textbox.png)
    