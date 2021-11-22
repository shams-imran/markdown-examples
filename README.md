**Header Example**

# H1 - This is H1

## H2 - This is H2

### H3 - This is H3

#### H4 - This is H4

##### H5 - This is H5

###### H6 - This is H6

***

#### Italic and Bold text 

*italic text here* with single *

_italic text here_ with underscore

**bold text here** with two **  
bold with double __underscores__ 

Strikethrough uses two tildes. ~~Scratch this.~~

Emphasis, aka italics, with *asterisks* or _underscores_.

Strong emphasis, aka bold, with **asterisks** or .
***
#### Paragraph and Line Breaks

Here's a line for us to start with.

This line is separated from the one above by two newlines, so it will be a *separate paragraph*.

This line is also a separate paragraph, but...
This line is only separated by a single newline, so it's a separate line in the *same paragraph*.

Use more than 2 space for new line.  
This is new line.

#### Link Example

Some [linked](http://google.com/ "Google") here.

[link_url]: http://google.com/ "Title"
An [example_with_id][link_url].

***

#### Images
![alt text](./sample_image.png "Image Title")

##### Images with Ref id
[img_id]: ./sample_image.png "Title Image"
![alt text][img_id]

##### Images with custom Size
<img src="./sample_image.png" 
alt="IMAGE ALT TEXT HERE" width="400" height="120" border="10" />

<p align="center">
  <img src="sample_image.png"/>
</p>


#### Reference Link
[I'm a relative reference to a repository file](./sample_file.txt)

***

#### Superscript 

E=MC<sup>2</sup>

#### Subscript 

CO<sub>2</sub>

***

### Lists

#### Ordered

1. Item 1
2. Item 2
3. Item 3

#### Unordered

* A list item.    
Type 4(Four Space for new line).  
Sample text for new line
* Bar.
If not type 4(Four Space) they are in same line.

#### Nested: 

* Abacus
    - absolute
        + sub-item 1
    + sub-item 2 
* Bananas
    1. bitter
    2. sitter
    3. pit
* Cunning
    1. abc
        * def
    2. fgh
        * ijk
        * lmn
*** 

#### Blockquotes

> Email-style angle brackets are used for blockquotes.
>> You can also nest them.
>>> Second level nested
>>>> Third level nested
> >
> * You can quote a list.
> * Etc.

> To break the nested blockquote, add a space between lines.

Add another line to resume regular paragraph text.

***

`<code>` spans are delimited by backticks.
You can include literal backticks like `` `this` ``.
Inline `code` has `back-ticks around` it.

This is a normal paragraph:

    This is a preformatted code block.
        his is second line
    This is third line.

Preceded by a space, the colon disappears : 

    This is a preformatted code block.

Code with language detection : 

###### Js Code
```javascript
var s = "JavaScript syntax highlighting";
alert(s);
```

###### python Code
```python
s = "Python syntax highlighting"
print(s)
```

###### json file
```json
{
"success": {
"message": "Welcome to JSON Viewer",
"status_code": 200
    }
}
```
###### No language indication
```
No language indicated, so no syntax highlighting. 
But let's throw in a <b>tag</b>.
```

#### Horizontal rules
Using Hyphens

--------

Using Asterisks

***

Using Underscores

___

#### Manual line breaks
End a line with two or more spaces: 

Roses are red,  
Violets are blue.

#### Text colors and fonts
This is <span style="color:red">red</span> color text.  
I am <span style="font-family:Papyrus; font-size:2em;">2 em!</span> font.  
I am <span style="color:red;font-family:Papyrus; font-size:1.5em;">1.5 em red color</span> font.

#### Tables

Colons can be used to align columns.

>There must be at least 3 dashes separating each header cell.
The outer pipes (|) are optional, and you don't need to make the 
raw Markdown line up prettily. You can also use inline Markdown.

| Tables        |      Are      |  Cool |
|---------------|:-------------:|------:|
| col 3 is      | right-aligned | $1600 |
| col 2 is      |   centered    |   $12 |
| zebra stripes |   are neat    |    $1 |

| Markdown | Less      | Pretty     |
|----------|-----------|------------|
| *Still*  | `renders` | **nicely** |
| 1        | 2         | 3          |

#### Checkbox Link
- [x] Write the press release
- [ ] Update the website
- [ ] Contact the media


#### Automatic URL Linking
http://www.example.com

#### Disabling Automatic URL Linking
`http://www.example.com`

