---
layout: default
---
# Coding and Decoding Unicode Characters in Python
You can code and decode Unicode characters by using a simple script in Python.

## Prerequsites
You need to prepare Python environment on your machine or you can use online interpreter. Online interpreters are free, just google for it.

## Coding Unicode Characters
Provide a string in sentenceUtf.
```
sentenceUtf = 'Text to convert'
a = ""
for _c in sentenceUtf: a = a+ ('U+%04x' % ord(_c))
print (a)
```

## Decoding Unicode Characters
```
title = "U+0054U+0065U+0078U+0074U+0020U+0074U+006fU+0020U+0063U+006fU+006eU+0076U+0065U+0072U+0074"
utfTitle = title.encode('utf-8').decode('unicode-escape')
print(utfTitle)

```
