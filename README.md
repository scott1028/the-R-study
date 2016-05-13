#### The R Study Note


* define & declare variable
```
x = 10
x <- 10
10 -> 10
```

* show all variables for current workspace
```
ls()
```

* delete a variable, ex: a <- 100; rm("a");
```
rm("a")
```

* delete a variables in current workspace
```
rm(list = ls())
```

* program block, return final line result
```
{
    x <- 10
    x + 100
}
P.S it will return 110.
```

* Show library you have installed in your PC.
```
library()
```

* Install a new package, then select a one package you want.
```
install.packages()
```

* update package
```
update.packages()
```

* remove library in your PC.( Don't do it )
```
detach("rgl")
```

* import library to current workspace
```
library("rgl")
```

* show library you have imported.
```
search()
```

* show function source code & execute
```
ls          # show source
ls()        # execute ls function
fix(ls)     # open source code in another window
edit(ls)    # open source code in another window
```

* 向量陣列宣告與型態查詢

![Alt text](https://raw.githubusercontent.com/scott1028/the-R-study/master/array_and_type.png "array_and_type.png")
- R 裏面所有的變數都是以向量 & Array 方式存在 a=1 就等於 a = [1]，存取 Array 變數名稱預設會回復第一個元素！

#### package & library

- A package is a standardized collection of material extending R, e.g. providing code, data, or documentation. A library is a place (directory) where R knows to find packages it can use (i.e., which were installed). R is told to use a package (to “load” it and add it to the search path) via calls to the function library. I.e., library() is employed to load a package from libraries containing packages.
