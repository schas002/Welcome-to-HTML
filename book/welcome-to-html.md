# Welcome to HTML

First, let me explain what is HTML.

HTML is a way of telling the computer what a webpage should look like. HTML is a map of what you see on the (computer) screen.

Now, let's see what HTML looks like.

## The simplest HTML web page

Here is the simplest HTML web page:

```html
<!DOCTYPE html>
<html>
  <head>
    <title></title>
  </head>
  <body>
  </body>
</html>
```

Looks strange, isn't it? The `<html>`, `<head>`, `<body>` etc. things are HTML **elements**. Most HTML elements have an opening tag (like the roof of a house) and a closing tag (like the floor of the house).

Opening tags look like this: `<html>`; and closing tags like this: `</html>`.

Note that the only difference between opening and closing tags is that the latter kind has a slash after their opening angle bracket.

Let's see what we have on the page.

`<!DOCTYPE html>` is a **document type declaration**. It is needed so that your browser knows how to read the page.

`<html>` is the opening tag for the HTML page. The `<html>` tag contains *everything* on the page.

`<head>` is the opening tag for the page **head** (like a human head). The head helps the browser with working with data.

`<title></title>` is the page **title**. It is needed so that the user knows what this page is about, but for a simple web page we skipped it.

`</head>` closes the page head. `<body>` opens the page **body** (like a human body), which contains what is shown on the page. But for a simple web page it contains nothing.

`</body>` closes the page body. Finally, `</html>` closes the HTML page and declares that nothing else is here.

## How do I make web pages?

To make web pages, you need a **browser** (with which you view the page) and a **plain text editor** (with which you edit it). You have both.

- On Windows, the browser is called ***Internet Explorer*** and the text editor ***Notepad***.
- On macOS, the browser is called ***Safari*** and the text editor ***TextEdit***. To set the latter to output plain text files (which we need), see the note on TextEdit and plain text below.
- On Linux, the browser and text editor vary per the distribution you installed. For Ubuntu, the browser is called ***Firefox*** and the text editor ***gedit***.

Now copy the simplest HTML web page in the text editor. Here it is again:

```html
<!DOCTYPE html>
<html>
  <head>
    <title></title>
  </head>
  <body>
  </body>
</html>
```

Save it somewhere where you can find it. The path to the place should not have spaces in it. For example, put it in `~/Documents/Welcome-to-HTML/simplest-web-page.html`. We need it later.

**Congraubbulations**! You are all set to make web pages.

{% em color="#f1ecba" %}
### A Note on TextEdit and Plain Text (macOS)

TextEdit is usually a Rich Text File (RTF) editor. This is not right, because HTML files are plain text files. You need to set it to plain text.

HOWTO set TextEdit to plain text:

1. Go to TextEdit - Preferences in the menu bar.
2. On the New Document tab, set the Format switch to "Plain text".

Changes will apply immediately, so all new TextEdit windows will be plain text.

### A Note on Choosing a Browser and Text Editor

There are many powerful programs dedicated to viewing and editing pages, or even both. Options like:

- [Notepad++](https://notepad-plus-plus.org/)
- [BBEdit](http://www.barebones.com/products/bbedit/)
- [Vim](http://www.vim.org/)
- [Firefox](https://www.mozilla.org/firefox/)
- [Chrome](https://www.google.com/chrome/), or even
- [KompoZer](http://www.kompozer.net/)

Options like these come to mind. But your distributors provide tools that are free, always available, and capable of handling the basics. By mastering these tools, they should be your first stop for editing web pages.
{% endem %}