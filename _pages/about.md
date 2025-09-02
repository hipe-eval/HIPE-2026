---
title: HIPE-2026 Shared Task
permalink: about
---

### HIPE-2026: Evaluating Accurate and Efficient Person–Place Relation Extraction

Following the successful evaluation labs in 2020 and 2022 on named entity processing, the third edition of the HIPE shared task will focus on **Person-Place Relation Mining in Historical Documents**.

The central question of HIPE-2026 is: **Who was where when?** Participants will develop systems to extract person-place relations from multilingual historical newspapers, a crucial step for building historical knowledge graphs, reconstructing biographies, and enabling new forms of spatial analysis.

### The Task

The task is framed as a three-way relation classification. For a given person and place in a document, systems must determine if a relation holds by assigning one of three labels: `true`, `probable`, or `false`. Two distinct relation types will be evaluated:

- **`wasAt`**: Denotes whether the person was ever at the place at any time before the document's publication.
- **`isAt`**: Denotes whether the person is at the place in the immediate context of the publication date.

### Evaluation Profiles

Recognizing the growing importance of computational costs, HIPE-2026 will feature two evaluation profiles:

1.  **Accuracy Profile**: Rewarding the highest-performing systems to push the state-of-the-art.
2.  **Efficiency Profile**: Promoting lightweight and scalable methods by considering a trade-off between accuracy, model size, and compute resources.

A surprise dataset from a different domain will be used to evaluate how well systems generalize.

### Registration and Information

More information on the schedule and registration will be available soon. For questions, please contact the organizers via our mailing list (link to be provided).

---

### About the Previous Edition (HIPE-2022)

HIPE-2022 was based on diverse datasets and aimed at confronting systems with the challenges of dealing with more languages, learning domain-specific entities, and adapting to diverse annotation tag sets.

The main **challenges** of the HIPE-2022 edition were:

- Multilingual corpora from different countries: English, German (AU,DE,CH), French (CH,FR), Finnish, Swedish
- Different document types (historical newspapers and classic commentaries)
- Noisy OCR
- Partial coverage of KBs with respect to historical entities
- Different annotation tagsets

### Registration and Mailing list

Please mail to our [HIPE 2026 mailing list](https://groups.google.com/g/hipe-2026) for any questions.
