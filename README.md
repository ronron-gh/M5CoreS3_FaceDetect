# M5CoreS3_FaceDetect
M5Stack CoreS3の内蔵カメラで顔検出するテストプログラム。  
フレームワークのexampleにあるCameraWebServerの顔検出部分のコードを切り出して使っています。

フレームワークのexampleはここに保存されています（Windows10の場合）。  
C:\Users\\(ユーザ名)\\.platformio\packages\framework-arduinoespressif32\libraries\ESP32\examples


## 開発環境
VSCode + PlatformIO

## ライブラリ
* M5Unified
* esp32-camera

## メモリ使用量
顔検出を追加することによるメモリ使用量の増分は次の通り。

- ビルド結果  
  - RAM：10kB増（グローバル変数などのstatic領域）
  - Flash：680kB増（プログラム、定数）
- 実行時ヒープ使用量
  - RAM：17kB増
  - PSRAM：増減なし
