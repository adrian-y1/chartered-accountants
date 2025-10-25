# Chartered Accountants Website

A professional, responsive website for an accounting firm built with Bootstrap 5, SCSS, and modern web technologies.

## Features

- **Responsive Design**: Mobile-first approach using Bootstrap 5
- **Professional Styling**: Clean, modern design with custom SCSS variables
- **Contact Form**: Interactive contact form with validation
- **Services Showcase**: Detailed services section with icon cards
- **Smooth Navigation**: Fixed navbar with smooth scrolling
- **SEO Optimized**: Proper meta tags and semantic HTML

## Technologies Used

- HTML5
- CSS3 / SCSS
- Bootstrap 5.3.2
- JavaScript (ES6+)
- Font Awesome 6.4.0

## Project Structure

```
Grant Pettitt Accounting/
├── index.html          # Main HTML file
├── css/
│   ├── style.scss      # SCSS source file with variables
│   └── style.css       # Compiled CSS file
├── js/
│   └── script.js       # Custom JavaScript
├── images/
│   └── README.md       # Image requirements and guidelines
└── README.md           # This file
```

## Setup Instructions

1. **Clone or Download** the project files
2. **Add Images**:
   - Add your logo as `images/logo.png`
   - Add a hero image as `images/accounting-hero.jpg`
   - See `images/README.md` for detailed requirements
3. **Customize Content**: Edit `index.html` to update:
   - Company information
   - Contact details
   - Services offered
   - About section content

## Customization

### Colors

All colors are defined as SCSS variables in `css/style.scss`:

- `$primary-color`: #1e3a8a (Professional blue)
- `$secondary-color`: #64748b (Slate gray)
- `$accent-color`: #0f766e (Teal accent)

### Content Areas to Update

1. **Company Information** (lines 20-22 in index.html):

   - Company name
   - Logo path
   - Navigation items

2. **Hero Section** (lines 44-65):

   - Main headline
   - Description text
   - Call-to-action buttons

3. **About Section** (lines 76-105):

   - Company description
   - Years of experience
   - Key selling points

4. **Services** (lines 120-195):

   - Service descriptions
   - Icons (Font Awesome classes)
   - Service details

5. **Contact Information** (lines 212-240):
   - Name and credentials
   - Phone number
   - Email address
   - Mailing address

## Deployment to GitHub Pages

1. **Create a GitHub Repository**
2. **Upload all files** to the repository
3. **Enable GitHub Pages**:
   - Go to repository Settings
   - Scroll to "Pages" section
   - Select "Deploy from a branch"
   - Choose "main" branch and "/ (root)" folder
   - Click Save
4. **Access your site** at: `https://yourusername.github.io/repository-name`

## SCSS Compilation

If you make changes to `style.scss`, you'll need to compile it to CSS:

### Option 1: Use VS Code Extension

- Install "Live Sass Compiler" extension
- Right-click on `style.scss` and select "Watch Sass"

### Option 2: Use Node.js/npm

```bash
npm install -g sass
sass css/style.scss css/style.css --watch
```

### Option 3: Online Compiler

- Use online SCSS compilers like sassmeister.com
- Copy compiled CSS to `style.css`

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers

## Contact Form Integration

The contact form currently shows an alert on submission. For production use, integrate with:

- Formspree.io
- Netlify Forms
- EmailJS
- Custom backend API

## License

This project is open source and available under the [MIT License](LICENSE).

## Support

For questions or support, please contact the development team.
