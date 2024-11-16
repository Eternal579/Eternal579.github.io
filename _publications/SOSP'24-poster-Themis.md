---
title: "Themis: Efficiently Mitigating Congestion-Induced Fairness Disparities in Long-Haul RDMA Networks"
collection: publications
category: conferences
permalink: /publication/SOSP'24-poster-Themis
excerpt: 'This paper is about leveraging programmable switch to mitigate unfairness caused by the difference of feedback loops for intra/inter-DC traffic'
date: 2024-09-21
venue: 'SOSP poster'
paperurl: 'http://bugeater.space/files/sosp24poster_Themis.pdf'
# citation: 'Your Name, You. (2024). &quot;Paper Title Number 3.&quot; <i>GitHub Journal of Bugs</i>. 1(3).'
---
Long feedback loop of inter-DC traffic is the crux of unfairness in long-haul networks. During the period from when congestion starts until the feedback signal arrives at the remote inter-DC traffic sender, only intra-DC traffic is suppressed. Meanwhile, inter-DC traffic continues at its original speed, causing queue buildup at the congestion point. This results in a significant increase in intra-DC FCT, while inter-DC traffic FCT is relatively less affected. To mitigate this issue, we present Themis, a fairness maintenance patch for widely deployed RDMA congestion control algorithms, via preemptive notification points and reaction points at external switch.
