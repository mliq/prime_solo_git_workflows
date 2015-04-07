# Week 1 day 3 - Git Workflows
##Assignment Overview

This assignment will build upon basic Git knowledge and illustrate a full Git workflow, much like workflows used in production environments. 

**Instructions:**

  - **Fork** this repository, which contains an `index.html` file and a markdown file named `README.md`. `fork` is much like `clone`, in that it is a copy of the existing repository, except that you can contribute back to the original project through 'pull requests' or by pushing to 'upstream' if you have contributor access. 
  - Create a new **branch** named 'readme'. This is what is called a 'feature branch' and is used to work on features without impacting the main branch.
  - Checkout the "readme" branch. 
  - Add a new JavaScript file and a new CSS file.
  - Edit the HTML file to include your new files.
  - Fill out the markdown document to explain that this is a basic HTML template, write at least one example on how to use it, add your contact information, and add a [software license of your choice](http://choosealicense.com/).
  - Once you're completely finished with the assignment, merge your branch back into the master branch of your repository to signal that the "feature" is complete.
  - Submit a pull request to the original repo.
  


##Contents
##README.md
This is the file you're reading. Add any content you like!

##index.html

###Doctype

The Document Type Declaration, or doctype, is a way to tell the browser what type of document it is looking at. It goes at the top of the document, and until other HTML tags, it does not need a closing bracket.

```
<!doctype html>
```

###Html Element

The `<html>` element is the document root. It is the recommended place for specifying the page language. 

It has a start tag `<html>` and an end tag `</html>`. The html element includes the `lang` attribute with a value of `en`, which specifies that the document is in English.

```
<html lang="en">
...
</html>
```

###Head Element

The `<head>` element is a container for metadata (*data about data*). HMetadata is not displayed. Metadata typically defines document title, styles, links, scripts, and other meta information. 


```
<head>
...
</head>
```


###Meta Element

The `<meta>` element is used to specify page description, keywords, author, and other metadata. Metadata is used by browsers, search engines, and other web services.

The first line inside the head is the one that defines the character encoding for the document, which is nearly always utf-8. The character encoding declaration must be included somewhere within the first 512 characters of your document, before any content based blocks.

Meta data is optional. Here we've also included the description and author.


```
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

```
<title>Empty HTML5 Template</title>
```

####Be sure to commit your changes to your development branch frequently!
![image](http://www.fillmurray.com/415/300)