---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Education
======
* B.Tech in Computer Science and Engineering at Indian Institute of Technology Kharagpur, 2025 (expected)
* High School from Pragati Public School, Dwarka, New Delhi, India.

Work experience
======
* **Summer 2024: Data Science Research Intern**
  * ABB Ability Innovation Centre, Hyderabad India
  * Developed a novel state-of-art retrieval augmented generation pipeline capable of answering complex single-hop as well as multi-hop queries on an unstructured proprietary knowledge Base in the form of PDF documents.
  * The pipeline incorporated both Vector RAG and Graph RAG methods to create a highly superior data processing suite for retrieving highly relevant context from the Knowledge Base to answer complex closed-domain queries.
  * Developed a second pipeline on top of graph creation to create a standardized Ontology from the Knowledge Graph outlined in the incoming paper _"OntoRAG: An automated RAG pipeline for deriving Ontology for an Unstructured Knowledge Base"_.
  * Supervisor: Dr. Mayukha Pal

* **Spring 2024: Machine Learning Engineer**
  * Mindcase Technologies, New Delhi, India
  * Developed an Azure cloud based QnA chat application on proprietary data using FastAPI that ensures secure data flow between data transformation endpoints like LLM deployment, SQL Database and Vector Index.
  * Researched and developed a novel QnA pipeline based on evolving Retrieval Augmented Generation methods that handles queries of varying complexity using LLM Pipeline as data processors to enhance the QnA performance.
  * Integrated AWS Speech recognition and transcription service as well as Textract service through Python Web Socket APIs to enable live language recognition/audio transcribing and OCR use cases within local applications.
  * Supervisor: Shubham Saurabh

* **Skills**
  * **Programming Languages**: Python, C++, C, JavaScript, SQL, Bash.
  * **Programming Frameworks**: 
    * PyTorch 
    * Huggingface
    * Langchain 
    * LlamaIndex 
    * DsPy 
    * neo4j 
    * Pinecone 
    * Milvus
  * **Technologies**: Deep Learning, Natural Language Processing, Retrieval Augmented Generation, Graph Machine Learning, Knowledge Graphs, AWS, Azure, Google Cloud, Docker, Git.

Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>

  
Service and leadership
======
* Academic Evaluator at **Asian Physics Olympiad, 2022** with participants from 28 countries in Asian Continent.
