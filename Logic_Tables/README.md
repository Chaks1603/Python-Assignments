In the 7 segment displayplot I plotted the segment in color display,
but there is a problem in the github side to open the file.
So writing it here for better explanation!

```python
def display_7_segment(a,b,c,d,e,f,g):
    if a==1:
        a = "1"
        a = a.replace("1", "_" )
    elif a==0:
        a = "0"
        a = a.replace("0", " ")
    if b==1:
        b = "1"
        b = b.replace("1", "|" )
    elif b==0:
        b = "0"
        b = b.replace("0", " ")
    if c==1:
        c = "1"
        c = c.replace("1", "|" )
    elif c==0:
        c = "0"
        c = c.replace("0", " ")
    if d==1:
        d = "1"
        d = d.replace("1", "_" )
    elif d==0:
        d = "0"
        d = d.replace("0", " ")
    if e==1:
        e = "1"
        e = e.replace("1", "|" )
    elif e==0:
        e = "0"
        e = e.replace("0", " ")
    if f==1:
        f = "1"
        f = f.replace("1", "|" )
    elif f==0:
        f = "0"
        f = f.replace("0", " ")
    if g==1:
        g = "1"
        g = g.replace("1", "_" )
    elif g==0:
        g = "0"
        g = g.replace("0", " ")
        
    print(' ',a,"\n",f,g,b,"\n",e,d,c)
    return ' '
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
      
