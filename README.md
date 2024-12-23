# Website-Summarizer-using-Ollama

This project provides a Python-based utility for summarizing the contents of a webpage using the Ollama API. The script uses requests to fetch web content, BeautifulSoup for parsing and cleaning, and integrates with Ollama's language model to generate concise, structured summaries.

## Features
1. Fetch and parse the contents of any publicly accessible webpage.
2. Remove irrelevant elements like navigation menus, scripts, styles, and images.
3. Generate structured summaries of website content using the Ollama API.
4. Display results in markdown format for better readability.

## Prerequisites
### Software Requirements
Python 3.8+

### The following Python libraries:
1. requests
2. beautifulsoup4
3. IPython

## API Requirements
Ollama API: The script requires the Ollama API to be running locally.
Default endpoint: http://localhost:11434/api/chat

## Installation
### Clone the repository:
git clone https://github.com/yourusername/website-summarizer.git
cd website-summarizer

### Install the required Python libraries:
pip install requests beautifulsoup4 ipython

## Usage:
### 1. Run the Script
#### Modify and run the script in your Python environment:
from summarizer import display_summary
display_summary("https://example.com")

