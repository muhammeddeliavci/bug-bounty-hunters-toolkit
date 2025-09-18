# Bug Bounty Hunter's Toolkit 🛠️

> **Live Demo:** [toolkit.pielse.com](https://toolkit.pielse.com)

A comprehensive, single-page security testing toolkit designed for bug bounty hunters, penetration testers, and security researchers. This tool provides quick access to essential security testing resources, payload generators, encoding tools, and vulnerability databases.

![Bug Bounty Toolkit](https://img.shields.io/badge/Status-Active-green) ![License](https://img.shields.io/badge/License-MIT-blue) ![Language](https://img.shields.io/badge/Language-HTML%2FJS-orange)

## 🌟 Features

### 🔍 Google Dorks Module
- **Quick Dork Generator** with 8 predefined categories
- **Real-time domain substitution** for multiple targets
- **Automated Google search links** generation
- **Export functionality** for dork collections
- **Live dork collection** fetched from GitHub repositories

### 🕵️ Reconnaissance & OSINT Tools
- **Search Engines**: Shodan, Censys, ZoomEye
- **Domain Intelligence**: crt.sh, DNSdumpster, Subdomain Finder
- **Email & Social**: Hunter.io, Have I Been Pwned, WhatsMyName
- **Web Archives**: Wayback Machine, URLScan.io, Archive.today
- **Network Analysis**: VirusTotal, Security Headers, SSL Labs
- **Code Analysis**: GitHub Search, grep.app, SearchCode

### 💉 Payload Generator & Testing
- **Parameter injection** with quick-add buttons
- **XSS payloads** collection with one-click copy
- **SQL injection** payloads for various scenarios
- **Wordlists & Collections**: Direct links to SecLists, FuzzDB, PayloadsAllTheThings

### 🔧 Encoding & Utility Tools
- **Base64** encoder/decoder
- **URL** encoder/decoder
- **Hash generators** (SHA1, SHA256)
- **HTTP header checker** with CORS support

### 🗄️ Vulnerability Databases
- **Exploit Databases**: Exploit-DB, Packet Storm, Sploitus
- **CVE Databases**: NVD, CVE MITRE, CVE Details
- **Security Advisories**: Rapid7, VulDB, Snyk
- **Bug Bounty Platforms**: HackerOne, Bugcrowd, Intigriti
- **Research Resources**: MITRE ATT&CK, OWASP Top 10, CWE

### 🌍 Multi-Language Support
- **English** and **Turkish** language support
- **Automatic language detection** and preference saving
- **Localized content** including domain examples and notifications

## 🚀 Quick Start

### Online Access
Visit [toolkit.pielse.com](https://toolkit.pielse.com) for immediate access to all features.

### Local Setup
1. Clone the repository:
   ```bash
   git clone https://github.com/muhammeddeliavci/bug-bounty-hunters-toolkit.git
   cd bug-bounty-hunters-toolkit
   ```

2. Open `index.html` in your web browser:
   ```bash
   # Using Python
   python -m http.server 8000
   
   # Using Node.js
   npx serve .
   
   # Or simply open index.html in your browser
   ```

3. Navigate to `http://localhost:8000` (if using a server)

## 📖 Usage Guide

### Google Dorks
1. **Enter target domain(s)** in the input field (comma-separated for multiple)
2. **Use quick generator buttons** for common vulnerability patterns
3. **Click generated dorks** to search directly on Google
4. **Copy or export** dork collections for later use

### Reconnaissance
1. **Browse categorized tools** for different reconnaissance phases
2. **Click tool links** to open in new tabs
3. **Combine multiple tools** for comprehensive target analysis

### Payload Testing
1. **Enter target URL** for parameter testing
2. **Add parameters** using quick-add buttons
3. **Copy payloads** for manual or automated testing
4. **Reference wordlists** for comprehensive testing

### Encoding Tools
1. **Enter text/URL** in respective input fields
2. **Click encode/decode** buttons for transformations
3. **Generate hashes** for integrity checking
4. **Check HTTP headers** for security analysis

## 🔧 Technical Details

### Architecture
- **Single-page application** built with vanilla HTML, CSS, and JavaScript
- **No external dependencies** except Tailwind CSS CDN
- **Responsive design** optimized for desktop and mobile
- **Client-side only** - no server required

### Browser Compatibility
- **Chrome/Edge**: Full support
- **Firefox**: Full support  
- **Safari**: Full support
- **Mobile browsers**: Responsive design

### Performance
- **Fast loading** with minimal external resources
- **Offline capabilities** for core functionality
- **Lazy loading** for external tool links
- **Optimized animations** and transitions

## 🛡️ Security Considerations

### Data Privacy
- **No data collection** - all operations are client-side
- **No tracking** or analytics
- **Local storage** only for language preferences

### CORS Limitations
- HTTP header checker may be limited by CORS policies
- External API calls respect browser security policies
- All external links open in new tabs for security

## 🤝 Contributing

We welcome contributions! Here's how you can help:

### Bug Reports
1. Check existing issues first
2. Provide detailed reproduction steps
3. Include browser and OS information

### Feature Requests
1. Describe the feature and use case
2. Explain how it benefits security testing
3. Consider implementation complexity

### Code Contributions
1. Fork the repository
2. Create a feature branch
3. Make your changes
4. Test thoroughly
5. Submit a pull request

### Translation Contributions
Help us add support for more languages:
1. Copy the English translation object
2. Translate all strings to your language
3. Test the UI with your translations
4. Submit a pull request

## 📝 Changelog

### v2.0.0 (Current)
- ✅ Multi-language support (EN/TR)
- ✅ Complete UI/UX redesign
- ✅ Added payload generator
- ✅ Enhanced encoding tools
- ✅ Expanded vulnerability databases
- ✅ Improved mobile responsiveness

### v1.0.0
- ✅ Initial Google Dorks functionality
- ✅ Basic OSINT tools collection
- ✅ Simple encoding tools

## 🔗 Related Projects

- [Google Dorks Bug Bounty](https://github.com/TakSec/google-dorks-bug-bounty) - Source of dork collection
- [SecLists](https://github.com/danielmiessler/SecLists) - Security tester's companion
- [PayloadsAllTheThings](https://github.com/swisskyrepo/PayloadsAllTheThings) - Web app security payloads

## 📊 Statistics

- **350+ translations** across two languages
- **50+ security tools** and databases linked
- **100+ payloads** for common vulnerabilities
- **8 dork categories** with automated generation
- **6 main modules** for complete security testing workflow

## 🙏 Acknowledgments

- **TakSec** for the comprehensive Google Dorks collection
- **OWASP** for security resources and guidelines
- **Security community** for tool recommendations and feedback
- **Open source projects** that make this toolkit possible

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 📞 Support

- **Website**: [toolkit.pielse.com](https://toolkit.pielse.com)
- **GitHub Issues**: For bug reports and feature requests
- **Email**: Contact through GitHub profile

---

**⚠️ Disclaimer**: This toolkit is designed for authorized security testing only. Users are responsible for ensuring they have proper authorization before testing any systems. The authors are not responsible for any misuse of this tool.

**🎯 Happy Bug Hunting!**
