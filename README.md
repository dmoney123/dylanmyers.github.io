# Dylan Myers - Engineering & AI Portfolio

A modern, responsive portfolio website showcasing engineering and AI projects, built with Next.js, TypeScript, and Tailwind CSS.

## Features

- **Responsive Design**: Optimized for all devices and screen sizes
- **Modern UI/UX**: Clean, professional design with smooth animations
- **Project Showcase**: Interactive project gallery with filtering and detailed views
- **Skills Section**: Comprehensive technical skills with progress indicators
- **Contact Form**: Functional contact form with validation
- **SEO Optimized**: Meta tags and structured data for better search visibility
- **Performance**: Fast loading times and optimized images

## Technologies Used

- **Frontend**: Next.js 15, React 19, TypeScript
- **Styling**: Tailwind CSS
- **Icons**: Heroicons
- **Deployment**: Vercel (recommended)

## Getting Started

1. Clone the repository:
```bash
git clone <your-repo-url>
cd portfolio
```

2. Install dependencies:
```bash
npm install
```

3. Run the development server:
```bash
npm run dev
```

4. Open [http://localhost:3000](http://localhost:3000) in your browser.

## Customization

### Personal Information
Update the following files with your information:
- `src/app/layout.tsx` - Meta tags and site title
- `src/components/Hero.tsx` - Name, roles, and introduction
- `src/components/About.tsx` - Personal story and statistics
- `src/components/Contact.tsx` - Contact information and social links

### Projects
Edit `src/components/Projects.tsx` to add your projects:
- Update the `projects` array with your project details
- Add project images to the `public` folder
- Update GitHub and demo URLs

### Skills
Modify `src/components/Skills.tsx` to reflect your technical skills:
- Update skill categories and proficiency levels
- Add or remove technologies as needed

### Styling
Customize the design in:
- `tailwind.config.js` - Color scheme and theme
- `src/app/globals.css` - Global styles and fonts

## Deployment

### Vercel (Recommended)
1. Push your code to GitHub
2. Connect your repository to Vercel
3. Deploy with zero configuration

### Other Platforms
The site can be deployed to any platform that supports Next.js:
- Netlify
- AWS Amplify
- Railway
- DigitalOcean App Platform

## License

MIT License - feel free to use this template for your own portfolio!

## Contact

Dylan Myers - dylan.myers@university.edu
LinkedIn: [linkedin.com/in/yourusername](https://linkedin.com/in/yourusername)
GitHub: [github.com/yourusername](https://github.com/yourusername)
