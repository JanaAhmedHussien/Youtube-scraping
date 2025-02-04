# YouTube Scraper: Low Carb Kitchen Analysis

## Description
This project implements a YouTube scraper to search for videos related to "low carb kitchen" using the SERP API. The scraper extracts video details, analyzes channel appearances, and crawls metadata for specific videos.

---

## Features
1. **YouTube Search with SERP API**:
   - Apply the query "low carb kitchen" to YouTube's search engine.
   - Retrieve results efficiently.

2. **Data Extraction**:
   - Extract video titles and their respective channels from the search results.

3. **Data Analysis**:
   - Analyze the frequency of the channel of the top result.
   - Provide insights into video/channel relationships.

4. **Crawling Metadata**:
   - Crawl the page of the second video in the search results.
   - Extract and analyze meta content, including the `og:image`.
   - Save the associated image locally.

---

## Prerequisites
- **Python** (version 3.8+)
- Installed Python Libraries:
  - `serpapi`
  - `beautifulsoup4`
  - `requests`

Install dependencies:
```bash
pip install serpapi beautifulsoup4 requests
