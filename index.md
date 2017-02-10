---
layout: default
title: {{ site.title }}
---

## Knowledge Graph Construction From Text

#### AAAI 2017 Tutorial <a href="http://www.aaai.org/Conferences/AAAI/2017/aaai17program.pdf">(schedule)</a>
#### February 5, 2017

#### Location: Continental 7-9, Ballroom Level (Hilton SF Union Sq)

<a href="https://www.jaypujara.org/"><img alt="Jay Pujara" src="img/jay.png" height="200px"></a>
<a href="http://sameersingh.org/"><img alt="Sameer Singh" src="img/sameer.png" height="200px"></a>
<a href="http://allenai.org/team/bhavanad/"><img alt="Bhavana Dalvi" src="img/bhavana.png" height="200px"></a>

### [Jay Pujara](https://www.jaypujara.org/), [Sameer Singh](http://sameersingh.org/), [Bhavana Dalvi](http://allenai.org/team/bhavanad/)

With the proliferation of large collections of unstructured text, the problem of extracting structured knowledge and integrating it into a coherent knowledge graph has become increasingly important.
Applications that rely on structured knowledge representations include digital assistants (Siri, Alexa, Cortana, and Google Now), question answering, summarization, and as well as many downstream autonomous decision-making.
Due to its importance, this area has been an active area of research spanning areas of natural language processing, information extraction, information integration, databases, search, and machine learning.

<!--
The variety and complexity of the available scholarly work, however, makes it difficult for a newcomer to familiarize themselves with the field.
Knowledge graph construction has been decomposed into a large number of inter-dependent and sometimes overlapping tasks, such as the traditional natural language processing, semantic parsing, entity extraction, entity disambiguation and linking, identification and classification of relations, and completion of the knowledge graph.
The kinds of machine learning approaches have also been quite varied, ranging from classification/clustering, probabilistic graphical models, probabilistic logic formulations, matrix/tensor factorization-based approaches, and more recently, deep learning.
There are also a plethora of existing systems that have been proposed, including from top universities such as Stanford (DeepDive), Carnegie Mellon (NELL), University of Washington (OpenIE), Mannheim (DBpedia), and the Max Planck Institut Informatik (YAGO, WebChild) among others.
This diverse and fragmented literature poses a significant roadblock for newcomers to contribute to the field.

We are designing our tutorial to address this barrier.
-->

Our goal is to present an accessible and structured overview of the existing approaches to extracting candidate facts from text and incorporating these into a well-formed knowledge graph. Our approach includes identifying the common themes and challenges in the area, and comparing and contrasting the existing approaches on the basis of these aspects.
We believe such a unifying framework will provide the necessary tools and perspectives to enable the newcomers to the field to explore, evaluate, and develop novel techniques for automated knowledge graph construction.

## Outline (with draft slides)

![Tutorial Overview](img/overview.png "Overview of the Tutorial")

### Part 1: Knowledge Graph Primer \[ [Slides](slides/Part1_Intro.pdf) \]
- What is a Knowledge Graph?
-	Why are Knowledge Graphs Important?
-	Where do Knowledge Graphs come from?
-	Knowledge Representation Choices
-	Problem Overview
 

### Part 2: Knowledge Extraction from Text

- NLP Fundamentals \[ [**Slides**](slides/Part2a_NLP.pdf) \]
   - Tokenization, chunking
   - Part-of-speech tagging
   - Named entity recognition
   - Dependency parsing
   - Entity resolution, coreference, and linking
- Information Extraction \[ [**Slides**](slides/Part2b_IE.pdf) \]
   - Defining knowledge domains
   - Learning knowledge extractors
   - Scoring extracted knowledge
   - Categories of IE techniques
   - Compositional models: Knowledge fusion 
   - IE systems in practice



#### Coffee Break

### Part 3: Knowledge Graph Construction
- Graph construction overview
- Probabilistic Models \[ [**Slides**](slides/Part3a_Prob.pdf) \]
  - Motivation
  - Graphical models
  - Random walk approaches
- Embedding Techniques \[ [**Slides**](slides/Part3b_Embds.pdf) \]
  - Relation extraction techniques
    - Matrix factorization 
    - Embedding entity pairs
  - Graph completion techniques
    - Tensor factorization
    - Entity and relation embeddings
    - Compositional models

### Part 4: Critical Overview and Conclusion \[ [Slides](slides/Part4_Summary.pdf) \]
- Summary                   
- Success stories       
- Datasets, tasks, softwares   
- Exciting active research    
- Future research directions    
