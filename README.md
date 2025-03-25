# Role of NLP in Construction Management

## Introduction

Construction consulting heavily relies on detailed reporting to communicate progress, safety compliance, and adherence to regulatory requirements, shop drawings, and architectural specifications. These reports, commonly known as Field Observation Reports (FORs), play a crucial role in ensuring that construction activities align with project standards.

## The Challenge
FORs are created based on on-site observations to assess whether construction elements: 1) Exhibit deficiencies, 2) Are incomplete, and 3) Are blocked or otherwise unable to be judged.

Processing these reports manually in the course of or after the to identify non-compliance issues and generate punch lists is highly time-consuming and prone to human errors and biases. The sheer volume of text data further complicates this task, making automation a valuable solution.

## The ROle of NLP and ML
To streamline this process, Natural Language Processing (NLP) techniques are employed to extract meaningful information from unstructured text data. This repository demonstrates how various NLP techniques can effectively classify and filter text in construction reports to support compliance checks and punch list creation.

### Techniques Used

This project explores multiple NLP approaches, including vectorization methods such as TF-IDF (Term Frequency-Inverse Document Frequency), Word2Vec, GloVe (Global Vectors for Word Representation), and FastText. Transformer models like BERT (Bidirectional Encoder Representations from Transformers) and DistilBERT (a lightweight version of BERT) are also employed. Additionally, custom Named Entity Recognition (NER) models are used to detect key entities such as building elements, materials, deficiencies, and safety issues. Rule-based programming complements these methods by leveraging predefined rules to enhance text filtering and ensure comprehensive coverage of construction-specific terminology.

## Impact

By combining ML-based text processing with NER and rule-based programming, this repository aims to transform unstructured FOR text data into structured, queryable databases, enable rapid identification of non-compliance issues and punch list generation, reduce manual processing time by hundreds of hours, and improve project tracking, quality assurance, and overall efficiency. This approach empowers Project Managers (PMs) by providing actionable insights and improving decision-making, ultimately saving significant time and resources for construction firms.
