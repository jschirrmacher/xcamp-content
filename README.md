# xcamp-blog

This repository contains the blog articles for https://xcamp.co

When pushing to `master`, the blog is automatically updated in a minute.

Each article should contain a "meta" block, which contains the following fields:

- **title** - The title of the article. This will be shown in the article list and as the title in the article itself, so there is no need to use another title by yourself.
- **author** - The name of the articles author - normally you ;-)
- **published** - The publishing date of the article.
- **image** - Name of the image file which should be used in the article list.
- **tags** - Comma separated list of tags for this article

In the article itself, you can use Markdown syntax as described in https://github.com/showdownjs/showdown/wiki/Showdown's-Markdown-syntax

Additionally, you can use a html comment `<!-- snip -->` to mark the position to stop showing preview text in the article list.
