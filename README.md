# Real-Time MongoDB to Pinecone Vector Sync and Query with LangChain
## Overview

This project demonstrates a real-time pipeline that syncs data from MongoDB to Pinecone, performs vector embeddings, and allows for querying with natural language processing using LangChain and Google Generative AI.
## Project Structure 
- **Notebook 1: Load Documents, Upsert Vectors, and Query**  - This notebook loads data into MongoDB, creates vector embeddings, upserts them into Pinecone, and provides functionality to query Pinecone and generate responses using LangChain. 
- **Notebook 2: Real-Time Synchronization**  - This notebook sets up a real-time synchronization pipeline to keep Pinecone updated with changes in MongoDB.
## Notebooks 
1. **[Notebook 1: Load Documents, Upsert Vectors, and Query]** 
- Install necessary libraries.
- Connect to MongoDB and Pinecone.
- Load dataset, clean, and insert records into MongoDB.
- Create embeddings and upsert them into Pinecone.
- Define query functions to interact with Pinecone.
- Query Pinecone for similar vectors based on input queries.
- Retrieve detailed information from MongoDB.
- Use LangChain and Google Generative AI to generate responses based on retrieved information. 
2. **[Notebook 2: Real-Time Synchronization]** 
- Install necessary libraries.
- Connect to MongoDB and Pinecone.
- Initialize the embedding model.
- Set up a real-time data synchronization pipeline.
## Setup and Execution 
1. Clone the repository:

```bash
git clone https://github.com/imranajec/Real-Time-MongoDB-to-Pinecone-Vector-Sync-and-Query-with-LangChain.git
``` 
2. Navigate to the project directory:

```bash
cd Real-Time-MongoDB-to-Pinecone-Vector-Sync-and-Query-with-LangChain
``` 
3. Open the notebooks in Google Colab: 
- [Notebook 1: Load Documents, Upsert Vectors, and Query]() 
- [Notebook 2: Real-Time Synchronization]()
## Requirements

Ensure you have the following API keys and connection strings:
- MongoDB URI
- Pinecone API Key
- Google API Key for LangChain

Replace placeholders in the notebooks with your actual keys and connection strings.
## License

This project is licensed under the MIT License - see the [LICENSE]()  file for details.---
