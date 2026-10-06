# HTML Attributes

HTML Attribute হলো এমন একটি বৈশিষ্ট্য (Property), যা **HTML Element-এর অতিরিক্ত তথ্য (Additional Information)** প্রদান করে। Attribute ব্যবহার করে কোনো Element-এর আচরণ (Behavior), বৈশিষ্ট্য (Property), চেহারা (Appearance) অথবা কার্যপ্রণালী (Functionality) নিয়ন্ত্রণ করা যায়।

উদাহরণস্বরূপ—

* একটি Link কোথায় যাবে তা `href` দ্বারা নির্ধারণ করা হয়।
* একটি Image কোথা থেকে Load হবে তা `src` দ্বারা নির্ধারণ করা হয়।
* একটি Element-এর পরিচয় `id` দ্বারা নির্ধারণ করা হয়।
* CSS Class নির্ধারণ করা হয় `class` দ্বারা।

অর্থাৎ, HTML Tag একটি Element তৈরি করে এবং **Attribute সেই Element-এর অতিরিক্ত তথ্য ও নিয়ন্ত্রণ প্রদান করে।**

---

### HTML Attribute কী?

HTML Attribute হলো এমন একটি **Name এবং Value-এর জোড়া (Name-Value Pair)**, যা HTML Tag-এর Opening Tag-এর ভিতরে লেখা হয়।

Attribute Browser-কে জানায় Element কীভাবে কাজ করবে, কী তথ্য বহন করবে অথবা কীভাবে প্রদর্শিত হবে।

সাধারণভাবে একটি Attribute-এর Syntax হলো—

```html
<tagname attribute="value">
    Content
</tagname>
```

উদাহরণ—

```html
<a href="https://example.com">
    Visit Website
</a>
```

এখানে—

* `<a>` → HTML Tag
* `href` → Attribute Name
* `"https://example.com"` → Attribute Value

---

### HTML Attribute-এর মৌলিক কাঠামো

```html
<!DOCTYPE html>
<html>

<head>
    <title>HTML Attributes</title>
</head>

<body>

    <a
        href="https://example.com"
        target="_blank"
        title="Visit Website">

        Click Here

    </a>

</body>

</html>
```

উপরের Code-এ একটি `<a>` Tag-এর মধ্যে একাধিক Attribute ব্যবহার করা হয়েছে।

---

### HTML Attribute Structure

```text
<tag
    attribute="value"
    attribute="value"
    attribute="value">

    Content

</tag>
```

---

### HTML Attribute-এর অংশসমূহ

```html
<img
    src="photo.jpg"
    alt="Profile Photo"
    width="300">
```

| অংশ               | ব্যাখ্যা        |
| ----------------- | --------------- |
| `<img>`           | HTML Element    |
| `src`             | Attribute Name  |
| `"photo.jpg"`     | Attribute Value |
| `alt`             | Attribute Name  |
| `"Profile Photo"` | Attribute Value |
| `width`           | Attribute Name  |
| `"300"`           | Attribute Value |

---

### HTML Attribute-এর প্রধান বৈশিষ্ট্য

* Attribute সবসময় Opening Tag-এর ভিতরে লেখা হয়।
* একটি Element-এ একাধিক Attribute থাকতে পারে।
* অধিকাংশ Attribute-এর Value থাকে।
* কিছু Attribute-এর কোনো Value থাকে না (Boolean Attribute)।
* Attribute Name সাধারণত ছোট হাতের (Lowercase) অক্ষরে লেখা হয়।
* HTML5-এ Double Quote (`" "`) ব্যবহার করা Best Practice।

---

### HTML Attribute-এর প্রকারভেদ

HTML Attribute-কে বিভিন্ন Category-তে ভাগ করা যায়।

| নং | Category                 | Attribute সংখ্যা |
| -- | ------------------------ | ---------------: |
| 1  | Global Attributes        |               11 |
| 2  | Link / Anchor Attributes |                6 |
| 3  | Image Attributes         |                7 |
| 4  | Form Attributes          |               22 |
| 5  | Input Type Attributes    |               13 |
| 6  | Script Attributes        |                5 |
| 7  | Table Attributes         |                4 |
| 8  | Media Attributes         |                7 |
| 9  | Iframe Attributes        |                7 |
| 10 | Meta Attributes          |                4 |
| 11 | List Attributes          |                3 |
| 12 | Button Attributes        |                4 |
| 13 | Select Attributes        |                5 |
| 14 | Option Attributes        |                3 |
| 15 | Misc Attributes          |                6 |

মোট Attribute: **১০৭টি**

---

### HTML Attribute Browser কীভাবে পড়ে?

Browser সাধারণত নিচের ধাপগুলো অনুসরণ করে—

```text
HTML Document
      │
      ▼
Read HTML Tag
      │
      ▼
Read Attribute Name
      │
      ▼
Read Attribute Value
      │
      ▼
Apply Attribute
      │
      ▼
Render Web Page
```

Browser প্রথমে HTML Tag পড়ে, এরপর প্রতিটি Attribute-এর Name এবং Value বিশ্লেষণ করে এবং সেই অনুযায়ী Element প্রদর্শন করে।

---

### Attribute Name এবং Attribute Value

প্রতিটি Attribute সাধারণত দুটি অংশ নিয়ে গঠিত।

#### Attribute Name

Attribute-এর নাম।

উদাহরণ—

```html
href
```

---

#### Attribute Value

Attribute-এর মান (Value)।

উদাহরণ—

```html
"https://example.com"
```

---

সম্পূর্ণ উদাহরণ—

```html
<a href="https://example.com">
```

এখানে—

* `href` → Attribute Name
* `"https://example.com"` → Attribute Value

---

### Boolean Attribute কী?

যেসব Attribute-এর কোনো Value লিখতে হয় না, সেগুলোকে **Boolean Attribute** বলা হয়।

উদাহরণ—

```html
<input type="text" required>

<input type="checkbox" checked>

<input disabled>
```

এখানে—

* `required`
* `checked`
* `disabled`

সবগুলোই Boolean Attribute।

---

### একাধিক Attribute ব্যবহার

একটি HTML Element-এ একাধিক Attribute ব্যবহার করা যায়।

```html
<img
    src="photo.jpg"
    alt="Profile Photo"
    width="300"
    height="300"
    loading="lazy">
```

Browser প্রতিটি Attribute আলাদাভাবে পড়ে এবং প্রয়োগ করে।

---

### HTML Attribute-এর গুরুত্ব

* Element-এর অতিরিক্ত তথ্য প্রদান করে।
* Element-এর আচরণ নিয়ন্ত্রণ করে।
* Link, Image, Form এবং Media সঠিকভাবে কাজ করতে সাহায্য করে।
* CSS এবং JavaScript-এর সাথে সংযোগ তৈরি করে।
* SEO উন্নত করতে সাহায্য করে।
* Accessibility বৃদ্ধি করে।
* Responsive Website তৈরিতে গুরুত্বপূর্ণ ভূমিকা পালন করে।

---

### বাস্তব উদাহরণ

ধরুন একটি **জাতীয় পরিচয়পত্র (National ID Card)** কল্পনা করুন।

| HTML      | বাস্তব উদাহরণ       |
| --------- | ------------------- |
| HTML Tag  | একজন ব্যক্তি        |
| Attribute | ব্যক্তির তথ্য       |
| `id`      | জাতীয় পরিচয় নম্বর |
| `class`   | পেশা বা শ্রেণি      |
| `title`   | অতিরিক্ত পরিচিতি    |
| `src`     | ছবির অবস্থান        |
| `href`    | ঠিকানা বা গন্তব্য   |

যেমন একজন ব্যক্তিকে শুধু দেখে সব তথ্য জানা যায় না, কিন্তু তার পরিচয়পত্রে অতিরিক্ত তথ্য থাকে। ঠিক তেমনি HTML Tag একটি Element তৈরি করে এবং Attribute সেই Element সম্পর্কে অতিরিক্ত তথ্য প্রদান করে।

---

### Best Practice

* সবসময় Lowercase Attribute Name ব্যবহার করুন।
* Attribute Value Double Quote (`" "`) এর ভিতরে লিখুন।
* প্রয়োজনীয় Attribute অবশ্যই ব্যবহার করুন।
* Image-এর ক্ষেত্রে সবসময় `alt` Attribute লিখুন।
* অপ্রয়োজনীয় Attribute ব্যবহার করবেন না।
* Semantic HTML-এর সাথে Attribute ব্যবহার করুন।

---

### সাধারণ ভুল (Common Mistakes)

❌ Quote ছাড়া Value লেখা

```html
<img src=photo.jpg>
```

✔ সঠিক

```html
<img src="photo.jpg">
```

---

❌ Image-এ `alt` না লেখা

```html
<img src="photo.jpg">
```

✔ সঠিক

```html
<img
    src="photo.jpg"
    alt="Profile Photo">
```

---

❌ একই Attribute বারবার লেখা

```html
<p class="red" class="blue">
```

✔ সঠিক

```html
<p class="red blue">
```

---

### সারসংক্ষেপ

HTML Attribute হলো HTML Element-এর অতিরিক্ত তথ্য ও বৈশিষ্ট্য নির্ধারণ করার উপায়। Attribute সবসময় Opening Tag-এর ভিতরে লেখা হয় এবং সাধারণত **Name="Value"** আকারে থাকে। এগুলোর মাধ্যমে Element-এর আচরণ, চেহারা, তথ্য এবং কার্যপ্রণালী নিয়ন্ত্রণ করা যায়। Link, Image, Form, Table, Media, Script এবং অন্যান্য HTML Element সঠিকভাবে কাজ করার জন্য Attribute অত্যন্ত গুরুত্বপূর্ণ। HTML শেখার ক্ষেত্রে Tag-এর পরে Attribute সম্পর্কে পরিষ্কার ধারণা থাকা একটি দক্ষ Web Developer হওয়ার অন্যতম ভিত্তি।






## 1. Global Attributes

Global Attributes হলো এমন কিছু HTML Attribute, যা **প্রায় সব HTML Element-এর সাথে ব্যবহার করা যায়।** এগুলোর মাধ্যমে Element-এর পরিচয় (Identity), শ্রেণি (Class), ভাষা (Language), দিক (Direction), Style, অতিরিক্ত তথ্য এবং বিভিন্ন ধরনের আচরণ (Behavior) নিয়ন্ত্রণ করা যায়।

Global Attributes HTML-এর সবচেয়ে বেশি ব্যবহৃত Attribute-এর মধ্যে অন্যতম। CSS, JavaScript, Accessibility এবং SEO-তেও এগুলোর গুরুত্বপূর্ণ ভূমিকা রয়েছে।

এই অধ্যায়ে আমরা **১১টি Global Attribute** সম্পর্কে জানব।

---

### Global Attribute কী?

Global Attribute হলো এমন Attribute, যা নির্দিষ্ট কোনো Tag-এর জন্য সীমাবদ্ধ নয়। অর্থাৎ, এগুলো HTML-এর অধিকাংশ Element-এর সাথে ব্যবহার করা যায়।

উদাহরণস্বরূপ—

* `id` → একটি Element-এর ইউনিক পরিচয় দেয়।
* `class` → একাধিক Element-কে একই Group-এ রাখে।
* `style` → Inline CSS যোগ করে।
* `title` → Tooltip দেখায়।

---

### Global Attributes-এর মৌলিক কাঠামো

```html
<!DOCTYPE html>
<html>

<head>
    <title>Global Attributes</title>
</head>

<body>

    <div
        id="box1"
        class="container"
        title="Example Box"
        lang="en">

        Hello World

    </div>

</body>

</html>
```

উপরের Code-এ একটি `<div>` Element-এর মধ্যে একাধিক Global Attribute ব্যবহার করা হয়েছে।

---

### Global Attributes-এর তালিকা

| নং | Attribute                      | কাজ                                      |
| -- | ------------------------------ | ---------------------------------------- |
| 1  | `id=""`                        | Element-এর ইউনিক পরিচয় নির্ধারণ করে     |
| 2  | `class=""`                     | Element-কে Group বা Class-এ যুক্ত করে    |
| 3  | `style=""`                     | Inline CSS যোগ করে                       |
| 4  | `title=""`                     | Tooltip বা অতিরিক্ত তথ্য দেখায়          |
| 5  | `hidden`                       | Element লুকিয়ে রাখে                     |
| 6  | `tabindex=""`                  | Keyboard Navigation-এর ক্রম নির্ধারণ করে |
| 7  | `lang=""`                      | Content-এর ভাষা নির্ধারণ করে             |
| 8  | `dir=""`                       | লেখার দিক নির্ধারণ করে                   |
| 9  | `draggable="true/false"`       | Element Drag করা যাবে কি না নির্ধারণ করে |
| 10 | `contenteditable="true/false"` | Content Edit করা যাবে কি না নির্ধারণ করে |
| 11 | `data-*`                       | Custom Data সংরক্ষণ করে                  |

---

### Global Attributes Structure

```text
HTML Element
      │
      ├── id
      ├── class
      ├── style
      ├── title
      ├── hidden
      ├── tabindex
      ├── lang
      ├── dir
      ├── draggable
      ├── contenteditable
      └── data-*
```

---

### প্রতিটি Attribute-এর সংক্ষিপ্ত পরিচয়

#### 1. `id=""`

* প্রতিটি Element-এর জন্য একটি **Unique ID** নির্ধারণ করে।
* একই Page-এ একটি `id` একবারই ব্যবহার করা উচিত।
* CSS এবং JavaScript-এ Element নির্বাচন করার জন্য ব্যবহৃত হয়।

**উদাহরণ**

```html
<div id="header">
    Welcome
</div>
```

---

#### 2. `class=""`

* একাধিক Element-কে একই Group-এ রাখে।
* CSS Styling এবং JavaScript-এর জন্য ব্যাপকভাবে ব্যবহৃত হয়।
* একটি Element-এ একাধিক Class থাকতে পারে।

**উদাহরণ**

```html
<p class="text primary">
    Hello World
</p>
```

---

#### 3. `style=""`

* Inline CSS লেখার জন্য ব্যবহৃত হয়।
* ছোটখাটো Styling-এর জন্য উপযোগী।
* বড় Project-এ External CSS ব্যবহার করা Best Practice।

**উদাহরণ**

```html
<p style="color: blue;">
    Hello
</p>
```

---

#### 4. `title=""`

* Mouse Pointer Element-এর উপর নিলে Tooltip দেখায়।
* অতিরিক্ত তথ্য প্রদর্শনের জন্য ব্যবহৃত হয়।

**উদাহরণ**

```html
<button title="Save File">
    Save
</button>
```

---

#### 5. `hidden`

* Element Browser-এ দৃশ্যমান থাকে না।
* JavaScript-এর মাধ্যমে পরে দেখানো যেতে পারে।
* এটি একটি **Boolean Attribute**।

**উদাহরণ**

```html
<p hidden>
    Hidden Text
</p>
```

---

#### 6. `tabindex=""`

* Keyboard-এর **Tab Key** চাপলে কোন Element আগে Select হবে তা নির্ধারণ করে।
* Accessibility উন্নত করতে ব্যবহৃত হয়।

**উদাহরণ**

```html
<input tabindex="1">
```

---

#### 7. `lang=""`

* Content-এর ভাষা নির্ধারণ করে।
* Search Engine এবং Screen Reader-এর জন্য গুরুত্বপূর্ণ।

**উদাহরণ**

```html
<html lang="en">
```

অথবা

```html
<p lang="bn">
    আমি বাংলা লিখছি।
</p>
```

---

#### 8. `dir=""`

* লেখার দিক নির্ধারণ করে।

* সাধারণ মান—

* `ltr` → Left to Right

* `rtl` → Right to Left

* `auto` → Browser নিজে নির্ধারণ করবে

**উদাহরণ**

```html
<p dir="rtl">
    مرحبا
</p>
```

---

#### 9. `draggable="true/false"`

* Element Drag করা যাবে কি না নির্ধারণ করে।
* Drag & Drop Application তৈরিতে ব্যবহৃত হয়।

**উদাহরণ**

```html
<img
    src="image.jpg"
    draggable="true">
```

---

#### 10. `contenteditable="true/false"`

* Element-এর Content Browser-এ Edit করা যাবে কি না নির্ধারণ করে।

**উদাহরণ**

```html
<p contenteditable="true">
    Edit Me
</p>
```

---

#### 11. `data-*`

* Custom Data সংরক্ষণের জন্য ব্যবহৃত হয়।
* JavaScript সহজেই এই Data ব্যবহার করতে পারে।
* `*`-এর স্থানে যেকোনো অর্থপূর্ণ নাম লেখা যায়।

**উদাহরণ**

```html
<div
    data-id="101"
    data-name="Laptop">
</div>
```

---

### Browser কীভাবে Global Attributes পড়ে?

Browser সাধারণত নিচের ধাপগুলো অনুসরণ করে—

```text
HTML Element
      │
      ▼
Read Global Attribute
      │
      ▼
Apply Property
      │
      ▼
Render Element
```

Browser প্রতিটি Global Attribute বিশ্লেষণ করে এবং Element-এর উপর সেই অনুযায়ী প্রভাব প্রয়োগ করে।

---

### Global Attributes-এর গুরুত্ব

* Element-এর পরিচয় নির্ধারণ করে।
* CSS এবং JavaScript-এর সাথে সংযোগ তৈরি করে।
* Accessibility উন্নত করে।
* SEO উন্নত করতে সাহায্য করে।
* User Experience বৃদ্ধি করে।
* Custom Data সংরক্ষণ করা যায়।
* Interactive Website তৈরিতে গুরুত্বপূর্ণ ভূমিকা পালন করে।

---

### বাস্তব উদাহরণ

ধরুন একটি **স্কুলের ছাত্র পরিচয়পত্র** কল্পনা করুন।

| Attribute | বাস্তব উদাহরণ           |
| --------- | ----------------------- |
| `id`      | ছাত্রের রোল নম্বর       |
| `class`   | শ্রেণি (Class)          |
| `style`   | পোশাকের রঙ              |
| `title`   | অতিরিক্ত পরিচিতি        |
| `hidden`  | গোপন তথ্য               |
| `lang`    | ছাত্রের ভাষা            |
| `dir`     | লেখার দিক               |
| `data-*`  | অতিরিক্ত ব্যক্তিগত তথ্য |

যেমন একজন ছাত্রের পরিচয়পত্রে নাম, রোল, শ্রেণি এবং অন্যান্য তথ্য থাকে, ঠিক তেমনি Global Attributes একটি HTML Element-এর বিভিন্ন বৈশিষ্ট্য নির্ধারণ করে।

---

### Best Practice

* `id` সবসময় Unique রাখুন।
* Styling-এর জন্য `style`-এর পরিবর্তে External CSS ব্যবহার করুন।
* অর্থপূর্ণ `class` Name ব্যবহার করুন।
* সবসময় সঠিক `lang` Attribute ব্যবহার করুন।
* Custom তথ্যের জন্য `data-*` ব্যবহার করুন।
* Accessibility-এর জন্য `tabindex` এবং `title` সঠিকভাবে ব্যবহার করুন।

---

### সাধারণ ভুল (Common Mistakes)

❌ একই `id` একাধিকবার ব্যবহার করা

```html
<div id="box"></div>
<p id="box"></p>
```

✔ সঠিক

```html
<div id="box1"></div>
<p id="box2"></p>
```

---

❌ অপ্রয়োজনীয় Inline Style ব্যবহার

```html
<p style="color:red; font-size:20px;">
```

✔ বড় Project-এ External CSS ব্যবহার করুন।

---

❌ অর্থহীন Class Name

```html
<div class="abc123">
```

✔ সঠিক

```html
<div class="product-card">
```

---

### সারসংক্ষেপ

Global Attributes হলো HTML-এর এমন Attribute, যা প্রায় সব HTML Element-এর সাথে ব্যবহার করা যায়। এই অধ্যায়ে **১১টি Global Attribute** আলোচনা করা হয়েছে—`id`, `class`, `style`, `title`, `hidden`, `tabindex`, `lang`, `dir`, `draggable`, `contenteditable` এবং `data-*`। এগুলোর মাধ্যমে Element-এর পরিচয়, Style, ভাষা, আচরণ, Accessibility এবং Custom Data নিয়ন্ত্রণ করা যায়। HTML, CSS এবং JavaScript-এর মধ্যে কার্যকর সংযোগ তৈরি করতে Global Attributes অত্যন্ত গুরুত্বপূর্ণ।






## 2. Link / Anchor Attributes

Link / Anchor Attributes হলো এমন কিছু HTML Attribute, যা মূলত `<a>` (Anchor) Tag-এর সাথে ব্যবহার করা হয়। এগুলোর মাধ্যমে একটি Link কোথায় যাবে, কীভাবে খুলবে, কোন ভাষার Content নির্দেশ করবে, File Download করবে কি না এবং Link সম্পর্কে অতিরিক্ত তথ্য নির্ধারণ করা যায়।

Web Development-এ Link তৈরি করা অত্যন্ত গুরুত্বপূর্ণ, কারণ Link-এর মাধ্যমেই একটি Web Page থেকে অন্য Web Page, একই Website-এর অন্য Page, কোনো File, Email Address অথবা নির্দিষ্ট Section-এ যাওয়া যায়।

এই অধ্যায়ে আমরা **৬টি Link / Anchor Attribute** সম্পর্কে জানব।

---

### Link / Anchor Attribute কী?

Link / Anchor Attribute হলো এমন Attribute, যা `<a>` Tag-এর কার্যপ্রণালী (Behavior) নিয়ন্ত্রণ করে।

উদাহরণস্বরূপ—

* `href` → Link কোথায় যাবে তা নির্ধারণ করে।
* `target` → Link কোথায় খুলবে তা নির্ধারণ করে।
* `rel` → বর্তমান Page এবং Target Page-এর সম্পর্ক নির্ধারণ করে।
* `download` → Link-এ Click করলে File Download করে।

---

### Link / Anchor Attributes-এর মৌলিক কাঠামো

```html
<!DOCTYPE html>
<html>

<head>
    <title>Link / Anchor Attributes</title>
</head>

<body>

    <a
        href="https://example.com"
        target="_blank"
        rel="noopener"
        title="Visit Example">

        Visit Website

    </a>

</body>

</html>
```

উপরের Code-এ একটি `<a>` Tag-এর সাথে একাধিক Link Attribute ব্যবহার করা হয়েছে।

---

### Link / Anchor Attributes-এর তালিকা

| নং | Attribute     | কাজ                                                |
| -- | ------------- | -------------------------------------------------- |
| 12 | `href=""`     | Link-এর গন্তব্য (Destination URL) নির্ধারণ করে     |
| 13 | `target=""`   | Link কোথায় খুলবে তা নির্ধারণ করে                  |
| 14 | `rel=""`      | বর্তমান Page ও Target Page-এর সম্পর্ক নির্ধারণ করে |
| 15 | `download`    | Link-এ Click করলে File Download করে                |
| 16 | `hreflang=""` | Link করা Page-এর ভাষা নির্দেশ করে                  |
| 17 | `type=""`     | Link করা Resource-এর MIME Type নির্দেশ করে         |

---

### Link / Anchor Attributes Structure

```text
<a>
 │
 ├── href
 ├── target
 ├── rel
 ├── download
 ├── hreflang
 └── type
```

---

### প্রতিটি Attribute-এর সংক্ষিপ্ত পরিচয়

#### 12. `href=""`

* Link-এর সবচেয়ে গুরুত্বপূর্ণ Attribute।
* কোন URL, File, Email বা Page-এ যাবে তা নির্ধারণ করে।
* `href` ছাড়া `<a>` Tag সাধারণত কার্যকর Link হিসেবে কাজ করে না।

**উদাহরণ**

```html
<a href="https://example.com">
    Visit Website
</a>
```

---

#### 13. `target=""`

* Link কোথায় খুলবে তা নির্ধারণ করে।

সবচেয়ে ব্যবহৃত Value—

| Value     | কাজ                       |
| --------- | ------------------------- |
| `_self`   | একই Tab-এ খুলবে (Default) |
| `_blank`  | নতুন Tab-এ খুলবে          |
| `_parent` | Parent Frame-এ খুলবে      |
| `_top`    | পুরো Window-তে খুলবে      |

**উদাহরণ**

```html
<a
    href="https://example.com"
    target="_blank">

    Open Website

</a>
```

---

#### 14. `rel=""`

* বর্তমান Page এবং Link করা Page-এর সম্পর্ক নির্ধারণ করে।
* Security এবং SEO-এর জন্য গুরুত্বপূর্ণ।

সবচেয়ে ব্যবহৃত Value—

* `noopener`
* `noreferrer`
* `nofollow`
* `author`
* `license`
* `external`

**উদাহরণ**

```html
<a
    href="https://example.com"
    target="_blank"
    rel="noopener noreferrer">

    Visit

</a>
```

---

#### 15. `download`

* Link-এ Click করলে Browser File Download করার চেষ্টা করে।
* সাধারণত PDF, Image, ZIP বা অন্যান্য File Download-এর জন্য ব্যবহৃত হয়।
* এটি একটি **Boolean Attribute**।

**উদাহরণ**

```html
<a
    href="notes.pdf"
    download>

    Download PDF

</a>
```

---

#### 16. `hreflang=""`

* Link করা Page-এর ভাষা নির্দেশ করে।
* SEO-এর জন্য সহায়ক।
* Search Engine-কে Target Language বুঝতে সাহায্য করে।

**উদাহরণ**

```html
<a
    href="https://example.com"
    hreflang="en">

    English Version

</a>
```

---

#### 17. `type=""`

* Link করা Resource-এর MIME Type নির্দেশ করে।
* Browser-কে File-এর ধরন সম্পর্কে ধারণা দেয়।

সাধারণ উদাহরণ—

* `text/html`
* `application/pdf`
* `image/png`
* `audio/mpeg`

**উদাহরণ**

```html
<a
    href="guide.pdf"
    type="application/pdf">

    User Guide

</a>
```

---

### Browser কীভাবে Link Attributes পড়ে?

Browser সাধারণত নিচের ধাপগুলো অনুসরণ করে—

```text
HTML Document
      │
      ▼
Read <a> Tag
      │
      ▼
Read Link Attributes
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

Browser প্রথমে `href` পড়ে Link তৈরি করে। এরপর `target`, `rel` এবং অন্যান্য Attribute অনুযায়ী Link-এর আচরণ নির্ধারণ করে।

---

### Link / Anchor Attributes-এর গুরুত্ব

* Web Page-এর মধ্যে Navigation তৈরি করে।
* External Website-এর সাথে সংযোগ স্থাপন করে।
* File Download করা যায়।
* নতুন Tab-এ Link খোলা যায়।
* SEO উন্নত করতে সাহায্য করে।
* Website-এর Security বৃদ্ধি করে।
* User Experience উন্নত করে।

---

### বাস্তব উদাহরণ

ধরুন একটি **বইয়ের সূচিপত্র (Table of Contents)** কল্পনা করুন।

| Attribute  | বাস্তব উদাহরণ                      |
| ---------- | ---------------------------------- |
| `href`     | কোন অধ্যায়ে যাবে                  |
| `target`   | নতুন বই খুলবে নাকি একই বইয়ে থাকবে |
| `rel`      | দুই বইয়ের সম্পর্ক                 |
| `download` | বইটি Download করা                  |
| `hreflang` | বইয়ের ভাষা                        |
| `type`     | বইটি PDF নাকি অন্য Format          |

যেমন একটি সূচিপত্র থেকে নির্দিষ্ট অধ্যায়ে যাওয়া যায়, ঠিক তেমনি `<a>` Tag এবং এর Attribute ব্যবহার করে একটি Web Page থেকে অন্য Page বা Resource-এ যাওয়া যায়।

---

### Best Practice

* সবসময় সঠিক URL সহ `href` ব্যবহার করুন।
* External Link-এর ক্ষেত্রে `target="_blank"` ব্যবহার করলে `rel="noopener noreferrer"` যোগ করুন।
* Download Link-এর জন্য `download` Attribute ব্যবহার করুন।
* SEO-এর জন্য প্রয়োজনে `hreflang` ব্যবহার করুন।
* Resource Type জানা থাকলে `type` ব্যবহার করুন।
* অর্থপূর্ণ Link Text লিখুন (যেমন "Download PDF", "Learn HTML")।

---

### সাধারণ ভুল (Common Mistakes)

❌ `href` ছাড়া Link তৈরি করা

```html
<a>Visit</a>
```

✔ সঠিক

```html
<a href="https://example.com">
    Visit
</a>
```

---

❌ নতুন Tab খুলে `rel` ব্যবহার না করা

```html
<a
    href="https://example.com"
    target="_blank">
    Visit
</a>
```

✔ সঠিক

```html
<a
    href="https://example.com"
    target="_blank"
    rel="noopener noreferrer">

    Visit

</a>
```

---

❌ অর্থহীন Link Text ব্যবহার করা

```html
<a href="guide.pdf">
    Click Here
</a>
```

✔ সঠিক

```html
<a href="guide.pdf">
    Download User Guide (PDF)
</a>
```

---

### সারসংক্ষেপ

Link / Anchor Attributes হলো `<a>` Tag-এর গুরুত্বপূর্ণ Attribute, যা Link-এর গন্তব্য, আচরণ এবং অতিরিক্ত বৈশিষ্ট্য নির্ধারণ করে। এই অধ্যায়ে **৬টি Link / Anchor Attribute** আলোচনা করা হয়েছে—`href`, `target`, `rel`, `download`, `hreflang` এবং `type`। এগুলোর মাধ্যমে নিরাপদ, SEO-বান্ধব এবং ব্যবহারকারী-বান্ধব Hyperlink তৈরি করা যায়। HTML শেখার ক্ষেত্রে Link Attribute সম্পর্কে পরিষ্কার ধারণা থাকা অত্যন্ত গুরুত্বপূর্ণ, কারণ Web-এর মূল ভিত্তিই হলো Hyperlink।






## 3. Image Attributes

Image Attributes হলো এমন কিছু HTML Attribute, যা মূলত `<img>` Tag-এর সাথে ব্যবহার করা হয়। এগুলোর মাধ্যমে Browser-কে জানানো হয় কোন ছবি প্রদর্শন করতে হবে, ছবির বিকল্প লেখা (Alternative Text) কী হবে, ছবির আকার কত হবে, কীভাবে Load হবে এবং বিভিন্ন Screen Size-এর জন্য কোন ছবি ব্যবহার করতে হবে।

বর্তমান Web Development-এ Image শুধুমাত্র সৌন্দর্য বৃদ্ধির জন্য নয়, বরং **SEO (Search Engine Optimization)**, **Accessibility**, **Performance** এবং **Responsive Design**-এর জন্যও অত্যন্ত গুরুত্বপূর্ণ।

এই অধ্যায়ে আমরা **৭টি Image Attribute** সম্পর্কে জানব।

---

### Image Attribute কী?

Image Attribute হলো এমন Attribute, যা `<img>` Element-এর ছবি প্রদর্শন, আকার, বিকল্প তথ্য এবং লোডিং প্রক্রিয়া নিয়ন্ত্রণ করে।

উদাহরণস্বরূপ—

* `src` → কোন ছবি দেখাবে তা নির্ধারণ করে।
* `alt` → ছবি Load না হলে বিকল্প লেখা দেখায়।
* `width` → ছবির প্রস্থ নির্ধারণ করে।
* `height` → ছবির উচ্চতা নির্ধারণ করে।

---

### Image Attributes-এর মৌলিক কাঠামো

```html
<!DOCTYPE html>
<html>

<head>
    <title>Image Attributes</title>
</head>

<body>

    <img
        src="images/laptop.jpg"
        alt="Laptop Image"
        width="400"
        height="250"
        loading="lazy">

</body>

</html>
```

উপরের Code-এ একটি `<img>` Tag-এর সাথে একাধিক Image Attribute ব্যবহার করা হয়েছে।

---

### Image Attributes-এর তালিকা

| নং | Attribute              | কাজ                                                         |
| -- | ---------------------- | ----------------------------------------------------------- |
| 18 | `src=""`               | ছবির অবস্থান (Source) নির্ধারণ করে                          |
| 19 | `alt=""`               | ছবি Load না হলে বিকল্প লেখা দেখায়                          |
| 20 | `width=""`             | ছবির প্রস্থ নির্ধারণ করে                                    |
| 21 | `height=""`            | ছবির উচ্চতা নির্ধারণ করে                                    |
| 22 | `loading="lazy/eager"` | ছবি কখন Load হবে তা নির্ধারণ করে                            |
| 23 | `srcset=""`            | বিভিন্ন Screen Size-এর জন্য একাধিক ছবি নির্ধারণ করে         |
| 24 | `sizes=""`             | কোন Screen Size-এ কোন Image Size ব্যবহার হবে তা নির্দেশ করে |

---

### Image Attributes Structure

```text
<img>
 │
 ├── src
 ├── alt
 ├── width
 ├── height
 ├── loading
 ├── srcset
 └── sizes
```

---

### প্রতিটি Attribute-এর সংক্ষিপ্ত পরিচয়

#### 18. `src=""`

* Image-এর Source বা Location নির্ধারণ করে।
* Local File অথবা Online URL ব্যবহার করা যায়।
* `src` ছাড়া `<img>` Tag ছবি প্রদর্শন করতে পারে না।

**উদাহরণ**

```html
<img src="images/photo.jpg">
```

---

#### 19. `alt=""`

* ছবি Load না হলে বিকল্প লেখা (Alternative Text) দেখায়।
* Screen Reader ব্যবহারকারীদের জন্য গুরুত্বপূর্ণ।
* SEO উন্নত করতেও সাহায্য করে।

**উদাহরণ**

```html
<img
    src="cat.jpg"
    alt="White Cat">
```

---

#### 20. `width=""`

* ছবির প্রস্থ (Width) নির্ধারণ করে।
* সাধারণত Pixel এককে ব্যবহৃত হয়।

**উদাহরণ**

```html
<img
    src="photo.jpg"
    width="400">
```

---

#### 21. `height=""`

* ছবির উচ্চতা (Height) নির্ধারণ করে।
* Width-এর সাথে ব্যবহার করলে Layout আরও স্থিতিশীল থাকে।

**উদাহরণ**

```html
<img
    src="photo.jpg"
    height="250">
```

---

#### 22. `loading="lazy/eager"`

* Browser কখন Image Load করবে তা নির্ধারণ করে।

সবচেয়ে ব্যবহৃত Value—

| Value   | কাজ                                 |
| ------- | ----------------------------------- |
| `lazy`  | প্রয়োজন হলে পরে Load হবে           |
| `eager` | Page Load হওয়ার সাথে সাথে Load হবে |

**উদাহরণ**

```html
<img
    src="photo.jpg"
    loading="lazy">
```

---

#### 23. `srcset=""`

* বিভিন্ন Screen Resolution বা Device-এর জন্য একাধিক Image নির্ধারণ করে।
* Responsive Website তৈরিতে ব্যবহৃত হয়।

**উদাহরণ**

```html
<img
    src="small.jpg"
    srcset="
        small.jpg 480w,
        medium.jpg 800w,
        large.jpg 1200w">
```

---

#### 24. `sizes=""`

* Browser-কে জানায় কোন Screen Size-এ কত বড় Image ব্যবহার করতে হবে।
* সাধারণত `srcset`-এর সাথে ব্যবহার করা হয়।

**উদাহরণ**

```html
<img
    src="photo.jpg"
    srcset="
        small.jpg 480w,
        large.jpg 1000w"
    sizes="
        (max-width:600px) 100vw,
        600px">
```

---

### Browser কীভাবে Image Attributes পড়ে?

Browser সাধারণত নিচের ধাপগুলো অনুসরণ করে—

```text
HTML Document
      │
      ▼
Read <img> Tag
      │
      ▼
Read src
      │
      ▼
Read Other Attributes
      │
      ▼
Load Image
      │
      ▼
Render Image
```

Browser প্রথমে `src` থেকে ছবির অবস্থান পড়ে। এরপর `width`, `height`, `loading`, `srcset` এবং `sizes` অনুযায়ী ছবি নির্বাচন ও প্রদর্শন করে। যদি ছবি Load না হয়, তাহলে `alt` Text প্রদর্শিত হয়।

---

### Image Attributes-এর গুরুত্ব

* Web Page-এ ছবি প্রদর্শন করে।
* Responsive Image তৈরি করতে সাহায্য করে।
* Website-এর Performance উন্নত করে।
* SEO উন্নত করে।
* Accessibility বৃদ্ধি করে।
* Layout Shift কমায়।
* Mobile এবং Desktop উভয় Device-এ ভালো অভিজ্ঞতা প্রদান করে।

---

### বাস্তব উদাহরণ

ধরুন একটি **ফটো অ্যালবাম** কল্পনা করুন।

| Attribute | বাস্তব উদাহরণ                  |
| --------- | ------------------------------ |
| `src`     | ছবিটি কোথায় রাখা আছে          |
| `alt`     | ছবির বর্ণনা                    |
| `width`   | ছবির প্রস্থ                    |
| `height`  | ছবির উচ্চতা                    |
| `loading` | কখন অ্যালবাম থেকে ছবি বের হবে  |
| `srcset`  | বিভিন্ন আকারের একই ছবি         |
| `sizes`   | কোন আকারের ছবি কখন ব্যবহার হবে |

যেমন একটি ফটো অ্যালবামে ছবির অবস্থান, আকার এবং বিবরণ থাকে, ঠিক তেমনি Image Attribute Browser-কে ছবি সঠিকভাবে প্রদর্শন করতে সাহায্য করে।

---

### Best Practice

* সবসময় `alt` Attribute ব্যবহার করুন।
* সম্ভব হলে `width` এবং `height` নির্ধারণ করুন।
* বড় ছবির ক্ষেত্রে `loading="lazy"` ব্যবহার করুন।
* Responsive Website-এর জন্য `srcset` এবং `sizes` ব্যবহার করুন।
* ছোট আকারের Optimized Image ব্যবহার করুন।
* অর্থপূর্ণ File Name ব্যবহার করুন (যেমন `laptop.jpg`, `flower.png`)।

---

### সাধারণ ভুল (Common Mistakes)

❌ `alt` ব্যবহার না করা

```html
<img src="photo.jpg">
```

✔ সঠিক

```html
<img
    src="photo.jpg"
    alt="Student Reading Book">
```

---

❌ অত্যন্ত বড় ছবি ব্যবহার করা

```html
<img src="large-image.png">
```

✔ সঠিক

* Optimized Image ব্যবহার করুন।
* প্রয়োজন হলে `loading="lazy"` ব্যবহার করুন।

---

❌ শুধুমাত্র `width` বা `height` পরিবর্তন করে ছবির অনুপাত নষ্ট করা

```html
<img
    src="photo.jpg"
    width="400"
    height="50">
```

✔ সঠিক

```html
<img
    src="photo.jpg"
    width="400"
    height="300">
```

---

### সারসংক্ষেপ

Image Attributes হলো `<img>` Tag-এর গুরুত্বপূর্ণ Attribute, যা ছবির অবস্থান, বিকল্প লেখা, আকার, Loading পদ্ধতি এবং Responsive Behavior নিয়ন্ত্রণ করে। এই অধ্যায়ে **৭টি Image Attribute** আলোচনা করা হয়েছে—`src`, `alt`, `width`, `height`, `loading`, `srcset` এবং `sizes`। এগুলোর সঠিক ব্যবহার Website-এর Performance, SEO, Accessibility এবং Responsive Design উন্নত করে। HTML শেখার ক্ষেত্রে Image Attribute সম্পর্কে পরিষ্কার ধারণা থাকা একটি আধুনিক ও মানসম্মত Website তৈরির জন্য অত্যন্ত গুরুত্বপূর্ণ।






## 4. Form Attributes

Form Attributes হলো এমন কিছু HTML Attribute, যা মূলত `<form>`, `<input>`, `<textarea>`, `<select>`, `<button>` এবং অন্যান্য Form Element-এর সাথে ব্যবহার করা হয়। এগুলোর মাধ্যমে Form কোথায় Data পাঠাবে, কীভাবে পাঠাবে, কোন Field বাধ্যতামূলক হবে, কী ধরনের Input গ্রহণ করবে এবং Browser কীভাবে Form পরিচালনা করবে তা নির্ধারণ করা যায়।

Web Development-এ Form অত্যন্ত গুরুত্বপূর্ণ, কারণ User Registration, Login, Contact Form, Search Box, Payment, Order, Survey এবং বিভিন্ন ধরনের তথ্য সংগ্রহের জন্য Form ব্যবহার করা হয়।

এই অধ্যায়ে আমরা **২২টি Form Attribute** সম্পর্কে জানব।

---

### Form Attribute কী?

Form Attribute হলো এমন Attribute, যা Form এবং Form Control-এর আচরণ (Behavior), Validation, Data Submission এবং User Input নিয়ন্ত্রণ করে।

উদাহরণস্বরূপ—

* `action` → Form Data কোথায় পাঠানো হবে তা নির্ধারণ করে।
* `method` → কোন HTTP Method ব্যবহার হবে তা নির্ধারণ করে।
* `required` → Field পূরণ করা বাধ্যতামূলক করে।
* `placeholder` → Input Box-এর Hint দেখায়।

---

### Form Attributes-এর মৌলিক কাঠামো

```html
<!DOCTYPE html>
<html>

<head>
    <title>Form Attributes</title>
</head>

<body>

    <form
        action="/submit"
        method="POST"
        autocomplete="on">

        <input
            type="text"
            name="fullname"
            placeholder="Enter Your Name"
            required>

        <button type="submit">
            Submit
        </button>

    </form>

</body>

</html>
```

উপরের Code-এ একটি Form-এর সাথে একাধিক Form Attribute ব্যবহার করা হয়েছে।

---

### Form Attributes-এর তালিকা

| নং | Attribute               | কাজ                                         |
| -- | ----------------------- | ------------------------------------------- |
| 25 | `action=""`             | Form Data কোথায় পাঠানো হবে তা নির্ধারণ করে |
| 26 | `method="GET/POST"`     | Data কোন Method-এ পাঠানো হবে                |
| 27 | `enctype=""`            | Data Encoding Type নির্ধারণ করে             |
| 28 | `target=""`             | Response কোথায় খুলবে তা নির্ধারণ করে       |
| 29 | `autocomplete="on/off"` | Browser Auto Complete করবে কি না            |
| 30 | `novalidate`            | Browser Validation বন্ধ করে                 |
| 31 | `name=""`               | Field-এর নাম নির্ধারণ করে                   |
| 32 | `value=""`              | Default Value নির্ধারণ করে                  |
| 33 | `placeholder=""`        | Input-এর Hint দেখায়                        |
| 34 | `required`              | Field পূরণ করা বাধ্যতামূলক করে              |
| 35 | `disabled`              | Field নিষ্ক্রিয় করে                        |
| 36 | `readonly`              | শুধুমাত্র পড়া যাবে, পরিবর্তন করা যাবে না   |
| 37 | `min=""`                | সর্বনিম্ন মান নির্ধারণ করে                  |
| 38 | `max=""`                | সর্বোচ্চ মান নির্ধারণ করে                   |
| 39 | `step=""`               | সংখ্যা বৃদ্ধির ধাপ নির্ধারণ করে             |
| 40 | `maxlength=""`          | সর্বোচ্চ Character নির্ধারণ করে             |
| 41 | `minlength=""`          | সর্বনিম্ন Character নির্ধারণ করে            |
| 42 | `pattern=""`            | নির্দিষ্ট Pattern অনুযায়ী Input গ্রহণ করে  |
| 43 | `checked`               | Checkbox বা Radio Default Select করে        |
| 44 | `multiple`              | একাধিক File বা Option নির্বাচন করতে দেয়    |
| 45 | `accept=""`             | কোন ধরনের File গ্রহণ করবে তা নির্ধারণ করে   |
| 46 | `form=""`               | অন্য Form-এর সাথে Element যুক্ত করে         |

---

### Form Attributes Structure

```text
<form>
 │
 ├── action
 ├── method
 ├── enctype
 ├── target
 ├── autocomplete
 ├── novalidate
 │
<input>
 │
 ├── name
 ├── value
 ├── placeholder
 ├── required
 ├── disabled
 ├── readonly
 ├── min
 ├── max
 ├── step
 ├── maxlength
 ├── minlength
 ├── pattern
 ├── checked
 ├── multiple
 ├── accept
 └── form
```

---

### প্রতিটি Attribute-এর সংক্ষিপ্ত পরিচয়

#### 25. `action=""`

* Form Submit হলে Data কোথায় পাঠানো হবে তা নির্ধারণ করে।
* সাধারণত Server URL লেখা হয়।

**উদাহরণ**

```html
<form action="/login">
```

---

#### 26. `method="GET/POST"`

* Data পাঠানোর Method নির্ধারণ করে।

সাধারণ Value—

| Value  | কাজ                                 |
| ------ | ----------------------------------- |
| `GET`  | URL-এর মাধ্যমে Data পাঠায়          |
| `POST` | Request Body-এর মাধ্যমে Data পাঠায় |

**উদাহরণ**

```html
<form method="POST">
```

---

#### 27. `enctype=""`

* Form Data কীভাবে Encode হবে তা নির্ধারণ করে।
* File Upload-এর জন্য গুরুত্বপূর্ণ।

সাধারণ Value—

* `application/x-www-form-urlencoded`
* `multipart/form-data`
* `text/plain`

**উদাহরণ**

```html
<form enctype="multipart/form-data">
```

---

#### 28. `target=""`

* Form Submit হওয়ার পর Response কোথায় খুলবে তা নির্ধারণ করে।

সবচেয়ে ব্যবহৃত Value—

* `_self`
* `_blank`

**উদাহরণ**

```html
<form target="_blank">
```

---

#### 29. `autocomplete="on/off"`

* Browser পূর্বের তথ্য স্বয়ংক্রিয়ভাবে পূরণ করবে কি না নির্ধারণ করে।

**উদাহরণ**

```html
<form autocomplete="on">
```

---

#### 30. `novalidate`

* Browser-এর Built-in Validation বন্ধ করে।
* এটি একটি Boolean Attribute।

**উদাহরণ**

```html
<form novalidate>
```

---

#### 31. `name=""`

* Form Field-এর নাম নির্ধারণ করে।
* Server এই Name ব্যবহার করে Data গ্রহণ করে।

**উদাহরণ**

```html
<input name="email">
```

---

#### 32. `value=""`

* Input-এর Default Value নির্ধারণ করে।

**উদাহরণ**

```html
<input
    value="Hasan">
```

---

#### 33. `placeholder=""`

* Input Box-এর ভিতরে Hint Text দেখায়।

**উদাহরণ**

```html
<input
    placeholder="Enter Your Name">
```

---

#### 34. `required`

* Field পূরণ করা বাধ্যতামূলক করে।
* এটি একটি Boolean Attribute।

**উদাহরণ**

```html
<input required>
```

---

#### 35. `disabled`

* Field সম্পূর্ণ নিষ্ক্রিয় করে।
* User Edit বা Submit করতে পারে না।

**উদাহরণ**

```html
<input disabled>
```

---

#### 36. `readonly`

* Field দেখা যাবে কিন্তু পরিবর্তন করা যাবে না।

**উদাহরণ**

```html
<input
    value="Bangladesh"
    readonly>
```

---

#### 37. `min=""`

* সর্বনিম্ন মান নির্ধারণ করে।

**উদাহরণ**

```html
<input
    type="number"
    min="18">
```

---

#### 38. `max=""`

* সর্বোচ্চ মান নির্ধারণ করে।

**উদাহরণ**

```html
<input
    type="number"
    max="60">
```

---

#### 39. `step=""`

* সংখ্যা কত ধাপে বাড়বে বা কমবে তা নির্ধারণ করে।

**উদাহরণ**

```html
<input
    type="number"
    step="5">
```

---

#### 40. `maxlength=""`

* সর্বোচ্চ কতটি Character লেখা যাবে তা নির্ধারণ করে।

**উদাহরণ**

```html
<input maxlength="20">
```

---

#### 41. `minlength=""`

* সর্বনিম্ন কতটি Character লিখতে হবে তা নির্ধারণ করে।

**উদাহরণ**

```html
<input minlength="8">
```

---

#### 42. `pattern=""`

* নির্দিষ্ট Pattern অনুযায়ী Input গ্রহণ করে।
* সাধারণত Regular Expression (Regex) ব্যবহার করা হয়।

**উদাহরণ**

```html
<input pattern="[A-Za-z]{3,}">
```

---

#### 43. `checked`

* Checkbox বা Radio Button Default অবস্থায় Select থাকে।
* এটি একটি Boolean Attribute।

**উদাহরণ**

```html
<input
    type="checkbox"
    checked>
```

---

#### 44. `multiple`

* একাধিক File বা Option নির্বাচন করতে দেয়।

**উদাহরণ**

```html
<input
    type="file"
    multiple>
```

---

#### 45. `accept=""`

* File Upload-এর সময় কোন ধরনের File গ্রহণ করা হবে তা নির্ধারণ করে।

**উদাহরণ**

```html
<input
    type="file"
    accept=".jpg,.png,.pdf">
```

---

#### 46. `form=""`

* Element-কে নির্দিষ্ট Form-এর সাথে যুক্ত করে, এমনকি Element যদি Form-এর বাইরে থাকে।

**উদাহরণ**

```html
<input
    form="loginForm">
```

---

### Browser কীভাবে Form Attributes পড়ে?

Browser সাধারণত নিচের ধাপগুলো অনুসরণ করে—

```text
HTML Form
      │
      ▼
Read Form Attributes
      │
      ▼
Read User Input
      │
      ▼
Validate Data
      │
      ▼
Submit Form
      │
      ▼
Send Data to Server
```

Browser প্রথমে Form-এর Attribute পড়ে, এরপর User-এর Input গ্রহণ করে, Validation সম্পন্ন করে এবং সবশেষে Data Server-এ পাঠায়।

---

### Form Attributes-এর গুরুত্ব

* Form Submission নিয়ন্ত্রণ করে।
* User Input Validation নিশ্চিত করে।
* ভুল Data প্রবেশ কমায়।
* File Upload সহজ করে।
* User Experience উন্নত করে।
* Browser-এর Auto Complete সুবিধা প্রদান করে।
* নিরাপদ এবং সুশৃঙ্খলভাবে Data Server-এ পাঠাতে সাহায্য করে।

---

### বাস্তব উদাহরণ

ধরুন একটি **ব্যাংকের Account Opening Form** কল্পনা করুন।

| Attribute     | বাস্তব উদাহরণ                      |
| ------------- | ---------------------------------- |
| `action`      | আবেদন কোথায় জমা হবে               |
| `method`      | কীভাবে আবেদন পাঠানো হবে            |
| `name`        | আবেদনকারীর তথ্যের নাম              |
| `placeholder` | কী লিখতে হবে তার নির্দেশনা         |
| `required`    | বাধ্যতামূলক তথ্য                   |
| `disabled`    | পরিবর্তন করা যাবে না এমন অংশ       |
| `accept`      | কোন ধরনের Document জমা দেওয়া যাবে |
| `multiple`    | একাধিক Document আপলোড              |

যেমন একটি ব্যাংক Form-এ বিভিন্ন নিয়ম ও শর্ত থাকে, ঠিক তেমনি Form Attribute একটি HTML Form-এর সম্পূর্ণ কার্যপ্রণালী নিয়ন্ত্রণ করে।

---

### Best Practice

* সবসময় `POST` Method ব্যবহার করুন যখন সংবেদনশীল তথ্য পাঠানো হয়।
* প্রতিটি Input-এর জন্য অর্থপূর্ণ `name` ব্যবহার করুন।
* প্রয়োজনীয় Field-এ `required` ব্যবহার করুন।
* File Upload-এর ক্ষেত্রে `accept` এবং `enctype="multipart/form-data"` ব্যবহার করুন।
* Input Validation-এর জন্য `pattern`, `min`, `max` এবং `maxlength` ব্যবহার করুন।
* User Experience উন্নত করতে `placeholder` এবং `autocomplete` ব্যবহার করুন।

---

### সাধারণ ভুল (Common Mistakes)

❌ `name` Attribute ব্যবহার না করা

```html
<input type="text">
```

✔ সঠিক

```html
<input
    type="text"
    name="fullname">
```

---

❌ File Upload-এ `enctype` ব্যবহার না করা

```html
<form method="POST">
```

✔ সঠিক

```html
<form
    method="POST"
    enctype="multipart/form-data">
```

---

❌ বাধ্যতামূলক Field-এ `required` না ব্যবহার করা

```html
<input
    type="email">
```

✔ সঠিক

```html
<input
    type="email"
    required>
```

---

### সারসংক্ষেপ

Form Attributes হলো HTML Form এবং Form Control-এর গুরুত্বপূর্ণ Attribute, যা Form Submission, User Input, Validation এবং Data Processing নিয়ন্ত্রণ করে। এই অধ্যায়ে **২২টি Form Attribute** আলোচনা করা হয়েছে—`action`, `method`, `enctype`, `target`, `autocomplete`, `novalidate`, `name`, `value`, `placeholder`, `required`, `disabled`, `readonly`, `min`, `max`, `step`, `maxlength`, `minlength`, `pattern`, `checked`, `multiple`, `accept` এবং `form`। এগুলোর সঠিক ব্যবহার নিরাপদ, ব্যবহারকারী-বান্ধব এবং কার্যকর Form তৈরির জন্য অত্যন্ত গুরুত্বপূর্ণ।






## 5. Input Type Attributes

Input Type Attributes বলতে `<input>` Tag-এর `type` Attribute-এর বিভিন্ন মান (Value) বোঝায়। `type` Attribute-এর মাধ্যমে Browser-কে জানানো হয় User কী ধরনের তথ্য (Input) প্রদান করবে। এর উপর ভিত্তি করে Browser বিভিন্ন ধরনের Input Control প্রদর্শন করে, যেমন—Text Box, Password Field, Email Field, Number Field, Checkbox, Radio Button, File Upload, Date Picker ইত্যাদি।

আধুনিক HTML5-এ `type` Attribute-এর মাধ্যমে Browser নিজেই অনেক ক্ষেত্রে **Validation**, **User Interface (UI)** এবং **User Experience (UX)** উন্নত করে।

এই অধ্যায়ে আমরা **১৩টি Input Type** সম্পর্কে জানব।

---

### Input Type Attribute কী?

`type` হলো `<input>` Tag-এর সবচেয়ে গুরুত্বপূর্ণ Attribute। এটি নির্ধারণ করে Input Field-এর ধরন কী হবে এবং User কী ধরনের তথ্য প্রদান করতে পারবে।

উদাহরণস্বরূপ—

* `type="text"` → সাধারণ লেখা গ্রহণ করে।
* `type="password"` → Password গ্রহণ করে।
* `type="email"` → Email Address গ্রহণ করে।
* `type="file"` → File Upload করার সুযোগ দেয়।

---

### Input Type Attributes-এর মৌলিক কাঠামো

```html
<!DOCTYPE html>
<html>

<head>
    <title>Input Type Attributes</title>
</head>

<body>

    <form>

        <input
            type="text"
            placeholder="Enter Your Name">

        <input
            type="email"
            placeholder="Enter Your Email">

        <input
            type="password"
            placeholder="Enter Password">

    </form>

</body>

</html>
```

উপরের Code-এ `<input>` Tag-এর সাথে বিভিন্ন `type` Attribute ব্যবহার করা হয়েছে।

---

### Input Type Attributes-এর তালিকা

| নং | Attribute         | কাজ                                        |
| -- | ----------------- | ------------------------------------------ |
| 47 | `type="text"`     | সাধারণ Text Input গ্রহণ করে                |
| 48 | `type="password"` | Password Input গ্রহণ করে                   |
| 49 | `type="email"`    | Email Address গ্রহণ করে                    |
| 50 | `type="number"`   | শুধুমাত্র সংখ্যা গ্রহণ করে                 |
| 51 | `type="radio"`    | একাধিক Option থেকে একটি নির্বাচন করতে দেয় |
| 52 | `type="checkbox"` | একাধিক Option নির্বাচন করতে দেয়           |
| 53 | `type="file"`     | File Upload করতে দেয়                      |
| 54 | `type="date"`     | Date নির্বাচন করতে দেয়                    |
| 55 | `type="submit"`   | Form Submit করে                            |
| 56 | `type="reset"`    | Form-এর সব তথ্য Reset করে                  |
| 57 | `type="button"`   | সাধারণ Button তৈরি করে                     |
| 58 | `type="range"`    | Slider Input প্রদান করে                    |
| 59 | `type="color"`    | Color Picker প্রদর্শন করে                  |

---

### Input Type Structure

```text
<input>
   │
   └── type
         │
         ├── text
         ├── password
         ├── email
         ├── number
         ├── radio
         ├── checkbox
         ├── file
         ├── date
         ├── submit
         ├── reset
         ├── button
         ├── range
         └── color
```

---

### প্রতিটি Input Type-এর সংক্ষিপ্ত পরিচয়

#### 47. `type="text"`

* সাধারণ Text Input গ্রহণ করে।
* Name, Address, City ইত্যাদি লেখার জন্য ব্যবহৃত হয়।

**উদাহরণ**

```html
<input
    type="text"
    placeholder="Enter Your Name">
```

---

#### 48. `type="password"`

* Password লিখতে ব্যবহৃত হয়।
* Browser Character গোপন (Mask) করে দেখায়।

**উদাহরণ**

```html
<input
    type="password"
    placeholder="Enter Password">
```

---

#### 49. `type="email"`

* Email Address গ্রহণ করে।
* Browser Email Format Validation করতে পারে।

**উদাহরণ**

```html
<input
    type="email"
    placeholder="example@email.com">
```

---

#### 50. `type="number"`

* শুধুমাত্র সংখ্যা গ্রহণ করে।
* `min`, `max` এবং `step` Attribute-এর সাথে ব্যবহার করা যায়।

**উদাহরণ**

```html
<input
    type="number"
    min="1"
    max="100">
```

---

#### 51. `type="radio"`

* একাধিক Option-এর মধ্যে শুধুমাত্র একটি নির্বাচন করা যায়।
* একই `name` ব্যবহার করলে একটি Group তৈরি হয়।

**উদাহরণ**

```html
<input
    type="radio"
    name="gender">
```

---

#### 52. `type="checkbox"`

* একাধিক Option নির্বাচন করা যায়।

**উদাহরণ**

```html
<input
    type="checkbox">
```

---

#### 53. `type="file"`

* User File নির্বাচন ও Upload করতে পারে।
* `accept` এবং `multiple` Attribute-এর সাথে ব্যবহার করা হয়।

**উদাহরণ**

```html
<input
    type="file"
    accept=".jpg,.png">
```

---

#### 54. `type="date"`

* Browser একটি Date Picker প্রদর্শন করে।

**উদাহরণ**

```html
<input
    type="date">
```

---

#### 55. `type="submit"`

* Form-এর তথ্য Server-এ Submit করে।

**উদাহরণ**

```html
<input
    type="submit"
    value="Submit">
```

---

#### 56. `type="reset"`

* Form-এর সকল তথ্য Default অবস্থায় ফিরিয়ে আনে।

**উদাহরণ**

```html
<input
    type="reset"
    value="Reset">
```

---

#### 57. `type="button"`

* সাধারণ Button তৈরি করে।
* JavaScript Event-এর সাথে বেশি ব্যবহৃত হয়।

**উদাহরণ**

```html
<input
    type="button"
    value="Click Me">
```

---

#### 58. `type="range"`

* Slider আকারে Number নির্বাচন করতে দেয়।

**উদাহরণ**

```html
<input
    type="range"
    min="0"
    max="100">
```

---

#### 59. `type="color"`

* Browser একটি Color Picker প্রদর্শন করে।

**উদাহরণ**

```html
<input
    type="color">
```

---

### Browser কীভাবে Input Type পড়ে?

Browser সাধারণত নিচের ধাপগুলো অনুসরণ করে—

```text
HTML Document
      │
      ▼
Read <input>
      │
      ▼
Read type Attribute
      │
      ▼
Create Input Control
      │
      ▼
Accept User Input
```

Browser প্রথমে `<input>` Tag পড়ে, এরপর `type` Attribute অনুযায়ী উপযুক্ত Input Control তৈরি করে এবং User-এর Input গ্রহণ করে।

---

### Input Type Attributes-এর গুরুত্ব

* বিভিন্ন ধরনের User Input গ্রহণ করতে সাহায্য করে।
* Browser-এর Built-in Validation ব্যবহার করা যায়।
* User Experience (UX) উন্নত করে।
* Mobile Device-এ উপযুক্ত Keyboard প্রদর্শন করে।
* Form আরও সহজ ও কার্যকর করে।
* Data Entry-তে ভুল কমায়।

---

### বাস্তব উদাহরণ

ধরুন একটি **অনলাইন Registration Form** কল্পনা করুন।

| Input Type | বাস্তব উদাহরণ      |
| ---------- | ------------------ |
| `text`     | নাম                |
| `password` | পাসওয়ার্ড         |
| `email`    | ইমেইল              |
| `number`   | বয়স               |
| `radio`    | লিঙ্গ নির্বাচন     |
| `checkbox` | শর্তে সম্মতি       |
| `file`     | ছবি আপলোড          |
| `date`     | জন্মতারিখ          |
| `submit`   | আবেদন জমা          |
| `reset`    | তথ্য মুছে ফেলা     |
| `button`   | বিশেষ কাজের Button |
| `range`    | সন্তুষ্টির মাত্রা  |
| `color`    | প্রিয় রঙ নির্বাচন |

যেমন একটি Registration Form-এ বিভিন্ন ধরনের তথ্যের জন্য আলাদা আলাদা ঘর থাকে, ঠিক তেমনি `type` Attribute Browser-কে বলে দেয় কোন ধরনের Input Field প্রদর্শন করতে হবে।

---

### Best Practice

* তথ্যের ধরন অনুযায়ী সঠিক `type` ব্যবহার করুন।
* Email-এর জন্য `type="email"` ব্যবহার করুন।
* Password-এর জন্য `type="password"` ব্যবহার করুন।
* সংখ্যার জন্য `type="number"` ব্যবহার করুন।
* File Upload-এর জন্য `accept` Attribute ব্যবহার করুন।
* `placeholder`, `required` এবং `name` Attribute ব্যবহার করতে ভুলবেন না।

---

### সাধারণ ভুল (Common Mistakes)

❌ Email Field-এ `text` ব্যবহার করা

```html
<input
    type="text">
```

✔ সঠিক

```html
<input
    type="email">
```

---

❌ Password Field-এ `text` ব্যবহার করা

```html
<input
    type="text">
```

✔ সঠিক

```html
<input
    type="password">
```

---

❌ Number Field-এ `text` ব্যবহার করা

```html
<input
    type="text">
```

✔ সঠিক

```html
<input
    type="number">
```

---

### সারসংক্ষেপ

Input Type Attributes হলো `<input>` Tag-এর `type` Attribute-এর বিভিন্ন মান, যা Input Field-এর ধরন নির্ধারণ করে। এই অধ্যায়ে **১৩টি Input Type** আলোচনা করা হয়েছে—`text`, `password`, `email`, `number`, `radio`, `checkbox`, `file`, `date`, `submit`, `reset`, `button`, `range` এবং `color`। এগুলোর সঠিক ব্যবহার Form-কে আরও নিরাপদ, ব্যবহারকারী-বান্ধব এবং কার্যকর করে তোলে। HTML Form তৈরির ক্ষেত্রে `type` Attribute সম্পর্কে পরিষ্কার ধারণা থাকা অত্যন্ত গুরুত্বপূর্ণ।






## 6. Script Attributes

Script Attributes হলো এমন কিছু HTML Attribute, যা মূলত `<script>` Tag-এর সাথে ব্যবহার করা হয়। এগুলোর মাধ্যমে Browser-কে জানানো হয় JavaScript File কোথা থেকে Load হবে, কখন Execute হবে, কী ধরনের Script ব্যবহার করা হচ্ছে এবং অন্য Server থেকে Script Load করার সময় কী ধরনের নিরাপত্তা (Security) নীতি অনুসরণ করা হবে।

আধুনিক Web Development-এ JavaScript Website-কে Interactive ও Dynamic করে তোলে। তাই Script Attribute-এর সঠিক ব্যবহার Website-এর **Performance**, **Loading Speed**, **Security** এবং **User Experience (UX)** উন্নত করতে গুরুত্বপূর্ণ ভূমিকা পালন করে।

এই অধ্যায়ে আমরা **৫টি Script Attribute** সম্পর্কে জানব।

---

### Script Attribute কী?

Script Attribute হলো এমন Attribute, যা `<script>` Tag-এর আচরণ (Behavior), Script Loading Process এবং Execution নিয়ন্ত্রণ করে।

উদাহরণস্বরূপ—

* `src` → কোন JavaScript File Load হবে তা নির্ধারণ করে।
* `async` → Script আলাদাভাবে Download ও Execute করে।
* `defer` → HTML সম্পূর্ণ Load হওয়ার পরে Script Execute করে।
* `type="module"` → JavaScript Module ব্যবহার করতে দেয়।

---

### Script Attributes-এর মৌলিক কাঠামো

```html
<!DOCTYPE html>
<html>

<head>
    <title>Script Attributes</title>

    <script
        src="app.js"
        defer>
    </script>

</head>

<body>

    <h1>Hello World</h1>

</body>

</html>
```

উপরের Code-এ `<script>` Tag-এর সাথে `src` এবং `defer` Attribute ব্যবহার করা হয়েছে।

---

### Script Attributes-এর তালিকা

| নং | Attribute        | কাজ                                              |
| -- | ---------------- | ------------------------------------------------ |
| 60 | `src=""`         | JavaScript File-এর অবস্থান নির্ধারণ করে          |
| 61 | `async`          | Script স্বাধীনভাবে Download ও Execute করে        |
| 62 | `defer`          | HTML সম্পূর্ণ Load হওয়ার পরে Script Execute করে |
| 63 | `type="module"`  | JavaScript Module হিসেবে Script চালায়           |
| 64 | `crossorigin=""` | Cross-Origin Request-এর নিয়ম নির্ধারণ করে       |

---

### Script Attributes Structure

```text
<script>
    │
    ├── src
    ├── async
    ├── defer
    ├── type="module"
    └── crossorigin
```

---

### প্রতিটি Attribute-এর সংক্ষিপ্ত পরিচয়

#### 60. `src=""`

* External JavaScript File যুক্ত করার জন্য ব্যবহৃত হয়।
* Local File অথবা Online URL ব্যবহার করা যায়।
* বড় Project-এ Inline Script-এর পরিবর্তে External File ব্যবহার করা Best Practice।

**উদাহরণ**

```html
<script src="app.js"></script>
```

---

#### 61. `async`

* Browser HTML Parse করার পাশাপাশি Script Download করে।
* Download শেষ হওয়ার সাথে সাথেই Script Execute হয়।
* HTML Parsing সাময়িকভাবে থেমে যেতে পারে।
* সাধারণত Independent Script-এর জন্য ব্যবহৃত হয়।
* এটি একটি **Boolean Attribute**।

**উদাহরণ**

```html
<script
    src="analytics.js"
    async>
</script>
```

---

#### 62. `defer`

* Browser HTML Parse করার সময় Script Download করে।
* HTML সম্পূর্ণ Parse হওয়ার পরে Script Execute হয়।
* একাধিক `defer` Script থাকলে সেগুলো ক্রমানুসারে Execute হয়।
* অধিকাংশ Website-এর জন্য এটি Best Practice।

**উদাহরণ**

```html
<script
    src="app.js"
    defer>
</script>
```

---

#### 63. `type="module"`

* JavaScript ES Module ব্যবহার করার জন্য ব্যবহৃত হয়।
* `import` এবং `export` ব্যবহার করা যায়।
* প্রতিটি Module নিজস্ব Scope-এ কাজ করে।
* আধুনিক JavaScript Development-এ বহুল ব্যবহৃত।

**উদাহরণ**

```html
<script
    type="module"
    src="main.js">
</script>
```

---

#### 64. `crossorigin=""`

* অন্য Domain থেকে Script Load করার সময় Security Policy নির্ধারণ করে।
* সাধারণত CDN থেকে File Load করার সময় ব্যবহৃত হয়।

সবচেয়ে ব্যবহৃত Value—

| Value             | কাজ                                        |
| ----------------- | ------------------------------------------ |
| `anonymous`       | User Credential ছাড়া Request পাঠায়       |
| `use-credentials` | Cookie ও Authentication Information পাঠায় |

**উদাহরণ**

```html
<script
    src="https://cdn.example.com/app.js"
    crossorigin="anonymous">
</script>
```

---

### Browser কীভাবে Script Attributes পড়ে?

Browser সাধারণত নিচের ধাপগুলো অনুসরণ করে—

```text
HTML Document
      │
      ▼
Read <script> Tag
      │
      ▼
Read Script Attributes
      │
      ▼
Download Script
      │
      ▼
Execute Script
      │
      ▼
Update Web Page
```

Browser প্রথমে `<script>` Tag পড়ে, তারপর `src`, `async`, `defer`, `type` এবং `crossorigin` অনুযায়ী JavaScript File Download ও Execute করে।

---

### `async` এবং `defer`-এর পার্থক্য

| Attribute | কাজ                                          |
| --------- | -------------------------------------------- |
| `async`   | Download শেষ হলেই Script Execute হয়         |
| `defer`   | HTML সম্পূর্ণ Load হওয়ার পরে Execute হয়    |
| `async`   | Script-এর Execution Order নিশ্চিত নয়        |
| `defer`   | Script-এর Execution Order বজায় থাকে         |
| `async`   | Analytics বা Tracking Script-এর জন্য উপযুক্ত |
| `defer`   | Website-এর Main JavaScript-এর জন্য উপযুক্ত   |

---

### Script Attributes-এর গুরুত্ব

* External JavaScript File যুক্ত করতে সাহায্য করে।
* Website-এর Loading Speed উন্নত করে।
* Performance বৃদ্ধি করে।
* JavaScript Module ব্যবহার করা যায়।
* Cross-Origin Security নিশ্চিত করে।
* Browser Blocking কমায়।
* বড় Project আরও সহজে পরিচালনা করা যায়।

---

### বাস্তব উদাহরণ

ধরুন একটি **নাটকের মঞ্চ** কল্পনা করুন।

| Attribute       | বাস্তব উদাহরণ                                |
| --------------- | -------------------------------------------- |
| `src`           | অভিনেতাকে কোথা থেকে আনা হবে                  |
| `async`         | অভিনেতা প্রস্তুত হলেই মঞ্চে উঠবে             |
| `defer`         | পুরো মঞ্চ প্রস্তুত হওয়ার পরে অভিনেতা আসবে   |
| `type="module"` | অভিনেতাদের আলাদা আলাদা দলে ভাগ করা           |
| `crossorigin`   | বাইরের দলকে কী নিয়মে প্রবেশ করতে দেওয়া হবে |

যেমন একটি নাটকে অভিনেতাদের সঠিক সময়ে মঞ্চে আনা হয়, ঠিক তেমনি Script Attribute Browser-কে বলে দেয় JavaScript কখন এবং কীভাবে চালাতে হবে।

---

### Best Practice

* External JavaScript-এর জন্য `src` ব্যবহার করুন।
* অধিকাংশ ক্ষেত্রে `defer` ব্যবহার করুন।
* আধুনিক Project-এ `type="module"` ব্যবহার করুন।
* CDN ব্যবহার করলে প্রয়োজনে `crossorigin` ব্যবহার করুন।
* অপ্রয়োজনীয় Inline JavaScript এড়িয়ে চলুন।
* Script File-এর নাম অর্থপূর্ণ রাখুন (যেমন `main.js`, `app.js`, `login.js`)।

---

### সাধারণ ভুল (Common Mistakes)

❌ HTML Block করে এমন Script ব্যবহার করা

```html
<script src="app.js"></script>
```

✔ সঠিক

```html
<script
    src="app.js"
    defer>
</script>
```

---

❌ ES Module ব্যবহার করে `type="module"` না লেখা

```html
<script src="main.js"></script>
```

✔ সঠিক

```html
<script
    type="module"
    src="main.js">
</script>
```

---

❌ বড় Project-এ Inline JavaScript ব্যবহার করা

```html
<script>

console.log("Hello");

</script>
```

✔ সঠিক

```html
<script
    src="app.js"
    defer>
</script>
```

---

### সারসংক্ষেপ

Script Attributes হলো `<script>` Tag-এর গুরুত্বপূর্ণ Attribute, যা JavaScript File-এর Loading, Execution এবং Security নিয়ন্ত্রণ করে। এই অধ্যায়ে **৫টি Script Attribute** আলোচনা করা হয়েছে—`src`, `async`, `defer`, `type="module"` এবং `crossorigin`। এগুলোর সঠিক ব্যবহার Website-এর Performance, Loading Speed, Security এবং Maintainability উন্নত করে। আধুনিক Web Development-এ কার্যকর ও দ্রুতগতির Website তৈরির জন্য Script Attribute সম্পর্কে পরিষ্কার ধারণা থাকা অত্যন্ত গুরুত্বপূর্ণ।






## 7. Table Attributes

Table Attributes হলো এমন কিছু HTML Attribute, যা মূলত `<table>`, `<th>` এবং `<td>` Element-এর সাথে ব্যবহার করা হয়। এগুলোর মাধ্যমে Table-এর Cell একত্রিত করা, Header-এর সম্পর্ক নির্ধারণ করা এবং Table-এর গঠন (Structure) আরও অর্থবহ (Semantic) করা যায়।

HTML5-এ Table Attribute-এর সঠিক ব্যবহার **Data Organization**, **Accessibility**, **Screen Reader Support** এবং **Semantic Structure** উন্নত করে।

এই অধ্যায়ে আমরা **৪টি Table Attribute** সম্পর্কে জানব।

---

### Table Attribute কী?

Table Attribute হলো এমন Attribute, যা Table-এর Cell-এর সম্পর্ক, আকার এবং Header-এর সাথে Data Cell-এর সংযোগ নির্ধারণ করে।

উদাহরণস্বরূপ—

* `colspan` → একাধিক Column একত্রিত করে।
* `rowspan` → একাধিক Row একত্রিত করে।
* `scope` → Header কোন অংশের জন্য প্রযোজ্য তা নির্ধারণ করে।
* `headers` → Data Cell কোন Header-এর সাথে সম্পর্কিত তা নির্ধারণ করে।

---

### Table Attributes-এর মৌলিক কাঠামো

```html
<!DOCTYPE html>
<html>

<head>
    <title>Table Attributes</title>
</head>

<body>

    <table border="1">

        <tr>
            <th scope="col">Name</th>
            <th scope="col">Age</th>
        </tr>

        <tr>
            <td>Hasan</td>
            <td>20</td>
        </tr>

    </table>

</body>

</html>
```

উপরের Code-এ `<th>` Element-এর সাথে `scope` Attribute ব্যবহার করা হয়েছে।

---

### Table Attributes-এর তালিকা

| নং | Attribute    | কাজ                                                       |
| -- | ------------ | --------------------------------------------------------- |
| 65 | `colspan=""` | একাধিক Column একত্রিত করে                                 |
| 66 | `rowspan=""` | একাধিক Row একত্রিত করে                                    |
| 67 | `scope=""`   | Header কোন Row বা Column-এর জন্য প্রযোজ্য তা নির্ধারণ করে |
| 68 | `headers=""` | Data Cell-এর সাথে Header Cell-এর সম্পর্ক নির্ধারণ করে     |

---

### Table Attributes Structure

```text
<table>
      │
      ├── <th>
      │      └── scope
      │
      └── <td>
             ├── colspan
             ├── rowspan
             └── headers
```

---

### প্রতিটি Attribute-এর সংক্ষিপ্ত পরিচয়

#### 65. `colspan=""`

* একটি Cell-কে একাধিক Column জুড়ে বিস্তৃত করে।
* সাধারণত Table-এর Title বা Summary Cell তৈরিতে ব্যবহৃত হয়।

**উদাহরণ**

```html
<tr>
    <th colspan="3">
        Student Information
    </th>
</tr>
```

---

#### 66. `rowspan=""`

* একটি Cell-কে একাধিক Row জুড়ে বিস্তৃত করে।
* একই তথ্য একাধিক Row-এ দেখানোর পরিবর্তে একটি Cell ব্যবহার করা যায়।

**উদাহরণ**

```html
<tr>
    <td rowspan="2">
        Hasan
    </td>

    <td>Math</td>
</tr>

<tr>
    <td>English</td>
</tr>
```

---

#### 67. `scope=""`

* Header Cell (`<th>`) কোন Row বা Column-এর জন্য প্রযোজ্য তা নির্ধারণ করে।
* Accessibility উন্নত করতে ব্যবহৃত হয়।

সবচেয়ে ব্যবহৃত Value—

| Value      | কাজ                       |
| ---------- | ------------------------- |
| `col`      | Column Header নির্দেশ করে |
| `row`      | Row Header নির্দেশ করে    |
| `colgroup` | Column Group নির্দেশ করে  |
| `rowgroup` | Row Group নির্দেশ করে     |

**উদাহরণ**

```html
<th scope="col">
    Name
</th>
```

---

#### 68. `headers=""`

* Data Cell (`<td>`) কোন Header Cell-এর সাথে সম্পর্কিত তা নির্ধারণ করে।
* সাধারণত জটিল (Complex) Table-এ ব্যবহার করা হয়।
* `headers` Attribute-এর Value হিসেবে সংশ্লিষ্ট `<th>` Element-এর `id` ব্যবহার করা হয়।

**উদাহরণ**

```html
<th id="name">
    Name
</th>

<td headers="name">
    Hasan
</td>
```

---

### Browser কীভাবে Table Attributes পড়ে?

Browser সাধারণত নিচের ধাপগুলো অনুসরণ করে—

```text
HTML Table
      │
      ▼
Read Table Attributes
      │
      ▼
Merge Rows / Columns
      │
      ▼
Identify Header Cells
      │
      ▼
Render Table
```

Browser প্রথমে Table-এর Attribute পড়ে, এরপর Cell Merge, Header সম্পর্ক নির্ধারণ করে এবং সবশেষে Table প্রদর্শন করে।

---

### Table Attributes-এর গুরুত্ব

* Table-এর গঠন আরও পরিষ্কার করে।
* একাধিক Row বা Column সহজে একত্রিত করা যায়।
* Accessibility উন্নত করে।
* Screen Reader Header ও Data-এর সম্পর্ক বুঝতে পারে।
* Complex Data সুন্দরভাবে উপস্থাপন করা যায়।
* Semantic HTML অনুসরণ করা সহজ হয়।

---

### বাস্তব উদাহরণ

ধরুন একটি **স্কুলের ফলাফল শিট** কল্পনা করুন।

| Attribute | বাস্তব উদাহরণ                                           |
| --------- | ------------------------------------------------------- |
| `colspan` | "বার্ষিক পরীক্ষার ফলাফল" শিরোনাম পুরো Table জুড়ে থাকবে |
| `rowspan` | একই ছাত্রের নাম একাধিক Subject-এর জন্য একবার দেখানো     |
| `scope`   | কোন Header কোন Column বা Row-এর জন্য তা নির্ধারণ        |
| `headers` | প্রতিটি নম্বর কোন Subject-এর তা নির্ধারণ                |

যেমন একটি Result Sheet-এ একই ছাত্রের নাম বারবার না লিখে একবার দেখানো হয়, ঠিক তেমনি `rowspan` এবং `colspan` Table-কে আরও সুন্দর ও সুশৃঙ্খল করে।

---

### Best Practice

* Header-এর জন্য সবসময় `<th>` ব্যবহার করুন।
* Accessibility-এর জন্য `scope` ব্যবহার করুন।
* জটিল Table-এ `headers` Attribute ব্যবহার করুন।
* অপ্রয়োজনীয় `rowspan` ও `colspan` ব্যবহার এড়িয়ে চলুন।
* Data Table-এর জন্য Semantic Structure বজায় রাখুন।

---

### সাধারণ ভুল (Common Mistakes)

❌ Header-এর জন্য `<td>` ব্যবহার করা

```html
<td>
    Name
</td>
```

✔ সঠিক

```html
<th scope="col">
    Name
</th>
```

---

❌ অতিরিক্ত `colspan` ব্যবহার করা

```html
<td colspan="10">
```

✔ শুধুমাত্র প্রয়োজনীয় সংখ্যক Column Merge করুন।

---

❌ `headers` ব্যবহার করলেও `id` না দেওয়া

```html
<th>
    Name
</th>

<td headers="name">
    Hasan
</td>
```

✔ সঠিক

```html
<th id="name">
    Name
</th>

<td headers="name">
    Hasan
</td>
```

---

### সারসংক্ষেপ

Table Attributes হলো HTML Table-এর গুরুত্বপূর্ণ Attribute, যা Table-এর Cell Merge, Header সম্পর্ক এবং Semantic Structure নিয়ন্ত্রণ করে। এই অধ্যায়ে **৪টি Table Attribute** আলোচনা করা হয়েছে—`colspan`, `rowspan`, `scope` এবং `headers`। এগুলোর সঠিক ব্যবহার Table-কে আরও সুন্দর, অর্থবহ, ব্যবহারকারী-বান্ধব এবং Accessibility-সম্মত করে। বড় এবং জটিল Data Table তৈরি করার জন্য Table Attribute সম্পর্কে পরিষ্কার ধারণা থাকা অত্যন্ত গুরুত্বপূর্ণ।






## 8. Media Attributes (Audio / Video)

Media Attributes হলো এমন কিছু HTML Attribute, যা মূলত `<audio>` এবং `<video>` Element-এর সাথে ব্যবহার করা হয়। এগুলোর মাধ্যমে Media File কীভাবে Play হবে, User কী ধরনের Control পাবে, Media স্বয়ংক্রিয়ভাবে চলবে কি না, বারবার চলবে কি না এবং Browser কীভাবে Media Load করবে তা নির্ধারণ করা যায়।

HTML5-এর মাধ্যমে Audio ও Video সরাসরি Browser-এ চালানো সম্ভব হয়েছে। Media Attribute-এর সঠিক ব্যবহার Website-এর **Performance**, **User Experience (UX)** এবং **Accessibility** উন্নত করে।

এই অধ্যায়ে আমরা **৭টি Media Attribute** সম্পর্কে জানব।

---

### Media Attribute কী?

Media Attribute হলো এমন Attribute, যা Audio এবং Video Element-এর আচরণ (Behavior), Playback এবং Loading নিয়ন্ত্রণ করে।

উদাহরণস্বরূপ—

* `controls` → Play, Pause, Volume Control দেখায়।
* `autoplay` → Media স্বয়ংক্রিয়ভাবে চালু করে।
* `muted` → Media-এর Sound বন্ধ রাখে।
* `loop` → Media বারবার চালায়।

---

### Media Attributes-এর মৌলিক কাঠামো

```html
<!DOCTYPE html>
<html>

<head>
    <title>Media Attributes</title>
</head>

<body>

    <video
        src="video.mp4"
        controls
        width="600"
        poster="thumbnail.jpg">
    </video>

</body>

</html>
```

উপরের Code-এ `<video>` Element-এর সাথে একাধিক Media Attribute ব্যবহার করা হয়েছে।

---

### Media Attributes-এর তালিকা

| নং | Attribute                      | কাজ                                                |
| -- | ------------------------------ | -------------------------------------------------- |
| 69 | `controls`                     | Media Control Button দেখায়                        |
| 70 | `autoplay`                     | Media স্বয়ংক্রিয়ভাবে চালু করে                    |
| 71 | `muted`                        | Media-এর Sound বন্ধ রাখে                           |
| 72 | `loop`                         | Media বারবার চালায়                                |
| 73 | `poster=""`                    | Video চালুর আগে Thumbnail Image দেখায়             |
| 74 | `preload="auto/metadata/none"` | Browser কতটুকু Media আগে Load করবে তা নির্ধারণ করে |
| 75 | `src=""`                       | Audio বা Video File-এর অবস্থান নির্ধারণ করে        |

---

### Media Attributes Structure

```text
<audio> / <video>
        │
        ├── src
        ├── controls
        ├── autoplay
        ├── muted
        ├── loop
        ├── poster
        └── preload
```

---

### প্রতিটি Attribute-এর সংক্ষিপ্ত পরিচয়

#### 69. `controls`

* Browser-এর Default Media Control প্রদর্শন করে।
* সাধারণত Play, Pause, Volume, Seek Bar এবং Fullscreen Button থাকে।
* এটি একটি **Boolean Attribute**।

**উদাহরণ**

```html
<video controls>
```

---

#### 70. `autoplay`

* Page Load হওয়ার সাথে সাথে Media স্বয়ংক্রিয়ভাবে চালু হয়।
* অনেক Browser-এ `muted` ছাড়া Autoplay কাজ নাও করতে পারে।
* এটি একটি **Boolean Attribute**।

**উদাহরণ**

```html
<video
    autoplay
    muted>
```

---

#### 71. `muted`

* Media-এর Sound বন্ধ রাখে।
* Autoplay Video-এর ক্ষেত্রে এটি প্রায়ই প্রয়োজন হয়।
* এটি একটি **Boolean Attribute**।

**উদাহরণ**

```html
<video muted>
```

---

#### 72. `loop`

* Media শেষ হওয়ার পরে আবার শুরু থেকে চালু হয়।
* এটি একটি **Boolean Attribute**।

**উদাহরণ**

```html
<audio loop>
```

---

#### 73. `poster=""`

* শুধুমাত্র `<video>` Element-এর জন্য ব্যবহৃত হয়।
* Video Play হওয়ার আগে একটি Preview Image দেখায়।

**উদাহরণ**

```html
<video
    poster="cover.jpg">
```

---

#### 74. `preload="auto/metadata/none"`

* Browser কতটুকু Media আগে থেকে Load করবে তা নির্ধারণ করে।

সবচেয়ে ব্যবহৃত Value—

| Value      | কাজ                              |
| ---------- | -------------------------------- |
| `auto`     | সম্ভব হলে পুরো Media Load করে    |
| `metadata` | শুধুমাত্র Media-এর তথ্য Load করে |
| `none`     | আগে থেকে কিছুই Load করে না       |

**উদাহরণ**

```html
<audio
    preload="metadata">
```

---

#### 75. `src=""`

* Media File-এর Location নির্ধারণ করে।
* Local File অথবা Online URL ব্যবহার করা যায়।

**উদাহরণ**

```html
<audio
    src="music.mp3"
    controls>
```

---

### Browser কীভাবে Media Attributes পড়ে?

Browser সাধারণত নিচের ধাপগুলো অনুসরণ করে—

```text
HTML Document
      │
      ▼
Read Audio / Video Tag
      │
      ▼
Read Media Attributes
      │
      ▼
Load Media File
      │
      ▼
Apply Settings
      │
      ▼
Play Media
```

Browser প্রথমে Media Element পড়ে, তারপর Attribute অনুযায়ী Media Load করে এবং নির্ধারিত নিয়ম অনুসারে Play করে।

---

### Media Attributes-এর গুরুত্ব

* Audio ও Video সহজে নিয়ন্ত্রণ করা যায়।
* Website-এর User Experience উন্নত করে।
* Media Loading Performance বৃদ্ধি করে।
* Bandwidth সাশ্রয় করতে সাহায্য করে।
* User-এর জন্য Media Control সহজ করে।
* Video-এর জন্য Preview Image দেখানো যায়।
* Responsive এবং আধুনিক Website তৈরিতে গুরুত্বপূর্ণ ভূমিকা পালন করে।

---

### বাস্তব উদাহরণ

ধরুন একটি **মিউজিক প্লেয়ার** কল্পনা করুন।

| Attribute  | বাস্তব উদাহরণ               |
| ---------- | --------------------------- |
| `src`      | কোন গান বাজবে               |
| `controls` | Play, Pause ও Volume Button |
| `autoplay` | অ্যাপ খুললেই গান চালু হওয়া |
| `muted`    | শুরুতেই শব্দ বন্ধ থাকা      |
| `loop`     | গান শেষ হলে আবার শুরু হওয়া |
| `poster`   | Album Cover দেখানো          |
| `preload`  | গান আগে থেকেই Buffer করা    |

যেমন একটি Music Player-এ Play, Pause এবং Volume নিয়ন্ত্রণ করা যায়, ঠিক তেমনি Media Attribute Browser-কে Media কীভাবে পরিচালনা করতে হবে তা নির্দেশ দেয়।

---

### Best Practice

* User-এর সুবিধার জন্য `controls` ব্যবহার করুন।
* অপ্রয়োজনীয় `autoplay` ব্যবহার এড়িয়ে চলুন।
* বড় Video-এর জন্য `preload="metadata"` ব্যবহার করুন।
* Video-এর জন্য `poster` Image ব্যবহার করুন।
* Media File-এর জন্য অর্থপূর্ণ File Name ব্যবহার করুন।
* একাধিক Format Support-এর জন্য `<source>` Tag ব্যবহার করা ভালো।

---

### সাধারণ ভুল (Common Mistakes)

❌ `controls` ব্যবহার না করা

```html
<video
    src="video.mp4">
</video>
```

✔ সঠিক

```html
<video
    src="video.mp4"
    controls>
</video>
```

---

❌ `autoplay` ব্যবহার করে `muted` না দেওয়া

```html
<video autoplay>
```

✔ সঠিক

```html
<video
    autoplay
    muted>
```

---

❌ Video-এর জন্য `poster` ব্যবহার না করা

```html
<video controls>
```

✔ সঠিক

```html
<video
    controls
    poster="thumbnail.jpg">
```

---

### সারসংক্ষেপ

Media Attributes হলো `<audio>` এবং `<video>` Element-এর গুরুত্বপূর্ণ Attribute, যা Media File-এর Loading, Playback এবং User Control নিয়ন্ত্রণ করে। এই অধ্যায়ে **৭টি Media Attribute** আলোচনা করা হয়েছে—`controls`, `autoplay`, `muted`, `loop`, `poster`, `preload` এবং `src`। এগুলোর সঠিক ব্যবহার Website-এর Performance, User Experience এবং Accessibility উন্নত করে। আধুনিক HTML5 Website-এ কার্যকরভাবে Audio ও Video ব্যবহারের জন্য Media Attribute সম্পর্কে পরিষ্কার ধারণা থাকা অত্যন্ত গুরুত্বপূর্ণ।






## 9. Iframe Attributes

Iframe Attributes হলো এমন কিছু HTML Attribute, যা মূলত `<iframe>` Element-এর সাথে ব্যবহার করা হয়। এগুলোর মাধ্যমে অন্য একটি Web Page, Website, Document, Map, Video বা Web Application কীভাবে একটি Web Page-এর ভিতরে প্রদর্শিত হবে তা নিয়ন্ত্রণ করা যায়।

`<iframe>` (Inline Frame) ব্যবহার করে একটি HTML Page-এর ভিতরে অন্য একটি HTML Page বা External Content Embed করা যায়। Iframe Attribute-এর সঠিক ব্যবহার **Security**, **Performance**, **Privacy**, **Responsive Design** এবং **User Experience (UX)** উন্নত করতে গুরুত্বপূর্ণ ভূমিকা পালন করে।

এই অধ্যায়ে আমরা **৭টি Iframe Attribute** সম্পর্কে জানব।

---

### Iframe Attribute কী?

Iframe Attribute হলো এমন Attribute, যা `<iframe>` Element-এর Source, Size, Permission, Security এবং Loading Behavior নিয়ন্ত্রণ করে।

উদাহরণস্বরূপ—

* `src` → কোন Web Page বা Resource দেখানো হবে।
* `width` → Iframe-এর প্রস্থ নির্ধারণ করে।
* `height` → Iframe-এর উচ্চতা নির্ধারণ করে।
* `sandbox` → নিরাপত্তা সীমাবদ্ধতা নির্ধারণ করে।

---

### Iframe Attributes-এর মৌলিক কাঠামো

```html
<!DOCTYPE html>
<html>

<head>
    <title>Iframe Attributes</title>
</head>

<body>

    <iframe
        src="https://example.com"
        width="800"
        height="500"
        loading="lazy">
    </iframe>

</body>

</html>
```

উপরের Code-এ `<iframe>` Element-এর সাথে একাধিক Iframe Attribute ব্যবহার করা হয়েছে।

---

### Iframe Attributes-এর তালিকা

| নং | Attribute           | কাজ                                                   |
| -- | ------------------- | ----------------------------------------------------- |
| 76 | `src=""`            | Embed করা Web Page বা Resource-এর ঠিকানা নির্ধারণ করে |
| 77 | `width=""`          | Iframe-এর প্রস্থ নির্ধারণ করে                         |
| 78 | `height=""`         | Iframe-এর উচ্চতা নির্ধারণ করে                         |
| 79 | `allow=""`          | Iframe-এর অনুমোদিত Feature নির্ধারণ করে               |
| 80 | `sandbox=""`        | নিরাপত্তা সীমাবদ্ধতা নির্ধারণ করে                     |
| 81 | `loading="lazy"`    | Iframe কখন Load হবে তা নির্ধারণ করে                   |
| 82 | `referrerpolicy=""` | Referrer তথ্য কীভাবে পাঠানো হবে তা নির্ধারণ করে       |

---

### Iframe Attributes Structure

```text
<iframe>
      │
      ├── src
      ├── width
      ├── height
      ├── allow
      ├── sandbox
      ├── loading
      └── referrerpolicy
```

---

### প্রতিটি Attribute-এর সংক্ষিপ্ত পরিচয়

#### 76. `src=""`

* Iframe-এর ভিতরে কোন Web Page, Document বা Resource দেখানো হবে তা নির্ধারণ করে।
* Local File অথবা Online URL ব্যবহার করা যায়।

**উদাহরণ**

```html
<iframe
    src="about.html">
</iframe>
```

---

#### 77. `width=""`

* Iframe-এর প্রস্থ (Width) নির্ধারণ করে।
* Pixel (`px`) অথবা Percentage (`%`) ব্যবহার করা যায়।

**উদাহরণ**

```html
<iframe
    width="800">
</iframe>
```

---

#### 78. `height=""`

* Iframe-এর উচ্চতা (Height) নির্ধারণ করে।

**উদাহরণ**

```html
<iframe
    height="500">
</iframe>
```

---

#### 79. `allow=""`

* Iframe কোন Browser Feature ব্যবহার করতে পারবে তা নির্ধারণ করে।
* সাধারণত Camera, Microphone, Fullscreen, Clipboard ইত্যাদির অনুমতি দেওয়ার জন্য ব্যবহৃত হয়।

সবচেয়ে ব্যবহৃত Value—

* `fullscreen`
* `camera`
* `microphone`
* `clipboard-read`
* `clipboard-write`

**উদাহরণ**

```html
<iframe
    src="video.html"
    allow="fullscreen">
</iframe>
```

---

#### 80. `sandbox=""`

* Iframe-এর জন্য নিরাপত্তা সীমাবদ্ধতা নির্ধারণ করে।
* প্রয়োজনীয় Permission আলাদাভাবে দেওয়া যায়।

সবচেয়ে ব্যবহৃত Value—

* `allow-scripts`
* `allow-forms`
* `allow-popups`
* `allow-same-origin`

**উদাহরণ**

```html
<iframe
    src="page.html"
    sandbox="allow-scripts">
</iframe>
```

---

#### 81. `loading="lazy"`

* Iframe কখন Load হবে তা নির্ধারণ করে।

সবচেয়ে ব্যবহৃত Value—

| Value   | কাজ                                 |
| ------- | ----------------------------------- |
| `lazy`  | প্রয়োজন হলে পরে Load করে           |
| `eager` | Page Load হওয়ার সাথে সাথে Load করে |

**উদাহরণ**

```html
<iframe
    src="map.html"
    loading="lazy">
</iframe>
```

---

#### 82. `referrerpolicy=""`

* Browser অন্য Website-এ কতটুকু Referrer Information পাঠাবে তা নির্ধারণ করে।
* Privacy এবং Security-এর জন্য গুরুত্বপূর্ণ।

সবচেয়ে ব্যবহৃত Value—

| Value           | কাজ                              |
| --------------- | -------------------------------- |
| `no-referrer`   | কোনো Referrer পাঠায় না          |
| `origin`        | শুধুমাত্র Domain পাঠায়          |
| `strict-origin` | নিরাপদ পরিস্থিতিতে Origin পাঠায় |

**উদাহরণ**

```html
<iframe
    src="https://example.com"
    referrerpolicy="no-referrer">
</iframe>
```

---

### Browser কীভাবে Iframe Attributes পড়ে?

Browser সাধারণত নিচের ধাপগুলো অনুসরণ করে—

```text
HTML Document
      │
      ▼
Read <iframe> Tag
      │
      ▼
Read Iframe Attributes
      │
      ▼
Load External Page
      │
      ▼
Apply Security Rules
      │
      ▼
Display Iframe
```

Browser প্রথমে `<iframe>` Tag পড়ে, এরপর Attribute অনুযায়ী External Resource Load করে এবং নির্ধারিত Security Policy প্রয়োগ করে।

---

### Iframe Attributes-এর গুরুত্ব

* অন্য Website বা Page সহজে Embed করা যায়।
* Google Map, YouTube Video ও Document প্রদর্শন করা যায়।
* Website-এর Security উন্নত করা যায়।
* Privacy Policy নিয়ন্ত্রণ করা যায়।
* Lazy Loading-এর মাধ্যমে Performance বৃদ্ধি করা যায়।
* Responsive Design তৈরিতে সহায়তা করে।
* আধুনিক Web Application তৈরিতে গুরুত্বপূর্ণ ভূমিকা পালন করে।

---

### বাস্তব উদাহরণ

ধরুন একটি **Shopping Mall-এর একটি দোকান** কল্পনা করুন।

| Attribute        | বাস্তব উদাহরণ                       |
| ---------------- | ----------------------------------- |
| `src`            | কোন দোকানটি দেখানো হবে              |
| `width`          | দোকানের প্রস্থ                      |
| `height`         | দোকানের উচ্চতা                      |
| `allow`          | দোকান কোন সুবিধা ব্যবহার করতে পারবে |
| `sandbox`        | দোকানের নিরাপত্তা নিয়ম             |
| `loading`        | কখন দোকানটি খোলা হবে                |
| `referrerpolicy` | বাইরের তথ্য কতটুকু শেয়ার করা হবে   |

যেমন একটি Shopping Mall-এর ভিতরে আলাদা দোকান থাকে, ঠিক তেমনি একটি Web Page-এর ভিতরে `<iframe>` ব্যবহার করে অন্য একটি Web Page প্রদর্শন করা যায়।

---

### Best Practice

* শুধুমাত্র বিশ্বস্ত (Trusted) Website Embed করুন।
* প্রয়োজন হলে `sandbox` ব্যবহার করুন।
* বড় Page-এর জন্য `loading="lazy"` ব্যবহার করুন।
* Privacy রক্ষার জন্য `referrerpolicy` ব্যবহার করুন।
* Responsive Layout-এর জন্য CSS ব্যবহার করুন।
* শুধুমাত্র প্রয়োজনীয় Permission `allow` Attribute-এ দিন।

---

### সাধারণ ভুল (Common Mistakes)

❌ `src` ব্যবহার না করা

```html
<iframe></iframe>
```

✔ সঠিক

```html
<iframe
    src="page.html">
</iframe>
```

---

❌ অপ্রয়োজনীয়ভাবে সব Permission দেওয়া

```html
<iframe
    allow="camera microphone fullscreen">
</iframe>
```

✔ শুধুমাত্র প্রয়োজনীয় Permission দিন।

---

❌ বড় Iframe-এ Lazy Loading ব্যবহার না করা

```html
<iframe
    src="map.html">
</iframe>
```

✔ সঠিক

```html
<iframe
    src="map.html"
    loading="lazy">
</iframe>
```

---

### সারসংক্ষেপ

Iframe Attributes হলো `<iframe>` Element-এর গুরুত্বপূর্ণ Attribute, যা Embedded Web Page-এর Source, Size, Permission, Security, Privacy এবং Loading নিয়ন্ত্রণ করে। এই অধ্যায়ে **৭টি Iframe Attribute** আলোচনা করা হয়েছে—`src`, `width`, `height`, `allow`, `sandbox`, `loading` এবং `referrerpolicy`। এগুলোর সঠিক ব্যবহার Website-কে আরও নিরাপদ, দ্রুত, ব্যবহারকারী-বান্ধব এবং আধুনিক করে তোলে। HTML-এ External Content Embed করার জন্য Iframe Attribute সম্পর্কে পরিষ্কার ধারণা থাকা অত্যন্ত গুরুত্বপূর্ণ।






## 10. Meta Attributes

Meta Attributes হলো এমন কিছু HTML Attribute, যা মূলত `<meta>` Element-এর সাথে ব্যবহার করা হয়। এগুলোর মাধ্যমে Browser, Search Engine এবং অন্যান্য Web Service-কে Web Page সম্পর্কে অতিরিক্ত তথ্য (Metadata) প্রদান করা হয়।

Metadata সরাসরি Web Page-এ দেখা যায় না, তবে এটি Browser, Search Engine Optimization (SEO), Social Media Sharing, Character Encoding এবং HTTP Response-এর জন্য অত্যন্ত গুরুত্বপূর্ণ।

এই অধ্যায়ে আমরা **৪টি Meta Attribute** সম্পর্কে জানব।

---

### Meta Attribute কী?

Meta Attribute হলো এমন Attribute, যা `<meta>` Tag-এর মাধ্যমে Web Page-এর বিভিন্ন তথ্য নির্ধারণ করে।

উদাহরণস্বরূপ—

* `charset` → Character Encoding নির্ধারণ করে।
* `name` → Metadata-এর ধরন নির্ধারণ করে।
* `content` → Metadata-এর প্রকৃত মান (Value) প্রদান করে।
* `http-equiv` → HTTP Header-এর মতো নির্দেশনা প্রদান করে।

---

### Meta Attributes-এর মৌলিক কাঠামো

```html
<!DOCTYPE html>
<html>

<head>

    <meta charset="UTF-8">

    <meta
        name="description"
        content="Learn HTML Meta Attributes">

</head>

<body>

</body>

</html>
```

উপরের Code-এ `<meta>` Element-এর সাথে `charset`, `name` এবং `content` Attribute ব্যবহার করা হয়েছে।

---

### Meta Attributes-এর তালিকা

| নং | Attribute       | কাজ                                     |
| -- | --------------- | --------------------------------------- |
| 83 | `charset=""`    | Character Encoding নির্ধারণ করে         |
| 84 | `name=""`       | Metadata-এর ধরন নির্ধারণ করে            |
| 85 | `content=""`    | Metadata-এর মান (Value) নির্ধারণ করে    |
| 86 | `http-equiv=""` | HTTP Header-এর মতো নির্দেশনা প্রদান করে |

---

### Meta Attributes Structure

```text
<meta>
     │
     ├── charset
     ├── name
     ├── content
     └── http-equiv
```

---

### প্রতিটি Attribute-এর সংক্ষিপ্ত পরিচয়

#### 83. `charset=""`

* Web Page-এর Character Encoding নির্ধারণ করে।
* বর্তমানে `UTF-8` সবচেয়ে বেশি ব্যবহৃত Encoding।
* বাংলা, ইংরেজি এবং অন্যান্য ভাষা সঠিকভাবে প্রদর্শনের জন্য এটি গুরুত্বপূর্ণ।

**উদাহরণ**

```html
<meta charset="UTF-8">
```

---

#### 84. `name=""`

* Metadata-এর ধরন নির্ধারণ করে।
* সাধারণত SEO, Author, Viewport এবং Description-এর জন্য ব্যবহৃত হয়।

সবচেয়ে ব্যবহৃত Value—

| Value         | কাজ                                   |
| ------------- | ------------------------------------- |
| `description` | Page-এর সংক্ষিপ্ত বিবরণ               |
| `keywords`    | গুরুত্বপূর্ণ Keyword                  |
| `author`      | Page-এর লেখক                          |
| `viewport`    | Responsive Design নিয়ন্ত্রণ করে      |
| `robots`      | Search Engine Crawling নিয়ন্ত্রণ করে |

**উদাহরণ**

```html
<meta
    name="author"
    content="Hasan">
```

---

#### 85. `content=""`

* `name` অথবা `http-equiv` Attribute-এর মান (Value) নির্ধারণ করে।
* Metadata-এর মূল তথ্য এখানে লেখা হয়।

**উদাহরণ**

```html
<meta
    name="description"
    content="HTML Tutorial">
```

---

#### 86. `http-equiv=""`

* Browser-কে HTTP Header-এর মতো নির্দেশনা প্রদান করে।
* Page Refresh, Cache Control এবং Compatibility-এর জন্য ব্যবহৃত হয়।

সবচেয়ে ব্যবহৃত Value—

| Value                     | কাজ                                            |
| ------------------------- | ---------------------------------------------- |
| `refresh`                 | নির্দিষ্ট সময় পরে Page Reload বা Redirect করে |
| `X-UA-Compatible`         | Browser Compatibility নির্ধারণ করে             |
| `Content-Security-Policy` | নিরাপত্তা নীতি নির্ধারণ করে                    |

**উদাহরণ**

```html
<meta
    http-equiv="refresh"
    content="5">
```

উপরের Code-এ Page ৫ সেকেন্ড পরে Reload হবে।

---

### Browser কীভাবে Meta Attributes পড়ে?

Browser সাধারণত নিচের ধাপগুলো অনুসরণ করে—

```text
HTML Document
      │
      ▼
Read <head>
      │
      ▼
Read <meta> Tag
      │
      ▼
Read Meta Attributes
      │
      ▼
Apply Browser Settings
      │
      ▼
Render Web Page
```

Browser প্রথমে `<head>` অংশ পড়ে, তারপর `<meta>` Tag-এর Attribute অনুযায়ী বিভিন্ন সেটিং প্রয়োগ করে।

---

### Meta Attributes-এর গুরুত্ব

* Character Encoding সঠিকভাবে নির্ধারণ করে।
* SEO উন্নত করতে সাহায্য করে।
* Responsive Website তৈরিতে সহায়তা করে।
* Search Engine-কে Page সম্পর্কে তথ্য দেয়।
* Browser Compatibility উন্নত করে।
* Social Media Preview উন্নত করতে সাহায্য করে।
* Web Security উন্নত করতে সহায়তা করে।

---

### বাস্তব উদাহরণ

ধরুন একটি **বইয়ের প্রচ্ছদ (Book Cover)** কল্পনা করুন।

| Attribute    | বাস্তব উদাহরণ             |
| ------------ | ------------------------- |
| `charset`    | বইটি কোন ভাষায় লেখা      |
| `name`       | বইয়ের তথ্যের ধরন         |
| `content`    | বইয়ের বিস্তারিত তথ্য     |
| `http-equiv` | প্রকাশকের বিশেষ নির্দেশনা |

যেমন একটি বইয়ের প্রচ্ছদে বইয়ের নাম, লেখক ও প্রকাশনার তথ্য থাকে, ঠিক তেমনি Meta Attribute একটি Web Page সম্পর্কে Browser এবং Search Engine-কে গুরুত্বপূর্ণ তথ্য প্রদান করে।

---

### Best Practice

* সবসময় `UTF-8` Encoding ব্যবহার করুন।
* প্রতিটি Page-এর জন্য অর্থপূর্ণ `description` লিখুন।
* Responsive Website-এর জন্য `viewport` Meta Tag ব্যবহার করুন।
* SEO-এর জন্য `author`, `description` এবং `robots` ব্যবহার করুন।
* অপ্রয়োজনীয় Meta Tag ব্যবহার করবেন না।
* Meta Tag সবসময় `<head>` Section-এর ভিতরে রাখুন।

---

### সাধারণ ভুল (Common Mistakes)

❌ `charset` ব্যবহার না করা

```html
<head>

</head>
```

✔ সঠিক

```html
<head>

<meta charset="UTF-8">

</head>
```

---

❌ `content` ছাড়া `name` ব্যবহার করা

```html
<meta name="description">
```

✔ সঠিক

```html
<meta
    name="description"
    content="HTML Learning Website">
```

---

❌ Meta Tag-কে `<body>`-এর ভিতরে রাখা

```html
<body>

<meta charset="UTF-8">

</body>
```

✔ সঠিক

```html
<head>

<meta charset="UTF-8">

</head>
```

---

### সারসংক্ষেপ

Meta Attributes হলো `<meta>` Element-এর গুরুত্বপূর্ণ Attribute, যা Browser, Search Engine এবং অন্যান্য Web Service-কে Web Page সম্পর্কে অতিরিক্ত তথ্য প্রদান করে। এই অধ্যায়ে **৪টি Meta Attribute** আলোচনা করা হয়েছে—`charset`, `name`, `content` এবং `http-equiv`। এগুলোর সঠিক ব্যবহার Website-এর SEO, Performance, Character Encoding, Browser Compatibility এবং Security উন্নত করে। আধুনিক ও Professional Website তৈরির জন্য Meta Attribute সম্পর্কে পরিষ্কার ধারণা থাকা অত্যন্ত গুরুত্বপূর্ণ।






## 11. List Attributes

List Attributes হলো এমন কিছু HTML Attribute, যা মূলত `<ol>` (Ordered List) এবং `<li>` (List Item) Element-এর সাথে ব্যবহার করা হয়। এগুলোর মাধ্যমে List-এর সংখ্যা কোথা থেকে শুরু হবে, উল্টো ক্রমে (Reverse Order) প্রদর্শিত হবে কি না এবং নির্দিষ্ট List Item-এর সংখ্যা নির্ধারণ করা যায়।

HTML List Attribute-এর সঠিক ব্যবহার List-কে আরও **সুশৃঙ্খল (Organized)**, **অর্থবহ (Semantic)** এবং **পাঠযোগ্য (Readable)** করে তোলে। বিশেষ করে বড় Document, Tutorial, Step-by-Step Guide এবং Question Paper তৈরিতে এগুলোর গুরুত্বপূর্ণ ভূমিকা রয়েছে।

এই অধ্যায়ে আমরা **৩টি List Attribute** সম্পর্কে জানব।

---

### List Attribute কী?

List Attribute হলো এমন Attribute, যা HTML List-এর Numbering এবং Display নিয়ন্ত্রণ করে।

উদাহরণস্বরূপ—

* `start` → List কোন সংখ্যা থেকে শুরু হবে তা নির্ধারণ করে।
* `reversed` → List উল্টো ক্রমে প্রদর্শন করে।
* `value` → নির্দিষ্ট List Item-এর Number নির্ধারণ করে।

---

### List Attributes-এর মৌলিক কাঠামো

```html id="4v8b2h"
<!DOCTYPE html>
<html>

<head>
    <title>List Attributes</title>
</head>

<body>

    <ol start="5">

        <li>HTML</li>
        <li>CSS</li>
        <li>JavaScript</li>

    </ol>

</body>

</html>
```

উপরের Code-এ `<ol>` Element-এর সাথে `start` Attribute ব্যবহার করা হয়েছে।

---

### List Attributes-এর তালিকা

| নং | Attribute  | কাজ                                                   |
| -- | ---------- | ----------------------------------------------------- |
| 87 | `start=""` | Ordered List কোন সংখ্যা থেকে শুরু হবে তা নির্ধারণ করে |
| 88 | `reversed` | Ordered List উল্টো ক্রমে প্রদর্শন করে                 |
| 89 | `value=""` | নির্দিষ্ট List Item-এর Number নির্ধারণ করে            |

---

### List Attributes Structure

```text id="v1r0au"
<ol>
   │
   ├── start
   ├── reversed
   │
   └── <li>
         └── value
```

---

### প্রতিটি Attribute-এর সংক্ষিপ্ত পরিচয়

#### 87. `start=""`

* Ordered List (`<ol>`) কোন সংখ্যা থেকে শুরু হবে তা নির্ধারণ করে।
* Default মান (Value) হলো `1`।
* যেকোনো পূর্ণসংখ্যা (Integer) ব্যবহার করা যায়।

**উদাহরণ**

```html id="vx5vv9"
<ol start="10">

    <li>HTML</li>
    <li>CSS</li>
    <li>JavaScript</li>

</ol>
```

উপরের List-এর Numbering `10` থেকে শুরু হবে।

---

#### 88. `reversed`

* Ordered List-কে উল্টো ক্রমে (Descending Order) প্রদর্শন করে।
* এটি একটি **Boolean Attribute**।
* বড় থেকে ছোট সংখ্যায় Numbering দেখানোর জন্য ব্যবহৃত হয়।

**উদাহরণ**

```html id="7u74x5"
<ol reversed>

    <li>Step One</li>
    <li>Step Two</li>
    <li>Step Three</li>

</ol>
```

উপরের List শেষ সংখ্যা থেকে শুরু হবে।

---

#### 89. `value=""`

* নির্দিষ্ট `<li>` Element-এর Number নির্ধারণ করে।
* মাঝখান থেকে নতুন Numbering শুরু করতে ব্যবহার করা হয়।
* শুধুমাত্র `<li>` Element-এর সাথে ব্যবহার করা হয়।

**উদাহরণ**

```html id="6e4b6o"
<ol>

    <li>HTML</li>

    <li value="10">
        CSS
    </li>

    <li>JavaScript</li>

</ol>
```

উপরের উদাহরণে দ্বিতীয় Item-এর Number হবে `10` এবং পরবর্তী Item-এর Number হবে `11`।

---

### Browser কীভাবে List Attributes পড়ে?

Browser সাধারণত নিচের ধাপগুলো অনুসরণ করে—

```text id="lfmjlwm"
Read <ol>
      │
      ▼
Read List Attributes
      │
      ▼
Generate Numbering
      │
      ▼
Apply Value
      │
      ▼
Display List
```

Browser প্রথমে `<ol>` Element পড়ে, তারপর `start`, `reversed` এবং `value` অনুযায়ী Numbering তৈরি করে এবং শেষে List প্রদর্শন করে।

---

### List Attributes-এর গুরুত্ব

* Numbering সহজে নিয়ন্ত্রণ করা যায়।
* Step-by-Step Guide তৈরি করা সহজ হয়।
* বড় Document আরও সুন্দরভাবে উপস্থাপন করা যায়।
* পুনরায় Numbering শুরু করা যায়।
* Ordered List আরও অর্থবহ হয়।
* Tutorial, Exam Paper এবং Instruction List তৈরিতে গুরুত্বপূর্ণ ভূমিকা পালন করে।

---

### বাস্তব উদাহরণ

ধরুন একটি **দৌড় প্রতিযোগিতার ফলাফল** কল্পনা করুন।

| Attribute  | বাস্তব উদাহরণ                                  |
| ---------- | ---------------------------------------------- |
| `start`    | প্রতিযোগিতা ১০ নম্বর থেকে শুরু করা             |
| `reversed` | শেষ স্থান থেকে প্রথম স্থানের দিকে ফলাফল দেখানো |
| `value`    | নির্দিষ্ট প্রতিযোগীকে বিশেষ Ranking দেওয়া     |

যেমন একটি প্রতিযোগিতার Ranking যেকোনো সংখ্যা থেকে শুরু করা যায় বা উল্টোভাবে দেখানো যায়, ঠিক তেমনি List Attribute HTML List-এর Numbering নিয়ন্ত্রণ করে।

---

### Best Practice

* শুধুমাত্র Ordered List-এর জন্য `start` ব্যবহার করুন।
* প্রয়োজন হলে `reversed` ব্যবহার করুন।
* অপ্রয়োজনীয়ভাবে `value` ব্যবহার করবেন না।
* List-এর Numbering যেন অর্থবহ হয়।
* বড় Tutorial বা Documentation-এ Numbering সঠিকভাবে ব্যবহার করুন।

---

### সাধারণ ভুল (Common Mistakes)

❌ `start` Attribute `<ul>`-এর সাথে ব্যবহার করা

```html id="n4m1md"
<ul start="5">

    <li>HTML</li>

</ul>
```

✔ সঠিক

```html id="mzhbqo"
<ol start="5">

    <li>HTML</li>

</ol>
```

---

❌ `value` Attribute `<ol>`-এর সাথে ব্যবহার করা

```html id="3gv1n2"
<ol value="5">
```

✔ সঠিক

```html id="66u5jw"
<li value="5">
    HTML
</li>
```

---

❌ অপ্রয়োজনীয়ভাবে `reversed` ব্যবহার করা

```html id="w0v5bp"
<ol reversed>

    <li>HTML</li>
    <li>CSS</li>

</ol>
```

✔ শুধুমাত্র প্রয়োজন হলে `reversed` ব্যবহার করুন।

---

### সারসংক্ষেপ

List Attributes হলো HTML List-এর গুরুত্বপূর্ণ Attribute, যা Ordered List-এর Numbering এবং প্রদর্শনের ধরন নিয়ন্ত্রণ করে। এই অধ্যায়ে **৩টি List Attribute** আলোচনা করা হয়েছে—`start`, `reversed` এবং `value`। এগুলোর সঠিক ব্যবহার List-কে আরও সুন্দর, অর্থবহ এবং ব্যবহারকারী-বান্ধব করে তোলে। বড় Tutorial, Documentation এবং Step-by-Step নির্দেশিকা তৈরির জন্য List Attribute সম্পর্কে পরিষ্কার ধারণা থাকা অত্যন্ত গুরুত্বপূর্ণ।






## 12. Button Attributes

Button Attributes হলো এমন কিছু HTML Attribute, যা মূলত `<button>` Element-এর সাথে ব্যবহার করা হয়। এগুলোর মাধ্যমে Button-এর ধরন (Type), সক্রিয় বা নিষ্ক্রিয় অবস্থা, নাম (Name) এবং পাঠানো মান (Value) নির্ধারণ করা যায়।

HTML Form এবং Interactive Web Application তৈরিতে Button-এর গুরুত্বপূর্ণ ভূমিকা রয়েছে। Button Attribute-এর সঠিক ব্যবহার **Form Submission**, **User Interaction**, **Accessibility** এবং **User Experience (UX)** উন্নত করে।

এই অধ্যায়ে আমরা **৪টি Button Attribute** সম্পর্কে জানব।

---

### Button Attribute কী?

Button Attribute হলো এমন Attribute, যা `<button>` Element-এর আচরণ (Behavior) এবং Form-এর সাথে এর কার্যক্রম নিয়ন্ত্রণ করে।

উদাহরণস্বরূপ—

* `type` → Button-এর কাজ নির্ধারণ করে।
* `disabled` → Button নিষ্ক্রিয় করে।
* `name` → Button-এর নাম নির্ধারণ করে।
* `value` → Button Click হলে কোন মান পাঠানো হবে তা নির্ধারণ করে।

---

### Button Attributes-এর মৌলিক কাঠামো

```html
<!DOCTYPE html>
<html>

<head>
    <title>Button Attributes</title>
</head>

<body>

    <form>

        <button
            type="submit"
            name="save"
            value="true">

            Save

        </button>

    </form>

</body>

</html>
```

উপরের Code-এ `<button>` Element-এর সাথে `type`, `name` এবং `value` Attribute ব্যবহার করা হয়েছে।

---

### Button Attributes-এর তালিকা

| নং | Attribute                    | কাজ                                       |
| -- | ---------------------------- | ----------------------------------------- |
| 90 | `type="button/submit/reset"` | Button-এর কাজ নির্ধারণ করে                |
| 91 | `disabled`                   | Button নিষ্ক্রিয় করে                     |
| 92 | `name=""`                    | Button-এর নাম নির্ধারণ করে                |
| 93 | `value=""`                   | Button-এর পাঠানো মান (Value) নির্ধারণ করে |

---

### Button Attributes Structure

```text
<button>
      │
      ├── type
      ├── disabled
      ├── name
      └── value
```

---

### প্রতিটি Attribute-এর সংক্ষিপ্ত পরিচয়

#### 90. `type="button/submit/reset"`

* Button কী কাজ করবে তা নির্ধারণ করে।
* যদি `type` উল্লেখ না করা হয়, তাহলে `<button>`-এর Default Type সাধারণত `submit` হয়।

সবচেয়ে ব্যবহৃত Value—

| Value    | কাজ                             |
| -------- | ------------------------------- |
| `button` | শুধুমাত্র Button হিসেবে কাজ করে |
| `submit` | Form Submit করে                 |
| `reset`  | Form-এর সকল Input Reset করে     |

**উদাহরণ**

```html
<button type="submit">
    Submit
</button>
```

---

#### 91. `disabled`

* Button-কে নিষ্ক্রিয় (Disabled) করে।
* Disabled Button-এ Click করা যায় না।
* এটি একটি **Boolean Attribute**।

**উদাহরণ**

```html
<button disabled>
    Save
</button>
```

---

#### 92. `name=""`

* Button-এর নাম নির্ধারণ করে।
* Form Submit হলে Server Button-এর Name শনাক্ত করতে পারে।
* সাধারণত `value` Attribute-এর সাথে ব্যবহার করা হয়।

**উদাহরণ**

```html
<button
    name="login">
    Login
</button>
```

---

#### 93. `value=""`

* Button Click করলে Form-এর সাথে কোন Value পাঠানো হবে তা নির্ধারণ করে।
* Server-side Programming-এ এটি গুরুত্বপূর্ণ।

**উদাহরণ**

```html
<button
    name="action"
    value="save">
    Save
</button>
```

---

### Browser কীভাবে Button Attributes পড়ে?

Browser সাধারণত নিচের ধাপগুলো অনুসরণ করে—

```text
Read <button>
      │
      ▼
Read Button Attributes
      │
      ▼
Check Type
      │
      ▼
Wait for Click
      │
      ▼
Perform Action
```

Browser প্রথমে `<button>` Element পড়ে, তারপর Attribute অনুযায়ী Button-এর কাজ নির্ধারণ করে এবং User Click করলে সেই অনুযায়ী Action সম্পন্ন করে।

---

### Button Attributes-এর গুরুত্ব

* Button-এর কাজ নির্ধারণ করে।
* Form Submission নিয়ন্ত্রণ করে।
* User Interaction সহজ করে।
* Accessibility উন্নত করে।
* Server-এ নির্দিষ্ট তথ্য পাঠাতে সাহায্য করে।
* আধুনিক Web Application তৈরিতে গুরুত্বপূর্ণ ভূমিকা পালন করে।

---

### বাস্তব উদাহরণ

ধরুন একটি **লিফটের Control Panel** কল্পনা করুন।

| Attribute  | বাস্তব উদাহরণ                               |
| ---------- | ------------------------------------------- |
| `type`     | কোন Button কী কাজ করবে (Open, Close, Alarm) |
| `disabled` | নষ্ট Button, যা চাপা যায় না                |
| `name`     | Button-এর পরিচয়                            |
| `value`    | Button চাপলে কোন নির্দেশনা পাঠানো হবে       |

যেমন একটি লিফটের প্রতিটি Button-এর নির্দিষ্ট কাজ থাকে, ঠিক তেমনি Button Attribute Browser-কে জানায় একটি Button কীভাবে কাজ করবে।

---

### Best Practice

* সবসময় `type` Attribute লিখুন।
* শুধুমাত্র প্রয়োজন হলে `disabled` ব্যবহার করুন।
* অর্থপূর্ণ `name` ব্যবহার করুন।
* Server-side Processing-এর জন্য `value` ব্যবহার করুন।
* Form Button এবং সাধারণ Button আলাদা রাখুন।

---

### সাধারণ ভুল (Common Mistakes)

❌ `type` না লেখা

```html
<button>
    Save
</button>
```

✔ সঠিক

```html
<button type="button">
    Save
</button>
```

---

❌ সব Button-এ `submit` ব্যবহার করা

```html
<button type="submit">
    Open Menu
</button>
```

✔ সঠিক

```html
<button type="button">
    Open Menu
</button>
```

---

❌ অপ্রয়োজনীয়ভাবে `disabled` ব্যবহার করা

```html
<button disabled>
    Submit
</button>
```

✔ শুধুমাত্র প্রয়োজন হলে `disabled` ব্যবহার করুন।

---

### সারসংক্ষেপ

Button Attributes হলো `<button>` Element-এর গুরুত্বপূর্ণ Attribute, যা Button-এর ধরন, কার্যক্রম এবং Form-এর সাথে এর সম্পর্ক নিয়ন্ত্রণ করে। এই অধ্যায়ে **৪টি Button Attribute** আলোচনা করা হয়েছে—`type`, `disabled`, `name` এবং `value`। এগুলোর সঠিক ব্যবহার Button-কে আরও কার্যকর, ব্যবহারকারী-বান্ধব এবং Form-এর সাথে সমন্বিত করে। আধুনিক HTML Form এবং Interactive Website তৈরির জন্য Button Attribute সম্পর্কে পরিষ্কার ধারণা থাকা অত্যন্ত গুরুত্বপূর্ণ।






## 13. Select Attributes

Select Attributes হলো এমন কিছু HTML Attribute, যা মূলত `<select>` Element-এর সাথে ব্যবহার করা হয়। এগুলোর মাধ্যমে Drop-down List-এর আচরণ (Behavior), একাধিক Option নির্বাচন করার সুবিধা, দৃশ্যমান Option-এর সংখ্যা, Form Validation এবং Form Data নিয়ন্ত্রণ করা যায়।

`<select>` Element ব্যবহার করে ব্যবহারকারীকে পূর্বনির্ধারিত (Predefined) Option-এর তালিকা থেকে একটি বা একাধিক Option নির্বাচন করার সুযোগ দেওয়া হয়। Select Attribute-এর সঠিক ব্যবহার **User Experience (UX)**, **Accessibility**, **Form Validation** এবং **Data Collection** উন্নত করে।

এই অধ্যায়ে আমরা **৫টি Select Attribute** সম্পর্কে জানব।

---

### Select Attribute কী?

Select Attribute হলো এমন Attribute, যা `<select>` Element-এর কার্যপ্রণালী এবং ব্যবহারকারীর নির্বাচন (Selection) নিয়ন্ত্রণ করে।

উদাহরণস্বরূপ—

* `multiple` → একাধিক Option নির্বাচন করার সুযোগ দেয়।
* `size` → একসাথে কতটি Option দেখা যাবে তা নির্ধারণ করে।
* `disabled` → Select Box নিষ্ক্রিয় করে।
* `required` → নির্বাচন বাধ্যতামূলক করে।
* `name` → Form Submit-এর সময় Field-এর নাম নির্ধারণ করে।

---

### Select Attributes-এর মৌলিক কাঠামো

```html id="pq8k3m"
<!DOCTYPE html>
<html>

<head>
    <title>Select Attributes</title>
</head>

<body>

    <form>

        <select
            name="country"
            required>

            <option>Bangladesh</option>
            <option>India</option>
            <option>Nepal</option>

        </select>

    </form>

</body>

</html>
```

উপরের Code-এ `<select>` Element-এর সাথে `name` এবং `required` Attribute ব্যবহার করা হয়েছে।

---

### Select Attributes-এর তালিকা

| নং | Attribute  | কাজ                                           |
| -- | ---------- | --------------------------------------------- |
| 94 | `multiple` | একাধিক Option নির্বাচন করতে দেয়              |
| 95 | `size=""`  | একসাথে কতটি Option দেখা যাবে তা নির্ধারণ করে  |
| 96 | `disabled` | Select Box নিষ্ক্রিয় করে                     |
| 97 | `required` | Option নির্বাচন বাধ্যতামূলক করে               |
| 98 | `name=""`  | Form Submit-এর সময় Field-এর নাম নির্ধারণ করে |

---

### Select Attributes Structure

```text id="n0rxl8"
<select>
       │
       ├── multiple
       ├── size
       ├── disabled
       ├── required
       └── name
```

---

### প্রতিটি Attribute-এর সংক্ষিপ্ত পরিচয়

#### 94. `multiple`

* ব্যবহারকারীকে একাধিক Option নির্বাচন করার সুযোগ দেয়।
* সাধারণত `Ctrl` (Windows) অথবা `Cmd` (Mac)-এর সাহায্যে একাধিক Option নির্বাচন করা হয়।
* এটি একটি **Boolean Attribute**।

**উদাহরণ**

```html id="s8r6az"
<select multiple>

    <option>HTML</option>
    <option>CSS</option>
    <option>JavaScript</option>

</select>
```

---

#### 95. `size=""`

* একসাথে কতটি Option দৃশ্যমান থাকবে তা নির্ধারণ করে।
* Default মান সাধারণত `1`।

**উদাহরণ**

```html id="0z7epn"
<select size="4">

    <option>HTML</option>
    <option>CSS</option>
    <option>JavaScript</option>
    <option>React</option>

</select>
```

---

#### 96. `disabled`

* Select Box-কে নিষ্ক্রিয় (Disabled) করে।
* Disabled অবস্থায় ব্যবহারকারী কোনো Option নির্বাচন করতে পারে না।
* এটি একটি **Boolean Attribute**।

**উদাহরণ**

```html id="97m7vg"
<select disabled>

    <option>Coming Soon</option>

</select>
```

---

#### 97. `required`

* Form Submit করার আগে একটি Option নির্বাচন করা বাধ্যতামূলক করে।
* যদি কোনো Option নির্বাচন না করা হয়, তাহলে Browser Validation Error দেখায়।
* এটি একটি **Boolean Attribute**।

**উদাহরণ**

```html id="7fy9u9"
<select required>

    <option value="">
        Select Country
    </option>

    <option>Bangladesh</option>

</select>
```

---

#### 98. `name=""`

* Form Submit করার সময় Select Field-এর নাম নির্ধারণ করে।
* Server এই Name ব্যবহার করে নির্বাচিত Value শনাক্ত করে।

**উদাহরণ**

```html id="7tdz0x"
<select name="country">

    <option>Bangladesh</option>

</select>
```

---

### Browser কীভাবে Select Attributes পড়ে?

Browser সাধারণত নিচের ধাপগুলো অনুসরণ করে—

```text id="nnvj3t"
Read <select>
      │
      ▼
Read Select Attributes
      │
      ▼
Display Options
      │
      ▼
Wait for User Selection
      │
      ▼
Submit Selected Value
```

Browser প্রথমে `<select>` Element পড়ে, তারপর Attribute অনুযায়ী Select Box তৈরি করে এবং ব্যবহারকারীর নির্বাচিত তথ্য Form-এর মাধ্যমে পাঠায়।

---

### Select Attributes-এর গুরুত্ব

* ব্যবহারকারীকে নির্দিষ্ট Option থেকে নির্বাচন করতে দেয়।
* Form Data আরও সঠিকভাবে সংগ্রহ করা যায়।
* Validation সহজ হয়।
* User Experience উন্নত হয়।
* Data Entry Error কমায়।
* Accessibility উন্নত করে।
* Professional Form তৈরিতে গুরুত্বপূর্ণ ভূমিকা পালন করে।

---

### বাস্তব উদাহরণ

ধরুন একটি **Restaurant Menu** কল্পনা করুন।

| Attribute  | বাস্তব উদাহরণ                       |
| ---------- | ----------------------------------- |
| `multiple` | একাধিক খাবার নির্বাচন করা           |
| `size`     | একসাথে কয়টি Menu Item দেখা যাবে    |
| `disabled` | আপাতত অর্ডার করা যাবে না            |
| `required` | একটি খাবার অবশ্যই নির্বাচন করতে হবে |
| `name`     | অর্ডারের ক্যাটাগরির নাম             |

যেমন একটি Restaurant Menu থেকে নির্দিষ্ট খাবার নির্বাচন করা হয়, ঠিক তেমনি `<select>` Element ব্যবহারকারীকে পূর্বনির্ধারিত Option থেকে নির্বাচন করার সুযোগ দেয়।

---

### Best Practice

* সবসময় অর্থপূর্ণ `name` ব্যবহার করুন।
* প্রয়োজন হলে `required` ব্যবহার করুন।
* শুধুমাত্র প্রয়োজন হলে `multiple` ব্যবহার করুন।
* অনেক Option থাকলে `size` ব্যবহার করুন।
* Disabled Option-এর পরিবর্তে পরিষ্কার নির্দেশনা দিন।
* প্রথম Option হিসেবে `"Select an option"` ধরনের Placeholder ব্যবহার করা ভালো।

---

### সাধারণ ভুল (Common Mistakes)

❌ `name` ব্যবহার না করা

```html id="x4x4jh"
<select>

    <option>HTML</option>

</select>
```

✔ সঠিক

```html id="c5hn0j"
<select name="course">

    <option>HTML</option>

</select>
```

---

❌ `required` ব্যবহার করেও Placeholder না দেওয়া

```html id="lhjk9m"
<select required>

    <option>Bangladesh</option>

</select>
```

✔ সঠিক

```html id="0xezn4"
<select
    name="country"
    required>

    <option value="">
        Select Country
    </option>

    <option>Bangladesh</option>

</select>
```

---

❌ অপ্রয়োজনীয়ভাবে `multiple` ব্যবহার করা

```html id="2l2k8k"
<select multiple>

    <option>HTML</option>

</select>
```

✔ শুধুমাত্র একাধিক নির্বাচন প্রয়োজন হলে `multiple` ব্যবহার করুন।

---

### সারসংক্ষেপ

Select Attributes হলো `<select>` Element-এর গুরুত্বপূর্ণ Attribute, যা Drop-down List-এর আচরণ, নির্বাচন পদ্ধতি এবং Form Data নিয়ন্ত্রণ করে। এই অধ্যায়ে **৫টি Select Attribute** আলোচনা করা হয়েছে—`multiple`, `size`, `disabled`, `required` এবং `name`। এগুলোর সঠিক ব্যবহার Form-কে আরও কার্যকর, ব্যবহারকারী-বান্ধব এবং নির্ভুল করে তোলে। আধুনিক HTML Form তৈরির জন্য Select Attribute সম্পর্কে পরিষ্কার ধারণা থাকা অত্যন্ত গুরুত্বপূর্ণ।






## 14. Option Attributes

Option Attributes হলো এমন কিছু HTML Attribute, যা মূলত `<option>` Element-এর সাথে ব্যবহার করা হয়। এগুলোর মাধ্যমে একটি Option-এর প্রকৃত মান (Value), ডিফল্টভাবে নির্বাচিত (Selected) অবস্থা এবং Option ব্যবহারযোগ্য (Enabled) বা অকার্যকর (Disabled) হবে কি না তা নির্ধারণ করা যায়।

`<option>` Element সাধারণত `<select>` এবং `<datalist>` Element-এর ভিতরে ব্যবহৃত হয়। Option Attribute-এর সঠিক ব্যবহার **Form Data Collection**, **User Experience (UX)**, **Accessibility** এবং **Form Validation** উন্নত করে।

এই অধ্যায়ে আমরা **৩টি Option Attribute** সম্পর্কে জানব।

---

### Option Attribute কী?

Option Attribute হলো এমন Attribute, যা `<option>` Element-এর মান (Value), নির্বাচন (Selection) এবং ব্যবহারযোগ্যতা (Availability) নিয়ন্ত্রণ করে।

উদাহরণস্বরূপ—

* `value` → Form Submit-এর সময় কোন মান পাঠানো হবে তা নির্ধারণ করে।
* `selected` → Option-কে ডিফল্টভাবে নির্বাচিত করে।
* `disabled` → Option নির্বাচন করা বন্ধ করে।

---

### Option Attributes-এর মৌলিক কাঠামো

```html id="q6w2vk"
<!DOCTYPE html>
<html>

<head>
    <title>Option Attributes</title>
</head>

<body>

    <form>

        <select name="country">

            <option value="">
                Select Country
            </option>

            <option
                value="bd"
                selected>

                Bangladesh

            </option>

            <option value="in">
                India
            </option>

        </select>

    </form>

</body>

</html>
```

উপরের Code-এ `<option>` Element-এর সাথে `value` এবং `selected` Attribute ব্যবহার করা হয়েছে।

---

### Option Attributes-এর তালিকা

| নং  | Attribute  | কাজ                                         |
| --- | ---------- | ------------------------------------------- |
| 99  | `value=""` | Form Submit-এর সময় পাঠানো মান নির্ধারণ করে |
| 100 | `selected` | Option-কে ডিফল্টভাবে নির্বাচিত করে          |
| 101 | `disabled` | Option নির্বাচন করা বন্ধ করে                |

---

### Option Attributes Structure

```text id="0yl12x"
<option>
       │
       ├── value
       ├── selected
       └── disabled
```

---

### প্রতিটি Attribute-এর সংক্ষিপ্ত পরিচয়

#### 99. `value=""`

* Form Submit করার সময় Server-এ কোন মান (Value) পাঠানো হবে তা নির্ধারণ করে।
* Display Text এবং Submitted Value আলাদা হতে পারে।

**উদাহরণ**

```html id="zmhtzl"
<option value="bd">
    Bangladesh
</option>
```

যদি ব্যবহারকারী **Bangladesh** নির্বাচন করে, তাহলে Server-এ `bd` পাঠানো হবে।

---

#### 100. `selected`

* Page Load হওয়ার সময় Option-কে ডিফল্টভাবে নির্বাচন করে।
* সাধারণত একটি `<select>`-এ একটি Option-ই `selected` থাকে।
* `multiple` Select হলে একাধিক `selected` ব্যবহার করা যায়।
* এটি একটি **Boolean Attribute**।

**উদাহরণ**

```html id="5r66fr"
<option selected>
    HTML
</option>
```

---

#### 101. `disabled`

* Option-কে নিষ্ক্রিয় (Disabled) করে।
* Disabled Option দেখা যায়, কিন্তু নির্বাচন করা যায় না।
* সাধারণত Placeholder বা অস্থায়ীভাবে অনুপলব্ধ Option-এর জন্য ব্যবহৃত হয়।
* এটি একটি **Boolean Attribute**।

**উদাহরণ**

```html id="ch1y6z"
<option disabled>
    Coming Soon
</option>
```

---

### Browser কীভাবে Option Attributes পড়ে?

Browser সাধারণত নিচের ধাপগুলো অনুসরণ করে—

```text id="vjlwm4"
Read <select>
      │
      ▼
Read <option>
      │
      ▼
Read Option Attributes
      │
      ▼
Display Options
      │
      ▼
Submit Selected Value
```

Browser প্রথমে `<select>` Element পড়ে, তারপর প্রতিটি `<option>`-এর Attribute অনুযায়ী Drop-down List তৈরি করে এবং নির্বাচিত Value Form-এর মাধ্যমে পাঠায়।

---

### Option Attributes-এর গুরুত্ব

* Form-এর সঠিক Value Server-এ পাঠাতে সাহায্য করে।
* Default Selection নির্ধারণ করা যায়।
* অনুপলব্ধ Option নিষ্ক্রিয় করা যায়।
* User Experience উন্নত করে।
* Form Validation সহজ করে।
* Data Processing আরও নির্ভুল হয়।
* Professional Form তৈরিতে গুরুত্বপূর্ণ ভূমিকা পালন করে।

---

### বাস্তব উদাহরণ

ধরুন একটি **Restaurant Menu** কল্পনা করুন।

| Attribute  | বাস্তব উদাহরণ                         |
| ---------- | ------------------------------------- |
| `value`    | খাবারের কোড নম্বর                     |
| `selected` | Chef-এর Recommended খাবার             |
| `disabled` | বর্তমানে অর্ডার করা যাবে না এমন খাবার |

যেমন একটি Restaurant Menu-তে কিছু খাবার ডিফল্টভাবে সুপারিশ করা হতে পারে এবং কিছু খাবার সাময়িকভাবে পাওয়া নাও যেতে পারে, ঠিক তেমনি Option Attribute `<option>` Element-এর আচরণ নিয়ন্ত্রণ করে।

---

### Best Practice

* সবসময় অর্থপূর্ণ `value` ব্যবহার করুন।
* শুধুমাত্র একটি Default Option-এর জন্য `selected` ব্যবহার করুন (যদি `multiple` না থাকে)।
* Placeholder Option-এর জন্য `disabled` ব্যবহার করতে পারেন।
* Display Text এবং `value`-এর মধ্যে যৌক্তিক সম্পর্ক রাখুন।
* Server-side Processing-এর সুবিধার জন্য ছোট ও অর্থপূর্ণ Value ব্যবহার করুন।

---

### সাধারণ ভুল (Common Mistakes)

❌ `value` ব্যবহার না করা

```html id="8iqlxv"
<option>
    Bangladesh
</option>
```

✔ সঠিক

```html id="e4h3pi"
<option value="bd">
    Bangladesh
</option>
```

---

❌ একই Select-এ একাধিক `selected` ব্যবহার করা

```html id="mr50ii"
<select>

    <option selected>HTML</option>
    <option selected>CSS</option>

</select>
```

✔ সঠিক

```html id="w2cbfx"
<select>

    <option selected>HTML</option>
    <option>CSS</option>

</select>
```

---

❌ Placeholder-এ `disabled` ব্যবহার না করা

```html id="dbphzn"
<option>
    Select Country
</option>
```

✔ সঠিক

```html id="ezbl71"
<option
    value=""
    selected
    disabled>

    Select Country

</option>
```

---

### সারসংক্ষেপ

Option Attributes হলো `<option>` Element-এর গুরুত্বপূর্ণ Attribute, যা Drop-down List-এর প্রতিটি Option-এর মান, নির্বাচন এবং ব্যবহারযোগ্যতা নিয়ন্ত্রণ করে। এই অধ্যায়ে **৩টি Option Attribute** আলোচনা করা হয়েছে—`value`, `selected` এবং `disabled`। এগুলোর সঠিক ব্যবহার Form-কে আরও নির্ভুল, ব্যবহারকারী-বান্ধব এবং কার্যকর করে তোলে। আধুনিক HTML Form তৈরির জন্য Option Attribute সম্পর্কে পরিষ্কার ধারণা থাকা অত্যন্ত গুরুত্বপূর্ণ।






## 15. Misc Attributes

Misc Attributes (Miscellaneous Attributes) হলো এমন কিছু HTML Attribute, যা বিভিন্ন HTML Element-এর অতিরিক্ত কার্যক্ষমতা (Extra Functionality), Accessibility, Keyboard Shortcut, বানান যাচাই (Spell Check), ভাষা অনুবাদ (Translation), স্বয়ংক্রিয় Focus এবং Form-এর সাথে সংযোগ (Association) নিয়ন্ত্রণ করতে ব্যবহৃত হয়।

এগুলো নির্দিষ্ট একটি Tag-এর জন্য নয়; বরং প্রয়োজন অনুযায়ী বিভিন্ন HTML Element-এর সাথে ব্যবহার করা যায়। আধুনিক Website এবং Web Application-এ User Experience (UX), Accessibility এবং Productivity উন্নত করতে এই Attribute-গুলোর গুরুত্বপূর্ণ ভূমিকা রয়েছে।

এই অধ্যায়ে আমরা **৬টি Misc Attribute** সম্পর্কে জানব।

---

### Misc Attribute কী?

Misc Attribute হলো এমন Attribute, যা HTML Element-এ অতিরিক্ত বৈশিষ্ট্য (Additional Features) যোগ করে এবং Browser-এর বিভিন্ন আচরণ নিয়ন্ত্রণ করে।

উদাহরণস্বরূপ—

* `accesskey` → Keyboard Shortcut নির্ধারণ করে।
* `spellcheck` → বানান যাচাই চালু বা বন্ধ করে।
* `translate` → Content অনুবাদ করা যাবে কি না নির্ধারণ করে।
* `contextmenu` → Custom Context Menu নির্ধারণ করে।
* `autofocus` → Page Load হওয়ার সাথে সাথে Focus দেয়।
* `form` → Element-কে নির্দিষ্ট Form-এর সাথে যুক্ত করে।

---

### Misc Attributes-এর মৌলিক কাঠামো

```html
<!DOCTYPE html>
<html>

<head>
    <title>Misc Attributes</title>
</head>

<body>

    <form id="loginForm">

        <input
            type="text"
            name="username"
            autofocus
            spellcheck="false">

    </form>

</body>

</html>
```

উপরের Code-এ `autofocus` এবং `spellcheck` Attribute ব্যবহার করা হয়েছে।

---

### Misc Attributes-এর তালিকা

| নং  | Attribute                 | কাজ                                            |
| --- | ------------------------- | ---------------------------------------------- |
| 102 | `accesskey=""`            | Keyboard Shortcut নির্ধারণ করে                 |
| 103 | `spellcheck="true/false"` | বানান যাচাই চালু বা বন্ধ করে                   |
| 104 | `translate="yes/no"`      | Browser Content অনুবাদ করবে কি না নির্ধারণ করে |
| 105 | `contextmenu=""`          | Custom Context Menu নির্ধারণ করে               |
| 106 | `autofocus`               | Page Load হওয়ার সাথে সাথে Focus দেয়          |
| 107 | `form=""`                 | Element-কে নির্দিষ্ট Form-এর সাথে যুক্ত করে    |

---

### Misc Attributes Structure

```text
HTML Element
      │
      ├── accesskey
      ├── spellcheck
      ├── translate
      ├── contextmenu
      ├── autofocus
      └── form
```

---

### প্রতিটি Attribute-এর সংক্ষিপ্ত পরিচয়

#### 102. `accesskey=""`

* Element-এর জন্য একটি Keyboard Shortcut নির্ধারণ করে।
* Browser ও Operating System অনুযায়ী Shortcut Key ভিন্ন হতে পারে।
* Accessibility উন্নত করতে ব্যবহৃত হয়।

**উদাহরণ**

```html
<button accesskey="s">
    Save
</button>
```

---

#### 103. `spellcheck="true/false"`

* Text-এর বানান (Spelling) Browser যাচাই করবে কি না নির্ধারণ করে।
* সাধারণত `<input>` এবং `<textarea>` Element-এর সাথে ব্যবহৃত হয়।

সম্ভাব্য Value—

| Value   | কাজ              |
| ------- | ---------------- |
| `true`  | বানান যাচাই চালু |
| `false` | বানান যাচাই বন্ধ |

**উদাহরণ**

```html
<textarea spellcheck="true">

</textarea>
```

---

#### 104. `translate="yes/no"`

* Browser বা Translation Tool Content অনুবাদ করবে কি না নির্ধারণ করে।

সম্ভাব্য Value—

| Value | কাজ                |
| ----- | ------------------ |
| `yes` | অনুবাদ করা যাবে    |
| `no`  | অনুবাদ করা যাবে না |

**উদাহরণ**

```html
<p translate="no">
    OpenAI
</p>
```

---

#### 105. `contextmenu=""`

* Element-এর জন্য Custom Context Menu নির্ধারণ করতে ব্যবহৃত হতো।
* আধুনিক Browser-এ এই Attribute আর সমর্থিত (Supported) নয়।
* বর্তমানে JavaScript ব্যবহার করে Custom Context Menu তৈরি করা হয়।

**উদাহরণ**

```html
<div contextmenu="menu1">

    Right Click Here

</div>
```

---

#### 106. `autofocus`

* Page Load হওয়ার সাথে সাথে নির্দিষ্ট Input Element-এ Cursor বা Focus নিয়ে যায়।
* সাধারণত Login Form, Search Box এবং Registration Form-এ ব্যবহৃত হয়।
* এটি একটি **Boolean Attribute**।

**উদাহরণ**

```html
<input
    type="text"
    autofocus>
```

---

#### 107. `form=""`

* Element-কে নির্দিষ্ট Form-এর সাথে যুক্ত করে।
* Element Form-এর বাইরে থাকলেও Form Submit-এর সময় এর Data পাঠানো যায়।
* `form` Attribute-এর Value হিসেবে Form-এর `id` ব্যবহার করা হয়।

**উদাহরণ**

```html
<form id="myForm">

</form>

<input
    type="text"
    form="myForm">
```

---

### Browser কীভাবে Misc Attributes পড়ে?

Browser সাধারণত নিচের ধাপগুলো অনুসরণ করে—

```text
Read HTML Element
        │
        ▼
Read Misc Attributes
        │
        ▼
Apply Browser Behavior
        │
        ▼
Render Web Page
```

Browser প্রতিটি Misc Attribute বিশ্লেষণ করে এবং সেই অনুযায়ী Element-এর আচরণ পরিবর্তন করে।

---

### Misc Attributes-এর গুরুত্ব

* Keyboard Shortcut যোগ করা যায়।
* বানান যাচাই নিয়ন্ত্রণ করা যায়।
* অনুবাদ নিয়ন্ত্রণ করা যায়।
* Page Load-এর সময় স্বয়ংক্রিয়ভাবে Focus দেওয়া যায়।
* Form-এর বাইরে থাকা Element-কে Form-এর সাথে যুক্ত করা যায়।
* Accessibility এবং User Experience উন্নত হয়।
* Professional Web Application তৈরিতে গুরুত্বপূর্ণ ভূমিকা পালন করে।

---

### বাস্তব উদাহরণ

ধরুন একটি **অফিস ডেস্ক** কল্পনা করুন।

| Attribute     | বাস্তব উদাহরণ                                        |
| ------------- | ---------------------------------------------------- |
| `accesskey`   | দ্রুত কাজের Shortcut Key                             |
| `spellcheck`  | বানান পরীক্ষার সফটওয়্যার                            |
| `translate`   | অনুবাদক (Translator)                                 |
| `contextmenu` | Right Click Menu                                     |
| `autofocus`   | কাজ শুরুতেই নির্দিষ্ট ফাইলে Cursor থাকা              |
| `form`        | অন্য টেবিলে থাকা ফাইলকে একই প্রকল্পের সাথে যুক্ত করা |

যেমন একটি অফিসে বিভিন্ন অতিরিক্ত সুবিধা কাজকে সহজ করে, ঠিক তেমনি Misc Attributes HTML Element-এ অতিরিক্ত কার্যক্ষমতা যোগ করে।

---

### Best Practice

* Accessibility-এর জন্য প্রয়োজন হলে `accesskey` ব্যবহার করুন।
* Text Input-এর ক্ষেত্রে প্রয়োজন অনুযায়ী `spellcheck` ব্যবহার করুন।
* Brand Name বা Code-এর জন্য `translate="no"` ব্যবহার করা যেতে পারে।
* শুধুমাত্র একটি Element-এ `autofocus` ব্যবহার করুন।
* `form` Attribute ব্যবহার করলে Form-এর `id` সঠিকভাবে লিখুন।
* `contextmenu` Attribute-এর পরিবর্তে আধুনিক JavaScript পদ্ধতি ব্যবহার করুন।

---

### সাধারণ ভুল (Common Mistakes)

❌ একাধিক Element-এ `autofocus` ব্যবহার করা

```html
<input autofocus>

<input autofocus>
```

✔ সঠিক

```html
<input autofocus>

<input>
```

---

❌ ভুল Form ID ব্যবহার করা

```html
<form id="loginForm">

</form>

<input form="login">
```

✔ সঠিক

```html
<form id="loginForm">

</form>

<input form="loginForm">
```

---

❌ `spellcheck`-এর ভুল Value ব্যবহার করা

```html
<textarea spellcheck="yes">

</textarea>
```

✔ সঠিক

```html
<textarea spellcheck="true">

</textarea>
```

---

### সারসংক্ষেপ

Misc Attributes হলো HTML-এর অতিরিক্ত (Miscellaneous) Attribute, যা বিভিন্ন HTML Element-এর আচরণ, Accessibility, Keyboard Shortcut, Spell Checking, Translation, Focus এবং Form-এর সাথে সংযোগ নিয়ন্ত্রণ করে। এই অধ্যায়ে **৬টি Misc Attribute** আলোচনা করা হয়েছে—`accesskey`, `spellcheck`, `translate`, `contextmenu`, `autofocus` এবং `form`। এগুলোর সঠিক ব্যবহার Website-কে আরও কার্যকর, ব্যবহারকারী-বান্ধব এবং Professional করে তোলে। আধুনিক HTML Development-এ Misc Attributes সম্পর্কে পরিষ্কার ধারণা থাকা অত্যন্ত গুরুত্বপূর্ণ।