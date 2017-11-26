# jsLibrary
Repository for javascript collection made by Alsve.

LICENSE : BSD License v3

## terbilang.js
Purpose of this program is to produce human readable string from float.

#### Example :
A float of 1000 would produce string "One thousand". But currently, the program were made in only Bahasa. You need to alter some of the parameter like the array of string to your language to suit your need.

#### Usage
Include the javascript file with script tag and insert it wherever you need. The js only need vanila javascript library and only take two global variable name (i.e. _\_Terbilang_ and _Terbilang_).

```javascript 
Terbilang.apa(float) // <fn, string> to produce full string
Terbilang.format(int) // <fn, string> to produce string with delimiter according to Terbilang.LOCALE.
Terbilang.koma(float) // <fn, string> to produce human readable decimal string.
Terbilang.PRESISI_DESIMAL // <integer> (default to 2) to set Decimal precision.
Terbilang.LOCALE // <locale string> 'en' for delimiter thousand with ',' and decimal with '.'
                 //                 'id' for delimiter decimal  with '.' and decimal with ','
```
[Try it yourself here.](https://jsbin.com/qovava/4/edit?html,output)
