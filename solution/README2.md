
# How to write an HTML Boilerplate

![HTML Boilerplate Code Snippet](https://media.istockphoto.com/id/1391198660/photo/hands-printing-on-laptop-banner.webp?a=1&b=1&s=612x612&w=0&k=20&c=OZXgKLFHB2U7gv94dDBs9gbOU2F_R3Y4FLo0FjSRIcQ=)

'An HTML boilerplate is a set of pre-written HTML, CSS, and JavaScript files that form the starting point for your web project. It includes essential elements like the doctype declaration, meta tags, link to CSS files, and script tags for JavaScript. The primary goal is to save time and ensure consistency by providing a robust template that follows industry standards' (GeeksforGeeks, 2024).

<br>

## Option 1: Using The _Emmett Abbreviation_
#### 1. Press _"!"_ which is the symbol shortcut of the HTML boilerplate. 
```html
!
```
> Tip: Ensure that your file has the extension of ".html"!
  
<br>

#### 2. Press _"Tab"_ or _"Enter"_ and the following code will be produced!


```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<body>
    
</body>
</html>
```
> Tip: Take the time to notice the difference between normal tags and self-closing tags!

<br>

## Option 2: Coding Manually

#### 1. Doctype Declaration
The doctype declaration is crucial as it informs the browser which version of HTML you are using. The most common version is HTML5, indicated by the following self-closing tag:
```html
<!DOCTYPE html>
```
> Tip: This is not an HTML tag! It simply lets the browser know what to expect.

<br>

#### 2. HTML Tag & Language Attribute
The _"html"_ tag is the root element of an HTML document that may include the _"lang"_ attribute which specifies the language of the content. This is also where you link your css style sheets or javascript files!
```html
<html lang="en">
```

> Tip: Including the lang attribute in your html tag heavily supports accessibility and Search Engine Optimization (SEO)!

<br>

#### 3. Head Section
The "_head_" tag includes metadata about the HTML that helps browsers and search engines interpret your page more efficiently. Note that this information is not displayed on the webpage itself.
```html
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Project</title>
```

> Tip: This is also where you link your css style sheets or javascript files!

<br>

#### 4. Body Section
The "_body_" tag includes all the information you wish to display on your page! From headings and paragraphs to images and links, there are numerous ways to showcase your content.
```html
<body>
</body>
```
> Tip: There can only be one body tag in an HTML document!

<br>

### You are ready to write the HTML boilerplate 🎉!