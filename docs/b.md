# JSON

_JavaScript Object Notation_ (JSON) is standardized by [RFC8259](https://datatracker.ietf.org/doc/html/rfc8259) and other [standards](https://ecma-international.org/publications-and-standards/standards/ecma-404/). It was intended as a "text-based, language-independent data interchange format", to be used by web applications to add state to transactions. Although it was originally derived from JavaScript, it is now language-independent and is supported by virtually every programming language.

Douglas Crockford is credited as the originator and I love the [fuss](https://lwn.net/Articles/707510/) about his original license. Maybe its the again rebel in me, but I so want to add that to all my projects!

Fundamentally, a JSON object is a collection of key value pairs, enclosed in curly braces. 

Each _key-value pair_ has a _name_ followed by a _colon_ and a _value_ and each pair are separated by a comma.

A value may be an _array_, this is denoted by square brackets.


For example

```json
{
    "first_name":"John",
    "surname" : "ORaw",
    "professions" : ["lecturer", "archaeologist", "rocket scientist"]
}
```

Once again, I will point you to the W3Schools introduction to [JSON](https://www.w3schools.com/jS/js_json.asp).