# Dr-Lane-Work

## Dataset notebook
The Dataset notebook contains code to transform the original JSON files from both OKState and ORState into formats compatible with Kaggle Models. Additionally, the notebook includes code for generating unique identifiers for each newly created separated file in the format Year-Month-Date-order_number-OKU/OSU.

## Hyperlinks notebook_Xiangyu
This notebook contains web scraping scripts designed to methodically extract certain types of hyperlinks from a sequence of web pages. The scripts are particularly focused on identifying and accumulating links associated with the United States Department of Agriculture (USDA).Furthermore, the methodology is tailored to pinpoint whether the scraped URL links include specific strings like "usda" and "nass," ensuring a targeted and efficient extraction of relevant data.
There are multiple sub analyses. For example, one of the scripts selectively gathers USDA-related links while intentionally omitting those that contain the term 'extension' in their URLs. 

## OSU_OKU_TextAnalysis
This notebook employs the LDA multiscore method from the gensim package in Python to train a specialized Latent Dirichlet Allocation (LDA) model on the extension corpora of each university's files. For this model, we established a cap of 20 topics, each comprising 10 words, and generated a frequency table for each topic. Subsequently, these topics were mapped back to their respective publications.
