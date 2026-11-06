# Using Local RAG Notebook

## Quick start

Run `python app.py examples "wave period"` for cited retrieval. Optionally append `--model YOUR_INSTALLED_MODEL` after installing Ollama and a model. Selected chunks and the question go only to localhost:11434.

## Supported workflow

1. Overlapping chunks with source citations.
2. BM25 ranked document retrieval.
3. Optional retrieval-augmented localhost Ollama response.

## Validation and troubleshooting

Run the commands in the README. Invalid inputs produce explicit errors rather than silently changing the requested operation. Browser audio requires a user gesture; microphone apps require HTTPS or localhost and permission. For file tools, supply supported input formats and writable output directories.

## Limitations

Lexical retrieval. Generation requires an installed Ollama model and is not exercised by offline tests; verify model citations.

Tests use synthetic fixtures. These tests do not certify hardware compatibility, real-world forecast quality, trained-model accuracy, or production suitability for every input.
