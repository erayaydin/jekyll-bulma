---
layout: post
title: Markup - Post with Images
description: Displaying images in posts
categories:
    - Markup
comments: true
permalink: post-with-images.html
---

Here are some examples of what a post with images might look like. You should add `image` class to `<img>` tag.

## Fixed Square Images

There are **7** dimensions to choose from, useful for **avatars**:

| `image is-16x16` | <figure class="image is-16x16"><img src="/assets/images/placeholders/16x16.png" alt="16x16" /></figure> | 16x16px
| `image is-24x24` | <figure class="image is-24x24"><img src="/assets/images/placeholders/24x24.png" alt="24x24" /></figure> | 24x24px
| `image is-32x32` | <figure class="image is-32x32"><img src="/assets/images/placeholders/32x32.png" alt="32x32" /></figure> | 32x32px
| `image is-48x48` | <figure class="image is-48x48"><img src="/assets/images/placeholders/48x48.png" alt="48x48" /></figure> | 48x48px
| `image is-64x64` | <figure class="image is-64x64"><img src="/assets/images/placeholders/64x64.png" alt="64x64" /></figure> | 64x64px
| `image is-96x96` | <figure class="image is-96x96"><img src="/assets/images/placeholders/96x96.png" alt="96x96" /></figure> | 96x96px
| `image is-128x128` | <figure class="image is-128x128"><img src="/assets/images/placeholders/128x128.png" alt="128x128" /></figure> | 128x128px

## Responsive images with ratios

If you don't know the exact dimensions but know the **ratio** instead, you can use one of the **5 ratio modifiers**:

| `image is-square` | <figure class="image is-square"><img src="/assets/images/placeholders/480x480.png" alt="Square" /></figure> | Square (or 1by1)
| `image is-1by1` | <figure class="image is-1by1"><img src="/assets/images/placeholders/480x480.png" alt="1By1" /></figure> | 1 by 1
| `image is-4by3` | <figure class="image is-4by3"><img src="/assets/images/placeholders/640x480.png" alt="4By3" /></figure> | 4 by 3
| `image is-3by2` | <figure class="image is-3by2"><img src="/assets/images/placeholders/480x320.png" alt="3By2" /></figure> | 3 by 2
| `image is-16by9` | <figure class="image is-16by9"><img src="/assets/images/placeholders/640x360.png" alt="16By9" /></figure> | 16 by 9
| `image is-2by1` | <figure class="image is-2by1"><img src="/assets/images/placeholders/640x320.png" alt="2By1" /></figure> | 2 by 1

The `.image` container will take up the **whole width** while maintaining the perfect ratio.