# Quantum Natural Language Processing Project - QuantumAI Internship(Quantum NLP : PROJ-00141)

## <p align="center">Quantum NLP for High-Level Sentence Classification</p>

![image](img1.png)

### Introduction:
Quantum Natural Language Processing (Quantum NLP) has emerged as a pioneering field at the intersection of quantum computing and natural language processing. It harnesses the unique properties of quantum systems to enhance the capabilities of traditional NLP techniques. This project aims to explore the potential of Quantum NLP in high-level sentence classification, employing both Classical and Quantum Pipelines, and to contribute novel features to the NLP landscape.

### Objective:
The primary goal of this project is to demonstrate the power of Quantum NLP in high-level sentence classification tasks and compare its performance with classical methods. Leveraging the inherent parallelism and information processing capabilities of quantum systems, this project aims to achieve improved accuracy and efficiency in classifying sentences based on their semantic meaning.

### The Team:
1. Dhruv Sachdeva
2. Hussein Shiri
3. Kiran Kaur
4. Maksym Husarov
5. Rishi Koushik Reddy Thippireddy

### How the project is organized:
This project contains 4 folders and 1 pdf:
1. sentences folder: contains a pdf for web scraping, collected sentences and the filtered sentences.
2. classical_pipeline folder: contains classical pipeline jupyter notebook with the sentences used.
3. hybrid_pipeline folder: contains hybrid pipeline jupyter notebook with the sentences used.
4. quantum_pipeline folder: contains quantum pipeline jupyter notebook with the sentences used.
5. research_paper: a small research paper for this project as a pdf.

### Technologies used:
- Python
- Spark
- Spark-nlp
- Jupyter notebook
- Google colab
- Lambeq


### Methodology:

Data Collection and Preprocessing: A diverse dataset of sentences from various domains will be collected and preprocessed to ensure uniformity and relevance. This dataset will serve as the foundation for training and evaluation.

<b>Classical Pipeline:</b> A classical NLP pipeline will be established as a baseline for comparison. This pipeline will involve common NLP techniques such as tokenization, feature extraction, and traditional machine learning models for sentence classification.

<b>Quantum Pipeline:</b> Leveraging quantum computing frameworks, a Quantum NLP pipeline will be developed. Quantum-enhanced techniques like Quantum Embedding and Quantum Amplitude Encoding will be employed to encode sentence semantics into quantum states. Quantum circuits will be designed for classification tasks using quantum algorithms like Variational Quantum Eigensolver (VQE) or Quantum Support Vector Machines (QSVM).

<b>Hybrid Approach:</b> A hybrid approach combining classical and quantum elements will be explored to capitalize on the strengths of both paradigms. This involves using classical pre-processing and post-processing steps alongside quantum computations for enhanced classification.

<b>Performance Comparison:</b> The performance of the Classical and Quantum Pipelines will be thoroughly evaluated using metrics like accuracy, precision, recall, and F1-score. A detailed analysis will be conducted to understand the scenarios where Quantum NLP excels.

<b>Contribution to NLP:</b> Aside from the comparative analysis, this project aims to contribute to the NLP field by introducing new features and techniques inspired by Quantum NLP. These could include novel ways of representing sentence semantics, improved feature extraction methods, and innovative strategies for solving high-level classification challenges.


### Comparison:

|           | classical | hybrid | quantum |
| --------- | ----------| ------ | ------- |
| time      | shortest  | medium | longest |
| memory    | least     | medium | biggest |
| accuracy  | best      | worst  | medium  |

In this table the time to complete, memory consumption and accuracy were compared.

It is reasonable that the classical pipeline is the best choice now. Quantum nlp is still a new field while classical nlp has been worked on a lot and many advances in the classical approach have been added to the classical programs. Also Spark-nlp is known to be the fastest, most advanced and most accurate nlp tool.

For a comparison between the hybrid and quantum case, although the quantum case got better accuracy with fewer training sentences, it's memory consumption was more than that of the hybrid pipeline. But a thing to note is that the quantum simulator used for both hybrid and quantum pipeline was without noise which could make the results a lot worse if noise was added, so the classical pipeline still wins even more.

![Screenshot from 2023-11-03 00-52-24](https://github.com/hosen20/quantumopenai_QNLP_internship_project/assets/84079430/74be433d-4bc7-4752-998a-f3bfa3b0fd68)


### Conclusion:
Through the exploration of Quantum NLP for high-level sentence classification and the comparison of Classical and Quantum Pipelines, this project aims to demonstrate the advancements that quantum computing can bring to the field of natural language processing. By contributing new features to the NLP landscape, this project aspires to push the boundaries of what’s achievable in semantic analysis and sentence classification.
