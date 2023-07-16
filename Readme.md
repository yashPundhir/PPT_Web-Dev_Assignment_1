# Core Modules Assignment 1 - HTML

---

**Q1.** `<!DOCTYPE html>` is it a tag of html? If not, what is it and why do we use it?

**Ans1.** The `<!DOCTYPE html>` declaration is not a tag in HTML; it is known as a document type declaration. It is used at the beginning of an HTML document to specify the version of HTML being used.

The purpose of the `<!DOCTYPE html>` declaration is to inform the web browser about the type of markup language used in the document. In this case, it indicates that the document is written in HTML5, the latest version of HTML.

---

**Q2.** Explain Semantic tags in html? And why do we need it?

**Ans2.** Semantic tags in HTML are a set of elements that provide meaning and structure to the content within a web page. Unlike generic tags like `<div>` or `<span>`, which are used for layout and styling purposes, semantic tags convey the purpose and significance of the enclosed content.

Some commonly used semantic tags:
`<header>`, `<nav>`, `<main>`, `<article>`, `<section>`, `<aside>`, `<footer>`.

---

**Q3.** Differentiate between HTML Tags and Elements?

**Ans3.**

**HTML Tags:** HTML tags are the building blocks of an HTML document. They define the structure and elements within the document. Tags are represented by angle brackets **< >** and come in pairs: an opening tag and a closing tag. The opening tag indicates the beginning of an element, and the closing tag indicates its end.

```html
<p>This is a paragraph.</p>
```

In this example, `<p>` is the opening tag, and `</p>` is the closing tag. The content between the opening and closing tags represents the content of the element.

**HTML Elements:**

HTML elements are made up of HTML tags, along with the content enclosed between the opening and closing tags. An element consists of the opening tag, the content, and the closing tag. For example, in the previous paragraph example, the `<p>` tag and the content **"This is a paragraph."** together form the `<p>` element.

```html
<div>
	<h1>Welcome</h1>
	<p>This is a paragraph.</p>
</div>
```

The `<div>` element contains an `<h1>` element and a `<p>` element.

---

**Q4.** Build Your Resume using HTML only

## [Resume](https://github.com/yashPundhir/Resume_HTML_Only)

---

**Q5.** Write HTML code so that it looks like the below image:

![img](https://pwskills.notion.site/image/https%3A%2F%2Fs3-us-west-2.amazonaws.com%2Fsecure.notion-static.com%2F5d76dcda-d8eb-4c2e-836d-5c1aee0f8c6d%2Fhtml.png?id=9eae56b9-1968-40e8-98e1-b745e9e0a4ea&table=block&spaceId=6fae2e0f-dedc-48e9-bc59-af2654c78209&width=2000&userId=&cache=v2)

## [Image Clone HTML Code](https://github.com/yashPundhir/Image_Clone_HTML_Only)

---

**Q6.** What are some of the advantages of HTML5 over its previous versions?

**Ans6.** HTML5 introduced various advancements and new features over its previous versions, offering numerous advantages. These are:

**Improved Semantics:** HTML5 introduced a set of semantic tags such as `<header>`, `<nav>`, `<section>`, and `<footer>`, which provide clearer and more meaningful structure to web content.

**Multimedia Support:** HTML5 brought native support for multimedia elements, including `<video>` and `<audio>` and provides a standardised way to embed and control media content.

**Canvas Element:** HTML5 introduced the `<canvas>` element, which enables dynamic rendering of graphics, animations, and interactive visualisations using JavaScript.

**Geolocation:** HTML5 introduced the Geolocation API, allowing web applications to access a user's location information with their consent.

**Improved Form Input Types:** HTML5 introduced new input types such as email, date, number, range, and more, making it easier to capture and validate user input.

---

**Q7.** Create a simple Music player using html only

## [Music Player](https://github.com/yashPundhir/Music_Player_HTML_Only)

---

**Q8.** What is the difference between `<figure>` tag and `<img>` tag?

**Ans8.**

`<figure>` tag:

The `<figure>` tag is used to encapsulate and provide semantic meaning to self-contained content, such as images, illustrations, diagrams, audio, or videos, along with an optional caption. It can include any block-level or inline elements within it. Typically, an image is placed inside the `<figure>` element.

Eg:

```html
<figure>
	<img src="path/to/image.jpg" alt="Description of the image" />
	<figcaption>Caption for the image</figcaption>
</figure>
```

**`<img>` tag:**

The `<img>` tag is used to embed an image into an HTML document. It is a self-closing tag and does not have any content or nested elements. It requires the src attribute, which specifies the path to the image file, and the alt attribute, which provides alternative text for the image.

Eg:

```html
<img src="path/to/image.jpg" alt="Description of the image" />
```

The `<img>` tag is primarily focused on displaying images and does not provide any semantic meaning or context for the image.

---

**Q9.** What’s the difference between html tag and attribute and give example of some global attributes?

**Ans9.**

**HTML Tags:** HTML tags are used to define elements within an HTML document. They are represented by opening and closing angle brackets < > and enclose the content they affect. Tags define the structure and semantics of the content. For example, `<p>`, `<div>`, `<h1>`, and `<img>` are all examples of HTML tags.

**HTML Attributes:** HTML attributes are used to provide additional information or modify the behaviour of HTML elements. They are placed within the opening tag of an element and consist of a name-value pair. Attributes provide instructions to browsers, define element properties, or enable certain functionalities.

For example, the src attribute in the `<img>` tag specifies the source URL of an image. Attributes can be optional or required depending on the element and its purpose.

**Some examples of global attributes:**

`class`: Specifies one or more class names to apply CSS styling or JavaScript manipulation to elements.

`id`: Provides a unique identifier for an element, which can be used to target and manipulate the element using CSS or JavaScript.

`style`: Allows inline CSS styles to be applied directly to an element.

`title`: Specifies additional information about an element. It is often displayed as a tooltip when hovering over the element.

`translate`: Specifies whether the content of an element should be translated or not.

---

**Q10.** Write Html code so that it looks like the below image:

![img](https://pwskills.notion.site/image/https%3A%2F%2Fs3-us-west-2.amazonaws.com%2Fsecure.notion-static.com%2F365d0427-ccce-4f03-8f68-f71394cb86b5%2FUntitled.png?id=bc83e227-e490-4173-966b-be20296428d1&table=block&spaceId=6fae2e0f-dedc-48e9-bc59-af2654c78209&width=2000&userId=&cache=v2)

## [Table HTML Code](https://github.com/yashPundhir/Table_Clone_HTML_Only)

---
