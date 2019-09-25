# Content for xcamp.co website

This repository contains the content of https://xcamp.co

When pushing to `master`, the blog is automatically updated in a minute.

## Page content

Pages are described with Markdown, a text format used to easily define simple formatting.
It is described in https://github.com/showdownjs/showdown/wiki/Showdown's-Markdown-syntax

## Page types

Currently, there are two kinds of pages, blog articles (located in `/_posts`) and team member pages (located in `/team`).

Each page should contain a "meta" block, which is at the beginning of each page and is surrounded by lines of three
dashes `---`.

The meta block contains the following fields:

**blog pages**
- **layout** - Should be set to `post`.
- **title** - The title of the article. It will be shown in the article list and as the title in the article itself, so
  there is no need to use another title by yourself.
- **authorPage** - The name of the authors page (in `/team` folder, don't use the `.md` here, just the name)
- **author** - The name of the articles author - you can leave that blank, if you have specified a `authorPage` and this
  page contains a `title` 
- **published** - The publishing date of the article.
- **image** - Name of the image file which should be used in the article list.
- **tags** - Comma separated list of tags for this article

**team member pages**
- **layout** - Should be set to `member-page`.
- **title** - The title of the page, which is the team members name.
- **image** - File name of a profile picture of the team member.


In blog pages, you can use a html comment `<!--more-->` in the markdown text to mark the position to stop showing
preview text in the article list.
