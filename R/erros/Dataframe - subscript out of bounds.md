
## Error message

`**Error in col[[i, exact = exact]] : subscript out of bounds**`

## Code causing it

`t =data.frame(name = NA,p.net = NA, fc.net = NA)`

`t[[2,2]]`

## Solution

Subscript out of bounds is **an error that occurs when trying to access an element at an index that is outside the range of the vector or matrix in R**.
-> The code has 3 columns and 1 row with "NAs" (see image:)

![[Pasted image 20240405224025.png]]

You cannot access a second row that doesn´t exist.
Check the dataframe/matrix/vector and make sure that you access the right index -> index should exist!