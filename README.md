# web-application-essentialss

### 1\. Reset CSS

A reset CSS aims to reduce browser inconsistencies by resetting styles to default values. This ensures a consistent baseline for styling.

```css
/* Reset CSS */
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}
```

### 2\. Body Styles

Set default styles for the body element to define basic typography, background, and spacing.


```css
/* Body Styles */
body {
    font-family: -apple-system, BlinkMacSystemFont, "avenir next", avenir, "helvetica neue", helvetica, ubuntu, roboto, noto, "segoe ui", arial, sans-serif;
    font-size: 16px;
    line-height: 1.6;
    background-color: #f5f5f5;
    color: #333;
    margin: 0;
    padding: 0;
}
```

### 3\. Links

Define styles for hyperlinks to ensure they are distinguishable and user-friendly.


```css
/* Links */
a {
    color: #007bff;
    text-decoration: none;
}

a:hover {
    text-decoration: underline;
}
```

### 4\. Headers

Styles for headings to establish hierarchy and readability.


```css
/* Headers */
h1, h2, h3, h4, h5, h6 {
    margin: 10px 0;
    font-weight: bold;
}

h1 {
    font-size: 32px;
}

h2 {
    font-size: 28px;
}

h3 {
    font-size: 24px;
}

h4 {
    font-size: 20px;
}

h5 {
    font-size: 18px;
}

h6 {
    font-size: 16px;
}
```

### 5\. Containers

Styles for containers to provide structure and spacing.


```css
/* Containers */
.container {
    width: 80%;
    margin: 0 auto;
}

/* Example usage: <div class="container">Content</div> */
```

### 6\. Images

```css
/* Responsive Images */
img {
    max-width: 100%;
    height: auto;
}
```

### Conclusion

By incorporating these default CSS styles into your web applications, you can ensure a consistent and user-friendly design across different projects. Feel free to customize these styles further to suit your specific requirements.
