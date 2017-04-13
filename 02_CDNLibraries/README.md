# 02_CDNLibraries

You don't have to use a local version of Vue in a project directory
in order to use Vue - you can simply source it from a CDN and
use it that way.

Simply run by firing up a static web server, for example with

>python -m SimpleHTTPServer

and browse to localhost:8000 (or whatever the default port of
you web browser is)

## Things to try

open the console and type 

> app.words

this will display 

> ['Hello', 'world!']

try typing 

> app.words = ['Goodbye', 'cruel', 'world']

and the list should dynamically update - this is the reactive data binding 
in Vue that give it so much power, and allows for a clean seperation of the
objects from the view.
