# Instruction for MarkDown


## Head
---

Use "#" to make text as Head1
Use "##" to make text as Head2


## Text formating
---

- Set * or _ before and after the word to italic *text*

- Set ** or __ (this is two _ _ symbols) before and after the word to bolt **text**

- You can mix two method and use ones together: _How **are** you?_

-  Set ~~ before and after the word to crossed ~~text~~


## Lists
---

Set "-" at the begining of the line to make list without numbers.

Example:
- one
- two
- three

Or set "+" at the begining of the line.

Example:
+ one
+ two
+ three

Or set "- -" at the begining of the line to set second step lists.

Example:

- - one
- - two
- - three

Set "1." in line's origin to make numbered list

Example:
1. one
2. two
3. three

Remember that you can combine it whith tabulation.

Example:
- one
    - two
        - three



## Using images
---

To input some images into text, type this code: "![description](file name "pop up")":

![im001.jpg](im001.jpg "GeekBrains logo")


## Links

To mark some text as links use this code:
simple text [name of link](http link "pop up for link"):

Example:

Text [GeekBrains](https://gb.ru/ "GeekBrains")

There it's possible to use just only (http link) without name of link or without pop up message at link.

Find alternative method set link:

[name][]

[name]:http link

Example:

[GeekBrains home][]

[GeekBrains courses][]

[GeekBrains home]:https://gb.ru/

[GeekBrains courses]:https://gb.ru/courses/all


## Quotation
---

It's easy:

> quotation

or
>>> quotation


## Code
---

Type like: input ` (it is left-side key with symbol ~) before and after the code.

Example:

`print("Hello, World!")`

Or input three symbols ``` for code (also before and after):

```
print("Hello, World!")
```
## Sheild pritection
---

Use \ before each markdown formating symbol to stop markdown script.
Get it, there markdown formating isn't working:

\*word\*


## Tables
---

For tabs input | -- | This will be one column of the table. Type it one under the other.

Example:

| word|word|
| --|--|
|tipe1|tipe2|



## And in conclusion
---

**Take care of yourself!**

.

.

.




# From GB.RU:


## Оформление текста


**жирный**
__жирный__
*курсив*
_курсив_
~~перечёркнутый текст~~


## Списки

* Generic list item
* Generic list item
* Generic list item
- Generic list item
- Generic list item
- Generic list item
1. Numbered list item
2. Numbered list item
3. Numbered list item

## Цитаты


> This is a quote.
> It can span multiple lines!
Код
`var example = "hello!";`

## Мультистрочный код:

```
var example = "hello!";
alert(example);
```

## Ссылки

[Title](https://gb.ru)