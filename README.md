# LLMs-for-design-of-alkali-activated-concrete-formulations

This repository can be used to run the experiments conducted in the paper 'LLMs-for-design-of-alkali-activated-concrete-formulations'

## About The Project

## Getting Started

### Setup - macOS


#### Create Python Environment 

```
python -m venv experiments/notebooks/venv
```

#### Activate Python Environment

```
source experiments/notebooks/venv/bin/activate
```

#### Install Dependencies 

```
pip install -r experiments/notebooks/requirements.txt
```

#### Specify Environment Variables

In order to utilize GPT-3.5 or GPT-4, an OpenAI API Key is required. Create a `.env` file in `LLMs-for-design-of-alkali-activated-concrete-formulations/experiments/notebooks` and specify your OpenAI API Key

```
OPENAI_API_KEY={YOUR_OPENAI_API_KEY}
```

#### Start Jupyter Notebook

```
jupyter notebook experiments/notebooks/main.ipynb
```

### Configure And Run Experiments

To run the experiments, execute each cell consecutively. 

Specify the details of the experiments you would like to run

![image](https://github.com/sandrocan/LLMs-for-design-of-alkali-activated-concrete-formulations/assets/53880336/0a5d5c62-0269-42fe-86a4-e9e78a9571cc)

Get an overview of the prompt utilized for the experiments. You may edit the contents of the prompts directly inside the textfield. All available prompts are located in `LLMs-for-design-of-alkali-activated-concrete-formulations/experiments/prompts` and can be permanently edited there.

![image](https://github.com/sandrocan/LLMs-for-design-of-alkali-activated-concrete-formulations/assets/53880336/a9d39a15-282c-4c52-a618-02641db27015)

Get a short overview of the configured experiments

![image](https://github.com/sandrocan/LLMs-for-design-of-alkali-activated-concrete-formulations/assets/53880336/ef0ce7f6-8830-40bb-a4e4-8dac00369740)

Run the experiments






