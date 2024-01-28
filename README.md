## Kettle Agent

### Introduction
A very simple python project to demonstrate a very simple software agent, powered by an LLM.

This attempts to connect to a simulator on localhost port `50102`

_Note:_ This code is an attempt to demonstrate the concept of a simple agent and be simple to understand, it's not supposed to be production quality code.

### Setup
`pip install requirements.txt` to install the correct python libs.

Add your OpenAI API Key as an environment variable OPENAI_API_KEY

### Running 
Run the Kettle Simulator Godot project, which will start a websocket server on port `50102`.

Now run the `_main.py` main entry file.
