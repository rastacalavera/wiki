---
title: What have I done?
summary: List of changes I've made.
authors:
- Rastacalavera
---

## Extensions
I added these to the `mkdocs.yml` file:
```
  - attr_list
  - md_in_html
```
The `attr_list` allows for cool additions and the `md_in_html` allows for html to be rendered in markdown files.

## Plugins
I added this to the `mkdocs.yml` file 
```
- glightbox
```
This plugin allows for images to be zoomed when clicked and can display a carousel of images that are all on a page. For this to work, an additional python packaged needed to be added to the `requirements.txt` file
```
mkdocs-glightbox
```