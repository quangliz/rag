### What?
- **Retrieval**: Searching and fetching relevant information from external knowledge base(database, documents, ...) in response to a user query.
- **Augmentation**: Retrieved information then being integrated into the LLM's prompt to enrich it with contextual details, creates an "augmented" prompt that guides the model more effectively, preventing it from hallucinating or generating generic responses.
- **Generation**: Just generate the output from the above step
In conclusion, RAG is a technique that enhances the capabilities of LLMs by combining information retrieval with generative processes. It ensures LLMs can leverage external, up-to-date knowledge, leading to more reliable and accurate outputs.
### Why?
- LLMs can't access confidential (private data), uncommon(specific data), or up-to-date information. This approach addresses LLM limitations, such as producing outdated information or hallucinations.
### How?
- Traditional LLMs:
!(../assets/LLMs.png)
- RAG:
![[Pasted image 20250722180337.png]]
