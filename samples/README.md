# How this samples were generated

## Map
1) Open MapStore 2 and select the wanted tools 
2) Save as html using chrome
3) Remove <script> tag with mapstore2.js
4) Remove unuseful noscript tag (regex to find: `<noscript\b[^>]*>(.*?)</noscript>\n` replaced with empty string)
5) Remove data-reactid attributes (regex: `data\-reactid=\"([^"]*)\"` replaced with empty string)

## Sample for bootstrap themes
 
We can use this service to generate bootstrap layout with base tools: 
http://www.layoutit.com/build 

