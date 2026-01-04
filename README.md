# Shaktishali Password Checker

A Python-based command-line tool that performs comprehensive password strength analysis with strict security checks. Built as a learning project to understand password security fundamentals and Python programming.

![Python Version](https://img.shields.io/badge/python-3.8%2B-blue)
![License](https://img.shields.io/badge/license-MIT-green)
![Status](https://img.shields.io/badge/status-active-success)

## ✨ Features

### Core Functionality
- **Real-time Password Analysis** - Instant feedback on password strength
- **Comprehensive Security Checks** - 8 different validation criteria
- **Detailed Feedback** - Clear explanations of strengths and weaknesses
- **Interactive Console Interface** - User-friendly command-line experience

### Security Checks (8 Total)
1. ✅ Minimum length (12 characters)
2. ✅ Uppercase letter requirements (2+)
3. ✅ Lowercase letter requirements (2+)
4. ✅ Number requirements (2+)
5. ✅ Special character requirements (2+)
6. ✅ Common password detection (20,000+ passwords)
7. ✅ Sequential character detection (abc, 123)
8. ✅ Repeated character detection (aaa, 111)

### Strength Ratings
- **Very Strong** (86-100): Excellent security, highly resistant to attacks
- **Strong** (71-85): Good security, resistant to most attacks
- **Moderate** (51-70): Acceptable but could be improved
- **Weak** (26-50): Vulnerable, should be strengthened
- **Very Weak** (0-25): Highly vulnerable, must be changed


## 🚀 Installation

### Prerequisites
- Python 3.8 or higher
- No external dependencies required (uses only Python standard library)

### Steps

1. **Clone the repository**
   ```bash
   git clone https://github.com/dipesh-khanal/shaktishali-password-checker.git
   cd shaktishali-password-checker
   ```

2. **Verify Python installation**
   ```bash
   python --version
   # or
   python3 --version
   ```

3. **Verify project structure**
   ```bash
   ls -la
   # Should see: main.py, password_checker.py, data/ folder
   ```

4. **Run the application**
   ```bash
   python main.py
   ```

## 💻 Usage

Follow the interactive prompts to check password strength.


### Architecture

```
┌─────────────────────────────────────┐
│           main.py                   │
│  (User Interface & Display)         │
└──────────────┬──────────────────────┘
               │
               ▼
┌─────────────────────────────────────┐
│      password_checker.py            │
│  (Core Logic & Validation)          │
└──────────────┬──────────────────────┘
               │
               ▼
┌─────────────────────────────────────┐
│         data/                       │          
│  └── common_passwords.txt           │
└─────────────────────────────────────┘
```

## 📁 Project Structure

```
shaktishali-password-checker/
│
├── main.py                    # Entry point & UI
├── password_checker.py        # Core validation logic
├── gui.py                     # Placeholder for future GUI
├── README.md                  # This file
├── LICENSE                    # MIT License
├── .gitignore                # Git ignore rules
│
└── data/
    └── common_passwords.txt       # 20,000+ common passwords
```

### File Descriptions

| File | Purpose | Lines of Code |
|------|---------|---------------|
| `main.py` | User interface, display formatting, input handling | ~200 |
| `password_checker.py` | Password validation logic, scoring algorithm | ~500 |
| `data/common_passwords.txt` | Database of commonly used passwords | ~20,000 |


## 🔮 Future Enhancements

### Planned Features
- [ ] **GUI Version** - Tkinter-based graphical interface
- [ ] **Password Generator** - Create strong random passwords
- [ ] **Breach Check** - Integration with Have I Been Pwned API
- [ ] **Password Manager** - Secure storage with encryption
- [ ] **Strength History** - Track password changes over time
- [ ] **Multi-language Support** - Internationalization
- [ ] **Export Reports** - PDF/CSV export functionality
- [ ] **Browser Extension** - Real-time password checking in browsers


## 🤝 Contributing

Contributions are welcome! This project was built as a learning exercise, and improvements are encouraged.

### How to Contribute

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

### Contribution Guidelines

- Write clear, commented code
- Follow PEP 8 style guidelines
- Add tests for new features
- Update documentation as needed
- Keep commits atomic and well-described

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

```
MIT License

Copyright (c) 2026 Dipesh Khanal

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
```

## 📧 Contact

**Project Creator**: Dipesh Khanal
- GitHub: [@dipesh-khanal](https://github.com/dipesh-khanal)
- Email: dipesh.khanal2004@gmail.com
- LinkedIn: [Dipesh Khanal](https://www.linkedin.com/in/i-am-dipesh-khanal/)


**Built with ❤️ as a learning project to understand password security and Python programming**

*Last Updated: January 2026*