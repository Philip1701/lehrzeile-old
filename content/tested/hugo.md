---
title: "Hugo Framework"
description: "Eine Beschreibung."
summary: "Zusammenfassung"
date: 2025-03-06T22:10:00+02:00
lastmod: 2025-03-06T22:10:00+02:00
draft: false
weight: 830
toc: true
---

Website:
[https://gohugo.io](https://gohugo.io)

## Installation

Quelle:
[https://gohugo.io/installation/macos/](https://gohugo.io/installation/macos/)


1) To install the extended edition of Hugo:
```sh
brew install hugo
```

2) To build the extended or extended/deploy edition from source you must:
	1. Install [Git](https://git-scm.com/)
	2. Install [Go](https://go.dev/) version 1.23.0 or later
	3. Install a C compiler, either [GCC](https://gcc.gnu.org/) or [Clang](https://clang.llvm.org/)

3) To build the standard edition:
```sh
go install github.com/gohugoio/hugo@latest
```


## Hugo starten

#### Hugo-Verzeichnis anlegen:

Create the [directory structure](https://gohugo.io/getting-started/directory-structure/) for your project in the `quickstart` directory.
```sh
hugo new site quickstart
```

Change the current directory to the root of your project.
```sh
cd quickstart
```

#### Theme installieren (Option 1):

[^1] Change into the `themes` directory and download a theme by replacing `URL_TO_THEME` with the URL of the theme repository:
```sh
cd themes
git clone URL_TO_THEME
```


#### Theme installieren (Option 2):

Initialize an empty Git repository in the current directory.
```sh
git init
```

Clone the [Ananke](https://github.com/theNewDynamic/gohugo-theme-ananke) theme into the `themes` directory, adding it to your project as a [Git submodule](https://git-scm.com/book/en/v2/Git-Tools-Submodules).
```sh
git submodule add https://github.com/theNewDynamic/gohugo-theme-ananke.git themes/ananke
```

Append a line to the site configuration file, indicating the current theme.
```sh
echo "theme = 'ananke'" >> hugo.toml
```


#### Server starten
Start Hugo’s development server to view the site.
```sh
hugo server
```

alternativ:
```sh
hugo server --minify --theme [themename]
```

Press `Ctrl + C` to stop Hugo’s development server.


#### Website aufrufen:
[http://localhost:1313/](http://localhost:1313/)



## Befehle

Add a new page to your site.
```sh
hugo new content content/posts/my-first-post.md
```


## Themes

Übersicht:
[https://themes.gohugo.io](https://themes.gohugo.io)

Hugo Book Theme:
[https://themes.gohugo.io/themes/hugo-book/](https://themes.gohugo.io/themes/hugo-book/)

LoveIt Theme:
[https://themes.gohugo.io/themes/loveit/](https://themes.gohugo.io/themes/loveit/)

Doks:
[https://themes.gohugo.io/themes/doks/](https://themes.gohugo.io/themes/doks/)

[^1]: Quelle:
	https://gohugobrasil.netlify.app/themes/installing-and-using-themes/
