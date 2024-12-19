# Agentic-InsightEdge-Intelligent-Chatbot

AGENTIC is an AI-powered chatbot that processes user queries and provides the most effective response format, whether through detailed text, engaging visuals, or helpful video tutorials.  

## Features  

- **Wikipedia Integration**: Delivers accurate text-based explanations for various topics.  
- **DALL·E 3 Image Generator**: Creates stunning visuals to explain complex concepts.  
- **YouTube Search Tool**: Finds relevant video tutorials for deeper insights.  
- **LangChain Integration**: Utilizes LangChain agents and tools for intelligent query handling.  
- **Customizable Execution Pipeline**: Dynamically identifies the best medium (text, image, or video) based on the user's query.  
- **Streamlit Interface**: Provides an interactive and user-friendly platform.  

## How It Works  

AGENTIC evaluates the user’s query and selects the most effective medium to respond:  

1. **Text**: Uses Wikipedia for detailed explanations.  
2. **Image**: Generates visuals with DALL·E 3.  
3. **Video**: Searches YouTube for relevant video tutorials.  

### Workflow  

1. User enters a query in the Streamlit UI.  
2. AGENTIC analyzes the query and determines the optimal response format.  
3. The result is displayed as text, an image, or a video, depending on the content.

## Technologies Used
Python: Core programming language.
LangChain: For tool and agent integration.
Streamlit: For building the user interface.
Wikipedia API: For fetching text-based information.
DALL·E 3: For generating images.
YouTube Search API: For finding relevant videos.

## Installation  

1. Clone this repository:  
   ```bash
   git clone https://github.com/your-username/agentic-chatbot.git
   cd agentic-chatbot
