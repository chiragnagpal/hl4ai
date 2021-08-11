# Exercise 3: Swahilli Verbs

LEXICAL FORM | SURFACE FORM | ENGLISH GLOSS
-------------|--------------|--------------
| `1SgS+Perf+3PlO+V+piga` | `nimewapiga` | I have beaten them  |
| `3PlS+Pres+1SgO+V+piga` | `wananipiga` | they are beating me  |
| `3PlS+Perf+1SgO+V+sumbua` | `wamenisumbua` | they have annoyed me |
| `2SgS+Perf+1PlO+V+piga` | `umetupiga` | you have beaten us  |
| `1PlS+Past+3PlO+V+piga` | `tʰuliwapiga` | we beat them | 
| `1SgS+Pres+3SgO+V+lipa` | `ninamlipa` | I am paying him |
| `3SgS+Fut+1SgO+V+lipa`    | `atanilipa`   | they will pay me|
| `2SgS+Fut+3PlO+V+piga`    | `utawapiga`   | you will beat them|
| `3PlS+Past+2SgO+V+penda`  | `walikupenda` | they liked you|
| `1SgS+Perf+3SgO+V+sumbua` | `nimemsumbua` | I have annoyed him|
|	  |  | | 

## How to run

Surface form to Lexical Form:
```console
$ foma -l swahilli.xsft -e "apply up"
```

Lexical form to Surface Form:
```console
$ foma -l swahilli.xsft -e "apply down"
```