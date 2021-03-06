---
title: "Lorem Arrested Development"
subtitle: "How to add panelsets in R Markdown posts."
excerpt: "Add tabbed sections with code and results."
date: 2021-05-24
author: "Alison Hill"
draft: false
# layout options: single, single-sidebar
layout: single
categories:
- evergreen
---

{{< here >}}

## Testing code here

```r
library(tidyverse)
```

```
## -- Attaching packages --------------------------------------- tidyverse 1.3.1 --
```

```
## v ggplot2 3.3.5     v purrr   0.3.4
## v tibble  3.1.3     v dplyr   1.0.7
## v tidyr   1.1.3     v stringr 1.4.0
## v readr   2.0.0     v forcats 0.5.1
```

```
## -- Conflicts ------------------------------------------ tidyverse_conflicts() --
## x dplyr::filter() masks stats::filter()
## x dplyr::lag()    masks stats::lag()
```

```r
glimpse(mpg)
```

```
## Rows: 234
## Columns: 11
## $ manufacturer <chr> "audi", "audi", "audi", "audi", "audi", "audi", "audi", "~
## $ model        <chr> "a4", "a4", "a4", "a4", "a4", "a4", "a4", "a4 quattro", "~
## $ displ        <dbl> 1.8, 1.8, 2.0, 2.0, 2.8, 2.8, 3.1, 1.8, 1.8, 2.0, 2.0, 2.~
## $ year         <int> 1999, 1999, 2008, 2008, 1999, 1999, 2008, 1999, 1999, 200~
## $ cyl          <int> 4, 4, 4, 4, 6, 6, 6, 4, 4, 4, 4, 6, 6, 6, 6, 6, 6, 8, 8, ~
## $ trans        <chr> "auto(l5)", "manual(m5)", "manual(m6)", "auto(av)", "auto~
## $ drv          <chr> "f", "f", "f", "f", "f", "f", "f", "4", "4", "4", "4", "4~
## $ cty          <int> 18, 21, 20, 21, 16, 18, 18, 18, 16, 20, 19, 15, 17, 17, 1~
## $ hwy          <int> 29, 29, 31, 30, 26, 26, 27, 26, 25, 28, 27, 25, 25, 25, 2~
## $ fl           <chr> "p", "p", "p", "p", "p", "p", "p", "p", "p", "p", "p", "p~
## $ class        <chr> "compact", "compact", "compact", "compact", "compact", "c~
```

## But first, panelsets with R code chunks

{{< panelset class="greetings" >}}
{{< panel name="Plot" >}}

<img src="{{< blogdown/postref >}}index_files/figure-html/plot-1.png" width="672" />

{{< /panel >}}
{{< panel name="Code" >}}


```r
plot(pressure)
```

{{< /panel >}}
{{< /panelset  >}}

## I'm half machine. I'm a monster.

It's a hug, Michael. I'm hugging you. I'm half machine. I'm a monster. There's only one man I've ever called a coward, and that's Brian Doyle Murray. No, what I'm calling you is a television actor. Bad news. Andy Griffith turned us down. He didn't like his trailer.

No, I did not kill Kitty. However, I am going to oblige and answer the nice officer's questions because I am an honest man with no secrets to hide. Guy's a pro. Really? __Did nothing cancel?__ *Get me a vodka rocks.* And a piece of toast.

## No??? but I'd like to be asked!

Oh, you're gonna be in a coma, all right. Steve Holt! I hear the jury's still out on science. No, I did not kill Kitty. However, I am going to oblige and answer the nice officer's questions because I am an honest man with no secrets to hide.

1. Really? Did nothing cancel?
2. That's what it said on 'Ask Jeeves.'
3. Get me a vodka rocks. And a piece of toast.

### That's what it said on 'Ask Jeeves.'

Did you enjoy your meal, Mom? You drank it fast enough. What's Spanish for "I know you speak English?" Bad news. Andy Griffith turned us down. He didn't like his trailer. Really? Did nothing cancel? I care deeply for nature.

* Michael!
* No! I was ashamed to be SEEN with you. I like being with you.
* We just call it a sausage.

Well, what do you expect, mother? It's called 'taking advantage.' It's what gets you ahead in life. Now, when you do this without getting punched in the chest, you'll have more fun. No, I did not kill Kitty. However, I am going to oblige and answer the nice officer's questions because I am an honest man with no secrets to hide.

I'm half machine. I'm a monster. It's a hug, Michael. I'm hugging you. Guy's a pro. First place chick is hot, but has an attitude, doesn't date magicians. He'll want to use your yacht, and I don't want this thing smelling like fish.

He'll want to use your yacht, and I don't want this thing smelling like fish. Now, when you do this without getting punched in the chest, you'll have more fun. We just call it a sausage. Guy's a pro. Bad news. Andy Griffith turned us down. He didn't like his trailer.

There's only one man I've ever called a coward, and that's Brian Doyle Murray. No, what I'm calling you is a television actor. It's called 'taking advantage.' It's what gets you ahead in life. We just call it a sausage.

Michael! First place chick is hot, but has an attitude, doesn't date magicians. I've opened a door here that I regret. Guy's a pro.

Army had half a day. Michael! Now, when you do this without getting punched in the chest, you'll have more fun. Well, what do you expect, mother? Now, when you do this without getting punched in the chest, you'll have more fun.

But I bought a yearbook ad from you, doesn't that mean anything anymore? Oh, you're gonna be in a coma, all right. It's a hug, Michael. I'm hugging you. I've opened a door here that I regret.

There's only one man I've ever called a coward, and that's Brian Doyle Murray. No, what I'm calling you is a television actor. That's why you always leave a note! He'll want to use your yacht, and I don't want this thing smelling like fish.

I've opened a door here that I regret. Now, when you do this without getting punched in the chest, you'll have more fun. I care deeply for nature. It's called 'taking advantage.' It's what gets you ahead in life.

It's a hug, Michael. I'm hugging you. No??? but I'd like to be asked! What's Spanish for "I know you speak English?" It's called 'taking advantage.' It's what gets you ahead in life. It's a hug, Michael. I'm hugging you.

I don't understand the question, and I won't respond to it. Really? Did nothing cancel? Did you enjoy your meal, Mom? You drank it fast enough. Bad news. Andy Griffith turned us down. He didn't like his trailer.


