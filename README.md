# RAG-system-from-scratch
The single biggest problem with the AI everyone is so excited about is that it’s confidently lying to you. You ask a powerful LLM a simple question about your data: a PDF, a company doc, or even just this morning’s news, and it either invents a plausible-sounding, completely wrong answer or just gives up. We call this hallucination, and it’s the single biggest problem holding AI back from being truly useful. The fix is surprisingly simple. We don’t need a bigger model; we need to give our model an open-book exam. This is the core idea behind a technique called Retrieval-Augmented Generation (RAG). Today, I’ll show you exactly how to build your first RAG system from scratch using Python.

Here are the tools we will be using:

transformers (Hugging Face): To get our powerful, free LLM.
sentence-transformers: The easiest way to get a top-tier embedding model.
faiss-cpu: Facebook AI’s blazing-fast, free vector search library. It’s our vector store.
langchain: We’ll only use its text splitter, which is a smart shortcut that saves us hours of regex pain.


NOTE : Interactive widgets are not supported in GitHub preview.
Open this notebook in Google Colab for full functionality.
