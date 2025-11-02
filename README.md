# CTT Wireless Security Auditor

**Professional-Grade Wireless Network Security Testing Tool**

Copyright © 2025 A.N.F Simões. All Rights Reserved.

## Overview

The CTT Wireless Security Auditor is a professional security testing tool that applies Convergent Time Theory (CTT) principles to wireless network security auditing. It demonstrates a novel approach to WPA/WPA2 key derivation using temporal resonance sampling.

## ⚠️ LEGAL NOTICE

**AUTHORIZED USE ONLY**

This tool is for:
- Testing networks you own
- Authorized penetration testing with written permission
- Educational purposes in controlled environments
- Security research by licensed professionals

**Unauthorized use is ILLEGAL and subject to prosecution under:**
- Computer Fraud and Abuse Act (USA)
- Computer Misuse Act (UK)
- EU Cybersecurity Regulations
- International cybercrime laws

## Features

- **Temporal Key Derivation**: CTT-based WPA/WPA2 password sampling
- **Prime Window Alignment**: Microsecond-precision temporal synchronization
- **Standard WPA Protocol**: Full PMK/PTK calculation and MIC verification
- **Professional Output**: Detailed logging and reporting
- **Research Platform**: Extensible architecture for security research

## Technical Specifications

- **Framework**: Convergent Time Theory (α = 0.0302)
- **Prime Window**: 10007 μs
- **Resonance Frequencies**: ω+ = 587 kHz, ω− = 293.5 kHz
- **Cryptography**: OpenSSL (PBKDF2-HMAC-SHA1, PRF)
- **Precision**: Microsecond-level temporal sampling

## Installation

### Prerequisites

```bash
# Fedora/RHEL
sudo dnf install gcc make openssl-devel

# Debian/Ubuntu
sudo apt install build-essential libssl-dev

# Arch
sudo pacman -S base-devel openssl
```

### Build

```bash
cd ctt-wireless-security
make
```

### Install (Optional)

```bash
sudo make install
```

## Usage

### Basic Execution

```bash
./ctt_wpa_auditor
```

### Integration

For integration into security platforms, see `docs/ctt-wireless-security-whitepaper.pdf`

## Documentation

- **Whitepaper**: `docs/ctt-wireless-security-whitepaper.tex`
- **License**: `LICENSE`
- **API Documentation**: Coming soon

### Generate PDF Documentation

```bash
cd docs
pdflatex ctt-wireless-security-whitepaper.tex
```

## Commercial Licensing

### License Tiers

1. **Research License**: Academic/non-commercial use
2. **Professional License**: Individual security consultants
3. **Enterprise License**: Corporate security teams
4. **OEM License**: Product integration

### Contact

- **Email**: amexsimoes@gmail.com

## Project Structure

```
ctt-wireless-security/
├── src/
│   └── ctt_wpa_auditor.c
├── docs/
│   └── ctt-wireless-security-whitepaper.tex
├── tests/
├── build/
├── Makefile
├── LICENSE
└── README.md
```

## Contributing

This is proprietary commercial software. For collaboration inquiries, contact antonio.simoes@ctt-security.com

## Security Considerations

### Responsible Disclosure

Report vulnerabilities found using this tool:
1. Contact affected parties immediately
2. Follow responsible disclosure practices
3. Do not exploit for malicious purposes
4. Document for security improvement

### Ethical Use

- Obtain written authorization
- Maintain confidentiality
- Follow applicable laws
- Use for defensive purposes only

## Disclaimer

THIS SOFTWARE IS PROVIDED "AS IS" WITHOUT WARRANTY OF ANY KIND. THE AUTHOR SHALL NOT BE LIABLE FOR ANY DAMAGES ARISING FROM THE USE OF THIS SOFTWARE.

## Copyright

Copyright © 2025 António Nuno Fernandes Simões. All Rights Reserved.

This software is proprietary and confidential. Unauthorized distribution or use is strictly prohibited.

---

**For licensing and support**: antonio.simoes@ctt-security.com
