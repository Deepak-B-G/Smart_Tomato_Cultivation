
# <p align="center">IoT enhanced tomato plant cultivation with machine learning</p>


## ABSTRACT

The project introduces an IoT and Machine Learning (ML) enhanced system designed to enhance tomato cultivation, addressing the challenges of modern agriculture by optimizing resource usage while meeting the rising global food demand. The system's core components include soil moisture and NPK (Nitrogen, Phosphorus, Potassium) sensors, continuously monitoring and maintaining optimal soil conditions. Soil moisture sensors trigger irrigation when the soil becomes dry, ensuring proper hydration, while NPK sensors monitor nutrient levels for robust plant growth. Innovatively, the project integrates ML through a camera module capturing real-time plant images. A sophisticated ML model identifies potential pest threats like insects and diseases, autonomously activating an alert system for immediate notification to the user. Remote monitoring via an IoT interface empowers users to access real-time data and configure settings. This IoT and ML-driven tomato cultivation system offers resource-efficient, proactive, and sustainable agriculture, elevating crop yields and reducing environmental impact.

## PROBLEM STATEMENT 

Traditional tomato cultivation faces challenges such as inefficient irrigation, imprecise nutrient management, pest-related crop losses, and limited data-driven insights, hindering the path toward sustainable agriculture. These challenges necessitate innovative solutions that optimize resource usage, enhance crop health, and provide real-time monitoring and control for improved yield and reduced environmental impact.


## PROPOSED SOLUTION

Our project aims to address these challenges by developing an integrated system that leverages IoT and Machine Learning to optimize irrigation, enhance nutrient management, enable real-time pest detection and control, promote sustainable farming practices, and provide data-driven decision support for tomato cultivation.

## PROOF OF CONCEPT



https://github.com/Deepak-B-G/Smart_Tomato_Cultivation/assets/97933847/c8bb9ce3-9d9e-440b-a951-0c2f8aa9e1d3


### SYSTEM ARCHITECTURE
<img src="https://github.com/Deepak-B-G/Smart_Tomato_Cultivation/assets/97933847/08835dfa-4371-477a-87a4-5c78137d092b" alt="System Architecture" width="700" height="600">


![carbon](https://github.com/Deepak-B-G/Smart_Tomato_Cultivation/assets/97933847/7943662b-9118-492b-901c-db87535a111e)



# We Divided the Projects into 2 Phases 


## Phase-01: Focus on Soil Moisture
- [PHASE-01](https://github.com/Deepak-B-G/Smart_Tomato_Cultivation/tree/master/Phase-01)

## Phase-02: Soil Nutrients and ML Model
- [PHASE-02](https://github.com/Deepak-B-G/Smart_Tomato_Cultivation/tree/master/Phase-02)


# [PHASE-01](./Phase-01)

Phase-01 of the project focuses on soil moisture management using IoT technology. It includes the implementation of a soil moisture sensor (AB054) interfaced with a NodeMCU board. The sensor continuously monitors soil moisture levels, and based on predefined thresholds, triggers a water pump for irrigation when moisture is low. This phase involves hardware components such as the soil moisture sensor, NodeMCU board, water pump, relay module, and a 9-volt HW battery for power supply. The software aspect includes programming the NodeMCU using the Arduino IDE or Lua language to control the irrigation system based on soil moisture readings. The goal of Phase-01 is to establish a reliable and automated soil moisture management system for efficient tomato plant cultivation.


![Sample](https://github.com/Deepak-B-G/Smart_Tomato_Cultivation/assets/97933847/05432ff1-35a3-4dfe-bb50-2a20ca5e0e6a)
Fig: The testing of soil moisture sensor with a water source.
<br>

![Output](https://github.com/Deepak-B-G/Smart_Tomato_Cultivation/assets/97933847/5b0f36a9-4679-4af3-91e4-c259c29e38c6)
Fig: The output displayed on the serial Monitor.


# [PHASE-02](./Phase-02)

## Phase-02 is further divided into 2 parts
 1. Soil Nutrients Monitoring
 2. Pest Detection  

 ### 1. Soil Nutrients Monitoring

Phase-02 of our project focuses on the crucial task of soil nutrient monitoring to ensure the optimal growth and health of tomato plants. We aim to integrate NPK (Nitrogen, Phosphorus, Potassium) sensors into our system and utilize the Blynk app for real-time monitoring of nutrient levels. This phase emphasizes precise data collection and analysis to enable efficient nutrient management and support healthy plant development.







