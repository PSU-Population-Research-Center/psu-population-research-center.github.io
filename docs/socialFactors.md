---
title: Social and Demographic Indicators for Oregon EJI Maping
layout: home
---
## Introduction to the Indicators and Data Sources

The Oregon Environmental Justice (EJ) Index incorporates Social Factors as one dimension that contributes to the goal of identifying EJ communities. The preeminent source of data on Social Factors is the American Community Survey (ACS), which is the primary source of demographic and socioeconomic data in all indicator projects with nationwide coverage at the census tract level. 

The ACS is a nationally representative survey of the entire resident population of the United States. It reaches approximately 40,000 Oregon households per year and more than 1,500 persons in congregate living situations. It is intended to include people regardless of the legal status of their US residence, and the Census Bureau is legally obligated to protect respondent privacy even from other federal agencies. The response rate is over 90%, and responses are required by federal law. There are more than 64,000 variables available in the American Community Survey (ACS), and different established indexes such as the Social Vulnerability Index (SVI) and the Environmental Justice Index (EJI) are based on different baskets of social indicators from the ACS customized to the purpose and use cases of each index.

The following are a shortlist of recommended indicators that capture specific areas of disparity that we offer as potentially _actionable and relevant_ to the purpose and use cases for the Oregon EJ index project. Population Research Center (PSU) at Portland State University has compiled a larger list of over 100 ACS-derived indicators that have been used in one or more index projects, including the SVI, EJI, and many more. Recommended indicators from other data sources besides the ACS are noted as applicable. 

## Selection Criteria and Data Processing

While many of these indicators are also used in vulnerability or community resilience assessments (such as for disaster preparedness), their selection here is based on their potential to inform policy interventions aimed at promoting social equity and environmental justice. The indicators discussed below are not a proxy for risk of exposure to or health hazards from any class of natural or human-precipitated disasters.

In order to comport with the current proposed methodological design for the Oregon EJ index, the selected variables are processed into <em>measure scores</em> that are on a common scale of 1-99, where higher numbers indicate a greater need for policy action by community leaders and government authorities. Each measure score is based on a Winsorized data series (to dampen the effect of outliers), converted into a Z-score (to measure a distance from the median, rather than from an absolute standard). The final <em>domain score</em> for the Social Factors domain is calculated by averaging all measure scores, with no weighting applied.

## Indicators, Descriptions, and Included Variables

1. No Internet Access : Measure the share of households without an internet subscription (ACS Table B28002)

Lack of an internet subscription may prevent people from becoming aware of or involved in decision-making affecting the environmental health of their communities. Additionally, many important communications during emergencies are shared through the internet and people living in communities without access to internet may be difficult to reach or unable to access crucial information.

This measure includes cellular data plans, fiber, cable, DSL, or satellite internet, and is available for Oregon census tracts as an average from data collected during a 5-year period.

2. Vulnerable Employment: Measure the share of employment in natural resource industries (ACS Table C24070)

The share of employment in natural resource industries is a critical economic indicator, particularly for regions where resource extraction and agriculture play a significant role in local economies. It helps assess economic dependence on volatile industries, which are often subject to fluctuations due to market conditions, environmental regulations, and climate change. Additionally, communities with high employment in these industries may face greater economic vulnerability during downturns in commodity prices or policy shifts affecting resource management. Measuring this indicator provides insights into regional economic diversity, workforce stability, and potential environmental impacts, helping policymakers and planners develop strategies for economic resilience and sustainable development.

This measure includes workers in agriculture, forestry, fishing, hunting, and mining industries (NAICS codes 11 and 21) who are in the the civilian labor force and age 16 and older, and is available for Oregon census tracts as an average from data collected during a 5-year period.

3. Limited English : Measure the share of the population who self-report speaking English less than "well" (ACS Table C16002)

Not being able to speak or understand English well can prevent individuals from advocating for themselves and their environmental health. It can also prevent them from understanding documents, news, and emergency announcements related to environmental hazards, putting them more at risk of experiencing the cumulative impacts of environmental burdens. 

This measure applies to the population age 5 and older, and is available for Oregon census tracts as an average from data collected during a 5-year period.

4. Share of Renters: Measure the share of households that are renters (ACS Table B25003)

Renters often face greater challenges in accessing safe and healthy housing on a stable basis. They move more often, and may develop more shallow ties in their communities. Renters may also lack financial resources or legal protections that homeowners have. Homeownership is the most significant source of generational wealth for a majority of Oregonians, and renters may not have the same resources to mitigate the impacts of environmental burdens.

This measure applies to all occupied housing, and is available for Oregon census tracts as an average from data collected during a 5-year period.

5. Employment Hardships : The combined average share of people with very long commutes and share of adults who have been out of work for an extended period (ACS Tables C23022 and B08134)

Long commutes and unemployment have been associated with higher stress and related health conditions, which can make individuals more vulnerable to the negative health effects of environmental burdens.

This measure applies to all workers age 16 and older or all persons age 16-64, respectively, and is available for Oregon census tracts as an average from data collected during a 5-year period.

6. Adult Without College : The share of adults without a college degree (ACS Table B15003)

Communities with lower levels of educational attainment may not be as aware of or as able to protect themselves from environmental hazards or the negative health outcomes associated with them. Higher education has been associated with greater adaptive capacity in the case of environmental hazards and burdens.

This measure applies to all persons age 25 and older, and is available for Oregon census tracts as an average from data collected during a 5-year period.

7. Disability Rate : The share of adults with one or more disabling conditions (CDC Places)

People with disabilities often have a harder time preventing, preparing for, and recovering from environmental hazards and burdens than the general population. Additionally, some conditions may result in higher vulnerability to environmental pollution or other hazards. 

The data are taken from the CDC Places project, which estimates a model-based prevalence of disability that covers the entire adult population whereas the ACS data exclude the population in institutional living situations. The definition of "one or more disabling conditions" is the predicted probability of answering yes to at least one of the following questions: (a) “Are you deaf or do you have serious difficulty hearing?”; (b) “Are you blind or do you have serious difficulty seeing, even when wearing glasses?”; (c) “Because of a physical, mental, or emotional condition, do you have serious difficulty concentrating, remembering, or making decisions?”; (d) “Do you have serious difficulty walking or climbing stairs?”; (e) “Do you have difficulty dressing or bathing?”; (f) “Because of a physical, mental, or emotional condition, do you have difficulty doing errands alone, such as visiting a doctor´s office or shopping?”.
    
This measure applies to all adults age 18 and older, and is available for Oregon census tracts with at least 50 adults as an average from data collected during a 5-year period.

8. Civic Dis-Engagement : The share of households that did not respond to the 2020 Census (USCB PDB)

Low response rates to the decennial census is associated with a nexus of social conditions including unstable neighborhoods with frequent in- and out-migration, and households with distractions or challenges such as young children, economic or social hardships, aged populations, or crowding. The same factors that predict non-response to the decennial census-- the largest government outreach program in the nation-- may also be associated with households that are hard to reach or unable to respond to environmental stressors or hazards.

The data are taken from the US Census Bureau's Planning Database (2023 edition), a database of operational metrics including response rates to the ACS and decennial census. 

This measure applies to all households, and is available for Oregon census tracts for the year 2020 (decennial census response rates) or 2021 (ACS response rates).

1. Disconnected Youth : The average of the share of school age children (5 to 17) not enrolled in school (ACS Table B14003) and the share of young persons age 16-19 who are not in education or the labor force (B14005). 

Disconnected youth face higher risks of long-term economic hardship, social exclusion, and reduced upward mobility. A lack of school enrollment or workforce participation can indicate barriers to education, family instability, or economic distress, which may contribute to higher crime rates, poverty, and social service dependency. Measuring this helps identify communities needing targeted interventions in education, job training, and social support to improve long-term outcomes.

This measure applies to all persons age 5-19, and is available for Oregon census tracts with at least 50 adults as an average from data collected during a 5-year period.

10. Uninsured Rate : The share of adults 18-64 without health insurance (CDC Places)

People without insurance are less likely to access health care and services and are more likely to experience illness, injury, and death from environmental hazards and exposures than insured populations.

This measure is from the CDC Places project, which estimates a model-based prevalence of uninsurance that covers the entire adult population below age 65 (when widespread Medicare eligibility begins) whereas the ACS data exclude the population in institutional living situations. 
