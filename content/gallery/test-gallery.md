---
date: '2026-03-11T20:23:00-07:00'
draft: true
title: 'Test Gallery'
slug: 'test-gallery'
tags: []
categories: []
params:
    gallery: 'images/test-gallery/'
cover:
    image: "<cover-image>" # image path/url
    alt: "<alt text>" # alt text
    caption: "caption" # display caption under cover
    relative: true # when using page bundles set this to true
    hiddenInSingle: true # only hide on current single page
    # The image resizing doesn't work on cover images, so images must be present in the body. 
    # But body images don't show in the lists, so a cover image must be present...
    # hiddenInList: false
---

{{< gallery path="images/test-gallery" >}}
