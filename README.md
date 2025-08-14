# Brochure Generator

This project automatically generates a short, well-structured brochure for any company by scraping its website, identifying relevant pages (e.g., About, Careers), and summarizing the content using the OpenAI API.  
It can display the brochure instantly in streaming mode, so you see it build in real time.

---

## Features
- **Web Scraping** – Fetches HTML from a given URL using `requests` and `BeautifulSoup`.
- **Noise Removal** – Strips out irrelevant HTML tags like `<script>`, `<style>`, `<img>`, `<input>`.
- **Link Extraction** – Identifies all anchor tags (`<a>`) and filters for relevant company pages.
- **Intelligent Link Selection** – Uses an OpenAI prompt to decide which links (About, Careers, etc.) should be included.
- **Content Aggregation** – Retrieves page content from relevant links.
- **Brochure Generation** – Uses OpenAI's GPT model to create a concise, markdown-formatted brochure.
- **Streaming Output** – Option to see the brochure generated live, token-by-token.

---

