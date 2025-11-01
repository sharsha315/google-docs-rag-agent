# google-docs-rag-agent




## Building Steps

1. Installing uv, activating venv 
- 1.1 - Installing uv using,
    - link - `curl -LsSf https://astral.sh/uv/install.sh | sh`
    - pip - `pip install uv`

- 1.2 - Initialized a uv project
    - using `uv init` for existing project

- 1.3 - Created and activate venv
    - create using - `uv venv .venv`
    - activate using - `source .venv/bin/activate`

2. Install required libraries
    - llama-index - `uv add llama-index`

#### Merge and Commit to main