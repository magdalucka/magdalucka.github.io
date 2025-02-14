---
author: "Magdaelna Łucka"
title: "PRELUDIUM 21"
date: 2021-07-13
description: "Read about my main project regarding SAR, glaciers and machine learning."
tags: ["shortcodes", "privacy"]
thumbnail: /lodowiec.png
---
<script src="https://kit.fontawesome.com/ee68e4fa6d.js" crossorigin="anonymous"></script>

<span style="color: RoyalBlue; font-size: 1.5em;">Novel view on the study of glacier kinematics in the context of global climate change</span>

#### Goal and siginifcance  <i class="fa-solid fa-bullseye"></i>
<p style="text-align: justify;">The project aims to develop a new method for monitoring glacier movements using SAR data and machine learning. By combining the Offset-Tracking (OT) and DInSAR technique, with high-resolution SAR images, it will analyze changes in glacier kinematics, detect anomalies, and assess speed trends in Greenland and Svalbard. The research involves testing machine learning algorithms to optimize displacement assessment, followed by comparative analyses using GIS software. Ultimately, the goal is to provide a more accurate and efficient way of monitoring glacier behavior and environmental changes.</p>

<hr style="border:1px solid black">

#### Tasks <i class="fa-solid fa-list-check"></i>

**Task 1. Collecting satellite radar images for selected research areas**
<p style="text-align: justify;">The research will be conducted on groups of glaciers in two main regions: Greenland and Svalbard. In Greenland, attention will be paid to the west coast, especially to the following glaciers: Jakobshavn (the highest velocities in Greenland), Sermaq (occurrence of collapse basins) and Petterman (hydrological issues with rivers which destabilize the glacier). The Nathorstbreen, Kronebreen and Hansbreen glaciers will be especially investigated in the Svalbard region which is characterized by slower velocities compared to Greenland. Radar images from the Sentinel-1 satellite mission will be collected as they are available free of charge and at regular intervals. Moreover, depending on the availability of data, it is planned to use high-resolution datasets from well-known (Cosmo-SkyMed, TerraSAR-X) or newly developed SAR missions (ICEYE, RCM, Capella Space or NISAR), which may be useful in areas of slower movements or smaller spatial extent.</p>

**Task 2. Processing of SAR data using classical methods**
<p style="text-align: justify;">In the second step, collected SAR datasets will be processed with such methods as DInSAR and OT to obtain information about the displacement field in selected regions. Additional, calculations will be improved by using the offset field to improve DInSAR analysis to detect local deformation. This approach finds applications in earthquake areas, nevertheless, it is not commonly used in glacier monitoring. As a result, information about horizontal and LOS displacements will be obtained for each research area.</p>

**M1 – the first milestone: characteristic of the displacement field based on SAR dataset**

**Task 3. Development of a novel algorithm based on Machine Learning tools**
<p style="text-align: justify;">Preprocessed SAR data containing phase information, coherence, the amplitude of a signal and the backscatter coefficient will be used as an input to test various ML models and as an effect to create an optimal algorithm for detecting full displacement field. Different ML models and their parameters will  be tested to obtain the best quality of the results. Each model will be assessed by the statistics calculated after each epoch.</p>

**Task 4. Gathering of reference data and analysis**
<p style="text-align: justify;">Information about glaciers from independent databases will be collected and analysed. In the Greenland area following databases will be investigated: MEaSUREs, CPOM Near Real-Time, and Promice. In the case of Svalbard, three datasets will be investigated: from the University of Oslo, the Norwegian Copernicus Glacier service, and the Polish Polar DataBase from Hornsund polar station. These databases contain different information such as velocity, terminus position, mass balance or in-situ measurement from ablation sticks or meteorological stations. Part of these datasets will be used in analysing glaciers dynamics, but part of the data containing information about velocities or displacement will be used to check the correctness of the newly developed method.</p>

**Task 5. Validation of the novel algorithm**
<p style="text-align: justify;">In this stage, the results obtained using a standard approach and a new method will be compared to movement values from independent databases. In case of a lack of data, results from classic calculations will be used as a reference. As a result, the best algorithm will be selected and prepared to use for further research including long-term analysis of displacements.</p>

**M2 – the second milestone: built and validated algorithm**

**Task 6. Analysis of glaciers dynamics**
<p style="text-align: justify;">The tools created in Task 5 will allow a long-term analysis of glacier dynamics. The full displacement field will be analyzed over long timespans to determine how the selected glaciers are changing over time. Special attention will be paid to finding areas and dates where collapse basins occurred. It will be also analyzed when the speed-up period appears and if there is any relation between horizontal and LOS displacements in time. It will also allow continuous monitoring of glaciers and detection of possible anomalies in trends of their dynamics.</p>

**M3 - the third milestone: investigation of the physics of the phenomena**

<hr style="border:1px solid black">

### Progress & Intermediate Results <i class="fa-solid fa-bars-progress"></i>

**Conference proceedings:**\
"Training Dataset for the Machine Learning Approach in Glacier Monitoring Applying SAR Data" - Ł. Piwowar, M. Łucka, W. Witkowski\
IGARSS 2023 Conference Proceedings\
Find out more: [article](https://ieeexplore.ieee.org/document/10281675)

**Articles:**\
"Investigation of machine learning algorithms to determine glaciers displacements" - M. Łucka\
Remote Sensing Applications: Society and Envrionment, 2025\
Find out more: [article](https://doi.org/10.1016/j.rsase.2025.101476)

**Codes and sample data:**\
Try out a new algorithm for horizontal displacements detection using CNN model (Łucka, 2025)!\
<i class="fa-brands fa-github"></i>     https://github.com/magdalucka/TrackOff  <i class="fa-brands fa-github"></i>

Proposed workflow:
<p align="center">
    <img src="../workflow.png">

Sample of results for syntehtic datasets - images shifted by vector [-10,-3]:
<p align="center">
    <img src="../syntheticdata.png">

Sample of results for real-world dataset - SAR images of Daugaard-Jensen Glacier (Greenland):
<p align="center">
    <img src="../DJ_data.png">