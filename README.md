# AskUI

Minimal UI kit by **AskSoft** — white sidebar, Inter font, Tailwind CDN + Alpine.js. No build step.

## Χρήση

```html
<!-- 1. Inter font -->
<link rel="preconnect" href="https://fonts.googleapis.com">
<link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;500;600;700;800&display=swap" rel="stylesheet">

<!-- 2. Tailwind CDN -->
<script src="https://cdn.tailwindcss.com"></script>
<script>
  tailwind.config = {
    theme: { extend: { fontFamily: { sans: ['Inter','ui-sans-serif','system-ui','sans-serif'] } } }
  }
</script>

<!-- 3. Alpine.js -->
<script defer src="https://cdn.jsdelivr.net/npm/alpinejs@3.x.x/dist/cdn.min.js"></script>

<!-- 4. AskUI -->
<link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/alfa-kappa/askui@main/dist/askui.css">
```

## Classes

| Class | Περιγραφή |
|-------|-----------|
| `.card` | White rounded card with subtle shadow |
| `.btn-primary` | Blue filled button |
| `.btn-secondary` | White outlined button |
| `.btn-danger` | Red filled button |
| `.btn-sm` | Modifier — smaller padding/font |
| `.badge` + `.badge-{color}` | Pill badge: blue green yellow red purple orange gray |
| `.alert` + `.alert-{type}` | Alert bar: success error warning info |
| `.form-input` | Styled input / select / textarea |
| `.form-label` | Label above form field |
| `.form-hint` | Helper text below field |
| `.form-error` | Red error text below field |
| `.nav-item` | Sidebar nav link |
| `.nav-item.active` | Active sidebar link |
| `.nav-section` | Uppercase section header in sidebar |
| `.th` / `.td` | Table header / cell |
| `.tr-hover` | Table row with hover background |
| `.auth-card` | Centered auth form card |
| `.auth-input` | Larger input for auth forms |
| `.auth-btn` | Gradient submit button for auth |

## Docs

Άνοιξε `docs/index.html` στον browser για live preview όλων των components.
