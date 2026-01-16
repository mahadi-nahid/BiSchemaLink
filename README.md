# Rethinking Schema Linking: A Context-Aware Bidirectional Retrieval Approach for Text-to-SQL [EACL 2026]

BiSchemaLink implements a context-aware bidirectional schema linking framework for Text-to-SQL, combining table-first and column-first retrieval to improve schema recall, reduce false positives, and boost execution accuracy on large databases.

## Abstract

Schema linking -- the process of aligning natural language questions with database schema elements -- is a critical yet underexplored component of Text-to-SQL systems. While recent methods have focused primarily on improving SQL generation, they often neglect the retrieval of relevant schema elements, which can lead to hallucinations and execution failures. In this work, we propose a context-aware bidirectional schema retrieval framework that treats schema linking as a standalone problem. Our approach combines two complementary strategies: table-first retrieval followed by column selection, and column-first retrieval followed by table selection. It is further augmented with techniques such as question decomposition, keyword extraction, and keyphrase extraction. Through comprehensive evaluations on challenging benchmarks such as BIRD and Spider, we demonstrate that our method significantly improves schema recall while reducing false positives. Moreover, SQL generation using our retrieved schema consistently outperforms full-schema baselines and closely approaches oracle performance, all without requiring query refinement. Notably, our method narrows the performance gap between full and perfect schema settings by 50\%. Our findings highlight schema linking as a powerful lever for enhancing Text-to-SQL accuracy and efficiency.

## Method Overview 

<image src="/Figures/bi-sl-intro-sketch-1.pdf">

<image src="/Figures/Figures/bi-sl-v2-sketch-3.pdf">

## Code and Data 

Coming soon.


## Paper 

If you want to cite our papers, please use:


```bibtex
@inproceedings{
nahid2026rethinking,
title={Rethinking Schema Linking: A Context-Aware Bidirectional Retrieval Approach for Text-to-{SQL}},
author={Md Mahadi Hasan Nahid and Davood Rafiei and Weiwei Zhang and Yong Zhang},
booktitle={19th Conference of the European Chapter of the Association for Computational Linguistics},
year={2026},
url={https://openreview.net/forum?id=O4E6HLB1SO}
}
```
