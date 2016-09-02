Chrome Extension with Polymer

To manage Bookmarks

After App vs. Ext hesitation, I am going for an extention. An apps is not well suited to access Bookmarks.

Basic Extension template and install Polymer with bower.

Styling is not perfect yet, but should be sovled soon.

Had to install "crisper", which has to be used in conjonction with vulcanize
`sudo npm install -g crisper`
`vulcanize app.html --inline-script | crisper --html build.html -js build.js`
Actually, it is even easier to install `sudo npm install -g polybuild`
https://github.com/PolymerLabs/polybuild then, `polybuild app.html` will generate the required files.


This is the master branch, I made other branches with other tools, but nothing perfrect yet!
