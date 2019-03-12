---
title: "Adding Website Content"
author: "EEECS Lego Lab"
---

# Adding Website Content

This website uses Jekyll to convert text files into stylised HTML pages with the EEECS Lego Lab branding. These files are uploaded to Github where the website is hosted. To add new pages and content, files can be uploaded directly to the Github repository.

## Creating a new file

Create a new text file - for a blog or project post, the title of the file must be the date in the format
```
YYYY/MM/DD-BlogTitle.md
e.g.
2019/03/13-MyNewBlogPost.md
```
For a generic site page, the title of the file just needs to be unique to that page, as it will be used for the URL to that page.
```
mynewpage.md
```
Will be accessible from:
```
https:///eeecslegolab.github.io/_pages/mynewpage
```

Each page/blog/project must have the following format:
```
---
title: "PAGE TITLE HERE"
author: "YOUR NAME HERE"
---
your content here.....
```
Formatting for your page can either be standard HTML tags, or [in Markdown syntax](https://www.markdownguide.org/basic-syntax/).

## Uploading to Github

Log into Github, and use the 'Upload file' tool to upload your new page to one of the following locations, depending on its content.

```
Github Repository
│   .github
│   _layouts
│   _sass
│   assets
│   docs
│   ...
│ 
└───_posts
│   │
│   └───blog
│   │   │   2019/03/13-MyNewBlogPost.md
│   │   │   BLOG POST FILES GO HERE
│   │   └   ...
│   │
│   └───projects
│       │   2019/04/15-MyNewProject.md
│       │   PROJECT FILES GO HERE
│       └   ...
│   
└───_pages
    │   tutorial.md <- This page!
    │   STANDARD PAGES GO HERE
    │   ...
```