# MyFitnessPal CORS Misconfiguration Proof of Concept

## 🚨 Security Demonstration

This repository demonstrates a critical CORS misconfiguration vulnerability in MyFitnessPal's API that could lead to account takeover of 40M+ users.

## ⚠️ Ethical Usage Only

This proof-of-concept is for:
- Security education
- Responsible disclosure
- Vulnerability demonstration

**DO NOT use this for malicious purposes.**

## 🔍 Vulnerability Details

- **Type**: CORS Misconfiguration
- **Target**: `https://api.myfitnesspal.com/`
- **Impact**: Account takeover via credential theft
- **CVSS**: 9.1 (Critical)

## 🛠️ Setup

1. Fork this repository
2. Enable GitHub Pages in repository settings
3. Visit your `https://username.github.io/repository-name` 

## 🎯 Demonstration

The live demo allows you to:
- Test CORS configuration
- Verify arbitrary origin acceptance  
- Simulate data theft attacks
- Generate evidence reports

## 📝 Evidence

The vulnerability allows:
- Any origin to make requests to MyFitnessPal API
- Credentials (cookies) to be sent cross-origin
- Access to sensitive user endpoints
- Potential account takeover

## 🔒 Responsible Disclosure

This vulnerability has been responsibly disclosed to MyFitnessPal's security team.

## 📄 License

Educational use only.
