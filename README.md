#### lasassesstt
#####Working with sassscript
######Looping 
```
$red:red;
$blue:blue;
$color:$red,$blue;
@for $i from 1 through length($color){
  h#{$i}{
    color: nth($color,$i);      //note position of param, 1st is array 2nd is idx(1 based)
  }
}
```
