#  RISE Tutorials

[![Build Status](https://img.shields.io/github/actions/workflow/status/YouvenZ/rise_tutorials/deploy.yml?branch=main&label=build)](https://github.com/YouvenZ/rise_tutorials/actions)
[![License: CC-BY-4.0](https://img.shields.io/badge/License-CC--BY%204.0-lightgrey.svg)](https://creativecommons.org/licenses/by/4.0/)
[![Contributors](https://img.shields.io/github/contributors/YouvenZ/rise_tutorials)](https://github.com/YouvenZ/rise_tutorials/graphs/contributors)
[![Website](https://img.shields.io/website?url=https%3A%2F%2Frise-miccai.github.io%2Frise-tutorials-website%2Fintro.html)](https://rise-miccai.github.io/rise-tutorials-website/intro.html)

**RISE Tutorials** is a collaborative, open-source educational platform developed by the [RISE-MICCAI](https://rise-miccai.github.io/rise-tutorials-website/intro.html) initiative. Our mission is to **democratize access to high-quality tutorials** in medical image analysis and AI.

Explore the live book 👉 [**RISE Tutorials Website**](https://rise-miccai.github.io/rise-tutorials-website/intro.html)

---

## 📘 About This Project

This repository hosts the source code and content for the **RISE Tutorials Book**, a continuously evolving resource built with [Jupyter Book](https://jupyterbook.org/).

It’s designed to be:

- 🔁 **Modular** – Each tutorial is independent and easy to expand
- 💻 **Interactive** – Code, markdown, figures, and widgets in one place
- 🌍 **Community-driven** – Contributions from researchers, students, and professionals worldwide

---

## 🧠 What You'll Learn

Our tutorials span a wide range of foundational and advanced topics, such as:

- 🏥 Handling medical datasets (DICOM, NIfTI, etc.)
- 📑 Cleaning, labeling, and preprocessing data
- ⚠️ Avoiding pitfalls like data leakage and overfitting
- 📊 Using evaluation metrics (AUROC, sensitivity, specificity)
- ⚖️ Dealing with class imbalance and rare disease data
- 🧠 Building and validating classification/segmentation models
- 🔍 Applying model explainability tools (e.g., saliency maps, Grad-CAM)
- 🧪 Ensuring reproducibility and robust validation

…and more to come!

---

## 🛠️ Getting Started

Follow these steps to build and run the book locally:

```bash
# 1. Clone the repository
git clone https://github.com/YouvenZ/rise_tutorials.git
cd rise_tutorials

# 2. Install required dependencies (use a virtual environment if possible)
pip install -r requirements.txt

# 3. (Optional) Edit content in the `rise_tutorials/` directory

# 4. Clean previous builds
jupyter-book clean rise_tutorials/

# 5. Build the HTML book
jupyter-book build rise_tutorials/
```

📁 The rendered site will appear in: `rise_tutorials/_build/html/`

---

## 🌐 Hosting the Book

You can publish the book using:

- **GitHub Pages** (default)
- **GitLab Pages**
- **Netlify**

For GitHub CI/CD deployment, we use [cookiecutter-jupyter-book](https://github.com/executablebooks/cookiecutter-jupyter-book), which includes GitHub Actions workflows to auto-deploy on push.

Refer to [Jupyter Book’s official deployment guide](https://jupyterbook.org/publish/web.html) for full instructions.

---

## 🧾 Tutorial Index

Here’s a preview of our current and planned tutorials:

| Tutorial | Description | Status |
|----------|-------------|--------|
| Medical image classification | What are the best practices, a beginner guide | ✅ Completed |
| Data Preprocessing 101 | Cleaning, normalizing, and splitting | 🚧 In progress |
| Evaluation Metrics in Medical AI | AUROC, sensitivity, etc. | 🚧 In progress |
| Explainability with Grad-CAM | Model interpretation | 🔜 Planned |
| Handling Class Imbalance | SMOTE, weighting, and tricks | 🔜 Planned |

> 🗂️ Want to suggest a topic? [Submit here »](https://docs.google.com/forms/d/e/1FAIpQLSc7dT94w_EPQ1ISN9NFEbbDkE1OcmYVuDRGkDSQ41P2i0lk0g/viewform)

---

## 🤝 Contributing

We’d love to have your contributions — whether you’re a student, researcher, or industry expert!

### 🧩 Ways to Contribute

- Add a new tutorial (e.g., segmentation, image registration)
- Improve content clarity, fix typos, or correct code
- Translate existing content to other languages
- Submit feedback, bug reports, or feature ideas

### 📬 Join the Initiative

📝 [Contributor Sign-Up Form](https://docs.google.com/forms/d/e/1FAIpQLSc7dT94w_EPQ1ISN9NFEbbDkE1OcmYVuDRGkDSQ41P2i0lk0g/viewform)  
👥 View our [Contributors](https://github.com/YouvenZ/rise_tutorials/graphs/contributors)

---

## 📣 Community & Communication

Stay connected and grow with us:

- 💬 **Discussion forum** *(coming soon!)*
- 💡 **Join our Slack/Discord** *(planned – DM us to get early access)*
- 📅 Events & workshops at [MICCAI](https://www.miccai.org/)
- 🗣️ Feedback and mentorship welcome!

---

## 📜 License

All content is released under the **Creative Commons Attribution 4.0 International (CC BY 4.0)** license.  
You are free to share and adapt the material, with proper attribution.

For code, please refer to individual notebooks/scripts for license specifics.

---

## 🔖 Citation

If you use RISE Tutorials in your research or teaching, please cite us:

```bibtex
@misc{rise_tutorials,
  author       = {MICCAI-RISE Community},
  title        = {RISE Tutorials: Open Educational Resources for Medical Imaging AI},
  year         = {2025},
  howpublished = {\url{https://rise-miccai.github.io/rise-tutorials-website/}},
  note         = {Version 1.0}
}
```

---

## 📏 Code of Conduct

We are committed to fostering a welcoming and respectful community.  
Please review our [Code of Conduct](CODE_OF_CONDUCT.md) before participating.

---

## 🙏 Acknowledgments

RISE Tutorials is made possible by:

- 🛠️ [Jupyter Book](https://jupyterbook.org/)
- 💡 [Executable Books Project](https://executablebooks.org/)
- 🤖 Contributions from the global MICCAI & RISE community

---

## 🚀 Vision

We aim to:

- Publish a **comprehensive tutorial book** for MICCAI attendees and researchers
- Support **community learning** through hybrid events
- Foster **collaborative authorship** in scientific education

Be part of something bigger. Let’s build the future of medical AI education — together.