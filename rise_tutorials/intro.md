# RISE-MICCAI Tutorial Hub

<p align="center">
  <img src="https://img.shields.io/badge/RISE-MICCAI-6c3fc5?style=for-the-badge&logo=python&logoColor=white" alt="RISE-MICCAI"/>
  <img src="https://img.shields.io/badge/Medical%20Imaging-AI-1ab3a4?style=for-the-badge&logo=pytorch&logoColor=white" alt="Medical Imaging AI"/>
  <img src="https://img.shields.io/badge/Open%20Source-Community-f5a623?style=for-the-badge&logo=github&logoColor=white" alt="Open Source"/>
</p>

---

## What is RISE?

**RISE-MICCAI** is a dedicated initiative to increase the representation and participation of researchers from under-represented regions in the Medical Image Computing and Computer-Aided Interventions (MICCAI) community — including **Latin America**, **South/Southeast Asia**, **Africa**, and the **Middle East**.

```{admonition} Why RISE Matters
:class: note
In MICCAI 2020, submissions from under-represented regions accounted for only **4%** of total papers, with just 6 out of 103 countries represented in accepted papers. RISE-MICCAI bridges this gap by fostering inclusiveness, support, and community-driven resources.
```

---

## Our Goals

```{grid} 2 2 3 3
:gutter: 3

:::{grid-item-card} 🌍 Geographic Diversity
Promote participation from under-represented regions in MICCAI conferences and research initiatives.
:::

:::{grid-item-card} 💡 Empower Researchers
Offer mentorship, funding opportunities, and community-driven support for researchers in LMICs.
:::

:::{grid-item-card} 🚀 Future Leaders
Cultivate emerging talents in LMICs, helping them gain visibility and recognition in the field.
:::

:::{grid-item-card} 🤝 Research Network
Foster collaborations across regions, institutions, and continents to address global disparities in medical imaging.
:::

:::{grid-item-card} 📚 Open Knowledge
Provide freely accessible, high-quality tutorials in AI for medical imaging to democratize education.
:::

:::{grid-item-card} 🔬 Cutting-Edge AI
Cover the full spectrum from classical CNNs to the latest foundation models and diffusion architectures.
:::
```

---

## Tutorials

All tutorials are designed to be run interactively. Each notebook includes **Google Colab** and **Binder** launch buttons so you can run them in the cloud with zero setup.

```{grid} 1 1 2 2
:gutter: 4

:::{grid-item-card} 🩺 Image Classification with CNNs
:link: Beginner_tuto/tutorial-rise-classification
:link-type: doc

An end-to-end deep learning classification pipeline for medical images. Covers CNN architectures, data augmentation, training, and evaluation.

+++
{bdg-primary}`Classification` {bdg-secondary}`CNN` {bdg-success}`Beginner`
:::

:::{grid-item-card} 👁️ Retina Classification — Diabetic Retinopathy
:link: Beginner_tuto/Retina_classification_using_CNN_
:link-type: doc

Detect diabetic retinopathy from retinal fundus images using CNNs and pretrained models. Includes class activation maps (CAMs) for interpretability.

+++
{bdg-primary}`Retina` {bdg-secondary}`CNN` {bdg-warning}`Colab Ready` {bdg-success}`Beginner`
:::

:::{grid-item-card} 🔬 Multiple Instance Learning — torchmil
:link: Beginner_tuto/tutorial-torchmil
:link-type: doc

Train an attention-based MIL model to detect breast cancer metastases from Whole Slide Images (WSIs) using the CAMELYON16 dataset and the **torchmil** library.

+++
{bdg-primary}`Histopathology` {bdg-secondary}`MIL` {bdg-info}`WSI` {bdg-success}`Beginner`
:::
```

---

## Covered Topics

Across current and upcoming tutorials, the hub covers:

| Category | Topics |
|---|---|
| **Classification** | CNNs, ResNet, EfficientNet, Transfer Learning |
| **Segmentation** | U-Net, nnU-Net, pixel-wise labelling |
| **Interpretability** | Grad-CAM, CAM, SHAP, LIME |
| **MIL / Pathology** | Attention MIL, CAMELYON, WSI pipelines |
| **Self-Supervised** | Contrastive Learning, MAE |
| **3D & Video** | Volumetric CNNs, 3D Transformers |
| **LLMs & Generative** | Report generation, Diffusion models, GANs |
| **Fairness & Bias** | Dataset bias, fairness metrics, mitigation |

---

## How to Run the Tutorials

```{admonition} Two ways to run every notebook
:class: tip

**Option 1 — Google Colab (recommended)**
Click the {bdg-warning}`Open in Colab` button at the top of any notebook page. A free GPU is available in Colab.

**Option 2 — Binder**
Click the {bdg-info}`Launch Binder` button to run an interactive environment in your browser with no local installation needed.

**Option 3 — Locally**
Clone the repository and run notebooks inside your own Python environment. See the README for dependency instructions.
```

---

## Contribute

```{admonition} Join the community
:class: important
You can contribute by:
- 📝 **Adding tutorials** — submit a notebook following the [contribution guide](https://github.com/RISE-MICCAI/rise-tutorials-website/blob/main/CONTRIBUTING.md)
- 🛠️ **Improving content** — fix typos, improve code, or add explanations
- 🌐 **Translating** — help make content accessible in more languages
- 💬 **Opening issues** — report problems or suggest improvements on [GitHub](https://github.com/RISE-MICCAI/rise-tutorials-website/issues)
```

