# rolled-out-custom-stages

[Rolled Out!](https://rolledoutgame.com/) のカスタムステージ。

## ステージの編集

まず Blender に [BlendToRolledOut](https://gitlab.com/RolledOut/blendtorolledout) プラグインを入れる。

Blender で `*.blend` ファイルを開き、[ドキュメント](https://docs.rolledoutgame.com/) 等を参考にしながらステージを編集する。

編集し終わったら Blender のサイドバー（N を押すと出てくるやつ）の BlendToRolledOut タブから
`Generate config at ///config.json` と `Generate OBJ at ///model.obj` を押すと、
ファイルと同じ名前のディレクトリ内にステージデータが生成される。

### メモ

- スタート地点やゴールの設定されていないステージを作ろうとすると、保存に失敗したり遊べなかったりするっぽい。
- メッシュにマテリアルがついていないと、保存に失敗したり遊べなかったりするっぽい。

## ステージで遊ぶ

まず Rolled Out! のステージデータが入っているディレクトリを探す。

例: `...\steamapps\common\rolledout\RolledOut\Content\Stages\`

そのディレクトリ内に適当な名前のディレクトリ（例: `custom\`）を作成し、
その中にこのリポジトリにあるディレクトリを放り込むと、プラクティスモードで遊べるようになる。

アーケードモードで遊ぶ方法は調査中。
