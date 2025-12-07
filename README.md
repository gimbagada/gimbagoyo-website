# Gimba Goyo Personal Website

Personal website for Gimba Goyo - Strategic Leadership Executive, Pharmacist, and WASH Expert committed to humanitarian causes.

## Overview

This is the official personal website for Gimba Goyo (Gimbo), showcasing professional achievements, humanitarian work, and personal milestones. The website serves as a digital portfolio and platform for connecting with colleagues, partners, and the community.

## Features

- **Professional Profile**: Comprehensive overview of career and expertise
- **50th Birthday Celebration**: Special section commemorating this milestone
- **Animated CV/Resume**: Interactive and engaging presentation of professional experience
- **LinkedIn Integration**: Direct connection to professional network
- **Responsive Design**: Optimized for all devices and screen sizes
- **Modern UI**: Built with contemporary web technologies

## Tech Stack

- **Vite** - Next-generation frontend tooling
- **JavaScript** - Core programming language
- **HTML5** - Semantic markup
- **CSS3** - Modern styling
- **pnpm** - Fast, disk space efficient package manager

## Project Structure

```
gimbagoyo-website/
├── src/              # Source files
├── public/           # Static assets
├── index.html        # Entry HTML file
├── package.json      # Dependencies and scripts
├── vite.config.js    # Vite configuration
└── components.json   # UI components configuration
```

## Installation

### Prerequisites

- Node.js 18+
- pnpm (or npm/yarn)

### Setup

1. Clone the repository:
```bash
git clone https://github.com/gimbagada/gimbagoyo-website.git
cd gimbagoyo-website
```

2. Install dependencies:
```bash
pnpm install
# or
npm install
```

3. Start development server:
```bash
pnpm dev
# or
npm run dev
```

The website will be available at `http://localhost:5173`

## Available Scripts

- `pnpm dev` - Start development server
- `pnpm build` - Build for production
- `pnpm preview` - Preview production build locally
- `pnpm lint` - Run ESLint for code quality

## Deployment

### Netlify Deployment (Recommended)

1. Push your code to GitHub
2. Connect your repository to Netlify
3. Configure build settings:
   - **Build command**: `pnpm build` or `npm run build`
   - **Publish directory**: `dist`
4. Deploy!

### Manual Deployment

1. Build the project:
```bash
pnpm build
```

2. Upload the `dist` folder to your hosting provider

### Custom Domain

To use a custom domain (e.g., gimbagoyo.com):

1. Register your domain with a registrar (Namecheap, GoDaddy, etc.)
2. Configure DNS settings to point to your hosting provider
3. Update hosting provider with custom domain
4. Enable HTTPS/SSL certificate

## Content Sections

### Professional Profile
- Career overview
- Areas of expertise
- Professional achievements
- Current role and responsibilities

### 50th Birthday Celebration
- Milestone commemoration
- Photo gallery
- Messages and tributes
- Event highlights

### Animated CV/Resume
- Interactive timeline
- Work experience
- Education
- Skills and certifications
- LinkedIn integration

## Customization

### Updating Content

1. Edit source files in the `src` directory
2. Update images in the `public` directory
3. Modify styling in CSS files
4. Test changes locally with `pnpm dev`
5. Build and deploy

### Styling

The website uses modern CSS with:
- Responsive design principles
- Mobile-first approach
- Smooth animations and transitions
- Accessible color schemes

## Contributing

While this is a personal website, suggestions and improvements are welcome! Please see [CONTRIBUTING.md](CONTRIBUTING.md) for details.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Contact

- **Name**: Gimba Goyo (Gimbo)
- **Email**: gimbagada@gmail.com
- **Location**: Abuja, Nigeria
- **Company**: Thermometer & Thermostat Consults
- **LinkedIn**: [Connect on LinkedIn](https://linkedin.com)
- **GitHub**: [@gimbagada](https://github.com/gimbagada)

## About Gimba Goyo

Gimba Goyo is a passionate Pharmacist and WASH Expert with a strong commitment to humanitarian causes. With expertise in strategic leadership and community development, Gimbo has dedicated his career to building a better world through healthcare innovation and sustainable development initiatives.

**Professional Focus:**
- Healthcare and pharmaceutical services
- Water, Sanitation, and Hygiene (WASH) programs
- Monitoring, Evaluation, Accountability, and Learning (MEAL)
- Humanitarian response and development
- Strategic leadership and organizational development

## Acknowledgments

- Thanks to the open-source community for excellent tools
- Gratitude to colleagues and partners for their support
- Special thanks to family and friends for their encouragement
