# Compare Solvers Random Knapsacks

- Zennの記事
    - [Package] JuMP+CbcとJuMP+SICPの比較: Pisingerのナップサック問題インスタンスを使って
    - https://zenn.dev/takilog/articles/7fd1e85b054a8d
- 実装は notebook/search-and-evaluate-SCIP.ipynb を見て下さい
- 実験するには hard instances を解凍した上で、 notebook/download_instance あたりに入れる必要があります（別でも良い）


# 結果（SCIP; gap 0.01）

| ファイル名 | 平均の比 | 平均の計算時間 |
| -- | -- | -- |
| knapPI_11_10000_1000.csv | 0.9998233048105855 | 0.9160730242729187 |
| knapPI_12_10000_1000.csv | 0.9998998854346434 | 0.9064184308052063 |
| knapPI_12_5000_1000.csv  | 0.9998473151115029 | 0.5555031299591064 |
| knapPI_13_10000_1000.csv | 0.9997428012813293 | 0.8743130874633789 |
| knapPI_13_5000_1000.csv  | 0.9997680048804578 | 0.5152662595113119 |
| knapPI_15_10000_1000.csv | 0.9996628777251206 | 0.7030484318733216 |
| knapPI_15_5000_1000.csv  | 0.9996096930304744 | 0.4814458063670567 |
