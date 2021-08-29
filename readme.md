# Photo Blog

My personal photo blog

## Hugo

Local Server with drafts:

`hugo server -D`

Build:

`hugo`

## Shortcodes

### img
Photos go in the /posts/post-name/ folder for processing. 

`{{< img src="images/2021/02/example.jpg" alt="Example" >}}`

Automatically scales, compresses, and lazy loads images.

### EXIF

`{{< exif src="images/2021/02/milk.jpg" >}}`

### Geotag

`{{< geo lat="46.21188" lon="-74.58684" place="Mont-Tremblant, Quebec" >}}`

Embeds an OpenStreetMap with optional place caption.

## Configuration

```
baseURL = "https://example.com/"
languageCode = "en-us"
title = "Site Title"
theme = "photoblog"

[params]
    author = "Anthony Di Iorio"
    title = "Anthony Di Iorio"
    description = "Photo blog"
    logo = "/logo.jpg"
    images = ["twitter.jpg"]

[social]
    twitter = "ve2hew"
    youtube = "thetechzonelive"

[imaging]
# See https://github.com/disintegration/imaging
resampleFilter = "lanczos"

[imaging.exif]
    includeFields = ".*"
```


