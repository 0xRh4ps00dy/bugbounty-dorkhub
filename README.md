# 🔍 BugBounty Dorkhub

An interactive web tool for performing reconnaissance searches (dorking) on target domains during Bug Bounty and pentesting activities.

## 📋 Description

BugBounty Dorkhub is a compilation of **Google Dorks**, **Shodan Dorks**, and **GitHub Dorks** that I've gathered from various public sources within the security community. This application facilitates the reconnaissance process by organizing hundreds of dorks into categories and enabling progress tracking for searches.

> ⚠️ **Important Note**: The dorks compiled in this tool come from multiple public sources shared by the Bug Bounty and information security community. This project is an educational compilation of such techniques.

## ✨ Main Features

### 🎯 Core Functionalities

- **Domain Search**: Enter a target domain and execute specific dorks with a single click
- **Progress Tracking**: Automatically marks executed dorks with a visual indicator (✓)
- **Data Persistence**: Progress is saved in localStorage for each domain
- **Selective Reset**: Reset progress by category or completely
- **Modern Interface**: Futuristic design with dark theme and smooth animations
- **Responsive**: Adapted to work on desktop and mobile devices

## 🚀 Usage

1. **Open the `index.html` file** in your web browser
2. **Enter the target domain** (e.g., `example.com`)
3. **Click on the dork buttons** you want to execute
4. **A new tab will automatically open** with the search results
5. **The button will be marked as completed** with a green ✓

### Workflow Example

```
1. Enter: example.com
2. Execute: Subdomains → site:*.example.com
3. Execute: Config files → site:example.com ext:xml | ext:conf | ext:cnf...
4. Review the results
5. Progress is saved automatically
```

## 🛠️ Installation

No installation required. Simply:

```bash
# Clone the repository
git clone https://github.com/0xRh4ps00dy/bugbounty-dorkhub.git

# Open in your browser
cd bugbounty-dorkhub
# Open index.html with your favorite browser
```

Or download the files and open them directly.

## 📁 Project Structure

```
bugbounty-dorkhub/
│
├── index.html          # Main page with all categories
├── script.js           # Application logic and dork functions
├── style.css           # Interface styles and design
└── README.md           # This file
```

## 🔧 Technologies Used

- **HTML5**: Semantic structure
- **CSS3**: Modern design with gradients and animations
- **JavaScript Vanilla**: No external dependencies
- **LocalStorage API**: Data persistence

## 📊 Statistics

- **240+ Dorks** organized
- **17 Categories** thematic
- **Multiple engines**: Google, Shodan, GitHub, Censys, etc.
- **100% client**: No server required

## ⚖️ Legal Considerations

⚠️ **RESPONSIBLE USE**: This tool is designed for:
- Authorized security testing
- Bug Bounty programs
- Ethical security research
- Audits with explicit permission

**DO NOT use this tool for**:
- Accessing systems without authorization
- Illegal activities
- Violation of terms of service

The author is not responsible for the misuse of this tool.

## 🙏 Credits

This project is a **compilation of dorks shared publicly** by the information security community. The dorks have been collected from:

- Public Twitter/X posts by security researchers
- Public GitHub repositories
- Bug Bounty Hunter blogs
- Cybersecurity forums and communities
- Ethical hacking tutorials and guides

**Special thanks** to the entire Bug Bounty community that openly shares knowledge.

## 🤝 Contributions

Contributions are welcome. If you know of useful new dorks or improvements for the application:

1. Fork the project
2. Create a branch for your feature (`git checkout -b feature/new-dork`)
3. Commit your changes (`git commit -m 'Add: new dork for X'`)
4. Push to the branch (`git push origin feature/new-dork`)
5. Open a Pull Request

## 📝 Changelog

### v1.0.0 (2025)
- ✅ Initial release
- ✅ 240+ dorks organized into 17 categories
- ✅ Progress tracking system
- ✅ Responsive interface
- ✅ Local persistence

## 📧 Contact

- GitHub: [@0xRh4ps00dy](https://github.com/0xRh4ps00dy)
- Project: [BugBounty Dorkhub](https://github.com/0xRh4ps00dy/bugbounty-dorkhub)

## 📜 License

This project is distributed under the MIT license. See `LICENSE` file for more details.

---

**⭐ If you find this tool useful, consider giving it a star on GitHub!**

**Happy Hacking! 🔐**
