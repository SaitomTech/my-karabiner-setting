# my-karabiner-setting
for karabiner-elements settings

## メモ
- `~/.config/karabiner/assets/complex_modifications` に作成したJSONファイルを格納することで、アプリ側で認識可能に。
  - [Qiitaの参考記事](https://qiita.com/s-show/items/a1fd228b04801477729c)
- JISとUS配列の違いによる差を吸収するために以下を参考にした
  - [Karabiner Elementsの記号対応表 (JIS用、シフト同時押し含む)](https://qiita.com/funatsufumiya/items/2d0395c6622468a31b4f)

## 設定方法
1. コピペ用コマンド: `$ cp karabiner_setting.json  ~/.config/karabiner/assets/complex_modifications/`
2. アプリの"Preferences" > "Complex modifications" > "Add rule" > "Enable All" 
