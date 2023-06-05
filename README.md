# Sinhala Web Scraping and Translation

This repository contains code for the automation of web scraping and translation project focused on Sinhala content. The project aims to scrape Sinhala web pages, extract textual content, and translate it to English using Google Translate.

## Features

- Scrapes content from multiple Sinhala news websites
- Extracts unique links from each page
- Tokenizes the Sinhala text into sentences
- Translates the Sinhala sentences into a target language using Google Translate API
- Creates a parallel corpus of Sinhala and translated sentences
- Schedules the script to run periodically (every 24-28 hours)

## Installation

1. Clone the repository:
   ```bash
   [   git clone https://github.com/your-username/sinhala-web-scraping-translator.git
   ](https://github.com/SivaAdeesh27/Sinhala-Corpus-Translation.git)   
2. Install the required dependencies:
    ```bash
   pip install -r requirements.txt
   
## Usage

1. Modify the `main_urls` and `output_files` lists as needed.
2. Change the target language for translation in the `translate_parallel_corpus` function call (currently set to `'en'` for English).
3. Run the script once, and it will keep updating the parallel corpus on the specified schedule.










