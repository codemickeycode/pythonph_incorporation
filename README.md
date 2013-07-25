pythonph_incorporation
======================

Stuff prepared for the incorporation of PythonPH

Essentials:
- Mission Vision
- Articles of Incorporation
- By-laws (repo for by-laws can be found here http://bb.ap.robillo.name/pythonph_inc)

Reference Materials:
- Frequently Asked Questions and Links used for Reference

Reference Doccuments:
(reference_docs/ - placed all the gov't reference docs we used in this directory.) Contains the ffg.:
- Philippine Corporation Code
- Revised Code
- SEC's Articles of Incorporation and By-laws Template


Clone this repo and install Sphinx
```
$ git clone https://github.com/codemickeycode/pythonph_incorporation.git
$ cd pythonph_incorporation
$ sudo pip install sphinx
```


To convert .rst to to ODT, HTML etc:
```
RST to ODT
$ rst2odt.py <input file> <output file>

Example:
$ rst2odt.py articles.rst articles.odt

RST to HTML
$ rst2html.py <input file> <output file>

Example:
$ rst2html.py articles.rst articles.html

etc.
```

