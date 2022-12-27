# klipper-config-ender3

* Ender-3系プリンター + fly-gemini v1の構成のklipper設定ファイル
* fluidd

## printer.cfg

* 基本設定ファイル
* 頻繁にいじる場合がある設定項目やgcodeマクロは別ファイルにしてinclude

## bltouch.cfg

* 何かトラブルときはだいたいこれだったのでいじりやすいように分けた

## homing.cfg

* センサーレスホーミングのためにオーバライドしてて邪魔だから分けた

## macro-util.cfg

* 便利マクロ

## input-shaper.cfg

* 分けることで使わないときはincludeをコメントアウトするだけでよくなった
