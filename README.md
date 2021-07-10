# Markdown
#### study markdown from scratch

#### hi, today is a great day to explore the markdown

• [Headers](#111) • [Emphasis](#222) • [Lists](#333) • [Links](#444) 

• [Images](#555) • [Tables](#666) • [Blockquotes](#777) • [Horizontal Rule](#888)

• [ticks](#999) • [Additional texts](#1100) • [raised text](#1000)

<a id="111"></a>

## Example 1

#### let's start with the text

```
# text 1
## text 1
### text 1
#### text 1
##### text 1
###### text 1

Alt-H1
======

Alt-H2
------
```

# text 1
## text 1
### text 1
#### text 1
##### text 1
###### text 1

Alt-H1
======

Alt-H2
------

#### This is how example 1 works. The more grids, the less text. Okay, let's start with another test

---

<a id="888"></a>

## Example 2

```
---

Hyphens

***

Asterisks

___

Underscores
```

#### you can now make lines that will separate the text

--- 

Hyphens

***

Asterisks

___

Underscores

#### the more stars or dashes, nothing will change, at least 3 dashes or asterisks.

--- 

## Example 3

```
_hello world!_

# _hello world!_

## _hello world!_

### _hello world!_

#### _hello world!_

##### _hello world!_

###### _hello world!_
```
#### to make the text in italics, you need to add underscores on the sides

_hello world!_

# _hello world!_

## _hello world!_

### _hello world!_

#### _hello world!_

##### _hello world!_

###### _hello world!_

#### That's how everything works, you can make the text large with a slope and small

---

<a id="333"></a>

## Example 4

```

* `Hi there! How are you?`

`Hi there! How are you?`

* It's a test

* _this text is italic_

```

* `Hi there! How are you?`

#### more text can be done without a dot but in a frame

`Hi there! How are you?`

#### or text without a border but with a period

* It's a test

* _this text is italic_

#### Here is our text wrapped in a frame

---

<a id="1000"></a>

## Example 5

```
- I did not put an end

- I did not put an end
  - I did not put an end

- I did not put an end
  - I did not put an end
    - no, well, I did not put a square

```

#### You can also put a dash instead of a period and make a list

- that's what I put a risk

___

- that's what I put a risk
  - that's what I put a risk
    - no, well, I did not put a square

_____

<a id="999"></a>

## Example 6

```

- [x] desing
- [x] Markdown
- [ ] test text

```

- [x] desing
- [x] Markdown
- [ ] test text

#### We proceed to Example 7

---

<a id="777"></a>

## Example 7

```

> You can make columns
>> And you can have two arrows

> **this is a test text**

```

> You can make columns
>> And you can have two arrows

> **this is a test text**

#### We proceed to Example 8

***

<a id="1100"></a>

## Example 8

#### Now I will be a little difficult because there will be many commands

```
<details id="missing-code-coverage">
  <summary>Test Button</summary>

Hello it's a test

Hello world! pass: 7586

</details>



<details id="missing-code-coverage">
  <summary>Help Button</summary>

#### Hello it's a test button

#### _this is not an auxiliary button :)_

`Here, too, everything works and the tilt of the text and the point and frame`

* `so everything is fine here!`

</details>

```

<details id="missing-code-coverage">
  <summary>Test Button</summary>

Hello it's a test

Hello world! pass: 7586

</details>

<details id="missing-code-coverage">
  <summary>Help Button</summary>

#### Hello it's a test button

#### _this is not an auxiliary button :)_

`Here, too, everything works and the tilt of the text and the point and frame`

* `so everything is fine here!`

</details>

#### As you can see it turns out very nice and cool!

---
<a id="5932"></a>

## Example 9

```
<img src="https://img.shields.io/badge/Build-passed-green.svg" alt="passed"> 
<img src="https://img.shields.io/badge/Version-None-blue.svg" alt="version"> 
<img src="https://img.shields.io/badge/license-GNU-orange.svg" alt="license">

<img src="https://img.shields.io/badge/NAME-NAME-COLOR.svg" alt="NAME"> 


```

<img src="https://img.shields.io/badge/Build-passed-green.svg" alt="passed"> 
<img src="https://img.shields.io/badge/Version-None-blue.svg" alt="version"> 
<img src="https://img.shields.io/badge/license-GNU-orange.svg" alt="license">

#### you can still make badges to make it beautiful

-------

## Example 10

```
<a id="5932"></a>





[Options](#5932)



<a id="NUMBER"></a>
[NAME](#NUMBER)

```

#### click on the word UP

[UP](#5932)

#### Where you put <a id="NUMBER"> </a> it will move to this command, but the command will not be visible

#### I put next to the word Example 9

********

<a id="666"></a>

## Example 11

#### Colons can be used to align columns.

```
| Tables        | total         | list  |
| ------------- |:-------------:| -----:|
| Green         | 788 and 1207  | 122   |
| While         | 544 and 568   | 176   |
| Yellow        | 282 and 775   | 212   |


Markdown | Less | Pretty
--- | --- | ---
*Still* | `renders` | **nicely**
1 | 2 | 3
```

| Tables        | total         | list  |
| ------------- |:-------------:| -----:|
| Green         | 788 and 1207  | 122   |
| While         | 544 and 568   | 176   |
| Yellow        | 282 and 775   | 212   |

#### the tables turn out very beautiful

Markdown | Less | Pretty
--- | --- | ---
*Still* | `renders` | **nicely**
1 | 2 | 3

_______

<a id="444"></a>

## Example 12

```
[I'm an inline-style link](https://www.google.com)

[I'm a reference-style link][Arbitrary case-insensitive reference text]

[You can use numbers for reference-style link definitions][1]

Or leave it empty and use the [link text itself]

URLs and URLs in angle brackets will automatically get turned into links. 
http://www.example.com or <http://www.example.com> and sometimes 
example.com (but not on Github, for example).

Some text to show that the reference links can follow later.

[arbitrary case-insensitive reference text]: https://www.mozilla.org
[1]: http://slashdot.org
[link text itself]: http://www.reddit.com
```

[I'm an inline-style link](https://www.google.com)

[I'm a reference-style link][Arbitrary case-insensitive reference text]

[You can use numbers for reference-style link definitions][1]

Or leave it empty and use the [link text itself]

URLs and URLs in angle brackets will automatically get turned into links. 
http://www.example.com or <http://www.example.com> and sometimes 
example.com (but not on Github, for example).

Some text to show that the reference links can follow later.

[arbitrary case-insensitive reference text]: https://www.mozilla.org
[1]: http://slashdot.org
[link text itself]: http://www.reddit.com


--------

<a id="222"></a>

## Example 13

```
Emphasis, aka italics, with *asterisks* or _underscores_.

Strong emphasis, aka bold, with **asterisks** or __underscores__.

Combined emphasis with **asterisks and _underscores_**.

Strikethrough uses two tildes. ~~Scratch this.~~
Emphasis, aka italics, with asterisks or underscores.

Strong emphasis, aka bold, with asterisks or underscores.

Combined emphasis with asterisks and underscores.

Strikethrough uses two tildes. Scratch this.
``` 

Emphasis, aka italics, with *asterisks* or _underscores_.

Strong emphasis, aka bold, with **asterisks** or __underscores__.

Combined emphasis with **asterisks and _underscores_**.

Strikethrough uses two tildes. ~~Scratch this.~~
Emphasis, aka italics, with asterisks or underscores.

Strong emphasis, aka bold, with asterisks or underscores.

Combined emphasis with asterisks and underscores.

Strikethrough uses two tildes. Scratch this.

__________

<a id="555"></a>

## Example 14

```
Inline-style: 
![alt text](https://github.com/adam-p/markdown-here/raw/master/src/common/images/icon48.png "Logo 1")

Reference-style: 
![alt text][logo]

[logo]: https://github.com/adam-p/markdown-here/raw/master/src/common/images/icon48.png "Logo 2"
```

#### you can also insert images

Inline-style: 
![alt text](https://github.com/adam-p/markdown-here/raw/master/src/common/images/icon48.png "Logo 1")

Reference-style: 
![alt text][logo]

[logo]: https://github.com/adam-p/markdown-here/raw/master/src/common/images/icon48.png "Logo 2"

