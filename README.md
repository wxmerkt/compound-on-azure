compound-on-azure
=================

Empty CompoundJS webapp to document changes necessary to get the framework running on Windows Azure.

Solution List
=============

  1) Add web.config file to your repo [You might want to change the debug parameters etc.]
  2) Change package.json to enable Azure to correctly identify the Node.js version
  3) Change .gitignore to include the folder node_modules/ as Azure cannot find three required modules via NPM (ejs-ext, seedjs, stylus)




Error List
==========
After applying above solution steps, one runs into the following persistent issues:

  - Routing doesn't work properly on Azure. Actually, it doesn't work at all.
