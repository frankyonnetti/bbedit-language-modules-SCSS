## BBEdit syntax coloring for SCSS

This should allow for the syntax coloring and code block folding in BBEdit.

### Adding to BBEdit:

1. Save the SCSS.plist file to ~/Library/Application Support/BBEdit/Language Modules
2. Then add `scss` to the "custom extension mappings" in BBEdit preferences > languages.

**Note: if you're syncing your BBEdit preferences via dropbox the plist file goes here:**

~/Dropbox/Application Support/BBEdit/Language Modules

---

**FYI - quickly test changes to .pfile file in terminal**

$ plutil ~/Library/Application\ Support/BBEdit/Language\ Modules/SCSS.plist

**Bare Bones CLM documentation**

http://www.barebones.com/support/develop/clm.html
