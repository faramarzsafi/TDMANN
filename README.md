# TDMANN
**Time Distributed Memory Augmented Neural Networks**

TDMANN is a novel deep learning framework that combines the strengths of **TimeDistributed wrappers**, **Memory-Augmented Neural Networks (NTM and DNC)**, and recurrent layers (like LSTM) to improve the binary classification of brain activity in EEG signals.

---

## 📄 Published Paper

This work is published in **Applied Soft Computing (Elsevier, 2024)**.  
📘 [Access the Article](https://doi.org/10.1016/j.asoc.2024.111206)

---

## 📌 How to Cite

If you use this work, please cite:

**APA:**
> Karimian, M., & Safi-Esfahani, F. (2024). TDMANN: Time Distributed Memory Augmented Neural Networks. *Applied Soft Computing*, 141, 111206. https://doi.org/10.1016/j.asoc.2024.111206

**BibTeX:**
```bibtex
@article{karimian2024tdmann,
  title={TDMANN: Time Distributed Memory Augmented Neural Networks},
  author={Karimian, Morteza and Safi-Esfahani, Faramarz},
  journal={Applied Soft Computing},
  volume={141},
  pages={111206},
  year={2024},
  publisher={Elsevier},
  doi={10.1016/j.asoc.2024.111206}
}
```

---

## 🧠 Model Overview

TDMANN leverages the **temporal encoding capacity** of TimeDistributed layers and the **external memory structure** of MANNs (NTM & DNC) to enhance EEG classification. Key innovations include:

- Memory-augmented controllers to better model sequential EEG patterns.
- Time-distributed feature maps for segment-wise temporal learning.
- Tested on real EEG datasets (e.g., IV2A) with various sampling rates and channel sizes.

---

## 🧪 Experimental Environment

Experiments were conducted on:
- **Hardware**: Intel Core i5-9500, 8GB RAM, ASUS GTX 1050 (768 CUDA cores)
- **Software**: Windows 10, Python 3.6, Anaconda
- **Libraries**:
  - TensorFlow 1.15.2
  - Keras 2.2.4

📈 Note: Hyperparameters may vary depending on dataset configurations (e.g., 3/22/64 EEG channels, 250Hz or 160Hz sampling rates).

![TDMANN Experiment Environment](https://github.com/karimian5188/TDMANN/blob/main/Environment.jpg)

---

## 🎓 Presentation

A visual overview is available here:  
🔗 [TDMANN Presentation](https://github.com/MortezaKarimian/TDMANN/blob/main/TDMANN_presentation.ppsx)

---

## 💻 About the Source Code

- The provided code is tuned for the **IV2A dataset**.
- Ensure input tensor dimensions match dataset-specific properties.
- External dependencies for memory modules:
  - [NTM Class (Keras)](https://github.com/flomlo/ntm_keras)
  - [DNC Class (TensorFlow)](https://github.com/willsq/tf-DNC)

---

## 📜 License & Credits

This research was conducted by:
- **Morteza Karimian**
- **Faramarz Safi-Esfahani**

Refer to the paper for experimental settings, architecture configurations, and further evaluations.
