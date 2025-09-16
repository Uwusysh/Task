
# Conversation Management & JSON Extraction Project

This project demonstrates managing conversation history with summarization and structured information extraction using the OpenAI-compatible Groq API.

## Overview

The project contains two main tasks:

### Task 1: Conversation History Management & Summarization

* Maintain a running history of user–assistant chats.
* Summarize conversation history to keep it concise.
* Supports **custom truncation options**:

  * Limit by number of conversation turns.
  * Limit by character or word length.
* **Periodic summarization**:

  * Summarizes conversation after every `k`-th run.
  * Stores or replaces the summarized version in the history.
* Demonstrates functionality with multiple conversation samples.

### Task 2: JSON Schema Classification & Information Extraction

* Extract structured details from chats:

  * `name`, `email`, `phone`, `location`, `age`
* Uses OpenAI function calling via **Groq API** for structured outputs.
* Demonstrates:

  * Parsing of sample chats.
  * Validation of outputs against the schema.

## Features

* Pure Python implementation (no frameworks).
* Uses Groq API OpenAI-compatible SDK.
* Clean, well-documented code.
* Output demonstrations for each feature.

## Project Structure

* **Google Colab Notebook:** [View Notebook](https://colab.research.google.com/drive/1Qp82MmNwlOl8HdBcfoyXDVWLAqeNOML7?usp=sharing)
* All code for conversation management, summarization, and JSON extraction is contained within the notebook.

## Usage

1. Open the Colab notebook.
2. Insert your **Groq API key** where indicated.
3. Run each cell sequentially:

   * Test conversation history management and truncation.
   * Observe periodic summarization after every `k`-th run.
   * Test JSON schema extraction with sample chats.
4. Review outputs for validation and correctness.

## Requirements

* Python 3
* `requests` library
* Groq API key (OpenAI-compatible)
* No additional frameworks needed

## References

* [OpenAI Function Calling Guide](https://platform.openai.com/docs/guides/function-calling)
* [Groq API OpenAI Client Docs](https://console.groq.com/docs/openai)

## Notes

* API keys are included in the notebook for testing purposes.
* Partial submission is allowed; you can update the notebook later.

