# ASTRA Website

This is the official website for ASTRA (Autonomous Spatial-Temporal Red-teaming for AI Software Assistants).

## 🚀 Features

- **Modern Design**: Clean, responsive design with gradient backgrounds and smooth animations
- **Mobile Friendly**: Optimized for all device sizes
- **Fast Loading**: Lightweight and optimized for performance
- **SEO Ready**: Proper meta tags and structured content

## 📁 Structure

```
website/
├── index.html          # Main homepage
├── assets/             # Images and other assets
│   └── wf.png         # System overview diagram
└── .github/workflows/  # GitHub Actions for deployment
    └── deploy.yml     # Automatic deployment workflow
```

## 🛠️ Deployment

### Automatic Deployment (Recommended)

1. **Enable GitHub Pages**:
   - Go to your repository settings
   - Navigate to "Pages" section
   - Set source to "GitHub Actions"

2. **Push to Main Branch**:
   - The website will automatically deploy when you push to the main branch
   - GitHub Actions will build and deploy the site

### Manual Deployment

1. **Clone the repository**:
   ```bash
   git clone https://github.com/PurCL/astra-share.git
   cd astra-share/website
   ```

2. **Serve locally** (for testing):
   ```bash
   python -m http.server 8000
   # Then visit http://localhost:8000
   ```

3. **Deploy to GitHub Pages**:
   - The `.github/workflows/deploy.yml` file handles automatic deployment
   - Just push your changes to the main branch

## 🎨 Customization

### Colors
The website uses CSS custom properties for easy color customization:

```css
:root {
    --primary-color: #1E40AF;
    --secondary-color: #3B82F6;
    --accent-color: #FF9900;
    --text-color: #1F2937;
    --light-bg: #F8FAFC;
}
```

### Content Updates
- **News Section**: Update the news items in the HTML
- **Achievements**: Modify the achievement cards
- **Contact Information**: Update email addresses and links
- **System Overview**: Replace `assets/wf.png` with your diagram

## 📱 Responsive Design

The website is fully responsive and works on:
- Desktop computers
- Tablets
- Mobile phones
- All modern browsers

## 🔧 Technical Details

- **Framework**: Bootstrap 5.3.0
- **Icons**: Font Awesome 6.0.0
- **Fonts**: Inter (system fallback)
- **Deployment**: GitHub Actions + GitHub Pages

## 📄 License

This website is part of the ASTRA project and follows the same MIT license.

## 🤝 Contributing

To contribute to the website:

1. Fork the repository
2. Make your changes in the `website/` directory
3. Test locally
4. Submit a pull request

## 📞 Support

For website-related issues or questions, please contact:
- **Xiangzhe Xu**: xu1415@purdue.edu
- **Guangyu Shen**: shen447@purdue.edu 