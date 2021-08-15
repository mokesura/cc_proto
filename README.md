# CC Proto
![CC Proto](https://github.com/mokesura/cc_proto/blob/main/img/cc_proto.jpg?raw=true)

CC Protoは、リバーシブル設計の18キーのキーボードです。

## 特徴
CC Protoは、以下の特徴を持っています。

- リバーシブル設計
- マイコンにPro Microを使用。コンスル―による抜き差しに対応。
- Cherry MX互換/Kailh Choc V1/Kailh Mid-Height/ALPS系スイッチ対応
  - Cherry MX互換/Kailh Mid-HeightスイッチはKailhソケットとはんだ付けの両方に対応。その他スイッチははんだ付けのみに対応。
  - Rev.3よりKailh Choc V2に対応。ただし、Rev.3ではスイッチの固定用足を切断する必要あり。Rev.4以降はスイッチの加工なしで取り付けができます。
  - 動作確認はCherry MX互換/Kailh Mid-Heightスイッチのみ。
- QMK Firmware対応
- [Remap](https://remap-keys.app)でのキーマップ変更に対応（VIAは動作未確認）
- LED（SK6812MINI）によるレイヤーの色分け表示（使用中ほとんど見えません）

## 組み立て済みキーボードを手にした方向けの利用ガイド
千葉千夏から組み立て済みのキーボードを受け取った方は、以下のページをご覧ください。

- [「CC Proto」組み立て済みキーボードを手にした方向けの利用ガイド](https://github.com/mokesura/cc_proto/blob/main/doc/0_guide_for_prepared_keyboard.md)

## ファームウェア
編集中につき、内容がコロコロ変わります。デフォルトファームウェアはRemap/VIA対応です。

- [Hex File](https://github.com/mokesura/cc_proto/tree/main/firmware)
- [QMK Firmware Sources](https://github.com/mokesura/qmk_firmware/tree/mokesura/cc_proto/keyboards/mokesura/cc_proto)

## キーボードの入手方法
自分用（というか、知り合いに使ってみてもらう用）に作成したキーボードですが、余った基板を頒布するかもしれません。  
ビルドガイドの作成予定は、今のところありません。

- [PCB Data](https://github.com/mokesura/cc_proto/tree/main/pcb) KiCadで作成した基板データ、ガーバーデータを公開しています。

## 回路図
- [回路図/Schematic](https://github.com/mokesura/cc_proto/blob/main/pcb/cc_proto-Schematic.pdf)

## 組み立てに必要な部品リスト

### 基板

- PCB×1
- ボトムプレート×1（データ未作成。PCBで代用可）
- トッププレート×1（データ公開予定。必要に応じて使用、Kailh Mid-Height/ALPS系スイッチには非対応）

### 基板以外の部品

- Pro Micro×1
- 12pin コンスルー×2（必要に応じて）
- ダイオード（1N4148または1N4148W）×18
- SK6812MINI×1（オプション）
- Kailh MX スイッチソケット×18（必要に応じて。Cherry MX互換/Kailh Mid-Heightスイッチのみ対応）
- タクトスイッチ（3.5x6.0x4.3mmのもの） ×1（Pro Microが露出している構造のため、RSTとGNDをショートさせることで代用可能）
- キースイッチ×18（Cherry MX互換/Kailh Choc V1/Kailh Choc V2/Kailh Mid-Height/ALPS系に対応。一応、混ぜても使用できますが、トッププレート使用時には工夫が必要です）
- キーキャップ×18（キースイッチに対応したもの）
- M2スペーサー、M2ネジ
  - 基板にはネジ穴が5つ開いてますが、中央を除いた4つをネジ止めすれば問題ないと思います。
  - スペーサーの長さは使用するスイッチによって異なります。Cherry MX互換スイッチ使用の場合、M2スペーサー3.5mm×8、M2ネジ8mm×4、M2ネジ3mm×4で組み立てしています。

## ライセンス
[MIT License](https://github.com/mokesura/cc_proto/blob/main/LICENSE)

## 使用したKiCadフットプリント
- [cc_proto.pretty](https://github.com/mokesura/cc_proto/tree/main/pcb/cc_proto.pretty) MIT Licenseのものを改変して利用。
- [KBD - for building keyboard libraries](https://github.com/foostan/kbd) 改変元。

## 連絡先
- Chinatsu Chiba (azulee/mokesura)
  - Twitter: [@azulee](https://twitter.com/azulee)
  - E-Mail: mokesura@gmail.com
