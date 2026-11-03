# 🧬 ANN Fundamentals

This repository handles classical machine learning configurations, sequence training loops, and generative framework architectures. Dependency states are explicitly locked and synchronized using `uv`.

---

## 🚀 Getting Started & Local Execution

Follow these precise steps to sync the production-ready dependencies and run the execution script directly on your local system layout.

### 1. Install `uv`
If you haven't installed Astral's packet engine yet, initialize it globally:

```bash
# macOS/Linux
curl -LsSf https://astral.sh | sh

# Windows (PowerShell)
powershell -c "irm https://astral.sh | iex"
```

### 2. Clone the Repository
Pull down the project code layout and step straight into the root working directory matrix:

```bash
# Clone the project code node from GitHub
git clone https://github.com/monisma/deeplearning_fundamentals/tree/main/01_backpropogation

# Enter the root directory folder
cd 01_backpropogation
```


### 2. Synchronize Your Local Environment
Instead of running manual installer strings, run the synchronization command. This reads the repository's configuration footprint (`pyproject.toml` or `uv.lock`) and safely replicates the exact workspace state inside an isolated environment structure:

```bash
uv sync
```

### 3. Run the Execution File
Execute the specific runtime script using the locked configuration framework:

```bash
uv run python network.py
```
*(Note: Replace `execution_file.py` with the actual name of your entrypoint script, such as `train_lstm.py` or `app.py`).*

---

## 🛠️ Modifying the Dependency Topology

If you need to add, subtract, or edit packages across this pipeline configuration safely:

```bash
# Add new packages to the project manifest file
uv add pandas scikit-learn langchain

# Pull modifications into your active virtual environment context
uv sync
```

---

## 📊 Environment Diagnostic Code
```text
// Synchronization Status  : Converged Successfully [UV Managed]
// Environment State Layer : Virtual Environment Activated
// Runtime State Mapping   : System ready for calculation vectors.
```
