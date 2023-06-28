[![GitHub issues](https://img.shields.io/github/issues/Altishofer/HansardSentimentTopicAnalysis.svg)](https://github.com/Altishofer/HansardSentimentTopicAnalysis/issues)
[![GitHub pull requests](https://img.shields.io/github/issues-pr/Altishofer/HansardSentimentTopicAnalysis.svg)](https://github.com/Altishofer/HansardSentimentTopicAnalysis/pulls)

# Change of Relevance of Royals in Parliament
Repository for recreating computed results used for the argumentation in the paper.

## Prequisits
- Python 3.9.x
- Jupyter Lab
- Eventually Microsoft Building Tols (https://aka.ms/vs/17/release/vs_BuildTools.exe)

## Setup & Computation
1) clone repository
   ```shell
   git clone https://github.com/Altishofer/HansardSentimentTopicAnalysis.git
   ``` 
3) access directory of cloned repository
   ```shell
   cd HansardSentimentTopicAnalysis
   ```
4) create needed directories (empty directories are not allowed on GitHub)
   ```shell
   mkdir processedData && mkdir diagramOutput && mkdir rawData
   ```
5) put the following files into the "rawData" folder (files were provided from Prof. Dr. Gerold Schneider)
  - sampler_10ktexts_perdecade.ALL2.tsv
  - sampler_10ktexts_perdecade.headed.ALL2.tsv
  - sampler_50ktexts_perdecade.headed.ALL.tsv
3) run Jupyter Node with Python 3.9.x Kernel
4) run all scripts except "Compare_BERTopic_PAM_SaHu" && "Sentiment_Normalized_MaBa" which MUST be last to be executed to compare the results of the previous results
