# Autonomous AI Assistant

It is an autonomous web research assistant that continuously searches for and extracts relevant information from the internet using multiple APIs and advanced AI models. Unlike traditional search engines, it performs iterative and structured research, ensuring that users receive **comprehensive, multi-source, and AI-processed results**.

## Features

### Multi-Source Aggregation

* Integrates multiple search APIs: **Google (SERPAPI), Bing, DuckDuckGo** for diversified results
* Uses **semantic search techniques** to retrieve contextually relevant documents

### AI-Driven Query Expansion & Filtering

* Leverages **GPT-4/Mixtral** to generate optimized search queries
* Uses an AI-based **credibility ranking system** for filtering low-quality sources
* Applies **graph-based modeling** to track relationships between different sources

### Parallel Processing

* **Batch processing** of search queries for improved performance
* **Async web scraping** with BeautifulSoup & Scrapy as a fallback
* **Streaming API support** for real-time results

### Summarization & Report Generation

* Uses **LLM-powered extractive & abstractive summarization**
* Generates structured research reports with key findings, insights, and citations
* Option to export reports in **Markdown, PDF, or JSON formats**

## How It Works

1. **Input Query:** The user enters a research topic
2. **AI Query Expansion:** The system generates multiple optimized search queries
3. **Multi-Source Search:** Queries are executed across different search engines
4. **Web Scraping & Context Extraction:** Relevant pages are fetched and summarized
5. **Iterative Refinement:** The AI decides whether additional searches are needed
6. **Final Report Generation:** A comprehensive report is compiled and delivered

## Tech Stack

* **Python (asyncio, aiohttp)** for parallel processing
* **GPT-4/Mixtral via OpenRouter API** for query optimization and summarization
* **SERPAPI, Bing, DuckDuckGo APIs** for multi-source search
* **FAISS/Weaviate** for AI-powered semantic search
* **Scrapy & BeautifulSoup** for web content extraction
* **Gradio/FastAPI** for UI & API access
