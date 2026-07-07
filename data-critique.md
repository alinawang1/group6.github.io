---
layout: page
title: Data Critique
permalink: /data-critique/
---

## About the Dataset

Our dataset comes from the [California Health Interview Survey (CHIS)](https://healthpolicy.ucla.edu/our-work/california-health-interview-survey-chis), conducted by the UCLA Center for Health Policy Research. CHIS is the nation's largest state health survey, and we are using the [2023–2024 Public Use Files (PUFs)](https://healthpolicy.ucla.edu/our-work/public-use-files), which are available in Adult, Teen, and Child age groups. This lets us examine how age affects health behaviors and access to care.

The dataset covers demographic characteristics, health status, chronic health conditions, health insurance coverage, access to healthcare, dental care, mental health, nutrition and physical activity, family environment, school environment, neighborhood safety, household income, and experiences related to discrimination.

## What This Dataset Can Illuminate

This data helps us understand patterns, relationships, and disparities across California's population, and how various factors positively or negatively affect people's well-being. It goes beyond simply asking whether people are healthy or sick — it also captures insurance status, income, employment, race and ethnicity, language, immigration-related characteristics, housing, and geography. This makes it possible to examine whether specific groups experience worse health outcomes or more difficulty accessing care than others — for example, whether low-income or uninsured residents, immigrants, limited-English-proficient residents, or specific racial and ethnic groups are more likely to delay care, skip medications, lack a usual source of care, face medical debt, or struggle to find doctors and specialists.

The dataset also speaks to specific public health issues in California, including chronic conditions, mental health needs, telehealth use, COVID-19 vaccination and long COVID, wildfire smoke protection, prescription painkiller use, hate incidents, and gambling-related harms, among others. These variables let us connect individual health experiences to broader social conditions — not just what health problems exist, but which communities are most affected and what barriers contribute to those differences.

## What This Dataset Cannot Illuminate

Because the data is not organized by individual longitudinal records — each row represents a single survey response from the 2023–2024 period — it is difficult to determine the order in which events occurred, such as how an individual's health changed over time. Establishing causation is similarly difficult: most variables are measured at a single point in time and summarized into frequency distributions, so the data can reveal associations but cannot prove that one factor causes another.

Coverage gaps also matter. CHIS's [2023-2024 Public Use Files](https://healthpolicy.ucla.edu/our-work/public-use-files) sample from residential addresses, so people experiencing homelessness or housing instability are unreachable, and institutionalized populations (e.g. nursing homes, youth facilities) are excluded entirely. Precise geography is also withheld — variables like latitude/longitude, census tract, and school location are restricted and only available through a separate IRB-approved application via the [Data Access Center](https://healthpolicy.ucla.edu/our-work/data-access-center), meaning fine-grained spatial analysis isn't possible with the public files. Respondents unable to complete the survey in the languages CHIS offers are also excluded, without being flagged as missing. Additionally, CHIS imputes some missing data through model-based methods, so certain cells are statistically generated rather than directly reported, with no easy way to distinguish between the two.

## Methodology and Sourcing

CHIS collects data using a probability sampling method, randomly selecting households across California to represent diverse populations across adults, adolescents, and children (the latter surveyed through a parent or guardian). Selected participants complete self-reported surveys covering physical and mental health, health insurance, housing, and related topics. Before 2019, interviews were conducted by phone; since 2019, participants can complete the survey online or by phone. Responses are then cleaned and de-identified before release as public use files for research ([CHIS Design and Methods](https://healthpolicy.ucla.edu/our-work/california-health-interview-survey-chis/chis-design-and-methods)).

The survey is conducted by the [UCLA Center for Health Policy Research](https://healthpolicy.ucla.edu/our-work/california-health-interview-survey-chis) in Westwood, and is primarily funded by the California Department of Public Health (CDPH) and the California Department of Health Care Services (CDHCS), with additional support from philanthropic organizations, government agencies including the NIH, and UCLA itself.

## Ideological Critique

CHIS organizes its data under the assumption that housing stability is the default condition of a Californian, meaning anyone outside that assumption is underrepresented or excluded from what the dataset defines as "the population." Health, in this framework, is treated largely as a matter of individual circumstance — insurance status, utilization, access — reflecting a biomedical model rather than a structural one. At the same time, survey questions frequently use race and ethnicity as administrative categories for stratification. Together, these choices can make a dataset with real gaps and distrust appear complete, when in reality it represents a narrower population: Californians who are stably housed and fluent in one of the survey's offered languages.

*Sources: [About CHIS](https://healthpolicy.ucla.edu/our-work/california-health-interview-survey-chis/about-chis), [Access CHIS Data](https://healthpolicy.ucla.edu/our-work/california-health-interview-survey-chis/access-chis-data), [Public Use Files](https://healthpolicy.ucla.edu/our-work/public-use-files), [CHIS Design and Methods](https://healthpolicy.ucla.edu/our-work/california-health-interview-survey-chis/chis-design-and-methods), [Data Access Center](https://healthpolicy.ucla.edu/our-work/data-access-center), UCLA Center for Health Policy Research.*
