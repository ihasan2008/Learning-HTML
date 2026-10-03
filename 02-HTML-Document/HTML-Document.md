# > HTML Document

একটি HTML Document হলো একটি Web Page-এর সম্পূর্ণ কাঠামো (Structure)। Browser এই Document পড়ে একটি Web Page তৈরি করে এবং ব্যবহারকারীর সামনে প্রদর্শন করে।

প্রতিটি HTML File সাধারণত নিচের কাঠামো অনুসরণ করে।

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

---

## HTML Document-এর অংশসমূহ

একটি HTML Document প্রধানত ৫টি অংশ নিয়ে গঠিত।

1. `<!DOCTYPE html>`
2. `<html>`
3. `<head>`
4. `<title>`
5. `<body>`

---

## HTML Document Structure Diagram

```text
HTML Document
│
├── <!DOCTYPE html>
│
└── <html>
    │
    ├── <head>
    │   │
    │   └── <title>
    │
    └── <body>
```

---

## প্রতিটি অংশের কাজ

### ১. `<!DOCTYPE html>`

এটি Browser-কে জানায় যে এটি একটি **HTML5 Document**।

এটি কোনো HTML Tag নয়।

এর কাজ হলো Browser-কে সঠিক Rendering Mode-এ Page প্রদর্শন করতে বলা।

```html
<!DOCTYPE html>
```

---

### ২. `<html>`

এটি পুরো HTML Document-এর Root Element।

Document-এর সকল Element এই Tag-এর ভিতরে থাকে।

```html
<html>

</html>
```

সব HTML Code এই Tag-এর ভিতরে লেখা হয়।

---

### ৩. `<head>`

`<head>` অংশে এমন তথ্য থাকে যা Browser ব্যবহার করে, কিন্তু ব্যবহারকারী সরাসরি Web Page-এ দেখতে পায় না।

এখানে সাধারণত থাকে—

* Title
* Meta Tag
* CSS Link
* JavaScript File Link
* Favicon
* Font Link

উদাহরণ—

```html
<head>

</head>
```

---

### ৪. `<title>`

`<title>` Tag Browser Tab-এর নাম নির্ধারণ করে।

উদাহরণ—

```html
<title>My Website</title>
```

Browser-এর Tab-এ দেখা যাবে—

```text
My Website
```

এটি SEO-এর জন্যও গুরুত্বপূর্ণ।

---

### ৫. `<body>`

`<body>` অংশে Website-এর সব দৃশ্যমান (Visible) Content লেখা হয়।

যেমন—

* Heading
* Paragraph
* Image
* Button
* Table
* Form
* Video

উদাহরণ—

```html
<body>

    <h1>Welcome</h1>

    <p>Hello World</p>

</body>
```

Browser-এ এই অংশটিই দেখা যায়।

---

## Browser কীভাবে HTML Document পড়ে?

Browser HTML File-টি উপরের দিক থেকে নিচের দিকে পড়ে।

প্রক্রিয়াটি সাধারণত এমন হয়—

```text
Read DOCTYPE
        │
        ▼
Read HTML
        │
        ▼
Read HEAD
        │
        ▼
Read TITLE
        │
        ▼
Read BODY
        │
        ▼
Display Web Page
```

---

## HTML Document-এর Flow

```text
HTML File
     │
     ▼
Browser
     │
     ▼
DOCTYPE
     │
     ▼
HTML
     │
     ▼
HEAD
     │
     ▼
BODY
     │
     ▼
Web Page
```

---

## বাস্তব উদাহরণ

ধরুন আপনি একটি **বই** তৈরি করছেন।

* `<!DOCTYPE html>` → বইটি কোন ভাষা বা ফরম্যাটে লেখা তা জানায়।
* `<html>` → পুরো বই।
* `<head>` → বইয়ের কভার ও তথ্য (শিরোনাম, লেখক, প্রকাশক ইত্যাদি)।
* `<title>` → বইয়ের নাম।
* `<body>` → বইয়ের মূল লেখা।

অর্থাৎ—

* **DOCTYPE** → Document-এর ধরন।
* **HTML** → পুরো Document।
* **HEAD** → তথ্য (Metadata)।
* **TITLE** → Page-এর নাম।
* **BODY** → দৃশ্যমান Content।

---

## HTML Document-এর বৈশিষ্ট্য

* প্রতিটি HTML File-এর একটি মৌলিক কাঠামো থাকে।
* `<!DOCTYPE html>` HTML5 নির্দেশ করে।
* `<html>` হলো Root Element।
* `<head>` Metadata ধারণ করে।
* `<title>` Browser Tab-এর নাম নির্ধারণ করে।
* `<body>`-তে দৃশ্যমান Content থাকে।
* Browser এই কাঠামো অনুসরণ করেই Web Page তৈরি করে।

---

## সম্পূর্ণ উদাহরণ

```html
<!DOCTYPE html>
<html>
    <head>
        <title>My First Website</title>
    </head>

    <body>

        <h1>Welcome</h1>

        <p>This is my first HTML page.</p>

    </body>
</html>
```

Browser-এ দেখা যাবে—

```text
------------------------------------
| My First Website              ✕ |
------------------------------------

Welcome

This is my first HTML page.
```

---

## সারসংক্ষেপ

একটি HTML Document হলো একটি Web Page-এর মৌলিক কাঠামো। এতে `<!DOCTYPE html>` Browser-কে HTML5 সম্পর্কে জানায়, `<html>` পুরো Document ধারণ করে, `<head>` Metadata সংরক্ষণ করে, `<title>` Browser Tab-এর নাম নির্ধারণ করে এবং `<body>`-তে ব্যবহারকারীর জন্য দৃশ্যমান সব Content থাকে। HTML শেখার প্রথম ব্যবহারিক ধাপ হলো এই Document Structure ভালোভাবে বোঝা।
