| File        | Discription      |
| ------------|-------------| 
|[groupby_parse_tokenize.ipynb](groupby_parse_tokenize.ipynb)  | Groups the data by document. Parses the HTML text. Then it tokenize it. Creates the file: tokenized_data | 
| [stemming.ipynb](stemming.ipynb)      | Removes stopwords from tokenized file and stems the words. Creates the file: stemmed_data    |  
| [evaluate_query_expansion.ipynb](evaluate_query_expansion.ipynb) | Computes the Normalized Discounted Cumulative Gain for the non stemmed corpus (tokenized_data) and stemmed corpus (stemmed_data)|
|[query_expansion.ipynb](query_expansion.ipynb)  | creates the expanded queries|
|[results_q_expansion.ipynb](results_q_expansion.ipynb)  | averages nDCG scores and plots them|
|[DESM_retrieval.ipynb](DESM_retrieval.ipynb) | DESM document retrieval using IN/OUT layer combinations|
