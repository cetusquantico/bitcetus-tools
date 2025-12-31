# bitcetus-tools
Bitcetus Tools — Educational Bitcoin Security Suite  Ferramentas open-source para análise forense de vulnerabilidades históricas do Bitcoin: • Nonce Reuse Attack (Android 2013) • Transaction Malleability • Weak RNG Comparison (2010 vs 2015+) • Private Key Recovery Demonstration  100% educacional · 100% offline · Pure JavaScript By Cetus 🐋 | 2025
# 🐋 BITCETUS TOOLS
## ⚠️ Important: Educational Purpose Only

Bitcetus Tools demonstrates **historical vulnerabilities** that have been fixed in modern Bitcoin implementations.

- No active attacks or brute force on current addresses
- All examples use public, historical data (zero balance wallets)
- Designed for learning ECDSA, RNG evolution, and Bitcoin security best practices

Use responsibly. Never attempt to recover keys that do not belong to you.
> Professional Bitcoin ECDSA Signature Forensics & Security Analysis Toolkit

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Bitcoin](https://img.shields.io/badge/Bitcoin-Security-orange.svg)](https://bitcoin.org)
[![ECDSA](https://img.shields.io/badge/ECDSA-Forensics-blue.svg)](https://en.wikipedia.org/wiki/Elliptic_Curve_Digital_Signature_Algorithm)

## 🔥 Features

### 🔬 ECDSA Signature Forensics v3.0
- **Nonce Reuse Detection** - Automatically detect duplicate R values
- **Private Key Recovery** - Mathematical attack on vulnerable signatures
- **Entropy Analysis** - Shannon entropy calculation for RNG quality
- **Canonization Check** - Identify high-S vs low-S signatures
- **Historical Comparison** - Compare 2010 weak RNG vs modern implementations

### 🕰️ Historical RNG Comparison Tool
- **Side-by-side Analysis** - Compare vintage (2010-2012) vs modern (2015+)
- **Vulnerability Database** - Real examples of weak RNG patterns
- **Visual Metrics** - Interactive charts and comparisons
- **Educational Cases** - Android SecureRandom bug, Bitcoin Core 0.3.x, and more

### 🎯 Puzzle #135 Entropy Analyzer
- **Florence Mode** - Specialized analysis for Bitcoin puzzles
- **Range Detection** - Check if values fall in known ranges
- **Pattern Recognition** - Detect repeating bytes and low entropy

## 🚀 Quick Start

### Online (No Installation)
1. Visit [GitHub Pages](#) *(configure this!)*
2. Select your tool
3. Paste signatures or transaction data
4. Click "Analyze"
5. Get instant forensic results!

### Local Usage
```bash
git clone https://github.com/cetusquantico/bitcetus-tools.git
cd bitcetus-tools
# Open HTML files directly in browser
```

## 📚 Use Cases

### 🛡️ Security Auditing
- Verify wallet implementations
- Test RNG quality
- Identify vulnerable transactions
- Validate signature canonization

### 🎓 Education
- Learn ECDSA vulnerabilities
- Understand cryptographic attacks
- Study Bitcoin security history
- Demonstrate mathematical concepts

### 🔍 Research
- Analyze blockchain data
- Study historical vulnerabilities
- Compare implementation quality
- Forensic investigation

## 🎬

*Coming soon: Video demonstrations of each tool*

## 📖 Documentation

### Tool Guides
- [ECDSA Forensics v3.0 Guide](docs/ecdsa-forensics.md)
- [Historical Comparison Guide](docs/historical-comparison.md)
- [Puzzle Analyzer Guide](docs/puzzle-analyzer.md)

### Technical Details
- [ECDSA Math Explained](docs/ecdsa-math.md)
- [Nonce Reuse Attack](docs/nonce-reuse-attack.md)
- [Entropy Analysis](docs/entropy-analysis.md)

### Case Studies
- [Android SecureRandom Bug (2013)](docs/cases/android-bug-2013.md)
- [Bitcoin Core 0.3.x Weak RNG (2010-2011)](docs/cases/bitcoin-core-early.md)
- [Blockchain.info Bug (2014)](docs/cases/blockchaininfo-2014.md)

## 🎯 Real-World Examples

### Example 1: Nonce Reuse Detection
```javascript
// Input: 2 signatures with same R value
Signature 1: r = d47ce4c0..., s = e1b8c1e1...
Signature 2: r = d47ce4c0..., s = 9284746...

// Output: Private key recovered!
Private Key: 79672bebc066fe73df9eedf38cc8a801...
```

### Example 2: Weak RNG Detection
```javascript
// Input: Signatures from Bitcoin Core 0.3.x
Entropy R: 2.85 (expected 3.7-4.0) ⚠️
Zeros: 28% (expected 6.25%) 🚨
Verdict: VULNERABLE - Weak RNG detected
```

## ⚠️ Ethical Use

**IMPORTANT**: These tools are for:
- ✅ Educational purposes
- ✅ Security research
- ✅ Auditing your own wallets
- ✅ Historical analysis

**NOT for**:
- ❌ Attacking others' wallets
- ❌ Stealing funds
- ❌ Malicious activities

## 🤝 Contributing

Contributions are welcome! Please:
1. Fork the repository
2. Create a feature branch
3. Make your changes
4. Submit a pull request

See [CONTRIBUTING.md](CONTRIBUTING.md) for details.

## 📄 License

MIT License - see [LICENSE](LICENSE) file for details

## 🙏 Acknowledgments

- Bitcoin Core developers
- ECDSA security researchers
- Cryptography community
- Historical vulnerability reporters

## 📬 Contact

- GitHub: [@cetusquantico](https://github.com/cetusquantico)
- Issues: [GitHub Issues](https://github.com/cetusquantico/bitcetus-tools/issues)

## 🌟 Star History

[![Star History Chart](https://api.star-history.com/svg?repos=cetusquantico/bitcetus-tools&type=Date)](https://star-history.com/#cetusquantico/bitcetus-tools&Date)

---

**Made with 💜 by Cetus | Bitcoin Security Research**

*"In cryptography we trust, in mathematics we verify"*
```

---

## 📁 **2. ESTRUTURA DE DIRETÓRIOS SUGERIDA**
```
bitcetus-tools/
│
├── 📄 README.md
├── 📄 LICENSE (MIT)
├── 📄 CONTRIBUTING.md
│
├── 📁 tools/
│   ├── ecdsa-forensics-v3.html
│   ├── historical-rng-comparison.html
│   ├── puzzle66-analyzer.html
│   └── bitcetus-hunter.html (se você tiver)
│
├── 📁 datasets/
│   ├── vulnerable-wallets-2010-2013.txt
│   ├── puzzle66-signatures.txt
│   └── android-bug-examples.txt
│
├── 📁 docs/
│   ├── ecdsa-forensics.md
│   ├── historical-comparison.md
│   ├── puzzle-analyzer.md
│   ├── ecdsa-math.md
│   ├── nonce-reuse-attack.md
│   └── entropy-analysis.md
│
├── 📁 docs/cases/
│   ├── android-bug-2013.md
│   ├── bitcoin-core-early.md
│   ├── blockchaininfo-2014.md
│   └── windows-xp-bug.md
│
├── 📁 images/
│   ├── logo.png
│   ├── screenshot-forensics.png
│   ├── screenshot-comparison.png
│   └── demo.gif
│
└── 📁 examples/
    ├── nonce-reuse-example.md
    ├── weak-rng-example.md
    └── recovery-walkthrough.md


    ## 🐋 Support Bitcetus Development

Se essas ferramentas te ajudaram a entender melhor a segurança do Bitcoin, inspiraram algum projeto ou simplesmente te fizeram dizer "caralho, que foda", considera apoiar o desenvolvimento futuro com uma doação voluntária.

**Bitcoin (BTC):**  
`bc1qs4wajz6r5qg9429d8cjdxzedjyyzwuqz7fh55d`

Todo satoshi ajuda a continuar construindo ferramentas educacionais open-source para a comunidade Bitcoin.

## 🛠️ Tools Included

- **Bitcetus Hunter v2.0** — Advanced ECDSA Nonce Forensics
- **ECDSA Signature Forensics v2.0** — Classic Dataset & Manual Analysis
- **ECDSA Forensics v3.0** — Private Key Recovery (Hybrid Mode)
- **Historical RNG Comparison** — 2010 Weak vs 2015+ Strong
- **Bitcetus Recovery v1.0** — Standalone Nonce Reuse Attack Demo

## ⚠️ Ethical Use Only

These tools demonstrate **historical vulnerabilities** that have been fixed in modern Bitcoin.

- All examples use public data from wallets with zero balance
- No active attacks or brute force
- For learning and research purposes only

## 🐋 Support the Project

If these tools helped you, consider a donation:

**BTC:** `bc1qs4wajz6r5qg9429d8cjdxzedjyyzwuqz7fh55d`

Thank you for supporting open-source Bitcoin education! 

Obrigado por fazer parte dessa jornada! 🐋

— Cetus | 2025–2026
