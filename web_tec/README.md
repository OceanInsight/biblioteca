## CSS Tricks

Looks like a guy publishing his technical stuff.

https://css-tricks.com/



## CSS and HTML

The Mozila website has a good set of examples showing HTML and CSS linked

### Main Element

The **`<main>`** HTML element represents the dominant content of the **`<body>`** of a document.

https://developer.mozilla.org/en-US/docs/Web/HTML/Element/main

```html
<header>Gecko facts</header>

<main>
    <p>Geckos are a group of usually small...</p>

    <p>Many species of gecko ...</p>
</main>
```

Then the CSS code is below:

```css
header {
    font: bold calc(0.025 * (100vw)) Arial, sans-serif;
}
```

### Division Content element

The **`<div>`** container does not represent anything. Instead it is used to group content so it can be easily styled using the the **class** or **id** attributes.

https://developer.mozilla.org/en-US/docs/Web/HTML/Element/div

Below is the HTML code

```html
<div class="warning">
    <img src="/media/examples/leopard.jpg"
         alt="An intimidating leopard.">
    <p>Beware of the leopard</p>
</div>
```

The CSS code is below

```css
.warning {
    border: 10px ridge #f00;
    background-color: #ff0;
    padding: 0.5rem;
    display: flex;
    flex-direction: column;
}

.warning img {
    width: 100%;
}

.warning p {
    font: small-caps bold 1.2rem sans-serif;
    text-align: center;
}
```

### Paragraph Element

The **`<p>`** HTML element represents a paragraph.

https://developer.mozilla.org/en-US/docs/Web/HTML/Element/p

### Aside Element

The **`<aside>`** element represents a portion of a document whose content is only indirectly related to the document's main content. Asides are frequently presented as sidebars or call-out boxes.

https://developer.mozilla.org/en-US/docs/Web/HTML/Element/aside

```css
aside {
    width: 40%;
    padding-left: 0.5rem;
    margin-left: 0.5rem;
    float: right;
    box-shadow: inset 5px 0 5px -5px #29627e;
    font-style: italic;
    color: #29627e;
}

aside > p {
    margin: 0.5rem;
}

p {
    font-family: 'Fira Sans', sans-serif;
}
```

Notice the **aside > p** notation.

Here is the HTML, the **`<p>`** tag is for **paragraph**.

```html
<p>Salamanders are ....</p>

<aside>
    <p>The Rough-skinned Newt defends itself with a deadly neurotoxin.</p>
</aside>

<p>Several species of salamander...</p>
```

