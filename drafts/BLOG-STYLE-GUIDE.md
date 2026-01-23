# Blog Post Style Guide

This guide documents all formatting elements for consistent blog posts.

---

## 1. Numbered Section Points

Use for main teaching points (1, 2, 3...). Number and title are centered.

```html
<div class="sermon-point">
    <div class="point-header">
        <div class="point-number">1</div>
        <h3 class="point-title">Your Point Title Here</h3>
    </div>
    <div class="point-content">
        <p>Your content here...</p>
    </div>
</div>
```

---

## 2. Scripture Blocks

Use for Bible verses. Purple left border with dark background.

```html
<div class="scripture-block">
    <p>"Scripture text goes here..."</p>
    <cite>— Book Chapter:Verse (Translation)</cite>
</div>
```

For multiple paragraphs in one scripture block:
```html
<div class="scripture-block">
    <p>"First part of scripture..."</p>
    <p>"Second part of scripture..."</p>
    <cite>— John 1:1-5, 14 (NIV)</cite>
</div>
```

---

## 3. Quote Blocks

Use for non-scripture quotes (authors, philosophers, etc.). Gradient background.

```html
<div class="quote-block">
    <p>"Quote text goes here..."</p>
    <cite>— Author Name, Source</cite>
</div>
```

---

## 4. Series Info Box

Use at the beginning of a post to show series overview.

```html
<div class="series-info">
    <h4>Series Overview: Series Name</h4>
    <ul>
        <li><strong>Part 1:</strong> Description</li>
        <li><strong>Part 2:</strong> Description</li>
        <li><strong>Part 3:</strong> Description</li>
    </ul>
</div>
```

---

## 5. Application Section (Questions)

Use at the end of posts for reflection questions. Has arrow icons.

```html
<div class="application-section">
    <h3 class="application-title">Questions to Consider</h3>
    <ul class="application-list">
        <li>First question?</li>
        <li>Second question?</li>
        <li>Third question or call to action.</li>
    </ul>
</div>
```

---

## 6. Headings

### Main Section Heading (h2)
Use for major topic shifts within the article.

```html
<h2>Main Section Title</h2>
```

### Sub-Section Heading (h3)
Use for subtopics within a section.

```html
<h3>Sub-Section Title</h3>
```

---

## 7. Text Formatting

### Bold Text
Use for emphasis or key phrases.

```html
<strong>Important text here</strong>
```

### Italic/Highlight Text
Use for terms, titles, or subtle emphasis. Appears in purple.

```html
<em>Emphasized text</em>
```

### Bullet Lists
```html
<ul>
    <li>First item</li>
    <li>Second item</li>
    <li>Third item</li>
</ul>
```

### Numbered Lists
```html
<ol>
    <li>First item</li>
    <li>Second item</li>
    <li>Third item</li>
</ol>
```

---

## 8. Regular Paragraphs

Just use standard paragraph tags.

```html
<p>Your paragraph text here. Use <strong>bold</strong> for emphasis and <em>italics</em> for highlighted terms.</p>
```

---

## Post Structure Template

Recommended order:

1. **Series Info** (if part of a series)
2. **Introduction** (1-2 paragraphs)
3. **Main Heading** (h2) - optional
4. **Numbered Points** (sermon-point sections)
   - Scripture blocks as needed
   - Quote blocks as needed
   - Sub-headings (h3) within points
5. **Conclusion Heading** (h2)
6. **Closing paragraph**
7. **Application Section** (Questions to Consider)
8. **Final statement** (bold, impactful)

---

## Color Reference

- **Purple accent:** Used for scripture borders, category tags, emphasized text
- **Dark cards:** Used for scripture blocks, numbered points
- **Gradient:** Used for quote blocks, application sections
