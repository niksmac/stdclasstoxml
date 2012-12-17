stdclasstoxml
=============

PHP Class for converting XML to Object and Object to XML

Information
===========
Conversion of XML string to PHP object is pretty simple. 
You just need to call simplexml_load_string() function (available in PHP 5+) and need to pass your XML string. 
This will return the object which you can use. 
The only requirement is your XML string need to be well-formed XML string otherwise PHP will through E_WARNING error message.
We need to recursively parse the Object and need to create XML tags for object attributes (keys). I’m using XmlWriter class for that purpose. 
