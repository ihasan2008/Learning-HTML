# HTML Tags

HTML Tags হলো HTML-এর সবচেয়ে গুরুত্বপূর্ণ অংশ। একটি HTML Document বিভিন্ন ধরনের Tag-এর সমন্বয়ে তৈরি হয়। প্রতিটি Tag-এর নির্দিষ্ট একটি কাজ (Purpose) রয়েছে এবং Browser সেই কাজ অনুযায়ী Web Page প্রদর্শন করে।

সহজভাবে বলতে গেলে, **HTML Tag হলো Browser-এর জন্য একটি নির্দেশনা (Instruction)**, যা বলে দেয় কোনো Content কীভাবে প্রদর্শিত হবে।

---

### HTML Tag কী?

HTML Tag হলো একটি বিশেষ Keyword, যা **Angle Brackets (`< >`)** এর মধ্যে লেখা হয়।

উদাহরণ:

```html
<p>Hello World</p>
```

এখানে—

* `<p>` → Opening Tag
* `Hello World` → Content
* `</p>` → Closing Tag

Browser বুঝতে পারে এটি একটি Paragraph এবং সেই অনুযায়ী প্রদর্শন করে।

---

### HTML Tag-এর গঠন (Syntax)

বেশিরভাগ HTML Tag-এর সাধারণ গঠন—

```html
<tagname>
    Content
</tagname>
```

Attribute ব্যবহার করলে—

```html
<tagname attribute="value">
    Content
</tagname>
```

উদাহরণ—

```html
<a href="https://example.com">Visit Website</a>
```

---

### HTML Tag-এর অংশসমূহ

| অংশ         | বর্ণনা           |
| ----------- | ---------------- |
| Opening Tag | Element শুরু করে |
| Content     | প্রদর্শিত তথ্য   |
| Closing Tag | Element শেষ করে  |

উদাহরণ—

```html
<h1>Welcome</h1>
```

---

### HTML Tag কীভাবে কাজ করে?

Browser HTML File পড়ার সময় নিচের ধাপগুলো অনুসরণ করে—

```text
Read HTML File
       │
       ▼
Read Opening Tag
       │
       ▼
Read Attributes
       │
       ▼
Read Content
       │
       ▼
Read Closing Tag
       │
       ▼
Render Web Page
```

---

### HTML Tag-এর প্রকারভেদ

HTML-এ বিভিন্ন ধরনের Tag রয়েছে। শেখার সুবিধার জন্য এগুলোকে বিভিন্ন Category-তে ভাগ করা হয়।

#### ১. HTML Document Tags

সম্পূর্ণ HTML Document-এর মূল কাঠামো তৈরি করে।

1. `<!DOCTYPE html>`
2. `<html></html>`
3. `<head></head>`
4. `<title></title>`
5. `<body></body>`

---

#### ২. Metadata Tags

Web Page সম্পর্কে অতিরিক্ত তথ্য (Metadata) প্রদান করে।

6. `<meta>`
7. `<link>`
8. `<base>`
9. `<style></style>`
10. `<script></script>`
11. `<noscript></noscript>`

---

#### ৩. Heading Tags

Heading বা শিরোনাম তৈরি করতে ব্যবহৃত হয়।

12. `<h1></h1>`
13. `<h2></h2>`
14. `<h3></h3>`
15. `<h4></h4>`
16. `<h5></h5>`
17. `<h6></h6>`

---

#### ৪. Basic Content Tags

Web Page-এর সাধারণ Content প্রদর্শনের জন্য ব্যবহৃত হয়।

18. `<p></p>`
19. `<div></div>`
20. `<span></span>`
21. `<br>`
22. `<hr>`
23. `<pre></pre>`

---

#### ৫. Text Formatting Tags

Text-এর Style এবং গুরুত্ব প্রকাশ করতে ব্যবহৃত হয়।

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

---

#### ৬. Quote & Reference Tags

উদ্ধৃতি, সংক্ষিপ্ত রূপ এবং রেফারেন্স প্রদর্শনের জন্য ব্যবহৃত হয়।

40. `<blockquote></blockquote>`
41. `<q></q>`
42. `<cite></cite>`
43. `<abbr></abbr>`
44. `<dfn></dfn>`
45. `<time></time>`
46. `<data></data>`

---

#### ৭. List Tags

বিভিন্ন ধরনের তালিকা (List) তৈরির জন্য ব্যবহৃত হয়।

47. `<ul></ul>`
48. `<ol></ol>`
49. `<li></li>`
50. `<dl></dl>`
51. `<dt></dt>`
52. `<dd></dd>`

---

#### ৮. Link Tags

Hyperlink তৈরি করার জন্য ব্যবহৃত হয়।

53. `<a></a>`

---

#### ৯. Image Tags

ছবি এবং Image সম্পর্কিত Content প্রদর্শনের জন্য ব্যবহৃত হয়।

54. `<img>`
55. `<picture></picture>`
56. `<source>`
57. `<figure></figure>`
58. `<figcaption></figcaption>`
59. `<map></map>`
60. `<area>`

---

#### ১০. Audio & Video Tags

Audio এবং Video Content প্রদর্শনের জন্য ব্যবহৃত হয়।

61. `<audio></audio>`
62. `<video></video>`
63. `<source>`
64. `<track>`

---

#### ১১. Table Tags

Table তৈরি করার জন্য ব্যবহৃত হয়।

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

---

#### ১২. Form Tags

User Input গ্রহণ করার জন্য Form তৈরি করতে ব্যবহৃত হয়।

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

---

#### ১৩. Semantic Layout Tags

Web Page-এর অর্থপূর্ণ (Semantic) Layout তৈরি করতে ব্যবহৃত হয়।

89. `<header></header>`
90. `<nav></nav>`
91. `<main></main>`
92. `<section></section>`
93. `<article></article>`
94. `<aside></aside>`
95. `<footer></footer>`
96. `<address></address>`

---

#### ১৪. Interactive Tags

Interactive UI তৈরির জন্য ব্যবহৃত হয়।

97. `<details></details>`
98. `<summary></summary>`
99. `<dialog></dialog>`

---

#### ১৫. Embedded Content Tags

অন্য Content বা Resource Embed করার জন্য ব্যবহৃত হয়।

100. `<iframe></iframe>`
101. `<embed>`
102. `<object></object>`
103. `<param>`

---

#### ১৬. Graphics Tags

Graphics এবং Drawing তৈরির জন্য ব্যবহৃত হয়।

104. `<canvas></canvas>`
105. `<svg></svg>`

---

#### ১৭. Web Components

Reusable Custom Component তৈরির জন্য ব্যবহৃত হয়।

106. `<template></template>`
107. `<slot></slot>`

---

#### ১৮. Ruby Annotation Tags

মূলত Japanese, Chinese এবং Korean ভাষার উচ্চারণ (Pronunciation) দেখানোর জন্য ব্যবহৃত হয়।

108. `<ruby></ruby>`
109. `<rt></rt>`
110. `<rp></rp>`

---

#### ১৯. Deprecated Tags

এই Tag-গুলো HTML5-এ আর ব্যবহার করার পরামর্শ দেওয়া হয় না।

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

### HTML Tag শেখা কেন গুরুত্বপূর্ণ?

* HTML Document তৈরি করতে সাহায্য করে।
* Web Page-এর Structure নির্ধারণ করে।
* CSS Styling প্রয়োগ করা সহজ হয়।
* JavaScript দিয়ে Element নিয়ন্ত্রণ করা যায়।
* SEO উন্নত করতে Semantic Tag গুরুত্বপূর্ণ।
* Responsive ও Accessible Website তৈরিতে সহায়তা করে।

---

### HTML Tag বনাম HTML Element

| HTML Tag                     | HTML Element                        |
| ---------------------------- | ----------------------------------- |
| একটি নির্দেশনা (Instruction) | একটি সম্পূর্ণ গঠন (Structure)       |
| `<p>`                        | `<p>Hello World</p>`                |
| `<img>`                      | `<img src="image.jpg" alt="Image">` |

---

### মনে রাখার বিষয়

* সব Tag-এর নির্দিষ্ট উদ্দেশ্য রয়েছে।
* বেশিরভাগ Tag-এর Opening ও Closing অংশ থাকে।
* কিছু Tag Empty (Void Tag), যেমন: `<br>`, `<img>`, `<meta>`।
* HTML5-এ Semantic Tag ব্যবহার করা ভালো অভ্যাস।
* Deprecated Tag-এর পরিবর্তে আধুনিক Tag ও CSS ব্যবহার করা উচিত।

---

### সারসংক্ষেপ

HTML Tags হলো HTML-এর মূল ভিত্তি। প্রতিটি Tag Browser-কে নির্দেশ দেয় কোনো Content কীভাবে প্রদর্শিত হবে। HTML Tags-কে বিভিন্ন Category-তে ভাগ করা হয়, যেমন Document, Metadata, Heading, Content, Formatting, Lists, Tables, Forms, Semantic Layout, Multimedia ইত্যাদি। একজন দক্ষ Frontend Developer হওয়ার জন্য প্রতিটি Tag-এর কাজ, ব্যবহার এবং সঠিক Syntax সম্পর্কে পরিষ্কার ধারণা থাকা অত্যন্ত গুরুত্বপূর্ণ।






## 1. HTML Document Tags

HTML Document Tags হলো একটি HTML Document-এর **মৌলিক কাঠামো (Basic Structure)** তৈরি করার জন্য ব্যবহৃত Tag ও Declaration। Browser একটি Web Page সঠিকভাবে বুঝতে এবং প্রদর্শন করতে এই অংশগুলোর উপর নির্ভর করে।

একটি HTML Document-এর শুরু থেকে শেষ পর্যন্ত যে মূল Structure থাকে, সেটিই HTML Document Tags দ্বারা গঠিত।

---

### HTML Document-এর মৌলিক কাঠামো

```html
<!DOCTYPE html>
<html>
    <head>
        <title>My Website</title>
    </head>

    <body>

    </body>
</html>
```

উপরের Code-টি একটি সম্পূর্ণ HTML Document-এর Basic Structure।

---

### HTML Document Tags-এর তালিকা

| নং | Tag               | কাজ                                         |
| -- | ----------------- | ------------------------------------------- |
| 1  | `<!DOCTYPE html>` | Browser-কে জানায় এটি HTML5 Document        |
| 2  | `<html></html>`   | সম্পূর্ণ HTML Document-এর Root Element      |
| 3  | `<head></head>`   | Metadata ও Document সম্পর্কিত তথ্য ধারণ করে |
| 4  | `<title></title>` | Browser Tab-এর Title নির্ধারণ করে           |
| 5  | `<body></body>`   | Web Page-এর দৃশ্যমান Content ধারণ করে       |

---

### HTML Document Structure

```text
<!DOCTYPE html>
        │
        ▼
     <html>
      │
      ├───────────────┐
      ▼               ▼
   <head>          <body>
      │
      ▼
   <title>
```

---

### প্রতিটি Tag-এর সংক্ষিপ্ত পরিচয়

#### 1. `<!DOCTYPE html>`

* এটি একটি **Document Type Declaration (DTD)**।
* Browser-কে জানায় যে Documentটি HTML5 Standard অনুসরণ করে লেখা হয়েছে।
* HTML File-এর প্রথম লাইনে লেখা হয়।
* এটি কোনো HTML Tag নয়।

---

#### 2. `<html></html>`

* এটি HTML Document-এর **Root Element**।
* পুরো HTML Document এই Tag-এর ভিতরে থাকে।
* `<head>` এবং `<body>` এই Tag-এর Child Element।

---

#### 3. `<head></head>`

* Document-এর Metadata সংরক্ষণ করে।
* এই অংশের তথ্য Browser ব্যবহার করে, কিন্তু ব্যবহারকারী Web Page-এ সরাসরি দেখতে পায় না।
* এখানে সাধারণত `<meta>`, `<link>`, `<style>`, `<script>` এবং `<title>` থাকে।

---

#### 4. `<title></title>`

* Browser Tab-এর নাম নির্ধারণ করে।
* Search Engine Optimization (SEO)-এর জন্য গুরুত্বপূর্ণ।
* Bookmark এবং Search Result-এও এই Title ব্যবহৃত হয়।

---

#### 5. `<body></body>`

* ব্যবহারকারীর সামনে দৃশ্যমান (Visible) সব Content এখানে লেখা হয়।
* যেমন—

  * Heading
  * Paragraph
  * Image
  * Table
  * Form
  * Button
  * Video
  * Audio

---

### Browser কীভাবে HTML Document পড়ে?

Browser সাধারণত নিচের ক্রম অনুসরণ করে HTML Document পড়ে—

```text
1. <!DOCTYPE html>
        │
2. <html>
        │
3. <head>
        │
4. <title>
        │
5. <body>
        │
6. Render Web Page
```

---

### HTML Document Tags-এর গুরুত্ব

* HTML Document-এর মূল কাঠামো তৈরি করে।
* Browser-কে Document সঠিকভাবে বুঝতে সাহায্য করে।
* HTML, CSS এবং JavaScript সঠিকভাবে কাজ করতে সহায়তা করে।
* SEO এবং Browser Compatibility উন্নত করে।
* একটি Standard Web Page তৈরির ভিত্তি হিসেবে কাজ করে।

---

### বাস্তব উদাহরণ

ধরুন, একটি **বই** কল্পনা করুন।

| HTML Tag          | বইয়ের সাথে তুলনা                    |
| ----------------- | ------------------------------------ |
| `<!DOCTYPE html>` | বইটির ধরন (যেমন: বিজ্ঞান, উপন্যাস)   |
| `<html>`          | পুরো বই                              |
| `<head>`          | বইয়ের তথ্য (শিরোনাম, লেখক, প্রকাশক) |
| `<title>`         | বইয়ের নাম                           |
| `<body>`          | বইয়ের মূল লেখা                      |

---

### সারসংক্ষেপ

HTML Document Tags একটি HTML Document-এর ভিত্তি (Foundation) তৈরি করে। `<!DOCTYPE html>` Browser-কে HTML Version জানায়, `<html>` পুরো Document ধারণ করে, `<head>` Metadata সংরক্ষণ করে, `<title>` Browser Tab-এর নাম নির্ধারণ করে এবং `<body>` ব্যবহারকারীর সামনে দৃশ্যমান সব Content ধারণ করে। এই পাঁচটি অংশ সম্পর্কে পরিষ্কার ধারণা থাকলে HTML শেখার পরবর্তী ধাপগুলো অনেক সহজ হয়ে যায়।






## 2. Metadata Tags

Metadata Tags হলো HTML-এর এমন কিছু বিশেষ Tag, যা **Web Page সম্পর্কে অতিরিক্ত তথ্য (Metadata)** সংরক্ষণ করে। এই তথ্যগুলো সাধারণত Browser, Search Engine, Social Media এবং অন্যান্য Web Service ব্যবহার করে। ব্যবহারকারী (User) সাধারণত এই তথ্যগুলো Web Page-এ সরাসরি দেখতে পায় না।

Metadata Tags সাধারণত **`<head>`** Section-এর ভিতরে লেখা হয় এবং একটি Web Page সঠিকভাবে লোড, প্রদর্শন ও Search Engine-এ Index হতে গুরুত্বপূর্ণ ভূমিকা পালন করে।

---

### Metadata কী?

**Metadata** শব্দের অর্থ হলো **"Data about Data"**, অর্থাৎ কোনো তথ্য সম্পর্কে অতিরিক্ত তথ্য।

উদাহরণস্বরূপ—

* Web Page-এর Character Encoding
* Responsive Viewport
* Page Description
* Author-এর নাম
* CSS File
* JavaScript File
* Favicon
* Base URL

এসব তথ্য ব্যবহারকারী সরাসরি দেখতে না পেলেও Browser এবং Search Engine এগুলো ব্যবহার করে।

---

### Metadata Tags-এর মৌলিক কাঠামো

```html
<!DOCTYPE html>
<html>

<head>

    <meta charset="UTF-8">

    <meta name="viewport" content="width=device-width, initial-scale=1.0">

    <title>My Website</title>

    <link rel="stylesheet" href="style.css">

    <base href="https://example.com/">

    <style>

        body{
            font-family: Arial, sans-serif;
        }

    </style>

    <script src="script.js"></script>

    <noscript>
        Please Enable JavaScript.
    </noscript>

</head>

<body>

</body>

</html>
```

উপরের Code-এ `<head>` Section-এর ভিতরে বিভিন্ন Metadata Tag ব্যবহার করা হয়েছে।

---

### Metadata Tags-এর তালিকা

| নং | Tag                     | কাজ                                                |
| -- | ----------------------- | -------------------------------------------------- |
| 6  | `<meta>`                | Web Page-এর Metadata প্রদান করে                    |
| 7  | `<link>`                | External Resource (CSS, Favicon ইত্যাদি) যুক্ত করে |
| 8  | `<base>`                | Document-এর Base URL নির্ধারণ করে                  |
| 9  | `<style></style>`       | Internal CSS লিখতে ব্যবহৃত হয়                     |
| 10 | `<script></script>`     | JavaScript যুক্ত করতে ব্যবহৃত হয়                  |
| 11 | `<noscript></noscript>` | JavaScript বন্ধ থাকলে বিকল্প Content দেখায়        |

---

### Metadata Tags Structure

```text
<head>
   │
   ├── <meta>
   │
   ├── <link>
   │
   ├── <base>
   │
   ├── <style>
   │
   ├── <script>
   │
   └── <noscript>
```

---

### প্রতিটি Tag-এর সংক্ষিপ্ত পরিচয়

#### 6. `<meta>`

* Web Page সম্পর্কে অতিরিক্ত তথ্য প্রদান করে।
* Character Encoding, Viewport, Description, Keywords, Author ইত্যাদি নির্ধারণ করতে ব্যবহৃত হয়।
* Search Engine Optimization (SEO)-এর জন্য গুরুত্বপূর্ণ।
* এটি একটি **Void (Empty) Element**।

---

#### 7. `<link>`

* External Resource যুক্ত করার জন্য ব্যবহৃত হয়।
* সাধারণত CSS File, Favicon এবং Font যুক্ত করতে ব্যবহার করা হয়।
* Browser Page Load হওয়ার সময় এই Resource-গুলোও Load করে।
* এটিও একটি **Void (Empty) Element**।

---

#### 8. `<base>`

* Document-এর Base URL নির্ধারণ করে।
* Relative URL-গুলো এই Base URL অনুসারে কাজ করে।
* একটি HTML Document-এ সাধারণত একটি `<base>` Tag ব্যবহার করা হয়।

---

#### 9. `<style></style>`

* HTML File-এর ভিতরে Internal CSS লেখার জন্য ব্যবহৃত হয়।
* Web Page-এর Design এবং Appearance নিয়ন্ত্রণ করতে সাহায্য করে।
* সাধারণত `<head>` Section-এ লেখা হয়।

---

#### 10. `<script></script>`

* JavaScript Code অথবা External JavaScript File যুক্ত করতে ব্যবহৃত হয়।
* Web Page-এ বিভিন্ন Interactive Feature যোগ করতে সাহায্য করে।
* Internal এবং External—উভয় ধরনের JavaScript ব্যবহার করা যায়।

---

#### 11. `<noscript></noscript>`

* যদি Browser-এ JavaScript Disable থাকে, তাহলে এই Tag-এর ভিতরের Content প্রদর্শিত হয়।
* User-কে JavaScript চালু করার নির্দেশনা দিতেও এটি ব্যবহার করা হয়।

---

### Browser কীভাবে Metadata Tags পড়ে?

Browser সাধারণত নিচের ধাপগুলো অনুসরণ করে—

```text
HTML Document
      │
      ▼
Read <head>
      │
      ▼
Read Metadata Tags
      │
      ├── Character Encoding
      ├── Viewport
      ├── CSS
      ├── JavaScript
      ├── Base URL
      └── Other Metadata
      │
      ▼
Load & Render Web Page
```

Browser প্রথমে `<head>` Section-এর Metadata পড়ে, তারপর Web Page Render করা শুরু করে।

---

### Metadata Tags-এর গুরুত্ব

* Browser-কে Web Page সম্পর্কে গুরুত্বপূর্ণ তথ্য প্রদান করে।
* Character Encoding সঠিকভাবে নির্ধারণ করে।
* Responsive Website তৈরি করতে সাহায্য করে।
* CSS এবং JavaScript যুক্ত করে।
* SEO উন্নত করতে সহায়তা করে।
* Browser Compatibility বৃদ্ধি করে।
* Social Media Preview-এর জন্য তথ্য প্রদান করতে পারে।
* Favicon এবং অন্যান্য External Resource যুক্ত করতে ব্যবহৃত হয়।

---

### বাস্তব উদাহরণ

ধরুন, একটি **বই** কল্পনা করুন।

| Metadata Tag | বইয়ের সাথে তুলনা                           |
| ------------ | ------------------------------------------- |
| `<meta>`     | বইয়ের ভাষা, সংস্করণ ও প্রকাশনার তথ্য       |
| `<link>`     | বইয়ের অতিরিক্ত সংযুক্তি বা রেফারেন্স       |
| `<base>`     | বইয়ের মূল উৎস বা ভিত্তি                    |
| `<style>`    | বইয়ের ডিজাইন ও ফরম্যাট                     |
| `<script>`   | বইয়ের সাথে থাকা ইন্টারঅ্যাকটিভ ডিজিটাল অংশ |
| `<noscript>` | বিশেষ পরিস্থিতিতে অতিরিক্ত নির্দেশনা        |

বইয়ের মূল গল্প শুরু হওয়ার আগে যেমন কিছু গুরুত্বপূর্ণ তথ্য থাকে, তেমনি একটি Web Page-এর মূল Content-এর আগে Metadata Tags গুরুত্বপূর্ণ তথ্য সংরক্ষণ করে।

---

### সারসংক্ষেপ

Metadata Tags হলো HTML Document-এর এমন কিছু গুরুত্বপূর্ণ Tag, যা Browser, Search Engine এবং অন্যান্য Web Service-কে Web Page সম্পর্কে অতিরিক্ত তথ্য প্রদান করে। এগুলো সাধারণত `<head>` Section-এর ভিতরে থাকে এবং Character Encoding, Responsive Design, CSS, JavaScript, Base URL, SEO এবং অন্যান্য গুরুত্বপূর্ণ তথ্য পরিচালনা করে। একটি Professional ও Standard HTML Document তৈরির জন্য Metadata Tags সম্পর্কে পরিষ্কার ধারণা থাকা অত্যন্ত গুরুত্বপূর্ণ।






## 3. Heading Tags

Heading Tags হলো HTML-এর এমন কিছু Tag, যা একটি Web Page-এর **শিরোনাম (Heading)** এবং **উপশিরোনাম (Subheading)** তৈরি করতে ব্যবহৃত হয়। এগুলো Content-কে সুশৃঙ্খল (Structured), সহজে পড়ার উপযোগী এবং অর্থপূর্ণ (Semantic) করে তোলে।

Heading Tags শুধুমাত্র Text বড় বা ছোট করার জন্য নয়, বরং একটি Web Page-এর **Structure**, **SEO (Search Engine Optimization)** এবং **Accessibility** উন্নত করার জন্যও অত্যন্ত গুরুত্বপূর্ণ।

HTML-এ মোট **৬টি Heading Tag** রয়েছে, যা `<h1>` থেকে `<h6>` পর্যন্ত।

---

### Heading Tag কী?

Heading Tag হলো এমন একটি HTML Element, যা কোনো Section, Topic অথবা Content-এর শিরোনাম প্রকাশ করে।

Browser প্রতিটি Heading-এর গুরুত্ব (Importance) অনুযায়ী আলাদা আকারে (Size) প্রদর্শন করে। `<h1>` সবচেয়ে গুরুত্বপূর্ণ এবং `<h6>` সবচেয়ে কম গুরুত্বপূর্ণ Heading।

---

### Heading Tags-এর মৌলিক কাঠামো

```html
<!DOCTYPE html>
<html>

<head>
    <title>HTML Heading Tags</title>
</head>

<body>

    <h1>Main Heading</h1>

    <h2>Sub Heading</h2>

    <h3>Section Heading</h3>

    <h4>Sub Section</h4>

    <h5>Small Heading</h5>

    <h6>Smallest Heading</h6>

</body>

</html>
```

উপরের Code-এ HTML-এর ৬টি Heading Tag ব্যবহার করা হয়েছে।

---

### Heading Tags-এর তালিকা

| নং | Tag         | গুরুত্ব (Importance) |
| -- | ----------- | -------------------- |
| 12 | `<h1></h1>` | সর্বোচ্চ (Highest)   |
| 13 | `<h2></h2>` | দ্বিতীয়             |
| 14 | `<h3></h3>` | তৃতীয়               |
| 15 | `<h4></h4>` | চতুর্থ               |
| 16 | `<h5></h5>` | পঞ্চম                |
| 17 | `<h6></h6>` | সর্বনিম্ন (Lowest)   |

---

### Heading Structure

```text
<h1> Main Title
      │
      ├── <h2> Main Section
      │      │
      │      ├── <h3> Sub Section
      │      │      │
      │      │      ├── <h4> Topic
      │      │      │      │
      │      │      │      ├── <h5> Sub Topic
      │      │      │      │      │
      │      │      │      │      └── <h6> Details
```

এই Structure দেখায় যে Heading Tag-গুলো একটি Hierarchy তৈরি করে।

---

### প্রতিটি Tag-এর সংক্ষিপ্ত পরিচয়

#### 12. `<h1></h1>`

* সবচেয়ে গুরুত্বপূর্ণ Heading।
* সাধারণত একটি Page-এর মূল শিরোনাম (Main Title) হিসেবে ব্যবহৃত হয়।
* একটি Page-এ সাধারণত একটি `<h1>` ব্যবহার করাই ভালো অভ্যাস।

---

#### 13. `<h2></h2>`

* প্রধান Section-এর Heading হিসেবে ব্যবহৃত হয়।
* `<h1>`-এর অধীনে বিভিন্ন বড় Section ভাগ করতে সাহায্য করে।

---

#### 14. `<h3></h3>`

* `<h2>`-এর উপ-অংশ (Sub Section) তৈরি করতে ব্যবহৃত হয়।
* Content-কে আরও ছোট ছোট ভাগে বিভক্ত করে।

---

#### 15. `<h4></h4>`

* `<h3>`-এর অধীনে আরও বিস্তারিত বিষয় (Topic) প্রদর্শন করে।
* সাধারণত বড় Document-এ ব্যবহার করা হয়।

---

#### 16. `<h5></h5>`

* ছোট Sub Topic বা অতিরিক্ত তথ্যের Heading হিসেবে ব্যবহৃত হয়।
* খুব বেশি ব্যবহার করা হয় না, তবে প্রয়োজন অনুযায়ী কাজে লাগে।

---

#### 17. `<h6></h6>`

* সবচেয়ে কম গুরুত্বপূর্ণ Heading।
* অতিরিক্ত বিস্তারিত বা ছোট Section-এর জন্য ব্যবহৃত হয়।

---

### Browser কীভাবে Heading Tags পড়ে?

Browser সাধারণত নিচের ধাপগুলো অনুসরণ করে—

```text
HTML Document
      │
      ▼
Read Heading Tag
      │
      ▼
Determine Heading Level
      │
      ▼
Apply Default Style
      │
      ▼
Display Heading
```

Browser প্রতিটি Heading-এর গুরুত্ব অনুযায়ী Default Font Size এবং Font Weight প্রয়োগ করে।

---

### Heading Tags-এর গুরুত্ব

* Web Page-এর Structure তৈরি করে।
* বড় Content-কে ছোট ছোট Section-এ ভাগ করে।
* Search Engine-কে Page বুঝতে সাহায্য করে।
* SEO উন্নত করে।
* Accessibility বৃদ্ধি করে।
* Screen Reader ব্যবহারকারীদের Page Navigation সহজ করে।
* User Experience (UX) উন্নত করে।

---

### বাস্তব উদাহরণ

ধরুন একটি **বই** কল্পনা করুন।

| Heading Tag | বইয়ের সাথে তুলনা       |
| ----------- | ----------------------- |
| `<h1>`      | বইয়ের নাম              |
| `<h2>`      | অধ্যায় (Chapter)       |
| `<h3>`      | অধ্যায়ের বিষয়         |
| `<h4>`      | উপ-বিষয়                |
| `<h5>`      | ছোট Topic               |
| `<h6>`      | অতিরিক্ত বিস্তারিত তথ্য |

যেমন একটি বইয়ে অধ্যায়, উপ-অধ্যায় এবং বিষয় থাকে, ঠিক তেমনি একটি Website-এ Heading Tag ব্যবহার করে Content সাজানো হয়।

---

### সারসংক্ষেপ

Heading Tags HTML-এর অন্যতম গুরুত্বপূর্ণ Structural Element। এগুলো একটি Web Page-এর শিরোনাম এবং উপশিরোনাম তৈরি করে, Content-কে অর্থপূর্ণভাবে সাজায় এবং SEO ও Accessibility উন্নত করে। HTML-এ মোট ৬টি Heading Tag (`<h1>` থেকে `<h6>`) রয়েছে, যেখানে `<h1>` সবচেয়ে গুরুত্বপূর্ণ এবং `<h6>` সবচেয়ে কম গুরুত্বপূর্ণ। একটি Professional Web Page তৈরির জন্য Heading-এর Hierarchy সঠিকভাবে অনুসরণ করা অত্যন্ত গুরুত্বপূর্ণ।






## 4. Basic Content Tags

Basic Content Tags হলো HTML-এর এমন কিছু গুরুত্বপূর্ণ Tag, যা একটি Web Page-এর **মূল Content (Main Content)** তৈরি, সাজানো এবং প্রদর্শনের জন্য ব্যবহৃত হয়। Paragraph লেখা, বিভিন্ন Content Group করা, নতুন Line তৈরি করা, Section আলাদা করা এবং নির্দিষ্ট Format-এ Text প্রদর্শনের জন্য এই Tag-গুলো ব্যবহার করা হয়।

HTML শেখার সময় এই Tag-গুলো সবচেয়ে বেশি ব্যবহৃত হয় এবং প্রায় প্রতিটি Website-এ এদের ব্যবহার দেখা যায়।

---

### Basic Content Tag কী?

Basic Content Tag হলো এমন একটি HTML Element, যা Web Page-এর সাধারণ Content তৈরি এবং Content-এর Structure নির্ধারণ করতে সাহায্য করে।

এই Tag-গুলোর মাধ্যমে Text, Paragraph, Layout, Line Break, Horizontal Line এবং Preformatted Text তৈরি করা যায়।

---

### Basic Content Tags-এর মৌলিক কাঠামো

```html
<!DOCTYPE html>
<html>

<head>
    <title>Basic Content Tags</title>
</head>

<body>

    <p>This is a paragraph.</p>

    <div>
        <span>Welcome to HTML</span>
    </div>

    First Line <br>
    Second Line

    <hr>

    <pre>
Name    : Hasan
Country : Bangladesh
Age     : 20
    </pre>

</body>

</html>
```

উপরের Code-এ HTML-এর Basic Content Tags ব্যবহার করা হয়েছে।

---

### Basic Content Tags-এর তালিকা

| নং | Tag             | কাজ                                         |
| -- | --------------- | ------------------------------------------- |
| 18 | `<p></p>`       | Paragraph তৈরি করে                          |
| 19 | `<div></div>`   | Block Level Section বা Container তৈরি করে   |
| 20 | `<span></span>` | Inline Content Group করে                    |
| 21 | `<br>`          | নতুন Line (Line Break) তৈরি করে             |
| 22 | `<hr>`          | অনুভূমিক রেখা (Horizontal Rule) তৈরি করে    |
| 23 | `<pre></pre>`   | নির্দিষ্ট Format অনুযায়ী Text প্রদর্শন করে |

---

### Basic Content Tags Structure

```text
<body>
   │
   ├── <p>
   │
   ├── <div>
   │      │
   │      └── <span>
   │
   ├── <br>
   │
   ├── <hr>
   │
   └── <pre>
```

এই Structure দেখায় যে `<body>`-এর ভিতরে বিভিন্ন ধরনের Basic Content Tag ব্যবহার করা হয়।

---

### প্রতিটি Tag-এর সংক্ষিপ্ত পরিচয়

#### 18. `<p></p>`

* Paragraph বা অনুচ্ছেদ তৈরি করতে ব্যবহৃত হয়।
* Text-কে আলাদা Paragraph হিসেবে Browser-এ প্রদর্শন করে।
* Browser স্বয়ংক্রিয়ভাবে Paragraph-এর আগে ও পরে কিছু Margin যোগ করে।

---

#### 19. `<div></div>`

* একটি **Block Level Container**।
* একাধিক HTML Element-কে Group করার জন্য ব্যবহৃত হয়।
* CSS Layout এবং JavaScript-এর সাথে সবচেয়ে বেশি ব্যবহৃত Tag-গুলোর একটি।

---

#### 20. `<span></span>`

* একটি **Inline Container**।
* Text বা ছোট Inline Content Group করতে ব্যবহৃত হয়।
* সাধারণত CSS Styling এবং JavaScript Manipulation-এর জন্য ব্যবহার করা হয়।

---

#### 21. `<br>`

* নতুন Line (Line Break) তৈরি করে।
* এটি একটি **Void (Empty) Element**।
* Closing Tag থাকে না।

---

#### 22. `<hr>`

* একটি অনুভূমিক রেখা (Horizontal Rule) প্রদর্শন করে।
* দুটি Section বা বিষয়কে আলাদা করতে ব্যবহৃত হয়।
* এটিও একটি **Void (Empty) Element**।

---

#### 23. `<pre></pre>`

* Preformatted Text প্রদর্শনের জন্য ব্যবহৃত হয়।
* Space, Tab এবং Line Break যেভাবে লেখা হয়, Browser ঠিক সেভাবেই প্রদর্শন করে।
* Code, ASCII Art বা নির্দিষ্ট Format-এর Text দেখানোর জন্য উপযোগী।

---

### Browser কীভাবে Basic Content Tags পড়ে?

Browser সাধারণত নিচের ধাপগুলো অনুসরণ করে—

```text
HTML Document
      │
      ▼
Read <body>
      │
      ▼
Identify Basic Content Tag
      │
      ▼
Render According to Tag
      │
      ▼
Display Web Page
```

Browser প্রতিটি Tag-এর ধরন অনুযায়ী আলাদা Style এবং Layout প্রয়োগ করে।

---

### Basic Content Tags-এর গুরুত্ব

* Web Page-এর মূল Content তৈরি করে।
* Paragraph এবং Text সুন্দরভাবে প্রদর্শন করে।
* Content-কে বিভিন্ন Section-এ ভাগ করতে সাহায্য করে।
* Layout তৈরির ভিত্তি তৈরি করে।
* CSS এবং JavaScript ব্যবহার সহজ করে।
* Website-কে আরও সুশৃঙ্খল এবং পাঠযোগ্য করে।

---

### Block Level এবং Inline Element

Basic Content Tags-এর মধ্যে কিছু Block Level এবং কিছু Inline Element রয়েছে।

| Tag      | Element Type               |
| -------- | -------------------------- |
| `<p>`    | Block Level                |
| `<div>`  | Block Level                |
| `<span>` | Inline                     |
| `<br>`   | Inline (Void Element)      |
| `<hr>`   | Block Level (Void Element) |
| `<pre>`  | Block Level                |

---

### বাস্তব উদাহরণ

ধরুন আপনি একটি **সংবাদপত্র** পড়ছেন।

| HTML Tag | সংবাদপত্রের সাথে তুলনা                     |
| -------- | ------------------------------------------ |
| `<p>`    | একটি অনুচ্ছেদ                              |
| `<div>`  | একটি সম্পূর্ণ সংবাদ বিভাগ                  |
| `<span>` | একটি নির্দিষ্ট শব্দ বা বাক্য Highlight করা |
| `<br>`   | নতুন লাইন শুরু                             |
| `<hr>`   | দুটি সংবাদের মাঝে বিভাজন রেখা              |
| `<pre>`  | নির্দিষ্ট Format-এ তথ্য বা তালিকা          |

যেভাবে একটি সংবাদপত্র বিভিন্ন অংশে ভাগ করা থাকে, ঠিক তেমনি HTML-এর Basic Content Tags Web Page-এর Content সাজাতে সাহায্য করে।

---

### সারসংক্ষেপ

Basic Content Tags HTML-এর সবচেয়ে বেশি ব্যবহৃত Tag-গুলোর একটি গুরুত্বপূর্ণ Group। এগুলোর মাধ্যমে Paragraph, Block Container, Inline Content, Line Break, Horizontal Line এবং Preformatted Text তৈরি করা যায়। `<p>`, `<div>`, `<span>`, `<br>`, `<hr>` এবং `<pre>` Tag সম্পর্কে ভালো ধারণা থাকলে HTML দিয়ে যেকোনো Web Page-এর মূল Content সহজেই তৈরি করা যায়। এগুলো Frontend Development-এর ভিত্তি হিসেবে কাজ করে।






## 5. Text Formatting Tags

Text Formatting Tags হলো HTML-এর এমন কিছু Tag, যা **Text-এর Appearance (দেখতে কেমন হবে), Meaning (অর্থ), Importance (গুরুত্ব)** এবং **Presentation (উপস্থাপন)** নির্ধারণ করতে ব্যবহৃত হয়। এগুলোর মাধ্যমে Text-কে **Bold, Italic, Underline, Highlight, Small, Subscript, Superscript, Deleted, Inserted** ইত্যাদি বিভিন্নভাবে প্রদর্শন করা যায়।

কিছু Tag শুধুমাত্র Text-এর **Style** পরিবর্তন করে, আবার কিছু Tag Text-এর **Semantic Meaning (অর্থপূর্ণ গুরুত্ব)** প্রকাশ করে। তাই সঠিক Tag নির্বাচন করা HTML, SEO এবং Accessibility-এর জন্য গুরুত্বপূর্ণ।

---

### Text Formatting Tag কী?

Text Formatting Tag হলো এমন একটি HTML Element, যা কোনো Text-এর **রূপ (Formatting)**, **গুরুত্ব (Importance)** অথবা **বিশেষ অর্থ (Semantic Meaning)** প্রকাশ করে।

এই Tag-গুলোর মাধ্যমে Browser বুঝতে পারে কোন Text গুরুত্বপূর্ণ, কোনটি উদ্ধৃত, কোনটি কোড, কোনটি কীবোর্ড ইনপুট বা কোনটি পরিবর্তিত হয়েছে।

---

### Text Formatting Tags-এর মৌলিক কাঠামো

```html id="k8wz1n"
<!DOCTYPE html>
<html>

<head>
    <title>Text Formatting Tags</title>
</head>

<body>

    <b>Bold Text</b><br>

    <strong>Important Text</strong><br>

    <i>Italic Text</i><br>

    <em>Emphasized Text</em><br>

    <u>Underlined Text</u><br>

    <mark>Highlighted Text</mark><br>

    <small>Small Text</small><br>

    H<sub>2</sub>O<br>

    X<sup>2</sup><br>

    <del>Deleted Text</del><br>

    <ins>Inserted Text</ins><br>

    <s>No Longer Valid</s><br>

    <code>console.log("Hello");</code><br>

    Press <kbd>Ctrl + C</kbd><br>

    <samp>Hello World</samp><br>

    <var>x</var> = 10

</body>

</html>
```

উপরের Code-এ HTML-এর বিভিন্ন Text Formatting Tag ব্যবহার করা হয়েছে।

---

### Text Formatting Tags-এর তালিকা

| নং | Tag                 | কাজ                               |
| -- | ------------------- | --------------------------------- |
| 24 | `<b></b>`           | Text Bold করে                     |
| 25 | `<strong></strong>` | গুরুত্বপূর্ণ Text নির্দেশ করে     |
| 26 | `<i></i>`           | Italic Text প্রদর্শন করে          |
| 27 | `<em></em>`         | গুরুত্বসহ Italic Text দেখায়      |
| 28 | `<u></u>`           | Text-এর নিচে দাগ (Underline) দেয় |
| 29 | `<mark></mark>`     | Text Highlight করে                |
| 30 | `<small></small>`   | ছোট আকারের Text প্রদর্শন করে      |
| 31 | `<sub></sub>`       | Subscript Text দেখায়             |
| 32 | `<sup></sup>`       | Superscript Text দেখায়           |
| 33 | `<del></del>`       | মুছে ফেলা Text নির্দেশ করে        |
| 34 | `<ins></ins>`       | নতুন যোগ করা Text নির্দেশ করে     |
| 35 | `<s></s>`           | আর প্রযোজ্য নয় এমন Text দেখায়   |
| 36 | `<code></code>`     | Computer Code প্রদর্শন করে        |
| 37 | `<kbd></kbd>`       | Keyboard Input নির্দেশ করে        |
| 38 | `<samp></samp>`     | Program Output দেখায়             |
| 39 | `<var></var>`       | Variable নির্দেশ করে              |

---

### Text Formatting Tags Structure

```text id="5yqfcb"
Text
 │
 ├── <b>
 ├── <strong>
 ├── <i>
 ├── <em>
 ├── <u>
 ├── <mark>
 ├── <small>
 ├── <sub>
 ├── <sup>
 ├── <del>
 ├── <ins>
 ├── <s>
 ├── <code>
 ├── <kbd>
 ├── <samp>
 └── <var>
```

---

### প্রতিটি Tag-এর সংক্ষিপ্ত পরিচয়

#### 24. `<b></b>`

* Text-কে **Bold** করে।
* শুধুমাত্র Appearance পরিবর্তন করে।
* Semantic Meaning প্রকাশ করে না।

---

#### 25. `<strong></strong>`

* গুরুত্বপূর্ণ (Important) Text নির্দেশ করে।
* Browser সাধারণত Bold করে দেখায়।
* SEO এবং Accessibility-এর জন্য গুরুত্বপূর্ণ।

---

#### 26. `<i></i>`

* Text-কে Italic আকারে প্রদর্শন করে।
* সাধারণত বিদেশি শব্দ, বইয়ের নাম বা বিশেষ শব্দের জন্য ব্যবহৃত হয়।

---

#### 27. `<em></em>`

* কোনো Text-এর ওপর বিশেষ গুরুত্ব (Emphasis) প্রকাশ করে।
* Browser সাধারণত Italic করে দেখায়।
* Semantic Meaning বহন করে।

---

#### 28. `<u></u>`

* Text-এর নিচে Underline দেয়।
* গুরুত্বপূর্ণ বা আলাদা করে দেখানোর জন্য ব্যবহার করা যায়।

---

#### 29. `<mark></mark>`

* Text Highlight করে।
* Browser সাধারণত হলুদ Background দিয়ে দেখায়।

---

#### 30. `<small></small>`

* ছোট আকারের Text প্রদর্শন করে।
* Copyright, Disclaimer বা Note লেখার জন্য ব্যবহৃত হয়।

---

#### 31. `<sub></sub>`

* Subscript Text তৈরি করে।
* যেমন: H₂O, CO₂।

---

#### 32. `<sup></sup>`

* Superscript Text তৈরি করে।
* যেমন: x², 10³।

---

#### 33. `<del></del>`

* মুছে ফেলা বা বাতিল করা Text নির্দেশ করে।
* Browser সাধারণত মাঝখানে দাগ (Strike-through) দেয়।

---

#### 34. `<ins></ins>`

* নতুন যোগ করা Text নির্দেশ করে।
* Browser সাধারণত Underline করে দেখায়।

---

#### 35. `<s></s>`

* আর প্রযোজ্য নয় বা অকার্যকর Text নির্দেশ করে।
* সাধারণত পুরোনো দাম বা তথ্য দেখাতে ব্যবহৃত হয়।

---

#### 36. `<code></code>`

* Computer Code প্রদর্শনের জন্য ব্যবহৃত হয়।
* Browser সাধারণত Monospace Font ব্যবহার করে।

---

#### 37. `<kbd></kbd>`

* Keyboard Input নির্দেশ করে।
* যেমন: **Ctrl + C**, **Enter**, **Shift**।

---

#### 38. `<samp></samp>`

* Program বা Computer-এর Output প্রদর্শন করে।

---

#### 39. `<var></var>`

* Variable বা গণিত/Programming-এর চলক নির্দেশ করে।
* Browser সাধারণত Italic আকারে দেখায়।

---

### Browser কীভাবে Text Formatting Tags পড়ে?

```text id="jlwm9q"
HTML Document
      │
      ▼
Read Formatting Tag
      │
      ▼
Determine Meaning
      │
      ▼
Apply Default Style
      │
      ▼
Display Formatted Text
```

Browser প্রতিটি Tag-এর Semantic Meaning এবং Default Style অনুযায়ী Text প্রদর্শন করে।

---

### Text Formatting Tags-এর গুরুত্ব

* Text আরও সুন্দর ও পাঠযোগ্য করে।
* গুরুত্বপূর্ণ তথ্য আলাদা করে তুলে ধরে।
* SEO উন্নত করতে সাহায্য করে।
* Accessibility বৃদ্ধি করে।
* Code, Keyboard Input এবং Variable আলাদা করে বোঝায়।
* User Experience (UX) উন্নত করে।

---

### বাস্তব উদাহরণ

ধরুন একটি **পাঠ্যবই** কল্পনা করুন।

| HTML Tag   | বইয়ের সাথে তুলনা            |
| ---------- | ---------------------------- |
| `<b>`      | মোটা অক্ষরের লেখা            |
| `<strong>` | গুরুত্বপূর্ণ সতর্কবার্তা     |
| `<i>`      | বিদেশি শব্দ বা বইয়ের নাম    |
| `<em>`     | জোর দিয়ে বলা বাক্য          |
| `<u>`      | দাগ দিয়ে চিহ্নিত অংশ        |
| `<mark>`   | হাইলাইট করা তথ্য             |
| `<small>`  | ফুটনোট বা ছোট লেখা           |
| `<sub>`    | রাসায়নিক সূত্র              |
| `<sup>`    | গণিতের সূচক                  |
| `<del>`    | কেটে দেওয়া লেখা             |
| `<ins>`    | নতুন যোগ করা লেখা            |
| `<s>`      | পুরোনো তথ্য                  |
| `<code>`   | প্রোগ্রামিং কোড              |
| `<kbd>`    | কীবোর্ড নির্দেশনা            |
| `<samp>`   | কম্পিউটারের আউটপুট           |
| `<var>`    | গণিত বা প্রোগ্রামিং Variable |

---

### সারসংক্ষেপ

Text Formatting Tags HTML-এর গুরুত্বপূর্ণ Tag Group, যা Text-এর রূপ, গুরুত্ব এবং অর্থ প্রকাশ করতে ব্যবহৃত হয়। HTML-এ মোট **১৬টি Text Formatting Tag** রয়েছে। কিছু Tag শুধুমাত্র Text-এর Style পরিবর্তন করে (যেমন `<b>`, `<i>`), আবার কিছু Tag Semantic Meaning প্রকাশ করে (যেমন `<strong>`, `<em>` )। এছাড়া `<code>`, `<kbd>`, `<samp>` এবং `<var>` প্রোগ্রামিং ও প্রযুক্তিগত লেখা প্রদর্শনের জন্য বিশেষভাবে ব্যবহৃত হয়। এই Tag-গুলোর সঠিক ব্যবহার একটি Professional, Accessible এবং SEO-Friendly Web Page তৈরিতে গুরুত্বপূর্ণ ভূমিকা পালন করে।






## 6. Quote & Reference Tags

Quote & Reference Tags হলো HTML-এর এমন কিছু Tag, যা **উদ্ধৃতি (Quote), রেফারেন্স (Reference), সংক্ষিপ্ত রূপ (Abbreviation), সংজ্ঞা (Definition), সময় (Time)** এবং **ডেটা (Data)** অর্থপূর্ণভাবে (Semantic) প্রদর্শন করতে ব্যবহৃত হয়।

এই Tag-গুলো শুধুমাত্র Text-এর Style পরিবর্তন করে না, বরং Browser, Search Engine এবং Screen Reader-কে Content-এর প্রকৃত অর্থ (Meaning) বুঝতে সাহায্য করে।

HTML-এ মোট **৭টি Quote & Reference Tag** রয়েছে।

---

### Quote & Reference Tag কী?

Quote & Reference Tag হলো এমন HTML Element, যা অন্য কোনো ব্যক্তি, বই, ওয়েবসাইট, গবেষণাপত্র বা উৎস (Source) থেকে নেওয়া তথ্য, সংক্ষিপ্ত রূপ, সংজ্ঞা, সময় এবং ডেটা অর্থপূর্ণভাবে প্রকাশ করতে ব্যবহৃত হয়।

এই Tag-গুলো HTML-এর **Semantic Elements**, অর্থাৎ এগুলো Content-এর অর্থ প্রকাশ করে।

---

### Quote & Reference Tags-এর মৌলিক কাঠামো

```html
<!DOCTYPE html>
<html>

<head>
    <title>Quote & Reference Tags</title>
</head>

<body>

    <blockquote>
        Learning never exhausts the mind.
    </blockquote>

    <p>
        <q>Knowledge is Power.</q>
    </p>

    <p>
        <cite>HTML & CSS Book</cite>
    </p>

    <p>
        <abbr title="HyperText Markup Language">HTML</abbr>
    </p>

    <p>
        <dfn>HTML</dfn> is a Markup Language.
    </p>

    <time datetime="2026-08-03">
        August 3, 2026
    </time>

    <br>

    <data value="101">
        Product ID
    </data>

</body>

</html>
```

উপরের Code-এ HTML-এর Quote & Reference Tags ব্যবহার করা হয়েছে।

---

### Quote & Reference Tags-এর তালিকা

| নং | Tag                         | কাজ                                                    |
| -- | --------------------------- | ------------------------------------------------------ |
| 40 | `<blockquote></blockquote>` | বড় উদ্ধৃতি (Block Quote) প্রদর্শন করে                 |
| 41 | `<q></q>`                   | ছোট উদ্ধৃতি (Inline Quote) প্রদর্শন করে                |
| 42 | `<cite></cite>`             | কোনো বই, চলচ্চিত্র, গবেষণা বা কাজের নাম নির্দেশ করে    |
| 43 | `<abbr></abbr>`             | সংক্ষিপ্ত রূপ (Abbreviation) নির্দেশ করে               |
| 44 | `<dfn></dfn>`               | কোনো শব্দের সংজ্ঞা (Definition) নির্দেশ করে            |
| 45 | `<time></time>`             | সময় ও তারিখ প্রকাশ করে                                |
| 46 | `<data></data>`             | মানুষের জন্য Text এবং Browser-এর জন্য Data সংরক্ষণ করে |

---

### Quote & Reference Tags Structure

```text
Text
 │
 ├── <blockquote>
 ├── <q>
 ├── <cite>
 ├── <abbr>
 ├── <dfn>
 ├── <time>
 └── <data>
```

---

### প্রতিটি Tag-এর সংক্ষিপ্ত পরিচয়

#### 40. `<blockquote></blockquote>`

* বড় উদ্ধৃতি (Long Quote) প্রদর্শনের জন্য ব্যবহৃত হয়।
* সাধারণত অন্য কোনো বই, ব্যক্তি বা Website থেকে নেওয়া উদ্ধৃতির জন্য ব্যবহার করা হয়।
* Browser এটিকে Block Level Element হিসেবে প্রদর্শন করে।

---

#### 41. `<q></q>`

* ছোট উদ্ধৃতি (Short Quote) প্রদর্শনের জন্য ব্যবহৃত হয়।
* Browser সাধারণত উদ্ধৃতির চারপাশে Quotation Mark (`" "`) যোগ করে।
* এটি একটি Inline Element।

---

#### 42. `<cite></cite>`

* কোনো বই, গবেষণাপত্র, সিনেমা, গান বা অন্য সৃজনশীল কাজের নাম নির্দেশ করে।
* সাধারণত Browser Italic Style-এ প্রদর্শন করে।
* এটি Author-এর নাম লেখার জন্য নয়, বরং কাজের (Work) নামের জন্য ব্যবহৃত হয়।

---

#### 43. `<abbr></abbr>`

* কোনো সংক্ষিপ্ত শব্দ (Abbreviation) বা Acronym বোঝাতে ব্যবহৃত হয়।
* `title` Attribute ব্যবহার করলে Mouse Hover করলে পূর্ণ অর্থ দেখা যায়।
* SEO এবং Accessibility-এর জন্য উপকারী।

---

#### 44. `<dfn></dfn>`

* কোনো নতুন শব্দ বা পরিভাষার সংজ্ঞা (Definition) নির্দেশ করে।
* সাধারণত প্রথমবার কোনো Technical Term পরিচয় করিয়ে দিতে ব্যবহার করা হয়।

---

#### 45. `<time></time>`

* সময় এবং তারিখ প্রকাশ করার জন্য ব্যবহৃত হয়।
* `datetime` Attribute-এর মাধ্যমে Machine-readable Date বা Time প্রদান করা যায়।
* Search Engine এবং Calendar Application এই তথ্য ব্যবহার করতে পারে।

---

#### 46. `<data></data>`

* মানুষের জন্য একটি Text এবং Browser-এর জন্য একটি নির্দিষ্ট Value সংরক্ষণ করে।
* `value` Attribute-এর মাধ্যমে প্রকৃত Data রাখা হয়।
* সাধারণত Product ID, Price বা Code প্রদর্শনের জন্য ব্যবহৃত হয়।

---

### Browser কীভাবে Quote & Reference Tags পড়ে?

```text
HTML Document
      │
      ▼
Read Quote & Reference Tag
      │
      ▼
Determine Semantic Meaning
      │
      ▼
Apply Default Style
      │
      ▼
Display Content
```

Browser প্রতিটি Tag-এর অর্থ (Semantic Meaning) অনুযায়ী Content প্রদর্শন করে এবং Search Engine-কে অতিরিক্ত তথ্য প্রদান করে।

---

### Quote & Reference Tags-এর গুরুত্ব

* উদ্ধৃতি সঠিকভাবে প্রদর্শন করে।
* Content-এর অর্থ (Semantic Meaning) প্রকাশ করে।
* SEO উন্নত করতে সাহায্য করে।
* Accessibility বৃদ্ধি করে।
* Browser এবং Search Engine-কে অতিরিক্ত তথ্য প্রদান করে।
* Date, Time এবং Reference সঠিকভাবে প্রকাশ করতে সহায়তা করে।

---

### Block Level এবং Inline Element

| Tag            | Element Type |
| -------------- | ------------ |
| `<blockquote>` | Block Level  |
| `<q>`          | Inline       |
| `<cite>`       | Inline       |
| `<abbr>`       | Inline       |
| `<dfn>`        | Inline       |
| `<time>`       | Inline       |
| `<data>`       | Inline       |

---

### বাস্তব উদাহরণ

ধরুন আপনি একটি **গবেষণাপত্র (Research Paper)** লিখছেন।

| HTML Tag       | গবেষণাপত্রের সাথে তুলনা          |
| -------------- | -------------------------------- |
| `<blockquote>` | বড় উদ্ধৃতি                      |
| `<q>`          | ছোট উদ্ধৃতি                      |
| `<cite>`       | বই বা গবেষণাপত্রের নাম           |
| `<abbr>`       | সংক্ষিপ্ত শব্দ (যেমন: HTML, CSS) |
| `<dfn>`        | নতুন শব্দের সংজ্ঞা               |
| `<time>`       | প্রকাশের তারিখ                   |
| `<data>`       | গবেষণার ID বা তথ্য               |

ঠিক যেভাবে একটি গবেষণাপত্রে উদ্ধৃতি, সংজ্ঞা এবং রেফারেন্স থাকে, HTML-এর Quote & Reference Tags সেই তথ্যগুলো অর্থপূর্ণভাবে প্রকাশ করে।

---

### সারসংক্ষেপ

Quote & Reference Tags HTML-এর গুরুত্বপূর্ণ **Semantic Tag Group**, যা উদ্ধৃতি, রেফারেন্স, সংজ্ঞা, সংক্ষিপ্ত রূপ, সময় এবং ডেটা অর্থপূর্ণভাবে উপস্থাপন করতে ব্যবহৃত হয়। HTML-এ মোট **৭টি Quote & Reference Tag** রয়েছে—`<blockquote>`, `<q>`, `<cite>`, `<abbr>`, `<dfn>`, `<time>` এবং `<data>`। এই Tag-গুলোর সঠিক ব্যবহার Web Page-কে আরও Professional, SEO-Friendly, Accessible এবং Semantic করে তোলে।






## 7. List Tags

List Tags হলো HTML-এর এমন কিছু Tag, যা **তথ্য, আইটেম বা ডেটাকে একটি তালিকা (List)** আকারে সাজিয়ে প্রদর্শন করতে ব্যবহৃত হয়। যখন একাধিক সম্পর্কিত তথ্য ধারাবাহিকভাবে দেখানোর প্রয়োজন হয়, তখন List Tags ব্যবহার করা হয়।

HTML-এ List তিন ধরনের হতে পারে—

* **Unordered List** (বুলেট লিস্ট)
* **Ordered List** (সংখ্যাযুক্ত লিস্ট)
* **Description List** (শব্দ ও তার ব্যাখ্যা)

এই তিন ধরনের List তৈরির জন্য HTML-এ মোট **৬টি প্রধান List Tag** রয়েছে।

---

### List Tag কী?

List Tag হলো এমন একটি HTML Element, যা একাধিক সম্পর্কিত তথ্যকে সুশৃঙ্খলভাবে তালিকা আকারে প্রদর্শন করে।

List ব্যবহার করলে Content আরও পরিষ্কার, পাঠযোগ্য এবং সহজে বোঝা যায়।

---

### List Tags-এর মৌলিক কাঠামো

```html id="m8q4dv"
<!DOCTYPE html>
<html>

<head>
    <title>List Tags</title>
</head>

<body>

    <h2>Unordered List</h2>

    <ul>
        <li>HTML</li>
        <li>CSS</li>
        <li>JavaScript</li>
    </ul>

    <h2>Ordered List</h2>

    <ol>
        <li>Install VS Code</li>
        <li>Write HTML</li>
        <li>Run Browser</li>
    </ol>

    <h2>Description List</h2>

    <dl>
        <dt>HTML</dt>
        <dd>HyperText Markup Language</dd>

        <dt>CSS</dt>
        <dd>Cascading Style Sheets</dd>
    </dl>

</body>

</html>
```

উপরের Code-এ HTML-এর তিন ধরনের List ব্যবহার করা হয়েছে।

---

### List Tags-এর তালিকা

| নং | Tag         | কাজ                                  |
| -- | ----------- | ------------------------------------ |
| 47 | `<ul></ul>` | Unordered (Bullet) List তৈরি করে     |
| 48 | `<ol></ol>` | Ordered (Numbered) List তৈরি করে     |
| 49 | `<li></li>` | List-এর প্রতিটি Item তৈরি করে        |
| 50 | `<dl></dl>` | Description List তৈরি করে            |
| 51 | `<dt></dt>` | Description Term (শব্দ) নির্ধারণ করে |
| 52 | `<dd></dd>` | Description (ব্যাখ্যা) প্রদর্শন করে  |

---

### List Tags Structure

```text id="2ghn0s"
List
 │
 ├── <ul>
 │      └── <li>
 │
 ├── <ol>
 │      └── <li>
 │
 └── <dl>
        ├── <dt>
        └── <dd>
```

এই Structure দেখায় যে `<ul>` এবং `<ol>`-এর ভিতরে `<li>` ব্যবহার করা হয়, আর `<dl>`-এর ভিতরে `<dt>` ও `<dd>` ব্যবহার করা হয়।

---

### প্রতিটি Tag-এর সংক্ষিপ্ত পরিচয়

#### 47. `<ul></ul>`

* Unordered List (Bullet List) তৈরি করে।
* প্রতিটি Item-এর আগে সাধারণত Bullet (•) দেখায়।
* যখন Item-এর নির্দিষ্ট ক্রম গুরুত্বপূর্ণ নয়, তখন ব্যবহার করা হয়।

---

#### 48. `<ol></ol>`

* Ordered List (Numbered List) তৈরি করে।
* Browser স্বয়ংক্রিয়ভাবে প্রতিটি Item-এর আগে সংখ্যা বা অক্ষর যোগ করে।
* যখন Item-এর ক্রম গুরুত্বপূর্ণ, তখন ব্যবহার করা হয়।

---

#### 49. `<li></li>`

* List-এর প্রতিটি Item তৈরি করে।
* `<ul>` অথবা `<ol>`-এর ভিতরে ব্যবহার করা হয়।
* List-এর মূল Content এই Tag-এর মধ্যে লেখা হয়।

---

#### 50. `<dl></dl>`

* Description List তৈরি করে।
* শব্দ এবং তার ব্যাখ্যা প্রদর্শনের জন্য ব্যবহৃত হয়।
* Dictionary বা Glossary তৈরিতে খুবই উপযোগী।

---

#### 51. `<dt></dt>`

* Description Term (শব্দ বা শিরোনাম) নির্ধারণ করে।
* `<dl>`-এর ভিতরে ব্যবহার করা হয়।

---

#### 52. `<dd></dd>`

* Description বা ব্যাখ্যা প্রদর্শন করে।
* `<dt>`-এর সাথে সম্পর্কিত তথ্য প্রদান করে।
* Browser সাধারণত সামান্য Indent করে দেখায়।

---

### Browser কীভাবে List Tags পড়ে?

```text id="cw9f4p"
HTML Document
      │
      ▼
Read List Tag
      │
      ▼
Identify List Type
      │
      ▼
Read List Items
      │
      ▼
Display List
```

Browser প্রথমে List-এর ধরন নির্ধারণ করে, তারপর প্রতিটি Item সাজিয়ে প্রদর্শন করে।

---

### List Tags-এর গুরুত্ব

* তথ্য সুশৃঙ্খলভাবে উপস্থাপন করে।
* Content পড়তে সহজ করে।
* User Experience (UX) উন্নত করে।
* SEO-তে সহায়তা করে।
* Menu, Navigation, Feature List এবং Step-by-Step নির্দেশনা তৈরিতে ব্যবহৃত হয়।
* Dictionary বা Glossary তৈরি করা সহজ হয়।

---

### বাস্তব উদাহরণ

ধরুন আপনি একটি **Shopping List** লিখছেন।

| HTML Tag | বাস্তব উদাহরণ                                 |
| -------- | --------------------------------------------- |
| `<ul>`   | বাজারের তালিকা (যেখানে ক্রম গুরুত্বপূর্ণ নয়) |
| `<ol>`   | রান্নার ধাপ (যেখানে ক্রম গুরুত্বপূর্ণ)        |
| `<li>`   | প্রতিটি পণ্যের নাম                            |
| `<dl>`   | Dictionary                                    |
| `<dt>`   | শব্দ                                          |
| `<dd>`   | শব্দের অর্থ                                   |

যেমন একটি Dictionary-তে প্রতিটি শব্দের পরে তার ব্যাখ্যা থাকে, ঠিক তেমনি `<dl>`, `<dt>` এবং `<dd>` একসাথে কাজ করে।

---

### সারসংক্ষেপ

List Tags HTML-এর গুরুত্বপূর্ণ Tag Group, যা তথ্যকে তালিকা আকারে উপস্থাপন করতে ব্যবহৃত হয়। HTML-এ তিন ধরনের List রয়েছে—**Unordered List**, **Ordered List** এবং **Description List**। এগুলো তৈরির জন্য `<ul>`, `<ol>`, `<li>`, `<dl>`, `<dt>` এবং `<dd>` Tag ব্যবহার করা হয়। সঠিকভাবে List ব্যবহার করলে Web Page আরও সুসংগঠিত, পাঠযোগ্য, SEO-Friendly এবং ব্যবহারকারী-বান্ধব (User-Friendly) হয়ে ওঠে।






## 8. Link Tags

Link Tags হলো HTML-এর এমন কিছু Tag, যা একটি **Web Page থেকে অন্য Web Page, Website, File, Email Address, Phone Number অথবা একই Page-এর নির্দিষ্ট অংশে সংযোগ (Link)** তৈরি করতে ব্যবহৃত হয়। Link-এর মাধ্যমে ব্যবহারকারী (User) একটি স্থান থেকে অন্য স্থানে সহজেই যেতে পারে।

HTML-এ Link তৈরির জন্য প্রধানত **একটি Tag** ব্যবহার করা হয়, সেটি হলো **`<a>` (Anchor Tag)**।

---

### Link Tag কী?

Link Tag হলো এমন একটি HTML Element, যা একটি Hyperlink তৈরি করে। Hyperlink-এর মাধ্যমে ব্যবহারকারী Mouse দিয়ে Click করে অথবা Keyboard ব্যবহার করে অন্য কোনো Resource-এ যেতে পারে।

এই Resource হতে পারে—

* অন্য Web Page
* অন্য Website
* Image
* PDF File
* Video
* Email Address
* Phone Number
* একই Page-এর নির্দিষ্ট Section

---

### Link Tags-এর মৌলিক কাঠামো

```html id="g8r4mk"
<!DOCTYPE html>
<html>

<head>
    <title>Link Tags</title>
</head>

<body>

    <a href="https://example.com">
        Visit Example
    </a>

</body>

</html>
```

উপরের Code-এ `<a>` Tag ব্যবহার করে একটি Hyperlink তৈরি করা হয়েছে।

---

### Link Tags-এর তালিকা

| নং | Tag       | কাজ                |
| -- | --------- | ------------------ |
| 53 | `<a></a>` | Hyperlink তৈরি করে |

---

### Link Tags Structure

```text id="m3wp7y"
<a>
 │
 ├── href
 ├── target
 ├── title
 ├── download
 ├── rel
 └── Link Text
```

`<a>` Tag-এর মাধ্যমে বিভিন্ন ধরনের Link তৈরি করা যায় এবং বিভিন্ন Attribute ব্যবহার করে Link-এর আচরণ নিয়ন্ত্রণ করা যায়।

---

### Tag-এর সংক্ষিপ্ত পরিচয়

#### 53. `<a></a>`

* Anchor Tag নামেও পরিচিত।
* একটি Hyperlink তৈরি করে।
* Web Page, Website, File অথবা অন্য Resource-এর সাথে সংযোগ স্থাপন করে।
* `href` Attribute-এর মাধ্যমে Link-এর ঠিকানা নির্ধারণ করা হয়।
* এটি একটি **Inline Element**।

---

### Browser কীভাবে Link Tag পড়ে?

Browser সাধারণত নিচের ধাপগুলো অনুসরণ করে—

```text id="d5q8zr"
HTML Document
      │
      ▼
Read <a> Tag
      │
      ▼
Read href Attribute
      │
      ▼
Create Hyperlink
      │
      ▼
User Click
      │
      ▼
Open Destination
```

Browser প্রথমে `href` Attribute পড়ে, তারপর ব্যবহারকারী Link-এ Click করলে নির্দিষ্ট Resource খুলে দেয়।

---

### Link Tags-এর গুরুত্ব

* Web Page-এর মধ্যে Navigation তৈরি করে।
* এক Website থেকে অন্য Website-এ যাওয়ার সুযোগ দেয়।
* Internal এবং External Link তৈরি করা যায়।
* SEO উন্নত করতে সাহায্য করে।
* User Experience (UX) উন্নত করে।
* File Download, Email এবং Phone Link তৈরি করা যায়।

---

### Link-এর ধরন

HTML-এর `<a>` Tag ব্যবহার করে বিভিন্ন ধরনের Link তৈরি করা যায়।

#### ১. External Link

অন্য Website-এ যাওয়ার জন্য।

```html id="8kfh3u"
<a href="https://example.com">
    Example Website
</a>
```

---

#### ২. Internal Link

একই Website-এর অন্য Page-এ যাওয়ার জন্য।

```html id="t2pm6v"
<a href="about.html">
    About Us
</a>
```

---

#### ৩. Bookmark Link

একই Page-এর নির্দিষ্ট অংশে যাওয়ার জন্য।

```html id="6znh4r"
<a href="#contact">
    Contact Section
</a>
```

---

#### ৪. Email Link

Email পাঠানোর জন্য।

```html id="j9rw1c"
<a href="mailto:example@email.com">
    Send Email
</a>
```

---

#### ৫. Phone Link

মোবাইল থেকে সরাসরি Call করার জন্য।

```html id="a7yd8n"
<a href="tel:+8801234567890">
    Call Now
</a>
```

---

#### ৬. Download Link

কোনো File Download করার জন্য।

```html id="e4mv2q"
<a href="notes.pdf" download>
    Download PDF
</a>
```

---

### সাধারণ Attribute

| Attribute  | কাজ                                         |
| ---------- | ------------------------------------------- |
| `href`     | Link-এর ঠিকানা নির্ধারণ করে                 |
| `target`   | Link কোথায় খুলবে তা নির্ধারণ করে           |
| `title`    | অতিরিক্ত তথ্য প্রদর্শন করে                  |
| `download` | File Download করায়                         |
| `rel`      | Link-এর সম্পর্ক (Relationship) নির্ধারণ করে |

---

### বাস্তব উদাহরণ

ধরুন একটি **বইয়ের সূচিপত্র (Table of Contents)** কল্পনা করুন।

| HTML Tag | বাস্তব উদাহরণ                  |
| -------- | ------------------------------ |
| `<a>`    | সূচিপত্রের একটি অধ্যায়ের Link |

যেমন সূচিপত্রে একটি অধ্যায়ের নামের উপর Click করলে সেই অধ্যায়ে যাওয়া যায়, ঠিক তেমনি `<a>` Tag ব্যবহার করে একটি Web Page থেকে অন্য Page বা Section-এ যাওয়া যায়।

---

### সারসংক্ষেপ

Link Tags HTML-এর অন্যতম গুরুত্বপূর্ণ Tag Group, যার মাধ্যমে বিভিন্ন Resource-এর মধ্যে সংযোগ (Hyperlink) তৈরি করা হয়। HTML-এ Link তৈরির জন্য প্রধান Tag হলো **`<a>` (Anchor Tag)**। এটি ব্যবহার করে Internal Link, External Link, Bookmark Link, Email Link, Phone Link এবং Download Link তৈরি করা যায়। `<a>` Tag Web Navigation-এর ভিত্তি এবং একটি Professional, User-Friendly ও SEO-Friendly Website তৈরির জন্য অত্যন্ত গুরুত্বপূর্ণ।






## 9. Image Tags

Image Tags হলো HTML-এর এমন কিছু Tag, যা **Website-এ ছবি (Image), Responsive Image, Image Caption এবং Image Map** প্রদর্শনের জন্য ব্যবহৃত হয়। একটি Web Page-কে আরও আকর্ষণীয় (Attractive), তথ্যবহুল (Informative) এবং ব্যবহারকারী-বান্ধব (User-Friendly) করতে Image Tags গুরুত্বপূর্ণ ভূমিকা পালন করে।

HTML-এ Image প্রদর্শনের জন্য শুধু `<img>` Tag নয়, বরং Responsive Image, Caption এবং Clickable Image Area তৈরির জন্য আরও কয়েকটি Tag রয়েছে।

HTML-এ মোট **৭টি Image Tag** রয়েছে।

---

### Image Tag কী?

Image Tag হলো এমন HTML Element, যা Browser-এ ছবি প্রদর্শন, ছবির বিভিন্ন সংস্করণ নির্বাচন, ছবির বর্ণনা (Caption) এবং ছবির নির্দিষ্ট অংশে Link তৈরির জন্য ব্যবহৃত হয়।

Image Tags ব্যবহার করে—

* Website-এ ছবি দেখানো যায়।
* Responsive Image তৈরি করা যায়।
* ছবির নিচে Caption যোগ করা যায়।
* একটি ছবির নির্দিষ্ট অংশে Click করা যায়।

---

### Image Tags-এর মৌলিক কাঠামো

```html
<!DOCTYPE html>
<html>

<head>
    <title>Image Tags</title>
</head>

<body>

    <figure>

        <picture>

            <source
                media="(min-width:768px)"
                srcset="desktop.jpg">

            <img
                src="mobile.jpg"
                alt="Nature Image">

        </picture>

        <figcaption>
            Beautiful Nature
        </figcaption>

    </figure>

</body>

</html>
```

উপরের Code-এ HTML-এর বিভিন্ন Image Tag ব্যবহার করা হয়েছে।

---

### Image Tags-এর তালিকা

| নং | Tag                         | কাজ                                      |
| -- | --------------------------- | ---------------------------------------- |
| 54 | `<img>`                     | Image প্রদর্শন করে                       |
| 55 | `<picture></picture>`       | Responsive Image তৈরি করে                |
| 56 | `<source>`                  | বিভিন্ন Image Source নির্ধারণ করে        |
| 57 | `<figure></figure>`         | Image বা Media Group করে                 |
| 58 | `<figcaption></figcaption>` | Image-এর Caption প্রদর্শন করে            |
| 59 | `<map></map>`               | Image Map তৈরি করে                       |
| 60 | `<area>`                    | Image Map-এর Clickable Area নির্ধারণ করে |

---

### Image Tags Structure

```text
<figure>
     │
     ├── <picture>
     │      │
     │      ├── <source>
     │      │
     │      └── <img>
     │
     └── <figcaption>

<map>
     │
     └── <area>
```

---

### প্রতিটি Tag-এর সংক্ষিপ্ত পরিচয়

#### 54. `<img>`

* Website-এ Image প্রদর্শনের জন্য ব্যবহৃত হয়।
* HTML-এর সবচেয়ে বেশি ব্যবহৃত Image Tag।
* `src` Attribute দিয়ে Image-এর Location নির্ধারণ করা হয়।
* `alt` Attribute দিয়ে Image-এর বিকল্প Text লেখা হয়।
* এটি একটি **Void (Empty) Element**।

---

#### 55. `<picture></picture>`

* Responsive Image প্রদর্শনের জন্য ব্যবহৃত হয়।
* Screen Size অনুযায়ী বিভিন্ন Image Load করতে পারে।
* সাধারণত `<source>` এবং `<img>` Tag-এর সাথে ব্যবহার করা হয়।

---

#### 56. `<source>`

* বিভিন্ন Image Source নির্ধারণ করে।
* সাধারণত `<picture>`, `<audio>` এবং `<video>` Tag-এর ভিতরে ব্যবহৃত হয়।
* Browser উপযুক্ত Source নির্বাচন করে।

---

#### 57. `<figure></figure>`

* Image, Diagram, Chart অথবা অন্য Media-কে একটি Group হিসেবে প্রদর্শন করে।
* সাধারণত `<figcaption>` Tag-এর সাথে ব্যবহার করা হয়।

---

#### 58. `<figcaption></figcaption>`

* Image-এর Caption বা বর্ণনা প্রদর্শন করে।
* সাধারণত `<figure>` Tag-এর ভিতরে লেখা হয়।

---

#### 59. `<map></map>`

* Image Map তৈরি করে।
* একটি Image-এর বিভিন্ন অংশকে Clickable করতে ব্যবহৃত হয়।

---

#### 60. `<area>`

* Image Map-এর Clickable Area নির্ধারণ করে।
* `shape`, `coords` এবং `href` Attribute ব্যবহার করে বিভিন্ন অংশে Link তৈরি করা যায়।
* এটি একটি **Void (Empty) Element**।

---

### Browser কীভাবে Image Tags পড়ে?

Browser সাধারণত নিচের ধাপগুলো অনুসরণ করে—

```text
HTML Document
      │
      ▼
Read Image Tag
      │
      ▼
Load Image Source
      │
      ▼
Check Screen Size
      │
      ▼
Display Image
```

যদি `<picture>` ব্যবহার করা হয়, Browser Screen Size অনুযায়ী উপযুক্ত Image নির্বাচন করে।

---

### Image Tags-এর গুরুত্ব

* Website-কে আকর্ষণীয় করে।
* Responsive Design তৈরি করতে সাহায্য করে।
* SEO উন্নত করে (`alt` Attribute-এর মাধ্যমে)।
* Accessibility বৃদ্ধি করে।
* Image-এর Caption যোগ করা যায়।
* Image Map ব্যবহার করে নির্দিষ্ট অংশে Link তৈরি করা যায়।
* User Experience (UX) উন্নত করে।

---

### Block Level এবং Inline Element

| Tag            | Element Type          |
| -------------- | --------------------- |
| `<img>`        | Inline (Void Element) |
| `<picture>`    | Inline                |
| `<source>`     | Void Element          |
| `<figure>`     | Block Level           |
| `<figcaption>` | Block Level           |
| `<map>`        | Inline                |
| `<area>`       | Void Element          |

---

### বাস্তব উদাহরণ

ধরুন আপনি একটি **পাঠ্যবই** পড়ছেন।

| HTML Tag       | বাস্তব উদাহরণ                         |
| -------------- | ------------------------------------- |
| `<img>`        | বইয়ের ছবি                            |
| `<picture>`    | বিভিন্ন আকারের একই ছবি                |
| `<source>`     | ছবির বিভিন্ন সংস্করণ                  |
| `<figure>`     | ছবি ও তার সম্পূর্ণ অংশ                |
| `<figcaption>` | ছবির নিচের বর্ণনা                     |
| `<map>`        | ছবির বিভিন্ন অংশে ক্লিক করার ব্যবস্থা |
| `<area>`       | ছবির নির্দিষ্ট Clickable অংশ          |

যেমন একটি বইয়ের ছবির নিচে Caption লেখা থাকে, ঠিক তেমনি HTML-এ `<figure>` এবং `<figcaption>` ব্যবহার করে ছবি ও তার বর্ণনা একসাথে দেখানো যায়।

---

### সারসংক্ষেপ

Image Tags HTML-এর গুরুত্বপূর্ণ Tag Group, যা Website-এ ছবি এবং বিভিন্ন ধরনের Media উপস্থাপনের জন্য ব্যবহৃত হয়। HTML-এ মোট **৭টি Image Tag** রয়েছে—`<img>`, `<picture>`, `<source>`, `<figure>`, `<figcaption>`, `<map>` এবং `<area>`। এগুলোর মাধ্যমে সাধারণ Image, Responsive Image, Image Caption এবং Clickable Image Map তৈরি করা যায়। একটি আধুনিক, Responsive, SEO-Friendly এবং User-Friendly Website তৈরিতে Image Tags অত্যন্ত গুরুত্বপূর্ণ।






## 10. Audio & Video Tags

Audio & Video Tags হলো HTML-এর এমন কিছু Tag, যা **Website-এ Audio (শব্দ) এবং Video (ভিডিও)** প্রদর্শন ও নিয়ন্ত্রণ (Control) করার জন্য ব্যবহৃত হয়। HTML5-এর আগে Audio এবং Video চালানোর জন্য Flash-এর মতো বাহ্যিক Plugin প্রয়োজন হতো, কিন্তু HTML5 আসার পর Browser নিজেই Audio ও Video সমর্থন করতে শুরু করে।

Audio & Video Tags ব্যবহার করে—

* গান (Music) চালানো যায়।
* ভিডিও প্রদর্শন করা যায়।
* একাধিক Media Source ব্যবহার করা যায়।
* Subtitle বা Caption যোগ করা যায়।

HTML-এ Media প্রদর্শনের জন্য মোট **৪টি প্রধান Tag** রয়েছে।

---

### Audio & Video Tag কী?

Audio & Video Tag হলো এমন HTML Element, যা Browser-এর মাধ্যমে Audio এবং Video File প্রদর্শন ও নিয়ন্ত্রণ করার জন্য ব্যবহৃত হয়।

এই Tag-গুলোর মাধ্যমে Play, Pause, Volume Control, Full Screen, Subtitle এবং বিভিন্ন Media Format ব্যবহার করা যায়।

---

### Audio & Video Tags-এর মৌলিক কাঠামো

```html id="m7q2lv"
<!DOCTYPE html>
<html>

<head>
    <title>Audio & Video Tags</title>
</head>

<body>

    <audio controls>

        <source src="music.mp3" type="audio/mpeg">

        Your browser does not support the audio element.

    </audio>

    <br><br>

    <video controls width="600">

        <source src="video.mp4" type="video/mp4">

        <track
            src="subtitle.vtt"
            kind="subtitles"
            srclang="en"
            label="English">

        Your browser does not support the video element.

    </video>

</body>

</html>
```

উপরের Code-এ HTML-এর Audio ও Video Tag ব্যবহার করা হয়েছে।

---

### Audio & Video Tags-এর তালিকা

| নং | Tag               | কাজ                                      |
| -- | ----------------- | ---------------------------------------- |
| 61 | `<audio></audio>` | Audio প্লে করে                           |
| 62 | `<video></video>` | Video প্লে করে                           |
| 63 | `<source>`        | Media-এর একাধিক Source নির্ধারণ করে      |
| 64 | `<track>`         | Subtitle, Caption এবং Text Track যোগ করে |

---

### Audio & Video Tags Structure

```text id="px8jru"
<audio>
     │
     └── <source>

<video>
     │
     ├── <source>
     │
     └── <track>
```

---

### প্রতিটি Tag-এর সংক্ষিপ্ত পরিচয়

#### 61. `<audio></audio>`

* Website-এ Audio File চালানোর জন্য ব্যবহৃত হয়।
* Browser-এর Built-in Audio Player প্রদর্শন করতে পারে।
* সাধারণত `controls` Attribute ব্যবহার করা হয়।
* MP3, OGG, WAV ইত্যাদি Format সমর্থন করে।

---

#### 62. `<video></video>`

* Website-এ Video প্রদর্শনের জন্য ব্যবহৃত হয়।
* Browser-এর Built-in Video Player প্রদান করে।
* Play, Pause, Volume, Full Screen ইত্যাদি Control ব্যবহার করা যায়।
* MP4, WebM এবং OGG Video সমর্থন করে।

---

#### 63. `<source>`

* Media-এর একাধিক Source নির্ধারণ করে।
* Browser যে Format সমর্থন করে, সেটি স্বয়ংক্রিয়ভাবে নির্বাচন করে।
* `<audio>` এবং `<video>` Tag-এর ভিতরে ব্যবহার করা হয়।
* এটি একটি **Void (Empty) Element**।

---

#### 64. `<track>`

* Subtitle, Caption, Description এবং অন্যান্য Text Track যোগ করতে ব্যবহৃত হয়।
* সাধারণত `.vtt` (WebVTT) File ব্যবহার করা হয়।
* Accessibility উন্নত করতে সাহায্য করে।
* এটি একটি **Void (Empty) Element**।

---

### Browser কীভাবে Audio & Video Tags পড়ে?

Browser সাধারণত নিচের ধাপগুলো অনুসরণ করে—

```text id="r3x7ma"
HTML Document
      │
      ▼
Read Media Tag
      │
      ▼
Read Source
      │
      ▼
Check Supported Format
      │
      ▼
Load Media
      │
      ▼
Display Media Player
```

Browser প্রথমে Media Source পরীক্ষা করে এবং সমর্থিত Format থাকলে Media Player প্রদর্শন করে।

---

### Audio & Video Tags-এর গুরুত্ব

* Plugin ছাড়াই Audio ও Video চালানো যায়।
* একাধিক Media Format সমর্থন করে।
* Subtitle ও Caption যোগ করা যায়।
* Accessibility উন্নত করে।
* Online Learning, Music Website এবং Video Platform তৈরিতে ব্যবহৃত হয়।
* User Experience (UX) উন্নত করে।

---

### Block Level এবং Inline Element

| Tag        | Element Type |
| ---------- | ------------ |
| `<audio>`  | Inline       |
| `<video>`  | Inline       |
| `<source>` | Void Element |
| `<track>`  | Void Element |

---

### বাস্তব উদাহরণ

ধরুন একটি **Online Learning Website** কল্পনা করুন।

| HTML Tag   | বাস্তব উদাহরণ                |
| ---------- | ---------------------------- |
| `<audio>`  | Lecture-এর Audio             |
| `<video>`  | Video Tutorial               |
| `<source>` | বিভিন্ন Format-এর Media File |
| `<track>`  | Subtitle বা Caption          |

যেমন YouTube-এ Video-এর সাথে Subtitle দেখা যায়, ঠিক তেমনি HTML-এর `<track>` Tag ব্যবহার করে Subtitle যোগ করা যায়।

---

### সারসংক্ষেপ

Audio & Video Tags HTML-এর গুরুত্বপূর্ণ Media Tag Group, যা Website-এ Audio এবং Video প্রদর্শনের জন্য ব্যবহৃত হয়। HTML-এ মোট **৪টি প্রধান Audio & Video Tag** রয়েছে—`<audio>`, `<video>`, `<source>` এবং `<track>`। এগুলোর মাধ্যমে Browser-এর Built-in Media Player ব্যবহার করে Audio ও Video চালানো, একাধিক Media Source নির্বাচন করা এবং Subtitle বা Caption যোগ করা যায়। আধুনিক, Interactive এবং User-Friendly Website তৈরিতে এই Tag-গুলোর ভূমিকা অত্যন্ত গুরুত্বপূর্ণ।






## 11. Table Tags

Table Tags হলো HTML-এর এমন কিছু Tag, যা **সারি (Row) এবং কলাম (Column)** ব্যবহার করে তথ্যকে **টেবিল (Table)** আকারে প্রদর্শনের জন্য ব্যবহৃত হয়। যখন কোনো তথ্যকে সুশৃঙ্খলভাবে সাজিয়ে দেখানোর প্রয়োজন হয়, তখন Table ব্যবহার করা হয়।

Table-এর মাধ্যমে—

* Student Result দেখানো যায়।
* Product List তৈরি করা যায়।
* Price List প্রদর্শন করা যায়।
* Financial Report তৈরি করা যায়।
* Schedule বা Routine দেখানো যায়।

HTML-এ একটি সম্পূর্ণ Table তৈরির জন্য মোট **১০টি প্রধান Tag** রয়েছে।

---

### Table Tag কী?

Table Tag হলো এমন HTML Element, যা Row এবং Column-এর মাধ্যমে তথ্যকে সারণি (Table) আকারে উপস্থাপন করে।

একটি Table-এর মধ্যে সাধারণত থাকে—

* একটি Table
* একটি Caption (ঐচ্ছিক)
* Header
* Body
* Footer
* Row
* Header Cell
* Data Cell

---

### Table Tags-এর মৌলিক কাঠামো

```html id="k4n8zp"
<!DOCTYPE html>
<html>

<head>
    <title>Table Tags</title>
</head>

<body>

    <table>

        <caption>
            Student Information
        </caption>

        <thead>

            <tr>
                <th>ID</th>
                <th>Name</th>
                <th>Department</th>
            </tr>

        </thead>

        <tbody>

            <tr>
                <td>101</td>
                <td>Hasan</td>
                <td>CSE</td>
            </tr>

            <tr>
                <td>102</td>
                <td>Rahim</td>
                <td>EEE</td>
            </tr>

        </tbody>

        <tfoot>

            <tr>
                <td colspan="3">
                    Total Students : 2
                </td>
            </tr>

        </tfoot>

    </table>

</body>

</html>
```

উপরের Code-এ একটি সম্পূর্ণ HTML Table তৈরি করা হয়েছে।

---

### Table Tags-এর তালিকা

| নং | Tag                     | কাজ                                                 |
| -- | ----------------------- | --------------------------------------------------- |
| 65 | `<table></table>`       | সম্পূর্ণ Table তৈরি করে                             |
| 66 | `<caption></caption>`   | Table-এর শিরোনাম (Title) দেখায়                     |
| 67 | `<thead></thead>`       | Table Header নির্ধারণ করে                           |
| 68 | `<tbody></tbody>`       | Table-এর মূল Data ধারণ করে                          |
| 69 | `<tfoot></tfoot>`       | Table Footer নির্ধারণ করে                           |
| 70 | `<tr></tr>`             | একটি Row তৈরি করে                                   |
| 71 | `<th></th>`             | Header Cell তৈরি করে                                |
| 72 | `<td></td>`             | Data Cell তৈরি করে                                  |
| 73 | `<colgroup></colgroup>` | Column Group নির্ধারণ করে                           |
| 74 | `<col>`                 | নির্দিষ্ট Column-এর Style বা বৈশিষ্ট্য নির্ধারণ করে |

---

### Table Tags Structure

```text id="h7m2wr"
<table>
     │
     ├── <caption>
     │
     ├── <colgroup>
     │      └── <col>
     │
     ├── <thead>
     │      └── <tr>
     │             └── <th>
     │
     ├── <tbody>
     │      └── <tr>
     │             └── <td>
     │
     └── <tfoot>
            └── <tr>
                   └── <td>
```

---

### প্রতিটি Tag-এর সংক্ষিপ্ত পরিচয়

#### 65. `<table></table>`

* সম্পূর্ণ Table তৈরি করে।
* Table-এর সকল অংশ এই Tag-এর ভিতরে থাকে।
* এটি একটি **Block Level Element**।

---

#### 66. `<caption></caption>`

* Table-এর শিরোনাম (Title) প্রদর্শন করে।
* সাধারণত Table-এর উপরে দেখা যায়।
* একটি Table-এ একটি Caption ব্যবহার করা হয়।

---

#### 67. `<thead></thead>`

* Table-এর Header অংশ নির্ধারণ করে।
* এখানে সাধারণত Column-এর নাম থাকে।
* `<th>` Tag ব্যবহার করা হয়।

---

#### 68. `<tbody></tbody>`

* Table-এর মূল Data ধারণ করে।
* অধিকাংশ Row এই অংশে থাকে।

---

#### 69. `<tfoot></tfoot>`

* Table-এর Footer অংশ নির্ধারণ করে।
* Summary, Total বা অতিরিক্ত তথ্য প্রদর্শনের জন্য ব্যবহৃত হয়।

---

#### 70. `<tr></tr>`

* একটি Row (সারি) তৈরি করে।
* `<thead>`, `<tbody>` অথবা `<tfoot>`-এর ভিতরে ব্যবহার করা হয়।

---

#### 71. `<th></th>`

* Header Cell তৈরি করে।
* Browser সাধারণত Bold এবং Center Align করে দেখায়।
* Column বা Row-এর শিরোনাম প্রদর্শনের জন্য ব্যবহৃত হয়।

---

#### 72. `<td></td>`

* সাধারণ Data Cell তৈরি করে।
* Table-এর প্রকৃত তথ্য এই Tag-এর মধ্যে লেখা হয়।

---

#### 73. `<colgroup></colgroup>`

* একাধিক Column-কে Group করে।
* নির্দিষ্ট Column-এর Style একসাথে নির্ধারণ করতে ব্যবহৃত হয়।

---

#### 74. `<col>`

* নির্দিষ্ট Column-এর Style বা বৈশিষ্ট্য নির্ধারণ করে।
* সাধারণত `<colgroup>`-এর ভিতরে ব্যবহার করা হয়।
* এটি একটি **Void (Empty) Element**।

---

### Browser কীভাবে Table Tags পড়ে?

Browser সাধারণত নিচের ধাপগুলো অনুসরণ করে—

```text id="d8x3qp"
HTML Document
      │
      ▼
Read <table>
      │
      ▼
Read Header
      │
      ▼
Read Body
      │
      ▼
Read Footer
      │
      ▼
Display Table
```

Browser প্রতিটি Row এবং Column অনুযায়ী Table তৈরি করে এবং ব্যবহারকারীর সামনে প্রদর্শন করে।

---

### Table Tags-এর গুরুত্ব

* তথ্যকে সুশৃঙ্খলভাবে উপস্থাপন করে।
* Row ও Column আকারে Data প্রদর্শন করে।
* Report, Result, Price List এবং Schedule তৈরিতে ব্যবহৃত হয়।
* Data পড়া ও তুলনা করা সহজ হয়।
* SEO এবং Accessibility উন্নত করতে সহায়তা করে।
* বড় Data-কে সংগঠিতভাবে দেখানোর জন্য উপযোগী।

---

### Block Level এবং Table Element

| Tag          | Element Type       |
| ------------ | ------------------ |
| `<table>`    | Block Level        |
| `<caption>`  | Table Element      |
| `<thead>`    | Table Element      |
| `<tbody>`    | Table Element      |
| `<tfoot>`    | Table Element      |
| `<tr>`       | Table Row          |
| `<th>`       | Table Header Cell  |
| `<td>`       | Table Data Cell    |
| `<colgroup>` | Table Element      |
| `<col>`      | Void Table Element |

---

### বাস্তব উদাহরণ

ধরুন একটি **স্কুলের ফলাফল শিট (Result Sheet)** কল্পনা করুন।

| HTML Tag     | বাস্তব উদাহরণ             |
| ------------ | ------------------------- |
| `<table>`    | সম্পূর্ণ ফলাফলের টেবিল    |
| `<caption>`  | "Student Result" শিরোনাম  |
| `<thead>`    | Subject-এর নাম            |
| `<tbody>`    | শিক্ষার্থীদের নম্বর       |
| `<tfoot>`    | মোট নম্বর বা গড়          |
| `<tr>`       | প্রতিটি শিক্ষার্থীর তথ্য  |
| `<th>`       | Column Header             |
| `<td>`       | শিক্ষার্থীর তথ্য          |
| `<colgroup>` | নির্দিষ্ট Column-এর Group |
| `<col>`      | নির্দিষ্ট Column-এর Style |

যেমন একটি Excel Sheet-এ Row এবং Column ব্যবহার করে তথ্য সাজানো হয়, ঠিক তেমনি HTML-এর Table Tags ব্যবহার করে Web Page-এ Data সুন্দরভাবে প্রদর্শন করা যায়।

---

### সারসংক্ষেপ

Table Tags HTML-এর গুরুত্বপূর্ণ Tag Group, যা তথ্যকে Row এবং Column আকারে উপস্থাপন করতে ব্যবহৃত হয়। HTML-এ মোট **১০টি প্রধান Table Tag** রয়েছে—`<table>`, `<caption>`, `<thead>`, `<tbody>`, `<tfoot>`, `<tr>`, `<th>`, `<td>`, `<colgroup>` এবং `<col>`। এগুলোর মাধ্যমে সুন্দর, সুশৃঙ্খল এবং অর্থবহ Table তৈরি করা যায়। Product List, Student Result, Price List, Financial Report এবং অন্যান্য Data-ভিত্তিক Web Page তৈরিতে Table Tags অত্যন্ত গুরুত্বপূর্ণ।






## 12. Form Tags

Form Tags হলো HTML-এর এমন কিছু Tag, যা **ব্যবহারকারীর কাছ থেকে তথ্য (User Input)** সংগ্রহ করার জন্য ব্যবহৃত হয়। Login Form, Registration Form, Contact Form, Search Box, Feedback Form, Online Order Form এবং Survey Form তৈরির জন্য Form Tags ব্যবহার করা হয়।

Form-এর মাধ্যমে ব্যবহারকারী বিভিন্ন ধরনের তথ্য দিতে পারে, যেমন—

* নাম (Name)
* ইমেইল (Email)
* পাসওয়ার্ড (Password)
* ফোন নম্বর (Phone Number)
* ঠিকানা (Address)
* মন্তব্য (Comment)
* ফাইল (File)
* অপশন নির্বাচন (Option Selection)

HTML-এ একটি পূর্ণাঙ্গ Form তৈরির জন্য মোট **১৪টি প্রধান Form Tag** রয়েছে।

---

### Form Tag কী?

Form Tag হলো এমন HTML Element, যা ব্যবহারকারীর কাছ থেকে তথ্য গ্রহণ, সংগঠিত এবং Server-এ পাঠানোর জন্য ব্যবহৃত হয়।

একটি Form-এর মধ্যে বিভিন্ন Input Field, Button, Label এবং অন্যান্য Form Control থাকতে পারে।

---

### Form Tags-এর মৌলিক কাঠামো

```html id="f8k2mp"
<!DOCTYPE html>
<html>

<head>
    <title>Form Tags</title>
</head>

<body>

    <form action="/submit" method="post">

        <fieldset>

            <legend>Student Registration</legend>

            <label for="name">Name</label>
            <input
                type="text"
                id="name"
                name="name">

            <br><br>

            <label for="department">Department</label>

            <select
                id="department"
                name="department">

                <option>CSE</option>
                <option>EEE</option>
                <option>Civil</option>

            </select>

            <br><br>

            <label for="comment">Comment</label>

            <textarea
                id="comment"
                rows="4"
                cols="30">
            </textarea>

            <br><br>

            <button type="submit">
                Submit
            </button>

        </fieldset>

    </form>

</body>

</html>
```

উপরের Code-এ HTML-এর বিভিন্ন Form Tag ব্যবহার করে একটি Registration Form তৈরি করা হয়েছে।

---

### Form Tags-এর তালিকা

| নং | Tag                     | কাজ                                   |
| -- | ----------------------- | ------------------------------------- |
| 75 | `<form></form>`         | সম্পূর্ণ Form তৈরি করে                |
| 76 | `<label></label>`       | Input Field-এর Label নির্ধারণ করে     |
| 77 | `<input>`               | বিভিন্ন ধরনের Input গ্রহণ করে         |
| 78 | `<textarea></textarea>` | একাধিক লাইনের Text Input গ্রহণ করে    |
| 79 | `<button></button>`     | Button তৈরি করে                       |
| 80 | `<select></select>`     | Drop-down List তৈরি করে               |
| 81 | `<option></option>`     | Drop-down-এর একটি Option তৈরি করে     |
| 82 | `<optgroup></optgroup>` | Option Group তৈরি করে                 |
| 83 | `<fieldset></fieldset>` | Form-এর বিভিন্ন অংশ Group করে         |
| 84 | `<legend></legend>`     | Fieldset-এর শিরোনাম নির্ধারণ করে      |
| 85 | `<datalist></datalist>` | Auto Suggestion List তৈরি করে         |
| 86 | `<output></output>`     | Calculation বা Result প্রদর্শন করে    |
| 87 | `<meter></meter>`       | নির্দিষ্ট Range-এর মান প্রদর্শন করে   |
| 88 | `<progress></progress>` | কাজের অগ্রগতি (Progress) প্রদর্শন করে |

---

### Form Tags Structure

```text id="w9e3yn"
<form>
     │
     ├── <fieldset>
     │      │
     │      ├── <legend>
     │      ├── <label>
     │      ├── <input>
     │      ├── <textarea>
     │      ├── <select>
     │      │      ├── <option>
     │      │      └── <optgroup>
     │      ├── <datalist>
     │      ├── <output>
     │      ├── <meter>
     │      ├── <progress>
     │      └── <button>
```

---

### প্রতিটি Tag-এর সংক্ষিপ্ত পরিচয়

#### 75. `<form></form>`

* সম্পূর্ণ Form তৈরি করে।
* ব্যবহারকারীর Input সংগ্রহ করে Server-এ পাঠায়।
* `action` এবং `method` Attribute সবচেয়ে গুরুত্বপূর্ণ।

---

#### 76. `<label></label>`

* Input Field-এর নাম বা বর্ণনা প্রদর্শন করে।
* `for` Attribute-এর মাধ্যমে নির্দিষ্ট Input-এর সাথে সংযুক্ত হয়।
* Accessibility উন্নত করে।

---

#### 77. `<input>`

* HTML-এর সবচেয়ে গুরুত্বপূর্ণ Form Element।
* বিভিন্ন ধরনের Input গ্রহণ করতে পারে।
* যেমন—

  * text
  * password
  * email
  * number
  * date
  * checkbox
  * radio
  * file
  * color
  * range
  * submit
* এটি একটি **Void (Empty) Element**।

---

#### 78. `<textarea></textarea>`

* একাধিক লাইনের Text লিখতে ব্যবহৃত হয়।
* Comment, Feedback এবং Description লেখার জন্য উপযোগী।

---

#### 79. `<button></button>`

* Button তৈরি করে।
* Submit, Reset অথবা সাধারণ Button হিসেবে ব্যবহার করা যায়।

---

#### 80. `<select></select>`

* Drop-down List তৈরি করে।
* ব্যবহারকারী একটি বা একাধিক Option নির্বাচন করতে পারে।

---

#### 81. `<option></option>`

* Drop-down List-এর প্রতিটি Option নির্ধারণ করে।
* `<select>` Tag-এর ভিতরে ব্যবহার করা হয়।

---

#### 82. `<optgroup></optgroup>`

* Option-গুলোকে Group করে।
* বড় Drop-down List-কে আরও সুসংগঠিত করে।

---

#### 83. `<fieldset></fieldset>`

* সম্পর্কিত Form Control-গুলোকে একটি Group হিসেবে সাজায়।
* Form আরও সুন্দর ও সংগঠিত হয়।

---

#### 84. `<legend></legend>`

* একটি `<fieldset>`-এর শিরোনাম নির্ধারণ করে।
* Form-এর বিভিন্ন অংশ সহজে বোঝা যায়।

---

#### 85. `<datalist></datalist>`

* Input Field-এর জন্য Auto Suggestion প্রদান করে।
* ব্যবহারকারী চাইলে Suggestion থেকে নির্বাচন করতে পারে অথবা নতুন মান লিখতে পারে।

---

#### 86. `<output></output>`

* কোনো Calculation বা JavaScript-এর Result প্রদর্শনের জন্য ব্যবহৃত হয়।

---

#### 87. `<meter></meter>`

* নির্দিষ্ট সীমার (Range) মধ্যে একটি মান প্রদর্শন করে।
* যেমন—

  * Disk Usage
  * Battery Level
  * Exam Score

---

#### 88. `<progress></progress>`

* কোনো কাজের অগ্রগতি (Progress) প্রদর্শন করে।
* যেমন—

  * File Upload
  * Download Progress
  * Installation Progress

---

### Browser কীভাবে Form Tags পড়ে?

Browser সাধারণত নিচের ধাপগুলো অনুসরণ করে—

```text id="u4r7km"
HTML Document
      │
      ▼
Read <form>
      │
      ▼
Read Form Controls
      │
      ▼
Display Input Fields
      │
      ▼
User Enters Data
      │
      ▼
Submit Data to Server
```

Browser Form প্রদর্শন করে, ব্যবহারকারীর Input গ্রহণ করে এবং Submit করলে Server-এ পাঠায়।

---

### Form Tags-এর গুরুত্ব

* ব্যবহারকারীর কাছ থেকে তথ্য সংগ্রহ করে।
* Login, Registration এবং Contact Form তৈরি করা যায়।
* Search Box এবং Online Order Form তৈরি করা যায়।
* Survey এবং Feedback সংগ্রহ করা যায়।
* User Interaction বৃদ্ধি করে।
* Web Application-এর অন্যতম গুরুত্বপূর্ণ অংশ।

---

### Block Level, Inline এবং Void Element

| Tag          | Element Type |
| ------------ | ------------ |
| `<form>`     | Block Level  |
| `<label>`    | Inline       |
| `<input>`    | Void Element |
| `<textarea>` | Inline       |
| `<button>`   | Inline       |
| `<select>`   | Inline       |
| `<option>`   | Form Element |
| `<optgroup>` | Form Element |
| `<fieldset>` | Block Level  |
| `<legend>`   | Block Level  |
| `<datalist>` | Form Element |
| `<output>`   | Inline       |
| `<meter>`    | Inline       |
| `<progress>` | Inline       |

---

### বাস্তব উদাহরণ

ধরুন আপনি একটি **অনলাইন ভর্তি ফরম (Online Admission Form)** পূরণ করছেন।

| HTML Tag     | বাস্তব উদাহরণ                  |
| ------------ | ------------------------------ |
| `<form>`     | সম্পূর্ণ আবেদন ফরম             |
| `<label>`    | নাম, ইমেইল, ফোনের শিরোনাম      |
| `<input>`    | নাম বা ইমেইল লেখার ঘর          |
| `<textarea>` | ঠিকানা বা মন্তব্য              |
| `<button>`   | Submit Button                  |
| `<select>`   | বিভাগ নির্বাচন                 |
| `<option>`   | CSE, EEE, Civil                |
| `<optgroup>` | Science, Business Group        |
| `<fieldset>` | ব্যক্তিগত তথ্য অংশ             |
| `<legend>`   | "Personal Information" শিরোনাম |
| `<datalist>` | Auto Suggestion                |
| `<output>`   | গণনার ফলাফল                    |
| `<meter>`    | Skill Level                    |
| `<progress>` | আবেদন সম্পন্ন হওয়ার অগ্রগতি   |

যেমন একটি কাগজের আবেদন ফরমে বিভিন্ন তথ্য লেখার আলাদা ঘর থাকে, ঠিক তেমনি HTML Form Tags ব্যবহার করে Web Page-এ তথ্য সংগ্রহের ব্যবস্থা করা হয়।

---

### সারসংক্ষেপ

Form Tags HTML-এর অন্যতম গুরুত্বপূর্ণ Tag Group, যা ব্যবহারকারীর কাছ থেকে তথ্য সংগ্রহ করার জন্য ব্যবহৃত হয়। HTML-এ মোট **১৪টি প্রধান Form Tag** রয়েছে—`<form>`, `<label>`, `<input>`, `<textarea>`, `<button>`, `<select>`, `<option>`, `<optgroup>`, `<fieldset>`, `<legend>`, `<datalist>`, `<output>`, `<meter>` এবং `<progress>`। এই Tag-গুলোর মাধ্যমে Login Form, Registration Form, Contact Form, Search Form, Feedback Form এবং অন্যান্য Interactive Web Form সহজেই তৈরি করা যায়। Form Tags আধুনিক Web Development-এর একটি মৌলিক এবং অপরিহার্য অংশ।






## 13. Semantic Layout Tags

Semantic Layout Tags হলো HTML-এর এমন কিছু Tag, যা **একটি Web Page-এর বিভিন্ন অংশকে অর্থপূর্ণ (Semantic) ও সুশৃঙ্খলভাবে (Structured)** ভাগ করার জন্য ব্যবহৃত হয়। HTML5-এ এই Tag-গুলো যোগ করা হয়েছে যাতে Browser, Search Engine এবং Screen Reader সহজে বুঝতে পারে কোন অংশটি Header, Navigation, Main Content, Article, Sidebar অথবা Footer।

আগে Web Page-এর Layout তৈরির জন্য প্রায় সব জায়গায় `<div>` ব্যবহার করা হতো। কিন্তু `<div>` কোনো অর্থ প্রকাশ করে না। Semantic Layout Tags ব্যবহার করলে HTML Code আরও পরিষ্কার (Clean), অর্থবহ (Meaningful), SEO-Friendly এবং Accessible হয়।

HTML-এ Layout তৈরির জন্য মোট **৮টি প্রধান Semantic Tag** রয়েছে।

---

### Semantic Layout Tag কী?

Semantic Layout Tag হলো এমন HTML Element, যা Web Page-এর বিভিন্ন অংশের **অর্থ (Meaning)** প্রকাশ করে এবং Page-এর Structure স্পষ্টভাবে নির্ধারণ করে।

এই Tag-গুলো ব্যবহার করে Browser, Search Engine এবং অন্যান্য Software সহজেই বুঝতে পারে কোন অংশে কী ধরনের Content রয়েছে।

---

### Semantic Layout Tags-এর মৌলিক কাঠামো

```html id="p7m3xk"
<!DOCTYPE html>
<html>

<head>
    <title>Semantic Layout Tags</title>
</head>

<body>

    <header>
        Website Header
    </header>

    <nav>
        Navigation Menu
    </nav>

    <main>

        <section>

            <article>
                Article Content
            </article>

        </section>

        <aside>
            Sidebar
        </aside>

    </main>

    <footer>
        Website Footer
    </footer>

</body>

</html>
```

উপরের Code-এ একটি সাধারণ Web Page-এর Semantic Layout দেখানো হয়েছে।

---

### Semantic Layout Tags-এর তালিকা

| নং | Tag                   | কাজ                                        |
| -- | --------------------- | ------------------------------------------ |
| 89 | `<header></header>`   | Header Section তৈরি করে                    |
| 90 | `<nav></nav>`         | Navigation Menu তৈরি করে                   |
| 91 | `<main></main>`       | মূল Content ধারণ করে                       |
| 92 | `<section></section>` | সম্পর্কিত Content-এর Section তৈরি করে      |
| 93 | `<article></article>` | স্বাধীন (Independent) Content প্রদর্শন করে |
| 94 | `<aside></aside>`     | Sidebar বা অতিরিক্ত তথ্য প্রদর্শন করে      |
| 95 | `<footer></footer>`   | Footer Section তৈরি করে                    |
| 96 | `<address></address>` | যোগাযোগের তথ্য প্রদর্শন করে                |

---

### Semantic Layout Structure

```text id="b5r8wv"
<body>
     │
     ├── <header>
     │
     ├── <nav>
     │
     ├── <main>
     │      │
     │      ├── <section>
     │      │      │
     │      │      └── <article>
     │      │
     │      └── <aside>
     │
     └── <footer>
            │
            └── <address>
```

---

### প্রতিটি Tag-এর সংক্ষিপ্ত পরিচয়

#### 89. `<header></header>`

* Website অথবা Section-এর Header তৈরি করে।
* সাধারণত Logo, Website Title, Search Box এবং Navigation-এর অংশ থাকে।
* একটি Page-এ একাধিক Header থাকতে পারে।

---

#### 90. `<nav></nav>`

* Navigation Menu তৈরি করে।
* Website-এর গুরুত্বপূর্ণ Link-গুলো এখানে রাখা হয়।
* যেমন—

  * Home
  * About
  * Services
  * Contact

---

#### 91. `<main></main>`

* Web Page-এর প্রধান Content ধারণ করে।
* একটি HTML Document-এ সাধারণত একটি মাত্র `<main>` থাকে।
* Sidebar, Header বা Footer-এর Content এখানে রাখা হয় না।

---

#### 92. `<section></section>`

* সম্পর্কিত Content-এর একটি আলাদা অংশ তৈরি করে।
* সাধারণত একটি Heading থাকে।
* যেমন—

  * About Section
  * Services Section
  * Contact Section

---

#### 93. `<article></article>`

* স্বাধীনভাবে ব্যবহারযোগ্য Content নির্দেশ করে।
* অন্য Page-এ কপি করলেও অর্থ পরিবর্তন হয় না।
* যেমন—

  * Blog Post
  * News Article
  * Forum Post

---

#### 94. `<aside></aside>`

* মূল Content-এর সাথে সম্পর্কিত অতিরিক্ত তথ্য প্রদর্শন করে।
* সাধারণত Sidebar হিসেবে ব্যবহৃত হয়।
* যেমন—

  * Advertisement
  * Related Post
  * Category List

---

#### 95. `<footer></footer>`

* Page বা Section-এর Footer তৈরি করে।
* সাধারণত থাকে—

  * Copyright
  * Contact Information
  * Social Media Link
  * Privacy Policy

---

#### 96. `<address></address>`

* ব্যক্তি, প্রতিষ্ঠান বা Website-এর যোগাযোগের তথ্য প্রদর্শন করে।
* যেমন—

  * Email
  * Phone Number
  * Address

---

### Browser কীভাবে Semantic Layout Tags পড়ে?

Browser সাধারণত নিচের ধাপগুলো অনুসরণ করে—

```text id="v9t4ly"
HTML Document
      │
      ▼
Read Semantic Tag
      │
      ▼
Determine Section Meaning
      │
      ▼
Build Page Structure
      │
      ▼
Display Web Page
```

Browser প্রতিটি Semantic Tag-এর অর্থ অনুযায়ী Page-এর Structure তৈরি করে এবং Search Engine-কে অতিরিক্ত তথ্য প্রদান করে।

---

### Semantic Layout Tags-এর গুরুত্ব

* Web Page-এর Structure পরিষ্কার করে।
* HTML Code আরও Readable এবং Maintainable হয়।
* SEO উন্নত করতে সাহায্য করে।
* Accessibility বৃদ্ধি করে।
* Screen Reader সহজে Content বুঝতে পারে।
* বড় Website তৈরি ও পরিচালনা করা সহজ হয়।

---

### Block Level Element

Semantic Layout Tags-এর সবগুলোই **Block Level Element**।

| Tag         | Element Type |
| ----------- | ------------ |
| `<header>`  | Block Level  |
| `<nav>`     | Block Level  |
| `<main>`    | Block Level  |
| `<section>` | Block Level  |
| `<article>` | Block Level  |
| `<aside>`   | Block Level  |
| `<footer>`  | Block Level  |
| `<address>` | Block Level  |

---

### বাস্তব উদাহরণ

ধরুন একটি **সংবাদপত্র (Newspaper)** কল্পনা করুন।

| HTML Tag    | সংবাদপত্রের সাথে তুলনা             |
| ----------- | ---------------------------------- |
| `<header>`  | পত্রিকার নাম ও শিরোনাম             |
| `<nav>`     | সূচিপত্র বা বিভাগ                  |
| `<main>`    | মূল সংবাদ                          |
| `<section>` | খেলাধুলা, রাজনীতি, প্রযুক্তি বিভাগ |
| `<article>` | একটি নির্দিষ্ট সংবাদ               |
| `<aside>`   | পাশের বিজ্ঞাপন বা সম্পর্কিত খবর    |
| `<footer>`  | প্রকাশকের তথ্য                     |
| `<address>` | অফিসের ঠিকানা ও যোগাযোগ            |

যেমন একটি সংবাদপত্রে প্রতিটি অংশের আলাদা কাজ থাকে, ঠিক তেমনি Semantic Layout Tags একটি Web Page-এর প্রতিটি অংশকে অর্থপূর্ণভাবে ভাগ করে।

---

### Semantic Layout Tags বনাম `<div>`

| `<div>`                       | Semantic Layout Tags            |
| ----------------------------- | ------------------------------- |
| কোনো অর্থ প্রকাশ করে না       | অর্থপূর্ণ Structure প্রদান করে  |
| Generic Container             | নির্দিষ্ট কাজ নির্দেশ করে       |
| SEO-তে কম সহায়ক              | SEO-Friendly                    |
| Accessibility কম              | Accessibility বেশি              |
| Browser Content বুঝতে পারে না | Browser সহজে Content বুঝতে পারে |

---

### সারসংক্ষেপ

Semantic Layout Tags HTML5-এর অন্যতম গুরুত্বপূর্ণ Feature, যা Web Page-এর Structure অর্থপূর্ণভাবে তৈরি করতে ব্যবহৃত হয়। HTML-এ মোট **৮টি প্রধান Semantic Layout Tag** রয়েছে—`<header>`, `<nav>`, `<main>`, `<section>`, `<article>`, `<aside>`, `<footer>` এবং `<address>`। এই Tag-গুলোর মাধ্যমে একটি Website আরও পরিষ্কার, সংগঠিত, SEO-Friendly এবং Accessible হয়। আধুনিক Web Development-এ Semantic Layout Tags ব্যবহার করা একটি Best Practice।






## 14. Interactive Tags

Interactive Tags হলো HTML-এর এমন কিছু Tag, যা **ব্যবহারকারীর (User) সাথে সরাসরি Interaction (মিথস্ক্রিয়া)** করার জন্য ব্যবহৃত হয়। এই Tag-গুলোর মাধ্যমে ব্যবহারকারী কোনো তথ্য **খুলতে (Expand), বন্ধ করতে (Collapse), অথবা Popup Dialog-এর মাধ্যমে কাজ করতে** পারে।

HTML5-এ Interactive Tags যুক্ত হওয়ার ফলে অনেক সাধারণ Interactive Feature JavaScript ছাড়াই তৈরি করা সম্ভব হয়েছে।

HTML-এ মোট **৩টি প্রধান Interactive Tag** রয়েছে।

---

### Interactive Tag কী?

Interactive Tag হলো এমন HTML Element, যা ব্যবহারকারীর কোনো Action (যেমন Click করা) অনুযায়ী Web Page-এর আচরণ পরিবর্তন করে।

এই Tag-গুলোর মাধ্যমে—

* তথ্য লুকিয়ে রাখা যায়।
* প্রয়োজন হলে তথ্য দেখানো যায়।
* Popup Dialog তৈরি করা যায়।
* User Experience (UX) উন্নত করা যায়।

---

### Interactive Tags-এর মৌলিক কাঠামো

```html id="t6p9rx"
<!DOCTYPE html>
<html>

<head>
    <title>Interactive Tags</title>
</head>

<body>

    <details>

        <summary>
            What is HTML?
        </summary>

        HTML stands for HyperText Markup Language.

    </details>

    <br>

    <dialog open>

        Welcome to HTML Learning!

    </dialog>

</body>

</html>
```

উপরের Code-এ HTML-এর Interactive Tags ব্যবহার করা হয়েছে।

---

### Interactive Tags-এর তালিকা

| নং | Tag                   | কাজ                                              |
| -- | --------------------- | ------------------------------------------------ |
| 97 | `<details></details>` | লুকানো Content Expand/Collapse করে               |
| 98 | `<summary></summary>` | `<details>`-এর শিরোনাম বা Clickable অংশ তৈরি করে |
| 99 | `<dialog></dialog>`   | Dialog Box বা Popup Window তৈরি করে              |

---

### Interactive Tags Structure

```text id="m2v8jk"
<details>
      │
      └── <summary>

<dialog>
```

---

### প্রতিটি Tag-এর সংক্ষিপ্ত পরিচয়

#### 97. `<details></details>`

* Expand এবং Collapse করা যায় এমন Content তৈরি করে।
* Browser ডিফল্টভাবে Content লুকিয়ে রাখে।
* ব্যবহারকারী Click করলে Content দেখা যায়।
* FAQ (Frequently Asked Questions) তৈরিতে খুবই জনপ্রিয়।

---

#### 98. `<summary></summary>`

* `<details>` Tag-এর শিরোনাম বা Clickable অংশ নির্ধারণ করে।
* ব্যবহারকারী এই অংশে Click করলে `<details>` খুলে বা বন্ধ হয়।
* একটি `<details>` Tag-এর প্রথম Child Element হিসেবে ব্যবহার করা উচিত।

---

#### 99. `<dialog></dialog>`

* Dialog Box বা Popup Window তৈরি করে।
* সাধারণত Message, Login Box, Confirmation Dialog অথবা Form প্রদর্শনের জন্য ব্যবহৃত হয়।
* JavaScript ব্যবহার করে Dialog Open এবং Close করা যায়।
* `open` Attribute ব্যবহার করলে Dialog শুরু থেকেই দৃশ্যমান থাকে।

---

### Browser কীভাবে Interactive Tags পড়ে?

Browser সাধারণত নিচের ধাপগুলো অনুসরণ করে—

```text id="g4q7ln"
HTML Document
      │
      ▼
Read Interactive Tag
      │
      ▼
Display Interactive Element
      │
      ▼
User Click
      │
      ▼
Update Display
```

Browser প্রথমে Interactive Element প্রদর্শন করে, তারপর ব্যবহারকারীর Action অনুযায়ী Content পরিবর্তন করে।

---

### Interactive Tags-এর গুরুত্ব

* JavaScript ছাড়াই সহজ Interactive Feature তৈরি করা যায়।
* FAQ Section তৈরি করা সহজ হয়।
* Popup Dialog তৈরি করা যায়।
* User Experience (UX) উন্নত করে।
* Web Page আরও আধুনিক ও ব্যবহারবান্ধব হয়।
* Accessibility উন্নত করতে সহায়তা করে।

---

### Block Level Element

| Tag         | Element Type                |
| ----------- | --------------------------- |
| `<details>` | Block Level                 |
| `<summary>` | Block Level (বিশেষ Element) |
| `<dialog>`  | Block Level                 |

---

### বাস্তব উদাহরণ

ধরুন একটি **FAQ (Frequently Asked Questions)** Page কল্পনা করুন।

| HTML Tag    | বাস্তব উদাহরণ                       |
| ----------- | ----------------------------------- |
| `<details>` | প্রশ্নের উত্তর লুকিয়ে রাখা অংশ     |
| `<summary>` | প্রশ্নের শিরোনাম                    |
| `<dialog>`  | Login Popup বা Confirmation Message |

যেমন একটি FAQ Page-এ প্রশ্নের উপর Click করলে উত্তর দেখা যায়, ঠিক তেমনি `<details>` এবং `<summary>` Tag একসাথে কাজ করে। আবার কোনো Website-এ Login Popup বা সতর্কবার্তা দেখানোর জন্য `<dialog>` ব্যবহার করা যায়।

---

### Interactive Tags বনাম সাধারণ Content

| সাধারণ Content        | Interactive Content                            |
| --------------------- | ---------------------------------------------- |
| সব সময় দৃশ্যমান      | প্রয়োজন অনুযায়ী দেখা যায়                    |
| User Interaction কম   | User Interaction বেশি                          |
| স্থির (Static)        | পরিবর্তনশীল (Dynamic Behavior)                 |
| শুধুমাত্র তথ্য দেখায় | ব্যবহারকারীর Action অনুযায়ী প্রতিক্রিয়া দেয় |

---

### সারসংক্ষেপ

Interactive Tags HTML5-এর একটি গুরুত্বপূর্ণ Tag Group, যা Web Page-এ ব্যবহারকারীর সাথে Interaction তৈরি করতে ব্যবহৃত হয়। HTML-এ মোট **৩টি প্রধান Interactive Tag** রয়েছে—`<details>`, `<summary>` এবং `<dialog>`। এগুলোর মাধ্যমে Expand/Collapse Content, FAQ Section এবং Popup Dialog সহজেই তৈরি করা যায়। JavaScript ছাড়াই অনেক সাধারণ Interactive Feature তৈরির জন্য এই Tag-গুলো অত্যন্ত কার্যকর এবং আধুনিক Web Development-এ ব্যাপকভাবে ব্যবহৃত হয়।






## 15. Embedded Content Tags

Embedded Content Tags হলো HTML-এর এমন কিছু Tag, যা **অন্য কোনো Web Page, File, Document, PDF, Multimedia অথবা External Resource** একটি Web Page-এর ভিতরে **Embed (সংযুক্ত বা প্রদর্শন)** করার জন্য ব্যবহৃত হয়।

এই Tag-গুলোর মাধ্যমে একটি Website-এর ভিতরে অন্য Website, PDF, Map, Animation, Plugin Content অথবা বিভিন্ন ধরনের External File দেখানো যায়।

HTML-এ Embedded Content প্রদর্শনের জন্য মোট **৪টি প্রধান Tag** রয়েছে।

---

### Embedded Content Tag কী?

Embedded Content Tag হলো এমন HTML Element, যা বর্তমান Web Page-এর মধ্যে অন্য কোনো Resource যুক্ত বা প্রদর্শন করার জন্য ব্যবহৃত হয়।

এই Resource হতে পারে—

* অন্য Website
* YouTube Video
* Google Map
* PDF File
* HTML Page
* Flash (পুরোনো)
* Multimedia File
* Plugin Content

---

### Embedded Content Tags-এর মৌলিক কাঠামো

```html id="y7m2qd"
<!DOCTYPE html>
<html>

<head>
    <title>Embedded Content Tags</title>
</head>

<body>

    <iframe
        src="https://example.com"
        width="600"
        height="300">
    </iframe>

    <br><br>

    <embed
        src="sample.pdf"
        width="500"
        height="300">

    <br><br>

    <object
        data="sample.pdf"
        width="500"
        height="300">

        <param
            name="zoom"
            value="100">

    </object>

</body>

</html>
```

উপরের Code-এ HTML-এর Embedded Content Tags ব্যবহার করা হয়েছে।

---

### Embedded Content Tags-এর তালিকা

| নং  | Tag                 | কাজ                                      |
| --- | ------------------- | ---------------------------------------- |
| 100 | `<iframe></iframe>` | অন্য Web Page বা Website Embed করে       |
| 101 | `<embed>`           | External File বা Multimedia Embed করে    |
| 102 | `<object></object>` | বিভিন্ন ধরনের Object বা File Embed করে   |
| 103 | `<param>`           | `<object>` Tag-এর Parameter নির্ধারণ করে |

---

### Embedded Content Tags Structure

```text id="k4x8nh"
<iframe>

<embed>

<object>
      │
      └── <param>
```

---

### প্রতিটি Tag-এর সংক্ষিপ্ত পরিচয়

#### 100. `<iframe></iframe>`

* Inline Frame তৈরি করে।
* একটি Web Page-এর ভিতরে অন্য Web Page বা Website প্রদর্শন করে।
* YouTube Video, Google Map এবং Online Document Embed করতে ব্যাপকভাবে ব্যবহৃত হয়।
* `src`, `width` এবং `height` Attribute বেশি ব্যবহৃত হয়।

---

#### 101. `<embed>`

* External Resource সরাসরি Embed করার জন্য ব্যবহৃত হয়।
* PDF, Audio, Video বা অন্যান্য Multimedia File প্রদর্শন করতে পারে।
* এটি একটি **Void (Empty) Element**।
* বর্তমানে `<iframe>` এবং `<object>` বেশি ব্যবহৃত হলেও `<embed>` এখনও সমর্থিত।

---

#### 102. `<object></object>`

* বিভিন্ন ধরনের File বা Object Embed করার জন্য ব্যবহৃত হয়।
* PDF, Image, Audio, Video এবং অন্যান্য Document প্রদর্শন করতে পারে।
* প্রয়োজনে বিকল্প (Fallback) Content-ও দেখানো যায়।

---

#### 103. `<param>`

* `<object>` Tag-এর জন্য অতিরিক্ত Parameter নির্ধারণ করে।
* যেমন—

  * Zoom Level
  * Auto Play
  * Quality
* এটি একটি **Void (Empty) Element**।
* শুধুমাত্র `<object>` Tag-এর ভিতরে ব্যবহার করা হয়।

---

### Browser কীভাবে Embedded Content Tags পড়ে?

Browser সাধারণত নিচের ধাপগুলো অনুসরণ করে—

```text id="n6v3zb"
HTML Document
      │
      ▼
Read Embedded Tag
      │
      ▼
Load External Resource
      │
      ▼
Render Embedded Content
      │
      ▼
Display Inside Web Page
```

Browser প্রথমে External Resource Load করে, তারপর সেটিকে বর্তমান Web Page-এর মধ্যে প্রদর্শন করে।

---

### Embedded Content Tags-এর গুরুত্ব

* অন্য Website Embed করা যায়।
* YouTube Video সহজে যুক্ত করা যায়।
* Google Map Embed করা যায়।
* PDF ও অন্যান্য Document দেখানো যায়।
* Multimedia Content প্রদর্শন করা যায়।
* User Experience (UX) উন্নত করে।
* Web Page-কে আরও তথ্যবহুল ও Interactive করে।

---

### Block Level, Inline এবং Void Element

| Tag        | Element Type |
| ---------- | ------------ |
| `<iframe>` | Inline       |
| `<embed>`  | Void Element |
| `<object>` | Inline       |
| `<param>`  | Void Element |

---

### বাস্তব উদাহরণ

ধরুন একটি **বিশ্ববিদ্যালয়ের Website** কল্পনা করুন।

| HTML Tag   | বাস্তব উদাহরণ                 |
| ---------- | ----------------------------- |
| `<iframe>` | Google Map বা YouTube Video   |
| `<embed>`  | Prospectus PDF                |
| `<object>` | PDF Document বা অন্য File     |
| `<param>`  | PDF Zoom বা অন্যান্য Settings |

যেমন একটি বিশ্ববিদ্যালয়ের Website-এ ক্যাম্পাসের Google Map, ভর্তি নির্দেশিকার PDF এবং একটি পরিচিতিমূলক Video একই Page-এ দেখা যায়, ঠিক তেমনি Embedded Content Tags ব্যবহার করে এসব Resource সহজেই যুক্ত করা যায়।

---

### `<iframe>` বনাম `<embed>` বনাম `<object>`

| Tag        | প্রধান ব্যবহার                         |
| ---------- | -------------------------------------- |
| `<iframe>` | অন্য Website বা Web Page Embed         |
| `<embed>`  | Multimedia বা External File Embed      |
| `<object>` | বিভিন্ন ধরনের Object বা Document Embed |
| `<param>`  | `<object>`-এর অতিরিক্ত Parameter       |

---

### সারসংক্ষেপ

Embedded Content Tags HTML-এর গুরুত্বপূর্ণ Tag Group, যা একটি Web Page-এর ভিতরে অন্য Web Page, PDF, Video, Map এবং অন্যান্য External Resource প্রদর্শনের জন্য ব্যবহৃত হয়। HTML-এ মোট **৪টি প্রধান Embedded Content Tag** রয়েছে—`<iframe>`, `<embed>`, `<object>` এবং `<param>`। এগুলোর মাধ্যমে Website-কে আরও সমৃদ্ধ (Rich), তথ্যবহুল (Informative) এবং Interactive করা যায়। আধুনিক Web Development-এ বিশেষ করে YouTube Video, Google Map এবং PDF Embed করার জন্য এই Tag-গুলোর ব্যবহার অত্যন্ত গুরুত্বপূর্ণ।






## 16. Graphics Tags

Graphics Tags হলো HTML-এর এমন কিছু Tag, যা **Web Page-এ বিভিন্ন ধরনের Graphics, Drawing, Shape, Chart, Icon, Animation এবং Vector Image** তৈরি ও প্রদর্শনের জন্য ব্যবহৃত হয়। HTML5-এ Graphics-এর জন্য বিশেষ দুটি Tag যোগ করা হয়েছে, যার মাধ্যমে JavaScript ব্যবহার করে Dynamic Graphics তৈরি করা যায় অথবা SVG ব্যবহার করে উচ্চমানের Vector Graphics প্রদর্শন করা যায়।

Graphics Tags ব্যবহার করে—

* Shape আঁকা যায়।
* Chart ও Graph তৈরি করা যায়।
* Animation তৈরি করা যায়।
* Logo এবং Icon প্রদর্শন করা যায়।
* Game Graphics তৈরি করা যায়।

HTML-এ Graphics তৈরির জন্য মোট **২টি প্রধান Tag** রয়েছে।

---

### Graphics Tag কী?

Graphics Tag হলো এমন HTML Element, যা Web Page-এর মধ্যে বিভিন্ন ধরনের Graphics তৈরি, আঁকা অথবা প্রদর্শনের জন্য ব্যবহৃত হয়।

Graphics Tags-এর মাধ্যমে—

* Pixel ভিত্তিক Drawing করা যায়।
* Vector ভিত্তিক Graphics তৈরি করা যায়।
* Interactive Graphics তৈরি করা যায়।

---

### Graphics Tags-এর মৌলিক কাঠামো

```html id="x4n8qj"
<!DOCTYPE html>
<html>

<head>
    <title>Graphics Tags</title>
</head>

<body>

    <canvas
        id="myCanvas"
        width="300"
        height="200">
    </canvas>

    <br><br>

    <svg
        width="300"
        height="200">

        <circle
            cx="100"
            cy="100"
            r="60"
            fill="blue">

        </circle>

    </svg>

</body>

</html>
```

উপরের Code-এ HTML-এর Graphics Tags ব্যবহার করা হয়েছে।

---

### Graphics Tags-এর তালিকা

| নং  | Tag                 | কাজ                                 |
| --- | ------------------- | ----------------------------------- |
| 104 | `<canvas></canvas>` | JavaScript-এর মাধ্যমে Graphics আঁকে |
| 105 | `<svg></svg>`       | Vector Graphics তৈরি করে            |

---

### Graphics Tags Structure

```text id="d2m7vp"
<canvas>

<svg>
     │
     ├── <circle>
     ├── <rect>
     ├── <line>
     ├── <ellipse>
     ├── <polygon>
     ├── <polyline>
     └── <path>
```

> **দ্রষ্টব্য:** `<circle>`, `<rect>`, `<line>` ইত্যাদি SVG-এর নিজস্ব Element, যা `<svg>` Tag-এর ভিতরে ব্যবহার করা হয়।

---

### প্রতিটি Tag-এর সংক্ষিপ্ত পরিচয়

#### 104. `<canvas></canvas>`

* JavaScript ব্যবহার করে Graphics আঁকার জন্য ব্যবহৃত হয়।
* এটি একটি খালি Drawing Area প্রদান করে।
* Drawing, Animation, Game এবং Chart তৈরিতে ব্যবহৃত হয়।
* Pixel ভিত্তিক (Raster) Graphics তৈরি করে।
* Canvas-এর ভিতরের Graphics JavaScript ছাড়া তৈরি করা যায় না।

---

#### 105. `<svg></svg>`

* SVG (Scalable Vector Graphics) তৈরি করার জন্য ব্যবহৃত হয়।
* XML ভিত্তিক Vector Graphics Format।
* যেকোনো আকারে বড় বা ছোট করলেও Quality নষ্ট হয় না।
* Logo, Icon, Diagram, Chart এবং Illustration তৈরিতে ব্যবহৃত হয়।
* JavaScript ছাড়াও SVG Element ব্যবহার করে Graphics তৈরি করা যায়।

---

### Browser কীভাবে Graphics Tags পড়ে?

Browser সাধারণত নিচের ধাপগুলো অনুসরণ করে—

```text id="u5k9hr"
HTML Document
      │
      ▼
Read Graphics Tag
      │
      ▼
Generate Graphics
      │
      ▼
Render Graphics
      │
      ▼
Display on Screen
```

যদি `<canvas>` ব্যবহার করা হয়, Browser JavaScript-এর মাধ্যমে Graphics তৈরি করে। আর `<svg>` ব্যবহার করলে Browser সরাসরি SVG Element Render করে।

---

### Graphics Tags-এর গুরুত্ব

* Website-এ সুন্দর Graphics তৈরি করা যায়।
* Interactive Animation তৈরি করা যায়।
* Chart ও Data Visualization করা যায়।
* Logo ও Icon তৈরি করা যায়।
* Browser-এ অতিরিক্ত Plugin ছাড়াই Graphics প্রদর্শন করা যায়।
* Game Development-এ ব্যবহার করা হয়।
* User Experience (UX) উন্নত করে।

---

### Block Level Element

| Tag        | Element Type   |
| ---------- | -------------- |
| `<canvas>` | Inline Element |
| `<svg>`    | Inline Element |

> **নোট:** যদিও `<canvas>` এবং `<svg>` অনেক সময় Block-এর মতো প্রদর্শিত হতে পারে, HTML Specification অনুযায়ী এগুলো সাধারণত **Inline Element** হিসেবে গণ্য করা হয়।

---

### `<canvas>` বনাম `<svg>`

| `<canvas>`                        | `<svg>`                                 |
| --------------------------------- | --------------------------------------- |
| Pixel ভিত্তিক Graphics            | Vector ভিত্তিক Graphics                 |
| JavaScript প্রয়োজন               | JavaScript ছাড়াও ব্যবহার করা যায়      |
| Animation ও Game-এর জন্য উপযোগী   | Logo, Icon ও Diagram-এর জন্য উপযোগী     |
| Resize করলে Quality কমতে পারে     | Resize করলেও Quality অপরিবর্তিত থাকে    |
| Drawing শেষে Pixel Image তৈরি হয় | প্রতিটি Shape আলাদা Element হিসেবে থাকে |

---

### বাস্তব উদাহরণ

ধরুন একটি **Online Dashboard** কল্পনা করুন।

| HTML Tag   | বাস্তব উদাহরণ                           |
| ---------- | --------------------------------------- |
| `<canvas>` | Sales Chart, Online Game, Drawing Board |
| `<svg>`    | Company Logo, Icon, Flowchart, Map      |

যেমন একটি Dashboard-এ Live Chart দেখা যায়, সেটি প্রায়ই `<canvas>` ব্যবহার করে তৈরি হয়। আবার কোনো Website-এর Logo বা Icon সাধারণত `<svg>` ব্যবহার করে তৈরি করা হয়, যাতে বড় বা ছোট করলেও ছবির মান ঠিক থাকে।

---

### সারসংক্ষেপ

Graphics Tags HTML5-এর একটি গুরুত্বপূর্ণ Feature, যা Website-এ Graphics তৈরি ও প্রদর্শনের জন্য ব্যবহৃত হয়। HTML-এ মোট **২টি প্রধান Graphics Tag** রয়েছে—`<canvas>` এবং `<svg>`। `<canvas>` JavaScript-এর মাধ্যমে Pixel ভিত্তিক Graphics, Animation এবং Game তৈরির জন্য ব্যবহৃত হয়, আর `<svg>` Vector ভিত্তিক Graphics, Logo, Icon এবং Diagram তৈরির জন্য ব্যবহৃত হয়। আধুনিক Web Development-এ আকর্ষণীয়, Responsive এবং Interactive Graphics তৈরিতে এই Tag-গুলোর ভূমিকা অত্যন্ত গুরুত্বপূর্ণ।






## 17. Web Components

Web Components হলো HTML-এর এমন একটি আধুনিক প্রযুক্তি, যার মাধ্যমে **নিজস্ব (Custom) HTML Element** তৈরি করা যায়। অর্থাৎ, HTML-এর Built-in Tag যেমন `<div>`, `<button>` বা `<table>`-এর পাশাপাশি আমরা নিজের প্রয়োজন অনুযায়ী নতুন Tag তৈরি করতে পারি।

Web Components ব্যবহার করলে একটি Component একবার তৈরি করে Website-এর বিভিন্ন জায়গায় বারবার ব্যবহার করা যায়। এর ফলে Code আরও **Reusable, Modular, Maintainable এবং Scalable** হয়।

HTML-এ Web Components-এর জন্য এই অধ্যায়ে **২টি প্রধান Tag** রয়েছে।

---

### Web Components কী?

Web Components হলো Web Platform-এর একটি Feature, যা HTML, CSS এবং JavaScript ব্যবহার করে **Reusable Custom Component** তৈরি করার সুযোগ দেয়।

একটি Web Component-এর মাধ্যমে—

* Custom HTML Element তৈরি করা যায়।
* একই Component বারবার ব্যবহার করা যায়।
* CSS ও JavaScript আলাদা রাখা যায়।
* বড় Project সহজে পরিচালনা করা যায়।

---

### Web Components-এর মৌলিক কাঠামো

```html id="v3n8pk"
<!DOCTYPE html>
<html>

<head>
    <title>Web Components</title>
</head>

<body>

    <template id="cardTemplate">

        <div class="card">

            <h2>Product Name</h2>

            <p>Product Description</p>

            <button>Buy Now</button>

        </div>

    </template>

    <my-card>

        <slot>
            Default Content
        </slot>

    </my-card>

</body>

</html>
```

উপরের Code-এ `<template>` এবং `<slot>` Tag ব্যবহার করে একটি সাধারণ Web Component-এর ধারণা দেখানো হয়েছে।

---

### Web Components Tags-এর তালিকা

| নং  | Tag                     | কাজ                                                      |
| --- | ----------------------- | -------------------------------------------------------- |
| 106 | `<template></template>` | পুনঃব্যবহারযোগ্য (Reusable) HTML Template সংরক্ষণ করে    |
| 107 | `<slot></slot>`         | Component-এর ভিতরে Content প্রদর্শনের স্থান নির্ধারণ করে |

---

### Web Components Structure

```text id="n8w5xy"
<template>
      │
      ▼
Reusable HTML Structure
      │
      ▼
Custom Component
      │
      ▼
<slot>
      │
      ▼
User Content
```

---

### প্রতিটি Tag-এর সংক্ষিপ্ত পরিচয়

#### 106. `<template></template>`

* Reusable HTML Structure সংরক্ষণ করে।
* Browser প্রথমে এই Content প্রদর্শন করে না।
* JavaScript ব্যবহার করে প্রয়োজন হলে Template থেকে Content তৈরি করা হয়।
* একই Layout বারবার ব্যবহার করার জন্য খুবই উপযোগী।

---

#### 107. `<slot></slot>`

* Custom Component-এর ভিতরে Content প্রদর্শনের জন্য Placeholder হিসেবে কাজ করে।
* Component ব্যবহারকারী যে Content দেয়, সেটি `<slot>`-এর স্থানে প্রদর্শিত হয়।
* Default Content-ও নির্ধারণ করা যায়।

---

### Browser কীভাবে Web Components পড়ে?

Browser সাধারণত নিচের ধাপগুলো অনুসরণ করে—

```text id="j2r6mq"
HTML Document
      │
      ▼
Read <template>
      │
      ▼
Wait for JavaScript
      │
      ▼
Create Custom Component
      │
      ▼
Insert <slot> Content
      │
      ▼
Render Component
```

Browser প্রথমে `<template>`-এর Content লুকিয়ে রাখে। পরে JavaScript Component তৈরি করলে সেই Template ব্যবহার করে Content Render করে এবং `<slot>`-এ ব্যবহারকারীর দেওয়া Content প্রদর্শন করে।

---

### Web Components-এর গুরুত্ব

* Reusable Component তৈরি করা যায়।
* Code-এর পুনরাবৃত্তি (Code Duplication) কমে।
* বড় Project পরিচালনা সহজ হয়।
* HTML, CSS এবং JavaScript সুন্দরভাবে সংগঠিত রাখা যায়।
* Maintainability বৃদ্ধি পায়।
* Modern Frontend Development-এর গুরুত্বপূর্ণ অংশ।

---

### Block Level Element

| Tag          | Element Type                         |
| ------------ | ------------------------------------ |
| `<template>` | Metadata / Script Supporting Element |
| `<slot>`     | Inline Element (Shadow DOM-এর অংশ)   |

> **নোট:** `<slot>` সাধারণ HTML Page-এ নয়, মূলত **Web Components-এর Shadow DOM**-এর ভিতরে ব্যবহৃত হয়।

---

### `<template>` বনাম `<slot>`

| `<template>`                   | `<slot>`                                    |
| ------------------------------ | ------------------------------------------- |
| HTML Structure সংরক্ষণ করে     | Content প্রদর্শনের স্থান নির্ধারণ করে       |
| শুরুতে Browser প্রদর্শন করে না | Component Render হওয়ার সময় Content দেখায় |
| JavaScript দিয়ে Clone করা হয় | User-এর Content গ্রহণ করে                   |
| Reusable Layout তৈরি করে       | Dynamic Content প্রদর্শন করে                |

---

### বাস্তব উদাহরণ

ধরুন একটি **E-commerce Website** কল্পনা করুন।

| HTML Tag     | বাস্তব উদাহরণ                                 |
| ------------ | --------------------------------------------- |
| `<template>` | Product Card-এর ডিজাইন সংরক্ষণ                |
| `<slot>`     | Product Name, Price বা Image প্রদর্শনের স্থান |

যেমন একটি Online Shop-এ শত শত Product Card দেখতে একই রকম হয়, কিন্তু প্রতিটি Card-এর তথ্য আলাদা। এই ধরনের ক্ষেত্রে একটি Template তৈরি করে প্রতিটি Product-এর তথ্য `<slot>`-এর মাধ্যমে দেখানো যায়।

---

### Web Components-এর ব্যবহার

Web Components ব্যবহার করে তৈরি করা যায়—

* Product Card
* User Profile Card
* Navigation Bar
* Modal Box
* Alert Box
* Login Form
* Dashboard Widget
* Custom Button
* Image Gallery
* Reusable UI Component

---

### সারসংক্ষেপ

Web Components হলো আধুনিক Web Development-এর একটি শক্তিশালী প্রযুক্তি, যা Reusable এবং Custom HTML Component তৈরির সুযোগ দেয়। এই অধ্যায়ে ব্যবহৃত **২টি প্রধান Tag** হলো `<template>` এবং `<slot>`। `<template>` পুনঃব্যবহারযোগ্য HTML Structure সংরক্ষণ করে এবং `<slot>` Component-এর ভিতরে Dynamic Content প্রদর্শনের স্থান নির্ধারণ করে। বড় এবং Professional Website তৈরিতে Web Components Code Reusability, Maintainability এবং Scalability উল্লেখযোগ্যভাবে বৃদ্ধি করে।






## 18. Ruby Annotation Tags

Ruby Annotation Tags হলো HTML-এর এমন কিছু Tag, যা **মূল লেখার (Base Text) উপরে বা পাশে ছোট আকারে উচ্চারণ (Pronunciation), অর্থ (Meaning) অথবা ব্যাখ্যা (Annotation)** প্রদর্শনের জন্য ব্যবহৃত হয়। এই Tag-গুলো বিশেষভাবে **জাপানি (Japanese), চীনা (Chinese) এবং কোরিয়ান (Korean)** ভাষায় ব্যবহৃত হয়, যেখানে একটি অক্ষরের সঠিক উচ্চারণ বা অর্থ দেখানোর প্রয়োজন হয়।

HTML-এ Ruby Annotation প্রদর্শনের জন্য মোট **৩টি প্রধান Tag** রয়েছে।

---

### Ruby Annotation Tag কী?

Ruby Annotation Tag হলো এমন HTML Element, যা কোনো শব্দ বা অক্ষরের সাথে অতিরিক্ত তথ্য, যেমন উচ্চারণ বা ব্যাখ্যা, ছোট আকারে প্রদর্শন করার জন্য ব্যবহৃত হয়।

Ruby Annotation-এর মাধ্যমে—

* শব্দের উচ্চারণ দেখানো যায়।
* কঠিন শব্দের অর্থ বোঝানো যায়।
* ভাষা শেখা সহজ হয়।
* Educational Website তৈরি করা যায়।

---

### Ruby Annotation Tags-এর মৌলিক কাঠামো

```html id="a7k4mz"
<!DOCTYPE html>
<html>

<head>
    <title>Ruby Annotation Tags</title>
</head>

<body>

    <ruby>

        漢

        <rt>かん</rt>

        <rp>(</rp>
        <rp>)</rp>

    </ruby>

</body>

</html>
```

উপরের Code-এ একটি Japanese Character-এর উচ্চারণ Ruby Annotation-এর মাধ্যমে দেখানো হয়েছে।

---

### Ruby Annotation Tags-এর তালিকা

| নং  | Tag             | কাজ                                            |
| --- | --------------- | ---------------------------------------------- |
| 108 | `<ruby></ruby>` | মূল Text এবং Annotation-এর Container           |
| 109 | `<rt></rt>`     | উচ্চারণ বা Annotation প্রদর্শন করে             |
| 110 | `<rp></rp>`     | Ruby Support না থাকলে বিকল্প Text প্রদর্শন করে |

---

### Ruby Annotation Tags Structure

```text id="v5n2xt"
<ruby>
     │
     ├── Base Text
     │
     ├── <rt>
     │
     └── <rp>
```

---

### প্রতিটি Tag-এর সংক্ষিপ্ত পরিচয়

#### 108. `<ruby></ruby>`

* Ruby Annotation-এর মূল Container।
* Base Text এবং Annotation-কে একসাথে ধারণ করে।
* সাধারণত `<rt>` এবং `<rp>` Tag-এর সাথে ব্যবহার করা হয়।

---

#### 109. `<rt></rt>`

* Ruby Text (Annotation) প্রদর্শন করে।
* সাধারণত Base Text-এর উপরে ছোট আকারে দেখা যায়।
* উচ্চারণ, অর্থ অথবা ব্যাখ্যা লেখার জন্য ব্যবহৃত হয়।

---

#### 110. `<rp></rp>`

* Browser যদি Ruby Annotation সমর্থন না করে, তাহলে বিকল্প চিহ্ন (যেমন বন্ধনী) প্রদর্শন করে।
* সাধারণত `<rt>` Tag-এর আগে ও পরে ব্যবহার করা হয়।
* পুরোনো Browser-এর জন্য Compatibility বৃদ্ধি করে।

---

### Browser কীভাবে Ruby Annotation Tags পড়ে?

Browser সাধারণত নিচের ধাপগুলো অনুসরণ করে—

```text id="y8m6qw"
HTML Document
      │
      ▼
Read <ruby>
      │
      ▼
Read Base Text
      │
      ▼
Read <rt>
      │
      ▼
Display Annotation
```

যদি Browser Ruby Annotation সমর্থন না করে, তাহলে `<rp>`-এর ভিতরের বিকল্প Text প্রদর্শিত হতে পারে।

---

### Ruby Annotation Tags-এর গুরুত্ব

* উচ্চারণ শেখাতে সাহায্য করে।
* ভাষা শিক্ষার Website তৈরিতে উপযোগী।
* Japanese, Chinese এবং Korean ভাষায় ব্যাপকভাবে ব্যবহৃত হয়।
* কঠিন শব্দ সহজে বোঝানো যায়।
* Accessibility এবং পাঠযোগ্যতা (Readability) বৃদ্ধি করে।

---

### Inline Element

Ruby Annotation-এর সবগুলো Tag সাধারণত **Inline Element**।

| Tag      | Element Type |
| -------- | ------------ |
| `<ruby>` | Inline       |
| `<rt>`   | Inline       |
| `<rp>`   | Inline       |

---

### বাস্তব উদাহরণ

ধরুন আপনি একটি **Japanese Learning Website** তৈরি করছেন।

| HTML Tag | বাস্তব উদাহরণ                        |
| -------- | ------------------------------------ |
| `<ruby>` | Japanese শব্দ                        |
| `<rt>`   | শব্দের উচ্চারণ                       |
| `<rp>`   | পুরোনো Browser-এর জন্য বিকল্প বন্ধনী |

উদাহরণস্বরূপ, একটি Japanese অক্ষরের উপরে ছোট করে তার উচ্চারণ লেখা থাকে। এটি Ruby Annotation-এর মাধ্যমে করা হয়, যাতে নতুন শিক্ষার্থীরা সহজে শব্দটি পড়তে পারে।

---

### Ruby Annotation Tags-এর ব্যবহার

Ruby Annotation Tags সাধারণত ব্যবহৃত হয়—

* Japanese Learning Website
* Chinese Dictionary
* Korean Language Learning
* Online Education Platform
* Digital Book
* E-book Reader
* Language Tutorial
* Educational Blog

---

### সারসংক্ষেপ

Ruby Annotation Tags HTML-এর একটি বিশেষ Tag Group, যা মূল লেখার সাথে উচ্চারণ, অর্থ বা ব্যাখ্যা প্রদর্শনের জন্য ব্যবহৃত হয়। HTML-এ মোট **৩টি প্রধান Ruby Annotation Tag** রয়েছে—`<ruby>`, `<rt>` এবং `<rp>`। `<ruby>` মূল Container হিসেবে কাজ করে, `<rt>` Annotation বা উচ্চারণ প্রদর্শন করে এবং `<rp>` পুরোনো Browser-এর জন্য বিকল্প Text প্রদান করে। বিশেষ করে Japanese, Chinese এবং Korean ভাষাভিত্তিক Website ও Educational Platform তৈরিতে Ruby Annotation Tags অত্যন্ত গুরুত্বপূর্ণ।






## 19. Deprecated Tags

Deprecated Tags হলো HTML-এর এমন কিছু Tag, যেগুলো **আগে HTML-এ ব্যবহৃত হতো, কিন্তু বর্তমানে HTML5-এ আর ব্যবহার করার পরামর্শ দেওয়া হয় না।** এগুলোর পরিবর্তে আধুনিক HTML এবং CSS-এর নতুন পদ্ধতি ব্যবহার করা হয়।

"**Deprecated**" শব্দের অর্থ হলো **বাতিল ঘোষিত (No Longer Recommended)**। অর্থাৎ Browser এখনো অনেক ক্ষেত্রে এই Tag-গুলো সমর্থন করতে পারে, কিন্তু নতুন Website তৈরিতে এগুলো ব্যবহার করা উচিত নয়।

HTML-এ মোট **১১টি উল্লেখযোগ্য Deprecated Tag** রয়েছে।

---

### Deprecated Tag কী?

Deprecated Tag হলো এমন HTML Element, যেগুলো একসময় HTML Standard-এর অংশ ছিল, কিন্তু বর্তমানে নতুন ও উন্নত প্রযুক্তি (বিশেষ করে CSS এবং Semantic HTML) দ্বারা প্রতিস্থাপিত হয়েছে।

এই Tag-গুলো ব্যবহার করলে—

* Code আধুনিক Standard অনুসরণ করে না।
* Website Maintain করা কঠিন হয়।
* ভবিষ্যতে Browser Support কমে যেতে পারে।

---

### Deprecated Tags-এর তালিকা

| নং  | Tag                     | পূর্বের ব্যবহার                | বর্তমানে বিকল্প                          |
| --- | ----------------------- | ------------------------------ | ---------------------------------------- |
| 111 | `<center></center>`     | Content মাঝখানে আনা            | CSS `text-align:center`                  |
| 112 | `<font></font>`         | Font Style পরিবর্তন            | CSS `font-family`, `font-size`, `color`  |
| 113 | `<big></big>`           | বড় Text দেখানো                | CSS `font-size`                          |
| 114 | `<tt></tt>`             | Typewriter Font                | CSS `font-family: monospace` বা `<code>` |
| 115 | `<strike></strike>`     | Text-এর মাঝখানে দাগ            | `<del>` বা CSS `text-decoration`         |
| 116 | `<frameset></frameset>` | Frame Layout তৈরি              | CSS Layout + `<iframe>`                  |
| 117 | `<frame>`               | Frame প্রদর্শন                 | `<iframe>`                               |
| 118 | `<noframes></noframes>` | Frame Support না থাকলে Content | আধুনিক Browser-এ প্রয়োজন নেই            |
| 119 | `<acronym></acronym>`   | Acronym ব্যাখ্যা               | `<abbr>`                                 |
| 120 | `<applet></applet>`     | Java Applet চালানো             | JavaScript, Web API                      |
| 121 | `<dir></dir>`           | Directory List                 | `<ul>`                                   |

---

### Deprecated Tags-এর সংক্ষিপ্ত পরিচয়

#### 111. `<center></center>`

* Content মাঝখানে (Center) দেখানোর জন্য ব্যবহৃত হতো।
* বর্তমানে CSS-এর `text-align: center;` ব্যবহার করা হয়।

---

#### 112. `<font></font>`

* Font-এর Size, Color এবং Style পরিবর্তনের জন্য ব্যবহৃত হতো।
* বর্তমানে CSS ব্যবহার করা হয়।

---

#### 113. `<big></big>`

* Text বড় করে দেখানোর জন্য ব্যবহৃত হতো।
* বর্তমানে CSS-এর `font-size` ব্যবহার করা হয়।

---

#### 114. `<tt></tt>`

* Typewriter Style বা Monospace Font প্রদর্শনের জন্য ব্যবহৃত হতো।
* বর্তমানে `<code>` অথবা CSS-এর `font-family: monospace;` ব্যবহার করা হয়।

---

#### 115. `<strike></strike>`

* Text-এর মাঝখানে দাগ (Strike Through) দেওয়ার জন্য ব্যবহৃত হতো।
* বর্তমানে `<del>` অথবা CSS-এর `text-decoration: line-through;` ব্যবহার করা হয়।

---

#### 116. `<frameset></frameset>`

* Browser Window-কে একাধিক Frame-এ ভাগ করার জন্য ব্যবহৃত হতো।
* HTML5-এ সম্পূর্ণভাবে বাতিল করা হয়েছে।

---

#### 117. `<frame>`

* `<frameset>`-এর ভিতরে প্রতিটি Frame তৈরি করার জন্য ব্যবহৃত হতো।
* বর্তমানে `<iframe>` ব্যবহার করা হয়।

---

#### 118. `<noframes></noframes>`

* Browser যদি Frame Support না করত, তাহলে বিকল্প Content দেখানোর জন্য ব্যবহৃত হতো।
* বর্তমানে এর প্রয়োজন নেই।

---

#### 119. `<acronym></acronym>`

* কোনো Acronym বা সংক্ষিপ্ত শব্দের অর্থ বোঝাতে ব্যবহৃত হতো।
* বর্তমানে `<abbr>` ব্যবহার করা হয়।

---

#### 120. `<applet></applet>`

* Java Applet চালানোর জন্য ব্যবহৃত হতো।
* নিরাপত্তা (Security) এবং Browser Compatibility-এর কারণে এটি বাতিল করা হয়েছে।

---

#### 121. `<dir></dir>`

* Directory List তৈরি করার জন্য ব্যবহৃত হতো।
* বর্তমানে `<ul>` এবং `<li>` ব্যবহার করা হয়।

---

### Browser কীভাবে Deprecated Tags পড়ে?

Browser সাধারণত নিচের ধাপগুলো অনুসরণ করে—

```text id="q7m4yv"
HTML Document
      │
      ▼
Read Deprecated Tag
      │
      ▼
Check Browser Support
      │
      ▼
Render Content
```

অনেক আধুনিক Browser এখনো এই Tag-গুলোর কিছু সমর্থন করে, তবে এগুলোর ব্যবহার নিরুৎসাহিত করা হয়।

---

### Deprecated Tags-এর সমস্যা

* HTML5 Standard অনুসরণ করে না।
* Code Maintain করা কঠিন হয়।
* CSS-এর সুবিধা পাওয়া যায় না।
* SEO-এর জন্য উপযুক্ত নয়।
* Accessibility কমে যেতে পারে।
* ভবিষ্যতের Browser-এ Support বন্ধ হয়ে যেতে পারে।

---

### Deprecated Tags-এর পরিবর্তে কী ব্যবহার করবেন?

| Deprecated Tag | আধুনিক বিকল্প             |
| -------------- | ------------------------- |
| `<center>`     | CSS `text-align: center;` |
| `<font>`       | CSS                       |
| `<big>`        | CSS `font-size`           |
| `<tt>`         | `<code>` বা CSS           |
| `<strike>`     | `<del>`                   |
| `<frameset>`   | CSS Layout                |
| `<frame>`      | `<iframe>`                |
| `<noframes>`   | প্রয়োজন নেই              |
| `<acronym>`    | `<abbr>`                  |
| `<applet>`     | JavaScript / Web API      |
| `<dir>`        | `<ul>`                    |

---

### বাস্তব উদাহরণ

ধরুন আপনি একটি **পুরোনো Website** আপডেট করছেন।

আগে—

```html id="0sd9hv"
<center>
    Welcome
</center>
```

বর্তমানে—

```html id="6d8lpa"
<div style="text-align: center;">
    Welcome
</div>
```

আরেকটি উদাহরণ—

আগে—

```html id="b2r8kw"
<font color="red" size="5">
    Hello
</font>
```

বর্তমানে—

```html id="m9x3qt"
<p style="color: red; font-size: 32px;">
    Hello
</p>
```

---

### Deprecated Tags-এর গুরুত্ব (জানার জন্য)

যদিও Deprecated Tags নতুন Project-এ ব্যবহার করা উচিত নয়, তবুও এগুলো সম্পর্কে জানা গুরুত্বপূর্ণ কারণ—

* পুরোনো Website-এর Code বুঝতে সাহায্য করে।
* Legacy Project Maintain করতে সুবিধা হয়।
* HTML-এর ইতিহাস বোঝা যায়।
* আধুনিক HTML-এর উন্নয়ন সম্পর্কে ধারণা পাওয়া যায়।

---

### সারসংক্ষেপ

Deprecated Tags হলো HTML-এর পুরোনো Tag, যেগুলো HTML5-এ আর ব্যবহার করার পরামর্শ দেওয়া হয় না। এই অধ্যায়ে মোট **১১টি Deprecated Tag** আলোচনা করা হয়েছে—`<center>`, `<font>`, `<big>`, `<tt>`, `<strike>`, `<frameset>`, `<frame>`, `<noframes>`, `<acronym>`, `<applet>` এবং `<dir>`। আধুনিক Web Development-এ এগুলোর পরিবর্তে CSS, Semantic HTML এবং নতুন HTML5 Tag ব্যবহার করা হয়। একজন দক্ষ Web Developer-এর জন্য Deprecated Tags সম্পর্কে জানা গুরুত্বপূর্ণ, তবে নতুন Project-এ সবসময় আধুনিক এবং Standard HTML ব্যবহার করা উচিত।