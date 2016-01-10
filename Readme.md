<!-- README.md is generated from README.Rmd. Please edit that file -->
Computational Reproducibility in Archaeological Research: Basic Principles and a Case Study of Their Implementation
===================================================================================================================

### Compendium URL

<https://dx.doi.org/10.6084/m9.figshare.1563661>

### Author

Ben Marwick (<benmarwick@gmail.com>)

### Contents

This repository contains the research compendium for my paper in the *Journal of Archaeological Method and Theory*:

> Marwick, B. (2016). Computational reproducibility in archaeological research: Basic principles and a case study of their implementation. *Journal of Archaeological Method and Theory*, 1-27. doi: 10.1007/s10816-015-9272-9

The paper is available as a free [PDF](https://github.com/benmarwick/basic_computational_reproducibility_case_study/raw/master/published/Marwick_2016_basic_computational_reproducibility.pdf), an [Open Access author-accepted manuscript], or on the subscription-only site for the [Journal of Archaeological Method and Theory](http://link.springer.com/article/10.1007/s10816-015-9272-9)

Here's a bibtex-style citation for easy copy-pasting:

    @article{
    year={2016},
    issn={1072-5369},
    journal={Journal of Archaeological Method and Theory},
    doi={10.1007/s10816-015-9272-9},
    title={Computational Reproducibility in Archaeological Research: Basic Principles and a Case Study of Their Implementation},
    url={http://dx.doi.org/10.1007/s10816-015-9272-9},
    publisher={Springer US},
    keywords={Reproducible research; Computer programming; Software engineering; Australian archaeology; Open science},
    author={Marwick, Ben},
    pages={1-27},
    language={English}
    }

### How to use

See the [`text`](https://github.com/benmarwick/basic_computational_reproducibility_case_study/tree/master/text) directory on GitHub for the [source code](https://github.com/benmarwick/basic_computational_reproducibility_case_study/blob/master/text/basic_computational_reproducibility.Rmd) that generated the manuscript. The Rmd file is the original source document, and the docx file was required by the publisher for submission.

See the published PDF ([view in browser](https://github.com/benmarwick/basic_computational_reproducibility_case_study/blob/master/published/Marwick_2016_basic_computational_reproducibility.pdf) or [download](https://github.com/benmarwick/basic_computational_reproducibility_case_study/raw/master/published/Marwick_2016_basic_computational_reproducibility.pdf))(<https://github.com/benmarwick/basic_computational_reproducibility_case_study/tree/master/published>) here in this repository.

### Dependencies

I used [RStudio](http://rstudio.com/) v0.99.825 with [Pandoc](http://pandoc.org/) 1.13.2. To generate a docx from the Rmd, see the `R Session Information` below for the R version and packages that I used. To generate a PDF, I used LaTeX ([MiKTeX](http://miktex.org/) 2.9).

### Licenses:

Text: CC-BY-4.0 <http://creativecommons.org/licenses/by/4.0/>

Code: MIT <http://opensource.org/licenses/MIT> year: 2015, copyright holder: Ben Marwick

Data: CC0 <http://creativecommons.org/publicdomain/zero/1.0/>

### Notes and resources

-   The [issues tracker](https://github.com/benmarwick/basic_computational_reproducibility_case_study/issues) is the place to report problems or ask questions

-   See the repository [history](https://github.com/benmarwick/basic_computational_reproducibility_case_study/commits/master) for a fine-grained view of progress and changes.

-   The organisation of this compendium is based on the work of [Carl Boettiger](http://www.carlboettiger.info/)

### R Session Information

``` r
sessionInfo()
#> R version 3.2.3 (2015-12-10)
#> Platform: x86_64-w64-mingw32/x64 (64-bit)
#> Running under: Windows 7 x64 (build 7601) Service Pack 1
#> 
#> locale:
#> [1] LC_COLLATE=English_United States.1252 
#> [2] LC_CTYPE=English_United States.1252   
#> [3] LC_MONETARY=English_United States.1252
#> [4] LC_NUMERIC=C                          
#> [5] LC_TIME=English_United States.1252    
#> 
#> attached base packages:
#> [1] stats     graphics  grDevices utils     datasets  methods   base     
#> 
#> loaded via a namespace (and not attached):
#>  [1] magrittr_1.5    formatR_1.2.1   tools_3.2.3     htmltools_0.3  
#>  [5] yaml_2.1.13     stringi_1.0-1   rmarkdown_0.9.3 knitr_1.12     
#>  [9] stringr_1.0.0   digest_0.6.9    evaluate_0.8
```
