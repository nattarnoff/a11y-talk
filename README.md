# Rapid Prototyping Toolkit

I got bored starting from scratch every time I built something new, so I compiled this prototyping toolkit. Its based on Bermon Painter's Middleman toolkit, with a few adjustments of my own based on the way I do things. 

It uses Middleman, Slim, and Sass, so make sure you have those running.

##To use

Make sure you have Ruby running on your machine. We'll need it for the middleman and sass. 

I have a .rvmrc file included to use Ruby 1.9.3. You'll have to remove/modify this if you want to use something other than RVM or Ruby 1.9.3. From my experience, Middleman won't work on anything lower.

Now do
````bundle install````

This will install the required gems including Middleman, Sass and Slim.

````bundle exec middleman````

This will launch a dev server at localhost:4567

To make a new page, create it in source at <PAGENAME>.html.slim (or .markdown if it's only copy) and then you can visit the page at localhost:4567/<PAGENAME>.