## Project Overview

The HomeMatch application personalizes the real estate search experience by matching properties to users based on individual preferences. The project utilizes synthetic data, vector databases, and Large Language Models (LLMs) to provide a highly personalized real estate discovery process, allowing users to find listings that best suit their needs.

## Generating Property Data

The application generates a variety of realistic real estate listings using a Large Language Model (LLM). These listings span different price ranges, locations, and property types, ensuring that diverse buyer preferences are met. Each listing includes detailed descriptions of both the property and its surrounding neighborhood.

## Building the Search Infrastructure

A vector database stores the property listings and their embeddings, enabling efficient semantic searches. The database allows the system to match listings based on specific buyer preferences, including price range, neighborhood characteristics, and property features.

## Customizing Property Descriptions

After retrieving relevant listings, the LLM further personalizes the descriptions of the top matching listings. The description is tailored to highlight features that align with the buyer’s preferences, ensuring the listing appeals directly to the user’s needs. The augmentation process ensures that descriptions are unique, engaging, and reflect the buyer's preferences without altering factual information.

## Prerequisites

Before running the notebook, you will need to install the required Python packages. You can do this by running the following commands in the first cell of your Jupyter Notebook:

### Uninstalling any existing versions of the required libraries

```bash
!pip uninstall -y langchain lancedb openai tiktoken pandas langchain-community langchain-core
```

### Installing the required libraries

```bash

!pip install langchain lancedb openai tiktoken pandas langchain-community langchain-core
```

## API Key Replacement

Replace the placeholder API key with your actual key in the notebook:

```bash
API_KEY = "YOUR API KEY"
```
