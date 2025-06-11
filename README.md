# Professor Finder 🎓

A specialized web tool for finding university faculty through targeted Google Scholar searches. Built to help graduate students, researchers, and academics discover potential advisors and collaborators based on their research interests and publication history.

## About the Creator

**MD. Sameer Iqbal Chowdhury**  
*Incoming PhD Student in Computer Science - Information Management*  
*Texas State University*

## 🚀 Features

- **Smart Keyword Search**: Search by paper titles and abstracts separately
- **Geographic Filtering**: Target specific countries and their academic domains
- **Date Range Control**: Focus on recent publications or specific time periods
- **Adjustable Search Strictness**: From flexible broad searches to exact phrase matching
- **Mobile-Responsive Design**: Works seamlessly on desktop and mobile devices
- **Academic Domain Filtering**: Automatically filters for university domains (.edu, .ac.uk, etc.)

## 🎯 Use Cases

- **Graduate School Applications**: Find potential PhD advisors in your field
- **Academic Collaboration**: Discover researchers working on similar topics
- **Literature Review**: Identify key authors and institutions in your area
- **Conference Networking**: Research speakers and attendees before academic events
- **Job Market Research**: Explore faculty positions and research groups

## 🛠️ How It Works

The tool constructs sophisticated Google Scholar queries using:

1. **Keyword Processing**: Intelligently combines title and abstract keywords
2. **Strictness Algorithm**: Adjusts search logic from broad OR queries to exact phrase matching
3. **Geographic Targeting**: Maps countries to their academic domain extensions
4. **Date Filtering**: Applies publication year constraints
5. **Domain Filtering**: Focuses on academic institutions (.edu, .ac.uk, .ac.in, etc.)

## 📋 Usage Guide

### Basic Search
1. Enter keywords related to your research area
2. Select your target country (optional)
3. Set the publication date range
4. Click "Search Faculty"

### Advanced Options

#### Search Strictness Levels
- **0.0 - 0.2 (Very Flexible)**: Broad search with OR logic
- **0.3 - 0.5 (Moderate)**: Balanced approach
- **0.6 - 0.8 (Strict)**: All terms required with AND logic
- **0.9 - 1.0 (Very Strict)**: Exact phrase matching only

#### Country Support
Supports major academic systems including:
- **US**: .edu domains
- **UK**: .ac.uk domains  
- **Canada**: .ca domains
- **Australia**: .edu.au domains
- **Germany**: .de domains
- **France**: .fr domains
- **Japan**: .ac.jp domains
- **India**: .ac.in domains
- **China**: .edu.cn domains
- **Brazil**: .br domains
- **Spain**: .es domains

## 🔧 Technical Details

### Built With
- **HTML5**: Semantic markup structure
- **CSS3**: Modern responsive design with flexbox
- **Vanilla JavaScript**: No external dependencies
- **Google Scholar API**: Leverages advanced search parameters

### Key Technical Features
- **Responsive Design**: Mobile-first approach with breakpoints
- **Accessibility**: ARIA labels and keyboard navigation
- **Performance**: Lightweight with no external dependencies
- **Cross-Browser**: Compatible with all modern browsers

### Search Query Construction
The tool builds complex Google Scholar queries using:
```
intitle:"keyword" AND "exact phrase" site:edu as_ylo:2020 as_yhi:2024
```

## 📁 Project Structure

```
professor-finder/
├── index.html          # Main application file
├── README.md           # This file
└── assets/             # Optional assets folder
    └── screenshots/    # Screenshots for documentation
```

## 🚀 Getting Started

### Option 1: Direct Use
1. Download the `index.html` file
2. Open it in any modern web browser
3. Start searching for faculty!

### Option 2: Web Hosting
1. Upload the `index.html` file to any web server
2. Access via your domain/hosting service
3. Share with colleagues and students

### Option 3: Local Development
```bash
# Clone the repository
git clone https://github.com/yourusername/professor-finder.git

# Navigate to the directory
cd professor-finder

# Open in browser (or serve with any local server)
open index.html
```

## 📱 Browser Compatibility

- ✅ Chrome 60+
- ✅ Firefox 55+
- ✅ Safari 12+
- ✅ Edge 79+
- ✅ Mobile browsers (iOS Safari, Chrome Mobile)

## 🎨 Customization

### Styling
The CSS uses CSS custom properties (variables) for easy theming:
```css
:root {
  --primary-color: #3b82f6;
  --background-color: #f8f9fa;
  --text-color: #333;
}
```

### Adding New Countries
To add support for new countries, modify the `searchFaculty()` function:
```javascript
case 'yourcountry':
    domainFilter = 'site:yourdomain';
    break;
```

## 🤝 Contributing

Contributions are welcome! Here are some ways you can help:

- 🐛 **Bug Reports**: Report issues via GitHub Issues
- 💡 **Feature Requests**: Suggest new functionality
- 🌍 **Country Support**: Add new academic domain mappings
- 📝 **Documentation**: Improve README and code comments
- 🎨 **UI/UX**: Enhance the user interface

### Development Guidelines
1. Maintain mobile-first responsive design
2. Keep the tool dependency-free
3. Follow semantic HTML practices
4. Ensure accessibility compliance
5. Test across different browsers

## 📊 Example Searches

### Machine Learning Researchers
- **Title Keywords**: "machine learning, artificial intelligence"
- **Abstract Keywords**: "neural networks, deep learning"
- **Country**: US
- **Years**: 2020-2024
- **Strictness**: 0.6

### Bioinformatics Faculty
- **Title Keywords**: "bioinformatics, computational biology"
- **Abstract Keywords**: "genomics, proteomics"
- **Country**: UK
- **Years**: 2018-2024
- **Strictness**: 0.4

## 📈 Future Enhancements

- [ ] Export search results to CSV/JSON
- [ ] Save and manage favorite searches
- [ ] Integration with academic databases beyond Google Scholar
- [ ] Batch processing for multiple keyword sets
- [ ] Author citation metrics integration
- [ ] University ranking integration

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🙏 Acknowledgments

- Built with modern web standards and accessibility in mind
- Inspired by the need for better academic discovery tools
- Thanks to the academic community for feedback and suggestions

## 📞 Contact

**MD. Sameer Iqbal Chowdhury**  
*Incoming PhD Student - Computer Science (Information Management)*  
*Texas State University*

- 📧 Email: [msichowdhury@txstate.edu]
- 🐦 Twitter: [(https://x.com/RavenXeen)]
- 💼 LinkedIn: [(https://www.linkedin.com/in/msichowdhury/)]
- 🌐 Website: [(https://msichowdhury.github.io/MSI-Chowdhury/)]

---

⭐ **Star this repository if it helped you find your perfect research advisor!**

*Made with ❤️ for the academic community*
