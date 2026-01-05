# Speech Emotion Recognition

A project focused on reproducing enhanced data generation techniques using Variational Autoencoders (VAEs) and Diffusion Models for speech emotion recognition.

## Overview

This repository implements and reproduces methods for speech emotion recognition using advanced generative models. The project explores data augmentation techniques through VAEs and diffusion models to improve emotion classification from speech signals.

## Project Structure

```
. 
├── EmoDB/                          # EmoDB dataset directory
├── RAVDESS/                        # RAVDESS dataset directory
├── speech-emotion-recognition.ipynb # Main implementation notebook
└── electronics-13-01314-v3.pdf     # Reference paper
```

## Datasets

The project utilizes two well-known speech emotion datasets: 

### EmoDB (Berlin Database of Emotional Speech)
- German language emotional speech database
- Contains recordings from professional actors
- Multiple emotion categories

### RAVDESS (Ryerson Audio-Visual Database of Emotional Speech and Song)
- English language emotional speech and song
- Multi-modal dataset with audio-visual recordings
- 8 emotion categories

## Getting Started

### Prerequisites

```bash
# Install required dependencies
pip install numpy pandas matplotlib scikit-learn
pip install tensorflow torch librosa
pip install jupyter notebook
```

### Usage

1. Clone the repository:
```bash
git clone https://github.com/yousra0/Speech-Emotion-Recognition.git
cd Speech-Emotion-Recognition
```

2. Open the Jupyter notebook:
```bash
jupyter notebook speech-emotion-recognition.ipynb
```

3. Follow the notebook cells to: 
   - Load and preprocess the datasets
   - Train VAE and diffusion models
   - Generate synthetic speech data
   - Evaluate emotion recognition performance

## Methodology

This project implements:
- **Variational Autoencoders (VAEs)** for learning latent representations of emotional speech
- **Diffusion Models** for high-quality synthetic speech generation
- **Data Augmentation** techniques to improve model generalization
- **Emotion Classification** using the augmented datasets

## Reference

The implementation is based on research in enhanced data generation for speech emotion recognition.  See `electronics-13-01314-v3.pdf` for detailed methodology and theoretical background.

## Results

Results and performance metrics can be found within the Jupyter notebook, including:
- Model training curves
- Classification accuracy
- Confusion matrices
- Sample generations

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request. 

## License

This project is available for academic and research purposes. 

## Contact

For questions or collaboration opportunities, please open an issue in this repository.
```
