# PDF Finder App with LLM Integration

This project aims to create a PDF finder application that leverages Large Language Models (LLMs) to crawl the web, find relevant PDF links, and extract information based on user queries.

## Overview

The PDF Finder App allows users to search for books, articles, research papers, documentation, and other PDF resources by typing queries into a search box. The system then crawls the web, identifies relevant PDF links, and presents them to the user along with extracted information.

## Key Features

- Web crawling for PDF discovery
- LLM-powered information extraction
- User-friendly search interface
- Link aggregation and presentation

## Architecture

1. **User Interface**: A simple search box for query input
2. **Web Crawler**: Searches the internet for relevant PDF links
3. **LLM Integration**: Processes and analyzes the content of found PDFs
4. **Vector Database**: Stores embeddings for efficient similarity search
5. **Results Presentation**: Displays found PDFs and extracted information

## Implementation Steps

1. **Web Crawling**:
   - Utilize libraries like BeautifulSoup and requests to crawl websites[3][4].
   - Implement a function to identify PDF links on web pages[4].

2. **PDF Processing**:
   - Use libraries such as PyPDF2 or PDFMiner to extract text from PDFs[7].
   - Implement text chunking for efficient processing[1].

3. **LLM Integration**:
   - Utilize open-source LLMs or cloud-based solutions like OpenAI's GPT[5].
   - Use LangChain or LlamaIndex for building the RAG (Retrieval-Augmented Generation) system[9].

4. **Vector Database**:
   - Implement a vector store using solutions like ChromaDB or MongoDB Atlas Vector Search[1][2].
   - Store embeddings of PDF content for similarity search.

5. **Search Functionality**:
   - Develop a search algorithm using vector similarity[2].
   - Implement relevance ranking for search results.

6. **User Interface**:
   - Create a web interface using frameworks like Flask or FastAPI[2].
   - Design a simple, intuitive search box and results display.

## Todo List

1. [ ] Set up the development environment and install necessary libraries
2. [ ] Implement web crawling functionality to discover PDF links
3. [ ] Develop PDF text extraction and processing module
4. [ ] Integrate an open-source LLM for content analysis
5. [ ] Set up a vector database for storing PDF embeddings
6. [ ] Implement the search algorithm using vector similarity
7. [ ] Create a basic web interface for user interaction
8. [ ] Develop the backend API to handle user queries
9. [ ] Implement result ranking and presentation logic
10. [ ] Test the system with various types of queries and PDFs
11. [ ] Optimize performance and handle edge cases
12. [ ] Document the code and create user guidelines
13. [ ] Deploy the application to a suitable hosting platform

## Getting Started

(Include instructions for setting up the project, installing dependencies, and running the application locally.)

## Contributing

(Add guidelines for contributing to the project, if applicable.)

## License

(Specify the license under which the project is released.)

---

This README provides a high-level overview of the PDF Finder App project. As development progresses, update this document with more detailed information, installation instructions, and usage guidelines.

Citations:
[1] https://www.youtube.com/watch?v=rIV1EseKwU4
[2] https://www.mongodb.com/solutions/solutions-library/pdf-search-with-vector-search-and-llm
[3] https://www.reddit.com/r/webscraping/comments/16nqvoo/how_can_i_crawl_a_website_including_its_pdfs_and/
[4] https://www.geeksforgeeks.org/how-to-scrape-all-pdf-files-in-a-website/
[5] https://www.shakudo.io/blog/build-pdf-bot-open-source-llms
[6] https://www.youtube.com/watch?v=AHbM2wCyd8s
[7] https://data-ox.com/scraping-and-downloading-pdf-files-python
[8] https://medium.com/@hopsworks_ai/build-your-own-private-pdf-search-tool-3d3d0fa333c0
[9] https://scrapfly.io/blog/how-to-use-web-scaping-for-rag-applications/
[10] https://www.youtube.com/watch?v=zxo3T4aQj6Q
