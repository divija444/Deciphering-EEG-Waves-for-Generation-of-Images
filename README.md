# Deciphering-EEG-Waves-for-the-Generation-of-Images
![BCI and EEG Research]() <!-- You can replace this with a relevant banner or image -->

## 📖 Overview
This project explores the uncharted territory of using electroencephalography (EEG) waves to generate images with a focus on open vocabulary. EEG waves, known for their application in studying neuronal and cognitive activities, diagnosing neurological disorders, and understanding human psychology, have immense potential in brain-computer interface (BCI) technology and neurolinguistics. 

Our approach combines meticulous EEG wave pre-processing, text decoding using large language models, and image generation via advanced diffusion models, paving the way for better communication and groundbreaking advancements in BCI research.

---

## 🧠 Key Highlights
- **EEG Pre-Processing**: 
  - Downsampling
  - Band-pass filtering
  - Bad-channel removal
  - Independent Component Analysis (ICA)
- **EEG-to-Text Decoding**:
  - Open vocabulary text generation
  - Pre-trained large language models: **BERT**, **BART**
- **Text-to-Image Generation**:
  - Utilized **Stable Diffusion Model** for generating meaningful images.
- **Datasets**:
  - Leveraged **ZuCo 1.0** and **ZuCo 2.0** datasets for EEG data.
- **Results**:
  - Achieved a **BLEU-1 score of 0.34** on EEG-to-Text decoding tasks.
- **Versatility**: 
  - High potential for handling diverse data types and developing a robust open-vocabulary brain-to-text system with appropriate datasets.

---

## 🚀 Technologies Used
- **Python**: Core implementation.
- **BERT**, **BART**: Large language models for text decoding.
- **Stable Diffusion Model**: For generating images from decoded text.
- **EEG Signal Processing**: Downsampling, ICA, Band-pass Filtering, etc.

---

## 🔧 Installation and Usage
1. **Clone the repository**:
    ```bash
    git clone https://github.com/Gaurav-22-11/EEG-Wave-Image-Generation.git
    cd EEG-Wave-Image-Generation
    ```

2. **Install dependencies**:
    ```bash
    pip install -r requirements.txt
    ```

3. **Run Pre-processing**:
    Use the pre-processing scripts provided to clean and analyze EEG data.

4. **Train/Run Models**:
    Follow the steps in `scripts/train.md` or `scripts/run.md` for EEG-to-Text and Text-to-Image generation.

5. **Visualize Results**:
    Output images and decoded text will be saved in the `output/` directory.

---

## 📊 Results
| Metric        | Value  |
|---------------|--------|
| BLEU-1 Score  | 0.34   |
| Dataset       | ZuCo 1.0 & ZuCo 2.0 |

---

-

## ✨ Future Work
- Integration of larger, diverse datasets for improved model performance.
- Real-time brain-to-text and brain-to-image decoding systems.
- Enhancing the BLEU score and exploring alternative evaluation metrics.

---

## 📚 References
- **ZuCo Datasets**: [Zurich Cognitive Language Processing Datasets](https://www.cl.uzh.ch/en/research/zuco.html)
- **BERT**: [BERT by Google AI](https://github.com/google-research/bert)
- **Stable Diffusion**: [Stable Diffusion on GitHub](https://github.com/CompVis/stable-diffusion)

---

## 🤝 Contributing
Contributions, issues, and feature requests are welcome!  
Feel free to check the [issues page](https://github.com/Gaurav-22-11/EEG-Wave-Image-Generation/issues) for open tasks.

---

## 📜 License
This project is licensed under the [MIT License](LICENSE).

---

## 🧑‍💻 Author
**Gaurav Dnyanesh Mahajan**  
- [GitHub](https://github.com/Gaurav-22-11)  
- [LinkedIn](https://linkedin.com/in/gauravdnyaneshmahajan)  
