
## error

`cp: cannot create directory '/Desktop/coding/': No such file or directory´

## Code that caused it

`cp -r ~/.config/rstudio /Desktop/coding/´

## Solution

If you intend to copy the `rstudio` directory into a folder named `coding` on your desktop, you should use the correct path. Typically, the desktop directory is located in the user's home directory.
- the `~/Desktop` path.

`cp -r ~/.config/rstudio ~/Desktop/coding/´

