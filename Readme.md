- scoot blog

# Scootfence

The entire site is written with Markdown. Which is a way of saying that you don't need to learn HTML, and instead get to write ina simpler way that can get rendered as HTML.

[Markdown Reference](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet)

### Short Examples

#### Bold

```markdown
**stuff between two asterisks is bold**
```

**stuff between two asterisks is bold**

#### Italic

```markdown
_stuff between single underscores is italic_
```

_stuff between single underscores is italic_

#### Links

```markdown
[text of the link](http://google.com)
```

[text of the link](http://google.com)

#### All of this site, including this readme

If you just check out any of the files that end with `.md` on this site and click "edit" you can toggle between the Preview mode and see how markdown turns in to formatted text.

## Background Image

The background image is set in the first few lines of [stylesheet.css](https://github.com/scootfence/scootfence.github.io/blob/master/stylesheet.css). As I write this that line looks like so:

```css
  background-image: url("http://farm8.staticflickr.com/7115/7882079648_d9315bd8c5_o.jpg");
```

To choose a different image, get the URL of that image, and replace the URL that is there already.

## The Stuff between three dashes at the top of most files

That stuff is special. It's needed, you'll see that there are things to the left of semicolons and things to the right. Hopefully it's kinda self explanatory. If you don't understand what a thing is, maybe just leave it alone. Maybe also send me an email or call me on the horn and ask.

## Work

The contents of **Work** is set in [work.md](https://github.com/scootfence/scootfence.github.io/blob/master/work.md). The template I created to make it easy to edit and yet also to separate items is such:

```markdown
### Title of Work
#### Subtitle of Work, year, place, etc

description of work, including images and video and text
```

This will put a bunch of empty space before this title, after whatever the last project was and will make the title Big. _Technical Note:_ The 3 # signs will be converted to an &lt;h3&gt; symbol.

## About

To edit the About page see [about.md](https://github.com/scootfence/scootfence.github.io/blob/master/about.md).

## Main Page

To edit the main page, when people first visit the site, check [index.md](https://github.com/scootfence/scootfence.github.io/blob/master/index.md).

Stick text in there, it'll be aligned with the navigation, no gray box. Lemme know if you want a gray box.

For instance, if you wanted to say that you've got an event happening soon you can do such as this:

```markdown
## Upcoming Show

This Friday at 8pm, at this place, map below

<iframe src="https://www.google.com/maps/embed?pb=!1m5!3m3!1m2!1s0x89c259617efce6a7%3A0x7cc1c33f7269781f!2sCAVE+home+of+LEIMAY%2C+Grand+Street%2C+Brooklyn%2C+NY!5e0!3m2!1sen!2sus!4v1386118757293" width="600" height="450" frameborder="0" style="border:0"></iframe>
```