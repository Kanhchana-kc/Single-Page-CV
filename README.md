

## ✅ A4 PAGE CSS (ADD THIS)

Put this **inside your `<style>` section**:

```css
@page {
    size: A4;
    margin: 20mm;
}

body {
    font-family: Arial, Helvetica, sans-serif;
    background: #f2f2f2;
    margin: 0;
    padding: 0;
}

.resume {
    width: 210mm;
    min-height: 297mm;
    margin: auto;
    background: #ffffff;
    padding: 20mm;
    box-sizing: border-box;
}
```

---

## ✅ FULL A4 STRUCTURE (EXAMPLE)

```html
<body>
    <div class="resume">

        <h1>Your Name</h1>
        <p class="title">Junior Frontend Developer</p>

        <div class="section">
            <p>123 Your Street</p>
            <p>Your City, ST 12345</p>
            <p>(123) 456-7890</p>
            <p>no_reply@example.com</p>
        </div>

        <h2>Experience</h2>

        <div class="section company">
            <strong>ICT Professional Training Center – Video Editor</strong><br>
            <span>June 2025 – November 2025</span>
            <ul>
                <li>Edited educational and promotional videos</li>
                <li>Added subtitles, transitions, and effects</li>
                <li>Worked with trainers to improve content quality</li>
            </ul>
        </div>

        <h2>Across the Internet</h2>
        <div class="section">
            <a href="https://www.linkedin.com/in/kong-kanhchana-872789359/" target="_blank">
                <i class="fab fa-linkedin"></i> LinkedIn
            </a>
            •
            <a href="https://github.com/Kanhchana-kc" target="_blank">
                <i class="fab fa-github"></i> GitHub
            </a>
        </div>

    </div>
</body>
```

---

## 🖨️ HOW TO EXPORT AS PDF (A4)

1. Open HTML in **Chrome**
2. Press **Ctrl + P**
3. Destination → **Save as PDF**
4. Paper size → **A4**
5. Margins → **Default**
6. Scale → **100%**

---





