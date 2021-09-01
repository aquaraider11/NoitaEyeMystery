# NoitaEyeMystery

Head over to
https://jsfiddle.net

add this code to JS field

set canvas size to be large enough, i recommend `width="1500" height="1500"`

You can change line 43 second parameter of `db()`to be whatever you want to be written next to each point, currently it is 
x : y where
x = how many "moves" since last point
y = how many total "points"


Currently this plots moves according to youtube comment 
```
Eye direction
Right means +1y
Up means +1x
Forward means create marker there.
```
in addition it keeps plotting from the location of last 'point' instead of resetting the location to start when encountering point, as this creates more interesting pattern.
