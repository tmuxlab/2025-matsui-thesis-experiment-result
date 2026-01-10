# 2025年度 松井 修士論文 - 実験結果

本リポジトリは、2025年度修士論文の付録資料（回帰結果）です。

##  PDFドキュメント

| ドキュメント | 説明 |
|-------------|------|
| [regression_result_SWWSP.pdf](regression_result_SWWSP.pdf) | SWWSPの回帰結果 |
| [regression_result_MWP.pdf](regression_result_MWP.pdf) | MWWPの回帰結果 |

##  回帰結果

### 図の凡例
- **黒線**: 元データ
- **黒点**: 訓練/検証データの境界
- **赤線**: 周期回帰の結果/予測
- **青線**: ARIMAのフィッティング結果/予測
- **緑線**: RNNのフィッティング結果/予測

### Approach A - SWWSP
データセット（DS1〜DS6）ごとに、異なる訓練データ割合（30%、50%、70%）で結果を整理しています。

### Approach B - MWWP
データセットと訓練データ割合ごとに、複数の解像度レベルで結果を整理しています。