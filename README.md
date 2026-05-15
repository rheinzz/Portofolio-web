# Portfolio Website Documentation

## 📌 Project Overview

Portfolio Website ini merupakan website pribadi yang dibuat untuk menampilkan profil, kemampuan, dan project yang dimiliki. Website ini dibuat menggunakan teknologi dasar front-end seperti HTML, CSS, dan JavaScript dengan tampilan modern serta fitur dark mode.

Website ini memiliki beberapa section utama seperti:

* Home
* About Me
* Work / Project Gallery
* Footer / Social Media


## 🛠️ Technologies Used

### 1. HTML

Digunakan sebagai struktur utama website, seperti membuat:

* Header
* Navigation Bar
* Section Home
* About
* Work Gallery
* Footer

### 2. CSS

Digunakan untuk:

* Styling website
* Layouting
* Responsive spacing
* Animation & hover effect
* Dark mode styling

### 3. JavaScript

Digunakan untuk:

* Mengatur fitur Dark Mode toggle


## 📂 Project Structure

```bash
project-folder/
│
├── Portofolio.html
├── style.css
├── portofolio.js
├── images/
│   └── picture.jpg
├── work1.jpg
├── work2.jpg
└── work3.jpg
```

---

# 📄 File Explanation

## 1. `Portofolio.html`

File utama website yang berisi struktur halaman.

### Features:

* Navigation bar
* Hero section
* About section
* Project gallery
* Footer
* Dark mode toggle

---

## 2. `style.css`

Digunakan untuk seluruh styling website.

### Styling Includes:

* Layouting
* Flexbox & Grid
* Hover animation
* Gallery styling
* Dark mode theme
* Responsive spacing

### Important Sections:

* Header Styling
* Home Section
* About Section
* Gallery Section
* Footer
* Dark Mode

---

## 3. `portofolio.js`

Digunakan untuk logika dark mode.

### Function:

```javascript
const toggle = document.getElementById("darkToggle");

toggle.addEventListener("change", () => {
    document.body.classList.toggle("dark");
});
```

### Explanation:

* Mengambil elemen toggle dark mode
* Ketika toggle ditekan:

  * class `dark` akan ditambahkan ke body
  * website berubah menjadi dark mode

---

# 🎨 UI Features

## ✅ Smooth Scroll

Website menggunakan:

```css
scroll-behavior: smooth;
```

Agar perpindahan antar section lebih halus.

---

## ✅ Dark Mode

Fitur untuk mengganti tema website menjadi gelap menggunakan JavaScript dan CSS class.



## ✅ Responsive Layout

Menggunakan:

* Flexbox
* CSS Grid

Agar tampilan lebih rapi dan modern.



## ✅ Hover Animation

Gallery project memiliki efek hover:

```css
transform: translateY(-8px);
```



# 📸 Sections Overview

## 🏠 Home

Menampilkan:

* Intro singkat
* Nama pemilik portfolio
* Gambar profile



## 👤 About Me

Berisi:

* Deskripsi diri
* Background pendidikan
* Passion di bidang coding
* Skill yang dimiliki

---

## 💼 Work / Projects

Gallery project sederhana untuk menampilkan hasil karya.



## 🔗 Footer

Berisi:

* Copyright
* Social media link

---

# 🚀 Future Improvement

Beberapa fitur yang bisa dikembangkan:

* Responsive Mobile Version
* Contact Form
* Project Detail Page
* Animation menggunakan AOS / GSAP
* Backend integration
* Database project
* Tailwind CSS migration
* React / Next.js version



# ▶️ How to Run

1. Download semua file project
2. Pastikan struktur folder sesuai
3. Buka file:

```bash
Portofolio.html
```

4. Jalankan menggunakan browser



# 👨‍💻 Author

**Muhammad Farhan Iqbal Maulana**

Frontend Developer Enthusiast
Passionate in Coding, Computing, and Game Development.
