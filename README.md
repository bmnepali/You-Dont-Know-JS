# You Don't Know JS (book series)

This is a series of books diving deep into the core mechanisms of the JavaScript language. The first edition of the series is now complete. It is written by Kyle Simpson and published in source code in his [github repo](https://github.com/getify/You-Dont-Know-JS). As I wanted to read it on the go, I added some scripts to create `ePub` books from it.

## Titles

* <img src="up %26 going/cover.jpg" width="75"> **Up & Going** [as ePub](https://github.com/tillg/You-Dont-Know-JS/raw/master/up%20%26%20going/build/epub/YDKJS-UpNgoing.epub)
* <img src="scope %26 closures/cover.jpg" width="75"> **Scope & Closures** [as ePub](https://github.com/tillg/You-Dont-Know-JS/raw/master/scope%20%26%20closures/build/epub/YDKJS-ScopeAndClosures.epub)
* <img src="this %26 object prototypes/cover.jpg" width="75"> **this & Object Prototypes** [as ePub](https://github.com/tillg/You-Dont-Know-JS/raw/master/this%20%26%20object%20prototypes/build/epub/YDKJS-ThisAndObjectPrototypes.epub)
*  <img src="types %26 grammar/cover.jpg" width="75"> **Types & Grammar** [as ePub](https://github.com/tillg/You-Dont-Know-JS/raw/master/types%20%26%20grammar/build/epub/YDKJS-ScopeAndClosures.epub)
* <img src="async %26 performance/cover.jpg" width="75"> **Async & Performance** [as ePub](https://github.com/tillg/You-Dont-Know-JS/raw/master/async%20%26%20performance/build/epub/YDKJS-AsyncAndPerformance.epub)
* <img src="es6 %26 beyond/cover.jpg" width="75"> **ES6 & Beyond** [as ePub](https://github.com/tillg/You-Dont-Know-JS/raw/master/es6%20%26%20beyond/build/epub/YDKJS-ES6andBeyond.epub)

## Installing and making the `epub`, `PDF` and `HTML` books

This copy of the [original Github repo](https://github.com/getify/You-Dont-Know-JS) has been modified: It contains scripts to build the books as `epub`, `PDF` and `HTML`. To generate those books:

1. If you have not already done so, install:
   
   * `git <http://git-scm.com/>`_
   * `make <http://www.gnu.org/software/make/>`_ (OS X users should install XCode
     and `download the command line tools
     <http://stackoverflow.com/questions/9329243/xcode-4-4-command-line-tools>`_.)
   * `pandoc <http://johnmacfarlane.net/pandoc>`_
   * `latex <http://www.latex-project.org/>`_ (OS X users should probably
     install `MacTex <http://tug.org/mactex/>`_.)


2. From the book directory (i.e. `./async & performance`), type ``make``.
   This generates three versions of the book in a ``build/`` directory.
