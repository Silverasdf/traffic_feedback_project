# traffic_feedback_project

## Setup

In order to run this project, you will need to have the following installed:

- Conda
- ollama (to run the LLM locally)

Check out the [conda installation instructions](https://docs.conda.io/projects/conda/en/latest/user-guide/install/index.html) for your operating system.
Check out the [ollama installation instructions](https://ollama.com/docs/installation) for your operating system.

When this is done, you can run the following commands to set up the project:

```bash
git clone https://github.com/Silverasdf/traffic_feedback_project.git
cd traffic_feedback_project
conda env create -f environment.yml
conda activate trafficfeedback
```

In order to use the LLM locally, you will need to download the model. You can do this by running the following command:

```bash
ollama run llama3.2
```

Then type

```bash
/bye
```

And do the same for the embedding model:

```bash
ollama run mxbai-embed-large
```

Make sure the model is downloaded successfully, and ollama is running on port 11434. You can do this by running the following command:

```bash
curl http://localhost:11434/v1/models
```

If this doesn't work for you, try running the following command:

```bash
ollama serve
```

and then run the curl command again.

## Running the project

You can run the cells in ollama_test.ipynb to test the LLM locally. Make sure you have the data downloaded and inside the repo. You can see, check, and download the data folder
[here](https://www.dropbox.com/scl/fo/jjf5t4bxwqx4p11vxhbdi/AO_swR_w6P4AqD3wZSF7Cgg?rlkey=bpmvlqh1utsw3tahyb61hjf13&e=1&dl=0). ONLY DRAG THE DATA PART INTO THIS REPO.

If you run the cells in ollama_test.ipynb, you should be able to run the rest of the project. Please email me [here](mailto:yhg461) with any questions.

## Authors and Acknowledgements

Research Project work done by Ryan Peruski, a student at the University of Tennessee Knoxville, under the supervision of Dr. Charles Cao and Dr. Yangsong Gu.
