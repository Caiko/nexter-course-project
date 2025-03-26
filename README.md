# SCSS: Nexter Course Project

### 📚 Overview

This project is a responsive real estate web layout called **Nexter**, built using **SCSS**. It focuses on creating a modern, modular, and scalable codebase using best practices like BEM, custom media queries, and a component-driven architecture.

### 🚀 Features

- **Responsive Design**: Built with CSS Grid and media queries.
- **SCSS Architecture**: Organized using partials such as `_header.scss`, `_footer.scss`, and `_gallery.scss` for maintainability and reusability.
- **CSS Grid Power**: Uses grid-template areas and advanced track management for clean layout control.
- **BEM Naming Convention**: Clear and consistent class naming for scalability.
- **Modular and Maintainable Code**: SCSS variables, nested rules, and mixins make styling efficient.

### 📸 Preview

![image](https://github.com/user-attachments/assets/f74c2d44-4112-48df-9995-5829259755ec)
![image](https://github.com/user-attachments/assets/d15516d9-90d8-42fa-9721-2d8fd54ef2c7)
![image](https://github.com/user-attachments/assets/1da72a34-e0f1-49f0-9796-b872283af668)
![image](https://github.com/user-attachments/assets/350b026c-958e-430b-9994-483d8591e566)
![image](https://github.com/user-attachments/assets/4d0c1132-ab48-4a14-82e1-2dda535800ca)
![image](https://github.com/user-attachments/assets/243d6939-1f8a-4273-a209-c27aa80ed0a9)

### 💻 Technologies Used

- **SCSS (Sassy CSS)** – For writing clean, modular CSS with variables, nesting, and partials.
- **CSS Grid, Flexbox** – For creating a flexible and responsive layout structure.
- **HTML5** – With semantic markup.

### 🪰 Prerequisites

Make sure you have the following installed:

- **Node.js** – https://nodejs.org/
- **Sass** – Install globally via:

```bash
npm install -g sass
```

### 📂 Project Structure

```bash
nexter-course-project/
├── css/
│   ├── style.css
│   ├── style.comp.css
│   ├── style.prefix.css
│   └── *.map
├── img/
├── node_modules/
├── sass/
│   ├── _base.scss
│   ├── _features.scss
│   ├── _footer.scss
│   ├── _gallery.scss
│   ├── _header.scss
│   ├── _homes.scss
│   ├── _realtors.scss
│   ├── _sidebar.scss
│   ├── _story.scss
│   ├── _typography.scss
│   └── main.scss
├── index.html
├── package.json
├── package-lock.json
└── README.md
```

### 💾 How to Run the Project

1️⃣ **Clone the repository:**

```bash
git clone https://github.com/Caiko/nexter-course-project.git
```

2️⃣ **Navigate into the project folder:**

```bash
cd nexter-course-project
```

3️⃣ **Install dependencies:**

```bash
npm install
```

4️⃣ **Compile SCSS (example build script):**

```bash
npm run build:css
```

5️⃣ **Open in browser:**

Open `index.html` in your browser to see the layout.

### 📚 SCSS Structure Explained

- **`_base.scss`**: Global resets, variables, and helper utilities.
- **`_typography.scss`**: Font styles and heading utilities.
- **`_header.scss`, `_footer.scss`, etc.**: Component-specific styles.
- **`main.scss`**: Central import file that brings everything together.





