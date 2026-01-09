# CORD19 Search Engine

A Data Structures & Algorithms (DSA) project implementing a Search Engine for the **CORD-19** dataset (COVID-19 Open Research Dataset) using Python.

---

## Project Overview

The goal of this project was to build a search engine tailored for the CORD-19 dataset — a large collection of scientific research papers on COVID-19. The search engine allows efficient querying over this dataset by preprocessing, indexing, and searching through the scientific articles.

---

## Dataset

We selected the **CORD-19 dataset**, which is publicly available and contains thousands of research papers related to COVID-19, SARS-CoV-2, and related coronaviruses.

---

## Project Workflow and Sequence

The project was developed following this sequence:

1. **Dataset Collection:**  
   Obtained the raw CORD-19 dataset files and organized them in the `batch_content/` folder.

2. **Data Preprocessing:**  
   Cleaned and processed the raw data to extract relevant text fields, remove noise, and prepare it for indexing. The processed results were stored in the `processed_data/` folder.

3. **Indexing:**  
   Implemented data structures and algorithms to create an index for quick retrieval of documents based on user queries.

4. **Search Implementation:**  
   Developed the search functionality that leverages the index to return relevant documents based on keyword queries.

5. **Testing & Validation:**  
   Tested the search engine with various queries to validate accuracy and performance.

---



## Setup Instructions

1. **Clone the repository**

```bash
git clone https://github.com/abdullah6093/CORD19__SearchEngine.git
cd CORD19__SearchEngine/main
Download Dataset and Processed Data

Download the batch_content and processed_data folders from the following Google Drive link:

[Insert actual Google Drive link here]

Replace folders

Copy and replace the existing batch_content and processed_data folders inside the main/ directory with the downloaded versions.

Run the Search Engine
run the main.py on console by this code: uvicorn main:app

Technologies Used
Python

Data Structures and Algorithms

Text Processing & Indexing

Future Work
Enhance search relevance and ranking

Implement advanced query features (phrase search, boolean queries)

Create a user-friendly web interface

Contact
For any questions or suggestions, please open an issue or contact me through GitHub.

GitHub Repository:
https://github.com/abdullah6093/CORD19__SearchEngine

