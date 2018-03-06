# helix_keymap

ref https://github.com/MakotoKurauchi/helix

## how to use

1. https://github.com/qmk/qmk_firmware/ を clone してくる
1. [この辺り](https://github.com/MakotoKurauchi/helix/blob/master/Doc/firmware_jp.md#%E3%83%93%E3%83%AB%E3%83%89%E7%92%B0%E5%A2%83%E3%82%92%E4%BD%9C%E3%82%8B) を参考にビルド環境を構築する
1. この設定を qmk_firmware にコピーする
  - `cp -rp layoutA <repo path>/qmk/qmk_firmware/keyboards/helix/rev2/keymaps/`
1. [この辺り](https://github.com/MakotoKurauchi/helix/blob/master/Doc/firmware_jp.md#%E3%83%93%E3%83%AB%E3%83%89%E3%81%A8%E6%9B%B8%E3%81%8D%E8%BE%BC%E3%81%BF) を参考にビルド&書き込みを行う
  - `make helix:layout_A:avrdude`
