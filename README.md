# phw251
Graduate school group project 

### Scenario 1: Hospital Funding and Health Equity
You are a researcher in the California Department of Public Health Office of Health Equity (OHE).  A policy has just been created to fund a public-private partnership for healthcare facility improvement in rural areas of California that have received minimal funding from the Department of Health Care Access and Information (HCAI) over the past 5 years. You are tasked with exploring and evaluating which 5 counties are the best targets for the development fund proposals. There are multiple components to this request.

First, OHE would like you to focus on rural areas, non-homeowners, and aging individuals as populations of interest in your analysis. Your task is to explore the California county census demographic dataLinks to an external site. and begin to identify counties that share three common attributes: low population per square mile `pop12_sqmi1`, high median age `med_age`, a high proportion of renters vs. homeowners (you may need to create a new variable for this third criteria). 

Second, OHE’s director would also like to include a total count of mortality from chronic health conditions over the past few years into the county level analysis. You've located a mortality surveillance datasetLinks to an external site. and plan to summarize a total count of occurrences attributed to known chronic health conditions by county, circa 2014-2020 (you may encounter missing values here, it's understood that replacing NAs with 0 is appropriate). Once the mortality data is summarized at the county level, you will join your dataframe with the county demographic data from above.

Finally, you must locate the most recent account of HCAI fundingLinks to an external site. for projects that are in closure for each county. Like you've done before, these estimates should be joined with the summarized demographics and mortality to expand your HCAI dataset for analysis.

Using these three data sources together, you must identify the 5 counties in which to recommend for the development funding partnerships. (Note, there is not a single right answer as to how counties are selected, rather it is important that you can defend how and why you selected them). To support your recommendation, you will create a print quality table and data visualization to bring to the next OHE business strategy meeting and explain why these particular top 5 counties should be selected for development funding partnerships.

Data Sources:
PHW251 Project Data RepoLinks to an external site.
hcai_healthcare_construction.csvLinks to an external site. (original source: https://data.ca.gov/dataset/total-construction-cost-of-healthcare-projectsLinks to an external site.)
ca_county_mortality.csvLinks to an external site. (original source: https://data.ca.gov/dataset/death-profiles-by-countyLinks to an external site.)
ca_county_demographics.csvLinks to an external site. 
