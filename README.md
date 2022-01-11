# CS539 Final Project

This project is designed and implemented for CS539 Machine Leaning Final Project.
This project mainly focus on Image-Text Alignment.

## Workflow

1. Proposal: Intro/Related Work/Datasets/Proposal/Reference

	Ruoxue: Intro/Related Work
	Kai: Datasets/Proposal
	others: review/edit
	first-edit:10.10
	
2. Research paper Pre:
	Slides - Yang
	others: reading
	
3. Website:
	Zihao Zhou
	
4. Code
5. final_pre&paper

# Use the Code

## Environment Setup

```bash
# Activate pipenv environment
pipenv shell

# Setup environment
pipenv install
```

## Data Preparation

You should run data generation script first:

```bash
python evaluation/run_gen_data.py
```

We have included the annotation data in `datasets/info/captions_train2014.json`, the above script will read annotation data and output image-text tuples and the binary classification labels.

## Model Training

```bash
python evaluation/run_training.py
```
