# 🏗️ Wasit Al-Shamal Real Estate – Design System Documentation

This document describes the **complete design system**, **layout structure**, **visual guidelines**, and **page requirements** for the *Wasit Al-Shamal Real Estate* website.  
It ensures design consistency and implementation accuracy across all frontend and backend layers.

---

## 🎨 Brand Identity

| Element | Value |
|----------|--------|
| **Primary Color** | Navy Blue `#0A2342` |
| **Secondary Color** | Medium Blue `#1E3A5F` |
| **Accent Color** | Gold `#D4AF37` |
| **Neutral Shades** | White `#FFFFFF`, Light Gray `#F5F5F5`, Dark Gray `#333333` |
| **Font Family** | GE SS Two (Bold / Medium / Regular / Light) |
| **Icon Set** | Font Awesome 6 |
| **Corner Radius** | 8–30px (buttons, cards, inputs) |
| **Hover Effects** | Subtle scale-up (+5%) and light shadow |
| **Language Direction** | RTL (Right-to-Left) Arabic support |

---

## 🧱 Global Components

### 1️⃣ Header (Top Navigation)

**Height:** 210px (3 layers)

**Structure:**
1. **Top Bar (40px)**  
   - Background: `#0A2342`  
   - Contact Numbers (white text)  
   - Social Media Icons (gold, enlarge on hover)  
   - Font: GE SS Two Regular, 14px

2. **Main Header (80px)**  
   - Logo (40×40px, navy) + Company Name  
   - Navigation Links: Home | About | Services | Properties | Areas | Blog | Contact  
   - Hover → Gold text  
   - Search & Call-to-Action Button (Gold background, rounded, shadow on hover)

3. **Info Bar (50px)**  
   - Left: Company Address  
   - Right: Quick stats (Properties, Areas, Rating)  
   - Background: `#1E3A5F`, Text: White + Gold

---

### 2️⃣ Footer (Site Bottom)

**Structure:** 3 sections  

1. **Top CTA Bar (100px)**  
   - Text: “Start your real estate journey today”  
   - Button: “Contact Us” – Gold background, navy text  

2. **Main Footer (350px)**  
   - 4 Columns:  
     - **About Us:** Company intro  
     - **Quick Links:** Navigation shortcuts  
     - **Our Services:** Key offerings  
     - **Contact Info:** Phones, Email, Address  
   - Social Icons (Facebook, Twitter, Instagram, LinkedIn, WhatsApp)  
     - Color: White → Gold on hover  

3. **Bottom Bar (60px)**  
   - Background: Dark Navy `#081A33`  
   - Left: “© 2025 Wasit Al-Shamal Real Estate”  
   - Right: “Developed by Wasit Al-Shamal Tech Team” (Gold text)

---

## 🏠 Home Page

**Sections:**
1. **Hero Section (600px)**  
   - Background Image + Navy Overlay (60%)  
   - Title: White (48px)  
   - Subtitle: Gold (24px)  
   - Buttons: “Search Property” & “Free Consultation”  

2. **Services Overview (500px)**  
   - Light Gray Background  
   - 3 Cards: Sale / Rent / Property Management  

3. **Featured Properties (600px)**  
   - White Background  
   - 3 Property Cards (with price, area, location)  

4. **Coverage Areas (500px)**  
   - Navy Background  
   - Map + 4 Area Cards  

5. **Why Choose Us (400px)**  
   - Light Gold Background  
   - 4 Circular Icons (Trust, Speed, Accuracy, Experience)  

6. **Contact CTA (300px)**  
   - Navy Background  
   - Text: White  
   - Button: Gold → White hover  

---

## 🏢 About Us Page

**Sections:**
1. **Hero (400px)** – Navy Overlay  
2. **Company Overview (300px)** – Two Columns (Text + CEO Image)  
3. **Vision & Mission (350px)** – Icons + Text Blocks  
4. **Values (400px)** – 4 Cards, Navy Background, Gold Icons  

---

## 🧰 Services Page

**Sections:**
1. **Hero (350px)** – Navy overlay  
2. **Overview (200px)** – Gray background text intro  
3. **Detailed Services (800px)** – 3 service blocks:  
   - Sale of Properties  
   - Leasing  
   - Property Management  
   Each includes: icon, description, features list, CTA button.  

---

## 🏡 Properties Page

**Sections:**
1. **Hero (350px)** – City skyline background  
2. **Filters Bar (100px)** – Dropdowns for property type, area, price, etc.  
3. **Properties Grid** – 3 columns (responsive)  
   - Card: Image, Type, Location, Price, Size  
   - Hover: Image zoom + shadow  
4. **Pagination** – Circle buttons (Gold active)  
5. **Contact CTA (300px)** – Navy section with Gold button  

---

## 🗺️ Coverage Areas Page

**Sections:**
1. **Hero (350px)** – Navy overlay  
2. **Interactive Map (500px)** – Highlighted Riyadh zones  
3. **Areas Grid (700px)** – 4×N cards (area name, image, property count)  
4. **Statistics (300px)** – 4 Info Boxes (Properties, Clients, Experience)  
5. **CTA (250px)** – Gold background, Navy button  

---

## 📰 Blog Page

**Sections:**
1. **Hero (350px)** – “Real Estate Blog”  
2. **Categories Bar (100px)** – Filter by topic  
3. **Blog Grid** – 3-column layout  
   - Card: Image, Title, Excerpt, Author, Read More  
4. **Pagination** – Circular buttons  
5. **Featured Posts (400px)** – 3 highlighted articles  
6. **Subscription CTA (250px)** – Email form on Gold background  

---

## ☎️ Contact Us Page

**Sections:**
1. **Hero (350px)** – “Contact Us” banner  
2. **Contact Info Cards (3)** – Phone, Email, Address  
3. **Google Map (400px)** – Riyadh location  
4. **Contact Form (500px)** – Name, Email, Subject, Message  
5. **Social Media Bar (150px)** – Navy background, Gold hover  

---

## ⚙️ Global Design Guidelines

| Element | Property | Value |
|----------|-----------|--------|
| **Font Sizes** | Headings | 24–48px |
|  | Body Text | 16–18px |
| **Button Styles** | Filled (Gold) / Outline (Navy) |
| **Icons** | Font Awesome 6, size 20–40px |
| **Shadow** | `0 3px 8px rgba(0,0,0,0.1)` |
| **Transitions** | `all 0.3s ease-in-out` |
| **Responsiveness** | Grid collapses to 2 columns on tablets, 1 on mobiles |
| **Hover Interactions** | Scale +5%, color swap, subtle glow |

---

## 🧩 Technical Integration Notes (for ASP.NET)

| Component | Implementation |
|------------|----------------|
| **Header** | Partial View `_Header.cshtml` |
| **Footer** | Partial View `_Footer.cshtml` |
| **Layout** | `_Layout.cshtml` – include partials and shared CSS/JS |
| **Fonts** | Include GE SS Two via local font-face |
| **Icons** | Font Awesome CDN |
| **Responsive Grid** | Bootstrap 5 or Tailwind CSS |

---

## 📄 Version & Maintenance

- **Version:** 1.0.0  
- **Last Updated:** 2025-10  
- **Maintained by:** Ammar Yasser (Backend Developer – ASP.NET Core)  
- **Team:** Wasit Al-Shamal Technical Team  

---

## ✅ Summary

The design of *Wasit Al-Shamal Real Estate* website emphasizes:
- Professional real estate identity  
- Full Arabic RTL compatibility  
- Clean, consistent, and responsive layout  
- High accessibility and readability  
- Unified branding across all pages  

---

© 2025 **Wasit Al-Shamal Real Estate** – All Rights Reserved.
