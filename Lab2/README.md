## 於Pubmed 200k資料集，建立反向索引

- 目標：學習使用現有工具(Pyserini)建立反向索引 
- 資料集：Pubmed200k
- 使用Library：Pyserini https://github.com/castorini/pyserini 
 
- 說明：
    - 使用Pubmed200k (The PubMed 200k RCT dataset is described in Franck Dernoncourt, Ji Young Lee. PubMed 200k RCT: a Dataset for Sequential Sentence Classification in Medical Abstracts. International Joint Conference on Natural Language Processing (IJCNLP). 2017.) 資料集可從 https://www.dropbox.com/s/miyb2awm2esrcpk/pubmed%20220%20train.txt?dl=0 下載。
    - 使用Pyserini (Follow https://github.com/castorini/pyserini#how-do-i-index-and-search-my-own-documents 中的說明) 建立文章等級的反向索引。
- 需求：比較暴力搜尋法(i.e., linear scan)與使用反向索引(retreive by inverted index)所需的時間差異。