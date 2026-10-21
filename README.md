<div align="center">

# Azwinndini Simon Mufara

### Bioinformatics Researcher · Biomedical AI Developer

📍 Cape Town, South Africa &nbsp;·&nbsp; 🎓 MSc Computational Health Informatics, University of Cape Town (CBIO)

[![ORCID](https://img.shields.io/badge/ORCID-0000--0002--4430--2380-A6CE39?style=for-the-badge&logo=orcid&logoColor=white)](https://orcid.org/0000-0002-4430-2380)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/simon-mufara/)
[![Email](https://img.shields.io/badge/Email-Get%20in%20touch-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:simon.mufara1@gmail.com)
[![OmicsLab](https://img.shields.io/badge/OmicsLab-omicsdatalab.tech-0b7285?style=for-the-badge&logo=googlechrome&logoColor=white)](https://omicsdatalab.tech)
[![DockerHub](https://img.shields.io/badge/DockerHub-simonmufara-2496ED?style=for-the-badge&logo=docker&logoColor=white)](https://hub.docker.com/u/simonmufara)

![Profile Views](https://komarev.com/ghpvc/?username=Simon-Mufara&color=blue&style=flat-square)
![Followers](https://img.shields.io/github/followers/Simon-Mufara?style=flat-square)

<br>

> *Building medical-imaging AI, reproducible genomics pipelines and accessible biomedical tools, with a focus on African health settings and under-resourced care.*

</div>

---

## 👋 About

I'm a bioinformatics researcher and software developer finishing an **MSc in Computational Health Informatics** at the University of Cape Town (Division of Computational Biology), funded by a **DSI-NRF Freestanding Scholarship**.

I build systems that are **usable, reproducible and deployment-ready**, from HPC pipelines and containers to interactive clinical web apps. My research sits where genomics, machine learning and public health meet.

## 🔬 Current focus

| | Project | What it is |
|---|---|---|
| 🫁 | **MSc research** | An automated multimodal machine learning pipeline for **thoracic nodule detection and TB-differential malignancy risk prediction** in South African public health settings: 3D CT imaging combined with clinical data, with uncertainty estimation and reader disagreement. |
| 🦠 | **H3N2 phylodynamics** | Research collaboration on influenza A (H3N2) subclade K phylodynamics in South Africa, with a manuscript in preparation. |
| 🧪 | **OmicsLab** | A learning and community platform for omics and bioinformatics, which I founded and develop. [omicsdatalab.tech](https://omicsdatalab.tech) |
| 🧬 | **BioPredict AI** | A biomedical AI platform integrating pharmacogenomic knowledge bases for drug-outcome mapping *(in development)*. |

## 🚀 Featured work

### 🧪 [OmicsLab](https://omicsdatalab.tech)
A bioinformatics learning and community platform built to make omics training accessible.

**Highlights:** structured study guides (OWAS, computational health informatics) · dataset hubs · quizzes and gamification · AI assistant · research-design tools · community features

### 🌎 [RSV Nicaragua Flow Maps](https://github.com/Simon-Mufara/rsv-nicaragua-flow-maps)
Reproducible R pipeline that turns phylogeographic event lists into publication-ready world flow maps of RSV-A and RSV-B introductions to, and exports from, Nicaragua.

`R` `ggplot2` `sf` `patchwork` `Phylogeography`

### 🔎 [Variant Analysis Suite](https://simon-variants.streamlit.app)
Genomic variant analysis web app for NGS data, with VCF ingestion, annotation, filtering and population frequency lookup. Built alongside a **Nextflow DSL2 whole-genome surveillance pipeline for Rotavirus A** during my internship at the UFS-NGS Unit.

`Python` `Streamlit` `Nextflow` `SnpEff` `bcftools`

### 🔬 [scRNA-seq Clinical Explorer](https://scrna-analysis.streamlit.app)
Interactive single-cell RNA-seq platform covering dimensionality reduction, clustering, differential expression and cell-type annotation.

`Python` `Scanpy` `Streamlit` `UMAP`

### 🧰 Pipelines and containers

| Repository | Description | Stack |
|---|---|---|
| [nf-bacteria-variant-calling](https://github.com/Simon-Mufara/nf-bacteria-variant-calling) | Nextflow DSL2 pipeline for bacterial variant calling on HPC and cloud | `Nextflow` `bcftools` `SLURM` |
| [nf-variant_calling_workflow](https://github.com/Simon-Mufara/nf-variant_calling_workflow) | End-to-end variant calling: preprocessing, alignment, BAM processing | `Nextflow` `samtools` |
| [qc-and-trim-container](https://github.com/Simon-Mufara/qc-and-trim-container) | Containerised sequencing QC and trimming (60+ DockerHub pulls) | `Docker` `Singularity` `FastQC` |

```bash
docker pull simonmufara/qc_and_trim:latest
singularity pull docker://simonmufara/qc_and_trim:latest   # HPC
```

## 🛠️ Tech stack

![Python](https://img.shields.io/badge/-Python-3776AB?style=flat-square&logo=python&logoColor=white)
![R](https://img.shields.io/badge/-R-276DC3?style=flat-square&logo=r&logoColor=white)
![SQL](https://img.shields.io/badge/-SQL-336791?style=flat-square&logo=postgresql&logoColor=white)
![Bash](https://img.shields.io/badge/-Bash-121011?style=flat-square&logo=gnu-bash&logoColor=white)
![JavaScript](https://img.shields.io/badge/-JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![PyTorch](https://img.shields.io/badge/-PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)
![Scikit-learn](https://img.shields.io/badge/-scikit--learn-F7931E?style=flat-square&logo=scikitlearn&logoColor=white)
![Nextflow](https://img.shields.io/badge/-Nextflow-3AC486?style=flat-square)
![Docker](https://img.shields.io/badge/-Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Streamlit](https://img.shields.io/badge/-Streamlit-FF4B4B?style=flat-square&logo=streamlit&logoColor=white)
![FastAPI](https://img.shields.io/badge/-FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![Linux](https://img.shields.io/badge/-Linux-FCC624?style=flat-square&logo=linux&logoColor=black)
![Git](https://img.shields.io/badge/-Git-F05032?style=flat-square&logo=git&logoColor=white)

<details>
<summary><b>Full toolbox</b></summary>
<br>

| Area | Tools |
|---|---|
| **Machine learning** | PyTorch · scikit-learn · XGBoost · Pandas · NumPy · Matplotlib · Seaborn |
| **Medical imaging** | 3D CNNs · vision transformers · multimodal fusion |
| **Bioinformatics** | Scanpy · bcftools · samtools · SnpEff · FastQC · MultiQC · GATK · BWA · STAR |
| **Workflows and infrastructure** | Nextflow · Snakemake · Docker · Singularity · SLURM · HPC · Git |
| **Web and APIs** | Streamlit · FastAPI · Node.js · Next.js · REST |
| **Reporting** | Power BI · Excel · scientific writing |

</details>

## 🎯 Research interests

- Medical-imaging AI for lung disease in high-TB-burden settings
- Genomic epidemiology and phylodynamics of respiratory viruses
- Multi-omics integration and pharmacogenomics
- African precision medicine and bioinformatics infrastructure
- Reproducible, containerised scientific computing

## 📊 GitHub activity

<p align="center">
  <img height="170" src="https://streak-stats.demolab.com?user=Simon-Mufara&theme=dark" />
  &nbsp;&nbsp;
  <img height="170" src="https://github-readme-stats.vercel.app/api?username=Simon-Mufara&show_icons=true&theme=dark&hide_border=true" />
</p>

## 🎓 Education and recognition

- 🎓 **MSc Computational Health Informatics**, University of Cape Town *(current)*
- 🎓 **BSc Honours Bioinformatics**, University of Cape Town
- 🎓 **Bachelor of Health System Sciences**, University of the Witwatersrand
- 🏆 **Top 10 Most Employable Graduate**, GradStar South Africa (2024)
- 💰 **DSI-NRF Freestanding Scholarship**, National Research Foundation
- 🔬 **Internships:** UFS-NGS Unit (a WHO Collaborating Centre) · Johnson & Johnson Innovative Medicine, Global Health Equity

## 🤝 Let's connect

Open to collaboration on medical-imaging AI, genomic surveillance and bioinformatics tooling for African health settings.

📧 [simon.mufara1@gmail.com](mailto:simon.mufara1@gmail.com) &nbsp;·&nbsp; 🔗 [LinkedIn](https://www.linkedin.com/in/simon-mufara/) &nbsp;·&nbsp; 🆔 [ORCID](https://orcid.org/0000-0002-4430-2380)

<div align="center">

*Build with purpose. Document clearly. Make research reproducible. Keep shipping.*

</div>
