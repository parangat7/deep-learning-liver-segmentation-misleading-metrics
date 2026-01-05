# A Deep Learning Framework for Automated Liver Segmentation

## 📄 Research Paper
**Title:** A Deep Learning Framework for Automated Liver Segmentation for Surgical Planning:  
*A Case Study on Misleading Metrics*

This repository contains the research paper, implementation notebook, and visualization
for a case study on misleading evaluation metrics in medical image segmentation.

## 🧠 Key Idea
Despite achieving a high Dice coefficient (~0.91) and binary accuracy (~0.99),
the trained U-Net model completely failed at liver segmentation.
This work highlights the dangers of relying solely on quantitative metrics
under severe class imbalance.

## 📁 Contents
- `paper/` – Camera-ready research paper (PDF)
- `notebook/` – Jupyter Notebook implementation
- `visualization/` – HTML visualization of misleading metrics

## 📊 Misleading Metrics Demonstration
The model learns to segment the entire patient body instead of the liver,
yet still achieves high Dice scores due to foreground–background imbalance.

➡️ See: `visualization/Liver_Segmentation.html`

## 🏅 Conference Presentation Certificate
This research paper was formally presented at an international conference.

- **Conference:** International Conference on Sustainable Developments in Computer Engineering,  
  Green Technology & Smart Systems (ICSDS-2025)
- **Dates:** December 20–21, 2025
- **Organizer:** Hooghly Engineering & Technology College, West Bengal, India

📄 Certificate: `certificate/ICSDS_2025_Presentation_Certificate_Parangat_Thakur`

## ⚠️ Important Takeaway
Quantitative metrics alone are insufficient for medical image segmentation.
Strict qualitative (visual) validation is mandatory.

## 📜 License
MIT License

## 🌐 Live Demo (GitHub Pages)
Interactive HTML visualization demonstrating misleading evaluation metrics:

🔗 https://parangat7.github.io/deep-learning-liver-segmentation-misleading-metrics/Liver_Segmentation.html
