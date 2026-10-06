# HTML Comments

## 1. HTML Comment কী?

HTML Comment হলো HTML Code-এর এমন একটি অংশ, যা **Browser পড়তে পারে কিন্তু Web Page-এ প্রদর্শন (Display) করে না।** অর্থাৎ, Comment শুধুমাত্র Developer-এর জন্য লেখা হয়, ব্যবহারকারীর জন্য নয়।

Comment ব্যবহার করে Code-এর ব্যাখ্যা (Explanation), নোট (Note), নির্দেশনা (Instruction), Reminder অথবা কোনো Code সাময়িকভাবে নিষ্ক্রিয় (Disable) রাখা যায়। এটি Code-কে আরও পরিষ্কার (Clean), সংগঠিত (Organized) এবং সহজে বোঝার উপযোগী (Readable) করে তোলে।

HTML Comment Browser দ্বারা Render হয় না, তাই এটি Web Page-এর দৃশ্যমান অংশে কোনো প্রভাব ফেলে না।

এই অধ্যায়ে আমরা HTML Comment-এর ধারণা, Syntax, Single Line Comment, Multi Line Comment, Browser কীভাবে Comment পড়ে এবং বাস্তবে কোথায় Comment ব্যবহার করা হয় তা বিস্তারিতভাবে জানব।

---

## 2. HTML Comment Syntax

HTML Comment লেখার জন্য একটি নির্দিষ্ট Syntax অনুসরণ করতে হয়।

Comment সর্বদা `<!--` দিয়ে শুরু হয় এবং `-->` দিয়ে শেষ হয়।

```html
<!-- This is a Comment -->
```

Browser এই অংশটিকে Comment হিসেবে চিনতে পারে এবং এটি Render করে না।

### Comment Syntax-এর গঠন

```text
<!--
     Comment Text
-->
```

### উদাহরণ

```html
<!-- Welcome Section -->
```

```html
<!-- This page is under development -->
```

### গুরুত্বপূর্ণ বিষয়

* Comment-এর ভিতরে যেকোনো লেখা লেখা যায়।
* Browser Comment প্রদর্শন করে না।
* Comment-এর ভিতরে HTML Tag লিখলেও তা Render হয় না।

---

## 3. Single Line Comment

Single Line Comment এক লাইনের ছোট ব্যাখ্যা, নোট অথবা Section-এর নাম লেখার জন্য ব্যবহৃত হয়।

এটি সাধারণত Code-এর একটি নির্দিষ্ট অংশ চিহ্নিত (Identify) করতে ব্যবহৃত হয়।

### উদাহরণ

```html
<!-- Header Section -->
```

```html
<!-- Navigation Menu -->
```

```html
<!-- Footer Starts Here -->
```

### বাস্তব উদাহরণ

```html
<!DOCTYPE html>
<html>

<head>

    <title>My Website</title>

</head>

<body>

    <!-- Website Header -->

    <header>

        <h1>Welcome</h1>

    </header>

</body>

</html>
```

এখানে `<!-- Website Header -->` শুধুমাত্র Developer-এর জন্য লেখা হয়েছে। Browser এটি প্রদর্শন করবে না।

### Single Line Comment-এর ব্যবহার

* ছোট নোট লিখতে
* Section-এর নাম লিখতে
* Code বুঝতে সহজ করতে
* Team Member-কে নির্দেশনা দিতে

---

## 4. Multi Line Comment

Multi Line Comment একাধিক লাইনের ব্যাখ্যা, Documentation অথবা বড় Note লেখার জন্য ব্যবহৃত হয়।

যখন একটি Comment এক লাইনের বেশি হয়, তখন Multi Line Comment ব্যবহার করা হয়।

### উদাহরণ

```html
<!--

This is a
Multi Line
Comment.

-->
```

### বাস্তব উদাহরণ

```html
<!--

=================================
    Website Header Section
=================================

Logo
Navigation
Search Bar

-->
```

### Code সাময়িকভাবে Disable করা

```html
<!--

<h1>Welcome</h1>

<p>

This paragraph is hidden.

</p>

-->
```

Browser এই Code Render করবে না।

### Multi Line Comment-এর ব্যবহার

* Documentation লিখতে
* বড় ব্যাখ্যা দিতে
* Code Disable করতে
* Team Project-এ Note রাখতে

---

## 5. HTML Comment কীভাবে কাজ করে?

Browser HTML File পড়ার সময় Comment শনাক্ত (Detect) করে।

তারপর Browser Comment-এর ভিতরের অংশকে উপেক্ষা (Ignore) করে এবং শুধুমাত্র বাকি HTML Code Render করে।

### Browser Processing

```text
HTML File
      │
      ▼
Read HTML
      │
      ▼
Detect Comment
      │
      ▼
Ignore Comment
      │
      ▼
Render Remaining HTML
```

### উদাহরণ

```html
<h1>Hello</h1>

<!-- Hidden Text -->

<p>Welcome</p>
```

Browser শুধুমাত্র নিচের Content দেখাবে—

```
Hello

Welcome
```

Comment Browser-এর Source Code-এ থাকবে, কিন্তু Web Page-এ দেখা যাবে না।

---

## 6. Comment ব্যবহার কোথায় হয়?

HTML Comment Web Development-এর বিভিন্ন ক্ষেত্রে ব্যবহার করা হয়।

### 6.1 Code Explanation

Code-এর উদ্দেশ্য বোঝানোর জন্য।

```html
<!-- Main Navigation -->
```

---

### 6.2 Section Divide

বড় HTML File-কে বিভিন্ন অংশে ভাগ করার জন্য।

```html
<!-- Header -->

<!-- Main -->

<!-- Footer -->
```

---

### 6.3 Documentation

Project সম্পর্কে গুরুত্বপূর্ণ তথ্য লিখতে।

```html
<!--

Created by:
WS HASAN

Version:
1.0

-->
```

---

### 6.4 Reminder

পরবর্তীতে পরিবর্তনের জন্য নোট রাখতে।

```html
<!--

Replace this image later.

-->
```

---

### 6.5 Debugging

কোনো Code সাময়িকভাবে Disable করতে।

```html
<!--

<div>

Old Banner

</div>

-->
```

---

### 6.6 Team Collaboration

Team Member-দের জন্য নির্দেশনা লিখতে।

```html
<!--

Do not remove this section.

-->
```

---

### 6.7 Future Development

ভবিষ্যতে নতুন Feature যোগ করার পরিকল্পনা লিখতে।

```html
<!--

Add Login Form Here

-->
```

---

## Browser কী Comment দেখায়?

| জায়গা              | Comment দেখা যায়? |
| ------------------- | ------------------ |
| Web Page            | ❌ না               |
| Browser Source Code | ✅ হ্যাঁ            |
| Developer Tools     | ✅ হ্যাঁ            |

Comment Browser-এর Source Code-এ দেখা যায়।

তাই **Password, API Key, Secret Information বা ব্যক্তিগত তথ্য কখনোই Comment-এর ভিতরে রাখা উচিত নয়।**

---

## HTML Comments-এর গুরুত্ব

* Code পড়তে সহজ হয়।
* Project সুন্দরভাবে সংগঠিত থাকে।
* Team Work সহজ হয়।
* Documentation লেখা যায়।
* Debugging সহজ হয়।
* Future Update করা সহজ হয়।
* Code Maintain করা সহজ হয়।

---

## বাস্তব উদাহরণ

ধরুন একটি **বই** কল্পনা করুন।

| HTML Comment    | বইয়ের উদাহরণ           |
| --------------- | ----------------------- |
| Single Comment  | একটি ছোট Note           |
| Multi Comment   | পুরো অধ্যায়ের ব্যাখ্যা |
| Section Comment | অধ্যায়ের শিরোনাম       |
| Documentation   | বইয়ের Preface          |
| Reminder        | Bookmark                |

যেমন একটি বইয়ে লেখক নিজের জন্য বা পাঠকের সুবিধার জন্য বিভিন্ন Note লিখে রাখেন, ঠিক তেমনি HTML Comment Developer-কে Code বুঝতে সাহায্য করে।

---

## Best Practice

* অর্থপূর্ণ Comment লিখুন।
* প্রতিটি বড় Section-এর আগে Comment ব্যবহার করুন।
* অপ্রয়োজনীয় Comment লিখবেন না।
* বড় Project-এ Documentation Comment ব্যবহার করুন।
* Comment ছোট, পরিষ্কার এবং বোধগম্য রাখুন।
* Sensitive Information কখনো Comment-এ লিখবেন না।

---

## সাধারণ ভুল (Common Mistakes)

### ❌ Comment বন্ধ করতে ভুলে যাওয়া

```html
<!-- Header
```

✔ সঠিক

```html
<!-- Header -->
```

---

### ❌ Password বা Secret Information লেখা

```html
<!--
Password = 123456
-->
```

✔ কখনোই Secret Information Comment-এ লিখবেন না।

---

### ❌ অপ্রয়োজনীয় Comment ব্যবহার

```html
<!-- Paragraph -->

<p>Hello</p>
```

এটি প্রয়োজন না হলে লিখবেন না।

---

### ❌ Comment-এর ভিতরে Comment লেখা

```html
<!--

<!-- Wrong -->

-->
```

HTML-এ Nested Comment সমর্থিত নয়।

---

## সারসংক্ষেপ

HTML Comment হলো এমন একটি বিশেষ অংশ, যা Browser পড়ে কিন্তু Web Page-এ প্রদর্শন করে না। এটি Code-এর ব্যাখ্যা, Documentation, Reminder, Debugging এবং Team Collaboration-এর জন্য ব্যবহৃত হয়। HTML Comment `<!--` দিয়ে শুরু হয় এবং `-->` দিয়ে শেষ হয়। Single Line এবং Multi Line—উভয় ধরনের Comment ব্যবহার করা যায়। একটি পরিষ্কার, Maintainable এবং Professional HTML Project তৈরির জন্য Comment অত্যন্ত গুরুত্বপূর্ণ।