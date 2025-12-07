# Climate Research - Youth & Climate Change

A web-based research presentation platform that assesses youth knowledge on the effectiveness of individual actions in mitigating climate change.

## 📖 About

This project presents research findings on how youth (aged 15-24) understand the effectiveness of various individual actions in contributing to climate change mitigation. The study reveals that youth have limited understanding of which actions are most effective, and identifies social media as the primary source of climate information for young people.

## ✨ Features

- **Interactive Research Paper**: Full research documentation with easy navigation
- **Responsive Design**: Optimized for all device sizes
- **Dark/Light Mode**: Toggle between dark and light themes for comfortable reading
- **Table of Contents**: Quick navigation to different sections of the research
- **Download Option**: Ability to download the research paper
- **Modern UI**: Clean and accessible interface with Font Awesome icons

## 🎯 Research Focus

The study examines:
- Youth knowledge levels regarding climate change mitigation actions
- Demographic characteristics of participants
- Factors influencing climate change awareness
- Primary sources of climate change information
- Correlation between various factors and knowledge levels

### Key Findings

- Youth often overestimate the impact of low-impact actions (e.g., recycling)
- High-impact actions are frequently underestimated
- Social media is the main source of climate change information for youth
- Higher education levels and active participation in environmental activities correlate with better knowledge

## 🛠️ Tech Stack

- **HTML5**: Structure and content
- **CSS3/SCSS**: Styling with Sass preprocessor
- **JavaScript**: Interactive features and functionality
- **Font Awesome**: Icon library for UI elements

## 📦 Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/gcl140/climate-research.git
   cd climate-research
   ```

2. **Install dependencies**
   ```bash
   npm install
   ```

3. **Compile SCSS (if making style changes)**
   ```bash
   npx sass styles/style.scss styles/style.css
   ```

## 🚀 Usage

### View Locally

Simply open `index.html` in your web browser:

```bash
# On macOS
open index.html

# On Linux
xdg-open index.html

# On Windows
start index.html
```

Or use a local development server:

```bash
# Using Python
python -m http.server 8000

# Using Node.js (http-server)
npx http-server
```

Then navigate to `http://localhost:8000` in your browser.

### Development

If you're modifying the SCSS files, you can watch for changes:

```bash
npx sass --watch styles/style.scss:styles/style.css
```

## 📁 Project Structure

```
climate-research/
├── index.html          # Main research presentation page
├── no.html             # Additional content page
├── styles/
│   ├── style.scss      # Source SCSS file
│   ├── style.css       # Compiled CSS
│   └── georgia.ttf     # Custom font
├── scripts/
│   └── script.js       # Interactive functionality
├── images/
│   ├── 8371913.ico     # Favicon
│   ├── gh.png          # GitHub image
│   └── source of knldg.png  # Knowledge source graphic
├── package.json        # Project dependencies
└── LICENSE             # MIT License
```

## 🎨 Features in Detail

### Navigation
- Collapsible table of contents for easy section access
- Smooth scrolling to research sections
- Mobile-friendly hamburger menu

### Theme Switching
- Toggle between light and dark modes
- Preference saved for better user experience

### Research Sections
- Abstract
- Introduction
- Statement of the Problem
- General Objective
- Significance of Study
- Definition of Key Terms
- Methodologies
- Results and Discussion
- Conclusion
- References

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

1. Fork the project
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 👥 Author

**gcl140**

## 🙏 Acknowledgments

- Research participants from the Dar es Salaam region
- Youth aged 15-24 who contributed to this study
- All contributors to climate change awareness and education

## 📞 Contact

For questions or feedback about this research, please open an issue on GitHub.

---

**Note**: This project presents important research on youth climate change knowledge. The findings suggest that targeted educational strategies and social media outreach are crucial for empowering youth to take effective climate action.
