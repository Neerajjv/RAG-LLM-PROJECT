# RAG-LLM-PROJECT

# Rule Whiz Techno-Bot

Welcome to Rule Whiz Techno-Bot, an intelligent chatbot designed to help students and staff navigate campus rules and regulations. This project is part of the IBM SkillsBuild Internship for AICTE EduNet.

## Overview

Rule Whiz Techno-Bot is an AI-powered FAQ system that provides quick and accurate answers to questions about college policies, rules, and regulations. Leveraging the power of Google Palm LLM, HuggingFace embeddings, and FAISS vector stores, Rule Whiz Techno-Bot ensures that users have access to reliable information at their fingertips.

## Features

- **Intelligent Query Handling:** Uses advanced language models to understand and respond to user queries.
- **Comprehensive Knowledge Base:** Covers a wide range of topics related to campus rules and regulations.
- **Interactive Interface:** Built with Streamlit for an engaging user experience.
- **Scalable and Extendable:** Designed to be easily extendable with additional documents and data sources.

## Project Structure

- `Helper.py`: Contains functions for creating the vector database and setting up the QA chain.
- `Main.py`: The main entry point for the Streamlit application.
- `rules.txt`: Contains the rules and regulations document used for creating the vector database.

## Getting Started

### Prerequisites

- Python 3.7+
- Streamlit
- HuggingFace Transformers
- FAISS
- Google API Key
