
# Agentic RAG using CrewAI

This project leverages CrewAI to build an Agentic RAG that can search through your docs and fallbacks to web search incase it don't find the answer in the docs, powered by a locally running Llama 3.2!


## Installation and setup

**Get API Keys**:
   - [FireCrawl](https://docs.firecrawl.dev/introduction)


**Install Dependencies**:
   Ensure you have Python 3.11 or later installed.
   ```bash
   pip install crewai crewai-tools chonkie[semantic] markitdown qdrant-client fastembed
   ```

**Running the app and Notebook**:

You can run the demo in ```demo_llama3.2.ipynb``` and app in ```app_llama3.2.py``` using command ``` streamlit run app_llama3.2.py ```


---

## Contribution

Contributions are welcome! Please fork the repository and submit a pull request with your improvements.
