# Regex - Character Class

Regex is short for Regular Expression. This is a term that describes a sequence of characters that specifies a search pattern in text. What this means is that it is a pattern that matches other strings or pieces of string. 

For example, gr(a|e)y means contains gray or grey. 

Or,

go+gle contains gogle, google, gooogle, goooogle, etc.
\d contains [0, 1, 2, 3, 4, 5, 6, 7, 8, 9]

There are many coding languages that allow us to dfeine regex in order to help us manipulate and specify our searches.

They allow us to: 
- validate that a piece of text or a portion of that text matches some pattern that we need 
- find fragments of some text that match a pattern that we need
- extract fragements of some text
- replace fragements of some text with another text

## Summary

Character classes allow us to find and isolate specific characters that we need using different notations. This is a very simple way to find values.

## Table of Contents

- [Character Classes](#character-classes)
- [Author](#author)

## Character Classes

Using brackets, we can define which specific character or characters we need. 

```
[a] indicates that we are only looking for the character a
[abc] indicates that we are looking for a, b, or c
[^] indicates we are looking for everything except what follows the ^
[-] indicates through; for example (a-z) would indicate all lower case letters
[[]] indicates unions; for example [a-d[n-s]] would indicate (a, b, c, d, n, o, p, q, r, s)
[&&[]] indicates intersection; for example [a-c&&[bcd]] would indicate (b, c) because those are the only ones that match both criteria
[&&[^]] indicates subtraction; for example [a-z&&[^b-t]] would indicate (a, u, v, w, x, y, z) because we are subtracting out b-t

```

## Author

This tutorial was created by Brian Wang, an aspiring developer who was a former teacher. He is currently working toward creating programs that can help both teachers and students in the classroom to develop better learning environments. Please reach out to his [GitHub](https://www.github.com/wangbrian26) if you would like to learn more about his work.

