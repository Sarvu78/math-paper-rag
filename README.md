# Math-RAG: Interactive Research Paper Analysis
Navigating mathematics research papers often leads to a "citation rabbit hole." When a proof relies on a specific Lemma or Theorem from a cited work, researchers must manually find, download, and search through external papers—a process that breaks cognitive flow.

Math-RAG is an intelligent Retrieval-Augmented Generation solution designed to make the citation network interactive. By indexing both the primary paper and its references, it provides immediate access to the technical details you need, exactly when you need them.

## Instructions to Use:
In the python notebook to the following changes:
Change the EMAIL variable to your email.
Change the PROJECT_DIR variable to the desired directory. 
QUERY variable to the query you want to ask. 
Change the TITLE variable to title of the paper. 
Change the PDF_PATH variable to path of the pdf. If you do not have the pdf set it to None. 

Providing the pdf file is highly recommended if it is not readily available as we rely on only open source providers.

Create a .env file with 
GOOGLE_API_KEY = "your gemini api key here"

## Future Work
Implement hierarchial retrieval logic, develop a more robust title extraction, implement rerankers, develop a front-end.
