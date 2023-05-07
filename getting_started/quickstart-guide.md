## Quickstart Guide

https://langchain.readthedocs.io/en/latest/getting_started/getting_started.html

This tutorial gives you a quick walkthrough about building an end-to-end language model application with LangChain.

## Installation

To get started, install LangChain with the following command:

```sh
pip install langchain
# or
conda install langchain -c conda-forge
```

## Environment Setup

Using LangChain will usually require integrations with one or more model providers, data stores, apis, etc.

For this example, we will be using OpenAI’s APIs, so we will first need to install their SDK:

```sh
pip install openai
```

We will then need to set the environment variable in the terminal.

```sh
export OPENAI_API_KEY="..."
```

Alternatively, you could do this from inside the Jupyter notebook (or Python script):

```python
import os
os.environ["OPENAI_API_KEY"] = "..."
pip install openai
```
