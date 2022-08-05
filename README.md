# OneEarth_Pelagic_LongLine

This repository contains the code and data processing shapefiles required to reproduce the main findings of Frawley et al. 2022. 

Step 1A details the procedure for processing daily AIS-based Fishing Effort data hosted by Global Fishing Watch and available for download using the following link: 
https://globalfishingwatch.org/data-download/datasets/public-fishing-effort. The version of the data used in the analysis is dated 3/18/2021 and was downloaded on 3/27/2021. For additional information concerning this dataset please see the following journal article: D.A. Kroodsma, J. Mayorga, T. Hochberg, N.A. Miller, K. Boerder, F. Ferretti, A. Wilson, B. Bergman, T.D. White, B.A. Block, P. Woods, B. Sullivan, C. Costello, and B. Worm. "Tracking the global footprint of fisheries." Science 361.6378 (2018).

Step 1B details the procedure for integrating gridded fishing longline catch and effort data provided by RFMOS (i.e., the IATTC and WCPFC) and standardizing reporting formats. Public IATTC data was available for download using the following link: https://www.iattc.org/en-US/Data/Public-domain. The version of the IATTC data used in the analysis is dated 9/11/20 and was downloaded on 1/28/2021. This data contained information regarding year, month, and flag of longline fishing activity by 5x5 grid cell in the IATTC convention area. Note that 4 seperate IATTC datasets (PublicLLSharkNum, PublicLLSharkMt, PublicLLTunaBillfishNum, & PublicLLTunaBillfishMt) were used as inputs for this step. WCPFC data was available for download using the following link: https://www.wcpfc.int/folder/public-domain-data. The version of the data used in the analysis is dated 3/25/2021 and was downloaded on 3/25/2021. This data, presented in a single .csv file, contained information regarding year and month of longline fishing activity by 5x5 grid cell in the WCPFC convention area.

Step 2 details the procedure for for calculating annual vessel clustering characteristics (i.e., Seasonal Center of Gravities, Intertia, EEZ Behavior, Catch (referred to as "Estimated Overlap" in the manuscript), and an Attributes) for all pelagic longline vessels engaged in fishing activity across the combined convention bounds of the IATTC and the WCPFC. Intermediate outputs of this process for each year of the study (i.e., 2017, 2018, & 2019) can be accessed in the repository file "Clustering_Characteristics".

Step 3 details the procedure for annual clustering of all pelagic longline vessels engaged in fishing activity across the combined convention bounds of the IATTC and WCPFC. This procedure relies on inputs produced by Step 2, which can be accessed from the repository file "Clustering_Characteristics" for those interested in the clustering procedure separate from data processing (Step 1) and the assessment of annual vessel clustering characteristics (Step 2). The final results of the clustering procedure (integrating the outputs from each of the threes study years) are presented in Excel Worksheet "Data_S1_Final_Cluster_Assignments". 

Additional queries and clarifications can be directed to Timothy Frawley, the lead author of the study, at tfrawley@ucsc.edu
