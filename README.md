# DaysQuakeGraph

地震回数を日ごとに積み上げ棒グラフで表示するWindowsアプリです。  
- 日ごとの震度別回数をグラフ表示
- 任意の震源名や期間でフィルタリング
- JSON形式の設定ファイル対応

## 動作環境
- Windows 10以降
- .NET 4.8

## 使い方
1. `config.json` で震源フィルターや期間を設定
2. アプリを起動
3. 自動で地震データを取得し、グラフ表示します。

## ライセンス
[MIT](./LICENSE)

## 謝辞
- 震度配色 JQuake(フランソワ 様)
- LiveCharts2 (https://github.com/beto-rodriguez/LiveCharts2)
- SkiaSharp (https://github.com/mono/SkiaSharp)
- quake.one API (https://quake.one/)
