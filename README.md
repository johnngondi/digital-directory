# 🏢 Digital Directory

A fully responsive, mobile-first **Digital Directory** for buildings like HH Towers — built using a single lightweight `index.html` file with embedded HTML, CSS, and JavaScript.

### 🔍 Features
- Smart search (by shop number, floor, tenant name, phone, or email)
- Popup on card tap with tenant or management contact
- Clickable phone numbers and emails
- Responsive grid layout
- Sticky search bar
- Font loaded non-blocking (Poppins)
- Vacant shops display developer contact info

---

## 🚀 Getting Started

You only need the `index.html` file to run the entire app.

### To Run:
1. Download or clone this repository
2. Open `index.html` in your browser

> ✅ No dependencies, build tools, or server needed

---

## ✏️ Updating the Directory

Open `index.html` and locate the embedded JSON in the JavaScript block:

```js
const data = {
  "building": "HH Towers",
  "floors": [
    {
      "name": "Ground Floor (G)",
      "code": "G",
      "shops": [
        {
          "shop_no": "G-01",
          "tenant": {
            "business_name": "Body by Fresh",
            "contact_name": "Cynthia Nduta",
            "phone": "+254701234567",
            "email": "support@bodybyfresh.com"
          }
        },
        {
          "shop_no": "G-02",
          "tenant": null
        }
      ]
    }
  ]
};
```

You can:
- Add more floors or shops
- Mark `tenant: null` for vacant shops
- Keep contact fields blank if unknown

Vacant shops automatically show this contact:
- 📞 `0715 823 592`
- 📧 `john@nwrealite.co.ke`

---

## 🌐 Hosting

You can drag-and-drop `index.html` to any static host:
- [Netlify Drop](https://app.netlify.com/drop)
- [GitHub Pages](https://pages.github.com)
- [Vercel](https://vercel.com)

---

## 📄 License

This project is open-source under the [MIT License](LICENSE).

---

## 👨‍💻 Developer Contact

Have questions or need a custom setup?

**John – NW Realite Ltd**  
📞 `0715 823 592`  
📧 `john@nwrealite.co.ke`
