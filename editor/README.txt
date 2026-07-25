FF14 Cyberpunk Card Layout Editor

構成
- index.html
- assets/card-template-reference.png

GitHub Pagesでの配置例
repository/
├─ index.html                  キャラクターカード本体
├─ editor/
│  ├─ index.html               このレイアウトエディター
│  └─ assets/
│     └─ card-template-reference.png
└─ assets/                     本体用素材

使い方
1. editorフォルダをリポジトリへアップロードします。
2. GitHub Pagesの「/editor/」へアクセスします。
3. 元の台紙を参考表示しながら、各パネルを移動・拡縮します。
4. JSONで座標を保存、またはPNGとして新しい台紙案を書き出します。

注意
元の台紙画像の内部を直接分解・編集するものではありません。
元画像を薄く参考表示し、その上で新しいパネル配置を作成する方式です。
