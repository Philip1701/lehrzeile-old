---
title: "Beispiel 2"
description: "Reference pages are ideal for outlining how things work in terse and clear terms."
summary: ""
date: 2025-03-06T22:10:00+02:00
lastmod: 2025-03-06T22:10:00+02:00
draft: true
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

### Boxen mit eigenen Shortcodes

{{< box-notice title="" >}}
    Mit <code>box-notice</code> kann eine Merkbox gesetzt werden.
{{< /box-notice >}}

{{< box-question title="" >}}
    Mit <code>box-question</code> können Fragen, Dinge zum Nachdenken oder wichtige Hinweise gesetzt werden.
{{< /box-question >}}

{{< box-important title="" >}}
    Der Shortcode <code>box-important</code> ist für wichtige Hinweise.
{{< /box-important >}}

{{< box-note title="" >}}
    Mithilfe von <code>box-note</code> können ebenfalls -- allerdings weniger auffällige -- Hinweise gesetzt werden.
{{< /box-note >}}

### Eigene Aufgabenumgebungen

Eine "normale" Aufgabenumgebung:

{{< job numbered="false" name="" title="Aufgabe" style="" columns="" >}}
Test. Lorem ipsum dolor sit amet consectetur, adipisicing elit. Dicta nemo ipsa deserunt? Quos officia aperiam distinctio animi ducimus. Delectus doloremque deserunt laborum ipsam, repellendus perferendis fuga iusto molestias tenetur neque!
{{< /job >}}

{{< job numbered="false" name="Dein Job" title="" style="" columns="2" >}}
Test. Lorem ipsum dolor sit amet consectetur, adipisicing elit. Dicta nemo ipsa deserunt? Quos officia aperiam distinctio animi ducimus. Delectus doloremque deserunt laborum ipsam, repellendus perferendis fuga iusto molestias tenetur neque!
<ol type="1">
  <li>erste Spalte</li>
  <li>erste Spalte</li>
  <li>zweite Spalte</li>
  <li>zweite Spalte</li>
</ol>
{{< /job >}}

Eine Aufgabenumgebung mit Unteraufgaben:

{{< job numbered="false" name="" title="" style="enum-arabic" >}}
  <li>Lorem ipsum dolor sit amet consectetur adipisicing elit. Nisi quaerat dolorem molestias quo earum corporis a consequuntur fuga, aliquid laboriosam. Iure in vitae corrupti hic est quam quod ratione sapiente.</li>
  <li>Lorem ipsum dolor sit amet consectetur adipisicing elit. Provident, porro accusantium esse aliquam molestias doloribus repudiandae quo quod libero fuga perspiciatis voluptates magnam non consequatur aliquid quidem! Atque, illum exercitationem?</li>
  <li>Lorem ipsum dolor, sit amet consectetur adipisicing elit. Maiores, fuga! Praesentium repellendus minima ad totam officiis unde suscipit quae accusamus vel in voluptatem voluptates maiores, explicabo reiciendis, consequuntur ducimus eos.</li>
{{< /job >}}

{{< job numbered="false" name="" title="" style="enum-alph" >}}
  <li>Lorem ipsum dolor sit amet consectetur adipisicing elit. Nisi quaerat dolorem molestias quo earum corporis a consequuntur fuga, aliquid laboriosam. Iure in vitae corrupti hic est quam quod ratione sapiente.</li>
  <li>Lorem ipsum dolor, sit amet consectetur adipisicing elit. Maiores, fuga! Praesentium repellendus minima ad totam officiis unde suscipit quae accusamus vel in voluptatem voluptates maiores, explicabo reiciendis, consequuntur ducimus eos.</li>
{{< /job >}}

Mehrere durchnummerierte Aufgaben (mit entsprechendem Counter):

{{< job name="" numbered="true" title="Einstiegsaufgabe" >}}
Test. Lorem ipsum dolor sit amet consectetur, adipisicing elit. Dicta nemo ipsa deserunt? Quos officia aperiam distinctio animi ducimus. Delectus doloremque deserunt laborum ipsam, repellendus perferendis fuga iusto molestias tenetur neque!
{{< /job >}}

{{< job numbered="true" name="*-Aufgabe" title="Sternchen-Aufgabe" >}}
Test. Lorem ipsum dolor sit amet consectetur, adipisicing elit. Dicta nemo ipsa deserunt? Quos officia aperiam distinctio animi ducimus. Delectus doloremque deserunt laborum ipsam, repellendus perferendis fuga iusto molestias tenetur neque!
{{< /job >}}

{{< job numbered="true" name="" title="" >}}
Test. Lorem ipsum dolor sit amet consectetur, adipisicing elit. Dicta nemo ipsa deserunt? Quos officia aperiam distinctio animi ducimus. Delectus doloremque deserunt laborum ipsam, repellendus perferendis fuga iusto molestias tenetur neque!
{{< /job >}}

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


{{< tabs "test" >}}
{{< tab "Aufgabe 1" >}}
Lorem ipsum dolor sit amet consectetur, adipisicing elit. Molestias sint id officiis possimus quos ullam sit, vel, cumque recusandae fugit unde veniam! Repudiandae doloremque praesentium dicta dignissimos maiores reiciendis iure.
{{< /tab >}}
{{< tab "Aufgabe 2" >}}
Molestias sint id officiis possimus quos ullam sit, vel, cumque recusandae fugit unde veniam! Repudiandae doloremque praesentium dicta dignissimos maiores reiciendis iure.
{{< /tab >}}
{{< tab "Aufgabe 3" >}}
Repudiandae doloremque praesentium dicta dignissimos maiores reiciendis iure.
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


### Notes & Quotes

> **Info:**  The note content.

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

{{< youtube 6MAzUT1YhWE >}}

### Instagram embed

{{< instagram CxOWiQNP2MO >}}

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
