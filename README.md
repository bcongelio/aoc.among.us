# **AOC Among Us Tweets**

As noted, the .csv file is too large to view within GitHub. It is advisable that you view the data within RStudio. 

You can do so by doing the following ... 

To load this into RStudio:
```
urlfile = "https://raw.githubusercontent.com/bcongelio/aoc.among.us/main/aoc-among-us.csv"

aoc-among-us.df <- read_csv(url(urlfile))
```
As well, setting your scientific notation in RStudio cleans some of the columns up:

```
options(scipen = 9999)
```
