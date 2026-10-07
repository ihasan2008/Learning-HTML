# HTML — HyperText Markup Language

> A structured roadmap for learning HTML, understanding web page structure, and practicing web development.

## 📚 Table of Contents

1. [HTML Basics](https://github.com/ihasan2008/Learning-HTML/blob/main/01-HTML-Basics/HTML-Basics.md)
2. [HTML Document](https://github.com/ihasan2008/Learning-HTML/blob/main/02-HTML-Document/HTML-Document.md)
3. [HTML Element](https://github.com/ihasan2008/Learning-HTML/blob/main/03-HTML-Element/HTML-Element.md)
4. [HTML Tags](https://github.com/ihasan2008/Learning-HTML/blob/main/04-HTML-Tags/HTML-Tags.md)
5. [HTML Attributes](https://github.com/ihasan2008/Learning-HTML/blob/main/05-HTML-Attributes/HTML-Attributes.md)
6. [HTML Content](https://github.com/ihasan2008/Learning-HTML/blob/main/06-HTML-Content/HTML-Content.md)
7. [HTML Comments](https://github.com/ihasan2008/Learning-HTML/blob/main/07-HTML-Comments/HTML-Comments.md)
8. [Advanced HTML](https://github.com/ihasan2008/Learning-HTML/blob/main/08-Advanced-HTML/Advanced-HTML.md)

---

# 1. HTML Basics

* [x] **1.1** What is HTML?
* [x] **1.2** HyperText কী?
* [x] **1.3** Markup Language কী?
* [x] **1.4** HTML-এর কাজ কী?
* [x] **1.5** HTML Versions
* [x] **1.6** HTML File Extension
* [x] **1.7** HTML Editor
* [x] **1.8** HTML Browser
* [x] **1.9** HTML কীভাবে কাজ করে?
* [x] **1.10** Website তৈরিতে HTML-এর ভূমিকা
* [x] **1.11** History of HTML
* [x] **1.12** Frontend-এর ৩টি প্রধান প্রযুক্তি
* [x] **1.13** HTML শেখার আগে যা জানা দরকার
* [x] **1.14** Static vs Dynamic Website
* [x] **1.15** HTML, CSS & JavaScript Relationship
* [x] **1.16** Frontend vs Backend
* [x] **1.17** Server & Database
* [x] **1.18** Next Learning Steps

---

# 2. HTML Document

An HTML document defines the basic structure of a web page.

```html
<!DOCTYPE html>
<html lang="en">
    <head>
        <meta charset="UTF-8">
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <title>My Website</title>
    </head>
    <body>

    </body>
</html>
```

## Document Structure

* `<!DOCTYPE html>` — Declares an HTML5 document.
* `<html>` — Root element of the document.
* `<head>` — Contains metadata and linked resources.
* `<title>` — Defines the browser tab title.
* `<body>` — Contains the visible page content.

---

# 3. HTML Element

An HTML element generally consists of an opening tag, content, and a closing tag.

```html
<tagname attribute="value">
    Content
</tagname>
```

**Example:**

```html
<p class="description">Learning HTML</p>
```

* Opening tag: `<p>`
* Attribute: `class="description"`
* Content: `Learning HTML`
* Closing tag: `</p>`

> Note: Void elements, such as `<img>` and `<br>`, do not have closing tags.

---

# 4. HTML Tags

## 4.1 Document Tags

1. `<!DOCTYPE html>`
2. `<html></html>`
3. `<head></head>`
4. `<title></title>`
5. `<body></body>`

## 4.2 Metadata & Resource Tags

6. `<meta>`
7. `<link>`
8. `<base>`
9. `<style></style>`
10. `<script></script>`
11. `<noscript></noscript>`

## 4.3 Heading Tags

12. `<h1></h1>`
13. `<h2></h2>`
14. `<h3></h3>`
15. `<h4></h4>`
16. `<h5></h5>`
17. `<h6></h6>`

## 4.4 Basic Content Tags

18. `<p></p>`
19. `<div></div>`
20. `<span></span>`
21. `<br>`
22. `<hr>`
23. `<pre></pre>`

## 4.5 Text Formatting Tags

24. `<b></b>`
25. `<strong></strong>`
26. `<i></i>`
27. `<em></em>`
28. `<u></u>`
29. `<mark></mark>`
30. `<small></small>`
31. `<sub></sub>`
32. `<sup></sup>`
33. `<del></del>`
34. `<ins></ins>`
35. `<s></s>`
36. `<code></code>`
37. `<kbd></kbd>`
38. `<samp></samp>`
39. `<var></var>`

## 4.6 Quote & Reference Tags

40. `<blockquote></blockquote>`
41. `<q></q>`
42. `<cite></cite>`
43. `<abbr></abbr>`
44. `<dfn></dfn>`
45. `<time></time>`
46. `<data></data>`

## 4.7 List Tags

47. `<ul></ul>`
48. `<ol></ol>`
49. `<li></li>`
50. `<dl></dl>`
51. `<dt></dt>`
52. `<dd></dd>`

## 4.8 Link Tags

53. `<a></a>`

## 4.9 Image & Image Map Tags

54. `<img>`
55. `<picture></picture>`
56. `<source>`
57. `<figure></figure>`
58. `<figcaption></figcaption>`
59. `<map></map>`
60. `<area>`

## 4.10 Audio & Video Tags

61. `<audio></audio>`
62. `<video></video>`
63. `<source>`
64. `<track>`

## 4.11 Table Tags

65. `<table></table>`
66. `<caption></caption>`
67. `<thead></thead>`
68. `<tbody></tbody>`
69. `<tfoot></tfoot>`
70. `<tr></tr>`
71. `<th></th>`
72. `<td></td>`
73. `<colgroup></colgroup>`
74. `<col>`

## 4.12 Form Tags

75. `<form></form>`
76. `<label></label>`
77. `<input>`
78. `<textarea></textarea>`
79. `<button></button>`
80. `<select></select>`
81. `<option></option>`
82. `<optgroup></optgroup>`
83. `<fieldset></fieldset>`
84. `<legend></legend>`
85. `<datalist></datalist>`
86. `<output></output>`
87. `<meter></meter>`
88. `<progress></progress>`

## 4.13 Semantic Layout Tags

89. `<header></header>`
90. `<nav></nav>`
91. `<main></main>`
92. `<section></section>`
93. `<article></article>`
94. `<aside></aside>`
95. `<footer></footer>`
96. `<address></address>`

## 4.14 Interactive Tags

97. `<details></details>`
98. `<summary></summary>`
99. `<dialog></dialog>`

## 4.15 Embedded Content Tags

100. `<iframe></iframe>`
101. `<embed>`
102. `<object></object>`
103. `<param>`

## 4.16 Graphics Tags

104. `<canvas></canvas>`
105. `<svg></svg>`

## 4.17 Web Components

106. `<template></template>`
107. `<slot></slot>`

## 4.18 Ruby Annotation Tags

108. `<ruby></ruby>`
109. `<rt></rt>`
110. `<rp></rp>`

## 4.19 Deprecated & Obsolete Tags

These tags are listed for historical awareness. Avoid using them in modern HTML.

111. `<center></center>`
112. `<font></font>`
113. `<big></big>`
114. `<tt></tt>`
115. `<strike></strike>`
116. `<frameset></frameset>`
117. `<frame>`
118. `<noframes></noframes>`
119. `<acronym></acronym>`
120. `<applet></applet>`
121. `<dir></dir>`

---

# 5. HTML Attributes

Attributes provide additional information or configure the behavior of HTML elements.

## 5.1 Global Attributes

1. `id=""`
2. `class=""`
3. `style=""`
4. `title=""`
5. `hidden`
6. `tabindex=""`
7. `lang=""`
8. `dir=""`
9. `draggable="true/false"`
10. `contenteditable="true/false"`
11. `data-*`

## 5.2 Link / Anchor Attributes

12. `href=""`
13. `target=""`
14. `rel=""`
15. `download`
16. `hreflang=""`
17. `type=""`

## 5.3 Image Attributes

18. `src=""`
19. `alt=""`
20. `width=""`
21. `height=""`
22. `loading="lazy/eager"`
23. `srcset=""`
24. `sizes=""`

## 5.4 Form Attributes

25. `action=""`
26. `method="GET/POST"`
27. `enctype=""`
28. `target=""`
29. `autocomplete="on/off"`
30. `novalidate`
31. `name=""`
32. `value=""`
33. `placeholder=""`
34. `required`
35. `disabled`
36. `readonly`
37. `min=""`
38. `max=""`
39. `step=""`
40. `maxlength=""`
41. `minlength=""`
42. `pattern=""`
43. `checked`
44. `multiple`
45. `accept=""`
46. `form=""`

## 5.5 Input Types

47. `type="text"`
48. `type="password"`
49. `type="email"`
50. `type="number"`
51. `type="radio"`
52. `type="checkbox"`
53. `type="file"`
54. `type="date"`
55. `type="submit"`
56. `type="reset"`
57. `type="button"`
58. `type="range"`
59. `type="color"`

## 5.6 Script Attributes

60. `src=""`
61. `async`
62. `defer`
63. `type="module"`
64. `crossorigin=""`

## 5.7 Table Attributes

65. `colspan=""`
66. `rowspan=""`
67. `scope=""`
68. `headers=""`

## 5.8 Media Attributes

69. `controls`
70. `autoplay`
71. `muted`
72. `loop`
73. `poster=""`
74. `preload="auto/metadata/none"`
75. `src=""`

## 5.9 Iframe Attributes

76. `src=""`
77. `width=""`
78. `height=""`
79. `allow=""`
80. `sandbox=""`
81. `loading="lazy"`
82. `referrerpolicy=""`

## 5.10 Meta Attributes

83. `charset=""`
84. `name=""`
85. `content=""`
86. `http-equiv=""`

## 5.11 List Attributes

87. `start=""`
88. `reversed`
89. `value=""`

## 5.12 Button Attributes

90. `type="button/submit/reset"`
91. `disabled`
92. `name=""`
93. `value=""`

## 5.13 Select Attributes

94. `multiple`
95. `size=""`
96. `disabled`
97. `required`
98. `name=""`

## 5.14 Option Attributes

99. `value=""`
100. `selected`
101. `disabled`

## 5.15 Miscellaneous Attributes

102. `accesskey=""`
103. `spellcheck="true/false"`
104. `translate="yes/no"`
105. `contextmenu=""` — Obsolete; avoid using it.
106. `autofocus`
107. `form=""`

> **Note:** This is a categorized study list, not an exhaustive list of every HTML attribute. Some attributes are element-specific, and repeated names such as `type`, `src`, `name`, and `form` have different uses depending on the element.

---

# 6. HTML Content

## 6.1 HTML Content কী?

## 6.2 HTML Content Types

* [ ] **6.2.1** Text Content
* [ ] **6.2.2** Image Content
* [ ] **6.2.3** Link Content
* [ ] **6.2.4** List Content
* [ ] **6.2.5** Table Content
* [ ] **6.2.6** Form Content
* [ ] **6.2.7** Media Content (Audio / Video)
* [ ] **6.2.8** Semantic Content
* [ ] **6.2.9** Preformatted Content
* [ ] **6.2.10** Code Content
* [ ] **6.2.11** Quote Content
* [ ] **6.2.12** Inline Content

## 6.3 HTML Content Structure

## 6.4 Empty Content Elements (Void Elements)

## 6.5 HTML Content Rules

## 6.6 Real Website Content Example

---

# 7. HTML Comments

* [ ] **7.1** HTML Comment কী?
* [ ] **7.2** HTML Comment Syntax
* [ ] **7.3** Single Line Comment
* [ ] **7.4** Multi Line Comment
* [ ] **7.5** HTML Comment কীভাবে কাজ করে?
* [ ] **7.6** Comment ব্যবহার কোথায় হয়?

### Comment Syntax

```html
<!-- This is an HTML comment -->
```

### Multi-line Comment

```html
<!--
    This is a multi-line comment.
    It can contain multiple lines.
-->
```

> HTML comments are visible in the page source. Do not put passwords, API keys, or other secrets inside comments.

---

# 8. Advanced HTML

* [ ] Semantic HTML in depth
* [ ] Accessible HTML
* [ ] Advanced Forms and Validation
* [ ] Responsive Images
* [ ] Audio and Video
* [ ] SVG and Canvas
* [ ] Iframes and Embedded Content
* [ ] SEO-friendly HTML
* [ ] HTML Best Practices
* [ ] HTML Performance
* [ ] HTML Security Basics
* [ ] HTML with CSS
* [ ] HTML with JavaScript
* [x] HTML Web Projects

---

## 📌 Learning Progress

* **Subject:** HTML
* **Category:** Web Development
* **Purpose:** Learn, Practice, Build, and Document
* **Repository:** Learning HTML

> Learn → Practice → Build → Improve → Repeat.