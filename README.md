# Minimal Theme

The [Minimal](http://orderedlist.com/minimal/) Theme for [nico](http://lab.lepture.com/nico/)

This theme requires nico 0.4.6+ now.

## Configuration

The basic configuration for a blog:

```
{
    "source": "content",
    "output": "_site",
    "theme": "_themes/minimal",
    "sitename": "Nico",
    "siteurl": "http://lab.lepture.com/nico/",
    "permalink": "{{directory}}/{{filename}}.html",
    "writers": [
        "nico.PostWriter",
        "nico.PageWriter",
        "nico.FileWriter",
        "nico.StaticWriter",
        "nico.ArchiveWriter",
        "nico.YearWriter",
        "nico.TagWriter",
        "nico.DirectoryWriter",
        "nico.FeedWriter"
    ]
}
```

Additional configuration this theme:

- tagline: A description of your site.
- touchIcon: Link of Apple Touch Icon.
- hideNico: Hide nico copyright at bottom.
- github: Github link, a github fork badge will display.
- navigation: A array of items of navigation.

GitHub example:

```
{
    "github": [
        {"title": "ZIP File", "link": "https://github.com/7anshuai/nico-minimal/zipballmus/master"},
        {"title": "TAR Ball", "link": "https://github.com/7anshuai/nico-minimal/tarball/master"},
        {"title": "GitHub", "link": "https://github.com/7anshuai/nico-minimal"}
    ]
}
```

Navigation example:

```
{
    "navigation": [
        {"title": "Life", "link": "/life/index.html"},
        {"title": "Work", "link": "/work/index.html"}
    ]
}
```

## Comment

Comment is available for posts. This theme support disqus and duoshuo.

Configure a disqus short name:

```
{
    "disqus": "short name"
}
```

If you prefer duoshuo:

```
{
    "duoshuo": "short name"
}
```
