# HTML Basic

## Table of Contents

- [What is HTML](#What-is-HTML)
- [HTML Elements](#HTML-Elements)
- [HTML Attributes](#HTML-Attributes)
- [HTML Headings](#HTML-Headings)
- [HTML Paragraphs](#HTML-Paragraphs)
- [HTML Links](#HTML-Links)
- [HTML Images](#HTML-Images)
- [HTML Lists](#HTML-Lists)
- [HTML Tables](#HTML-Tables)
- [HTML Forms](#HTML-Forms)

## What is HTML

> HTML is the standard markup language for creating Web pages.

- HTML stands for Hyper Text Markup Language
- HTML describes the structure of a Web page
- HTML consists of a series of elements
- HTML elements tell the browser how to display the content
- HTML elements are represented by tags
- HTML tags label pieces of content such as "heading", "paragraph", "table", and so on
- Browsers do not display the HTML tags, but use them to render the content of the page

```html
<!DOCTYPE html>
<html>
  <head>
    <title>Page Title</title>
  </head>
  <body>
    <h1>My First Heading</h1>
    <p>My first paragraph.</p>
  </body>
</html>
```

> Example Explained

- The `<!DOCTYPE html>` declaration defines this document to be HTML5
- The `<html>` element is the root element of an HTML page
- The `<head>` element contains meta information about the document
- The `<title>` element specifies a title for the document
- The `<body>` element contains the visible page content
- The `<h1>` element defines a large heading
- The `<p>` element defines a paragraph

## HTML Elements

| Start tag | Element content     | End tag |
| --------- | ------------------- | ------- |
| `<h1>`    | My First Heading    | `</h1>` |
| `<p>`     | My first paragraph. | `</p>`  |
| `<br/>`   |                     |         |

## HTML-Attributes

- All HTML elements can have attributes
- Attributes provide additional information about an element
- Attributes are always specified in the start tag
- Attributes usually come in name/value pairs like: name="value"

> Example

```html
<a href="https://www.w3schools.com">This is a link</a>

<img src="img_girl.jpg" />

<p style="color:red">This is a red paragraph.</p>
```

> Example The lang Attribute

```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="utf-8" />
  </head>
  <body>
    ...
  </body>
</html>
```

## HTML Headings

> Headings are defined with the `<h1>` to `<h6>` tags.
>
> `<h1>` defines the most important heading. `<h6>` defines the least important heading.

> Example

```html
<h1>Heading 1</h1>
<h2>Heading 2</h2>
<h3>Heading 3</h3>
<h4>Heading 4</h4>
<h5>Heading 5</h5>
<h6>Heading 6</h6>
```

> Output

<h1>Heading 1</h1>
<h2>Heading 2</h2>
<h3>Heading 3</h3>
<h4>Heading 4</h4>
<h5>Heading 5</h5>
<h6>Heading 6</h6>

## HTML-Paragraphs

> The HTML `<p>` element defines a paragraph:

```html
<p>This is a paragraph.</p>
<p>This is another paragraph.</p>
```

## HTML Links

> You can click on a link and jump to another document.

```html
<a href="url">link text</a>
```

> The target Attribute
> <br>
> The target attribute specifies where to open the linked document.
> <br>
> The target attribute can have one of the following values:
> <br> > \_blank - Opens the linked document in a new window or tab
> <br> > \_self - Opens the linked document in the same window/tab as it was clicked (this is default)
> <br> > \_parent - Opens the linked document in the parent frame
> <br> > \_top - Opens the linked document in the full body of the window
> <br>
> framename - Opens the linked document in a named frame
> <br>
> This example will open the linked document in a new browser window/tab:

## HTML Images

> Images can improve the design and the appearance of a web page.

```html
<img src="pic_trulli.jpg" alt="Italian Trulli" />
```

## HTML Lists

> An unordered list starts with the `<ul>` tag. Each list item starts with the `<li>` tag.

```html
<ul>
  <li>Coffee</li>
  <li>Tea</li>
  <li>Milk</li>
</ul>
```

## HTML Tables

> An HTML table is defined with the `<table>` tag.
> <br>
> Each table row is defined with the `<tr>` tag.
> <br>
> A table header is defined with the `<th>` tag.
> <br>
> By default, table headings are bold and centered. A table data/cell is defined with the `<td>` tag.

```html
<table style="width:100%">
  <tr>
    <th>Firstname</th>
    <th>Lastname</th>
    <th>Age</th>
  </tr>
  <tr>
    <td>Jill</td>
    <td>Smith</td>
    <td>50</td>
  </tr>
  <tr>
    <td>Eve</td>
    <td>Jackson</td>
    <td>94</td>
  </tr>
</table>
```

## HTML Forms

> The HTML `<form>` element defines a form that is used to collect user input

```html
<form>
  . form elements .
</form>
```

> The `<input>` Element

| Type                    | Description                                                |
| ----------------------- | ---------------------------------------------------------- |
| `<input type="text">`   | Defines a single-line text input field                     |
| `<input type="radio">`  | Defines a radio button (for selecting one of many choices) |
| `<input type="submit">` | Defines a submit button (for submitting the form)          |

```html
<input type="text" id="firstname" name="firstname" />
<input type="radio" id="male" name="gender" value="male" />
<input type="submit" value="Submit" />
```

> The `<select>` Element

```html
<select id="cars" name="cars">
  <option value="volvo">Volvo</option>
  <option value="saab">Saab</option>
  <option value="fiat">Fiat</option>
  <option value="audi">Audi</option>
</select>
```
