In the 7 segment displayplot I plotted the segment in color display,
but there is a problem in the github side to open the file.

So writing it here for better explanation!

```python
        
    print(' ',a,"\n",f,g,b,"\n",e,d,c)
```
      
And on calling it as:

```python 
print(display_7_segment(1,1,1,1,1,1,1)) 
```
 we get the output
```python
  _ 
| _ | 
| _ |
           
```


Now what I did , to get the coloured plot is to change the initials of print as 




```python
        
    print('\033[1;31;48m',' ',a,"\n",f,g,b,"\n",e,d,c,'\033[0m')
    
```
      
<img align=center src="https://github.com/Chaks1603/Python-Assignments/blob/main/Logic_Tables/img/bcd.png">
