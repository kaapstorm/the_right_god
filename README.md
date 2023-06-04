The Right God
=============

by Norman Hooper

![Quantum decoherence](src/img/quantum_decoherence.jpg)
_Credit: CC0 Public Domain_

<a rel="license" href="http://creativecommons.org/licenses/by-nc-sa/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by-nc-sa/4.0/88x31.png" /></a><br /><span xmlns:dct="http://purl.org/dc/terms/" href="http://purl.org/dc/dcmitype/Text" property="dct:title" rel="dct:type">The Right God</span> by <a xmlns:cc="http://creativecommons.org/ns#" href="https://github.com/kaapstorm/the_right_god" property="cc:attributionName" rel="cc:attributionURL">Norman Hooper</a> is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by-nc-sa/4.0/">Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License</a>.


How to make a document
----------------------

You can turn these files into an ePub document, a single-page HTML document, or HTML files with one page per chapter.

The following instructions are for Linux, and assume that you have Git and Python installed.

1. Clone this repository locally.

2. Create and activate a Python virtual environment.
   ```
   $ python3 -m venv venv
   $ source venv/bin/activate
   ```

3. Install requirements.
   ```
   $ pip install -r requirements.txt
   ```

4. You are now ready to build your document.

   a. For ePub:
      ```
      $ sphinx-build -b epub src _build/epub
      ```

      Your ePub will be saved as
      `_build/epub/TheRightGod.epub`.

   b. For single-page HTML:
      ```
      $ sphinx-build -b singlehtml src _build/singlehtml
      ```

      To read, open `_build/singlehtml/index.html` in your browser.

   c. For page-per-chapter HTML:
      ```
      $ sphinx-build -b html src _build/html
      ```

      To read, open `_build/html/index.html` in your browser.
