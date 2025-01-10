# 📚 Open-Source Air Pollution Prediction Models

Welcome to this curated collection of research papers in the field of **air pollution prediction** that have made their models available as open-source projects. This repository aims to serve as a resource for researchers, developers, and enthusiasts interested in exploring and building upon existing models.

---

## 🌟 Stay Connected  
If you have any questions or suggestions, feel free to reach out to us!  

- 📧 **Email:** [m.abbasi1@email.kntu.ac.ir](mailto:m.abbasi1@email.kntu.ac.ir)  

We appreciate your interest and support. Thank you! 🙌

---

## 🎯 Purpose  
This repository gathers papers that contribute to air pollution prediction, focusing on models shared openly for reproducibility and further development.

---

## 📝 Included Papers

# 🌟 RCL-Learning  
**RCL-Learning: ResNet and convolutional long short-term memory-based spatiotemporal air pollutant concentration prediction model**  

[![DOI](https://img.shields.io/badge/DOI-YourDOI-blue)](https://doi.org/10.1016/j.eswa.2022.118017)  
[![Journal](https://img.shields.io/badge/Journal-YourJournalName-lightgreen)](https://www.sciencedirect.com/journal/expert-systems-with-applications)  

---

## 📖 Abstract  
Predicting air pollutant concentrations is crucial for pollution prevention and early warnings. This project proposes **RCL-Learning**, a model combining **ResNet** for spatial feature extraction and **ConvLSTM** for spatiotemporal sequence learning. Key highlights:  
- **Accurate multi-city PM2.5 predictions** with RMSE ranging from **5.478 to 13.622** for 1- to 3-hour tasks.  
- **Robust multiscale forecasting** with an average RMSE of **22.927** for 1- to 15-hour tasks.  
- Improved prediction performance over traditional models and other neural network approaches.  

---

## 🖼️ Model Overview  
<div align="center">
  <img src="images/figure1.png" alt="Model Architecture" width="80%">
</div>

---

## 🏗️ Model Architecture  
1. **ResNet**  
   - Extracts spatial distribution features of pollutant concentrations and meteorological data.  
2. **ConvLSTM**  
   - Captures spatiotemporal dependencies from the ResNet-extracted features for accurate forecasting.  

---

## 🚀 Performance  
| **Prediction Horizon** | **RMSE (Min)** | **RMSE (Max)** |  
|-------------------------|----------------|----------------|  
| 1–3 hours              | 5.478          | 13.622         |  
| 1–15 hours             | -              | 22.927         |  

---

## 🔗 Resources  
- **Paper**: [Read Here](https://www.sciencedirect.com/science/article/abs/pii/S0957417422012349)  
- **Code Repository**: [GitHub](https://github.com/zouguojian/RCL-Learning)  
- **Code Capsule**: [CodeOcean](https://codeocean.com/capsule/6049117/tree)  

---

## 📊 Citation  
If you use this work, please cite as:  
```latex
@article{zhang2022rcl,  
  title={RCL-Learning: ResNet and convolutional long short-term memory-based spatiotemporal air pollutant concentration prediction model},  
  author={Zhang, Bo and Zou, Guojian and Qin, Dongming and Ni, Qin and Mao, Hongwei and Li, Maozhen},  
  journal={Expert Systems with Applications},  
  pages={118017},  
  year={2022},  
  publisher={Elsevier}  
}  


---
