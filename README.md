![SASS-CSS Bolierplate ](http://dl.dropbox.com/u/28188511/SASS-CSS%20Boilerplate/logo.png)

#Description
This boilerplate was created to be used alongside with HTML5 boilerplate. I use SASS with most of my projects
and I have converted the style.css file that is in HTML5 boilerplate to work with
SASS. This is the result of the migration from CSS to SASS CSS.

#Components
In the HTML5 boilerplate css file (style.css) contains great styling and for the purposes of this 
project, I haven't made much changes to it. However I have broken the file into 
the following components:

* normalize.scss: this file contains the normalize css for the boilerplate. Some components 
have been abstracted and placed in a file named "_normalize-mixins.scss".
* helper.scss: this file contains the helper classes (for example .ir and .hidden classes).
* padding-margin.scss: this file contains all the padding and margin classes to override individual padding and margins.
* style.scss: this file will contain all the site specific css information.
* partials: This folder contains all the partial SASS CSS files that will help in abstraction 
of css and data. All CSS (and SASS mixins) in these file cannot stand on their own and 
require the above SASS CSS files to use them. The naming convention for these files will 
begin with '_' (underscore) :
1.  _media-queries.scss: This file will contain all the media queries for the responsive 
design implementation.
2. _mixins.scss: this file contains all the mixins that have been created (and any future 
mixins).
3. _normalize-mixins.scss: this file contains the mixins for normalize.scss file.
4. _print.scss: this file contains all the CSS for the print version of the site.
5. _variables.scss: this file contains all the variables that is used throughout the SASS
CSS files.
* functions: this folder contains all the SASS functions created. Each function will be placed in 
their own file. For ease of use, create an overloaded function that will be easier to type. For example 
in this boilerplate I have created a function called "_responsive-font-size", I also have a function
named "rfs". The naming convention for these files will 
begin with '_' (underscore)
