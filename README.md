# TowerPlugin-for-TE3
Plug-in that stacks images starting from the trigger

## 画像が積みあがるやつ for TanuEsa3

### 導入方法

- HTMLフォルダをTanuEsa3のHTMLに上書き
- 上書きしたフォルダの `Tower Plugin.html` をOBSのソースにドラッグ&ドロップ
- たぬえさを設定する

### たぬえさ設定

- ちゃねぽ報酬 (Reward Twitchイベント設定画面)で該当するアクションを選ぶ
- オペレーション一覧でメディアファイルを選択
- メディアタイプをHTMLに設定
- HTMLファイルの場所に 'Tower Plugin.html' を指定

``` text
e.g. TanuEsa3.1.1.1\HTML\Tower Plugin.html
```

- HTML引数に `command=add&count=1` を設定

保存してプレビューを押すと画像が積みあがるかもね

### かすたまいず

- `たぬえさフォルダ/HTML/image` の中にある
- `drop-object.png` を任意のファイルに置き換える

```
widthは100pxに固定されるからサイズ変えたかったから適当にHTMLを修正してちょんまげ
```

### 過去のりりーすのーと
- v0.1 - Fixed failed load image (modified image file path)
- v0.11 - Add feature drop / dropped image switch (with change to gif file)