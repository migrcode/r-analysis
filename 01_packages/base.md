# 1. General 

### Switch is a more compact version of if-else

```R
x_option <- function(x) {
  switch(x,
    a = "option 1",
    b = "option 2",
    c = "option 3",
    stop("Invalid `x` value")
  )
}

x_option("a")
```
by https://adv-r.hadley.nz/control-flow.html

