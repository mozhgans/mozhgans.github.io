---
title: "Context-enhanced concept disambiguation in wikification"
collection: publications
permalink: /publication/2019-10-01-paper-title-number-1
excerpt: ''
date: 2023-09-01
venue: 'Intelligent Systems'
paperurl: 'https://www.sciencedirect.com/science/article/pii/S2667305323000716'

citation: 'Mozhgan Saeidi, Kaveh Mahdaviani, Evangelos Milios, Norbert Zeh. (2023). &quot; journal={Intelligent Systems with Applications
}, pages={1--10}, year={2022}, publisher={World Scientific} <i>Journal 1</i>. 1(1).'
---
 Wikification is a method to automatically enrich a text with links to Wikipedia as a knowledge base. One step in Wikification is detecting ambiguous mentions, and one other step is disambiguating those mentions.

In this paper, we worked on the mention disambiguation problem. Some state-of-the-art disambiguation approaches have divided long input document text into non-overlapping windows. Later, for each ambiguous mention, they pick the most similar sense to the chosen meaning of the key-entity (a word that helps disambiguation other words of the text). Partitioning the input into disjoint windows means that the most appropriate key-entity to disambiguate a given mention may be in an adjacent window. The disjoint windows negatively affect the accuracy of these methods. This work presents CACW (Context-Aware Concept Wikifier), a knowledge-based approach to produce the correct meaning for ambiguous mentions in the document. CACW incorporates two algorithms; the first uses co-occurring mentions in consecutive windows to augment the available contextual information to find the correct sense. The second algorithm ranks senses based on their context relevancy. We also define a new metric for disambiguation to measure the coherence of the whole text document. Comparing our approach with state-of-the-art methods shows the effectiveness of our method in terms of text coherence in the English Wikification task. We observed between 10-20 percent improvement in the F1 measure compared to the state-of-the-art techniques.
