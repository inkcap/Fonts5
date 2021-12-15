Icons and Fonts as Icons with no deployed JavaScript.

JavaScript can sometimes introduce security vulnerabilities. 
This project is just CSS and icons. Practically speaking, CSS and icons do not have security issues.


## Usage
```
<link href="assets/Fonts5/css/fonts5.min.css" rel="stylesheet" type="text/css"/>
<link href="assets/Fonts5/css/solid.min.css" rel="stylesheet" type="text/css"/>
```

# SVG vs WebFonts
For SVG, use svg sprites. This requires a syntax change from the traditional &lt; i &gt; usage.
```
<a href="./somepage.html">
   <svg><use xlink:href="/public/css/sprites.svg#pencil"></use></svg>
</a>
```
When using SVG with stacked icons, the default CSS doesn't always line up. Be prepared to make some css adjustemnts.
If this is an issue, then use the traditional web fonts.
   
If your application only uses a few fonts, I highly recomend hand crafting your own fonts5 sprites.svg file.
Doing so will significantly decrease the download size.
Look at the existing /sprites/solid.svg file for more information.
  

## License
This project is a fork of FontAwesome that removes the JavaScript and is just CSS, Fonts, and SVG's. 

FontAwesome / Fonts5 Free is free, open source, and GPL friendly. You can use it for
commercial projects, open source projects, or really almost whatever you want.

- Icons — CC BY 4.0 License
  - In the Fonts5 Free download, the CC BY 4.0 license applies to all icons packaged as .svg and .js files types.
- Fonts — SIL OFL 1.1 License
  - In the Fonts5 Free download, the SIL OLF license applies to all icons packaged as web and desktop font files.
- Code — MIT License
  - In the Fonts5 Free download, the MIT license applies to all non-font and non-icon files.

Attribution is required by MIT, SIL OLF, and CC BY licenses. Downloaded Font
Awesome Free files already contain embedded comments with sufficient
attribution, so you shouldn't need to do anything additional when using these
files normally.


