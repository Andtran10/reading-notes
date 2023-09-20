# HTML NOTES
Wireframe: Define/plan design for website, app, product
Wireframe tools: 
- Pen and paper
- UXPin
- InVision
- Wireframe.cc
- Figma

Key principles:
- Clarity
- Confidence
- Simplicity is key

# HTML structure

HTML: (**H**yper**T**ext **M**arkup **L**anguage)

**Vocabulary**: 

Element: a unit of content in a HTML document formed by tags, texts, media

Tag: element name surrounded by opening (<) and closing (>)

Opening Tag: Start a HTML element (<>)

Content: Info between opening and closing tags

Closing Tag: Close a HTML element (</>)

Attributes: Content added to opening tags with uses: providing info to changing styling

- The Name of the attribute
- The Value of the attribute

Example: id= (specify different content)

Whitespace: Makes code more readable by putting each element on its own line

```html
**Before Whitespace**

<!DOCTYPE html>
<html>
<body><h1>Whitespace</h1><p> Whitespace and indentation make html documents
easier to read</p></body>
</html>

**After Whitespace**

<!DOCTYPE html>
<html>
  <body>
    <h1>Whitespace</h1>
    <p>Whitespace and indentation make html documents easier to read</p>
  </body>
</html>
```

Indentation: Space before a line of code. Standard (W3C) is two lines. Depends on nested elements more indentation may be needed. 

```html
<body>
  <h1>Whitespace</h1>    
  <div>
    <p>Whitespace and indentation make html documents easier to read.</p>
  </div>  
</body>
```

Comments: <!- -, - > : Adds comment to code, but won’t show in browser.

```html
<!-- hi -->
```

**Structure Element:** Start tag, some content, and an end tag

<!DOCTYPE code language>: Specify what type of code and the standard is being presented/used.

HTML tag: <html> </html> : Anything between these two tags will be interpreted as HTML code

```html
<!DOCTYPE html>
	<html>
		<head>
			<title> "Example" </title>
		</head>
	</html>
```

Head Element: <head> </head> : Contains the metadata for the page (info about page, but not displayed on the page). Goes above <body> element.

Title Element: <title> </title> : Display title of webpage. Goes inside of <head> element.

Body Element: <body> </body> : Contains all of the page’s visible content

```html
<body>
	<p>
		"hi"
	</p>
</body>
Prints hi
```

Parent Element: When an element contains another elements inside it

Child Element: When an element is contained inside another element

```html
<body>
	<p>
		"hi"
	</p>
</body>
<body> = Parent
<p> = Child
```

Division Element: <div> </div> : Divides the page into sections. Groups other elements together. When to use: Divide content into blocks

Paragraph Element: <p> </p> : Contain a block of plain text

Span : <span> </span> : contains short pieces of text or other HTML. When to use: Target a specific piece of content

Emphasizes: <em> </em> : Generally render as *italic* emphasis. 

Strong: <strong> </strong>: Generally render as **bold** emphasis.

Line Break: <br> : Modifies the spacing in the browser. Modifies the vertical spacing. **Only uses a starting tag**

Unordered List: <ul> </ul> : Display content in a list (bullet points). Should not hold raw text and won’t automatically format raw text.

Ordered List: <ol> </ol> : Display content in a list (numbered). When to use: list different steps, ranking items for first to last. 

List Item: <li> </li> : Describe an item in a list

```html
<ul>
	<li>Seattle</li>
	<li>Federal Way</li>
	<li>Tacoma</li>
</ul>

(bullet points before)
Seattle
Federal Way
Tacoma

<ol>
	<li>Seattle</li>
	<li>Federal Way</li>
	<li>Tacoma</li>
</ol>

1. Seattle
2. Federal Way
3. Tacoma
```

Images: <img/> : Allows you to add an image to a web page. Image is a self closing tag <img />. This tag requires the attribute (**src**): source of image or location of image usually a URL. Need (””) at beginning and end of URL/source. 

```html
<img scr="image-location.jpg" />
```

Image alts attribute: alt : Alternative text, brings meaning to images on site. Need (””) at beginning and end of text description.

```html
<img scr="image-location.jpg" alt="description of image" />
```

Example: 

Image doesn’t load: mouse over intended image for a brief description.

Visually impaired: Allows screen reading software to read image description

Search Engine Optimization (SEO): SEO cannot “see” images.

Video: <video > </video> : Allows you to display video to a web page. 

Attribute: 

width, height : Use to set the size of the video displayed in the browser. 

control: Instructs browser to include basic controls such as pausing and playing

```html
<video src="myVideo.mp4" width="320" height="240" controls>
	video not supported
</video> 

video not supported will display if browser is unable to load the video
```

Anchor: <a > </a> : Add links to a webpage. Can wrap video/images tags to allows video/images as hyperlink source.

Hyperlink reference: **href** attribute : 

```html
<a href="https://www.wikipedia.org/">This Is A Link To Wikipedia</a>
```

Link to internal web page: ./ : Tells browser to look for file in the current folder

```html
<a href="./FolderName1.html">FolderName1 contents</a>
```

Video/images as link: Put destination of link with <a></a>. <img /> will be inside anchor thus transforming <img /> into a link. 

```html
<a href="https://en.wikipedia.org/wiki/Opuntia" target="_blank">
<img src="https://www.Prickly_Pear_Closeup.jpg" alt="A red prickly pear fruit"/></a>
```

Target attribute: Specifies how a link should open. Requires a value of (”_blank”). Opens link in new window

```html
<a href="https://en.wikipedia.org/wiki/Brown_bear" 
target="_blank">The Brown Bear</a>

Opens link in a new tab
```

Id attribute: id= : Link to a target on the same page. Target link is a string containing the **#** and the targets element’s id.

```html
<ul>
    <li><a href="#introduction"> Introduction</a></li>
    <li><a href="#habitat">Habitat</a></li>
    <li><a href="#media">Media</a></li>
  </ul>

Turns list: Introduction, Habitat, and Media into links redirecting to 
different sections of the page. <a> Adds link, href= link reference/
destination, "#xxxx" is the destination of the link (found in the code), 
Title is what is present on the page. 
```

Style: <style> : write CSS rules in HTML document

**Headings:**

6 different headings: 

- <h1> - used for main heading. All other smaller headings are used for subheadings
- <h2>
- <h3>
- <h4>
- <h5>
- <h6>

**********************************Preparing for HTML:********************************** 

**Document type declaration:** First line of Code: Tells browser what type of document to expect


# Questions
1. What is HTML and why do we use it?
1. What are the 3 main parts of an HTML element
1. What is it called when you give an element extra element?
1. What is a semantic element?
