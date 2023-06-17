This repository contains the potential usage of the SymbolicAI architecture.
See the Symbolic AI repository here: https://github.com/Xpitfire/symbolicai

Symbolic AI defines everything as a symbol, with some symbols storing information, 
and some symbols are like expressions used to **process** the symbols to get information. 
At its core, symbols are manipulated using Large Language Model-defined operations.

Each symbol is basically stored in text form. 
There are basic operations already defined that enable you to do translation (translate), classification (choice), compose text (compose), do question answer (query). 
If you want to customize your own, you can use expressions to do any text-based instruction to the symbol. 
Furthermore, if you want even more flexibility, you can simply use an LLM-based function, just like in Wolfram-Alpha!

To install SymbolicAI, simply do:
``` pip install --upgrade symbolicai ```

To interface your OpenAI API key (so you can use the symbol functionality, simply do:
```
# Linux / MacOS
export OPENAI_API_KEY="<OPENAI_API_KEY>"

# Windows (PowerShell)
$Env:OPENAI_API_KEY="<OPENAI_API_KEY>"

# Jupyter Notebooks (important: do not use quotes)
%env OPENAI_API_KEY=<OPENAI_API_KEY>
```

More in the future:
- Chatbot
- Interfacing with Pinecone, Wolfram Alpha, Whispr APIs
