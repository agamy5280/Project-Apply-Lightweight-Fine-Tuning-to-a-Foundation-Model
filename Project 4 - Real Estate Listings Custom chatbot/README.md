## Project Overview

The HomeMatch application is designed to personalize the real estate search experience for users by matching properties based on individual preferences. The project leverages synthetic data, vector databases, and LLMs to create a seamless, user-tailored process for discovering real estate listings.

## Generating Property Data

The application uses a Large Language Model (LLM) to generate a variety of realistic real estate listings. These listings cover a range of prices, locations, and property types, ensuring diverse options that cater to different buyer preferences. Each listing includes detailed descriptions of the property and its surrounding neighborhood.

## Building the Search Infrastructure

A vector database is utilized to store the property listings along with their embeddings, allowing for efficient and semantic searches. The database enables the system to match listings with specific buyer preferences, such as desired price ranges, neighborhood qualities, and property features.

## Customizing Property Descriptions

Once the system retrieves potential matches, the LLM personalizes each listing’s description. This tailored approach highlights features that are particularly relevant to the buyer, ensuring that each property is presented in a way that aligns with the buyer’s preferences and needs.

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
