# 🧬 HMNexus (formerly TCGA-DL)

*A GUI Platform for High-Speed, Code-Free TCGA Data Download*

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Python Version](https://img.shields.io/badge/python-3.9+-blue.svg)](https://www.python.org/downloads/)
[![Platform](https://img.shields.io/badge/platform-windows%20%7C%20macos%20%7C%20linux-lightgrey.svg)](https://github.com/Siamak-salimy/HMNexus)

🔗 **Project Page & Download:**
<https://siamak-salimy.github.io/HMNexus/>

🔗 **Official TCGA Data Portal (GDC):**
<https://portal.gdc.cancer.gov/>

---

## 🚀 Announcement

We built a cross-platform **desktop application** for downloading TCGA data. Accessing these datasets traditionally required command-line tools and scripting. **HMNexus** was designed to eliminate that barrier by providing a **fully graphical Tkinter-based interface**, allowing researchers to download TCGA data **with zero coding required**.

---

## Overview

**HMNexus** (formerly TCGADownloader during early development) is a modern, open-source, and high-performance desktop application for downloading **The Cancer Genome Atlas (TCGA)** data directly from the **NCI Genomic Data Commons (GDC)**.

Developed using **Python and Tkinter**, HMNexus provides a **code-free, GUI-driven workflow** for manifest-based TCGA downloads. This feature makes large-scale cancer genomics data accessible to:
- Biologists
- Clinicians
- Medical Researchers
- Students and Trainees

---

## Abstract

**Background:** The Cancer Genome Atlas (TCGA) is a foundational resource for cancer genomics research. However, downloading TCGA data typically requires command-line tools or scripting, limiting accessibility for non-technical users. While the NCI's GDC Data Transfer Tool supports manifest-based downloads, it lacks a graphical interface and provides no interactive dataset exploration.

**Results:** We present **HMNexus**, an open-source, Tkinter-based desktop application that combines intuitive graphical data selection with high-speed, manifest-driven downloads from the GDC portal. Users can browse and filter TCGA datasets by cancer type and data category, import or export GDC manifest files, and perform optimized concurrent downloads through a point-and-click interface. Benchmark experiments on a BRCA cohort (18.2 GB) demonstrate up to a **4.8× reduction in download time** compared to sequential command-line workflows. Downloaded files are automatically organized into analysis-ready directory structures.

**Conclusions:** HMNexus bridges the gap between usability and performance, enabling rapid and effortless access to TCGA data. The tool is cross-platform, lightweight (Python 3 + Tkinter), and distributed under the MIT License.

---

## 🌟 Key Features

- ✅ **Zero Coding Required** — Fully graphical interface built with Tkinter.
- ⚡ **High-Speed Concurrent Downloads** — Utilizes official GDC manifest files for optimized performance.
- 🧾 **Manifest-Driven Workflow** — Import and export official GDC manifest files.
- 📁 **Automatic Directory Organization** — Files are sorted into logical folders (e.g., `BRCA/clinical/` or `LUAD/rnaseq/`).
- 🔒 **MD5 Checksum Validation** — Ensures data integrity and corruption-free downloads.
- 🌐 **Cross-Platform** — Runs on Windows, macOS, and Linux.
- 📦 **Standalone Executables** — No Python installation required.
- 🆓 **Open-Source** — Released under the permissive MIT License.

---

## 📊 Performance Benchmark

| Tool | Interface | Time (for 18.2 GB BRCA data) | Coding Required |
| :--- | :--- | :--- | :--- |
| **HMNexus** | **GUI (Tkinter)** | **12 min 18 sec** | **No** |
| GDC Data Transfer Tool | CLI | 58 min 42 sec | Yes |
| TCGAbiolinks (R) | Scripted | ~54 min | Yes |

> *Note: Performance may vary depending on your network bandwidth and system resources.*

---

## 🛠️ Technology & Language

- **Programming Language:** Python 3.9+
- **GUI Framework:** Tkinter
- **Download Engine:** Manifest-based concurrent HTTP downloads
- **Packaging:** PyInstaller
- **License:** MIT

---

## 🚀 Installation & Quick Start

### **Option 1 — Standalone Executable (Recommended)**

Download and run the executable for your operating system from the link below. No Python installation is required.

<https://siamak-salimy.github.io/HMNexus/>

### **Option 2 — Run from Source**

1.  First, clone the repository:
    ```bash
    git clone https://github.com/Siamak-salimy/HMNexus.git
    ```
2.  Navigate to the project directory:
    ```bash
    cd HMNexus
    ```
3.  Install the required packages:
    ```bash
    pip install -r requirements.txt
    ```
4.  Run the application:
    ```bash
    python main.py
    ```

---

## 👨‍💻 Development Team

- **Siamak Salimy** (Team Lead)
- **Amirmohammad Asgari**
- **Mohammadreza Shahbazi**
- **Abolfazl Ghasemi**
- **Mahan Mirzade**

---

## 📜 Citation

If you use HMNexus in your academic research, please cite our paper:

> Salimy S., Asgari A., Shahbazi M., Ghasemi A., & Mirzade M. (2025). HMNexus: A Tkinter GUI Platform for High-Speed, Code-Free TCGA Data Download. *BMC Bioinformatics*.

---

## 📄 License

© 2025 HMNexus Project

Released under the [MIT License](https://opensource.org/licenses/MIT).
