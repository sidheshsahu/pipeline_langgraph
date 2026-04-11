# LangGraph Practice

This repository is my practice space for learning **LangGraph** by building small notebook-based workflows.

The goal here is not to create a production-ready project. It is mainly for understanding how LangGraph works step by step through simple examples, experiments, and iterative improvements.

## What I Am Practicing

This repo includes hands-on practice with:

- Sequential workflows
- Conditional routing
- Parallel execution
- Iterative refinement loops
- Database-oriented agent flows
- State management inside LangGraph
- LLM integration using `langchain` and `langchain-groq`

## Project Files

- `sequential.ipynb`  
  Practice with a basic step-by-step LangGraph flow.

- `conditional.ipynb`  
  Practice with branching logic and conditional edges.

- `parallel.ipynb`  
  Practice with parallel paths and tool-based execution.

- `iteration.ipynb`  
  Practice with loop-based refinement, such as improving text across multiple iterations.

- `db_agent.ipynb`  
  Practice with a database-related agent workflow.

- `house_price.csv`  
  Sample dataset used for database or agent experiments.

- `house_prices.db`  
  SQLite database file used in the database practice notebook.

## Tech Stack

- Python 3.11+
- LangGraph
- LangChain
- LangChain Groq
- SQLAlchemy
- Pandas
- Jupyter Notebook / IPython Kernel

## Setup

Install dependencies using `uv`:

```bash
uv sync
```

If you are using Jupyter, make sure the notebook kernel is available:

```bash
uv run python -m ipykernel install --user --name pipeline-langgraph
```

## Environment Variables

Create a `.env` file and add the API keys you need. For example:

```env
GROQ_API_KEY=your_api_key_here
```

Some notebooks may require additional environment variables depending on the tools or services being tested.

## How To Run

Start Jupyter:

```bash
uv run jupyter notebook
```

Then open any notebook and run the cells one by one while practicing the LangGraph concepts.

## Notes

- This is a learning repo, so the code may change often.
- Some notebooks are intentionally simple because they are focused on understanding one concept at a time.
- Outputs may vary depending on the model and API responses.

## Learning Focus

I am using this repository to get comfortable with:

- How nodes and edges work in LangGraph
- How state is passed and updated
- How to build small agent workflows
- How to debug graph behavior
- How different execution patterns behave in practice

## Future Practice Ideas

- Add memory-based workflows
- Try human-in-the-loop patterns
- Build a multi-agent example
- Add better visualization for graph execution
- Compare different prompting styles across notebooks
