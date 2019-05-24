Rstudio themes
================

  - [49th Parallel :coffee:](#th-parallel-coffee)

# 49th Parallel :coffee:

A dark Rstudio theme created as thanks to a particular Vancouver coffee
shop that fueled many productive mornings.

*Requires Rstudio version \>
1.2*

<img src="images/preview_49th_parallel.png" width="770" height="550" style="display: block; margin: auto;" />
<br>

**To install,**

**Step 1.** Make a coffee :coffee:

**Step 2.** Open R and run the following:

``` r
# create temporary download directory
theme_49th_parallel <- fs::path_temp("49th_parallel-RStudio", 
                                     ext = "rstheme")

# download theme from github
download.file("https://raw.githubusercontent.com/wvictor14/rstudio_themes/master/49th%20Parallel.rstheme", 
              theme_49th_parallel)

# apply the theme
rstudioapi::addTheme(theme_49th_parallel, 
                     apply = TRUE)
```

**Step 3.** Start coding while enjoying your coffee :yum: :computer:
