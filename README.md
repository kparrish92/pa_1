
``` r
dur_hablo_stressed<-.405
dur_hablo_unstressed<-.219
dur_o_stressed<-.153
dur_o_unstressed<-.15
int_o_stressed<- 42.27070634852784
int_o_unstressed<- 37.5406276034746
f0_o_stressed<-110.34620729227878
f0_o_unstressed<- 106.77174064609862
```

The difference in ms between “hablo” and “habló”

``` r
dur_hablo_stressed - dur_hablo_unstressed
```

    ## [1] 0.186

The difference in ms between the stressed and unstressed \[o\]

``` r
dur_o_stressed-dur_o_unstressed
```

    ## [1] 0.003

The difference in intensity between the stressed and unstressed \[o\]

``` r
int_o_stressed-int_o_unstressed
```

    ## [1] 4.730079

The difference in F0 between the stressed and unstressed \[o\]

``` r
f0_o_stressed-f0_o_unstressed
```

    ## [1] 3.574467

I decided to leave to descriptions of the calculations above the code in
order to organize them. This is pretty cool, but I bet it gets very
complicated quickly.
