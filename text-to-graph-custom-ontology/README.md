# Text to graph with a custom ontology

## Introduction

This is a simple example of how to use the Lettria API to import an ontology and use it to transform natural language to RDF triples.

## Pre-requisites

-   You need to have a Lettria account. If you don't have one, you can create one for free on our [website](https://lettria.com)
-   You need to have a Lettria Project. Help center article [here](https://help.lettria.com/create-and-manage-projects)
-   You need to have a Project API key. Help center article [here](https://help.lettria.com/api-key).
-   Your must replace the API key in the `jwt_token.txt` file with your own API key.

## Configuration

-   Edit the files inside the data folder to add your own ontology and text.

## Installation

```bash
pip install -r requirements.txt
```

## Usage

-   Run the notebook import_ontology.ipynb to import your ontology to Lettria.
-   Run the notebook document_to_graph.ipynb to transform your text to RDF triples.
