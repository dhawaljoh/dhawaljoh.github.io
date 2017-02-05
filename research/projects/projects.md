---
layout: page
title: Projects
permalink: /research/projects/
---

-	**Analysis of clinical notes of ICU patients using Topic Models**: [Work done at XRCI, IISc with <em><a class="tosu" href="https://sites.google.com/site/vaibhavrajan/" target="_blank">Dr. Vaibhav Rajan</a></em>] <br>
Worked on predictive healthcare using unstructured nursing notes by looking at temporal evolutions of topic proportions generated via Topic Modelling.

-	**[Temporal Scoping of Relational Facts in a Knowledge Base](/files/openday2015.pdf)**: [Work done at SERC, IISc with <em><a class="tosu" href="http://www.talukdar.net/" target="_blank">Prof. Partha Talukdar</a></em>] <br>
To identify if a relation existed between two entities in a sentence, we constructed a model consisting of n-grams which provided clues for the relation. These n-grams, along with features from Entity Linking were used to train a GBDT to identify relations. Stanford’s SUTime was used to extract temporal information present and then normalized. Triggers chosen manually from the language model were used to indicate the start or end of relationships. We devised an algorithm to update the start/end times iteratively as more temporal information was found through new sentences.

-   **[Automatic Driver Behaviour Profiling](https://github.com/dhawaljoh/IIT-Kharagpur)**: [Work done at CSE, IIT Kharagpur with <em><a class="tosu" href="http://www.facweb.iitkgp.ernet.in/~sudeshna/" target="_blank">Prof. Sudeshna Sarkar</a></em>] <br>
Worked on profiling the driving patterns of various drivers using GPS data of trucks across India over 15 years using GPS dataset provided by MHRD. Some preliminary data munging and visualizations were done to understand the spread of data. Detection of hotspots(stoppage areas, resting places) using DBSCAN algorithm and road segmentation based on their speed profiles was also done. I also modified the "simplekml" module to plot the GPS points on Google Maps.

-   **[Craigslist Post Classifier: Identify the Category](https://github.com/dhawaljoh/craigslist_category_classification)**: Used bag of words model, tf-idf and SVM to classify posts on Craigslist into sections based on the product description.
The open dataset was available on HackerRank. **Accuracy**: 81%

-   **[Peptide Status Detection](https://github.com/dhawaljoh/PeptideStatusDetection)**: Worked with Prof. Smitha Nair on detecting Fibrous regions in proteins using the UniProtKB/Swiss-Prot data. Used Support Vector Machines and Bee Colony Optimization for PCA.

-   **[Data Science London + Scikit-learn](https://github.com/dhawaljoh/kaggle--data-science-london)**: Kaggle competition to explore sklearn.