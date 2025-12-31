# Contributing to Bitcetus Tools

First off, thank you for considering contributing to Bitcetus Tools! 🎉

## 🌟 How Can I Contribute?

### 🐛 Reporting Bugs

Before creating bug reports, please check existing issues. When creating a bug report, include:

- **Clear title and description**
- **Steps to reproduce**
- **Expected vs actual behavior**
- **Screenshots** (if applicable)
- **Browser/OS information**

Example:
```
**Bug:** ECDSA Forensics v3.0 crashes on large datasets

**Steps:**
1. Load tool
2. Paste 100+ signatures
3. Click "Analyze"
4. Tool freezes

**Expected:** Should process all signatures
**Actual:** Browser tab becomes unresponsive

**Environment:** Chrome 120, Windows 11
```

### ✨ Suggesting Enhancements

Enhancement suggestions are tracked as GitHub issues. Include:

- **Clear use case**
- **Why this enhancement would be useful**
- **Possible implementation approach**

### 📝 Pull Requests

1. Fork the repo
2. Create a feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

#### PR Guidelines

- ✅ Follow existing code style
- ✅ Test your changes
- ✅ Update documentation if needed
- ✅ Add comments for complex logic
- ✅ Keep PRs focused (one feature per PR)

### 📚 Improving Documentation

Documentation improvements are always welcome! This includes:

- Fixing typos
- Adding examples
- Clarifying explanations
- Adding tutorials
- Translating to other languages

## 🎨 Code Style

### HTML/JavaScript

- Use 4 spaces for indentation
- Use meaningful variable names
- Add comments for complex algorithms
- Keep functions focused and small
- Use modern JavaScript (ES6+)

Example:
```javascript
// ✅ Good
function calculateShannonEntropy(hexString) {
    const frequency = {};
    for (let char of hexString) {
        frequency[char] = (frequency[char] || 0) + 1;
    }
    // ... rest of implementation
}

// ❌ Bad
function calc(h) {
    let f = {};
    for(let c of h) { f[c] = (f[c] || 0) + 1; }
    // ...
}
```

## 🏷️ Labels

We use these labels for issues:

- `bug` - Something isn't working
- `enhancement` - New feature or request
- `documentation` - Documentation improvements
- `good first issue` - Good for newcomers
- `help wanted` - Extra attention needed
- `question` - Further information requested

## 💬 Communication

- Be respectful and constructive
- Assume good intentions
- Focus on the code, not the person
- Accept that disagreements happen

## 📜 Code of Conduct

By participating, you agree to abide by our Code of Conduct (see CODE_OF_CONDUCT.md).

## 🙏 Recognition

Contributors will be:
- Added to README.md contributors section
- Mentioned in release notes
- Credited in relevant documentation

## 📧 Contact

Questions? Open an issue or reach out to [@cetusquantico](https://github.com/cetusquantico)

---

**Thank you for making Bitcetus Tools better! 🐋💜**
