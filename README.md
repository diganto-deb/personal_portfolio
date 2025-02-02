# Personal Portfolio Website

A modern, responsive portfolio website built with Astro, React, and Tailwind CSS. Features a dark mode, smooth animations, and a contact form powered by EmailJS.

## 🚀 Features

- ⚡️ Fast and lightweight with Astro
- 🎨 Tailwind CSS for styling
- 🌙 Dark/Light mode
- 📱 Fully responsive design
- ✨ Smooth animations with AOS
- 📬 Contact form with EmailJS integration
- 🔍 SEO friendly
- 🎯 Analytics ready

## 🛠️ Tech Stack

- [Astro](https://astro.build)
- [Tailwind CSS](https://tailwindcss.com)
- [TypeScript](https://www.typescriptlang.org)
- [EmailJS](https://www.emailjs.com)

## 🏗️ Getting Started

### Prerequisites

- Node.js 16+ and npm

### Installation Steps

1. Clone the repository
bash
git clone https://github.com/yourusername/portfolio.git
2. Change into the project directory
directory
bash
cd portfolio


3. Install dependencies
```bash
npm install
```
4. Create a `.env` file in the root directory
```bash
cp .env.example .env
```
5. Update the `.env` file with your EmailJS credentials
```bash
PUBLIC_EMAILJS_SERVICE_ID=your_service_id
PUBLIC_EMAILJS_TEMPLATE_ID=your_template_id
PUBLIC_EMAILJS_PUBLIC_KEY=your_public_key
```
6. Start the development server
```bash
bash
npm run dev
```
The site should now be running at `http://localhost:4321`