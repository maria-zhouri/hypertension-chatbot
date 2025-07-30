# Hypertension Support Chatbot

An AI-powered chatbot designed to help users better understand and manage high blood pressure through localized, evidence-based guidance.

## Project Overview

This project was developed for the Health Data Analytics course in the Master of Business Analytics program at Saint Mary’s University (Sobey School of Business). It uses Ollama and AnythingLLM to run locally on a user's machine, with a retrieval-augmented generation (RAG) setup that delivers grounded responses using uploaded documents.

## Features

- Provides support in interpreting blood pressure readings
- Offers guidance on diet (e.g., sodium limits, DASH diet) and lifestyle habits (e.g., alcohol, stress, exercise)
- Responds to user queries using plain-language responses grounded in healthcare knowledge
- Operates locally with user privacy in mind

## Knowledge Sources

| File Name                 | Description                                        |
|--------------------------|----------------------------------------------------|
| `knowledge_document_1.txt` | BP classification and treatment thresholds        |
| `knowledge_document_2.txt` | DASH diet, sodium limits, foods to avoid          |
| `knowledge_document_3.txt` | Lifestyle advice: exercise, alcohol, stress       |
| `chat_transcript.txt`      | Sample Q&A demonstrating chatbot behavior         |
| `system_prompt.txt`        | Defines tone, scope, and guardrails               |
| `use_case_description.md`  | Describes user pain points and chatbot objectives |

## Demo

A demonstration video of the chatbot in action is included in `demo_video.mp4`.

## Technologies Used

- Ollama for running local large language models
- AnythingLLM as the interface for managing documents and chat context
- TXT files used to simulate document-based retrieval (RAG-style responses)

## Purpose

This project was a practical opportunity to experiment with open-source LLM tools in a real-world healthcare context. It explores how AI can support chronic condition management through simple, user-friendly conversations while respecting privacy and information quality.
