# Onid 

A simple but robust theme for the static site generator [Hugo](https://gohugo.io/).

![Onid Theme](http://i.imgur.com/7KJrFDv.png)

### Install 

After creating a new hugo site, cd into themes and run:

```bash
$ git clone https://github.com/xDinomode/onid
```

Next cd back into the root project and add the theme variable to the config.toml: 

```toml
baseurl = "http://replace-this-with-your-hugo-site.com/"
languageCode = "en-us"
title = "My New Hugo Site"
#add this
theme = "onid"
```

You create a page (contact, about me, etc..):

```bash
# don't forget the .md
$ hugo new contact.md
```

You create an article (/article/cats/):

```bash
# don't forget the .md
$ hugo new article/cats.md
```

All published articles can be viewed at /article
