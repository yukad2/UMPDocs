# BGMを設定する
## Unityに音源をインポートする
インポート後、Force to Monoを選択することで軽量化することができます。(モノラル化)チェックを入れて右下のApllyを押してください。
![img](https://i.gyazo.com/8311f0cc5827b74dac82d4522a0e1701.png)

## 追加する
Hierarchyから`BGMController`を選択してください。デフォルトでは`UdonMediaPlayer/BGMController`です。

Udon Behaviour内、Bgmsourcesを選択して、曲数を入力してください。Projectから音源をドラッグアンドドロップしてください。
![img](https://i.gyazo.com/554649dc08911b2b5e0deabdb61cda97.png)

!!! Warning
    短すぎる音源(効果音など)や長過ぎる音源(1時間以上)は正常に再生されない場合があります。

!!! Tip
    もし、VRCに持ち込んで音楽が再生されない場合、MusicPlayerUIをActive(Inspectorのチェックボックス)にしてからCompile All UdonSharp Programsをしてみてください。
    ![tmpnotice](https://i.gyazo.com/a7bf80fcf2862ef90309f7e7a348ce24.png)

    それでも動かない場合はご一報ください。[@yukad2](https://twitter.com/yukad2_)

!!! summary
    これで終了です。Syncの使用上ローカルでは動作しない場合があります。アップロードして確認してください。