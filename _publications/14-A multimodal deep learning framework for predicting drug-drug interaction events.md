---
title: "A multimodal deep learning framework for predicting drug-drug interaction events"
collection: publications
permalink: /publication/2020/5/14-A multimodal deep learning framework for predicting drug-drug interaction events
excerpt: 'This paper proposed a deep learning framework that combines different features of drugs to predict drug-drug interaction events.'
date: 2020/5/14
venue: 'Bioinformatics'
paperurl: 'https://academic.oup.com/bioinformatics/article-abstract/doi/10.1093/bioinformatics/btaa501/5837109'
citation: 'Deng Y, Xu X, Qiu Y, et al. A multimodal deep learning framework for predicting drug-drug interaction events[J]. Bioinformatics, 2020.'
---

<a href='https://academic.oup.com/bioinformatics/article-abstract/doi/10.1093/bioinformatics/btaa501/5837109'>Download paper here</a>

Drug-drug interactions (DDIs) are one of the major concerns in pharmaceutical research. Many machine learning based methods have been proposed for the DDI prediction, but most of them predict whether two drugs interact or not. The studies revealed that DDIs could cause different subsequent events,and predicting drug-drug interaction-associated events is more useful for investigating the mechanism hidden behind the combined drug usage or adverse reactions. In this paper, we collect DDIs from DrugBank database, and extract 65 categories of DDI events by dependency analysis and events trimming. We propose a multimodal deep learning framework named DDIMDL that combines diverse drug features with deep learning to build a model for predicting drug-drug interaction-associated events. DDIMDL first constructs deep neural network-based sub-models by respectively using four types of drug features: chemical substructures, targets, enzymes and pathways, and then adopts a joint DNN framework to combine the sub-models to learn cross-modality representations of drug-drug pairs and predict DDI events. In computational experiments, DDIMDL produces high-accuracy performances and has high efficiency. Moreover, DDIMDL outperforms state-of-the-art DDIevent prediction methods and baseline methods. Among all the features of drugs, the chemical substructures seem to be the most informative. With the combination of substructures, targets and enzymes, DDIMDL achieves an accuracy of 0.8852 and an area under the precision-recall curve of 0.9208.