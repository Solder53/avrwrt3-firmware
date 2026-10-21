# avrwrt3-firmware

共立電子産業のAVRライター基板（ATtiny2313）用の互換ファームウェアです。
AVRWRT.exe Ver.1.6.0.2 の通信を調べて、一から作成しました。

## 書き込み方

- 対象: ATtiny2313（基板上のマイコン）
- ファイル: AVRWRT3.hex
- ヒューズ: L=0xFF H=0xDF E=0xFF（外付け8MHzセラロック）

## 動作確認

- 本物の基板 ＋ AVRWRT.exe Ver.1.6.0.2 ＋ Arduino Nano（ATmega328P）
- 検出・ヒューズ・FLASH・EEPROM・消去・ロックビット・クロック出力・校正値
- 通常モード、V3モード（1/2/4/6MHz）

## 注意

- 共立電子産業およびデジットとは関係のない、個人による非公式のファームウェアです。
- AVRWRT.exe は含まれていません。
- 使用は自己責任でお願いします。
