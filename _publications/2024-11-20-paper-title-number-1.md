---
title: "Hops: Fine-grained heterogeneous sensing, efficient and fair Deep Learning cluster scheduling system"
collection: publications
category: conferences
permalink: /publication/2024-11-20-paper-title-number-1
excerpt: |
  In recent years, the number of clusters and cloud platforms dedicated to deep learning acceleration has increased, and research on multi-tenant deep learning (DL) cluster scheduling systems has also advanced quickly. However, we have observed several shortcomings in these systems. Firstly, resources exhibit heterogeneity, but even the most advanced heterogeneity-aware schedulers can only reach the GPU-type level. In addition, most scheduling systems cannot perform well in balancing efficiency and fairness, which leads to unfair resource allocation and reduced user satisfaction. Moreover, we have noticed the phenomenon of cluster fragmentation and job starvation. 
  In this paper, we propose a new scheduling architecture: Hops, which includes (1) fine-grained heterogeneity awareness and accurate throughput estimators, which allows for heterogeneity awareness at the server entity level. (2) Hops performs resource allocation by executing prior weighted integer linear programming (ILP) for specific placement locations, effectively balancing fairness and efficiency. (3) Hops introduces "latency ratio fairness" (LRF) as a user fairness criterion, which helps reduce starvation and enhance user experience. (4) To address cluster fragmentation, Hops intentionally uses low-sensitivity jobs to fill fragments. The final experimental results show that, in physical experiments, compared with the state-of-the-art scheduling architectures: Sia and Gavel, Hops reduces cluster completion time by 18.5% to 34.2%, shortens average job completion time (JCT) by 27.4% to 45.9%, lowers waiting latency by 35.4% to 54.9%, significantly reduces cluster fragmentation, and performs significantly better in fairness metrics compared to Sia and Gavel. In the 512-GPU simulation experiments, Hops not only improves system efficiency but also reduces the maximum job latency ratio by over 21x and decreases cluster fragmentation to less than 1 GPU per round on average.
date: 2024-11-20
venue: "ACM Symposium on Cloud Computing (SoCC '24), November 20–22, 2024, Redmond, WA, USA"
slidesurl: "http://academicpages.github.io/files/slides1.pdf"
paperurl: "https://craneqinghe.github.io/QingheWang.github.io/files/ACM_SOCC_final_template.pdf"
citation: "Qinghe Wang, Futian Wang, and Xinwei Zheng. (2024). \"Hops: Fine-grained heterogeneous sensing, efficient and fair Deep Learning cluster scheduling system.\" <i>ACM Symposium on Cloud Computing</i>."
videourl: "https://www.youtube.com/embed/video_id"
---

The contents above will be part of a list of publications, if the user clicks the link for the publication than the contents of section will be rendered as a full page, allowing you to provide more information about the paper for the reader. When publications are displayed as a single page, the contents of the above "citation" field will automatically be included below this section in a smaller font.
