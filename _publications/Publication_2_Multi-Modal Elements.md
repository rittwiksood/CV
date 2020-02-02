---
title: "Multi-Modal Elements Association Approach for Form Structure Extraction"
collection: publications
permalink: /publication/2/
excerpt: ''
date: 2020-03-05
venue: '<i>Accepted</i> at IEEE Winter Conference on Applications of Computer Vision (WACV 2020)'
paperurl: ''
citation: "Milan Aggarwal, Mausoom Sarkar, <b>Hiresh Gupta</b>, Balaji Krishnamurthy"
---
<b>Abstract:</b>
Document structure extraction has been a widely re-searched area for decades. Recent work in this direction has been deep learning-based, mostly focusing on extract-ing structure using fully convolution NN through semantic segmentation. In this work, we present a novel multi-modal approach for form structure extraction. Given simple ele-ments such as textruns and widgets, we extract higher-order structures such as TextBlocks, Text Fields, Choice Fields, and Choice Groups, which are essential for information col-lection in forms. To achieve this, we obtain a local image patch around each low-level element (reference) by iden-tifying candidate elements closest to it. We process textual and spatial representation of candidates sequentially through a BiLSTM to obtain context-aware representations and fuse them with image patch features obtained by processing it through a CNN. Subsequently, the sequential decoder takes this fused feature vector to predict the association type between reference and candidates. These predicted associations are utilized to determine larger structures through connected components analysis. Experimental results show the effectiveness of our approach achieving a recall of 90.29%, 73.80%, 83.12%, and 52.72% for the above structures, respectively, outperforming semantic segmentation baselines signiﬁcantly. We show the efﬁcacy of our method through ablations, comparing it against using individual modalities. We also introduce our new rich human-annotated Forms Dataset.