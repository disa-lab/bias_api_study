# Bias API Library Study
Replication package for the paper "Applications and Challenges of Fairness APIs in Machine Learning Software".

## Files
Following directory and files are included in this repository:
- `api libraries/`: contains data related to the 11 studied bias API libraries.
  - `bias_api_libraries.csv`: contains details (e.g., popularity metrics, update information, etc.) of our selected 11 bias API libraries.
  - `bias_api_libraries_download_stats.csv`: contains download stat data of the 11 libraries.
  - `bias_api_libraries_labelled_apis.csv`: contains manually labeled API information of the APIs found within the 11 bias API libraries.
  
- `applications/`: contains data related to the use cases of the 230 studied GitHub repositories.
  - `repository_summary_230_repos.csv`: contains summary of our performed analysis on the final selected repository set.
  - `repository_metadata_230_repos.csv`: contains additional metadata information of our final selected repository set.
  - `repository_detected_api_usage_3664_entries.csv`: contains details about all detected fairness APIs within our selected repository set.
  - `usecase_summary_25_usecases.csv`: contains descriptions of the 25 use cases that we found within our selected repository set.
  - `repository_nongeneric_detection_api_trends.csv`: contains detection API usage data that have been used to generate the trend plots.
  - `repository_nongeneric_mitigation_api_trends.csv`: contains mitigation API usage data that have been used to generate the trend plots.

- `challenges/`: contains data related to the topics of issue and issue comments of the 11 studied API libraries.
  - `topic_modeling.py.ipynb`: contains the code to run the LDA topic modeling and generate topics.
  - `issue_discussions_metadata_2540_discussions.csv`: contains the metadata information of the used issue discussions. 
  - `issue_discussion_topics_labelled_2540_discussions.csv`: contains the topic labeling outcome of the used issue discussions. This file contains the following information:
    - `Dominant Topic`: Dominant topic within an issue discussion  labeled by the LDA topic modeling.
    - `topic_label`: Manually assigned topics labels.
    - `topic_type`: Higher level categorization of the manually labeled topics.
