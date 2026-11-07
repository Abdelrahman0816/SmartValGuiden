<div align="center">

# 🛒 SmartValGuiden

### *Skillnaden som faktiskt spelar roll*

A Swedish consumer-tech guide that helps people **understand, compare and choose** electronics, starting with mobile phones.

<br/>

<a href="https://smartvalguiden.se"><img src="https://img.shields.io/badge/Live%20site-smartvalguiden.se-103F84?style=for-the-badge&logo=googlechrome&logoColor=white" alt="Live site" /></a>
<img src="https://img.shields.io/badge/Status-Rebuild%20in%20progress-F5A623?style=for-the-badge" alt="Status: rebuild in progress" />

</div>

<br/>

<p align="center">
  <img src="screenshots/startsida.jpg" width="90%" alt="SmartValGuiden start page" />
</p>

<br/>

## 📝 About the project

Most comparison sites only compare prices. **SmartValGuiden** aims to help Swedish shoppers understand what actually differs between products, so they can make a confident choice.

I started the project on my own and built the first version from scratch. I am now rebuilding it on a modern stack to make it faster, easier to extend and ready for more product categories.

> 🔒 The source code is kept in a private repository. This repository presents the project.

<br/>

## ✨ Features

**Version 1 – live today**
- 📱 Phone catalogue with search and price filters
- ⚖️ Side-by-side comparison of up to three phones, with scores and specifications
- 🔐 Admin panel with authentication for managing content
- 🤖 AI integration to support content and buying guidance

**Version 2 – in development**
- ⚡ Rebuilt in **Next.js** and **React**
- 🗂️ Product catalogue with filters and sorting
- 📄 Dedicated product pages
- ⚖️ Compare two or three products, with the selection stored in the URL so comparisons can be shared

<p align="center">
  <img src="screenshots/jamforelse.jpg" width="90%" alt="Side-by-side comparison of three phones" />
  <br/>
  <sub>Side-by-side comparison of three phones with scores, prices and specifications</sub>
</p>

<br/>

## 👀 Version 2 preview

Screenshots of version 2 running locally (Next.js, React and Supabase). Version 2 is not live yet.

<p align="center">
  <img src="screenshots/v2/startsida.png" width="90%" alt="SmartValGuiden version 2 start page" />
  <br/>
  <sub>Start page with search, category overview and a live comparison of three phones</sub>
</p>

<p align="center">
  <img src="screenshots/v2/katalog.png" width="90%" alt="Phone catalogue with filters in version 2" />
  <br/>
  <sub>Phone catalogue with filters for brand, screen size and screen type, plus sorting and grid or list view</sub>
</p>

<p align="center">
  <img src="screenshots/v2/produktsida.png" width="90%" alt="Product page for Samsung Galaxy S24 Ultra in version 2" />
  <br/>
  <sub>Product page with key specifications, full specification list and available configurations</sub>
</p>

<p align="center">
  <img src="screenshots/v2/jamforelse.png" width="90%" alt="Comparison of three phones in version 2" />
  <br/>
  <sub>Comparison of three phones: rows where the values differ are highlighted and missing data is shown as a dash</sub>
</p>

<p align="center">
  <img src="screenshots/v2/startsida-mobil.png" width="300" alt="SmartValGuiden version 2 start page on mobile" />
  <br/>
  <sub>Start page on mobile (390 px wide)</sub>
</p>

<br/>

## 🔒 Security work

Before the rebuild I carried out my own security audit of version 1 and fixed:

- **Cross-site scripting (XSS)** vulnerabilities
- **Timing-unsafe token comparisons** in authentication
- **Unsafe image and input validation** in the server-side image proxy

<br/>

## 🛠️ Tech stack

| | Version 1 | Version 2 |
|---|---|---|
| **Frontend** | HTML, CSS, JavaScript | React, Next.js |
| **Backend** | PHP | Next.js |
| **Workflow** | Git | Git, local AI models with Ollama |

<p>
<img src="https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white" alt="Next.js" />
<img src="https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB" alt="React" />
<img src="https://img.shields.io/badge/PHP-777BB4?style=flat-square&logo=php&logoColor=white" alt="PHP" />
<img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black" alt="JavaScript" />
<img src="https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white" alt="HTML5" />
<img src="https://img.shields.io/badge/CSS3-1572B6?style=flat-square&logo=css3&logoColor=white" alt="CSS3" />
<img src="https://img.shields.io/badge/Ollama-000000?style=flat-square&logo=ollama&logoColor=white" alt="Ollama" />
</p>

<br/>

## 🗺️ Roadmap

- [x] Version 1 live with phones
- [x] Security audit of version 1
- [ ] Launch version 2 (Next.js)
- [ ] Price history for each product
- [ ] Personalised scoring based on what matters to each user
- [ ] More categories: laptops, TVs, headphones, tablets, smartwatches and monitors

<br/>

## 👤 Author

**Abdelrahman Hana** · Computer Engineering student at KTH Royal Institute of Technology

[GitHub](https://github.com/Abdelrahman0816) · [abduhassan930@gmail.com](mailto:abduhassan930@gmail.com)
