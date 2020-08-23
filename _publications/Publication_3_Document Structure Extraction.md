---
title: "Document Structure Extraction for Forms using Very High Resolution Semantic Segmentation"
collection: publications
permalink: /publication/3/
excerpt: ''
date: 2020-08-20
venue: '<i>Accepted</i> at European Conference on Computer Vision (ECCV 2020)'
paperurl: 'https://www.ecva.net/papers/eccv_2020/papers_ECCV/papers/123730647.pdf'
citation: 'Mausoom Sarkar, Milan Aggarwal*, Arneh Jain*, <b>Hiresh Gupta*</b>, Balaji Krishnamurthy'
---
<b>Abstract:</b> 
Structure extraction from document images has been a long standing research topic due to its high impact on a wide range of practical applications. In this paper, we share our findings on employing a hierarchical semantic segmentation network for this task of structure extraction. We propose a prior based deep hierarchical CNN network architecture that enables document structure extraction using very high resolution($1800  \times 1000$) images. We divide the document image into overlapping horizontal strips such that the network segments a strip and uses its prediction mask as prior while predicting the segmentation for the subsequent strip. We perform experiments establishing the effectiveness of our strip based network architecture through ablation methods and comparison with low-resolution variations.
Further, to demonstrate the capabilities of our network, we train it on only one type of documents (Forms) and achieve state-of-the-art results over other general document datasets. We introduce this new human-annotated forms dataset, and we do ablations to show that our method significantly outperforms different segmentation baselines on this dataset in extracting hierarchical structures. Our method is currently being used in a world-leading customer experience management software suite for automated conversion of paper and PDF forms to modern HTML based forms.

[Download paper here](https://www.ecva.net/papers/eccv_2020/papers_ECCV/papers/123730647.pdf).