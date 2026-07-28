# 👋 About Me

Hi, I’m **Hamish Phillips** — a recent graduate from the **University of Otago**, where I completed a **Bachelor of Arts & Science**, majoring in **Software Engineering** and **Music**.

I currently work as an **Administrator at Wellington Regional Hospital** and as an **Software Engineer** for my business **Phillips Music & Tech**, where I support clients with software development, web management, SEO optimisation, automation tools, and IT troubleshooting.

View my CV here: [HPhillips CV](https://hamtana.github.io/HPhillips-CV/)

---

## 🛠️ Recently Completed Projects

### 1. [EV Autos](https://evautos.co.nz)

🚗 Shipping a full-stack workshop platform: EV Autos

I built EV Autos, a full-stack website for auto workshops, combining public marketing pages with real booking, enquiry, and feedback flows, plus a protected admin dashboard to run it all.

Here's the stack behind it:

- TanStack Start — full-stack React architecture with type-safe server functions

- TanStack Router — file-based routing with public, auth, and protected route groups

- TanStack Query — caching, fetching, and cache invalidation for live data

- TanStack Form + Zod — form state management with schema-based validation

- Clerk — authentication guarding the admin dashboard 🐘 Neon PostgreSQL +

- Drizzle ORM — typed, serverless database access

- Tailwind CSS + shadcn/ui — clean, consistent UI

What it does:

- Customers can book appointments, with server-side re-validation of availability and blocked dates to avoid race conditions
- Enquiry and feedback forms route straight to admin notifications
- Admins get a dashboard to view, cancel, and manage bookings, plus block/unblock dates
- Every domain operation (bookings, enquiries, feedback) is implemented as a TanStack Start server function, called directly from the UI for end-to-end type safety

The most interesting part was designing the booking flow: client-side date state gets enriched with query data (fully booked + blocked dates), but the real check happens server-side to keep things consistent under concurrent bookings.

This project pushed me deeper into the TanStack ecosystem (Start, Router, Query, Form working together) and reinforced how much a well-typed server function layer simplifies full-stack development.

### 2. [Southern Paediatrics](https://southernpaediatrics.co.nz)

Designed and built a website for Southern Paediatrics Ltd, a private specialist healthcare service operating across Dunedin and Central Otago, New Zealand. This project strengthened my practical knowledge of CSS and the Tailwind framework, particularly in building clean, responsive layouts.

**Tech Used:**  
✔️ Next.Js · ✔️ TailwindCSS · ✔️ Vercel

---

### 3. [Review Engine](https://github.com/hamtana/ReviewEngine)

A lightweight feedback system designed to help businesses receive and act on low-star reviews privately. If a user submits a rating below three stars, they’re prompted to send an email instead — reducing negative public reviews while improving customer experience.

**Tech Used:**  
✔️ Docker · ✔️ React.js · ✔️ Express.js · ✔️ TailwindCSS

---

### 4. Monthly File Copier

A simple yet impactful automation tool created after noticing the manual workload for a Health Provider. Staff were manually copying and renaming daily spreadsheets — so I built an application to automate the process. Users can input the month and year and choose from four tailored copying options.

**Tech Used:** ✔️ Java

---

### 5. [Email Verifier](https://github.com/hamtana/EmailVerifier)

As part of my contract work, I often send emails containing multiple links. To avoid broken or outdated URLs, I developed a Python script that parses a `.eml` file, extracts every link, and returns the HTTP response codes — saving time and ensuring reliability.

**Tech Used:** ✔️ Python

---

## 🚧 Currently Working On

### 1. Nichol's Website

Developing a website for a local Otago and Southland business, Nichol's. The site is being built using Wordpress, WooCommerce and features a customised theme to match the business's branding. The project is still in it's early stages, and I am excited to share updates as the site progresses.

### 2. [Emily Alice Band Website](https://github.com/hamtana)

Developing a website for a local Wellington band, Emily Alice. The site will feature pages for media, music, shows, and contact information, along with a protected admin dashboard for managing content. The project is still in the early stages, but I’m excited to apply my skills to create a visually appealing and functional site.

**Technologies Used:**

| Purpose    | Technology     |
| ---------- | -------------- |
| Frontend   | Tanstack Start |
| Backend    | Tanstack Start |
| Database   | PostgreSQL     |
| Deployment | Vercel         |

---

### 3. [Address Verifier](https://github.com/hamtana/AddressVerifier)

Developing an API that integrates with LINZ (Land Information New Zealand) data to verify addresses across New Zealand. When queried, the API returns JSON-formatted address data including street address, suburb, and city, which can be used to pre-populate form fields.

**Technologies**

| Purpose    | Technology        |
| ---------- | ----------------- |
| API        | Java Spring Boot  |
| Deployment | Docker/Kubernetes |

<!-- ### 2. [Travel Tracker](https://github.com/hamtana/TravelTracker)

A much-needed replacement for spreadsheet-based patient travel tracking. This system uses a centralised database to make travel data more accessible, reliable, and efficient for staff across the country.

**Technologies**

| Purpose    | Technology       |
| ---------- | ---------------- |
| Backend    | Java Spring Boot |
| Database   | PostgreSQL       |
| Build Tool | Gradle           |
| CSS        | TailwindCSS      |
| API Tool   | OpenAPI          | -->

<!-- --- -->
<!--
### 2. [Uniform Tracker](https://github.com/hamtana/Uniform-Tracker) -->
<!--
Developed for a Health Provider, this tool manages staff uniforms and procurement across multiple wards, reducing manual admin and improving accuracy.

**Technologies**

| Purpose    | Technology       |
| ---------- | ---------------- |
| Backend    | Java Spring Boot |
| Database   | PostgreSQL       |
| Build Tool | Gradle           |
| CSS        | TailwindCSS      | -->

---

## 📚 Currently Learning

- React
- Python
- TailwindCSS
- NextJs
- Docker deployment with Kubernetes

---

## 📬 Get in Touch

You can reach me at **hamish@phillipsmusictech.co.nz**,  
or send a message via my website.

<!--
**hamtana/hamtana** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
