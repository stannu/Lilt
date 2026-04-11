# Lilt4R

**ホームポジションをさらに快適に。**

Lilt4Rは、メインキーボードの手前に配置することを想定した、XIAO RP2040搭載のミニマルなマクロパッドです。親指や左手をホームポジションからわずかに手前にスライドさせるだけで、頻繁に使うショートカットやレイヤー操作にアクセスできます。

## Features
* **Ergonomic Design:** 腕を大きく動かす必要がなく、タイピングのフローを止めることなく直感的に操作可能。
* **MCU:** Seeed Studio XIAO RP2040
* **Controls:** 4 x Mechanical Switches + 1 x Rotary Encoder (EC11)
* **Visuals:** 2 x SK6812MINI-E (Addressable RGB LED)
* **Firmware:** ZMK Firmware (Support ZMK Studio)

## Layer Design & Navigation
Lilt4Rは、4つのキーとコンボ入力を組み合わせることで、コンパクトながら多機能な操作を実現しています。

* **Layer 0 (Base):** 通常のショートカットやメディアコントロール。
* **Layer 1 (Function):** Fキーやシステム操作。
* **Layer 2 (Settings):** LEDの輝度調整や、ZMK Studioによるリアルタイム設定。

### Special Shortcuts (Combo)
ホームポジションを崩さないための工夫として、特定の2キーを同時に押す「コンボ入力」を採用しています。
* **Key 1 + Key 2:** レイヤーを瞬時に切り替え。
* **Key 3 + Key 4:** Mac / Windows 用レイヤーのトグル切り替え。

これにより、ボタンを探す手間を省き、指のわずかな動きだけで複雑なワークフローを制御できます。

## Hardware Specification
* **Microcontroller:** Raspberry Pi RP2040 (XIAO)
* **Connectivity:** USB-C
* **RGB Underglow:** Driven by PIO-based SPI driver for stable performance.

## Design Inspiration
デザインはミニマルな美学にインスパイアされています。

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
