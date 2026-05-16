# Lawyer Website

Professional website for an advocate/lawyer based in Kanpur, India. This website is designed to showcase legal services, build trust with potential clients, and provide an easy way for visitors to contact the lawyer.

## Features

- **Responsive Design**: Works seamlessly on desktop, tablet, and mobile devices
- **Modern UI**: Clean, professional interface with a navy blue and gold color scheme
- **Service Showcase**: Highlights legal services offered
- **Case Studies**: Demonstrates successful case outcomes
- **Contact Form**: Integrated with EmailJS for client inquiries
- **Mobile Navigation**: Hamburger menu for mobile devices
- **SEO Optimized**: Built with best practices for search engine visibility

## Pages

1. **Home** (`index.html`) - Landing page with hero section, about, services, and contact
2. **About** (`about.html`) - Lawyer profile, experience, and credentials
3. **Services** (`services.html`) - Detailed list of legal services offered
4. **Case Studies** (`case-studies.html`) - Success stories and case outcomes
5. **Contact** - Integrated contact form for client inquiries

## Tech Stack

- **HTML5** - Semantic markup
- **Tailwind CSS** - Utility-first CSS framework for rapid development
- **EmailJS** - Client-side email delivery for contact form
- **JavaScript** - Interactive elements and form handling

## Setup

### Prerequisites
- A modern web browser (Chrome, Firefox, Safari, Edge)
- A code editor (VS Code, Sublime Text, etc.)

### Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/Azazel49/Lawyer-Website.git
   ```
2. Navigate to the project directory:
   ```bash
   cd Lawyer-Website
   ```
3. Open `index.html` in your browser to view the website.

### EmailJS Configuration (Optional)
To enable the contact form functionality, you need to configure EmailJS:

1. Sign up for an EmailJS account at [emailjs.com](https://www.emailjs.com/)
2. Create a service and template in the EmailJS dashboard
3. Update the `index.html` file with your EmailJS credentials:
   ```javascript
   emailjs.sendForm('YOUR_SERVICE_ID', 'YOUR_TEMPLATE_ID', this)
   ```
4. Include the EmailJS SDK script in the `<head>` section:
   ```html
   <script src="https://cdnjs.cloudflare.com/ajax/libs/emailjs-com/2.6.0/email.min.js"></script>
   ```

## Usage

### Local Development
1. Open `index.html` in your browser
2. Navigate through the pages using the navigation menu
3. Test the contact form by filling out the fields and submitting

### Deployment
The website is fully static and can be deployed to any static hosting service:

- **GitHub Pages**: Enable GitHub Pages in repository settings
- **Netlify**: Drag and drop the folder onto Netlify
- **Vercel**: Deploy with a single command
- **Any web server**: Copy files to your server's public directory

## Customization

### Update Content
- Replace placeholder text with your actual content
- Update lawyer name, credentials, and contact information
- Add real case studies and testimonials

### Modify Design
- Change colors in the Tailwind configuration (or use utility classes)
- Update typography by changing font families
- Adjust layout by modifying Tailwind classes

### Add New Pages
1. Create a new HTML file (e.g., `blog.html`)
2. Copy the header and footer from an existing page
3. Add your content in the main section
4. Update the navigation menu to include the new page

## Contributing

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Contact

For questions or support, please contact:
- Email: [your-email@example.com](mailto:your-email@example.com)
- Phone: [Your Phone Number]
- Address: [Your Office Address]

## Acknowledgments

- [Tailwind CSS](https://tailwindcss.com/) - For the amazing CSS framework
- [EmailJS](https://www.emailjs.com/) - For the email delivery service
- [Font Awesome](https://fontawesome.com/) - For icons (if used)

---

> **Note**: This website is a template. Please ensure you comply with all applicable laws and regulations regarding legal advertising in your jurisdiction.