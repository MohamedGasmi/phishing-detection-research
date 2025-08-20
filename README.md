# Phishing Websites Detection using Machine Learning

This repository presents my published research on **phishing websites detection** through the combination of **lexical, host, and content-based features**, evaluated across multiple machine learning models.

📄 **Paper (Open Access)**: [Download PDF](https://publications.eai.eu/index.php/sis/article/view/4421/3169)  
🔗 **Official Publication Link**: [EAI SIS Journal](https://publications.eai.eu/index.php/sis/article/view/4421)  
📌 **DOI**: [10.4108/eetsis.4421](https://doi.org/10.4108/eetsis.4421)  

---

## 📑 Abstract
Phishing attacks are one of the most prevalent cybersecurity threats, aiming to steal sensitive data by imitating legitimate websites. In this work, we propose and evaluate a machine learning approach to detect phishing URLs by combining **lexical, host, and content-based features**.  

Using a balanced dataset of **31,980 URLs** (15,990 phishing + 15,990 legitimate), we extracted **39 features** and applied different feature selection techniques. We then trained and compared four models: **SVM, Decision Tree, Random Forest, and XGBoost**.  

The **XGBoost model** achieved the best results with:  
- **Accuracy:** 95.70%  
- **Recall (TPR):** 98.06%  
- **F1-score:** 95.80%  
- **False Negative Rate:** 1.94%  

These results confirm that combining multiple feature categories significantly improves phishing detection performance.  

---

## 🧑‍💻 My Contributions
- Built a **balanced dataset** from PhishTank (phishing URLs) and Alexa Top 1M (legitimate sites).  
- Developed Python scripts for **data cleaning, feature extraction, and normalization**.  
- Implemented **feature selection** techniques (Pearson/Spearman correlation, feature importance).  
- Conducted **comparative evaluation** of ML models (SVM, DT, RF, XGBoost).  
- Achieved state-of-the-art performance with **XGBoost**.  
- Co-authored and published the final paper in **EAI Endorsed Transactions on Scalable Information Systems**.  

---

## 📊 Key Results
| Model          | Accuracy | Precision | Recall | F1-score | FNR   |
|----------------|----------|-----------|--------|----------|-------|
| SVM            | 94.12%   | 93.34%    | 95.03% | 94.17%   | 4.97% |
| Decision Tree  | 81.64%   | 78.72%    | 86.74% | 82.53%   | 13.26%|
| Random Forest  | 81.64%   | 78.72%    | 86.74% | 82.53%   | 13.26%|
| **XGBoost**    | **95.70%** | **93.64%** | **98.06%** | **95.80%** | **1.94%** |

---

## 🗂️ Repository Structure
- `docs/` → Contains the published paper (PDF).   

> ⚠️ Note: Due to institutional and copyright restrictions, the source code is not shared here.
 

---

## 📢 Citation
If you use this work, please cite:  

```bibtex
@article{hamadouche2024phishing,
  title={Combining Lexical, Host, and Content-based features for Phishing Websites detection using Machine Learning Models},
  author={Hamadouche, Samiya and Boudraa, Ouadjih and Gasmi, Mohamed},
  journal={EAI Endorsed Transactions on Scalable Information Systems},
  volume={11},
  number={6},
  year={2024},
  publisher={EAI},
  doi={10.4108/eetsis.4421}
}
