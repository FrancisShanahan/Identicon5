/*
Plugin: Identicon5 v1.0.0

Author: http://FrancisShanahan.com
Test Page: http://francisshanahan.com/identicon5/test.html
Project Description: http://francisshanahan.com/index.php/identicon5

Identicon5 draws identicons using HTML5 Canvas instead of the Gravatar image link. 
If Canvas is not supported, defaults to the standard gravatar link. 

Attribution: Based off the PHP implementation of Don Park's original identicon code for visual representation of MD5 hash values.
Reference: http://sourceforge.net/projects/identicons/

Usage: 
Place Md5 hash values inside a list like so: <ol><li>071e3f61671e790fc492b583a01ae22b</li></ol>
call $('li').identicon5();

Options: {
rotate:true/false  =  whether or not to rotate each tile in place for greater variation of the images
size: int value = size of the images, default is 32px and identicons are always square. 
}

Usage with options: $('li').identicon5({rotate:true, size:100});

*/