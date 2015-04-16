#README.md
This file, explaining the purpose of this repo.

##Contact Info
Michael Liquori
liquori@gmail.com

## License Info
The MIT License (MIT)

Copyright (c) [2015] [Michael Liquori]

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.

## Recommended Uses:

Uses   |  Recommended?
------------ | -------------
for Good | Yes
for Evil | No!

## How to Use

#### 1. Clone in Git.
In Terminal, enter: 

```sh 
git clone https://github.com/mliq/prime_solo_git_workflows.git
```
#### 2. Place your HTML in `index.html`. 
See index.html section below for more in-depth information.
#### 3. Place your Javascript in `script.js`.
#### 4. Place your CSS styling in `stylesheet.css`. 

##index.html
This is a basic HTML Template.

###Doctype

The Document Type Declaration, or doctype, is a way to tell the browser what type of document it is looking at. It goes at the top of the document, and until other HTML tags, it does not need a closing bracket.

```html
<!doctype html>
```

###Html Element

The `<html>` element is the document root. It is the recommended place for specifying the page language. 

It has a start tag `<html>` and an end tag `</html>`. The html element includes the `lang` attribute with a value of `en`, which specifies that the document is in English.

```html
<html lang="en">
...
</html>
```

###Head Element

The `<head>` element is a container for metadata (*data about data*). HMetadata is not displayed. Metadata typically defines document title, styles, links, scripts, and other meta information. 


```html
<head>
...
</head>
```


###Meta Element

The `<meta>` element is used to specify page description, keywords, author, and other metadata. Metadata is used by browsers, search engines, and other web services.

The first line inside the head is the one that defines the character encoding for the document, which is nearly always utf-8. The character encoding declaration must be included somewhere within the first 512 characters of your document, before any content based blocks.

Meta data is optional. Here we've also included the description and author.


```html
<head>
<meta charset="utf-8">
...
<meta name="description" content="Empty HTML5 Template">
<meta name="author" content="Joseph Szczesniak">
...
</head>
```

###Title Element

The `<title>` element defines the title of the document and is required in all HTML/XHTML documents. It defines a title in the browser toolbar,
provides a title for the page when it is added to favorites, and displays a title for the page in search engine results.

```html
<title>Empty HTML5 Template</title>
```

##stylesheet.css

CSS goes here.

##script.js

Javascript goes here.


####Be sure to commit your changes to your development branch frequently!
![image](http://www.fillmurray.com/415/300)