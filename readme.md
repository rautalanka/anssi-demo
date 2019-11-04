Install npm if you dont have it

Run a server to test the pages

    npx serve
    
Open localhost:5000 to view the site.


## ideas

### index

1. split index.html and $PACKAGE.html (in this case, python.html) into template partials.

2. header.template would contain lines 1 to 15 from index.html

3. then add <li><a href="$PACKAGE">$PACKAGE</a></li> for each item

4. then add footer.template to index.html which closes the ul, main, body and html tags.

### packages

1. generate new $PACKAGE.html for each package to /package/$PACKAGE.html

2. build $PACKAGE.html with template, then enumerate dependencies and dependendants and add closing footer template into a single html file.
