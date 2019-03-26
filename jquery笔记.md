---
1.jquery对象与DOM对象互转

``` 
var btnObj=document.getElementById("btn")
jquery对象
$("btnObj")
转DOM对象 $("btnObj")[0]
```
2.三种页面加载事件

``` javascript
>$("window").load(function( ){ });
>$("document").ready(function( ){ } );
>$(function( ){ } );
```

