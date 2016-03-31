## MD-Shell
#### What the heck?

A very basic shell, written in html and css only, to be used together with the [Markdown Here](http://markdown-here.com/) browser extension as a simple [Markdown](https://github.com/adam-p/markdown-here/wiki/Markdown-Here-Cheatsheet) editor.
Released 2016-04-01 under the WTFPL.

#### Dependencies

- A web browser supported by the 'Markdown Here' extension, which boils down to *Gecko* and *Chromium* based browsers.
- The 'Markdown Here' extension must be installed in your browser.

#### Usage

- Write your markdown stuff (or paste from a text editor), <right click>[Markdown Toggle] to render, <right click>[Markdown Toggle] again to unrender (or use Ctrl+Alt+M).
- You can print directly after rendering: Only your content will be printed.
- You can save to PDF (or other formats) by printing to a file. The method depends on your OS and is beyond the scope of this manual.
- You can save your document (Ctrl+S) to a new html file, and edit it later, if you save it while rendered. 'Markdown Here' takes care of saving your source code inside the file. Just unrender to edit.
- If you get tired of seeing all this, use this version instead :

```html
<!DOCTYPE html>
<html>
  <head>
    <title>MD Shell</title>
  </head>
  <body>
    <div contenteditable="true" style="min-height:200px;" title="Use with 'Markdown Here' extension!"></div>
  </body>
</html>
```
