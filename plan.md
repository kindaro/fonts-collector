plan
----

0. Make a React list of links to css files that presumably contain @font-face s.
0. Make the list synchronize with head/link tags.
0. Link a css parser (I believe jscssp fits). Parse those css files linked and create a list of
   font faces available.
0. Create a text line for each of those font faces.
0. Allow a text input that modifies example text.
0. Enjoy!

parts
-----

- editable **"list of links"**
- editable **"sample text input line"** for user to enter example text
- css parsed **"list of font faces"**
- **head/link** tag group synchronized with **"list of links"** (asking for a "head" component)
- **body/samples** tag group synchronized by list with **"list of font faces"** and by content with **"sample text input line"**

