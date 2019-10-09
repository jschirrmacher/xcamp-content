# Content for xcamp.co website

This repository contains the content of https://xcamp.co

When pushing to `master`, the website is automatically updated in a minute. There is also a `preview` branch,
which is shown in https://test.xcamp.co - this should be used to test the changes, before merging to the `master`
branch.

## Page content

Pages are described with Markdown, a text format used to easily define simple formatting.
It is described in https://github.com/showdownjs/showdown/wiki/Showdown's-Markdown-syntax

All pages have an extension `.md` for "Markdown".

Each page should contain a "meta" block, which is at the beginning of each page and is surrounded by lines of three
dashes `---`.

The meta block contains at least the following fields:

- **layout** - Should be set to `standard` in most of the cases, but could specify another template if needed.
- **title** - The title of the page.

## Special page types

There are two special kinds of pages, blog articles (located in `/blog`) and team member pages (located in `/team`).

Blog pages should have their `layout` meta field set to `blog`, team member pages should have the `layout` value
`member-page`.

The meta block contains the following additional fields:

**blog pages**
- **authorPage** - The name of the authors page (in `/team` folder, don't use the `.md` here, just the name)
- **author** - The name of the articles author - you can leave that blank, if you have specified a `authorPage` and this
  page contains a `title` 
- **published** - The publishing date of the article.
- **image** - Name of the image file which should be used in the article list.
- **tags** - Comma separated list of tags for this article

**team member pages**
- **image** - File name of a profile picture of the team member.


In blog pages, you can use a html comment `<!--more-->` in the markdown text to mark the position to stop showing
preview text in the article list.
