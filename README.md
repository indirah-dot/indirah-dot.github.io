# indirah-dot.github.io

### **Minimalist Technical Archive & Documentation**
> **Guiding Principle:** Zero-JavaScript. Zero-Bloat. Zero-External Dependencies.

---

## 🛠 System Recovery Seed (`index.html`)
If the site breaks, paste this code into `index.html`. It points to the internal `favicon.png`.

```html
<!DOCTYPE html>
<title>Indirah-Dot</title>
<link rel="icon" type="image/png" href="favicon.png">
<style>
  body{font-family:sans-serif;max-width:700px;margin:40px auto;padding:20px;line-height:1.6;color:#222}
  nav a{margin-right:15px;font-weight:700;text-decoration:none;color:#0056b3}
  header,footer{border-bottom:1px solid #ddd;padding-bottom:10px;margin-bottom:20px}
  footer{border-top:1px solid #ddd;border-bottom:0;margin-top:50px;font-size:12px}
</style>
<header>
  <h1>Indirah-Dot</h1>
  <nav><a href="index.html">Home</a><a href="meta.html">Meta</a></nav>
</header>
<p>Technical archive. Static. No scripts. No bloat.</p>
<footer>&copy; 2026</footer>
