![banner_purchase_propensity](https://github.com/lorainemnrc/predict-purchase-propensity/assets/23328647/ede5eb16-d905-4dd0-af1d-b3b6abdd9db2)

<h1 style="color: #1048CB"><b>Overview</b></h1>

<p align="justify"> &emsp; Climate change poses significant risks to ecosystems, human societies, and economies, underscoring the importance of this study. By delving into the intricacies of precipitation and temperature patterns, we seek to unveil their evolving nature over time. Through the identification of noteworthy variations and trends, we can gather compelling evidence of climate change's presence and grasp its potential implications for specific regions.

The outcomes of our study will foster a deeper comprehension of climate change and its ramifications for diverse geographical areas. By pinpointing distinctive shifts in precipitation and temperature patterns, we can proactively raise awareness about regions that necessitate focused efforts in climate adaptation and mitigation strategies. Furthermore, our analysis will provide invaluable insights for policymakers, scientists, and stakeholders engaged in crucial decision-making processes relating to climate change. </p>

<h1 style="color: #1048CB"><b>Data Source</b></h1>

**NOAA Global Historical Climatology Network Daily (GHCN-D)**

The NOAA Global Historical Climatology Network Daily (GHCN-D) dataset is a comprehensive collection of daily climate observations from around the world. It provides valuable historical climate data, including temperature, precipitation, wind speed, and other meteorological variables. The dataset is widely used for climate research, monitoring climate trends, and understanding the impact of climate change.

The GHCN-D dataset encompasses observations from thousands of weather stations, spanning over a century of data. It contains measurements from both land-based stations and buoys, offering a global perspective on climate patterns. The dataset undergoes rigorous quality control procedures to ensure accuracy and reliability, making it a trusted resource for climate scientists and researchers worldwide.

**Download Details**

*The dataset can be accessed from the Registry of Open Data on AWS*

The Registry of Open Data on AWS is a repository of diverse datasets that are freely accessible on the Amazon Web Services (AWS) cloud platform. It serves as a centralized hub for discovering and accessing open datasets, promoting collaboration and innovation across different domains. The GHCN-D dataset can be found in the registry using the following link:

Link: https://registry.opendata.aws/noaa-ghcn/

**AWS S3 Bucket**

The GHCN-D dataset is stored in the AWS S3 bucket with the Amazon Resource Name (ARN) arn:aws:s3:::noaa-ghcn-pds. The dataset files have been converted from CSV format to parquet format, which optimizes storage and facilitates faster data loading and processing. The parquet files are stored in a separate S3 bucket.

**For the Original CSV Files**

 - **Amazon Resource Name (ARN)**

 - `arn:aws:s3:::noaa-ghcn-pds`

 - **AWS Region**

 - `us-east-1`

 - **AWS CLI Access (No AWS account required)**

 - `aws s3 ls --no-sign-request s3://noaa-ghcn-pds/`

**For the Parquet Files**

 - **Amazon Resource Name (ARN)**

 - `arn:aws:s3:::bdcc-lab2-2023`

 - **AWS Region**

 - `ap-southeast-2`

 - **AWS CLI Access (No AWS account required)**

 - `aws s3 ls --no-sign-request s3://bdcc-lab2-2023/`

**Dataset Summary:**

GHCN-Daily is a composite of climate records from numerous sources that were merged and subjected to a common suite of quality assurance reviews (Durre et al., 2010). The archive includes the following meteorological elements:

 - Daily maximum temperature
 - Daily minimum temperature
 - Temperature at the time of observation
 - Precipitation (i.e., rain, melted snow)
 - Snowfall
 - Snow depth
 - Other elements where available

In this archive, the period of record station files is parsed into yearly files that contain all available GHCN-Daily station data for that year plus a time of observation field (where available—primarily for U.S. Cooperative Observers). The observation times for U.S. Cooperative Observer data come from the station history archived in NCDC’s Historical Observing Metadata Repository (HOMR). The files are updated daily on AWS to be in sync with updates to the GHCN-Daily dataset at NOAA.

**Original Data Description (More Details)**

Link: https://github.com/awslabs/open-data-docs/tree/main/docs/noaa/noaa-ghcn

<h1 style="color: #1048CB"><b>Highlights</b></h1>

**Global Temporal Trends** 

<span style="color:#f26419; font-size:18px"><i>Temperature variations over time</i></span>

- Our analysis revealed significant variations in temperature over the years, with the highest variation recorded in 2012 and 2010. These variations have implications for climate change, as increased frequency and intensity of extreme weather events can disrupt ecosystems and pose risks to human health and infrastructure.

<span style="color:#f26419; font-size:18px"><i>Precipitation variations over time</i></span>

- We observed notable variations in precipitation over the years, with the highest variation recorded in 2015 and 2017. These deviations from usual precipitation patterns suggest unstable weather events related to rainfall, which can have profound impacts on ecosystems, agriculture, water resources, and human societies.

</br>

**Regional Trends** 

<span style="color:#f26419; font-size:18px"><i>Temperature variations across countries</i></span>

- We found that regions in the United States, Afghanistan, France, Iraq, and Sudan experienced the greatest variations in temperature. These variations can be attributed to a combination of natural climate variability and human-induced climate change. Understanding these temperature variations is crucial for addressing the impacts on agriculture, water resources, and energy demands in these regions.

<span style="color:#f26419; font-size:18px"><i>Precipitation variations across countries</i></span>

- Our analysis revealed that regions in Sierra Leone, Guinea-Bissau, Burma (Myanmar), France, and Liberia exhibited the greatest variations in precipitation. Human activities, such as deforestation and greenhouse gas emissions, may have contributed to these alterations in precipitation patterns. The observed variations can lead to increased risks of flooding, landslides, water scarcity, and reduced crop yields.

</br>

**Climate Change Vulnerability**

<span style="color:#f26419; font-size:18px"><i>Factors contributing to vulnerability</i></span>

The vulnerability of countries such as Iran, Sudan, Kazakhstan, Armenia, and Mauritania to climate change can be attributed to their geographical locations, which expose them to specific climate risks and hazards. These include droughts, heat waves, water scarcity, desertification, and sea-level rise.

<span style="color:#f26419; font-size:18px"><i>Implications for vulnerable countries</i></span>

The impacts of climate change in these vulnerable countries are diverse, ranging from agricultural challenges and water resource management to public health risks and ecological stress. Addressing their vulnerability requires targeted adaptation strategies and international support.</p>
