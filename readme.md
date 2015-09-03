wkhtmltopdf-selfcontained
=========================

A Node.js wrapper for the [wkhtmltopdf](http://wkhtmltopdf.org/) command line tool.  As the name implies, 
it converts HTML documents to PDFs using WebKit.

This is a fork of
[Devon Govett's wkhtmltopdf package](https://www.npmjs.com/package/wkhtmltopdf). It
is identical, except that on 64-bit Linux it uses a binary which is included in
the package by default.
