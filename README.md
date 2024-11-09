# Finance-RAG-Challenge

This repository contains code and data for the Finance-RAG-Challenge, a project focused on optimizing retrieval-augmented generation (RAG) techniques for financial data tasks. The process involves multiple steps, including retrieval, hybrid search, and reranking, with evaluations on task-specific datasets. For more details, refer to `report.pdf`.

## Repository Structure

- **final/**: Contains result files intended for final submission.
- **eval/**: Holds evaluation datasets for validation purposes.
- **data/**: Stores data related to each task, including corpus and query files. Each task includes separate data for retrieval and rerank stages.
- **notebooks/**: Jupyter notebooks used to generate results for each task.

## Workflow

The overall process for this project follows three main steps:

1. **Retrieval**: Initial retrieval of relevant documents based on each task's queries.
2. **Hybrid Search**: Combines both sparse and dense retrieval methods to enhance relevance.
3. **Rerank**: Final reranking of retrieved results to maximize accuracy.

## Additional Information

For a detailed explanation of the methodology, data handling, and evaluation metrics, please refer to `report.pdf`.
