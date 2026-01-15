#  ReAct Agent with Hugging Face Transformers - No Frameworks, No paid APIs
### Tiziana Ligorio for *AI Agents (CSCI 395.32)* taught at Hunter College of The City University of New York
Build an agent that reasons step-by-step and uses tools to solve problems, from scratch (framework-free). Uses open-source models.

## Running Locally

### Prerequisites
- Python 3.12 or higher
- GPU recommended (but CPU works)

### Setup

#### Option 1: Using uv (Recommended)
```bash
# Clone the repository
git clone https://github.com/tligorio/hugging_react_agent_tutorial.git
cd hugging_react_agent_tutorial

# Create virtual environment and install dependencies
uv venv
source .venv/bin/activate  # On Windows: .venv\Scripts\activate
uv pip install -e .

# Start Jupyter
jupyter notebook hugging_ReAct_agent_Qwen2.5.ipynb
```

#### Option 2: Using pip
```bash
# Clone the repository
git clone https://github.com/tligorio/hugging_react_agent_tutorial.git
cd hugging_react_agent_tutorial

# Create virtual environment
python -m venv .venv
source .venv/bin/activate  # On Windows: .venv\Scripts\activate

# Install dependencies
pip install -r requirements.txt

# Start Jupyter
jupyter notebook hugging_ReAct_agent_Qwen2.5.ipynb
```

