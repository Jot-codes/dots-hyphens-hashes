---
layout: default
---

# Coding and Decoding Unicode Characters in Python
You can code and decode Unicode characters by using a simple script in Python.

## Prerequsites
You need to prepare Python environment on your machine or you can use online interpreter. Online interpreters are free, just google them.

## Coding Unicode Characters
Provide a string, which you want to code to Unicode in sentenceUtf.
```
sentenceUtf = 'Text to convert'
a = ""
for _c in sentenceUtf: a = a+ ('U+%04x' % ord(_c))
print (a)
```
Output:
```
U+0054U+0065U+0078U+0074U+0020U+0074U+006fU+0020U+0063U+006fU+006eU+0076U+0065U+0072U+0074
```

## Decoding Unicode Characters
Provide Unicode characters, which you want to decode in sentenceUnicode.

```
sentenceUnicode = "U+0054U+0065U+0078U+0074U+0020U+0074U+006fU+0020U+0063U+006fU+006eU+0076U+0065U+0072U+0074"
newSentence = sentenceUnicode.replace('U+','\\u')

utfSentence = newSentence.encode('utf-8').decode('unicode-escape')
print(utfSentence)
```
Output:
```
Text to convert

```
