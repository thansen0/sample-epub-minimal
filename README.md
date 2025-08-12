Minimal Ebook
==============

This is a minimal epub v3 ebook file.  It contains no cover, and only has two chapters and a copyright.  The purpose of this repo is for people to get up and running with a super simple book, which they may freely add to and modify.

For those that just want to work with and build this ebook, you should be able to download it, compress the folder to a zip, and then rename it using the extension .epub.  That will produce a readable ebook.

```bash
git clone git@github.com:thansen0/sample-epub-minimal.git
cd sample-epub-minimal/minimal/
zip -X0 ../minimal.epub mimetype
zip -rX9 ../minimal.epub * -x mimetype
```

The key to the file structure inside the zip (.epub) file structure is the `mimetype` file. It should remain uncompressed for best compatibility with readers (hence the -X0 flag), while the rest of the book can be compressed normally (with the -rX9 flag).

The .epub file contained in the repo is the epub created from the folder.

You may read more about .epub's at their official site, http://idpf.org/epub, or at their official and much more complex samples, https://github.com/IDPF/epub3-samples.

Lastly you may visit my site for building .epub files here https://thansen0.github.io/Building-an-epub-file/

### Editing

If you use this epub template, be sure to edit `minimal/OEBPS/content.opf`to set your name as author and title.

### LICENSE

This is released into the public domain with the Unlicense License. That means you do not have to cite where you got the template from, and you may place it under your own license as you see fit.
