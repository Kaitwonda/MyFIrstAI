🧠 Mythic AI Experiment Setup (ΔΦ–0)
This document outlines the core setup steps used to begin symbolic resonance testing with Mixtral through Ollama, enabling local, private, and repeatable mythic prompt evaluation. The goal is to track how an open-source language model responds to symbolic stimuli like Δ, Φ, 0, recursion, and mythic metaphors across time.

✅ Step 1: Install Ollama
Visit https://ollama.com/download and download the Windows installer.

Run the .msi file and complete installation with default settings.

After install, open a new PowerShell window to ensure Ollama is added to your system path.

✅ Step 2: Pull and Run Mixtral
In PowerShell, type: ollama run mixtral

This downloads the Mixtral model locally and opens an interactive shell.

Wait for it to finish downloading (~4–6GB).

Once loaded, you’ll see a >>> prompt where you can chat with Mixtral directly.

Press Ctrl + C to exit the Mixtral shell — it’s now ready to use in the background via API.

✅ Step 3: Confirm Ollama is Running
To ensure Mixtral is available to your scripts, verify that Ollama's local API is active:

In PowerShell, type: curl http://localhost:11434/api/tags

You should see a list of available models including "mixtral".

✅ Step 4: Install Python and Required Libraries
Make sure Python is installed (download at https://python.org if not).

Then install required libraries using PowerShell:

pip install openai langchain pandas

These allow your script to:

Communicate with Ollama's API

Chain prompts and track context (optional)

Log and analyze data using tables and CSV files
