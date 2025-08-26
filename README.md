# Comparative Analysis of Diffusion Models for Audio Denoising

This repository contains the research page for our study on the efficacy of diffusion models for audio denoising, comparing a baseline diffusion model with an enhanced model incorporating Connectionist Temporal Classification (CTC) loss.

## 🔗 Live Demo

Visit the live research page: [https://[your-username].github.io/paper_page](https://[your-username].github.io/paper_page)

## 📋 Abstract

This study investigates the efficacy of diffusion models for audio denoising. We present a comparative analysis between a baseline diffusion model and an enhanced model incorporating a Connectionist Temporal Classification (CTC) loss function. The objective is to evaluate the impact of CTC loss on model performance at various stages of training.

## ✨ Features

- **Interactive Audio Samples**: Compare clean, noisy, and denoised audio across different training epochs
- **Real-time Waveform Visualization**: Powered by SeeWav for interactive audio waveforms
- **Adobe Audition-style Spectrograms**: High-resolution STFT spectrograms with streaming computation
- **Interactive Charts**: Dynamic Frechet VGGish Score comparison using Chart.js
- **Responsive Design**: Mobile-friendly layout using Bulma CSS framework

## 📊 Results

The quantitative results show that the CTC Loss-Improved model achieves a consistently lower Frechet VGGish Score, indicating closer statistical similarity to clean audio. This is corroborated by perceptual evaluation of the audio samples.

## 🎵 Audio Samples

The page includes:
- **Reference Audio**: Clean original and noisy input samples
- **Model Outputs**: Baseline and CTC-enhanced model outputs at epochs 0, 10, and 20
- **Interactive Controls**: Synchronized audio playback with waveform and spectrogram visualization

## 🛠️ Technologies Used

- **Frontend**: HTML5, CSS3 (Bulma), JavaScript
- **Audio Visualization**: SeeWav.js for waveforms
- **Spectrograms**: Custom STFT implementation with streaming
- **Charts**: Chart.js for interactive data visualization
- **Hosting**: GitHub Pages

## 🚀 Local Development

1. Clone the repository:
   ```bash
   git clone https://github.com/[your-username]/paper_page.git
   cd paper_page
   ```

2. Serve the files using a local HTTP server:
   ```bash
   # Using Python 3
   python3 -m http.server 8000
   
   # Using Node.js (if you have http-server installed)
   npx http-server
   ```

3. Open your browser and navigate to `http://localhost:8000`

## 📁 Project Structure

```
├── index.html                 # Main research page
├── static/
│   ├── css/                  # Stylesheets (Bulma + custom)
│   ├── js/                   # JavaScript libraries
│   ├── images/               # Images and figures
│   ├── baseline_model/       # Baseline model audio outputs
│   ├── ctc_loss/            # CTC model audio outputs
│   └── graphs/              # CSV data for interactive charts
└── README.md
```

## 📄 Citation

If you use this work in your research, please cite:

```bibtex
@misc{aspis2025diffusion,
  title={Comparative Analysis of Diffusion Models for Audio Denoising},
  author={Elad Aspis},
  year={2025},
  institution={Bar Ilan University},
  url={https://[your-username].github.io/paper_page}
}
```

## 📧 Contact

**Elad Aspis**  
Bar Ilan University  
[Your Email]

## 📜 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
