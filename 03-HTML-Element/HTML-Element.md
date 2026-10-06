# HTML Element

HTML Element হলো একটি Web Page-এর মৌলিক নির্মাণ উপাদান (Building Block)। একটি HTML Document অসংখ্য Element নিয়ে গঠিত। প্রতিটি Element Browser-কে জানায় কোনো Content কীভাবে প্রদর্শিত হবে।

সহজভাবে বলতে গেলে, **HTML Tag + Content = HTML Element**।

---

## HTML Element-এর সাধারণ গঠন

একটি HTML Element সাধারণত তিনটি অংশ নিয়ে গঠিত—

1. Opening Tag (Start Tag)
2. Content
3. Closing Tag (End Tag)

```html id="e1t8k5"
<tagname>
    Content
</tagname>
```

অথবা Attribute-সহ—

```html id="w4m9q2"
<tagname attribute="value">
    Content
</tagname>
```

---

## HTML Element-এর অংশসমূহ

```html id="r6x3p1"
<h1>Hello World</h1>
```

এখানে—

| অংশ         | উদাহরণ        | কাজ              |
| ----------- | ------------- | ---------------- |
| Opening Tag | `<h1>`        | Element শুরু করে |
| Content     | `Hello World` | প্রদর্শিত তথ্য   |
| Closing Tag | `</h1>`       | Element শেষ করে  |

---

## Element Structure Diagram

```text id="a8v2n6"
┌─────────────────────────────┐
│       HTML Element          │
├─────────────────────────────┤
│ Opening Tag                 │
│      │                      │
│      ▼                      │
│   <h1>                      │
│      │                      │
│      ▼                      │
│ Hello World                 │
│      ▲                      │
│      │                      │
│   </h1>                     │
│ Closing Tag                 │
└─────────────────────────────┘
```

---

## HTML Element কীভাবে কাজ করে?

Browser যখন HTML File পড়ে—

1. Opening Tag শনাক্ত করে।
2. Content পড়ে।
3. Closing Tag পর্যন্ত Element-এর অংশ হিসেবে বিবেচনা করে।
4. নির্দিষ্ট নিয়ম অনুযায়ী Content প্রদর্শন করে।

উদাহরণ—

```html id="n2c5y8"
<p>This is a paragraph.</p>
```

Browser বুঝবে—

* এটি একটি Paragraph Element।
* ভিতরের Text-টি Paragraph হিসেবে দেখাতে হবে।

---

## বিভিন্ন ধরনের HTML Element

### ১. Container Element

যেসব Element-এর Opening Tag এবং Closing Tag থাকে এবং তাদের ভিতরে Content রাখা যায়।

উদাহরণ—

```html id="g9m1d4"
<p>Hello World</p>

<h1>Welcome</h1>

<div>This is a container.</div>
```

---

### ২. Empty Element (Void Element)

কিছু HTML Element-এর কোনো Closing Tag বা Content থাকে না। এগুলোকে **Empty Element** বা **Void Element** বলা হয়।

উদাহরণ—

```html id="u7q8r3"
<br>

<hr>

<img src="image.jpg" alt="Image">
```

এগুলো শুধু একটি কাজ সম্পন্ন করে, তাই Closing Tag প্রয়োজন হয় না।

---

### ৩. Nested Element

যখন একটি HTML Element-এর ভিতরে আরেকটি HTML Element থাকে, তখন তাকে Nested Element বলা হয়।

উদাহরণ—

```html id="b3k7n9"
<div>

    <h1>Welcome</h1>

    <p>Hello World</p>

</div>
```

এখানে—

* `<div>` Parent Element।
* `<h1>` এবং `<p>` Child Element।

---

## Parent এবং Child Element

উদাহরণ—

```html id="j6x4f2"
<body>

    <section>

        <h1>Title</h1>

    </section>

</body>
```

সম্পর্ক—

```text id="p9t5m1"
<body>
   │
   └── <section>
            │
            └── <h1>
```

* `<body>` → Parent
* `<section>` → Child of `<body>`
* `<h1>` → Child of `<section>`

---

## HTML Element-এ Attribute

Element-এর অতিরিক্ত তথ্য দেওয়ার জন্য Attribute ব্যবহার করা হয়।

উদাহরণ—

```html id="h8v2c7"
<a href="https://example.com">Visit Website</a>
```

এখানে—

* Element → `<a>...</a>`
* Attribute → `href`
* Value → `"https://example.com"`

আরেকটি উদাহরণ—

```html id="q5m1w8"
<img src="logo.png" alt="Company Logo">
```

এখানে—

* `src`
* `alt`

দুটি Attribute।

---

## Browser কীভাবে Element পড়ে?

```text id="l3d9r6"
Opening Tag
      │
      ▼
Read Attributes
      │
      ▼
Read Content
      │
      ▼
Closing Tag
      │
      ▼
Display Output
```

---

## HTML Element-এর বৈশিষ্ট্য

* HTML Document Element দিয়ে তৈরি হয়।
* প্রতিটি Element-এর একটি নির্দিষ্ট উদ্দেশ্য থাকে।
* কিছু Element-এর Closing Tag থাকে, কিছু Element Empty হয়।
* Element-এর ভিতরে অন্যান্য Element রাখা যায়।
* Attribute ব্যবহার করে Element-এর অতিরিক্ত তথ্য দেওয়া যায়।
* Browser Element অনুযায়ী Content প্রদর্শন করে।

---

## বাস্তব উদাহরণ

ধরুন, একটি **উপহারের বাক্স (Gift Box)** কল্পনা করুন।

* **Opening Tag** → বাক্সের ঢাকনা খোলা।
* **Content** → বাক্সের ভিতরের উপহার।
* **Closing Tag** → বাক্সের ঢাকনা বন্ধ করা।

যদি বাক্সের ভিতরে আরেকটি ছোট বাক্স থাকে, তাহলে সেটি **Nested Element**-এর মতো।

অর্থাৎ—

* Element একটি সম্পূর্ণ একক (Complete Unit)।
* Tag শুধু Element-এর শুরু এবং শেষ নির্দেশ করে।

---

## HTML Element বনাম HTML Tag

অনেক নতুন শিক্ষার্থী **Element** এবং **Tag**-কে একই জিনিস মনে করেন, কিন্তু তারা এক নয়।

| HTML Tag                    | HTML Element                        |
| --------------------------- | ----------------------------------- |
| শুধু Opening বা Closing Tag | Opening Tag + Content + Closing Tag |
| যেমন: `<p>`                 | যেমন: `<p>Hello</p>`                |
| Element-এর অংশ              | সম্পূর্ণ গঠন                        |

উদাহরণ—

```html id="z4k8m2"
<p>Hello World</p>
```

এখানে—

* `<p>` → Opening Tag
* `</p>` → Closing Tag
* `<p>Hello World</p>` → HTML Element

---

## সম্পূর্ণ উদাহরণ

```html id="s1q6x9"
<!DOCTYPE html>
<html>
<head>
    <title>HTML Element Example</title>
</head>
<body>

    <h1>Welcome</h1>

    <p>This is my first HTML Element.</p>

    <img src="logo.png" alt="Logo">

</body>
</html>
```

এখানে—

* `<h1>Welcome</h1>` → Heading Element
* `<p>...</p>` → Paragraph Element
* `<img>` → Empty Element

---

## সারসংক্ষেপ

HTML Element হলো HTML Document-এর মৌলিক নির্মাণ উপাদান। একটি সাধারণ Element Opening Tag, Content এবং Closing Tag নিয়ে গঠিত। কিছু Element Empty (Void) হয় এবং Closing Tag ছাড়াই কাজ করে। আবার অনেক Element-এর ভিতরে অন্য Element থাকতে পারে, যাকে Nested Element বলা হয়। HTML Document-এর প্রতিটি অংশই মূলত বিভিন্ন Element-এর সমন্বয়ে তৈরি হয়, যা Browser পড়ে একটি সম্পূর্ণ Web Page প্রদর্শন করে।