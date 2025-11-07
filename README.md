# 🌍 Yale-UNC-CH — Geophysical Waveform Inversion (Kaggle 2025)

This repository contains my solution and research artifacts for the [Kaggle Image Matching Challenge 2025](https://www.kaggle.com/competitions/image-matching-challenge-2025), adapted to the domain of geophysical waveform inversion. The project explores deep learning techniques for matching and interpreting seismic waveform data across complex geological settings.

## 🧠 Project Goal

Apply image matching and attention-based architectures to geophysical waveform inversion tasks, with the aim of:

- 🔍 Enhancing subsurface imaging resolution
- 🧭 Improving inversion accuracy across heterogeneous media
- 🧠 Leveraging Transformer-based models for spatial-temporal pattern recognition

## 📁 Repository Structure

```
Yale-UNC-CH---Geophysical-Waveform-Inversion/
├── CAFormer_code.ipynb         # Cross-attention model for waveform inversion
├── Convnext_code.ipynb         # ConvNeXt baseline adaptation
├── Code2.ipynb                 # Experimental pipeline and visualization
├── 000039dca2.npy              # Sample waveform data
├── README.md                   # Project documentation
└── README_assets/              # Diagrams, figures, and architecture illustrations
```

## 🛠️ Methods & Models

- 🧬 **CAFormer**: A cross-attention Transformer tailored for waveform matching and inversion
- 🌀 **ConvNeXt**: Adapted for spatial feature extraction from seismic slices
- 🧪 **Hybrid Pipeline**: Combines classical inversion priors with deep learning-based refinement

## 📊 Results & Evaluation

- Benchmarked on synthetic and real seismic datasets
- Visualized inversion accuracy using error maps and waveform overlays
- Compared attention-based models with convolutional baselines

## 📦 Setup Instructions

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/Yale-UNC-CH---Geophysical-Waveform-Inversion.git
   cd Yale-UNC-CH---Geophysical-Waveform-Inversion
   ```

2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

3. Run notebooks:
   Open `.ipynb` files in Jupyter or VSCode to explore models and results.

## 📌 Notes

- Data format: `.npy` files containing waveform arrays
- Visualization tools: Matplotlib, Seaborn, Plotly
- Model training: GPU recommended for CAFormer experiments

## 🤝 Acknowledgments

- Kaggle organizers and the Image Matching Challenge 2025 community
- Yale, UNC, and CH collaborators for seismic data and domain insights
- Open-source contributors for baseline architectures

## 📄 License

This project is released under the MIT License. For academic use, please cite appropriately.
