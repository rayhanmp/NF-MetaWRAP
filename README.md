# NF-MetaWRAP

A **Nextflow implementation** of the MetaWRAP pipeline (Uritskiy et al., 2018) designed for **reproducible and scalable** metagenomic data analysis across diverse environments.
<p align="center">
  <a href ="https://www.gnu.org/licenses/gpl-3.0"><img src="https://img.shields.io/badge/License-MIT-blue.svg" alt="License - MIT"></a>
  <img src="https://img.shields.io/badge/status-alpha-orange" alt="Status - Alpha"></a>
</p>

---

## ⚙️ Installation Guide

1. **Clone the Repository:**

```bash
git clone https://github.com/rayhanmp/NF-MetaWRAP.git
cd NF-MetaWRAP
```

2. **Install Nextflow:**

```bash
curl -s https://get.nextflow.io | bash
```

3. **Set Up Conda:**

  ```bash
  conda create -n nf-metawrap-env -c bioconda nextflow
  conda activate nf-metawrap-env
  ```

4. **(Optional) Verify Installation:**

```bash
nextflow run main.nf -profile test
```

---

## 📚 Citation & Credits

If you use **NF-MetaWRAP** in your work, please cite the original MetaWRAP paper:

> Uritskiy, G. V., DiRuggiero, J., & Taylor, J. (2018). MetaWRAP—a flexible pipeline for genome-resolved metagenomic data analysis. *Microbiome*, **6**(1), 158. [https://doi.org/10.1186/s40168-018-0541-1](https://doi.org/10.1186/s40168-018-0541-1)

If you'd like to credit **NF-MetaWRAP** specifically, please mention this repository in your work with:

> "This research utilized the NF-MetaWRAP pipeline ([GitHub Repository](https://github.com/rayhanmp/NF-MetaWRAP)) for metagenomic data analysis."

---

## 📜 License

This project is licensed under the MIT License.
