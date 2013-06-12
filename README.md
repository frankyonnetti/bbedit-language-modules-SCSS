## BBEdit syntax coloring for SCSS

This should allow for the syntax coloring and code block folding in BBEdit.

### Adding to BBEdit:

1. Save the SCSS.plist file to ~/Library/Application Support/BBEdit/Language Modules
2. Then add `scss` to the "custom extension mappings" in BBEdit preferences > languages.

---

### Quickly test changes to .pfile file in terminal

$ plutil ~/Library/Application\ Support/BBEdit/Language\ Modules/SCSS.plist
