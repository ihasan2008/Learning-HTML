i0.1 1.1 5.1 - {1} HTML
i0.1 1.1 5.1.1 - HTML Basics
i0.1 1.1 5.1.2 - HTML Document
i0.1 1.1 5.1.3 - HTML Element
i0.1 1.1 5.1.4 - HTML Tags
i0.1 1.1 5.1.5 - HTML Attributes
i0.1 1.1 5.1.6 - HTML Content
i0.1 1.1 5.1.7 - HTML Comments
i0.1 1.1 5.1.8 - Advanced HTML

-------------------------------------------

# > { 1 } HTML - Hyper Text Markup Language

1. HTML Basics

    1.1 What is HTML?
    1.2 HyperText কী?
    1.3 Markup Language কী?
    1.4 HTML এর কাজ কী?
    1.5 HTML Versions
    1.6 HTML File Extension
    1.7 HTML Editor
    1.8 HTML Browser
    1.9 HTML কীভাবে কাজ করে?
    1.10 Website তৈরিতে HTML এর ভূমিকা
    1.11 History of HTML
    1.12 Frontend এর 3টি প্রধান প্রযুক্তি
    1.13 HTML শেখার আগে যা জানা দরকার
    1.14 Static vs Dynamic Website
    1.15 HTML, CSS & JavaScript Relationship
    1.16 Frontend vs Backend
    1.17 Server & Database
    1.18 Next Learning Steps


2. HTML Document

    <!DOCTYPE html>
    <html>
        <head>
            <title>My Website</title>
        </head>
        <body>

        </body>
    </html>


3. HTML Element

    <tagname attribute="value">
        Content
    </tagname>


4. HTML Tags

    HTML Document Tags

    1 - <!DOCTYPE html>
    2 - <html></html>
    3 - <head></head>
    4 - <title></title>
    5 - <body></body>

    Metadata Tags

    6 - <meta>
    7 - <link>
    8 - <base>
    9 - <style></style>
    10 - <script></script>
    11 - <noscript></noscript>

    Heading Tags

    12 - <h1></h1>
    13 - <h2></h2>
    14 - <h3></h3>
    15 - <h4></h4>
    16 - <h5></h5>
    17 - <h6></h6>

    Basic Content Tags

    18 - <p></p>
    19 - <div></div>
    20 - <span></span>
    21 - <br>
    22 - <hr>
    23 - <pre></pre>

    Text Formatting Tags

    24 - <b></b>
    25 - <strong></strong>
    26 - <i></i>
    27 - <em></em>
    28 - <u></u>
    29 - <mark></mark>
    30 - <small></small>
    31 - <sub></sub>
    32 - <sup></sup>
    33 - <del></del>
    34 - <ins></ins>
    35 - <s></s>
    36 - <code></code>
    37 - <kbd></kbd>
    38 - <samp></samp>
    39 - <var></var>

    Quote & Reference Tags

    40 - <blockquote></blockquote>
    41 - <q></q>
    42 - <cite></cite>
    43 - <abbr></abbr>
    44 - <dfn></dfn>
    45 - <time></time>
    46 - <data></data>

    List Tags

    47 - <ul></ul>
    48 - <ol></ol>
    49 - <li></li>
    50 - <dl></dl>
    51 - <dt></dt>
    52 - <dd></dd>

    Link Tags

    53 - <a></a>

    Image Tags

    54 - <img>
    55 - <picture></picture>
    56 - <source>
    57 - <figure></figure>
    58 - <figcaption></figcaption>
    59 - <map></map>
    60 - <area>

    Audio & Video Tags

    61 - <audio></audio>
    62 - <video></video>
    63 - <source>
    64 - <track>

    Table Tags

    65 - <table></table>
    66 - <caption></caption>
    67 - <thead></thead>
    68 - <tbody></tbody>
    69 - <tfoot></tfoot>
    70 - <tr></tr>
    71 - <th></th>
    72 - <td></td>
    73 - <colgroup></colgroup>
    74 - <col>

    Form Tags

    75 - <form></form>
    76 - <label></label>
    77 - <input>
    78 - <textarea></textarea>
    79 - <button></button>
    80 - <select></select>
    81 - <option></option>
    82 - <optgroup></optgroup>
    83 - <fieldset></fieldset>
    84 - <legend></legend>
    85 - <datalist></datalist>
    86 - <output></output>
    87 - <meter></meter>
    88 - <progress></progress>

    Semantic Layout Tags

    89 - <header></header>
    90 - <nav></nav>
    91 - <main></main>
    92 - <section></section>
    93 - <article></article>
    94 - <aside></aside>
    95 - <footer></footer>
    96 - <address></address>

    Interactive Tags

    97 - <details></details>
    98 - <summary></summary>
    99 - <dialog></dialog>

    Embedded Content Tags

    100 -  <iframe></iframe>
    101 -  <embed>
    102 -  <object></object>
    103 -  <param>

    Graphics Tags

    104 - <canvas></canvas>
    105 - <svg></svg>

    Web Components

    106 - <template></template>
    107 - <slot></slot>

    Ruby Annotation Tags

    108 - <ruby></ruby>
    109 - <rt></rt>
    110 - <rp></rp>

    Deprecated Tags

    111 - <center></center>
    112 - <font></font>
    113 - <big></big>
    114 - <tt></tt>
    115 - <strike></strike>
    116 - <frameset></frameset>
    117 - <frame>
    118 - <noframes></noframes>
    119 - <acronym></acronym>
    120 - <applet></applet>
    121 - <dir></dir>


5. HTML Attributes

    Global Attributes

    1 - id=""
    2 - class=""
    3 - style=""
    4 - title=""
    5 - hidden
    6 - tabindex=""
    7 - lang=""
    8 - dir=""
    9 - draggable="true/false"
    10 - contenteditable="true/false"
    11 - data-* (custom attribute)

    Link / Anchor Attributes

    12 - href=""
    13 - target=""
    14 - rel=""
    15 - download
    16 - hreflang=""
    17 - type=""

    Image Attributes

    18 - src=""
    19 - alt=""
    20 - width=""
    21 - height=""
    22 - loading="lazy/eager"
    23 - srcset=""
    24 - sizes=""

    Form Attributes

    25 - action=""
    26 - method="GET/POST"
    27 - enctype=""
    28 - target=""
    29 - autocomplete="on/off"
    30 - novalidate
    31 - name=""
    32 - value=""
    33 - placeholder=""
    34 - required
    35 - disabled
    36 - readonly
    37 - min=""
    38 - max=""
    39 - step=""
    40 - maxlength=""
    41 - minlength=""
    42 - pattern=""
    43 - checked
    44 - multiple
    45 - accept=""
    46 - form=""

    Input Type Attributes

    47 - type="text"
    48 - type="password"
    49 - type="email"
    50 - type="number"
    51 - type="radio"
    52 - type="checkbox"
    53 - type="file"
    54 - type="date"
    55 - type="submit"
    56 - type="reset"
    57 - type="button"
    58 - type="range"
    59 - type="color"
    
    Script Attributes

    60 - src=""
    61 - async
    62 - defer
    63 - type="module"
    64 - crossorigin=""

    Table Attributes

    65 - colspan=""
    66 - rowspan=""
    67 - scope=""
    68 - headers=""

    Media Attributes (Audio / Video)

    69 - controls
    70 - autoplay
    71 - muted
    72 - loop
    73 - poster=""
    74 - preload="auto/metadata/none"
    75 - src=""

    Iframe Attributes

    76 - src=""
    77 - width=""
    78 - height=""
    79 - allow=""
    80 - sandbox=""
    81 - loading="lazy"
    82 - referrerpolicy=""

    Meta Attributes

    83 - charset=""
    84 - name=""
    85 - content=""
    86 - http-equiv=""

    List Attributes

    87 - start=""
    88 - reversed
    89 - value=""

    Button Attributes

    90 - type="button/submit/reset"
    91 - disabled
    92 - name=""
    93 - value=""

    Select Attributes

    94 - multiple
    95 - size=""
    96 - disabled
    97 - required
    98 - name=""

    Option Attributes

    99 - value=""
    100 - selected
    101 - disabled

    Misc Attributes

    102 - accesskey=""
    103 - spellcheck="true/false"
    104 - translate="yes/no"
    105 - contextmenu=""
    106 - autofocus
    107 - form=""


6. HTML Content

    6.1 HTML Content কী?
    6.2 HTML Content Types
    6.2.1 Text Content
    6.2.2 Image Content
    6.2.3 Link Content
    6.2.4 List Content
    6.2.5 Table Content
    6.2.6 Form Content
    6.2.7 Media Content (Audio / Video)
    6.2.8 Semantic Content
    6.2.9 Preformatted Content
    6.2.10 Code Content
    6.2.11 Quote Content
    6.2.12 Inline Content
    6.3 HTML Content Structure
    6.4 Empty Content Elements (Void Elements)
    6.5 HTML Content Rules
    6.6 Real Website Content Example


7. HTML Comments

    7.1 HTML Comment কী?
    7.2 HTML Comment Syntax
    7.3 Single Line Comment
    7.4 Multi Line Comment
    7.5 HTML Comment কীভাবে কাজ করে?
    7.6 Comment ব্যবহার কোথায় হয়?


8. Advanced HTML
@Practice HTML

-------------------------------------------
