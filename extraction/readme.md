# Extraction Schema

## General

| **Key**          | **Description**                                                                                                                                                                  |
|------------------|----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| _G_Relevance_    | Assess the overall relevance. HIGH=the paper is only about DTs for Security, MEDIUM=the Paper describes the DT4Sec in a few paragraphs and LOW=the paper shortly describes DT4sec. |
| _G_Contribution_ | Extract the main contribution of the paper (e.g., abstract).                                                                                                                     |

## RQ1: Digital Twin Paradigm

| **Key**          | **Description**                          |
|------------------|------------------------------------------|
| _RQ1_Definition_ | Extract Definitions of the Digital Twin. |

## RQ2: Digital Twin Application

| **Key**                    | **Description**                                                 |
|----------------------------|-----------------------------------------------------------------|
| _RQ2_Benefit_              | Extract the reason why the autors use the Digital Twin.         |
| _RQ2_Application_Domain_   | Extract in which Industry the Digital Twin is used.             |
| _RQ2_Application_Scenario_ | Extract the concret cybersecurity scenario of the Digital Twin. |

## RQ3: Digital Twin Implementation

| **Key**                    | **Description**                                                                                                                          |
|----------------------------|------------------------------------------------------------------------------------------------------------------------------------------|
| _RQ3_Deployment_           | Extract the location of the Digital Twin (e.g., cloud, embedded, edge etc.).                                                             |
| _RQ3_Asset_                | Which object or asset is relevant for the Digital Twin? (e.g, Machine, Network, Car etc.)?                                               |
| _RQ3_Data_                 | What kind of data is used?                                                                                                               |
| _RQ3_Communication_Flow_   | Extract the type of communication. Does the Digital Twin communicate with an Expert, with a physical Object or with other Digital Twins? |
| _RQ3_Level_of_Integration_ | Extract the Digital Twin level of tntegration (Digital Twin, Digital Shadow, or Digital Model).                                          |
| _RQ3_Protocol_             | Extract all protocols (MQTT) or data formats (AML, XML, JSON) that are used in the paper.                                                |
| _RQ3_Tools_                | Which tools are used with the Digital Twin (e.g, Wireshark, Elasticsearch, CPS Twinning etc.)?                                           |
| _RQ3_Operation_Mode_       | Which operation modes/algorithms are used (e.g., simulation, replication, analysis, model, or Kalman filter)?                            |
| _RQ3_Generation_           | How to create or generate a Digital Twin?                                                                                                |
| _RQ3_Architecture_         | Does the paper provide a framework/ architecture?                                                                                        |

## RQ4: Challenges & Future Research

| **Key**                        | **Description**                                                                    |
|--------------------------------|------------------------------------------------------------------------------------|
| RQ4_Challenges_Future_Research | Extract the challenges and future research (can be found often in the conclusion). |


