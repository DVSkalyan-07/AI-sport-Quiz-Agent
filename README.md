# AI-Powered Sports Quiz Generation Agent

An interactive Streamlit application leveraging Hybrid RAG (ChromaDB Vector Store + Dynamic Live Web Search via DuckDuckGo) to generate grounded, contextually accurate multiple-choice quizzes.

## Architecture Highlights
- **Vector Base:** ChromaDB chunks and manages offline historical dataset facts contextually.
- **Live Extension:** Automated search API updates live dynamic events context dynamically.
- **LLM Grounding:** Strictly bound constraints target deterministic execution models preventing structural text hallucination.

## Setup Instructions

1. **Clone and Navigate into Workspace:**
   ```bash
   git clone <your-repository-url>
   cd sports-quiz-agent
