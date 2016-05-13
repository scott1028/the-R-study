#### The R Study Note

```
# define & declare variable
x = 10
x <- 10
10 -> 10

# show all variables for current workspace
ls()

# delete a variable, ex: a <- 100; rm("a");
rm("a")

# delete a variables in current workspace
rm(list = ls())

# program block, return final line result
{
	x <- 10
	x + 100
}
P.S it will return 110.
```
