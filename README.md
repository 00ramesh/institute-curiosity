# Curiosity Institute - Professional Coaching Website

A modern, professional, and responsive website for Curiosity Institute coaching services built with HTML5, CSS3, and JavaScript.

## 📋 Project Structure

```
institute/
├── index.html           # Home page
├── classes.html         # Classes & Programs page
├── team.html           # Our Team page
├── about.html          # About Us page
├── contact.html        # Contact Us page
├── css/
│   └── style.css       # Main stylesheet (responsive design)
├── js/
│   └── script.js       # JavaScript for interactivity
└── README.md           # This file
```

## 🎨 Features

### Pages Included:
1. **Home Page** - Eye-catching hero section with key features and statistics
2. **Classes Page** - Comprehensive course listing with filtering by category
3. **Our Team Page** - Team members showcase with professional profiles
4. **About Us Page** - Company mission, vision, values, and achievements
5. **Contact Us Page** - Contact form, office hours, FAQ, and location info

### Design Features:
- ✨ Modern gradient color scheme (Purple/Indigo/Pink)
- 📱 Fully responsive mobile-first design
- 🎯 Smooth animations and transitions
- 🧭 Sticky navigation header
- 🔍 Intersection observer for scroll animations
- 🌙 Professional typography and spacing
- 📊 Interactive class filtering
- 🎨 Beautiful card layouts and grids

## 🚀 Getting Started

### Option 1: Local File System
1. Open `index.html` in your web browser
2. Navigate through pages using the top navigation menu

### Option 2: Web Server (Recommended)
1. Place the `institute` folder in your web server's root directory
2. Access via `http://localhost/institute`

### Option 3: Live Server (VS Code)
1. Install the "Live Server" extension
2. Right-click on `index.html` and select "Open with Live Server"

## 🖼️ Images

All images are stored locally in the `images/` directory. The website includes:

- Hero/banner images for each page
- Team member photos
- Feature card images
- Course card images
- Background images for sections

Image files:
- `hero-professionals.jpg` - Professional team and community
- `hero-data-science.jpg` - Technology and data science
- `hero-learning.jpg` - Education and learning themes
- `hero-contact.jpg` - Communication themes
- `team-sarah.jpg`, `team-michael.jpg` - Team member photos
- `feature-*.jpg`, `course-*.jpg` - Feature and course images

To replace images, simply substitute the files in the `images/` folder with your own images of the same filename.

## 🎯 Customization Guide

### Change Colors
Edit the CSS variables in `css/style.css`:
```css
:root {
  --primary-color: #E8DCC8;
  --secondary-color: #D4C5B9;
  --accent-color: #C19A6B;
  /* ... other colors ... */
}
```

### Update Company Information
Replace these throughout the HTML files:
- Company name: "Curiosity Institute"
- Email: "info@curiosityinstitute.com"
- Phone: "+1 (555) 123-4567"
- Address: "123 Learning Street, Education City, EC 12345"

### Add/Remove Classes
Edit `classes.html` and add/remove `.card` elements with:
- Class name and description
- Duration, format, and level
- Price
- Image URL

### Update Team Members
Edit `team.html` to modify team member cards with:
- Photo URL
- Name and role
- Bio description
- Social media links

### Customize Forms
The contact form in `contact.html` includes validation. To integrate with a backend:
1. Modify the form action/method
2. Update JavaScript in `js/script.js` form submission handler

## 📱 Responsive Design

The website is fully responsive across:
- 📱 Mobile devices (320px and up)
- 📱 Tablets (768px and up)
- 💻 Desktops (1024px and up)
- 🖥️ Large screens (1200px and up)

## 🎮 Interactive Features

### Mobile Menu
- Hamburger menu appears on screens < 768px
- Click icon to toggle navigation
- Auto-closes when a link is clicked

### Class Filtering
- Filter classes by category on the Classes page
- Smooth animations when filtering
- All categories visible by default

### Form Validation
- Name, email, and message fields are required
- Email format validation
- Success message on submission
- Error alerts for incomplete forms

### Scroll Animations
- Elements fade in as they come into view
- Counter animations for statistics
- Smooth scroll behavior for anchor links

## 🔧 Browser Support

- ✅ Chrome/Edge (latest)
- ✅ Firefox (latest)
- ✅ Safari (latest)
- ✅ Mobile browsers (iOS Safari, Chrome Mobile)

## 📊 Performance

- Lightweight CSS (no frameworks)
- Vanilla JavaScript (no dependencies)
- Optimized images from Pexels
- Fast load times
- SEO-friendly structure

## 🎓 Navigation

All pages have a consistent header with:
- Logo/Brand name
- Navigation links to all pages
- Mobile-responsive hamburger menu
- Sticky positioning for easy access

Footer appears on all pages with:
- About section
- Quick links
- Contact information
- Social media links
- Copyright information

## 📝 File Descriptions

| File | Purpose |
|------|---------|
| `index.html` | Home page with hero and features |
| `classes.html` | Classes page with filtering |
| `team.html` | Team member showcase |
| `about.html` | Company info and values |
| `contact.html` | Contact form and info |
| `css/style.css` | All styles and responsive design |
| `js/script.js` | Interactive features and validation |

## 🔐 Security Notes

- Contact form is client-side only (for demo purposes)
- To handle real submissions, implement backend validation
- Add CSRF protection for production
- Use HTTPS in production environment

## 📄 License

This website template is created for Curiosity Institute. Feel free to customize and use for your coaching business.

## 💡 Tips for Enhancement

1. **Add Testimonials** - Create a new section with student success stories
2. **Pricing Tables** - Add detailed pricing comparison tables
3. **Video Content** - Embed coaching videos or testimonial videos
4. **Blog Section** - Add a blog for articles and insights
5. **Search Functionality** - Implement class search feature
6. **User Accounts** - Add login/registration system
7. **Payment Integration** - Connect with Stripe or PayPal
8. **Email Integration** - Use services like Formspree or EmailJS

## 🚀 Deployment

### GitHub Pages
1. Create a GitHub repository
2. Push this folder to the repository
3. Enable GitHub Pages in settings
4. Website will be live at `https://yourusername.github.io/institute`

### Netlify
1. Connect your GitHub repository
2. Set build command: (leave blank)
3. Set publish directory: (leave blank)
4. Deploy!

### Traditional Hosting
1. Upload files to your web server via FTP
2. Ensure all files maintain their folder structure
3. Make sure server supports HTML/CSS/JS

## 📞 Support

For questions or customizations, refer to the inline comments in:
- `css/style.css` - Styling structure
- `js/script.js` - Function documentation

---

**Created for Curiosity Institute** | A Modern Coaching Platform for Professional Development
