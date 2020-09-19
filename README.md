# alchengs-website

View at https://leoncheng57.github.io/achengs-website/

# Purpose

Built for Anthony Cheng's personal use. Anthony was losing access to his WordPress-created website hosted at http://alcheng.scripts.mit.edu/ and wanted a way to port it over to a different host. The new version should be 
- able to be hosted for free (preferably static)
- easy to edit style or content in (preferably in html or css)
- look exactly the same as the old version

I heard about this and wanted to test my website-from-scratch making abilities. So I set out to coding it up and in less than 2 days, this was created. I enjoyed the process and especially appreciated learning more about the magical precomputability of *Sass* (for CSS) and *Pug* (for HTML). Building scalable and well-designed static websites is made so much easier with these free tools.

- [Sass](https://sass-lang.com/guide)
- [Pug](https://pugjs.org/api/getting-started.html)

### VSCode extensions for live compiling
- **Live Pug Compiler** by jaheenafsarsyed 
    - https://marketplace.visualstudio.com/items?itemName=jaheenafsarsyed.live-pug-compiler
    - note: Unclear how reliable this is. If html edits seem unresponsive, then stop and start the vscode extension again.
- **Live Sass Compiler** by Ritwick Dey 
    - https://marketplace.visualstudio.com/items?itemName=ritwickdey.live-sass

# Editing (@[Anthony](https://github.com/acheng98))

## Where you should edit
Any .scss or .pug files. You can write css directly in scss or learn scss through a simple tutorial. For Pug, you can use a html2pug convertor or learn the simple syntax of Pug.

## Where you should NOT edit
- *.html
- styles/*.css

You can edit css/html files if absolutely necessary but if you ever edit in the scss or pug files later on, they will overwrite these files.

## Advanced

If you want to reorganize the structure, you can change the settings for where Pug files or Sass files are compiled into. Currently, Pug's compiled html files are left in the same folder as the source files. The same holds true for Sass files. 

`_base.pug` links to `style.css` through the line `link(rel="stylesheet" href="styles/style.css")`.
