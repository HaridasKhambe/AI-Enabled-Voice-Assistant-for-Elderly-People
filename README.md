# AI-Enabled Voice Assistant – Sentiment Analysis Module

## Overview
This repository contains my contribution to a larger AI-enabled voice assistant project designed for elderly people. The focus of my work was **sentiment analysis** to enhance empathetic and context-aware interactions in Hindi.

The sentiment module plays a critical role in detecting emotions from user speech (converted to text), enabling the assistant to respond appropriately and improve user engagement.

---

## Sentiment Analysis Features
- **Domain-Specific Dataset** – Curated Hindi dialogues reflecting elderly communication contexts.
- **Multi-Emotion Classification** – Supports classification into five primary emotional categories.
- **Sarcasm Awareness** – Handles indirect and sarcastic expressions to improve accuracy.
- **Robust Preprocessing** – Tokenization, normalization, and text cleaning tailored for Hindi.
- **Optimized Performance** – Balanced accuracy, precision, recall, and F1 score for real-world usage.

## My Contribution
- **Dataset Creation** – Curated and labeled a 51,100-sample Hindi dialogue dataset across 5 emotions:
  - `0`: Anger  
  - `1`: Joy  
  - `2`: Sadness  
  - `3`: Suspense  
  - `4`: Neutral  
- **Model Development** – Implemented and trained:
  - **BiLSTM + Attention** – Achieved 84.73% accuracy
  - **Fine-tuned IndicBERT** – Achieved 83.71% accuracy
- **Sarcasm Handling** – Improved detection of sarcastic expressions in Hindi.
- **Performance** – Balanced accuracy, precision, recall, and F1 score for robust real-world performance.

---

## High-Level Architecture
- **STT**: Converts spoken Hindi to text.
- **Sentiment Analysis Module** (my work): Detects emotion category.
- **Response Generation**: Generates context-aware Hindi text.
- **TTS**: Outputs speech in a cloned family voice.

---

## Technologies Used
- **Languages**: Python  
- **Deep Learning**: TensorFlow, PyTorch  
- **NLP Models**: BiLSTM + Attention, IndicBERT  
- **Libraries**: Hugging Face Transformers, scikit-learn, NumPy, Pandas  

---

## Results
| Model                   | Accuracy | Precision | Recall | F1-Score |
|------------------------|----------|-----------|--------|----------|
| BiLSTM + Attention     | **84.73%** | 86.0      | 85.0   | 85.0     |
| IndicBERT Fine-tuned   | 83.71%    | 85.36     | 83.71  | 84.13    |

---

## Note
This repository contains only the **sentiment analysis module** and related assets for demonstration purposes. Full system code and proprietary datasets are not included for privacy and intellectual property reasons.

---

## License

## Contact
Feel free to reach out for collaboration opportunities, feedback, or further discussion on this project.  

**Haridas Khambe**  
📧 Email: haridaskhambe@gmail.com  
💼 LinkedIn: [linkedin.com/in/haridas-khambe](https://www.linkedin.com/in/haridas-khambe-aa650926b/)  

