# 📚 Open-Source Air Pollution Prediction Models

Welcome to this collection of research papers on air pollution prediction, where the models are shared as open-source projects. This repository serves as a valuable resource for researchers, developers, and enthusiasts who want to explore and build on existing models.

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

[![DOI](https://img.shields.io/badge/DOI-https://doi.org/10.1016/j.eswa.2022.118017-blue)](https://doi.org/10.1016/j.eswa.2022.118017)  
[![Journal](https://img.shields.io/badge/Journal-Expert%20Systems%20with%20Applications-lightgreen)](https://www.sciencedirect.com/journal/expert-systems-with-applications)

**Abstract**<br> 
Predicting air pollutant concentrations is crucial for pollution prevention and early warnings. This project proposes **RCL-Learning**, a model combining **ResNet** for spatial feature extraction and **ConvLSTM** for spatiotemporal sequence learning. Key highlights:  
- **Accurate multi-city PM2.5 predictions** with RMSE ranging from **5.478 to 13.622** for 1- to 3-hour tasks.  
- **Robust multiscale forecasting** with an average RMSE of **22.927** for 1- to 15-hour tasks.  
- Improved prediction performance over traditional models and other neural network approaches.  


**Model Overview**<br> 
<div align="center">
  <img src="image/figure1.png" alt="Model Architecture" width="80%">
</div>


**Model Architecture**  
1. **ResNet**  
   - Extracts spatial distribution features of pollutant concentrations and meteorological data.  
2. **ConvLSTM**  
   - Captures spatiotemporal dependencies from the ResNet-extracted features for accurate forecasting.  


**Performance Evaluation**<br>   
| **Prediction Horizon** | **RMSE (Min)** | **RMSE (Max)** |  
|-------------------------|----------------|----------------|  
| 1–3 hours              | 5.478          | 13.622         |  
| 1–15 hours             | -              | 22.927         |  


**Resources**   
- **Paper**: [Read Here](https://www.sciencedirect.com/science/article/abs/pii/S0957417422012349)  
- **Code Repository**: [GitHub](https://github.com/zouguojian/RCL-Learning)  
- **Code Capsule**: [CodeOcean](https://codeocean.com/capsule/6049117/tree)  


**Citation**
If you use this work, please cite as:
* Latex inference:


      @article{zhang2022rcl,  
            title={RCL-Learning: ResNet and convolutional long short-term memory-based spatiotemporal air pollutant concentration prediction model},  
            author={Zhang, Bo and Zou, Guojian and Qin, Dongming and Ni, Qin and Mao, Hongwei and Li, Maozhen},  
            journal={Expert Systems with Applications},  
            pages={118017},  
            year={2022},  
            publisher={Elsevier}  
           }  

---

# 🌍 EDSModel  

**A Novel Encoder-Decoder Model Based on Read-First LSTM for Air Pollutant Prediction**  

[![DOI](https://img.shields.io/badge/DOI-https://doi.org/10.1016/j.scitotenv.2020.144507-blue)](https://doi.org/10.1016/j.scitotenv.2021.144507)  
[![Journal](https://img.shields.io/badge/Journal-Science%20of%20The%20Total%20Environment-lightgreen)](https://www.sciencedirect.com/journal/science-of-the-total-environment)  

**Abstract**    
Predicting air pollutant concentrations is crucial for effective environmental management and pollution prevention. In this study, we propose **RLSTM**, a Read-First LSTM that addresses the dependency between gate units, enabling better long-term feature extraction compared to traditional RNNs, LSTMs, and GRUs.  
We combine RLSTM as the Encoder and LSTM as the Decoder to build an **Encoder-Decoder System (EDSModel)** for air pollutant prediction. Key highlights of our findings:  
- Superior **long-term prediction accuracy** with RMSE of **30.218** for 1 to 24-hour tasks.  
- Overcomes traditional challenges in time-series modeling.  


**Model Overview**<br>   
<div align="center">
  <img src="image/figure2.png" alt="Model Architecture" width="80%">
</div>  


**Performance Evaluation**<br>  
| **Prediction Horizon** | **Metric**      | **Value** |  
|-------------------------|-----------------|-----------|  
| 1–24 hours             | RMSE            | 30.218    |  


**Resources**    
- **Paper**: [Read Here](https://www.sciencedirect.com/science/article/abs/pii/S0048969720380384)  
- **Code Repository**: [GitHub](https://github.com/zouguojian/Read-first-LSTM)  


**Citation**
If you use this work, please cite as:  

	@article{zhang2021novel,  
  	  title={A novel Encoder-Decoder model based on read-first LSTM for air pollutant prediction},  
  	  author={Zhang, Bo and Zou, Guojian and Qin, Dongming and Lu, Yunjie and Jin, Yupeng and Wang, Hui},  
  	  journal={Science of The Total Environment},  
  	  volume={765},  
  	  pages={144507},  
 	  year={2021},  
 	  publisher={Elsevier}  
	}

---

# 🌟 3D CNN-GRU  
**An integrated 3D CNN-GRU deep learning method for short-term prediction of PM2.5 concentration in urban environment**  

[![DOI](https://img.shields.io/badge/DOI-https://doi.org/10.1016/j.scitotenv.2022.155324-blue)](https://doi.org/10.1016/j.scitotenv.2022.155324)  
[![Journal](https://img.shields.io/badge/Journal-Science%20of%20The%20Total%20Environment-lightgreen)](https://www.sciencedirect.com/journal/science-of-the-total-environment)  

**Abstract**<br> 
Predicting PM2.5 concentrations is critical for air quality management and pollution control. In this study, we introduce the 3D CNN-GRU model, which integrates three-dimensional convolutional neural networks with gated recurrent units to enhance spatiotemporal prediction. The model learns spatial patterns from similar air quality (AQ) stations while capturing long-term temporal dependencies for simultaneous learning and prediction across different time intervals. Key findings from our study include:

High prediction accuracy with R² values of 0.84 for 1-hour forecasts and 0.78 for 24-hour forecasts.
Outperforms traditional methods such as LSTM, GRU, ANN, SVR, and ARIMA in predicting PM2.5 concentrations.


**Model Overview**<br> 
<div align="center">
  <img src="image/figure3.png" alt="Model Architecture" width="80%">
</div>


**Model Architecture**   
The architecture of the model consists of two main components:  
1. **3D CNN (Convolutional Neural Network)**  
   - Captures spatial features from the input data and learns the spatial distribution of pollutants.  
2. **GRU (Gated Recurrent Unit)**  
   - Handles the temporal dependencies of the data and predicts future concentrations based on historical information.  
  
**Performance Evaluation**<br>  
| **Prediction Horizon** | **Metric**   | **Value**    |  
|------------------------|--------------|--------------|  
| 1 hour                 | R$^2$        | 0.84         |  
| 1 day                  | R$^2$        | 0.78         |  


**Resources**   
- **Paper**: [Read Here](https://www.sciencedirect.com/science/article/abs/pii/S0048969722024172)  
- **Code Repository**: [GitHub](https://github.com/saeednadi/3D-CNN-GRU)  



**Citation**  
If you use this work, please cite as:
* Latex inference:

	@article{nadi2022integrated,  
	  title={An integrated 3D CNN-GRU deep learning method for short-term prediction of PM2.5 concentration in urban environment},  
      	  author={Nadi, Saeed and others},  
           journal={Expert Systems with Applications},  
           volume={187},  
           pages={115964},  
           year={2022},  
           publisher={Elsevier}  
	}



     


