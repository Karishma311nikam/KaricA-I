# KaricA-I 
  A sophisticated, conversational AI agent built with Python and LangChain that autonomously researches complex queries. This agent leverages the power of large language models to understand user intent, select appropriate tools, gather information from multiple sources, and return a structured, reliable response.

**Key Features**
Dynamic Tool Use: Intelligently selects the best tool for the job, whether it's performing a real-time web search or querying a structured knowledge base.

Multi-Source Data Aggregation: Gathers information from the web (DuckDuckGo) and encyclopedic sources (Wikipedia) to provide comprehensive answers.

Structured & Validated Output: Utilizes Pydantic to ensure the final output is always in a clean, predictable, and validated format, making it reliable for downstream tasks.

Extensible Architecture: Easily add new custom tools to the agent's arsenal to expand its capabilities.

Persistent Storage: Includes a custom tool to save research findings directly to a local text file for logging and review.


**Example Output**
Here is an example of the agent researching the history of the Python programming language. The agent first uses a web search, then consults Wikipedia, and finally formats the data into a structured object.

<img width="1868" height="991" alt="image" src="https://github.com/user-attachments/assets/166aa4f0-3460-4dc2-a919-72cc16663116" />
<img width="1844" height="991" alt="image" src="https://github.com/user-attachments/assets/65de353d-2c1c-4277-af8c-9182a8d8278b" />
<img width="1870" height="1018" alt="image" src="https://github.com/user-attachments/assets/cf3f51bf-83fe-4ed2-b5eb-d612dcb1979e" />
<img width="1891" height="1038" alt="image" src="https://github.com/user-attachments/assets/223d947f-a23b-47eb-81b7-75e26658df2f" />
<img width="1870" height="985" alt="image" src="https://github.com/user-attachments/assets/7c3f8806-9210-43f9-816d-1b3f7b8b9821" />
<img width="1834" height="975" alt="image" src="https://github.com/user-attachments/assets/6348c3bc-1f92-477e-b11a-5915360a9ed3" />


**Technologies Used**
Core Framework: LangChain

Language: Python

LLM: Anthropic Claude 3.5 Sonnet

Data Validation: Pydantic

Tools: DuckDuckGo Search, Wikipedia API, Custom File I/O








