---
title: "Large Language Models are Fixated by Red Herrings: Exploring Creative Problem Solving and Einstellung Effect using the Only Connect Wall Dataset"
collection: publications
permalink: /publication/2019-10-01-paper-title-number-1
excerpt: 'This work explores how well large language models can solve creative problems by analyzing their performance on a dataset inspired by a quiz show segment that involves making connections between seemingly unrelated words.'
date: 2024-1-01
venue: 'Advances in Neural Information Processing Systems(NeuRIPS)'
paperurl: '[https://arxiv.org/pdf/2109.14497.pdf](https://proceedings.neurips.cc/paper_files/paper/2023/file/11e3e0f1b29dcd31bd0952bfc1357f68-Paper-Datasets_and_Benchmarks.pdf)'

citation: 'Naeini, Saeid and Saqur, Raeid and Saeidi, Mozhgan and Giorgi, John and Taati, Babak. (2023). &quot; journal={journal={Advances in Neural Information Processing Systems}}, pages={100--130}, year={2024}, publisher={NeurIPS} <i>Journal 1</i>. 1(1).'
---
The quest for human imitative AI has been an enduring topic in AI research since
its inception. The technical evolution and emerging capabilities of the latest cohort
of large language models (LLMs) have reinvigorated the subject beyond academia
to the cultural zeitgeist. While recent NLP evaluation benchmark tasks test some aspects of human-imitative behavior (e.g., BIG-bench’s ‘human-like behavior’ tasks),
few, if not none, examine creative problem-solving abilities. Creative problem-solving in humans is a well-studied topic in cognitive neuroscience with standardized
tests that predominantly use the ability to associate (heterogeneous) connections
among clue words as a metric for creativity. Exposure to misleading stimuli —
distractors dubbed red herrings — impede human performance in such tasks via the
fixation effect and Einstellung paradigm. In cognitive neuroscience studies, such
fixations are experimentally induced by pre-exposing participants to orthographically similar incorrect words to subsequent word fragments or clues. The popular
British quiz show Only Connect’s Connecting Wall segment essentially mimics
Mednick’s Remote Associates Test (RAT) formulation with built-in, deliberate
red herrings, which makes it an ideal proxy task to explore and study the fixation
effect and Einstellung paradigm from cognitive neuroscience in LLMs. In this
paper, we present the novel Only Connect Wall (OCW) dataset and report results
from our evaluation of selected pre-trained language models and LLMs on creative
problem solving tasks like grouping clue words by heterogeneous connections and
identifying correct open knowledge domain connections in respective groups. We
synthetically generate two additional datasets: OCW-Randomized, OCW-WordNet
to further analyze our red-herrings hypothesis in language models. The code and
link to the dataset are available at https://github.com/TaatiTeam/OCW.


@article{naeini2023large,
  title={Large language models are fixated by red herrings: Exploring creative problem solving and einstellung effect using the only connect wall dataset},
  author={Naeini, Saeid and Saqur, Raeid and Saeidi, Mozhgan and Giorgi, John and Taati, Babak},
  journal={arXiv preprint arXiv:2306.11167},
  year={2023}
