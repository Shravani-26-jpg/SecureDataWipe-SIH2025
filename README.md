# 🔐 Secure Data Wiping for Trustworthy IT Asset Recycling  
**SIH 2025 Project – Team CyberSanctrix** 

## # Problem Statement  
India generates **1.75M tonnes of e-waste annually**, but much of it is not recycled due to **fear of data breaches**.  
People and enterprises hoard devices worth **₹50,000+ crore** because current wiping tools are:  
- ❌ Too complex or expensive  
- ❌ Don’t provide verifiable proof of deletion  
- ❌ Lack offline/portable usability  

This creates a **huge barrier to safe IT asset disposal and circular economy**.  

## 🎯 Objectives  
- Develop a **cross-platform wiping tool** (Windows, Linux, Android).  
- Ensure **secure, verifiable, and permanent data deletion** (aligned with **NIST SP 800-88**).  
- Generate **tamper-proof wipe certificates** (PDF/JSON).  
- Provide a **simple one-click interface** for general users.  
- Enable **offline usability** (Bootable ISO/USB).  
- Support **third-party verification** of wipe status.  

## 💡 Proposed Solution  
Our solution is a **secure data wiping system** that combines:  
- **Cryptographic overwriting (AES, multi-pass wipe)** → makes recovery impossible.  
- **Tamper-proof wipe certificates** → digitally signed in PDF & JSON.  
- **Cross-platform support** → Windows, Linux, Android.  
- **Offline mode** → works via bootable ISO/USB.  
- **Optional decentralized verification** → Blockchain/IPFS for auditability.  

## 🛠️ Tech Stack  
- **Languages:** C/C++, Python  
- **Libraries:** OpenSSL, PyCryptodome, ReportLab (for certificates)  
- **Platforms:** Windows, Linux, Android  
- **Optional:** Blockchain/IPFS for decentralized certificate storage  

## 📂 Repository Structure  
