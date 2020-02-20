Data Science: Everyday Music Listening
================

## GitHub Documents

# I am a big heading

## I am a smaller heading

## I am an even smaller heading

Normal *italic* **bold** text.

  - List
  - Another
    list

<!-- end list -->

    ## ── Attaching packages ────────────────────────────────────────────────────────── tidyverse 1.3.0 ──

    ## ✓ ggplot2 3.2.1     ✓ purrr   0.3.3
    ## ✓ tibble  2.1.3     ✓ dplyr   0.8.4
    ## ✓ tidyr   1.0.2     ✓ stringr 1.4.0
    ## ✓ readr   1.3.1     ✓ forcats 0.4.0

    ## ── Conflicts ───────────────────────────────────────────────────────────── tidyverse_conflicts() ──
    ## x dplyr::filter() masks stats::filter()
    ## x dplyr::lag()    masks stats::lag()

    ## # A tibble: 50 x 61
    ##    playlist_id playlist_name playlist_img playlist_owner_… playlist_owner_…
    ##    <chr>       <chr>         <chr>        <chr>            <chr>           
    ##  1 37i9dQZF1D… Today's Top … https://i.s… Spotify          spotify         
    ##  2 37i9dQZF1D… Today's Top … https://i.s… Spotify          spotify         
    ##  3 37i9dQZF1D… Today's Top … https://i.s… Spotify          spotify         
    ##  4 37i9dQZF1D… Today's Top … https://i.s… Spotify          spotify         
    ##  5 37i9dQZF1D… Today's Top … https://i.s… Spotify          spotify         
    ##  6 37i9dQZF1D… Today's Top … https://i.s… Spotify          spotify         
    ##  7 37i9dQZF1D… Today's Top … https://i.s… Spotify          spotify         
    ##  8 37i9dQZF1D… Today's Top … https://i.s… Spotify          spotify         
    ##  9 37i9dQZF1D… Today's Top … https://i.s… Spotify          spotify         
    ## 10 37i9dQZF1D… Today's Top … https://i.s… Spotify          spotify         
    ## # … with 40 more rows, and 56 more variables: danceability <dbl>, energy <dbl>,
    ## #   key <int>, loudness <dbl>, mode <int>, speechiness <dbl>,
    ## #   acousticness <dbl>, instrumentalness <dbl>, liveness <dbl>, valence <dbl>,
    ## #   tempo <dbl>, track.id <chr>, analysis_url <chr>, time_signature <int>,
    ## #   added_at <chr>, is_local <lgl>, primary_color <chr>, added_by.href <chr>,
    ## #   added_by.id <chr>, added_by.type <chr>, added_by.uri <chr>,
    ## #   added_by.external_urls.spotify <chr>, track.artists <list>,
    ## #   track.available_markets <list>, track.disc_number <int>,
    ## #   track.duration_ms <int>, track.episode <lgl>, track.explicit <lgl>,
    ## #   track.href <chr>, track.is_local <lgl>, track.name <chr>,
    ## #   track.popularity <int>, track.preview_url <chr>, track.track <lgl>,
    ## #   track.track_number <int>, track.type <chr>, track.uri <chr>,
    ## #   track.album.album_type <chr>, track.album.artists <list>,
    ## #   track.album.available_markets <list>, track.album.href <chr>,
    ## #   track.album.id <chr>, track.album.images <list>, track.album.name <chr>,
    ## #   track.album.release_date <chr>, track.album.release_date_precision <chr>,
    ## #   track.album.total_tracks <int>, track.album.type <chr>,
    ## #   track.album.uri <chr>, track.album.external_urls.spotify <chr>,
    ## #   track.external_ids.isrc <chr>, track.external_urls.spotify <chr>,
    ## #   video_thumbnail.url <lgl>, key_name <chr>, mode_name <chr>, key_mode <chr>

This is an R Markdown format used for publishing markdown documents to
GitHub. When you click the **Knit** button all R code chunks are run and
a markdown file (.md) suitable for publishing to GitHub is generated.

## Including Code

You can include R code in the document as follows:

    ##      speed           dist       
    ##  Min.   : 4.0   Min.   :  2.00  
    ##  1st Qu.:12.0   1st Qu.: 26.00  
    ##  Median :15.0   Median : 36.00  
    ##  Mean   :15.4   Mean   : 42.98  
    ##  3rd Qu.:19.0   3rd Qu.: 56.00  
    ##  Max.   :25.0   Max.   :120.00

## Including Plots

You can also embed plots, for example:

![](README_files/figure-gfm/pressure-1.png)<!-- -->

Note that the `echo = FALSE` parameter was added to the code chunk to
prevent printing of the R code that generated the plot.
