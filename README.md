# Markdown to EPUB template

Use this starter template to create an EPUB ebook using Markdown files.

## Chapter files

Ensure there's a blank line at the end of each chapter. Otherwise, the next chapter will "run into" the previous chapter.

## Cover image

1600 x 2560 JPG or TIFF

## Building the EPUB

pandoc -o output.epub metadata.yaml contents/*.md --table-of-contents (--toc-depth={1-6})
