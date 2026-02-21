# raisingpixels.dev ✨

A curated collection of coding platforms, STEM toys, educational apps, and hardware kits to help parents introduce their children to technology and programming in fun, engaging ways.

Built by [@meimakes](https://x.com/meimakes)


## ✨ Features

- **🔍 Live Search** - Instantly filter resources as you type
- **📱 Responsive Design** - Works beautifully on all devices
- **🌓 Auto Dark/Light Mode** - Automatically adapts to browser preferences
- **🏷️ Category Filters** - Quick filtering by resource type:
  - Coding Platforms
  - STEM Toys
  - Apps & Games
  - Hardware & Kits
  - Books & Media
- **🎨 Retro Aesthetic** - Modern brutalist design with playful colors and solid shadows
- **✨ Subtle Animations** - Floating pixels, hover effects, and smooth transitions
- **👶 Age Recommendations** - Clear age ranges for each resource

## 🚀 Development Quick Start

### Option 1: Direct Use
Simply open `index.html` in your web browser. No build process or dependencies required!

### Option 2: Local Development
```bash
# Clone the repository
git clone https://github.com/meimakes/raisingpixels.dev.git

# Navigate to the project
cd raisingpixels.dev

# Open in your browser
open index.html

# Or use a local server (optional)
python -m http.server 8000
# Then visit http://localhost:8000
```

### Option 3: Deploy to GitHub Pages
1. Fork this repository
2. Go to Settings → Pages
3. Select "Deploy from a branch"
4. Choose `main` branch and `/root` folder
5. Your site will be available at `https://yourusername.github.io/raisingpixels.dev`

## 🛠️ Customization

### Adding New Resources

Edit the `resources` array in the JavaScript section:

```javascript
{
    title: "Resource Name",
    category: "coding", // coding, toys, apps, hardware, or books
    icon: "🎯",         // Emoji icon
    color: "#ffb3d9",   // Accent color
    description: "Brief description of the resource",
    ageRange: "8-12 years",
    link: "https://example.com"
}
```

### Modifying Color Themes

Update the CSS variables in the `:root` selector:

```css
:root {
    --bg-primary: #fdf6ff;    /* Main background */
    --bg-secondary: #fff;      /* Card backgrounds */
    --text-primary: #2d1b69;   /* Main text */
    --text-secondary: #6b5b95; /* Secondary text */
    --accent-1: #ffb3d9;       /* Pink accent */
    --accent-2: #b3e5ff;       /* Blue accent */
    /* ... more colors */
}
```

### Dark Mode Colors

Adjust dark mode in the `@media (prefers-color-scheme: dark)` section.

## 🤝 Contributing

Contributions are welcome! Here's how you can help:

1. **Fork the repository**
2. **Create a feature branch** (`git checkout -b feature/NewResource`)
3. **Add your resource or feature**
4. **Commit your changes** (`git commit -m 'Add new resource: XYZ'`)
5. **Push to the branch** (`git push origin feature/NewResource`)
6. **Open a Pull Request**

### Contribution Guidelines

- Ensure resources are appropriate for children
- Include accurate age recommendations
- Verify all links are working
- Keep descriptions concise but informative
- Test theme changes in both light and dark modes
- Maintain the existing code style

## 📝 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🙏 Acknowledgments

- Inspired by the need to help parents navigate the digital education landscape
- Design influenced by modern brutalist web aesthetics
- Color palette inspired by playful, child-friendly interfaces

## 📧 Contact

For questions, suggestions, or to report broken links, please open an issue on GitHub.

---

**Made with 💜 for parents raising the next generation of creators**