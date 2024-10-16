# Description
In the Big Data Challenge (BDC) Satria Data 2024, participants were challenged to classify issues discussed by authors in their tweets related to the 2024 Presidential Election. This classification was based on the Astagatra framework, which represents components of national resilience. The task involved categorizing tweets into eight classes:

Ideology: Fundamental values, principles, and worldviews guiding the nation and state.
Politics: Government systems, policies, and political processes within the country.
Economy: Economic management, financial resources, and efforts to create prosperity.
Socio-Culture: Social values, cultural norms, and societal aspects influencing national unity and identity.
Defense and Security: National defense and internal security against threats or disruptions.
Natural Resources: Management and utilization of natural resources for development and national security.
Geography: Location, physical conditions, and natural environment affecting life and policies.
Demography: Population structure, growth, distribution, and dynamics influencing national policies and development. This competition required participants to analyze tweets and correctly classify them into one of these eight categories related to the nation's resilience factors.
# Research Highlight
Worked with a dataset of 5,000 tweets categorized and 8 classes. Cleaned the data by removing slang words, stopwords, and special characters, and applied tokenization.
Developed a predictive model using IndoBERT for sequence classification. Configured the model with an optimizer and CrossEntropyLoss, and trained it using DataLoader for efficient batch processing.
Evaluated the model, achieving a balanced accuracy of 41% on the new dataset
