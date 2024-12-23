# 🎵 Intelligent Explicit Lyrics Analysis

## 📚 **Project Overview**
This is an advanced Natural Language Processing (NLP) project designed to classify explicit content in song lyrics into four key categories:  
- **Sexual Content**  
- **Violence**  
- **Substance Use**  
- **Explicit Language**  

Using state-of-the-art transformer-based models (BERT, BigBird, and Longformer), this project analyzes lyrical content to detect both explicit keywords and contextual nuances. The ultimate goal is to enhance content filtering tools and provide insights into explicit lyrical trends.

---

## 🚀 **Key Features**
- **Multi-Label Classification:** Classifies song lyrics into multiple explicit categories simultaneously.  
- **Bootstrapping for Label Refinement:** Iteratively refines labels using semantic similarity with Sentence-BERT.  
- **LLM-Assisted Verification:** Enhances accuracy with ChatGPT-assisted validation.  
- **Transformer Models:** Fine-tuned BERT, BigBird, and Longformer architectures tailored for lyrics analysis.  
- **Rich Dataset:** Based on the `billboard-lyrics-spotify.csv` dataset, enriched with semantic and contextual tagging.

---

## 🛠️ **Tech Stack**
- **Python**  
- **HuggingFace Transformers**  
- **Sentence-BERT**  
- **Datamuse API**  
- **Pandas**  
- **Scikit-learn**

---

## 📊 **Dataset**
- **Source:** [`billboard-lyrics-spotify.csv`](https://github.com/zhao1701/spotify-song-lyric-analysis/blob/master/data/billboard-lyrics-spotify.csv)  
- **Attributes:** Song metadata, Billboard chart performance, full lyrics, and Spotify features.  

---

## 📑 **Methodology**
1. **Data Preprocessing:** Tokenization, normalization, and keyword matching.  
2. **Bootstrapping:** Iterative label refinement using sliding windows and SBERT similarity scoring.  
3. **LLM Validation:** ChatGPT-assisted verification for ambiguous classifications.  
4. **Model Training:** Fine-tuning BERT, BigBird, and Longformer models.  
5. **Evaluation:** Performance measured using metrics like Subset Accuracy, Per-Category Accuracy, Precision, Recall, and F1 Score.

---

## 📊 **Results Summary**
- **Best Performing Model:** Longformer  
- **Subset Accuracy:** 91.94%  
- **Category Performance:**  
   - Sexual: 95.16%  
   - Violence: 97.58%  
   - Substance: 98.39%  
   - Language: 98.39%  

---

## 🧠 **Future Work**
- Integrate acoustic features for enhanced multi-modal analysis.  
- Extend analysis to multilingual song datasets.

---

## 🤝 **Contributors**
- **Aryan Kakadia** (Northeastern University, Seattle)  
- **Kai-Yu Lu** (Northeastern University, Seattle)  
- **Yifei Shang** (Northeastern University, Seattle)

---

## 📜 **License**
This project is licensed under the MIT License.

---