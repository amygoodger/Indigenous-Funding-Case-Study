# Regional Analysis of Funding: Indigenous vs. Non-Indigenous

## Overview
The Regional Analysis of Funding: Indigenous vs. Non-Indigenous Case Study explores the allocation of public funds from the Queensland Government’s Advance Queensland Program, particularly focusing on funding disparities between Indigenous and non-Indigenous recipients. This project investigates how funds were distributed across different regions, especially in response to the economic recovery efforts after the COVID-19 pandemic, and assesses whether the program adequately supports Indigenous communities.

## Project Structure
The analysis is split into two parts:

### Part A
Focuses on the overall distribution of Advance Queensland funds between South-East Queensland and Regional Queensland, particularly during and after the COVID-19 pandemic. The aim was to understand trends in funding allocation and how the program adapted to support economic resilience during uncertain times.

### Part B
Builds on the findings of Part A by analysing the imbalance between funding received by Indigenous and non-Indigenous recipients. This part extends the analysis by utilising unstructured data from the Guardian API and applying machine learning techniques to explore funding patterns in more detail.

## Key Techniques Used
- **Descriptive Statistics:** Provided an initial understanding of the data, including the distribution of funds across regions and demographics.
- **Natural Language Processing (NLP):** Employed for analysing unstructured data from news articles to identify discussions surrounding Indigenous funding, and assess the public discourse around this topic.
- **Topic Modelling (TF-IDF & NMF):** Used to uncover hidden themes in media coverage and provide insights into the societal conversation on funding imbalances.
- **Clustering Analysis:** Applied to further investigate funding distribution patterns across regions and groups.

## Key Insights
- **Funding Distribution Across Regions:** South-East Queensland consistently receives a larger share of the funding, which aligns with the higher population density, but the gap narrows when considering economic factors such as infrastructure and employment.
- **Impact of COVID-19:** A notable increase in funding was observed in 2020, likely a response to the pandemic. Post-2020, Indigenous funding remained at pre-pandemic levels, while non-Indigenous funding decreased.
- **Indigenous vs Non-Indigenous Funding:** Indigenous recipients received significantly less funding (2.12%) compared to their non-Indigenous counterparts, despite Indigenous people comprising 4.6% of the Queensland population. Additionally, funding for Indigenous programs often had lower maximum and average amounts, pointing to an inequity in how funds are allocated.
- **Regional Imbalances:** Some regions with high Indigenous populations, such as Moreton Bay and Cairns, received little to no Indigenous-focused funding, despite the higher percentage of the Indigenous population in those areas. This indicates possible gaps in targeted support for these communities.

## Conclusion
The project highlights a significant imbalance in the distribution of funds between Indigenous and non-Indigenous recipients within the Advance Queensland Program. While funding disparities can be attributed to factors like population size and economic activity, the analysis suggests that Indigenous communities require additional targeted support. The findings call for a reassessment of funding allocation strategies to ensure Indigenous communities receive equitable support to drive economic development, innovation, and job creation.

## Ethical Considerations
Ethical considerations were carefully taken into account, particularly when handling unstructured data. Potential biases from media sources were mitigated by using a variety of articles and analysing multiple modelling approaches. The identification of Indigenous-focused programs was based on keyword searches, but this may have introduced some inaccuracies in classifying relevant programs.
