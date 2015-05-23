Markdown Converter
==================

How to use
----------

1. In **terminal** navigate to folder markdown-to-html-converter/bin and run ./watch.sh
2. Edit text.md file. Once you save it, _whenchanged_ script will automatically detect it and run _Markdown.pl_ script to convert the text to HTML.
3. The converted text will be available under the **formatted.html** file.
4. If you wish, you can preview your text by inserting this folder in your PHP server folder - the index.php will generate the output.

Acknowledgement
---------------

This is a humble converter that just mixes various different projects:

* [Markdown converter](http://daringfireball.net/projects/markdown/) by John Gruber
* [When changed](https://github.com/joh/when-changed) python script by joh
* [Bootstrap](http://getbootstrap.com/) css framework


Requirements
-------------

* Perl
* Python
* (optionally) PHP server (Apache / nginx)


License
--------

Because my own input in this project is small, my own work is [unlicensed](http://unlicense.org/.)