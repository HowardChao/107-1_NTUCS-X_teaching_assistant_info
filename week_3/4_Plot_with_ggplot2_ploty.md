# 使用 `ggplot2` 以及 `plotly` 畫圖

## ggplot2

1. 關於ggplot2的基本資訊：
    * [ggplot2官網](http://ggplot2.tidyverse.org/index.html)
    * [ggplot2 function manual](https://cran.r-project.org/web/packages/ggplot2/ggplot2.pdf)
    * [ggplot2 cheat sheet](https://www.rstudio.com/wp-content/uploads/2015/03/ggplot2-cheatsheet.pdf)

2. 學習ggplot2的資源：
    * [R Graphics Cookbook: Practical Recipes for Visualizing Data線上電子書（推薦）](http://www.cookbook-r.com/Graphs/)
    * [ggplot2官方網站 tutorial with examples（推薦](https://plot.ly/ggplot2/getting-started/)
    * [R for Data Science's tutorial](http://r4ds.had.co.nz/data-visualisation.html)

    * 其他參考：

        * [用資料說話，R語言有哪七種視覺化應用？](https://www.tipelse.com/article/686868.html)

        * 以內建Housing prices Data進行視覺化範例[Introduction to R graphics with ggplot2 - R Tutorials](http://tutorials.iq.harvard.edu/R/Rgraphics/Rgraphics.html)


## plotly

* 關於[plotly](https://plot.ly/ggplot2/)...
    * Plotly for R is an interactive, browser-based charting library built on the open source JavaScript graphing library plotly.js.

    * It works entirely locally in your web-browser via the HTML widgets framework.

    * 讓你的靜態圖片動動動起來。

    * 學習參考：
        * 最好的參考，就是從[Plotly ggplot2 Library](https://plot.ly/ggplot2/#basic-charts)直接觀察呢！！（學會ggplot2，就會plotly for ggplot）

---

## 另外關於什麼是[tidyverse](https://www.tidyverse.org/)...?（Optional）

或許在查找資料時，你發現有些code或文章內使用了...library(tidyverse)<-- 這是什麼？

> * The tidyverse is an opinionated collection of R packages designed for data science.
> * All packages share an underlying design philosophy, grammar, and data structures.

* 參考[R for Data Science](http://r4ds.had.co.nz/data-visualisation.html)的內容
    * tidyverse包含了幾個資料處理與視覺化的packages，幫助使用者省下一些引用麻煩。（簡單來說就是一個懶人包套件）

```
library(tidyverse)
#> Loading tidyverse: ggplot2
#> Loading tidyverse: tibble
#> Loading tidyverse: tidyr
#> Loading tidyverse: readr
#> Loading tidyverse: purrr
#> Loading tidyverse: dplyr
#> Conflicts with tidy packages ----------------------------------------------
#> filter(): dplyr, stats
#> lag():    dplyr, stats
```