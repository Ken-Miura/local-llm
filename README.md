# local LLM
This project provides a Compose file that allows you to run an LLM on your local machine.

# how to use

## create and start containers
`docker compose up -d`

## download models
`docker exec local-llm-container ollama pull "model you want to download"`

you can check models you can download [here](https://www.ollama.com/library).
