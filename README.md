# Vpk-mart

VPK Mart is a modern, responsive grocery store website built with HTML, CSS (via Tailwind CSS), and JavaScript. The website provides customers with an online presence for browsing products, reading informative blog content, and contacting the business.

## Features

### Homepage
- Modern, responsive design with Tailwind CSS
- Hero section with call-to-action buttons
- Key features highlighting fresh produce, daily essentials, and contactless delivery
- Customer testimonials for social proof
- Consistent navigation across all pages

### Products Page
- Dynamic product listing with images, descriptions, and pricing
- Product quality indicators and customer ratings
- Top customer reviews display
- Special offers banner
- Search and filtering capabilities

### Blog
- Informative articles on healthy eating, local farming, and sustainability
- Individual blog post pages with detailed content
- **User review system** - Visitors can rate and review blog posts
- Popular posts section
- Category filtering
- Newsletter subscription

### Contact Page
- Contact form with name, email, subject, and message fields
- Detailed contact information with icons
- FAQ section with expandable answers
- Store location information
- Customer service details

## Technical Details

### Technologies Used
- HTML5
- CSS (Tailwind CSS CDN)
- JavaScript (Vanilla)
- Font Awesome for icons

### Design Features
- Responsive layout that works on mobile, tablet, and desktop
- Consistent color scheme with green as the primary brand color
- Professional typography and spacing
- Interactive elements with hover effects
- Image fallback system for graceful degradation

### File Structure
```
├── index.html          # Homepage
├── products.html       # Products listing page
├── blog.html           # Blog listing page
├── blog-post.html      # Individual blog post pages
├── contact.html        # Contact page
├── README.md           # This file
└── assets/             # Images and other media
    ├── apple.jpg
    ├── banana.jpg
    ├── blog1.jpg
    ├── blog2.jpg
    ├── bread.jpg
    ├── broccoli.jpg
    ├── carrot.jpg
    ├── cooking.jpg
    ├── eggs.jpg
    ├── farm-fresh.jpg
    ├── grapes.jpg
    ├── healthy-eating.jpg
    ├── hero.jpg
    ├── milk.jpg
    ├── onion.jpg
    ├── orange.jpg
    ├── organic-farming.jpg
    ├── potato.jpg
    ├── rice.jpg
    ├── strawberry.jpg
    ├── sugar.jpg
    ├── team.jpg
    ├── tomato.jpg
    └── watermelon.jpg
```

## Getting Started

### Prerequisites
- A modern web browser (Chrome, Firefox, Safari, Edge)

### Installation
1. Clone or download the repository
2. Open `index.html` in your web browser to view the homepage
3. Navigate through the site using the navigation menu

### Development
- Edit HTML files directly with any text editor
- Changes can be viewed by refreshing the browser
- No build process required

## Blog Functionality

The blog section includes enhanced features:

### Reading Articles
- Click "Read More" on any blog post to view the full article
- Each article has its own dedicated page with detailed content
- Related articles are suggested in the sidebar

### User Reviews
- Visitors can leave star ratings (1-5 stars) for blog posts
- Written reviews can be submitted with the reviewer's name
- All reviews are displayed below the article content
- Reviews are sorted chronologically

### Content Management
- Blog posts are managed through JavaScript objects in the HTML files
- Adding new posts requires updating the posts array in `blog.html` and `blog-post.html`
- Images are automatically handled with fallback mechanisms

## Image Handling

All images include fallback mechanisms:
- If a specific image fails to load, a default image is displayed
- Primary fallback: `hero.jpg`
- Secondary fallbacks: `blog1.jpg`, `blog2.jpg`

## Customization

### Colors
The primary color scheme uses various shades of green:
- Primary: `green-700` for headers and buttons
- Secondary: `green-800` for darker elements
- Accents: `green-100` and `green-500` for highlights

### Fonts
The site uses the default Tailwind CSS font stack which includes:
- System UI fonts for optimal performance
- Automatic fallbacks for cross-platform compatibility

## Browser Support

The website works on all modern browsers:
- Chrome 60+
- Firefox 55+
- Safari 12+
- Edge 79+

## Contributing

1. Fork the repository
2. Create a feature branch
3. Commit your changes
4. Push to the branch
5. Create a pull request

## License

This project is open source and available under the MIT License.

## Contact

For support or inquiries, please use the contact form on the website or reach out directly to:
- support@vpkmart.com
- +91 98765 43210

---

© 2025 VPK Mart. All rights reserved.