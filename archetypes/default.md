---
date: '{{ .Date }}'
draft: true
title: '{{ replace (replaceRE "^\\d{4}-\\d{2}-\\d{2}-" "" .File.ContentBaseName) "-" " " | title }}'
slug: '{{ replaceRE "^\\d{4}-\\d{2}-\\d{2}-" "" .File.ContentBaseName | lower }}'
tags: []
categories: []
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