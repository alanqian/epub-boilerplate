# Epub Boilerplate

Purpose of this project creating a general boilerplate for EPUB creation. 
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
that epubs, using this css will generate clean mobi's with kindlegen.
The other platforms of significance are followed:
 * Kindle (for converting to .mobi)
 * Nook
 * iBooks
 * Adobe Digital Edition (ADE)
 * FBReader
 * Kobo
 * Apabi Reader
 * Stanza

Unfortunately, cheap and older readers don't support newer epub3 standard,
especially FBReader or Adobe Digital Edition based devices. Some reader programs
are very finicky about CSS stylesheets and will ignore the whole sheet if there 
is an error or such property that unknown by the reader. 

For that we create a legacy EPUB2 and a newer EPUB3 version of this starter kit.
EPUB2 version created for legacy readers, tested on Adobe Digital Edition and 
FBReader based reader, but keeping compatibility with the original Epub CSS 
Starter Kit by Matt Harrison. EPUB3 version is for newer, smarter devices,
mainly for the mentioned three platforms, Kindle, Nook and iBooks.

## Resources
 * Calibre Edit E-book - https://manual.calibre-ebook.com/edit.html
 * Sigil - https://sigil-ebook.com/
 * Paul Salvette: EPUB and KindleGen Tutorial - http://www.paulsalvette.com/2011/08/epub-and-kindlegen-tutorial-ebook.html
 * BB eBooks: EPUB and KindleGen Tutorial - http://bbebooksthailand.com/bb-epub-kindlegen-tutorial.html
 * MobileRead Wiki: Standard CSS for Epub files - http://wiki.mobileread.com/wiki/Standard_CSS_for_Epub_Files
 * 99problems: A globa list of e-reader rendering bugs - https://github.com/dvschultz/99problems
