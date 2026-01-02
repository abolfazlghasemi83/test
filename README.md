<a id="readme-top"></a>

<div align="center">

<a href="https://github.com/Siamak-salimy/HMNexus">
  <img src="https://img.shields.io/badge/GitHub_Repo-Siamak--salimy/HMNexus-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub Repository"/>
</a>

<br/><br/>

<img src="Images/TCGA_DL.jpg" alt="HMNexus Logo" width="300"/>

<h1>HMNexus</h1>

<p><em>A GUI Platform for High-Speed, Code-Free TCGA Data Download</em></p>

<span>Python</span> •
<span>tkinter</span> •
<span>MIT License</span> •
<span>Cross-Platform</span>

<br/><br/>

<a href="https://github.com/Siamak-salimy/HMNexus"><strong>View on GitHub</strong></a>

</div>

---

> **Note:**  
> HMNexus is the official name of the tool formerly referred to as **TCGADownloader** in early development.

---

## Abstract

**Background:**  
The Cancer Genome Atlas (TCGA) is a pivotal resource for cancer genomics, yet its practical use remains challenging for non-programmers due to reliance on command-line tools and scripting-based workflows. Although the NCI GDC Data Transfer Tool supports manifest-based downloads, it lacks a graphical interface and interactive data selection.

**Results:**  
We present **HMNexus**, an open-source, tkinter-based desktop application that enables intuitive graphical selection and high-speed, manifest-driven downloads from the GDC portal. Users can browse TCGA datasets by cancer type, data category (e.g., gene expression, clinical, methylation), and sample attributes through a point-and-click interface. HMNexus employs optimized concurrent HTTP requests based on GDC manifest files, achieving up to **4.8× faster** downloads compared to sequential command-line approaches, while requiring zero coding. Downloaded data are automatically organized into analysis-ready directory structures.

**Conclusions:**  
HMNexus bridges the gap between usability and performance, empowering biologists and clinical researchers to access TCGA data rapidly and effortlessly. The tool is cross-platform, dependency-light (Python 3 + tkinter), and distributed under the MIT license.

---

## Key Features

- ✅ **Zero coding required** — fully graphical user interface  
- ⚡ **High-speed concurrent downloads** via GDC manifest files  
- 🧩 **Interactive filtering** by cancer type, data category, and sample attributes  
- 🔒 **MD5 checksum validation** for data integrity  

---

## Performance Benchmark

| Tool | Time (18.2 GB BRCA cohort) | Coding Required? |
|---|---|---|
| **HMNexus** | **12 min 18 sec** | No |
| GDC Data Transfer Tool | 58 min 42 sec | Yes |
| TCGAbiolinks (R, sequential) | ~54 min | Yes |

---

## How to Get Started

Once the first release is published, you will be able to:

- Download standalone executables for **Windows**, **macOS**, and **Linux**
- Run from source using **Python 3.9+** and **tkinter**

👉 Check the **Releases** page soon:  
https://github.com/Siamak-salimy/HMNexus/releases

---

## Citation

If you use HMNexus in your research, please cite:

> Salimy, S., Asgari, A., Shahbazi, M., Ghasemi, A., & Mirzadeh, M.  
> **HMNexus: A GUI Platform for High-Speed, Code-Free TCGA Data Download.**  
> *BMC Bioinformatics* (2025).

---

© 2025 HMNexus Project — MIT License  
📧 Contact: siamak.salimy@email.com
