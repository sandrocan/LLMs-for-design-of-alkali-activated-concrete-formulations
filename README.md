# LLMs for Materials and Chemistry Hackathon - llama3 For The Design of Alkali-Activated-Concrete Formulations

![concrete-llama](https://github.com/sandrocan/LLMs-for-design-of-alkali-activated-concrete-formulations/assets/53880336/d69120ef-f7c3-4227-93aa-e6c7992ed552)

## About The Project

This is the repository containing the submission made by the Llama 3 Material Scientist Team for the LLMs for Materials and Chemistry Hackathon. We demonstrated that small open-source models such as Llama3 8B 🐑, which can run on consumer laptops, can be used for designing eco-friendly and high-performing building materials. This breakthrough opens up the possibility of designing new materials in natural language from the comfort of your home 🏠.

## Getting Started

### Setup

#### Create Python Environment 

```
python -m venv experiments/notebooks/venv
```

#### Activate Python Environment

```
source experiments/notebooks/venv/bin/activate
```

#### Install Project Dependencies 

```
pip install -r experiments/notebooks/requirements.txt
```

#### Install ollama

[ollama](https://github.com/ollama/ollama)

#### Run llama3 using ollama

```
ollama run llama3:8b
```

#### Specify Environment Variables

Create a `.env` file in `LLMs-for-design-of-alkali-activated-concrete-formulations/experiments/notebooks` and specify the URL over which the llama3 model is available. When running ollama locally, the URL is usually `http://localhost:11434/v1`

```
LLAMA3_SERVER_URL="http://localhost:11434/v1"
```

Iif you want to utilize GPT-3.5 or GPT-4, an OpenAI API Key is required. Specify your OpenAI API Key in your `.env` file

```
OPENAI_API_KEY={YOUR_OPENAI_API_KEY}
```

### Start Jupyter Notebook

```
jupyter notebook experiments/notebooks/main.ipynb
```

### Configure And Run Experiments

To run the experiments, execute each cell consecutively. 

1. Specify the details of the experiments you would like to run

![image](https://github.com/sandrocan/LLMs-for-design-of-alkali-activated-concrete-formulations/assets/53880336/0a5d5c62-0269-42fe-86a4-e9e78a9571cc)

2. Get an overview of the prompt utilized for the experiments. You may edit the contents of the prompts directly inside the textfield. All available prompts are located in `LLMs-for-design-of-alkali-activated-concrete-formulations/experiments/prompts` and can be permanently edited there.

![image](https://github.com/sandrocan/LLMs-for-design-of-alkali-activated-concrete-formulations/assets/53880336/a9d39a15-282c-4c52-a618-02641db27015)

4. Get a short overview of the configured experiments

![image](https://github.com/sandrocan/LLMs-for-design-of-alkali-activated-concrete-formulations/assets/53880336/ef0ce7f6-8830-40bb-a4e4-8dac00369740)

5. Run the experiments

![image](https://github.com/sandrocan/LLMs-for-design-of-alkali-activated-concrete-formulations/assets/53880336/ace0ea7b-a5e6-4bca-b063-c1c1d2c10d50)


## Validation Dataset And Experiment Data

The dataset used for validation is stored in `LLMs-for-design-of-alkali-activated-concrete-formulations/experiments/data/DiscoveryData_Sample.csv`. The data generated during each development cycle of an experiment is saved under `LLMs-for-design-of-alkali-activated-concrete-formulations/experiments/results`

## Contact

Dr. Tehseen Rug : tehseen.rug@iteratec.com

Dr. Christoph Völker : christoph.voelker@iteratec.com

Alexander Mooshammer : alexander.mosshammer@iteratec.com

Alessandro Canalicchio : alessandro.canalicchio@iteratec.com







