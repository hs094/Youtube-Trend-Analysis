# YouTube Trend Analysis with CrewAI and BrightData
This project implements a YouTube Trend Analysis with CrewAI and BrightData.
- BrightData is used to scrape YouTube videos.
- CrewAI is used to analyze the transcripts of the videos and generate a summary.
- Streamlit is used to create a web interface for the project.

---
## Setup and installations
**Get BrightData API Key**:
- Go to [BrightData](https://brightdata.com/) and sign up for an account.
- Once you have an account, go to the API Key page and copy your API key.
- Paste your API key by creating a `.env` file as follows:

```
BRIGHT_DATA_API_KEY=your_api_key
GROQ_API_KEY=your_api_key
```

**Install Dependencies**:
   Ensure you have Python 3.11 or later installed.
   ```bash
   pip install streamlit ollama crewai crewai-tools
   ```
---

## Run the project

Finally, run the project by running the following command:

```bash
streamlit run app.py
```
