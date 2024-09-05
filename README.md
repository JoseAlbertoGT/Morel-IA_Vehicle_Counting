# Morel-IA_Vehicle_Counting (Vehicle Counting and Traffic Analysis in Morelia, Michoacán) 🚗
![](TrafficFlow.jpg)

## Researchers 🧑‍🔬
- *Dr. José A. Guzmán-Torres* <br />
jose.alberto.guzman@umich.mx <br />
https://orcid.org/0000-0002-9309-9390

- *Dr. Francisco J. Domínguez-Mota* <br />
francisco.mota@umich.mx <br />
https://orcid.org/0000-0001-6837-172X

- *Dr. Gerardo Tinoco-Guerrero* <br />
gerardo.tinoco@umich.mx <br />
https://orcid.org/0000-0003-3119-770X

- *Dra. Elia Mercedes Alonso Guzmán* <br />
elia.alonso@umich.mx <br />
https://orcid.org/0000-0002-8502-4313

- *Dr. Wilfrido Martínez Molina* <br />
wilfrido.martinez@umich.mx <br />
https://orcid.org/0000-0002-3301-4949

*Universidad Michoacana de San Nicolás de Hidalgo, Faculty of Civil Engineering* <br />
*AULA-CIMNE, Morelia, Michoacán, México* <br />
*Researchers National System México*

## Description: 📝

<p align="justify"> This repository contains data from the **Morel-IA** project, which focuses on vehicle counting and traffic analysis in Morelia, Michoacán. The dataset was collected using advanced object detection algorithms, specifically the YOLO family of models, to monitor and analyze vehicle traffic in real-time across various strategic locations in the city.
</p>

## Project summary, description, or abstract: 📚
<p align="justify">
The primary goal of the **Morel-IA** project is to revolutionize traffic management in Morelia by providing precise and continuous data on vehicle flow. The data collected serves to improve urban planning, optimize traffic infrastructure, and enhance road safety by providing actionable insights based on real-time traffic patterns. The dataset not only includes vehicle counts but also offers detailed information on vehicle types, speeds, and movement directions, making it a comprehensive tool for traffic analysis and decision-making.
</p>

## Video demonstration
[![Watch a video demonstration](https://img.youtube.com/vi/ISWTuto5ocA/maxresdefault.jpg)](https://youtu.be/ISWTuto5ocA)

# The dataset includes the following columns: 🔥
- Vehicle ID <br />
- Timestamp <br />
- Location (Monitoring Station) <br />
- Vehicle Type (Car, Truck, Motorcycle, etc.) <br />
- Speed (km/h) <br />
- Direction (Inbound/Outbound) <br />
- Lane Number <br />

Each row represents a vehicle detected at a specific monitoring station, with data captured at various times and locations across Morelia.

# This dataset can aid the urban planning and traffic management field in several ways: ✨
<p align="justify">
- **Traffic Flow Analysis**: This dataset allows researchers and urban planners to study traffic patterns, identify congestion points, and propose solutions for improved traffic flow in urban areas.
- **Safety Enhancements**: By analyzing vehicle speeds and directions, the dataset can be used to identify high-risk areas and inform road safety improvements.
- **Infrastructure Planning**: The data supports the development of new road infrastructures, optimization of traffic signals, and better allocation of resources for road maintenance.
</p>

## Description of files: ✍️
The repository contains multiple CSV files in the `data/` directory:
<p align="justify">
- **raw/**: Raw data files with initial vehicle counts and details for each monitoring station and date.
- **processed/**: Processed data files ready for analysis, including additional computed fields such as average speed and traffic density.
</p>

## Repository structure 🔥
Morel-IA_Vehicle_Counting/ <br />
| <br />
├── README.md <br />
├── data/ <br />
│   ├── raw/ <br />
│   │   ├── MS1_Calzada_La_Huerta_YYYY-MM-DD.csv <br />
│   │   ├── MS2_Camelinas_Avenue_YYYY-MM-DD.csv <br />

## Cite this research
@Article{ai5030077,
AUTHOR = {Guzmán-Torres, José A. and Domínguez-Mota, Francisco J. and Tinoco-Guerrero, Gerardo and García-Chiquito, Maybelin C. and Tinoco-Ruíz, José G.},
TITLE = {Efficacy Evaluation of You Only Learn One Representation (YOLOR) Algorithm in Detecting, Tracking, and Counting Vehicular Traffic in Real-World Scenarios, the Case of Morelia México: An Artificial Intelligence Approach},
JOURNAL = {AI},
VOLUME = {5},
YEAR = {2024},
NUMBER = {3},
PAGES = {1594--1613},
URL = {https://www.mdpi.com/2673-2688/5/3/77},
ISSN = {2673-2688},
ABSTRACT = {This research explores the efficacy of the YOLOR (You Only Learn One Representation) algorithm integrated with the Deep Sort algorithm for real-time vehicle detection, classification, and counting in Morelia, Mexico. The study aims to enhance traffic monitoring and management by leveraging advanced deep learning techniques. The methodology involves deploying the YOLOR model at six key monitoring stations, with varying confidence levels and pre-trained weights, to evaluate its performance across diverse traffic conditions. The results demonstrate that the model is effective compared to other approaches in classifying multiple vehicle types. The combination of YOLOR and Deep Sort proves effective in tracking vehicles and distinguishing between different types, providing valuable data for optimizing traffic flow and infrastructure planning. This innovative approach offers a scalable and precise solution for intelligent traffic management, setting new methodologies for urban traffic monitoring systems.},
DOI = {10.3390/ai5030077}
}
