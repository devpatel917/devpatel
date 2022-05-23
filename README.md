## Dev's Data Science Portfolio


### Projects
**Department Deep Structure (Illinois Geometry Lab)**
What is the structure of the math department at the University of Illinois? The question is not as simple as it seems: the research group composition changes fast, and their impact on the global scale might be smaller or larger than it seems. The goal of this project is to detect research clusters in the math department at the University. 

1. We used python libraries Selenium and BeautifulSoup to web scrape data from MathSciNet, a research database containing mathematical publications, references, citations, etc
2. From this extracted information, we generated distance matrices to represent connections between each pair of faculty in the math department
3. We applied hierarchical clutering algorithms to these distance matrices to generate research clusters between faculty members

[Final Report](https://drive.google.com/file/d/1g3Dv-cTI_qWQOws_tKPm-aUfNhc8Uagn/view?usp=sharing)

[Poster](https://drive.google.com/file/d/14vDHpwclFKu1Q50qCm7aBtL-sq-H8VeM/view?usp=sharing)



**Gut Microbiome Data Science Project (National Center for Supercomputing Applications)**
Diet is a modifiable lifestyle factor that can alter the composition of the human gastrointestinal microbiome. To study these changes, data science techniques can be applied to identify fecal metabolites as objective biomarkers of food consumption. The aim of this project was to identify
significant metabolites and taxonomic groups from five separate randomized, controlled dietary interventions providing almonds, avocados, broccoli, whole grain barley and oats, and walnuts.

1. Data Cleaning/Pre-processing - Separating control vs treatment participants, handling missing values, data normalization, etc
2. Exploratory Data Analysis - Create box and whisker plots for control vs treatment for all metabolites/taxonomic groups
3. Significance Testing - Utilized t test to determine significant metabolites and bacterial groups that caused the most change in the gut microbiome
4. Principal Component Analysis - Generated PCA plots to show if significant clusters between control vs treatment arised for all food interventions
5. Machine Learning Models - Used Random Forest and Logistic Regression to classify food intake from significant metabolites and taxonomic groups

[Final Report](https://drive.google.com/file/d/1PuUYHk2G0YUckFo4FEECkubsmZK4WMq0/view?usp=sharing)

[Poster](https://drive.google.com/file/d/1P1kzv5zsek4r7QCOsSr7Gk9YfFbhIi4L/view?usp=sharing)
