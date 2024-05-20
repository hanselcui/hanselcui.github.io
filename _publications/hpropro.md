---
title: "Exploring Hybrid Question Answering via Program-based Prompting"
collection: publications
permalink: /publication/hpropro
excerpt: 'We propose HProPro, a novel program-based framework for the hybrid question answering task.'
date: 2024-05-18
venue: 'ACL'
slidesurl:
paperurl: 'https://arxiv.org/pdf/2402.10812'
citation: 'Shi Q, Cui H, Wang H, et al. Exploring Hybrid Question Answering via Program-based Prompting[J]. arXiv preprint arXiv:2402.10812, 2024.
'
---
[ACL 2024, Main Conference] [[PDF](https://arxiv.org/pdf/2402.10812), [Code](https://github.com/qshi95/HProPro)]

Question answering over heterogeneous data requires reasoning over diverse sources of data, which is challenging due to the large scale of information and organic coupling of heterogeneous data. Various approaches have been proposed to address these challenges. One approach involves training specialized retrievers to select relevant information, thereby reducing the input length. Another approach is to transform diverse modalities of data into a single modality, simplifying the task difficulty and enabling more straightforward processing. In this paper, we propose HProPro, a novel program-based prompting framework for the hybrid question answering task. HProPro follows the code generation and execution paradigm. In addition, HProPro integrates various functions to tackle the hybrid reasoning scenario. Specifically, HProPro contains function declaration and function implementation to perform hybrid information-seeking over data from various sources and modalities, which enables reasoning over such data without training specialized retrievers or performing modal transformations. Experimental results on two typical hybrid question answering benchmarks HybridQA and MultiModalQA demonstrate the effectiveness of HProPro: it surpasses all baseline systems and achieves the best performances in the few-shot settings on both datasets.
