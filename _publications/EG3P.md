---
title: "Explanation Graph Generation via Generative Pre-training over Synthetic Graphs"
collection: publications
permalink: /publication/EG3P
excerpt: 'Explanation Graph Generation via Generative Pre-training over Synthetic Graphs'
date: 2023-05-16
venue: 'ACL-Findings'
slidesurl:
paperurl: 'https://arxiv.org/abs/2306.00652'
citation: 'Cui H, Li S, Zhang Y, et al. Explanation Graph Generation via Generative Pre-training over Synthetic Graphs[J]. arXiv preprint arXiv:2306.00652, 2023.'
---
Accecpted by ACL2023-Findings, [[PDF](https://arxiv.org/abs/2306.00652), [Code](https://github.com/hanselcui/EG3P)]

The generation of explanation graphs is a significant task that aims to produce explanation graphs in response to user input, revealing the internal reasoning process. This task is challenging due to the significant discrepancy between unstructured user queries and structured explanation graphs. Current research commonly fine-tunes a text-based pre-trained language model on a small downstream dataset that is annotated with labeled graphs. However, due to the limited scale of available datasets, this approach may prove to be insufficient in bridging the gap between natural language text and structured graphs. In this paper, to alleviate the above limitations, we propose a novel pre-trained framework EG3P(for Explanation Graph Generation via Generative Pre-training over synthetic graphs) for the explanation graph generation task. Specifically, we first propose a text-to-graph generative task to pre-train the model with the goal of bridging the text-graph gap. Additionally, we propose an automatic corpus synthesis strategy for synthesizing a large scale of high-quality corpus, reducing the reliance on costly manual annotation methods. Experimental results on ExplaGraphs show the effectiveness of EG3P that our model surpasses all baseline systems with remarkable margins. Besides, further analysis demonstrates that EG3P is able to generate better explanation graphs on actual reasoning tasks such as CommonsenseQA and OpenbookQA.
