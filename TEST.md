# Create a formula to correctly evaluate blank cells in Excel

## Summary



## More information



```excel
=IF(B1=0,"zero","blank")
```


```excel
=IF(ISBLANK(B2),"blank",IF(B2=0,"zero","other"))
```

> [!NOTE]
> The above formula returns "zero" if there is a zero value in the cell, "blank" if the cell is blank, and "other" if anything else is in the cell.
