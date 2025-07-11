# 📚 New Model FAQ with Main and Sub Parts for Power BI

A modern, flexible FAQ design inspired by standard HTML5 `<details>` and `<summary>` elements — adapted for **Power BI** using pure **DAX, HTML, and CSS**, with no JavaScript required.

This **new model FAQ** is perfect for larger projects that need both **main questions and nested subparts**. It’s lightweight, user-friendly, and easy to customise for any report theme.

---

## 📌 What This Is

✅ A customisable FAQ template:
- Organise complex FAQs with clear main questions and nested sub-answers.
- Pure HTML5 and CSS — works in Power BI Desktop and Service.
- SEO-friendly structure when used on a website.
- No plugins needed.

✅ Lightweight & Accessible:
- Uses the HTML `<details>` and `<summary>` tags for a native expand/collapse effect.
- Works perfectly in any HTML Viewer or HTML Content visual in Power BI.

✅ Dynamic Ready:
- Store FAQs in a data table and build them dynamically with `CONCATENATEX` if needed.
- Keeps your FAQ content updated automatically.

---

## ✨ Why Use This

- Perfect for big projects with multiple FAQ layers.
- Clear layout makes it easy for viewers to navigate complex topics.
- Works fully offline — no external libraries.
- Responsive and accessible.

---

## ⚙️ How It Works

1️⃣ **DAX Measure**

Write your entire HTML + CSS in a single DAX measure. Use static or dynamic text as needed.

2️⃣ **HTML Viewer Visual**

Use a certified HTML Content or HTML Viewer visual from AppSource. Add your measure to render your FAQ in Power BI.

3️⃣ **Details Accordion**

The expand/collapse effect is handled entirely by the standard HTML5 `<details>` tag — no scripting needed.

---

## 🎨 Customisation Tips

✅ Tweak the colours, borders, fonts, and padding in your inline CSS to match your report’s branding.

✅ If using this on a website, wrap your code with `<html>`, `<head>`, and `<body>` tags for SEO best practice.

✅ Add as many main questions and subparts as you need — this structure is easy to expand.

---

## 🔗 Inspiration & Source

This approach is based on the standard HTML5 `<details>` accordion pattern — widely used by developers and documented in the [MDN Web Docs](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/details).

---

## ✅ Example Use Cases

- FAQs for technical documentation inside Power BI.
- Layered help sections for big projects or compliance dashboards.
- Glossary with definitions and nested details.
- Anything that benefits from clear main questions and grouped sub-answers.

---

## 📄 Licence

Open-source and free to use.  
If you adapt it, please keep a note that it uses the standard HTML5 `<details>` tag approach for easy referencing.

---

**Enjoy building your New Model FAQ with Main and Sub Parts for Power BI!** 📚✨
