# GEOG3003M
My Report Assignment for Programming For Geographic Information Analysis. 

## Introduction to the project:
The UK Government has set a target for 1.5 million homes to be built over the course of the current parliament. Local authorities have been given substantially different targets to reach based  on their degree of urbanisation, and have accomplished varying percentages of these goals using existing local plans (Jones Lang LaSalle IP, Inc, 2024). The myriad ways councils have risen to their unique challenges leads to large spatial heterogeneity in the rates and amounts of housing development nationwide (Ministry of Housing, Communities and Local Government, 2025).

One approach is to support developments led by a collaboration between the public and private sectors, providing both public benefit and a profitable private enterprise. A proporton of these homes are owned by housing associations, and are an alternative to council-provided affordable homes. However, with the Government emphasising social rent over affordable rent, a more equitable approach, the profitability of schemes for housing associations is impacted as rents are often lower than 'affordable rent', which is simply 80% of the market average. 

One priority for housing developers is the presence of housing associations in an area, as projects they support are more likely to be granted planning permission due to their alignment with local economic and social policy. Since housing associations must target certain areas over others, it is important to understand the relationship between residential sales and the number of housing association-owned homes, which areas are most and least supported and where the social benefit of housing developments will be felt most. 

## Introduction to the data:
The datasets for this project come from the Office for National Statistics, consisting of dataframes of the GDP and residential sales per local authority and a shapefile of their boundaries, and the Regulator of Social Housing, detailing the affordable housing stock per local authority. These were all accessed from open source websites. All three numerical datasets are updated each year. The GDP data was only available to 2023, so the residential sales data was selected for this year even though it was available to 2024 for consistency between these economic variables. 

## Introduction to the code:
The code for this project follows the same pattern for both non-spatial and spatial data, i.e. reading in the datasets one at a time, undertaking pre-processing to clean them and make them easier to reference, joining them to the previously created datasets, and finally visualisation via appropriate channels. Each code segment is accompanied by an explanation and each line is explained by comments in the code block itself. 
