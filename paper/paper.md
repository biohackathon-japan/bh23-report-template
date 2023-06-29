---
title: 'BioHackJP 2023 Report R1: linked data standardization with LLMs'
title_short: 'BioHackJP 2023 LD-LLM'
tags:
  - Linked Data
  - Large Language Models
authors:
  - name: First Author
    orcid: 0000-0000-0000-0000
    affiliation: 1
  - name: Last Author
    orcid: 0000-0000-0000-0000
    affiliation: 2
affiliations:
  - name: First Affiliation
    index: 1
  - name: Second Affiliation
    index: 2
date: 30 June 2023
cito-bibliography: paper.bib
event: BH23JP
biohackathon_name: "BioHackathon Japan 2023"
biohackathon_url:   "https://2023.biohackathon.org/"
biohackathon_location: "Kagawa, Japan, 2023"
group: R1
# URL to project git repo --- should contain the actual paper.md:
git_url: https://github.com/biohackathon-jp/bh23-report-template
# This is the short authors description that is used at the
# bottom of the generated paper (typically the first two authors):
authors_short: First Author \emph{et al.}
---

# Background

The field of bioinformatics plays a crucial role in enabling researchers to extract meaningful insights from the vast amount of biological data generated today. With advancements in technology and the availability of large-scale datasets, it has become increasingly important to develop standardized approaches for representing and integrating biological information. Linked data, a method for publishing structured data on the web, has emerged as a promising solution for facilitating the integration and interoperability of diverse biological data sources.

The BioHackathon 2023, held in Japan, provided an ideal platform for researchers and bioinformatics enthusiasts to collaborate and explore innovative solutions to address the challenges in the field. Our project focused on the application of Linked Data and Large Language Models (LLMs) to standardize biological data and enhance its accessibility and usability.

LLMs, such as OpenAI's GPT-3.5 architecture, have demonstrated remarkable capabilities in understanding and generating human-like text. Leveraging the power of LLMs, we aimed to automate the process of extracting relevant biological terms from unstructured text and mapping them to existing ontology terms. Ontologies, which are hierarchical vocabularies of terms and their semantic relationships, provide a standardized framework for organizing and categorizing biological concepts.

# Outcomes

To achieve our objectives, we conducted a comprehensive survey of open source language models available and evaluated their suitability for our task. We explored different models, taking into consideration factors such as performance, computational requirements, and ease of deployment. Subsequently, we sought to run the selected models on a local computer, ensuring that the infrastructure requirements were met.

Having established a working environment for LLMs, we developed a set of pipelines that incorporated various natural language processing techniques to extract relevant biological terms from textual data. These terms were then matched and mapped to the corresponding ontology terms, thereby providing a standardized representation of the extracted information. By utilizing Linked Data principles, we aimed to create an interconnected network of biological knowledge that would facilitate data integration and enable advanced analysis.

![Caption for BioHackrXiv logo figure](./biohackrxiv.png)

# Future work

Moving forward, there are several areas of potential future work to enhance our project's linked data standardization with LLMs. First, exploring advanced LLMs and optimizing computational efficiency can improve performance. Additionally, expanding ontology mapping to cover more domains and integrating external data sources would increase the scope of our standardization efforts. Validating and evaluating results against gold-standard datasets, involving domain experts, and developing a user-friendly interface for researchers to interact with the pipelines are crucial next steps. These future endeavors will refine and advance our methodology, increasing its impact and adoption in bioinformatics.

## Acknowledgements

We would like to thank the fellow participants at BioHackathon 2023 for their collaboration and constructive advice, which greatly influenced our project. We are grateful to the organizers for providing this platform and the developers of open source language models. Special thanks to our mentors, advisors, and colleagues for their guidance and support. Without their contributions, our project in linked data standardization with LLMs in bioinformatics would not have been possible.

## References

1.
