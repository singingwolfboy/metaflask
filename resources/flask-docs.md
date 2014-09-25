# Flask Documentation Builder

For the Flask project (and some other projects) there is a dedicated
documentation builder bot available.  It's currently installed on the
pocoo server and builds the documentation in regular intervals.

The way this generally works is by splitting documentation building into
two parts:

* the source of the documentation.  It lives in the repository of the
  project that is being built.  For instance the Flask repository has a
  `docs` folder which contains the Sphinx documentation.
* the builder repository.  It lives at pocoo/flask-docs and contains all
  the shared information between Flask projects for online documentation
  publishing.

For more information please refer to the shared documentation
repository:

* https://github.com/pocoo/flask-docs
