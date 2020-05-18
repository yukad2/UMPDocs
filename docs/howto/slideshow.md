# スライドショーを設定する
スライドショーへの画像の追加、変更を説明します。

## 画像を変更する
Hierarchyから`SlideshowController`を探してください。デフォルトでは`UdonMediaPlayer/MainUI/HomeUI/SlideshowController`です。
![img](https://i.gyazo.com/caea5e8b7175820d3cfcb75420f8523f.png)

子のRawImageを選択してInspecterを見てください。Raw Image - TextureにProjectから画像をドラッグアンドドロップしてください。
![img](https://i.gyazo.com/ca2bb4bbdfe7f359b660f6c2ae2c257c.png)

!!! summary
    画像の変更はこれで終了です。UnityのPlayボタンを押して確認してください。

## 画像を追加、削除する
### 追加する時
子のRawImageを選択して`Ctrl+D`で複製してください。複製したRawImageには変更する時と同様にTextureを指定してください。

![img](https://i.gyazo.com/9449c6785d7426eb9f3c03a597ae14ac.png)

`SlideshowController`を選択してUdon Behaviourを見ます。Imgsを開き、SizeにRawImageの枚数を入力してください。そして、複製したRawImageを新しくドラッグアンドドロップで追加してください。

![img](https://i.gyazo.com/73499766c338e7aec7fdac701a1f2732.png)

### 削除する時
RawImageを削除して、`SlideshowController`を選択してUdon BehaviourのImgs-Sizeを削除後の枚数にしてください。

!!! summary
    追加削除はこれで終了です。UnityのPlayボタンを押して確認してください。