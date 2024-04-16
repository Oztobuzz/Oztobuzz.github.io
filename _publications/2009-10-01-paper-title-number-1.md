---
title: "Low-Rank Adaptation Approach for Vietnamese-Bahnaric Lexical Mapping from Non-Parallel Corpora"
collection: publications
# permalink: /publication/2009-10-01-paper-title-number-1z`
excerpt: 'This paper is about the number 1. The number 2 is left for future work.'
date: 2023-10-01
venue: 'The 3rd Symposium on Computer Science & Engineering'
paperurl: 'http://Oztobuzz.github.io/files/ASK.pdf'
# citation: 'Your Name, You. (2009). &quot;Paper Title Number 1.&quot; <i>Journal 1</i>. 1(1).'
---

Bilingual dictionaries are vital tools for automated machine translation. Leveraging advanced machine learning techniques, it is possible to construct bilingual dictionaries by automatically learning lexical mappings from bilingual corpora. However, procuring extensive bilingual corpora for low-resource languages, such as Bahnaric, poses a significant challenge. Recent studies suggest that non-parallel corpora, supplemented with a handful of anchor words, can aid in the learning of these mappings, which contain parameters for automated translation between source and target languages. The prevailing methodology involves using Generative Adversarial Networks (GANs) and solving the Procrustes orthogonal problem to generate this mapping. 

This approach, while innovative, exhibits instability and demands substantial computational resources, posing potential issues in rural regions where Bahnaric is spoken natively. To mitigate this, we propose a low-rank adaptation strategy, where the limitations of GANs can be circumvented by directly calculating the rigid transformation between the source and target languages. We evaluated our approach using the French-English dataset, and a low-resource dataset, Vietnamese-Bahnaric. Notably, the Vietnamese-Bahnaric lexical mapping produced by our method is valuable not only to the field of computer science, but also contributes significantly to the preservation of Bahnaric cultural heritage within Vietnam’s ethnic minority communities.
