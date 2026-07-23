# XML

_EXtensible Markup Language_ (XML) has been around since c. 1996 and was a common format for storing data in both a human readable and machine readable format. It is a free, open standard of the World Wide Web Consortium specifically for exchanging data over the Internet and between heterogenous systems.

- [XML1.0](https://www.w3.org/TR/2008/REC-xml-20081126/) last modified 2013.
- [XML1.1](https://www.w3.org/TR/2006/REC-xml11-20060816/) from 2006.

An XML document consists of;

1. A declaration of XML version
2. A root element <notification> within which all other elements must be nested
3. Child elements (to, from, content, etc)
4. End of root element

All elements must have a closing tag, normally marked as /. 

Every element can be nested, and this nesting provides unique paths to elements, some of which may otherwise have the same name. This gives each element namespace isolation. 

Attributes can be contained in the start tag of an element and must be contained in quotation marks, for example <note date=”18MAR18”>. Generally I prefer to use elements rather than attributes.

````
<?xml version="1.0" encoding="UTF-8"?>
<notification>
    <date>2026-JUL-22</date>
    <to>Class</to>
    <from>JOR</from>
    <content>Pay attention to the layout, tags, etc.</content>
</notification>
````

To gain some basic familiarity, review this [course](https://www.w3schools.com/xml/default.asp) on W3 Schools.

I find XML a bit hard to read and it is a bit verbose. There are more economical ways to transfer data.
