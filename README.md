# solid

This repo will collect all basic BuzzFeed styling CSS.

It is implemented in SASS/SCSS.

The harp webserver is used to display and develop the styling locally:

<http://harpjs.com/>

> The static web server with built-in preprocessing.

> Harp serves Jade, Markdown, EJS, CoffeeScript, Sass, LESS and Stylus as HTML, CSS & JavaScript—no configuration necessary.


## Dev

Install node dependencies (including **harp** and **sass**):

    npm install

Run the harp server locally:

    ./node_modules/.bin/harp server

Open the site in your web browser:

<http://localhost:9000/>


## Code Snippets

To add code snippets/highlighted syntax to pages in solid, wrap your html/css inside <%= ' ' %> 

***Examples***

To add documentation on an h2 or a p with a class of .type-2 in html:
<pre> 
    <code class="html"> <%= '<h2> Yale Will Offer Its First Online Degree </h2>' %> <br /> <%= '<p class="type-2"> Yale Will Offer Its First Online Degree </p>' %> 
    </code>
</pre>

To add <code> documentation on the $type-2 variable in css:
<pre> 
    <code class="css"> <%= '.class { font-size: $type-2; }' %> </code>
</pre>


