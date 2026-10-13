# 🚀 Clothes Store — React Storefront

A clothing e-commerce storefront with a product catalog and shopping cart, built with React and TypeScript.

## 📌 Overview

A front-end storefront showing a product catalog, detail modals, and a working cart, with smooth animations. Product data is stored locally in the app — there is no backend. The source is packaged as `clothes website.zip` in this repository.

## ✨ Features

* Product catalog with a detail modal
* Shopping cart (add, remove, change quantity)
* Responsive navbar and hero section
* Smooth animations with Framer Motion

## 🛠️ Tech Stack

* Language: TypeScript
* Libraries: React, Vite, Tailwind CSS, Framer Motion, Lucide icons
* Tools: Git, GitHub, npm

## 📂 Project Structure

```
clothes-store-react/
├── clothes website.zip     # contains the project/ source folder
├── LICENSE
└── README.md

# inside the zip:
project/
├── src/
│   ├── App.tsx             # app shell, product grid, cart state
│   ├── components/         # navbar, product cards, modals, cart
│   └── data/products.ts    # local product catalog
├── package.json
└── vite.config.ts
```

## ⚙️ Installation

1. Clone the repository:

```
git clone https://github.com/JAIMINRSOJITRA/clothes-store-react.git
```

2. Navigate to the project:

```
cd clothes-store-react
```

3. Unzip the project:

```
unzip "clothes website.zip"
cd project
```

4. Install dependencies:

```
npm install
```

## ▶️ Usage

```
npm run dev       # start the dev server
npm run build     # production build
```

## 📊 Results / Demo

* Run `npm run dev` and open the printed local URL to browse the catalog and use the cart.

## 🧠 What I Learned

* Structuring a React + TypeScript app into reusable components
* Managing cart state across components
* Styling quickly with Tailwind and adding motion with Framer Motion

## 🔮 Future Improvements

* Connect a real backend or database for products and orders
* Add search, filters, and checkout
* Extract the project out of the zip so the code is browsable on GitHub

## 🤝 Contributing

Contributions, issues, and suggestions are welcome.

## 📄 License

This project is licensed under the MIT License.

## 👨‍💻 Author

Jaimin Sojitra

* GitHub: https://github.com/JAIMINRSOJITRA
* LinkedIn: https://www.linkedin.com/in/jaimin-sojitra-4683a1277/
