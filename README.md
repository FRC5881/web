# 5881 Website

This is the repository for the website of FRC 5881, the TVHS Dragons. The website is built using [Hugo](https://gohugo.io/), a static site generator. We're using the [dot-org](https://themes.gohugo.io/themes/dot-org-hugo-theme/) theme.

## Website Structure

The website is organized into the following pages:

- Home
- Blog
- Sponsors
- About Us
- Support

### Home

The home page is simply an index to quickly navigate to the other pages. We shouldn't really put any content here.

### Blog

Generally, this is where we should post updates. Similar to our Instagram or other social media. We can post game reveals, build season updates, sponsor spotlights, and competition results here. A new blog post can be added by adding a new markdown file to the [content/en/blog](content/en/blog) directory.

Blogs posts should have the follow structure:

```markdown
---
title: "My first blog post!"
date: 2024-01-06
author: alextopher
---

Hello world!
```

The author-field is configured by editing the [data/authors.yml](data/authors.yml) file. If you're posting blog posts you should add yourself to the authors file.

```yaml
alextopher:
  name: Christopher Mahoney
```

### Sponsors

A list of this year's sponsors and their logos.

At the end of every season, we should post a blog post as a thank you to our sponsors. This will serve as an archive of our sponsors over the years.

### Support

Information on how to support the team. Either financially or through donations of materials, tools, or services.

Every season the business team should evaluate this page and update it to encourage more support.

### About Us

Introduction about TVHS, FIRST Robotics Competition, and our team.

## Hosting

At the moment this website is being hosted by our mentor @Alextopher. He will redeploy it as often as necessary.
