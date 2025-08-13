eam_MTU_DesignQA

Official submission for ASME Prob2_DesignQA Hackathon 2025 by Team_MTU.

Project Overview

This repository contains our solutions for ASME Prob2_DesignQA Hackathon 2025, covering all six DesignQA benchmark subsets:

Retrieval

Compilation

Definition

Presence

Dimension

Functional Performance

The code for each subset runs independently and produces outputs in the required submission format.

API Key Setup

This project uses the OpenAI API. For security reasons, no API key is included in this repository.
You will need to set your own API key in an environment variable named OPENAI_API_KEY before running any scripts.

Mac / Linux (Terminal):

export OPENAI_API_KEY="your_api_key_here"


Windows PowerShell:

setx OPENAI_API_KEY "your_api_key_here"


(Restart PowerShell after running this command.)

Google Colab:

import os
os.environ["OPENAI_API_KEY"] = "your_api_key_here"


Once the key is set, run the corresponding Python script or notebook for the desired subset (e.g., rule_retrieval.py or rule_retrieval.ipynb).
