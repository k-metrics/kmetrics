in-IDE tutorials in Japanese
================

　`kmetrics` パッケージは、[RStudio IDE
v1.3](https://blog.rstudio.com/2020/05/27/rstudio-1-3-release/) の
[チュートリアル機能（in-IDE
tutorial）](https://blog.rstudio.com/2020/02/25/rstudio-1-3-integrated-tutorials/)
用のチュートリアルファイルをインストールするためのパッケージです。チュートリアルファイルとヘルプ以外は含まれていません。

　

## Requirement

　`kmetrics` パッケージを利用するには以下の環境が必要です。

| Env.     | Requirement                                | Memo              |
| -------- | ------------------------------------------ | ----------------- |
| R        | 3.6.0 or later                             | 4.0.x 推奨          |
| RStudio  | 1.3 or later                               | Desktop or Server |
| Packages | learnr, shiny, tidyverse, knitr, rmarkdown | 事前インストールをおすゝめします  |

　

## Install

　パッケージは [GitHub repository](https://github.com/k-metrics/kmetrics)
からインストールしてください。

``` r
install.packages("devtools")
devtools::install_github("k-metrics/kmetrics")
```

　インストールが終わりましたら R
のセッションをリスタートさせてください。チュートリアルタブにチュートリアルファイルが表示されます。チュートリアルファイルが表示されない場合は、RStudio
を再起動してみてください。

　

## Usage

　RStudio IDE (Desktop or Server) の “Tutorial” タブに表示されているチュートリアルを選び［Start
Tutorial］ボタンをクリックするとレンダリング処理後にチュートリアルが表示されます。対話形式のチュートリアルになっていますので、設問などに解答する形式で学習をすゝめられます。  
　チュートリアルを終了する場合は “Tutorial” タブのツールバーに表示されている赤色の［Stop
tutorial］ボダンをクリックしてください。

　

## Tutorials

　`kmetrics`
パッケージが提供するチュートリアルファイルについてはヘルプでご確認ください。なお、チュートリアルの内容は予告なく変更します。

　

## License

| Targets        | License                       | Memo                    |
| -------------- | ----------------------------- | ----------------------- |
| package source | MIT License                   | チュートリアルファイルを除く全ての公開ファイル |
| tutorial files | CC 4.0 BY-NC-SA, Sampo Suzuki |                         |

　

-----
