# Portfolio Landing Page

A modern, responsive developer portfolio website built with React and Tailwind CSS. Showcase your projects, experience, and skills with this elegant and fully customizable portfolio template.

[![React](https://img.shields.io/badge/React-18+-61DAFB?style=flat-square&logo=react&logoColor=black)](https://reactjs.org/) [![Tailwind CSS](https://img.shields.io/badge/Tailwind%20CSS-3+-38B2AC?style=flat-square&logo=tailwind-css&logoColor=white)](https://tailwindcss.com/) [![TypeScript](https://img.shields.io/badge/TypeScript-5+-3178C6?style=flat-square&logo=typescript&logoColor=white)](https://www.typescriptlang.org/)

## ✨ Features

- **🎨 Modern Design**: Clean, professional layout with smooth animations
- **📱 Fully Responsive**: Perfect display on desktop, tablet, and mobile devices
- **⚡ Performance Optimized**: Fast loading times and smooth interactions
- **🔧 Easy Customization**: Simple configuration for personal branding
- **🎯 SEO Ready**: Optimized for search engines with proper meta tags
- **♿ Accessible**: Built with accessibility best practices
- **🌙 Dark/Light Mode**: Toggle between themes (coming soon)
- **📊 Analytics Ready**: Easy integration with Google Analytics
- **🚀 Modern Tech Stack**: React 18+, Tailwind CSS 3+, TypeScript

## 🚀 Quick Start

### Prerequisites

Make sure you have the following installed:

- [Node.js](https://nodejs.org/) (v18 or higher)
- [npm](https://www.npmjs.com/) or [yarn](https://yarnpkg.com/)

### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/tirthgoyani11/portfolio-landing-page.git
   cd portfolio-landing-page
   ```

2. **Install dependencies**
   ```bash
   npm install
   # or
   yarn install
   ```

3. **Start the development server**
   ```bash
   npm run dev
   # or
   yarn dev
   ```

4. **Open your browser**
   Navigate to `http://localhost:3000` to see your portfolio in action!

## 🛠️ Configuration

### Personal Information

Update your personal information in `src/config/portfolio.js`:

```javascript
export const portfolioConfig = {
  name: "Tirth Goyani",
  title: "Full Stack Developer",
  email: "tirthgoyani11@gmail.com",
  website: "https://tirthgoyani.dev",
  social: {
    linkedin: "https://linkedin.com/in/tirthgoyani",
    twitter: "https://twitter.com/tirthgoyani",
    github: "https://github.com/tirthgoyani11"
  }
};
```

### Customizing Content

- **Hero Section**: Edit `src/components/Hero.jsx`
- **About Section**: Update `src/components/About.jsx`
- **Projects**: Add your projects in `src/data/projects.js`
- **Experience**: Update your work history in `src/data/experience.js`
- **Skills**: Modify your skills in `src/data/skills.js`

### Styling

The project uses Tailwind CSS for styling. You can:

- Modify the color scheme in `tailwind.config.js`
- Add custom CSS in `src/styles/globals.css`
- Update component styles directly in JSX files

## 📁 Project Structure

```
portfolio-landing-page/
├── public/
│   ├── images/
│   └── favicon.ico
├── src/
│   ├── components/
│   │   ├── Header.jsx
│   │   ├── Hero.jsx
│   │   ├── About.jsx
│   │   ├── Projects.jsx
│   │   ├── Experience.jsx
│   │   ├── Skills.jsx
│   │   ├── Contact.jsx
│   │   └── Footer.jsx
│   ├── data/
│   │   ├── projects.js
│   │   ├── experience.js
│   │   └── skills.js
│   ├── config/
│   │   └── portfolio.js
│   ├── styles/
│   │   └── globals.css
│   ├── utils/
│   └── App.jsx
├── package.json
├── tailwind.config.js
├── vite.config.js
└── README.md
```

## 🎨 Sections

The portfolio includes the following sections:

1. **Header/Navigation** - Smooth scrolling navigation
2. **Hero** - Eye-catching introduction with call-to-action
3. **About** - Personal introduction and background
4. **Projects** - Showcase of your best work
5. **Experience** - Professional work history
6. **Skills** - Technical skills and expertise
7. **Contact** - Contact form and social links
8. **Footer** - Additional links and information

## 🚀 Deployment

### Vercel (Recommended)

1. Push your code to GitHub
2. Visit [Vercel](https://vercel.com/) and import your repository
3. Deploy with zero configuration

### Netlify

1. Build the project: `npm run build`
2. Drag and drop the `dist` folder to [Netlify](https://netlify.com/)

### GitHub Pages

1. Install gh-pages: `npm install --save-dev gh-pages`
2. Add to package.json:
   ```json
   "homepage": "https://yourusername.github.io/portfolio-landing-page",
   "scripts": {
     "predeploy": "npm run build",
     "deploy": "gh-pages -d dist"
   }
   ```
3. Deploy: `npm run deploy`

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

1. Fork the project
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📝 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🙏 Acknowledgments

- [React](https://reactjs.org/) - The web framework used
- [Tailwind CSS](https://tailwindcss.com/) - For styling
- [Vite](https://vitejs.dev/) - Build tool
- [Lucide React](https://lucide.dev/) - For beautiful icons

## 📞 Support

If you like this project, please give it a ⭐ on GitHub!

For support, email tirthgoyani11@gmail.com or create an issue on GitHub.

---
**Built with ❤️ by [Tirth Goyani](https://tirthgoyani.dev)**
