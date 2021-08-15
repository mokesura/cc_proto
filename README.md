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
編集中につき、内容がコロコロ変わります。

- [Hex File](https://github.com/mokesura/cc_proto/tree/main/firmware)
- [QMK Firmware Sources](https://github.com/mokesura/qmk_firmware/tree/mokesura/cc_proto/keyboards/mokesura/cc_proto)

## キーボードの入手方法
自分用（というか、知り合いに使ってみてもらう用）に作成したキーボードですが、余った基板を頒布するかもしれません。  
ビルドガイドの作成予定は、今のところありません。

- [PCB Data](https://github.com/mokesura/cc_proto/tree/main/pcb) KiCadで作成した基板データ、ガーバーデータを公開しています。

## 回路図
- [回路図/Schematic](https://github.com/mokesura/cc_proto/blob/main/pcb/cc_proto-Schematic.pdf)

## 部品リスト
公開予定。

## ライセンス
[MIT License](https://github.com/mokesura/cc_proto/blob/main/LICENSE)

## 使用したKiCadフットプリント
- [cc_proto.pretty](https://github.com/mokesura/cc_proto/tree/main/pcb/cc_proto.pretty) MIT Licenseのものを改変して利用。
- [KBD - for building keyboard libraries](https://github.com/foostan/kbd) 改変元。

## 連絡先
- Chinatsu Chiba (azulee/mokesura)
  - Twitter: [@azulee](https://twitter.com/azulee)
  - E-Mail: mokesura@gmail.com
