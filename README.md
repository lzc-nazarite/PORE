## Overview
The repository for the EMNLP2024 Paper —— Rethinking the Reversal Curse of LLMs: a Prescription from Human Knowledge Reversal.

## Three Reversal Curse Datasets
1. Celebrity Dataset: It includes 1K most popular celebrities from IMDB and queries GPT-4 for their parents. Consequently, it contained 1,513 items of relationships between actual celebrities
and their parents. The relational words for a parentchild pair are "father/mother" and "child". The original version comes from 'The reversal curse: Llms trained on" a is b" fail to learn "b is a"'

2. Author-Work Dataset: It is derived from the DBLP (Digital Bibliography & Library Project) bibliography, a widely used and publicly available bibliographic database of compute science research papers and proceedings. We randomly selected 2,000 author-work pairs from it and limited each author to no more than three books. The relational words for an author-work pair are "book" and "work".

3. Company-Ceo Dataset: It is crawled from Forbes.com. We first selected the data on the top 2000 companies and their corresponding chief executive officers. Then, we filtered out the N/A entries and consequently obtained 1,697 items of relationships between actual companies and their corresponding chief executive officers. The relational words for a company-CEO pair are "company" and "CEO".

## Code
The code is based on "https://github.com/trestad/mitigating-reversal-curse", where we only replace the dataset and adjust the hyper-parameter.
