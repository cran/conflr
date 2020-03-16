## Simple example

You can embed an R code chunk like this:

``` r
summary(cars)
#>      speed           dist       
#>  Min.   : 4.0   Min.   :  2.00  
#>  1st Qu.:12.0   1st Qu.: 26.00  
#>  Median :15.0   Median : 36.00  
#>  Mean   :15.4   Mean   : 42.98  
#>  3rd Qu.:19.0   3rd Qu.: 56.00  
#>  Max.   :25.0   Max.   :120.00
```

## Including Plots

You can also embed plots, for example:

``` r
plot(pressure)
```

![](example_files/figure-commonmark/pressure-1.png)<!-- -->

## Tables

``` r
knitr::kable(head(iris))
```

<table>
<thead>
<tr class="header">
<th style="text-align: right;">Sepal.Length</th>
<th style="text-align: right;">Sepal.Width</th>
<th style="text-align: right;">Petal.Length</th>
<th style="text-align: right;">Petal.Width</th>
<th style="text-align: left;">Species</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="text-align: right;">5.1</td>
<td style="text-align: right;">3.5</td>
<td style="text-align: right;">1.4</td>
<td style="text-align: right;">0.2</td>
<td style="text-align: left;">setosa</td>
</tr>
<tr class="even">
<td style="text-align: right;">4.9</td>
<td style="text-align: right;">3.0</td>
<td style="text-align: right;">1.4</td>
<td style="text-align: right;">0.2</td>
<td style="text-align: left;">setosa</td>
</tr>
<tr class="odd">
<td style="text-align: right;">4.7</td>
<td style="text-align: right;">3.2</td>
<td style="text-align: right;">1.3</td>
<td style="text-align: right;">0.2</td>
<td style="text-align: left;">setosa</td>
</tr>
<tr class="even">
<td style="text-align: right;">4.6</td>
<td style="text-align: right;">3.1</td>
<td style="text-align: right;">1.5</td>
<td style="text-align: right;">0.2</td>
<td style="text-align: left;">setosa</td>
</tr>
<tr class="odd">
<td style="text-align: right;">5.0</td>
<td style="text-align: right;">3.6</td>
<td style="text-align: right;">1.4</td>
<td style="text-align: right;">0.2</td>
<td style="text-align: left;">setosa</td>
</tr>
<tr class="even">
<td style="text-align: right;">5.4</td>
<td style="text-align: right;">3.9</td>
<td style="text-align: right;">1.7</td>
<td style="text-align: right;">0.4</td>
<td style="text-align: left;">setosa</td>
</tr>
</tbody>
</table>

## Math

$$ 2 + 2 = 5 $$
