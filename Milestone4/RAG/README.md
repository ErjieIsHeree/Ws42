_This project has been created as part of the 42 curriculum by exia_

# RAG against the machine

## Description

**RAG against the machine** is a Retrieval-Augmented Generation (RAG) system
that answers questions about a codebase. Instead of relying on knowledge
frozen inside a language model, the system retrieves the most relevant
evidence from an external source at answer time and uses it to generate a
grounded response.

The goal of the project is to ingest the provided **vLLM repository**,
retrieve the source snippets that best answer a question, generate a
coherent answer from them with a small local model
(**Qwen/Qwen3-0.6B**), and measure retrieval quality with **recall@k**.

## Instructions

Here is an example of how to set/initialize/run the program:

```bash
echo example
```

## Resources

- [Example source 1](link1)
- [Example source 2](link2)
- [Example source 3](link3)

## Additional sections

### System architecture

### Chunking strategy

### Retrieval method

### Performance analysis

### Design decisions

### Challenges faced

### Example usage
