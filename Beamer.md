---
title: Example
author: Nick Hood
date: 29th April 2020
# background-image: desktop.JPG
classoption: "aspectratio=169"
theme: Pittsburgh
colortheme: beaver
fonttheme: structuresmallcapsserif
---

## Outline / Agenda
* Introduction 
* Next
* Q & A

## Main presentation

::: {.columns}
::: {.column width="60%"}
Ut eleifend blandit lobortis. Aliquam quis commodo purus. Suspendisse porta leo id vulputate placerat. Praesent purus erat, placerat vel odio quis, semper sodales eros. Ut consectetur rhoncus laoreet. Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vestibulum ante ipsum primis in faucibus orci luctus et ultrices posuere cubilia Curae; Quisque euismod tincidunt purus, id blandit turpis tincidunt non. Nunc ultricies, dui sed venenatis aliquam, neque ipsum bibendum nisi, nec egestas neque velit cursus augue. Aenean molestie leo ut ante semper gravida. Nam feugiat purus sed fringilla maximus [@Kruger1999].
:::
::: {.column }
![Santana](Carlos_Santana.jpg)
:::
:::

## Bullets and links

* First [Link](https://cullaloe.net)!
* No link
* Bullet

# Q & A

## How to make this
```bash
$ pandoc -t beamer Beamer.md -o Beamer.pdf \
    --bibliography="/path/to/bibliography.bib"
```
Themes, etc. are [online](http://deic.uab.es/~iblanes/beamer_gallery/index_by_theme.html)

## YAML Header

```ruby
---
title: Example
author: Nick Hood
date: 22nd September 2019
background-image: forth-bridge.jpg
classoption: "aspectratio=169"
theme: Pittsburgh
colortheme: beaver
fonttheme: structuresmallcapsserif
---
```

## References

<!--END-->
