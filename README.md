<div align="center">

<!-- Animated wave header -->
<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0D1B2A,50:4ECDC4,100:0D1B2A&height=160&section=header&text=Dental%20Website%20Template&fontSize=36&fontColor=ffffff&animation=fadeIn&fontAlignY=55&desc=Modern%20%7C%20Responsive%20%7C%20Ready%20to%20Deploy&descAlignY=75&descSize=14&descColor=4ECDC4" width="100%" />

<br/>



<br/><br/>

[![Live Demo](https://img.shields.io/badge/🌐%20Live%20Demo-View%20Site-4ECDC4?style=for-the-badge)](https://lucent-boba-25e564.netlify.app/)
[![Made By](https://img.shields.io/badge/Built%20by-AurnoQ-0D1B2A?style=for-the-badge)](https://aurnoq-opal.vercel.app)
[![Single File](https://img.shields.io/badge/Single-HTML%20File-FF6B6B?style=for-the-badge&logo=html5&logoColor=white)]()

</div>

---



## 🏥 Clinic Name — How to Change

The clinic name appears in **4 places** in the HTML. Search for `Oneness dental care` and replace all:

```html
<!-- 1. Browser tab title (~line 6) -->
<title>Oneness dental care</title>
→ <title>Your Clinic Name</title>

<!-- 2. Navigation bar (~line 290) -->
<div class="clinic-name">Oneness dental care</div>
→ <div class="clinic-name">Your Clinic Name</div>

<!-- 3. Footer brand (~line 430) -->
<div class="clinic-name" style="...">Oneness dental care</div>
→ <div class="clinic-name" style="...">Your Clinic Name</div>

<!-- 4. Footer copyright (last few lines) -->
© 2025 BrightSmile Dental. All rights reserved.
→ © 2025 Your Clinic Name. All rights reserved.
```

> 💡 **Tip:** Use `Ctrl + H` (Find & Replace) in any code editor to update all 4 at once.

---

## 🖼️ Logo — How to Replace

The logo is currently a `🦷` emoji inside a teal circle. Replace it with your own image:

**Find this in the HTML** (appears in the nav, ~line 290):
```html
<!-- FIND -->
<div class="logo-circle">🦷</div>

<!-- REPLACE WITH -->
<div class="logo-circle" style="background:transparent; padding:0;">
  <img src="your-logo.png"
       alt="Clinic Logo"
       style="width:42px; height:42px; border-radius:50%; object-fit:cover;" />
</div>
```

**Find it again in the footer** (~line 430):
```html
<!-- FIND -->
<div class="logo-circle" style="width:36px;height:36px;font-size:16px;">🦷</div>

<!-- REPLACE WITH -->
<div class="logo-circle" style="width:36px;height:36px;background:transparent;padding:0;">
  <img src="your-logo.png"
       alt="Clinic Logo"
       style="width:36px; height:36px; border-radius:50%; object-fit:cover;" />
</div>
```

> 📁 Put your logo image in the **same folder** as `index.html` and use the exact filename.

---

## 📞 Phone Number

Search for `+919999999999` — it appears in **3 places**. Replace all:

```html
<!-- 1. Call button in hero -->
href="tel:+919999999999"
→ href="tel:+91XXXXXXXXXX"

<!-- 2. WhatsApp floating button -->
href="https://wa.me/919999999999?text=..."
→ href="https://wa.me/91XXXXXXXXXX?text=..."

<!-- 3. Footer display + WhatsApp link -->
📞 +91 99999 99999
→ 📞 +91 XXXXX XXXXX
```

---

## ✉️ Email Address

```html
<!-- FIND -->
href="mailto:hello@onenessdentalcare.com"
>✉️ hello@onenessdentalcare.com</a>

<!-- REPLACE WITH -->
href="mailto:your@email.com"
>✉️ your@email.com</a>
```

---

## 📍 Address

```html
<!-- FIND in footer -->
📍 123, Main Road, City

<!-- REPLACE WITH -->
📍 Your Clinic Full Address
```

---

## 🕐 Opening Hours

```html
<!-- FIND in footer -->
<li><a href="#">Mon–Sat: 9AM – 7PM</a></li>
<li><a href="#">Sunday: 10AM – 2PM</a></li>

<!-- REPLACE WITH your real timings -->
<li><a href="#">Mon–Fri: 10AM – 8PM</a></li>
<li><a href="#">Sat–Sun: 9AM – 3PM</a></li>
```

---

## ✅ Quick Setup Checklist

```
 □  Clinic name updated (4 places)
 □  Logo image added and path updated (2 places)
 □  Phone number updated (3 places)
 □  Email address updated
 □  Clinic address updated
 □  Opening hours updated
```

---

## 🚀 Deploy in Seconds

| Platform | How |
|---|---|
| **Netlify** | Drag & drop `index.html` → [app.netlify.com/drop](https://app.netlify.com/drop) |
| **Vercel** | Upload at [vercel.com](https://vercel.com) |
| **GitHub Pages** | Push to repo → Settings → Pages → Deploy |

---

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0D1B2A,50:4ECDC4,100:0D1B2A&height=100&section=footer&animation=fadeIn" width="100%" />

<div align="center">
<sub>Built with ❤️ by <a href="https://aurnoq-opal.vercel.app"><strong>AurnoQ</strong></a> — AI · Software · Automation</sub>
</div>
