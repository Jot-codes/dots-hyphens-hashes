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
title = "\\u006f\\u0020\\u006d\\u0061\\u0074\\u006b\\u006f\\u002c\\u0020\\u006a\\u0061\\u006b\\u0020\\u006a\\u0061\\u0020\\u006e\\u0069\\u0065\\u006e\\u0061\\u0077\\u0069\\u0064\\u007a\\u0119\\u0020\\u0070\\u0072\\u006f\\u0067\\u0072\\u0061\\u006d\\u006f\\u0077\\u0061\\u006e\\u0069\\u0061\\u002c\\u0020\\u0074\\u0061\\u0020\\u0077\\u0065\\u0077\\u006e\\u0119\\u0074\\u0072\\u007a\\u006e\\u0061\\u0020\\u007a\\u0142\\u006f\\u015b\\u0107\\u0020\\u006a\\u0065\\u0073\\u0074\\u0020\\u0064\\u0061\\u006c\\u0065\\u006a\\u0020\\u0077\\u0065\\u0020\\u006d\\u006e\\u0069\\u0065"
utfTitle = title.encode('utf-8').decode('unicode-escape')
print(utfTitle)

```
