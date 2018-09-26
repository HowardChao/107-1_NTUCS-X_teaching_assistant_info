# 如何更快速的前處理資料？

## dplyr with dataframe

* dplyr is a powerful R-package to transform and summarize tabular data with rows and columns.

* 幫助在前處理數據時常用的功能(ex分組、排序、篩選等），變成簡單好用的函式。

1. 安裝與使用套件
```
install.packages("dplyr")

library(dplyr)
```

2. 官方文件
    * [dplyr overview](dplyr overview)
    * [Package ‘dplyr’ pdf(v0.7.4, 2017.09)](https://cran.r-project.org/web/packages/dplyr/dplyr.pdf)

3. 學習資源

    1. [dplyr tutorial](http://genomicsclass.github.io/book/pages/dplyr_tutorial.html)
    2. [DataScienceRBook探索式資料分析](https://yijutseng.github.io/DataScienceRBook/eda.html)
    3. [dplyr cheat sheet](https://www.rstudio.com/wp-content/uploads/2015/02/data-wrangling-cheatsheet.pdf)

---

## 關於apply家族

* 一個比自己用for迴圈對數據集進行循環更好的選擇。

    * 包括apply, lapply, sapply, vapply, mapply, tapply, rapply, eappply。

    * 相信我。不使用apply家族，你會後悔。

    * 而且很傻。

* 學習資源：
    * [Coursera上的apply family課程](https://www.coursera.org/learn/r-programming/lecture/t5iuo/loop-functions-lapply)
    * [R tutorial on the Apply family of functions](https://www.r-bloggers.com/r-tutorial-on-the-apply-family-of-functions/)
    * [掌握R語言中的apply函數](http://blog.fens.me/r-apply/)