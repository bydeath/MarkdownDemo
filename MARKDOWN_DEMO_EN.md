Markdown Demo
=============

Description
-----------
This is a Demo to show how to write markdown script.

Generally code will be in a box like this:

```
I'm a box.
```

and effect of that code will show up above the box.

1.Headers
---------

use large header 
================

```
use large header 
================
```

use small header 
----------------
```
use small header 
----------------
```

# use header of size 1

```
# use header of size 1
```

## use header of size 2

```
## use header of size 2
```

### use header of size 3

```
### use header of size 3
```

#### use header of size 4

```
#### use header of size 4
```

##### use header of size 5

```
##### use header of size 5
```

###### use header of size 6

```
####### use header of size 6
```

2.List
------

Ordered List

1. one of ordered list
2. two of ordered list
    1. one of ordered list
    2. two of ordered list
        1. one of ordered list
        2. two of ordered list
        3. three of ordered list
    3. three of ordered list
3. three of ordered list

```
1. one of ordered list
2. two of ordered list
    1. one of ordered list
    2. two of ordered list
        1. one of ordered list
        2. two of ordered list
        3. three of ordered list
    3. three of ordered list
3. three of ordered list
```
Unordered List

* one of unordered list
* two of unordered list
    * one of unordered list
    * two of unordered list
        * one of unordered list
        * two of unordered list
        * three of unordered list
    * three of unordered list
* three of unordered list

```
* one of unordered list
* two of unordered list
    * one of unordered list
    * two of unordered list
        * one of unordered list
        * two of unordered list
        * three of unordered list
    * three of unordered list
* three of unordered list
```
Mixed Use of Ordered and Unordered List

1. one of ordered list
2. two of ordered list
    * one of unordered list
    * two of unordered list
        1. one of ordered list
        2. two of ordered list
        3. three of ordered list
    * three of unordered list
3. three of ordered list

```
1. one of ordered list
2. two of ordered list
    * one of unordered list
    * two of unordered list
        1. one of ordered list
        2. two of ordered list
        3. three of ordered list
    * three of unordered list
3. three of ordered list
```

3.Box
-----

```
This is a box.
```
    ```
    This is a box.
    ```
    
4.Blockquotes
-------------
> Email-style angle brackets are used for blockquotes.
> > And, they can be nested.
> > > And, they can be nested.
> > > > And, they can be nested.
>
> #### Headers can be used in blockquotes
> * You can quote a list.
> 
> ```
> You can quote a box.
> ```
> And so on.

5.Inline Code
-------------
`spans are delimited by backticks.`

```
`spans are delimited by backticks.`
or
``spans are delimited by backticks.``
```

6.Block Code
------------
    Indent every line of a code block by at least 4 spaces or 1 tab to make a block.

```
    Indent every line of a code block by at least 4 spaces or 1 tab to make a block.
```

7.Horizontal Rules
------------------
---
***
----

```
---
***
----
```

8.Line Break
------------

End a line with two or more spaces,    
or use <br> to break line.

```
End a line with two or more spaces,    
or use <br> to break line.
```

9.Strong and Emphasize
----------------------
*emphasize* **strong** _emphasize_ __strong__

```
*emphasize* **strong** _emphasize_ __strong__
```

10.Links
--------
[My Blog](http://pengjingwen.lofter.com)

```
[My Blog](http://pengjingwen.lofter.com)
```

[My Blog][id]
[id]:http://pengjingwen.lofter.com

>```
>[My Blog][id]
>[id]:http://pengjingwen.lofter.com
>```

11.Email
--------
My Email <pengjingwen1994@gmail.com>

```
My Email <pengjingwen1994@gmail.com>
```

12.Images
---------
![github](https://help.github.com/assets/help/invertocat.png)

```
![github](https://help.github.com/assets/help/invertocat.png)
```
![github](https://github.global.ssl.fastly.net/images/spinners/octocat-spinner-32.gif)

```
![github](https://github.global.ssl.fastly.net/images/spinners/octocat-spinner-32.gif)
```

13.Tables
---------
First Header | Second Header | Third Header
------------ | ------------- | ------------
Content Cell | Content Cell  | Content Cell
Content Cell | Content Cell  | Content Cell

```
First Header | Second Header | Third Header
------------ | ------------- | ------------
Content Cell | Content Cell  | Content Cell
Content Cell | Content Cell  | Content Cell
```

First Header | Second Header | Third Header
:----------- | :-----------: | -----------:
Left         | Center        | Right
Left         | Center        | Right

```
First Header | Second Header | Third Header
:----------- | :-----------: | -----------:
Left         | Center        | Right
Left         | Center        | Right
```

14.Anchor
---------
This is a [target](id:anchor).

This is a [link](#anchor) to that target.

```
This is a [target](id:anchor).

This is a [link](#anchor) to that target.
```

15.Strikethrough
----------------

~~This is a Strikethrough.~~

```
~~This is a Strikethrough.~~
```
