# Thesis_Earthquake-prediction

-------
## 1. Thesis title

"Catalyzing Earthquake Prediction in Bangladesh: A Machine Learning Approach"

### 1.1 Introduction
In the dynamic region situated between the Eurasian and Indian tectonic plates, Bangladesh faces an ongoing seismic risk that demands attention and preparedness. Rapid urbanization and infrastructure development in this densely populated nation underscore the importance of earthquake prediction for disaster mitigation.

This thesis embarks on a pragmatic exploration of earthquake prediction, leveraging the capabilities of machine learning. The objective is to develop a region-specific model tailored to Bangladesh's geological context. This endeavor seeks to enhance early warning systems and inform disaster preparedness strategies, ultimately safeguarding lives and infrastructure.

The following chapters delve into the scientific foundation, data analysis, model development, and validation processes integral to our machine learning approach. Through this research, we aim to contribute valuable insights to the field of earthquake prediction, with a focus on a region that has historically faced seismic challenges.

Welcome to the exploration of "Catalyzing Earthquake Prediction in Bangladesh: A Machine Learning Approach," where data-driven science meets the quest for seismic resilience.



## 2. Literature Review 

| Reference | Title | Authors | Publication Year | Key Findings | Limitations |
|-----------|-------|---------|-------------------|--------------|-------------|
| 1         | Earthquake magnitude prediction in Hindukush region using machine learning techniques | K. M. Asim, F. Martínez-Álvarez, A. Basit, T. Iqbal | 2023 | Machine learning techniques used for earthquake magnitude prediction in Hindukush region. | - Limited to the Hindukush region, may not generalize to other areas. - Dependence on data quality and availability. |
| 2         | Earthquake prediction by RBF neural network ensemble | Liu Y, Wang Y, Li Y, Zhang B, Wu G | 2023 | Prediction of earthquakes using a radial basis function (RBF) neural network ensemble. | - Performance may vary depending on the choice of hyperparameters. - Generalization to different regions and earthquake types needs further investigation. |
| 3         | Earthquake prediction in Iraq using machine learning techniques | Nada Badr Jarah, Kadhim Mahdi Hashim, Abbas Hanon Hassin Alasadi | 2023 | The study addresses the scientific achievements and historical context of earthquake prediction in Iraq, acknowledging the increasing frequency of earthquakes in southern regions due to factors like excessive oil extraction. | Noise interference, particularly at low levels, poses a concern as it can disrupt seismic signal accuracy. Temporal offsets due to wave propagation introduce complexity in earthquake detection, varying by source-station distance. |
| 4         | The magnitude distribution of declustered earthquakes in Southern California | Knopoff L | 2020 | Analyzes the magnitude distribution of declustered earthquakes in Southern California. | - Limited to a specific geographic region. - May not account for recent data changes or geological shifts. |
| 5         | Developing an expert system based on association rules and predicate logic for earthquake prediction | Ikram A, Qamar U | 2015 | Develops an expert system for earthquake prediction using association rules and predicate logic. | - Reliance on rule-based approaches may lead to oversimplification. - Expert systems are highly dependent on the quality of rules and data. |
| 6         | A testable five-year forecast of moderate and large earthquakes in southern California based on smoothed seismicity | Kagan YY, Jackson DD, Rong Y | 2021 | Proposes a five-year forecast of moderate and large earthquakes in southern California based on smoothed seismicity. | - Long-term forecasts are inherently uncertain. - Model assumptions may not hold for all seismic situations. |
| 7         | Structural and seismic evidence for intracontinental subduction in the Peter the First Range, central Asia | Hamburger MW, Sarewitz DR, Pavlis TL, Popandopulo GA | 2022 | Discusses structural and seismic evidence for intracontinental subduction in central Asia. | - Limited to a specific geographic region. - Requires further corroborating evidence. |
| 8         | Nowcasting Earthquakes by Visualizing the Earthquake Cycle with Machine Learning: A Comparison of Two Methods | John B. Rundle, Andrea Donnellan, Geofrey Fox, and James P. Crutchfeld | 2021 | The study suggests that the proposed methods, based on small earthquake correlations, offer valuable insights into the earthquake cycle, allowing for the characterization of stress accumulation and release associated with significant tectonic events. | The study primarily focuses on California, and the applicability of the methods to other seismically active regions needs exploration. |
| 9         | Seismic quiescence as an indicator for large earthquakes in a system of self-organized criticality | Hainzl S, Zoller G, Kurths J, Zschau J | 2021 | Examines seismic quiescence as an indicator for large earthquakes in a self-organized criticality system. | - Effectiveness as a predictive tool may vary by region and fault system. - Limited to specific conditions of self-organized criticality. |
| 10        | Non-Poissonian earthquake clustering and the hidden Markov model as bases for earthquake forecasting in California | Ebel JE, Chambers DW, Kafka AL, Baglivo JA | 2020 | Discusses non-Poissonian earthquake clustering and the hidden Markov model for earthquake forecasting in California. | - Model assumptions may not always align with real-world seismic behavior. - Practical implementation challenges and computational requirements. |


## 3. Problem Statement

Over the past decades, Bangladesh, situated within the dynamic convergence zone of the Eurasian and Indian tectonic plates, has faced an increasing risk of devastating earthquakes. Despite this vulnerability, there exists an alarming absence of dedicated earthquake prediction models tailored to the region. The absence of accurate earthquake prediction models hinders proactive disaster preparedness, timely response, and mitigation efforts. This research aims to address this critical problem by developing a region-specific earthquake prediction model without suggesting a solution, to enhance the resilience and safety of Bangladesh in the face of seismic hazards.

## 4. Significance of the thesis

The significance of this thesis lies in its potential to address a pressing issue that affects both the safety and well-being of the people of Bangladesh and the broader field of earthquake prediction research:

1. **Humanitarian Impact:** Bangladesh is densely populated, and its vulnerability to earthquakes poses a significant threat to human lives and infrastructure. Developing an effective earthquake prediction model can lead to improved disaster preparedness, timely evacuations, and reduced casualties in the event of seismic activity.

2. **Scientific Advancement:** The proposed research bridges a critical gap in earthquake prediction by focusing on a region often overlooked in seismic research. By applying machine learning techniques specifically to Bangladesh's unique geological context, this project has the potential to contribute novel insights to the field of earthquake prediction.

3. **Regional Resilience:** The outcomes of this research can empower Bangladesh with the knowledge and tools needed to enhance its resilience against seismic hazards. This, in turn, can have a positive economic impact by safeguarding critical infrastructure and reducing the long-term costs associated with post-earthquake recovery efforts.

4. **Global Relevance:** As seismic events are not limited by borders, the lessons learned and methodologies developed in this research may have broader implications for earthquake-prone regions worldwide. The project's findings can contribute to the global knowledge base on earthquake prediction and risk mitigation.

5. **Timeliness:** With the increasing urbanization and development in Bangladesh, the need for accurate earthquake prediction models has never been more critical. By addressing this issue now, we can better prepare for and mitigate potential future seismic disasters.

In summary, this thesis holds significance both in terms of its potential humanitarian impact on a vulnerable population and its contribution to the advancement of earthquake prediction science, making it relevant and important to a wide range of stakeholders.

## 5. Aims/ Objectives

**Aims:**
The primary aim of this thesis is to develop a robust and region-specific earthquake prediction model for Bangladesh, situated between the Eurasian and Indian tectonic plates. This model will be designed to enhance disaster preparedness and mitigate the impact of seismic events in the region.

**Objectives**
1. To employ machine learning techniques, including feature engineering and model training, to develop an accurate earthquake prediction model tailored to the geological characteristics of Bangladesh.


## 6. Research Gap

Despite the significant seismic activity potential in the region situated between the Eurasian and Indian plates, there is a notable lack of comprehensive and accurate earthquake prediction models specifically tailored to Bangladesh. Existing research has primarily focused on earthquake prediction in other regions, often overlooking the unique geological characteristics and seismic risks that Bangladesh presents. Therefore, a critical research gap exists in developing and validating machine learning-based earthquake prediction models specifically designed for Bangladesh, which could enhance preparedness and mitigation efforts in this highly vulnerable area. Addressing this gap is essential for improving the region's resilience to seismic hazards and ensuring the safety of its population and infrastructure.

## Gantt Chart
![Gantt chartTHESIS](https://github.com/smafraim/Team-20_Thesis/assets/70313535/c346a8fb-ec86-47d2-b019-d0eede8ebeab)


## Methodology

### Methodological Approach

This research employs a data-driven approach to predict earthquakes in Bangladesh, utilizing machine learning techniques. The methodology integrates seismic data, geological information, and real-time monitoring to develop predictive models. The objective is to enhance earthquake preparedness and reduce potential damage.

### Methods of Data Collection

1. **Seismic Data**: Historical seismic data, spanning several decades, are obtained from international seismic databases. Real-time seismic data are acquired through a network of seismic sensors.

2. **Geological Data**: Geological surveys and satellite-based observations provide geological features and tectonic information.

3. **Real-time Monitoring**: Data streams from seismic sensors are continuously collected and preprocessed to maintain an up-to-date dataset.

### Methods of Analysis

1. **Data Preprocessing**: Collected data undergo preprocessing to eliminate noise, standardize formats, and handle missing values. Feature engineering is employed to extract relevant attributes.

2. **Feature Selection**: Feature selection techniques are applied to identify the most informative variables for machine learning model development.

3. **Machine Learning Models**: Various machine learning algorithms, including regression models for magnitude prediction and classification models for earthquake occurrence, are implemented. Model training and validation are conducted using historical data.

4. **Real-time Prediction**: Models are updated in real-time with incoming seismic data to provide ongoing earthquake predictions.

### Tools and Materials

- Python programming language is used for data analysis, feature engineering, and model development.
- Scikit-learn, TensorFlow, and Keras libraries are utilized for machine learning implementations.
- Geographic Information System (GIS) software aids in visualizing geological data.

### Rationale for Methodology

This methodology aligns with the research objectives of improving earthquake prediction in Bangladesh. The choice of machine learning models is based on their proven effectiveness in handling complex patterns in seismic data. Real-time monitoring and model updates aim to enhance prediction accuracy and timeliness.

The methodology leverages existing research practices in earthquake prediction while introducing a novel approach by integrating machine learning into the prediction process. It addresses a critical gap in earthquake preparedness and disaster mitigation strategies for Bangladesh.

## Flowchart Methodology
![flowchart](https://github.com/smafraim/Team-20_Thesis/assets/70313535/ebc74245-cda3-438c-8756-1287d9ca3b19)



## Data Overview:

1) https://ds.iris.edu/ieb/index.html?format=text&nodata=4JUdGzvrMFDWrUUwY3toJATSeNwjn54LkCnKBPRzDuhzi5vSepHfUckJNxRL2gjkNrSqtCoRUrEDAgRwsQvVCjZbRyFTLRNyDmT1a1boZVcaller=self&name=S.E.%20Asia%20Region&zm=5&mt=ter

2) climate-changebd.csv
3) export_EMSC.csv
4) BD_Earthquake.xlsx
