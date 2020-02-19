index
========================================================
author: Rafaela Becerra
date: February 19, 2020
autosize: true
font-import: https://fonts.googleapis.com/css?family=Pacifico&display=swap
font-family: 'Pacifico' 

<!--https://rafaelab1227.github.io/Rpresentation/#/-->

First Slide
========================================================
type: alert
incremental: true
For more details on authoring R presentations please visit <https://support.rstudio.com/hc/en-us/articles/200486468>.

<li class="fragment" fade-in" data-fragment-index="3"> Bullet 1</li>
<li class="fragment" fade-in" data-fragment-index="1">Bullet 2
<li class="fragment" fade-out" data-fragment-index="2">Bullet 3
<li class="fragment" fade-in" data-fragment-index="4">Bullet 4

Slide With Code
========================================================


```r
summary(cars)
```

```
     speed           dist       
 Min.   : 4.0   Min.   :  2.00  
 1st Qu.:12.0   1st Qu.: 26.00  
 Median :15.0   Median : 36.00  
 Mean   :15.4   Mean   : 42.98  
 3rd Qu.:19.0   3rd Qu.: 56.00  
 Max.   :25.0   Max.   :120.00  
```

Slide With Plot
========================================================

![plot of chunk unnamed-chunk-2](index-figure/unnamed-chunk-2-1.png)
Plotly graph
========================================================



<style>
  .p_iframe iframe {
    width:90%;
    height:576px;
}
</style>

<div class="p_iframe">
<iframe frameborder="0" seamless='seamless' scrolling=no src="plotly.html"></iframe>
</div>



