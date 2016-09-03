# Epub Boilerplate

Purpose of this project creating a general boilerplate for epub2-3 creation. 
Unfortunately every main ebook-reader platform has it's own vendor-specific way
to displaying epub-files. 

Creating epubs that work in multiple readers can be painful, like debugging web 
problems back in the glory days of ie6. Only this time there is no firebug.

There are some boilerplate projects for giving a good starting point for 
cross-platform epub-file creation. Many of them inspired by this project:
 * Epub CSS Starter Kit by Matt Harrison - https://github.com/mattharrison/epub-css-starter-kit
 * Epub CSS Starter Kit fork by Christian Tietze - https://github.com/DivineDominion/epub-css-starter-kit
 * Epub Boilerplate by Javier Arce - https://github.com/javierarce/epub-boilerplate

## What platform is the focus of this effort?
As Matt Harrison wrote, oddly enough, the .mobi format for Kindle, is the least 
common denominator that we want to get working. Given that it has 70% of the 
market, it makes sense to put the effort there. Every effort has been made so 
that epubs using this css will generate clean mobi's with kindlegen.
The other platforms of significance are nook and ibooks, in that order, finally
other platforms.
