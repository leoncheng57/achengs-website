# alchengs-website

View at https://leoncheng57.github.io/alchengs-website/

# Purpose

Built for Anthony Cheng's personal use. Anthony was losing access to his WordPress-created website hosted at http://alcheng.scripts.mit.edu/ and wanted a way to port it over to a different host. The new version should be 
- able to be hosted for free (preferably static)
- easy to edit style or content in (preferably in html or css)
- look exactly the same as the old version

I was heard about this and wanted to test my abilities in making a website from scratch. So I set out to coding it up and in less than 2 days, this was created. I enjoyed the process and especially appreciated learning more about the magical precomputabiilty of Sass (for CSS) and Pug (for HTML). Building scalable and well-designed static websites is made so much easier with these free tools.

# Languages
- [Sass](https://sass-lang.com/guide)
- [Pug](https://pugjs.org/api/getting-started.html)

# VSCode extensions used
- **Live Pug Compiler** by jaheenafsarsyed 
    - https://marketplace.visualstudio.com/items?itemName=jaheenafsarsyed.live-pug-compiler
    - note: Unclear how reliable this is. If html edits seem unresponsive, then stop and start the vscode extension again.
- **Live Sass Compiler** by Ritwick Dey 
    - https://marketplace.visualstudio.com/items?itemName=ritwickdey.live-sass


## Where you should edit
- styles/*.scss
- *.pug

## Where you should NOT edit
- *.html
- styles/*.css

You can edit these if absolutely necessary but if you ever edit in the scss or pug files later they will overwrite these files.
