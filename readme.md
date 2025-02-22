# 🚀 TechSpark LLM Novice Workspace

## 📌 Clone the Repository

To get started, clone this repository to your local machine:

```sh
git clone git@github.com:TechSparkWorkspace/tspark-llm-novice-workspace.git
cd tspark-llm-novice-workspace
```

## 📦 Install Conda (If Not Installed)

Make sure you have **Miniconda** or **Anaconda** installed. If not, download and install:

- [Miniconda](https://docs.conda.io/en/latest/miniconda.html) (lightweight version)
- [Anaconda](https://www.anaconda.com/) (comes with pre-installed packages)

Verify installation:

```sh
conda --version
```

## 🏗️ Create and Activate the Conda Environment

Create a virtual environment to keep dependencies organized:

```sh
conda create -n tspark_llm_workspace python=3.10
```

Activate the environment:

```sh
conda activate tspark_llm_workspace
```

## 📚 Install Dependencies

Run the following command to install required libraries:

```sh
conda install numpy pandas matplotlib scikit-learn
pip install torch torchvision torchaudio transformers datasets jupyterlab
```

## 📝 Launch Jupyter Notebook

Start Jupyter Notebook or Jupyter Lab to work with your notebooks:

```sh
jupyter lab
```

This will open Jupyter Lab in your browser, where you can navigate and run the notebooks in this repository. 🚀

## 🔄 Deactivating the Environment

When you’re done, you can deactivate the Conda environment:

```sh
conda deactivate
```

## 🎯 Next Steps

- Modify and run existing notebooks in the repo.
- Experiment with different LLM models.
- Push your changes to GitHub with:
  ```sh
  git add .
  git commit -m "Updated notebooks"
  git push origin main
  ```

Enjoy your AI development journey! 🚀
