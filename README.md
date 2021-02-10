# Alt readme

Installing this forked version of live preview provides the following extra functionality:

* each adoc render contains a new header
* the header is a temporary file in `/tmp/header.adoc`
* you create a script to populate that header.

. Install the extension as a unpacked extension.

.. Navigate to chrome://extensions/

.. Click *Load unpacked*.

.. Choose the `app` directory from this.

. Test in VS Code

.. Load this repo in VS Code.

.. Run `bin/process.sh contrib/samples/main.adoc`

You should see the rendered content of main.adoc with a header showing links to the other files.


