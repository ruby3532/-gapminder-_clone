# 練習專案一：兩百個國家、兩百年、四分鐘

## 簡介

這個專案「兩百個國家、兩百年、四分鐘」復刻了名聞遐邇的 [Hans Rosling's 200 Countries, 200 Years, 4 Minutes](https://www.youtube.com/watch?v=jbkSRLYSojo) 資料視覺化，我們使用了 ˋpandasˋ 與 ˋsqlite3ˋ 建立了資料庫，利用 ˋmatplotlibˋ 進行概念驗證，最後以 ˋplotly.expressˋ 做出成品。

## 如何重現

- 安裝 [Miniconda](https://docs.anaconda.com/miniconda/)
- 依據 ˋenvironment.ymlˋ 建立環境：ˋconda env create -f environment.ymlˋ

ˋˋˋshell
conda env create -f environment.yml
ˋˋˋ

- 將 ˋdata/ˋ 資料夾中的四個 CSV 檔案置放於工作目錄中的 ˋdata/ˋ 資料夾。
- 啟動環境並執行 ˋpython create_gapminder_db.pyˋ 就能在 ˋdata/ˋ 資料夾中建立 ˋgapminder.dbˋ
- 啟動環境並執行 ˋpython plot_with_px.pyˋ 就能生成 ˋgapminder_clone.htmlˋ