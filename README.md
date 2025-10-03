# Portfolio Website

A modern, responsive portfolio website built with React to showcase my projects, skills, and professional experience.

## 🌟 Features

- **Responsive Design**: Optimized for desktop, tablet, and mobile devices
- **Modern UI/UX**: Clean and professional design with smooth animations
- **Project Showcase**: Interactive gallery of projects with detailed descriptions
- **Skills Section**: Visual representation of technical skills and expertise
- **Contact Form**: Functional contact form for potential clients and employers
- **Fast Performance**: Optimized loading times and smooth user experience
- **SEO Friendly**: Proper meta tags and semantic HTML structure

## 🚀 Tech Stack

- **Frontend**: React 18+
- **Styling**: CSS3 / Styled Components / Tailwind CSS
- **Build Tool**: Vite / Create React App
- **Deployment**: Netlify / Vercel / GitHub Pages
- **Version Control**: Git & GitHub

## 📦 Installation

1. Clone the repository:
```bash
git clone https://github.com/yourusername/portfolio-website.git
cd portfolio-website
```

2. Install dependencies:
```bash
npm install
```

3. Start the development server:
```bash
npm start
```

4. Open [http://localhost:3000](http://localhost:3000) to view it in the browser.

## 🛠️ Available Scripts

- `npm start` - Runs the app in development mode
- `npm test` - Launches the test runner
- `npm run build` - Builds the app for production
- `npm run eject` - Ejects from Create React App (one-way operation)

## 📁 Project Structure

```
portfolio-website/
├── public/
│   ├── index.html
│   └── favicon.ico
├── src/
│   ├── components/
│   │   ├── Header/
│   │   ├── Hero/
│   │   ├── About/
│   │   ├── Projects/
│   │   ├── Skills/
│   │   ├── Contact/
│   │   └── Footer/
│   ├── assets/
│   │   ├── images/
│   │   └── icons/
│   ├── styles/
│   ├── utils/
│   ├── App.js
│   └── index.js
├── package.json
└── README.md
```

## 🎨 Customization

### Adding New Projects

1. Navigate to `src/data/projects.js`
2. Add your project object with the following structure:
```javascript
{
  id: 'unique-id',
  title: 'Project Title',
  description: 'Brief project description',
  technologies: ['React', 'CSS', 'JavaScript'],
  image: '/path/to/image.jpg',
  liveUrl: 'https://project-live-url.com',
  githubUrl: 'https://github.com/username/project'
}
```

### Updating Personal Information

- Edit `src/data/personal.js` to update your personal information
- Replace images in `src/assets/images/` with your own photos
- Update the resume link in the hero section

### Styling

- Global styles: `src/styles/globals.css`
- Component-specific styles: Located in each component folder
- Color scheme: Modify CSS custom properties in `globals.css`

## 🚀 Deployment

### Netlify

1. Build the project: `npm run build`
2. Drag and drop the `build` folder to [Netlify](https://netlify.com)

### Vercel

1. Install Vercel CLI: `npm i -g vercel`
2. Run: `vercel`
3. Follow the prompts

### GitHub Pages

1. Install gh-pages: `npm install --save-dev gh-pages`
2. Add to package.json scripts:
```json
"predeploy": "npm run build",
"deploy": "gh-pages -d build"
```
3. Run: `npm run deploy`

## 📱 Responsive Breakpoints

- Mobile: 320px - 768px
- Tablet: 768px - 1024px
- Desktop: 1024px+

## 🔧 Performance Optimizations

- Lazy loading for images
- Code splitting with React.lazy()
- Optimized bundle size
- Compressed assets
- Efficient re-rendering with React.memo

## 🤝 Contributing

1. Fork the repository
2. Create a feature branch: `git checkout -b feature/new-feature`
3. Commit your changes: `git commit -m 'Add new feature'`
4. Push to the branch: `git push origin feature/new-feature`
5. Open a Pull Request

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 📞 Contact

- **Email**: your.email@example.com
- **LinkedIn**: [Your LinkedIn Profile](https://linkedin.com/in/yourprofile)
- **GitHub**: [Your GitHub Profile](https://github.com/yourusername)
- **Portfolio**: [Live Website](https://yourportfolio.com)

## 🙏 Acknowledgments

- Design inspiration from [Dribbble](https://dribbble.com)
- Icons from [React Icons](https://react-icons.github.io/react-icons/)
- Fonts from [Google Fonts](https://fonts.google.com)

---

⭐ If you found this project helpful, please give it a star on GitHub!