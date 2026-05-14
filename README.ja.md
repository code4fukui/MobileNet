# MobileNet

MobileNetはTensorFlow.jsベースの画像分類ウェブアプリケーションです。

## デモ
ライブデモは https://code4fukui.github.io/MobileNet/ でお試しいただけます。

## 特徴
- MobileNetモデルを使用したリアルタイム画像分類
- 多種多様な物体や動物などを分類
- 信頼度スコアとともに上位の分類結果を表示
- デバイスのカメラを使用してビデオストリームを取得

## 要件
- HTML5の`<video>`要素および使用されているJavaScript APIをサポートするモダンウェブブラウザ（例: Chrome、Firefox、Safari）

## 使い方
1. ウェブブラウザで[デモページ](https://code4fukui.github.io/MobileNet/)を開きます。
2. カメラへのアクセスを求められたら、許可します。
3. アプリケーションがカメラに映った物体の分類を開始し、結果を表示します。

## データ / API
画像分類は、TensorFlow.jsライブラリから読み込まれた事前学習済みのMobileNetモデルによって実行されます。

## ライセンス
MIT License — 詳細は [LICENSE](LICENSE) を参照してください。
