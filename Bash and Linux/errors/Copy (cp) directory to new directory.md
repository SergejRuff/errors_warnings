
## Error message


`cp: -r not specified; omitting directory '/home/sergej/.config/rstudio'´




## The code that caused it


`cp ~/.config/rstudio /Desktop/coding/´



## Solution



The error message indicates that the user is trying to copy a directory (`~/.config/rstudio`) without specifying the `-r` flag, which is necessary to recursively copy directories. To resolve this issue, one needs to use the `-r` flag in the `cp` command.

`cp -r ~/.config/rstudio /Desktop/coding/´

