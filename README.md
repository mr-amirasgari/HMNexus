# HMNexus 🧬💻  
> A **graphical, code-free**, and **high-speed** desktop application for downloading TCGA data from the Genomic Data Commons (GDC).

[![License](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)
[![Python 3.9+](https://img.shields.io/badge/Python-3.9%2B-green)](https://www.python.org/)
[![tkinter](https://img.shields.io/badge/GUI-tkinter-orange)](https://docs.python.org/3/library/tkinter.html)
![GitHub Release](https://img.shields.io/github/v/release/Siamak-salimy/HMNexus)

HMNexus empowers biologists, clinicians, and researchers **without programming expertise** to access The Cancer Genome Atlas (TCGA) data through an intuitive point-and-click interface. Built with **Python + tkinter**, it supports **manifest-based parallel downloads** directly from the GDC portal—up to **× faster** than standard tools—while automatically organizing files for downstream analysis.


---

## ✨ Key Features

- ✅ **Zero coding required** – fully graphical interface  
- ⚡ **High-speed concurrent downloads** via GDC manifest files  
- 🧩 **Interactive filtering** by cancer type, data category (e.g., RNA-seq, clinical, methylation), and sample attributes  
- 🔒 **MD5 checksum validation** for data integrity  
- 📦 **Standalone executables** available (no Python needed)  
- 🆓 **Open-source** under MIT License

  
---

## 📊 Performance Benchmark

| Tool | Interface | Time (for 18.2 GB BRCA data) | Coding Required |
| :--- | :--- | :--- | :--- |
| HMNexus | GUI (Tkinter) | 12 min 18 sec | No |
| GDC Data Transfer Tool | CLI | 58 min 42 sec | Yes |
| TCGAbiolinks (R) | Scripted | ~54 min | Yes |

> *Note: Performance may vary depending on your network bandwidth and system resources.*

---

## 🛠️ Technology & Language

- Programming Language: Python 3.9+
- GUI Framework: Tkinter
- Download Engine: Manifest-based concurrent HTTP downloads
- Packaging: PyInstaller
- License: MIT

---

## 🚀 Quick Start

### Option 1: Download Executable (Recommended)
1. Go to [Releases](https://github.com/Siamak-salimy/HMNexus/releases)
2. Download the file for your OS:
   - 🪟 **Windows**: `HMNexus-*-Windows.exe`

3. Run it — no installation or Python required!

---

## 👨‍💻 Development Team

- Siamak Salimy (Team Lead)
- Amirmohammad Asgari
- Mohammadreza Shahbazi
- Abolfazl Ghasemi
- Mahan Mirzade

---
🔗 Official TCGA Data Portal (GDC):
<https://portal.gdc.cancer.gov/>
---

## 📜 Citation

If you use HMNexus in your academic research, please cite our paper:

> Salimy S., Asgari A., Shahbazi M., Ghasemi A., & Mirzade M. (2025). HMNexus: A Tkinter GUI Platform for High-Speed, Code-Free TCGA Data Download. *BMC Bioinformatics*.

---

## 📄 License

© 2025 HMNexus Project
