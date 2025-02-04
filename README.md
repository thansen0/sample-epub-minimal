Minimal Ebook
==============

This is a minimal epub v3 ebook file.  It contains no cover, and only has two chapters and a copyright at the end.  The purpose of this is so that people are able to compare their ebooks with this and hopefully more easily make their own ebooks.

For those that just want to work with and build this ebook to see how it works, you should be able to download it, compress the folder to a zip, and then rename it using the extension .epub.  That should produce a readable ebook.

```bash
git clone git@github.com:thansen0/sample-epub-minimal.git
cd sample-epub-minimal
zip -r minimal.epub minimal/
```

The .epub file contained in the repo is the epub created from the folder.

You may read more about .epub's at their official site, http://idpf.org/epub, or at their official and much more complex samples, https://github.com/IDPF/epub3-samples.

Lastly you may visit my site for building .epub files here https://thansen0.github.io/Building-an-epub-file/

### Editing

If you use this epub template, be sure to edit `minimal/OEBPS/content.opf`to set your name as author and title.

### LICENSE

This is released into the public domain with the Unlicense License. That means you do not have to cite where you got the template from, and you may place it under your own license as you see fit.
