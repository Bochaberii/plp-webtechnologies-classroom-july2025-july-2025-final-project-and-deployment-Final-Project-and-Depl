# 🌟 Sandra's Portfolio Website

A clean, modern, and responsive portfolio website showcasing Sandra's journey as an electrical engineering student with interests in IoT, web development, and UI/UX design.

## 🚀 Live Demo

[Visit the live website](https://your-vercel-url.vercel.app)

## ✨ Features

- **Responsive Design** - Works perfectly on desktop, tablet, and mobile
- **Modern UI** - Clean and professional design with smooth animations
- **Fast Loading** - Optimized images and minimal CSS for quick load times
- **SEO Friendly** - Proper HTML structure and meta tags
- **Easy to Deploy** - Ready for Vercel, Netlify, or any static hosting

## 📁 Project Structure

```
📦 Sandra's Portfolio
├── 📄 index.html              # Homepage
├── 📄 about.html              # About page with hobbies & interests
├── 📄 contact.html            # Contact information
├── 📄 package.json            # Project configuration
├── 📄 vercel.json             # Vercel deployment settings
├── 📄 favicon.ico             # Website icon
├── 📄 README.md               # Project documentation
└── 📂 assets/                 # All website assets
    ├── 📂 css/                # Styles
    │   └── styles.css         # Single consolidated stylesheet
    ├── 📂 js/                 # JavaScript
    │   └── script.js          # Interactive functionality
    └── 📂 images/             # Organized images
        ├── 📂 hobbies/        # Hobby section images
        │   ├── art.jpg        # Art & Design
        │   ├── biking.jpg     # Biking
        │   └── swimming.jpg   # Swimming
        ├── 📂 interests/      # Professional interests
        │   ├── iot.jpg        # IoT & Electronics
        │   ├── webb.jpg       # Web Development
        │   └── ui.jpg         # UI/UX Design
        ├── 📂 favorites/      # Slideshow content
        │   ├── movie.jpg      # Favorite movies
        │   ├── seris.jpg      # TV series
        │   ├── novels.jpg     # Books
        │   ├── john green.jpg # John Green books
        │   ├── food.jpg       # Favorite foods
        │   └── drinks.jpg     # Favorite drinks
        └── me.jpg             # Main profile photo
```

## 🎨 Pages

### Homepage (`index.html`)

- Hero section with introduction
- Call-to-action buttons
- Professional profile photo
- Social media links

### About (`about.html`)

- Personal introduction
- Hobbies showcase with hover effects
- Professional interests section
- Interactive slideshow of favorites

### Contact (`contact.html`)

- Contact form (frontend only)
- Contact information
- Responsive design

## 🛠️ Technologies Used

- **HTML5** - Semantic markup
- **CSS3** - Modern styling with Flexbox and Grid
- **JavaScript** - Interactive slideshow and animations
- **Font Awesome** - Social media icons
- **Google Fonts** - Poppins font family

## 📱 Responsive Design

The website is fully responsive and tested on:

- Desktop (1200px+)
- Laptop (768px - 1199px)
- Tablet (481px - 767px)
- Mobile (320px - 480px)

## 🚀 Deployment

### Vercel (Recommended)

1. Connect your GitHub repository to Vercel
2. Vercel will automatically detect it's a static site
3. Deploy with zero configuration needed

### Other Platforms

- **Netlify**: Drag and drop the project folder
- **GitHub Pages**: Push to `gh-pages` branch
- **Surge.sh**: `surge` command in project directory

## 📋 Getting Started

1. **Clone the repository**

   ```bash
   git clone https://github.com/yourusername/portfolio
   cd portfolio
   ```

2. **Open locally**

   ```bash
   # Simple HTTP server
   python -m http.server 8000
   # or
   npx serve .
   ```

3. **Open in browser**
   ```
   http://localhost:8000
   ```

## 🎯 Performance

- ✅ Optimized images (proper sizing and formats)
- ✅ Minified CSS (single file, no dependencies)
- ✅ Fast loading (minimal HTTP requests)
- ✅ SEO optimized (semantic HTML, meta tags)
- ✅ Accessibility friendly (proper contrast, alt tags)

## 🔧 Customization

### Colors

Update CSS variables in `assets/css/styles.css`:

```css
:root {
  --primary-color: #ae55f7;
  --primary-color-dark: #9333ea;
  --text-dark: #1f2937;
  --text-light: #6b7288;
}
```

### Content

- Edit HTML files directly
- Replace images in `assets/images/`
- Update contact information in `contact.html`

### Styling

All styles are in one file: `assets/css/styles.css`

- Base styles and variables
- Navigation and layout
- Page-specific styles
- Responsive breakpoints

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

## 👩‍💻 About Sandra

Electrical Engineering student at JKUAT with a passion for:

- Internet of Things (IoT) and Electronics
- Web Development
- UI/UX Design
- Art and Creative Expression

---

**Made with ❤️ by Sandra** | **2024**
└── 📂 images/ # All images organized by category
├── 📂 hobbies/ # Hobby-related images
│ ├── art.jpg
│ ├── biking.jpg
│ └── swimming.jpg
├── 📂 interests/ # Interest/skill images
│ ├── iot.jpg
│ ├── webb.jpg
│ ├── ui.jpg
│ └── web.jpg
├── 📂 favorites/ # Slideshow images (movies, books, food, etc.)
│ ├── movie.jpg
│ ├── seris.jpg
│ ├── novels.jpg
│ ├── john green.jpg
│ ├── food.jpg
│ └── drinks.jpg
├── me.jpg # Profile photo
└── mrembo.jpeg # Additional profile image

````

## 🛠️ Technologies Used

- **HTML5** - Semantic markup and structure
- **CSS3** - Custom styling and animations
- **JavaScript** - Interactive elements and slideshow
- **Tailwind CSS** - Utility-first CSS framework
- **Font Awesome** - Icons and social media icons
- **Remix Icons** - Additional icon set

## 🌐 Features

- **Responsive Design** - Works on all device sizes
- **Interactive Slideshow** - Showcase of favorite movies, books, and food
- **Smooth Animations** - CSS transitions and hover effects
- **Clean Navigation** - Easy-to-use menu system
- **Contact Form** - Ready for integration with form services

## 🚀 Deployment

This website is optimized for deployment on **Vercel**:

1. Push to GitHub repository
2. Connect to Vercel
3. Deploy automatically

### Build Commands

```bash
# Install dependencies
npm install

# Build Tailwind CSS
npm run build

# Watch for changes (development)
npm run watch
````

## 📝 Content Sections

### Home Page

- Personal introduction
- Call-to-action buttons
- Professional summary

### About Page

- Personal background
- **Hobbies Section**: Art & Design, Biking, Swimming
- **Interests Section**: IoT & Electronics, Web Development, UI/UX Design
- **Favorites Slideshow**: Movies, Series, Books, Food, Drinks

### Contact Page

- Contact form (ready for backend integration)
- Direct contact information
- Social media links

## 🎨 Design Philosophy

The website follows a modern, clean design with:

- Purple accent color (#800080) for headings
- Responsive grid layouts
- Card-based content organization
- Smooth hover effects and transitions
- Mobile-first responsive design

## 🔧 Customization

To customize the website:

1. **Colors**: Update CSS custom properties in `assets/css/style.css`
2. **Content**: Edit HTML files directly
3. **Images**: Replace images in appropriate `assets/images/` subdirectories
4. **Styles**: Modify CSS files in `assets/css/`

## 📱 Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

## 👩‍💼 About Sandra

Electrical Engineering student at JKUAT with passion for:

- Internet of Things (IoT)
- Web Development
- UI/UX Design
- Art & Creative Design

---

**Copyright © 2024 - Designed by Sandra**

You're now ready to bring everything together—HTML, CSS, JavaScript, planning, structure, and deployment. This final project challenges you to **conceptualize, build, and deploy a multi-page website** that is responsive, interactive, and ready for the real world.

This assignment will guide you from planning your site all the way to deploying it online. Let’s make your project _production-worthy_! 🚀

---

## 🌐🎯 Part 1: Planning and Organizing a Multipage Website

Before you write any code, take time to plan:

- Define your website's purpose (portfolio, product showcase, blog, etc.)
- Outline 3–5 pages (e.g., Home, About, Services, Contact, Gallery)
- Sketch or describe the layout of each page
- Map out internal navigation (how pages link to one another)

**Goal:** Show intentional structure and user journey across the site.

---

## 🌍💻 Part 2: Build the Website Using HTML5, CSS, and JavaScript

Using your plan, begin building:

- Use HTML5 for semantic structure
- Apply CSS for responsive layout, styling, and animations
- Use JavaScript to add interactivity (menus, forms, toggles, dynamic content)

Each page should:

- Be mobile-responsive
- Share a consistent layout/header/footer
- Include at least one interactive element (e.g., form validation, toggle menu, animation on scroll)

**Goal:** Integrate everything you’ve learned in a cohesive, functioning project.

---

## 🛠️🚀 Part 3: Best Practices for Code Organization

Before deployment, refactor your project to follow production-friendly practices:

- Organize files in folders (`/css`, `/js`, `/images`, etc.)
- Write clean, modular, and commented code
- Use meaningful file names and relative paths
- Validate your HTML/CSS and test on different screen sizes

**Goal:** Prepare your codebase to be readable, maintainable, and scalable.

---

## 🌐🚀 Part 4: Introduction to Hosting and Deployment

Once your project is complete, choose a method to **host your site online**.

You can use:

- **GitHub Pages** (great for portfolios and static sites)
- **Netlify** (powerful CI/CD features and easy form support)
- **Vercel** (lightning-fast deployment for frontend projects)

Deploy your project and confirm that:

- All links and scripts work
- It loads properly on mobile and desktop
- It has a clear, shareable URL

**Goal:** Publish your work online and make it accessible to the world.

---

## Deliverables

1. A GitHub repository containing:

   - Your complete project code, properly organized
   - A `README.md` file explaining your project purpose, structure, and live URL

2. A live deployed website (hosted via GitHub Pages, Netlify, or Vercel)

---

## Outcome

- Clarity and thoroughness of planning documentation
- Proper use of HTML5, CSS, and JavaScript across multiple pages
- Responsive and accessible design
- Clean, well-organized, and commented code
- Successful live deployment with a working link
- Evidence of following best practices
