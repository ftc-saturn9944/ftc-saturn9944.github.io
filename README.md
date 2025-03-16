# Saturn 9944 Website

2025 rework of the Saturn9944 website using Hugo and Papermod

## Development Setup

[Install hugo][hugo-install], [git][git] and [go][go] following the official
documentation.

If you have [chocolatey][chocolatey] installed you can install all three with

```pwsh
choco install -y git hugo go
```

## Updating the site

The vast majority of changes to the website can be handled by updating the
existing files under `content/` to add new content.  Doing so requires some
knowledge of [Markdown][md] to get formatting working.  If you are familiar 
with how to format text in Discord or Github then you already know the basics.

If you need to add new pages or change the navigation settings you will have to
look in `./hugo.toml`.  Information about how to modify the settings can be
found on the [hugo][hugo] website.  Theme specific information can be found on 
[papermod][papermod] and information

1. Run `hugo server --navigateToChanged` to get the live reload functionality.
2. In your browser go to http://localhost:1313 to view the website.  When you
   save changes to the pages under `content/` the website will pick up the changes
   allowing you to see the results.
3. Images are stored under `assets/`.  Picture Galleries are under their matching
   paths relative to this.

## Useful Links
These are included in the text above but are gathered here for ease of lookup

- [hugo][hugo]
- [markdown][md]
- [papermod][papermod]

  [hugo-install]: https://gohugo.io/installation/
  [hugo]: https://gohugo.io/
  [papermod]: https://github.com/adityatelange/hugo-PaperMod
  [go]: https://go.dev/doc/install
  [md]: https://www.markdownguide.org/
  [git]: https://git-scm.com/downloads
  [chocolatey]: https://chocolatey.org/install