## Overview
This project explores Agentic Search techniques using the Tavily API and compares them to Regular Search using DuckDuckGo. It demonstrates intelligent querying, web scraping, and data extraction for real-world tasks such as weather forecasting and tech news retrieval.

## Project Structure
bash
Copy code
📁 SearchSmart/
│
├── Lesson_3_Student-Copy1.ipynb    # Jupyter Notebook with all code and output
├── .env                            # Stores the API key securely (not uploaded)
├── README.md                       # Project documentation
## Technologies Used
Python 3.x

Tavily API for Agentic Search

DuckDuckGo Search API (duckduckgo_search)

requests, BeautifulSoup for web scraping

dotenv for secure environment variable management

pygments and json for pretty output formatting

## Features
✅ Compare Agentic vs Regular search behavior

✅ Handle rate-limiting and fallback strategies

✅ Scrape weather data dynamically from the web

✅ Extract and clean structured data using NLP techniques

✅ Visualize and highlight JSON responses

## Setup Instructions
Clone the repository:

bash
Copy code
git clone https://github.com/your-username/SearchSmart.git
cd SearchSmart
Create and activate a virtual environment (optional but recommended):

bash
Copy code
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
Install dependencies:

bash
Copy code
pip install -r requirements.txt
Add your Tavily API key in a .env file:

ini
Copy code
TAVILY_API_KEY=your_api_key_here
Run the Jupyter Notebook:

bash
Copy code
jupyter notebook
## Example Use Case
Query:
"What is in Nvidia's new Blackwell GPU?"

Agentic Search Result:
Direct, precise response pulled using Tavily’s intelligent query system.

Regular Search Result:
Requires web scraping and manual extraction from multiple sources.
## OUTPUT:
<img width="1844" height="790" alt="image" src="https://github.com/user-attachments/assets/f40979fe-5aa3-4168-b869-8db89de29da1" />


## Future Improvements
Integrate OpenAI or Claude for answer summarization

Add visualization for search performance comparison

Create a Streamlit-based front-end interface
## Contributors
Your Name – Project Lead

📜 License
This project is licensed under the MIT License – see the LICENSE file for details.
