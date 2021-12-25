# Jekyll-starter
Purpose of this project is to help you create your first static website with [Jekyll](https://jekyllrb.com/) as easily as possible. It is free, you just need a GitHub account and follow the steps below 😉

## About Jekyll
Jekyll is one of the [most popular](https://jamstack.org/generators/) static site generators. It takes text written in your favorite markup language (e.g. Markdown, Textile, etc.) and uses layouts (themes) to create a static website. It does not use databases to generate the pages dynamically. Instead of using databases, Jekyll supports loading content from YAML, JSON, CSV, and TSV files. This content can be accessed via [Liquid](https://shopify.github.io/liquid/) templating system. [GitHub Pages](https://pages.github.com/) are powered by Jekyll behind the scenes, so they’re a great way to host your Jekyll-powered website for free. Another possible solution is to host Jekyll sites by [GitLab Pages](https://docs.gitlab.com/ee/user/project/pages/).

## Demo
Here is a [**LIVE DEMO**](https://brazacz.github.io/jekyll-starter) preview of default static website which was generated by GitHub Pages from this [source repository](https://github.com/brazacz/jekyll-starter).

## Getting started with Jekyll Starter
1. First you need to create a [GitHub account](https://github.com/join). GitHub will be used to host your websites for free.
2. Either follow this step-by-step [tutorial](https://docs.github.com/en/pages/setting-up-a-github-pages-site-with-jekyll) or you can simply ![Fork](https://raw.githubusercontent.com/brazacz/svg-icons/main/src/github-fork.svg) **Fork** (copy) [this repository](https://github.com/brazacz/jekyll-starter) to your GitHub account by clicking on [this link](https://github.com/brazacz/jekyll-starter/fork).
3. Go to your GitHub account >> Repositories >> jekyll-starter >> Settings >> Pages. Or simply open `https://github.com/<YourUserName>/jekyll-starter/settings/pages` where `<YourUserName>` is your Github user name. Please set the **Source** of GitHub Pages to be `Branch: gh-pages` and click **Save**. Now wait a minute until your site is published.
4. Your published website is here: `https://<YourUserName>.github.io/jekyll-starter`, where `<YourUserName>` is your Github user name.
5. Customize your website to your needs. Configure your website by changing `_config.yml`, edit the main page by changing `index.md` and edit the about page by changing `about.md`. To edit these files, find them in GitHub (e.g. `https://github.com/<YourUserName>/jekyll-starter/_config.yml`), click ![Edit](https://raw.githubusercontent.com/brazacz/svg-icons/main/src/github-edit.svg) **Edit**, make your changes and ![Commit](https://raw.githubusercontent.com/brazacz/svg-icons/main/src/github-commit.svg) **Commit** (save) the changes. If you want to create posts, please folow this [tutorial](https://jekyllrb.com/docs/posts/). If you want to work with data files, use this [tutorial](https://jekyllrb.com/docs/datafiles/). See more information in [Jekyll documentation](https://jekyllrb.com/docs/)

## About Markdown
Markdown is a markup language which allows you to write using an easy-to-read, easy-to-write plain text format, then convert it to structurally valid XHTML (or HTML). To write in markdown language, please use file extensions `.md` or `.markdown`. Here is an example of markdown usage:

```markdown
# Heading level 1
## Heading level 2
### Heading level 3

- Unordered list 1
- Unordered list 2

1. Numbered list 1
2. Numbered list 2

> Here is a blockquote

**Bold**, *Italic* and `Inline code` text

[Link](url) and ![Image](src)
```
Even this text you are reading right now is written in markdown - you can check the source file [index.md](https://raw.githubusercontent.com/brazacz/jekyll-starter/gh-pages/index.md). For more details about writing in markdown see [this tutorial](https://docs.github.com/en/github/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax).

## Jekyll Themes
To change the layout and styles of your site you can change the `_config.yml` configuration file. Default setting is `theme: minima`. Here is the [list of themes](https://rubygems.org/search?query=summary%3Ajekyll+summary%3Atheme) you can use. Just replace `minima` with another theme and commit the changes (e.g. `jekyll-theme-cayman`, `just-the-docs` or `minimal-mistakes-jekyll`).

## References
- [Jekyll Quickstart](https://jekyllrb.com/docs/)
- [Jekyll Directory Structure](https://jekyllrb.com/docs/structure/)
- [Jekyll Minima Theme](https://github.com/jekyll/minima)
- [Jekyll Full Installation Guide](https://jekyllrb.com/docs/step-by-step/01-setup/)
- [GitHub Pages](https://pages.github.com/)
- [GitLab Pages](https://docs.gitlab.com/ee/user/project/pages/)
- [Liquid templating language](https://shopify.github.io/liquid/)

## License
This project is available as open source under the terms of the [MIT License](http://opensource.org/licenses/MIT).

## Contributing
This project is intended to be a safe, welcoming space for collaboration. If you found an mistake or better expression, please raise an ![Issue](https://raw.githubusercontent.com/brazacz/svg-icons/main/src/github-issue.svg) [Issue](https://github.com/brazacz/jekyll-starter/issues/new). If you want to contribute, please ![Fork](https://raw.githubusercontent.com/brazacz/svg-icons/main/src/github-fork.svg) [Fork](https://github.com/brazacz/jekyll-starter/fork) this repository, make your changes and send a ![Pull Request](https://raw.githubusercontent.com/brazacz/svg-icons/main/src/github-pullrequest.svg) [Pull Request](https://github.com/brazacz/jekyll-starter/pulls).