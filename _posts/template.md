---
layout: post
title: Template post
author: Firstname Lastname
tags: [authors of interest, my name, topics]
---

_Citation_

## Header 1

This could be one big concept, or an introduction to the topic

Here's a nice picture

<div class="fig figcenter fighighlight">
  <img src="/assets/img/sipping_tea.jpg">
</div>

If you want to use a picture, put it in the assets folder in the repository (location above) then use the above to put it in blog post. 

## Header 2

Another big idea

### Sub-header 

Sub-idea under header 2. Can **bold** or _italicize_ stuff you like. 

Would this be a good spot to pretend there's code? 

```{r}
helpme <- dplyr::tibble(
    a = 1:3
    b = 4:6
)
```

```{sas}
proc sql;
    select count (*) as total
    from helpme
    ;
quit;
```

#### Sub-sub-header 

another level!!

If you want to have a weird little table:

| Syntax      | Description |
| ----------- | ----------- |
| Header      | Title       |
| Paragraph   | Text        |


## What we talked about

Maybe a section to step through what the group talked about. 

Could do bullet points:

* tangential we went on
* another tangential

> or here's a nice aside

Or number
1. here's an idea
2. here's another
