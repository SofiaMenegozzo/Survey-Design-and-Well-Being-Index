## Survey Design, Statistical Models and Composite Well-Being Index
This project was developed for the Social Statistics course and combines three different applications of quantitative methods to social research.

- The first part focuses on the design of a survey aimed at evaluating the quality of university catering services at the University of Milano-Bicocca. 
- The second part applies psychometric and statistical methods to construct and validate a Guttman scale measuring reactive aggression and hostility, and to investigate its relationship with optimism.
- The third part focuses on the construction of a composite well-being indicator based on ISTAT's BES (Equitable and Sustainable Well-being) framework.

The project combines survey design, measurement theory, statistical analysis and multivariate methods, with the aim of showing how quantitative tools can be used to study different aspects of social well-being.

### Objectives
The first part of the project focuses on designing a questionnaire for students at the University of Milano-Bicocca to evaluate university catering services in the context of a possible renewal of the management contract. The questionnaire aims to identify the main dimensions of the catering service and organise them into a logical area tree. It will assess aspects such as food quality, prices, accessibility, organisation, staff, and overall satisfaction, while distinguishing between students who use catering services and those who do not. Appropriate measurement scales and neutral question wording will be used to reduce potential response biases. The questionnaire will also be designed to take approximately 10 minutes to complete.

The second part of the project focuses on constructing a Guttman scale to measure reactive aggression and hostility. The aim is to select and organise items representing different forms and levels of aggressive behaviour along a cumulative scale, from less to more intense forms of aggression. The quality of the scale will be assessed using the Coefficient of Reproducibility and Minimal Marginal Reproducibility. The analysis will also examine differences in aggression levels between males and females and explore the relationship between aggression and optimism, measured through the Life Orientation Test-Revised (LOT-R).

The third part focuses on constructing a composite indicator based on ISTAT’s BES framework. The analysis involves selecting indicators related to education, employment, and social relationships, standardising them to ensure comparability, and addressing missing data through appropriate methods. The indicators will then be weighted and aggregated to create a synthetic measure of educational and cultural development. Finally, the analysis will identify groups of Italian regions with similar levels of well-being and investigate the relationship between territorial well-being and subjective life satisfaction, combining the different dimensions into an overall composite well-being indicator.

### Data & Analysis 
The first part is based on information concerning the catering services offered by the University of Milano-Bicocca, including official university material describing available services and facilities.The target population is composed of students enrolled at the University.

The second part uses a questionnaire dataset containing 60 items (V18_1–V18_60) describing behaviours and attitudes.
A subset of these items was selected to construct the aggression and hostility scale.
Optimism was measured using the LOT-R, consisting of 10 items, including 6 items used to calculate the score and 4 filler items.

The third part uses indicators from the BES (Equitable and Sustainable Well-being) framework provided by ISTAT.
Three dimensions of well-being are considered: education and training; work and work-life balance; and social relationships.
The education dimension is further divided into areas including early learning, basic skills, cultural participation, digital skills and educational outcomes.

### Methodology
The questionnaire was developed from a general research objective, which was progressively divided into specific analytical dimensions. An area tree was created to structure the questionnaire into eight main sections covering the respondent profile, use of university catering services, dietary needs, food offer, organisation, service quality, economic evaluation, and overall evaluation. The questionnaire includes filter questions, single- and multiple-choice questions, ordinal rating scales, and open-ended questions. Four-point ordinal scales without a neutral option were used for several evaluations, while different types of scales were alternated to reduce response-set effects. The questionnaire was designed to take approximately 10 minutes to complete while ensuring respondents’ anonymity.

The Guttman scale was constructed by initially selecting 12 items related to emotional and behavioural reactions in situations involving conflict or frustration.
The items were ordered along a continuum ranging from relatively mild forms of assertiveness and hostility to more extreme forms of aggressive behaviour.
The scale was progressively refined by removing or replacing items that generated a high number of errors.
The final version consists of 8 items and achieved a Coefficient of Reproducibility of 0.912, exceeding the conventional 0.90 threshold and indicating a satisfactory cumulative structure.
The resulting scale was then used to investigate gender differences and the relationship between aggression and optimism.

For the composite indicator, the first measure was developed for the Education and Training dimension of the BES framework. The analysis considered five sub-dimensions covering early learning, basic skills, cultural participation, digital skills, and educational outcomes. Since the indicators were expressed in different units and scales, they were standardised using Z-scores to make them comparable. Different weights were then assigned to the components according to their relative importance within the index. Missing values were handled through a combination of imputation and exclusion procedures, depending on the availability and characteristics of the data. The robustness of the resulting index was assessed by comparing different aggregation methods using Spearman’s correlation and Kendall’s coefficient of concordance. Finally, cluster analysis was performed to identify groups of Italian regions with similar levels of educational and cultural performance.

### Results
The final questionnaire provides a structured framework for evaluating university catering services.
The use of filter questions allows the questionnaire to adapt to both users and non-users of the service, while the combination of closed and open questions makes it possible to collect both quantitative evaluations and more specific suggestions.
The questionnaire also takes into account methodological aspects such as question wording, scale design, response bias and respondent burden.

The final 8-item Guttman scale achieved a Coefficient of Reproducibility of 0.912, indicating a good cumulative structure.
The analysis found a statistically significant difference between males and females, although the difference in average aggression scores was relatively small.
The relationship between aggression and optimism was negative and statistically significant. Individuals with higher aggression scores tended to report lower levels of optimism.
The results therefore suggest an association between these two psychological dimensions, although the correlation is moderate and should not be interpreted as evidence of a causal relationship.

The educational and cultural index reveals clear territorial differences across Italy.
The highest-performing regions are mainly located in Central and Northern Italy, while most Southern regions occupy the lowest positions.
The cluster analysis identifies three main groups of regions, broadly corresponding to higher, intermediate and lower levels of educational and cultural performance.
The results therefore highlight the persistence of territorial differences in education and well-being across Italy.

The relationship between the composite indicator and subjective life satisfaction is positive, but relatively weak at regional level. This suggests that objective territorial indicators of well-being and subjective perceptions of quality of life capture related but not identical aspects of well-being.

### Tools
The project uses different tools for data management, statistical analysis and document preparation.
R was used for statistical analysis, Guttman scale construction and validation, correlation analysis, cluster analysis, PCA and data visualisation.
Excel was used to organise the BES data, manage the elementary indicators and support the construction of the composite index.
A word-processing tool was used to design and prepare the questionnaire in a printable format.

### Repository Contents
- elaborato.pdf — complete project report
- questionario_versione_stampabile.pdf — printable version of the survey questionnaire
- indicatore_sintetico.xlsx — BES data and spreadsheets used to construct the composite indicator
- script_R.R — R script used for the statistical analyses
- envoronment.RData — R workspace containing the objects generated during the analysis
- grafico_aggiuntivo_dendrogramma_regioni.png — dendrogram of the regional cluster analysis
- grafico_aggiuntivo_metodo_elbow.png — Elbow Method plot used to identify the number of clusters

### Limitations
For the survey design, the questionnaire was not administered to students, so its effectiveness could not be empirically tested on a real sample. Some design choices, such as the use of scales without a neutral category, may also influence respondents' answers.

For the Guttman scale, the final Coefficient of Reproducibility is slightly above the conventional threshold of 0.90. Although this indicates an acceptable cumulative structure, the scale should not be considered a perfect measurement instrument. Moreover, the use of self-reported data may introduce social desirability and other response biases.

For the composite indicator, some missing BES indicators required the exclusion or imputation of data. The assignment of weights also introduces a degree of subjectivity into the construction of the index. Finally, the relationship between the composite indicator and subjective life satisfaction is not statistically significant at regional level. This highlights the difficulty of representing a multidimensional concept such as well-being through a single synthetic measure.

Despite these limitations, the project provides an integrated example of how statistical methods can be applied to different stages of social research, from survey design and measurement to the construction and analysis of composite indicators.

### Context
Academic project developed for the Social Statistics course as part of the Bachelor's degree in Statistics and Information Management at the University of Milano-Bicocca.

**Authors:** Sofia Menegozzo, Alessia Cazzulani

