# gdelt-project

This project investigated the question ‘What are the ten countries which are most similar to New Zealand in terms of the attitudes present when discussing climate change?’. Canada, Ireland, Australia, the United States, Malaysia, United Kingdom, Zimbabwe, Norway, Germany and South Africa were identified as the most similar countries to New Zealand. 

Data for this research was sourced from the Global Database of Events, Language and Tone (GDELT) Global Knowledge Graph. Specifically, data on the location, theme, publication language and Global Context Analysis Measures of articles from the month of May 2021 was used. The GDELT data was filtered to relevant entries and aggregated by country. Countries with fewer than 20 articles present were identified and excluded from the analysis. Cosine similarity was used as a measure of the ‘distance’ between the publications from each country.

Open in Google Colab: https://colab.research.google.com/github/pugglebert/gdelt-project/blob/main/gdelt_project.ipynb
