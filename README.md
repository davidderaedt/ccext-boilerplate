# CC Extension Boilerplate

Boilerplates for creating HTML based extensions for Adobe Creative Cloud applications.

Those are (mostly) complete rewrite of the template used by *Extension Builder 3*.

Two versions are available:

* *Basic*: only includes the minimum for extensions to work: an HTML file and the CSXS manifest, plus an empty css, `main.js` and `hostscript.jsx` *ExtendScript* files.


* *Standard*: adds to *Basic* what a typical extension will need, including *jquery* support, *CSInterface* for *ExtendScript* communication, CC app theme management, and basic sample code to get started.

###Which should I use?

If you're new to CC extension development, you should choose the standard one and study the code.

Once you're familiar with it, you'll probably want to use the Basic one and customize it to your need.


###How can I run the extension?

You can use command line tools to deploy it, or use ready to use editor plugins, such as the *CC Ext. builder* for *Brackets* or *Extension Builder 3* for Eclipse.

