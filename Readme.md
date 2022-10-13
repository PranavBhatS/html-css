

 <!DOCTYPE html> --> purpose is to prevent browser from switching into "quirk-mode" when rendering document.
---------------->

<html lang="fr"> - it is used to  determine the language of the text used on the webpage. it also help to change the language on webpage according to browser settings. (html & css ಗೆ ಸುಸ್ವಾಗತ)

using this we can change the css styling according to languages.

Google uses the hreflang tag to determine the location & lang of content.
---------------->

<head> - The head element represents a collection of metadata for the Document.
---------------->

<meta charset="UTF-8">  - Unicode Transformation Format 8Bits
inCludes pretty much any charector from any human language
<?xml version="1.0" encoding="UTF-8"?>
------------>


<script> 
With the async, the browser downloads JS files asynchronously while parsing HTML but as soon as the download is finished it stops parsing HTML and executes JavaScript. With the defer, the browser downloads JS files asynchronously while parsing HTML but only executes them when HTML parsing completes.

None - html parsing=> js downloading => js executing => html parsing
Async - html parsing         => js executing => html parsing (not maitain the order)
               js downloading

defer -  html parsing        => js executing
               js downloading
---->






