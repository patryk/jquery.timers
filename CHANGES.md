Version 1.2.1
-------------
05.06.2013 by Andrey Hihlovskiy (akhikhl)

Put plugin into document-ready call to improve integration with multiple jQuery 
instances (for example, when parts of the page are loaded via jQuery.load 
and their html includes jQuery.timers).
