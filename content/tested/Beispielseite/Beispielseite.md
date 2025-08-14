---
title: "Beispielseite"
description: "Reference pages are ideal for outlining how things work in terse and clear terms."
summary: ""
date: 2025-03-06T22:10:00+02:00
lastmod: 2025-03-06T22:10:00+02:00
draft: false
weight: 810
toc: true
---

## Typography

Paragraphs are separated by a blank line.

2nd paragraph. *Italic*, **bold**, and `monospace`.

I need to highlight these <mark>very important words</mark>.

H<sub>2</sub>O

x<sup>2</sup>

Use 3 dashes for an em-dash like this ---. Use 2 dashes for ranges (ex., "it's all
in chapters 12--14"). Three dots ... will be converted to an ellipsis.
Unicode is supported. ☺

~~The world is flat.~~ We now know that the world is round.

### Emoji

Gone camping! :tent: Be back soon.

That is so funny! :joy: 😂

You find the complete list [here](https://gist.github.com/rxaviers/7360908).

## Boxes

### Callouts

"Normal" callouts:

{{< callout note >}} This is a note callout. Example text to show it in action. {{< /callout >}}

{{< callout tip >}} This is a tip callout. Example text to show it in action. {{< /callout >}}

{{< callout context="note" title="Aufgabe" icon="outline/edit" >}}
This is a note callout. Example text to show it in action.
{{< /callout >}}

{{< callout context="note" title="Note" icon="outline/info-circle" >}}
Test.
{{< /callout >}}

Tip:

{{< callout context="tip" title="Wusstest du?" icon="outline/bulb" >}}
Thulite simplifies developer on boarding time and makes for faster collaboration by using a single declaration manifest for [dependencies](https://docs.thulite.io/concepts/dependencies/).
{{< /callout >}}

Caution:

{{< callout context="caution" title="Aufpassen!" icon="outline/alert-triangle" >}}
If you are not sure you want an awesome docs site, think twice before using [Doks](https://getdoks.org/).
{{< /callout >}}

Important:

{{< callout context="important" title="Merke dir:" icon="outline/device-floppy" >}}
Test.
{{< /callout >}}

Example:

{{< callout context="example" title="Beispiel gefällig?" icon="outline/puzzle" >}}
Test.
{{< /callout >}}

Question:

{{< callout context="question" title="Nachgedacht..." icon="outline/help" >}}
Test.
{{< /callout >}}

Danger:

{{< callout context="danger" title="Problem!?" icon="outline/bolt" >}}
Test.
{{< /callout >}}

### Notes

> **Info:**  The note content.

### Details

Closed at the beginning:

{{< details "Details" >}}
Something small enough to escape casual notice.
{{< /details >}}

Start in open state:

{{< details "Start in open state" open >}}
This Boolean attribute indicates whether the details -- that is, the contents of the details-element -- are currently visible. The details are shown when this attribute exists, or hidden when this attribute is absent. By default this attribute is absent which means the details are not visible.
{{< /details >}}

### Tabs

{{< tabs "create-new-site" >}}
{{< tab "Hinweis #1" >}}

```bash
npm create thulite@latest
```

{{< /tab >}}
{{< tab "Hinweis #2" >}}

```bash
pnpm create thulite@latest
```

{{< /tab >}}
{{< tab "Hinweis #3" >}}

```bash
yarn create thulite
```

{{< /tab >}}
{{< /tabs >}}

### Link cards

{{< link-card
  title="Showcase"
  description="Explore the infinite possibilities of Doks"
  href="#link-cards"
  target="_blank"
>}}

{{< link-card title="eins alleine" href="#link-cards" >}}

{{< card-grid >}}
{{< link-card title="eins" href="#link-cards" >}}
{{< link-card title="zwei" href="#link-cards" >}}
{{< /card-grid >}}

{{< card-grid >}}
{{< link-card title="eins" href="#link-cards" >}}
{{< link-card title="zwei" href="#link-cards" >}}
{{< link-card title="drei" href="#link-cards" >}}
{{< /card-grid >}}

{{< card-grid >}}
{{< link-card title="eins" href="#link-cards" >}}
{{< link-card title="zwei" href="#link-cards" >}}
{{< link-card title="drei" href="#link-cards" >}}
{{< link-card title="vier" href="#link-cards" >}}
{{< /card-grid >}}

{{< card-grid >}}
{{< link-card title="eins" href="#link-cards" >}}
{{< link-card title="zwei" href="#link-cards" >}}
{{< link-card title="drei" href="#link-cards" >}}
{{< link-card title="vier" href="#link-cards" >}}
{{< link-card title="fünf" href="#link-cards" >}}
{{< /card-grid >}}

### Quotes

> Block quotes are
> written like so.
>
> They can span multiple paragraphs,
> if you like.

> "Quote."\
> <cite>Author</cite>

## Code blocks

This is `some inline code`.

Here's a code sample:

    # Let me re-iterate ...
    for i in 1 .. 10 { do-something(i) }

As you probably guessed, indented 4 spaces. By the way, instead of
indenting the block, you can use delimited blocks, if you like:

```python
define foobar() {
    print "Welcome to flavor country!";
}
```

(which makes copying & pasting easier). You can optionally mark the
delimited block for Pandoc to syntax highlight it:

```python
import time
# Quick, count to ten!
for i in range(10):
    # (but not *too* quick)
    time.sleep(0.5)
    print i
```

### Code blocks with line numbers

```js {lineNos=true lineNoStart=32}
if ([1, "one", 2, "two"].includes(value)) {
  console.log("Number is either 1 or 2."); // comment
}
```

```go {linenos=true,hl_lines=[8,"15-17"],linenostart=199}
// GetTitleFunc returns a func that can be used to transform a string to
// title case.
//
// The supported styles are
//
// - "Go" (strings.Title)
// - "AP" (see https://www.apstylebook.com/)
// - "Chicago" (see https://www.chicagomanualofstyle.org/home.html)
//
// If an unknown or empty style is provided, AP style is what you get.
func GetTitleFunc(style string) func(s string) string {
  switch strings.ToLower(style) {
  case "go":
    return strings.Title
  case "chicago":
    return transform.NewTitleConverter(transform.ChicagoStyle)
  default:
    return transform.NewTitleConverter(transform.APStyle)
  }
}
```

### Terminal windows

```bash {title="Installing dependencies…"}
npm install
```

## Lists

Itemized lists look like:

- this one
- that one
- the other one

Note that --- not considering the asterisk --- the actual text
content starts at 4-columns in.

Here's a numbered list:

 1. first item
 2. second item
 3. third item

Note again how the actual text starts at 4 columns in (4 characters
from the left side).

Now a nested list:

 1. First, get these ingredients:

      * carrots
      * celery
      * lentils

 2. Boil some water.

 3. Dump everything in the pot and follow
    this algorithm:

        find wooden spoon
        uncover pot
        stir
        cover pot
        balance wooden spoon precariously on pot handle
        wait 10 minutes
        goto first step (or shut off burner when done)

    Do not bump wooden spoon or it will fall.

Here is a task list:

- [x] Write the press release
- [ ] Update the website
- [ ] Contact the media

Notice again how text always lines up on 4-space indents (including
that last line which continues item 3 above).

Here's a definition list:

apples
: Good for making applesauce.

oranges
: Citrus!

tomatoes
: There's no "e" in tomatoe.

## Links

Here's a link to [a website](https://kicker.de), to a [local
doc](local-doc.html), and to a [section heading in the current
doc](#an-h2-header). Here's a footnote [^1].

[^1]: Footnote text goes here.

## Tables

Tables can look like this:

| linksbündig | rechtsbündig | zentriert | normal |
| :--- | ---: | :---: | --- |
| Lorem ipsum dolor sit amet consectetur adipisicing elit. Temporibus sint nesciunt distinctio recusandae culpa. Tempore vero iusto magnam veniam architecto ipsam, fugit, enim nobis ut eius tenetur, sequi placeat cupiditate. | Lorem ipsum dolor sit amet consectetur adipisicing elit. Veritatis modi vitae maxime. Nobis cum suscipit dolorem accusamus. Non dolor voluptas eveniet beatae excepturi quis nemo, voluptatum ipsam fugiat veniam dignissimos! | Lorem ipsum dolor sit amet, consectetur adipisicing elit. Dolor voluptatem saepe, recusandae nostrum tenetur beatae repellat autem. Libero exercitationem fugiat deleniti.  | Lorem ipsum dolor sit amet consectetur adipisicing elit. Commodi impedit magni voluptates, cum dolorum placeat distinctio expedita dicta consequatur possimus amet culpa voluptate nihil ab eius, sint sequi necessitatibus ut. |
| eins | zwei | drei | vier ||

## Images and Videos

### Images

Images can be specified like so:

[logo]: https://github.com/adam-p/markdown-here/raw/master/src/common/images/icon48.png "Ein Logo"

![logo]

### Videos

<!-- [![IMAGE ALT TEXT HERE](https://img.youtube.com/vi/6MAzUT1YhWE/0.jpg)](https://youtu.be/6MAzUT1YhWE?si=LLOdcIgy6FyLLRG1) -->

<iframe width="560" height="315" src="https://www.youtube.com/embed/6MAzUT1YhWE?si=CyPKf2shoA8U7gTw" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>

## Math expressions

Inline math equations go in like so: {{< math >}}$\omega = d\phi / dt${{< /math >}}. Display
math should get its own line and be put in in double-dollarsigns:

```math
$$
\frac{1}{\Gamma(s)}\int_{0}^{\infty} \frac{u^{s-1}}{e^{u}-1} \mathrm{d}u
$$
```

```math {.text-center}
$$
I = \int \rho R^{2} dV
$$
```

And note that you can backslash-escape any punctuation characters which you wish to be displayed literally, ex.: \`foo\`, \*bar\*, etc.
