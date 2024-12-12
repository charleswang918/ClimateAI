# ClimateAI

**ClimateAI** is an innovative system combining **Retrieval-Augmented Generation (RAG)** with **Large Language Models (LLMs)** to automate the generation of **Project Design Documents (PDDs)** compliant with the **Verified Carbon Standard (VCS)**. This project addresses the complexities of PDD creation by leveraging advanced retrieval and generation techniques, ensuring compliance, accuracy, and efficiency.

## Features

- **Multimodal Integration**: Combines textual data and domain-specific annotations to build a robust knowledge base.
- **Retrieval-Augmented Generation (RAG)**: Dynamically retrieves relevant content from the knowledge base to enhance document generation.
- **Interactive User Interface**: Built with [Dify](https://dify.ai), providing user-friendly input fields and an intuitive chatbot experience.
- **Efficient Deployment**: Developed and containerized using [Docker](https://www.docker.com), supporting local and cloud deployment for scalability and accessibility.

## Objectives

1. Streamline the creation of VCS-compliant PDDs.
2. Reduce administrative burden and enhance documentation quality.
3. Ensure scalable compliance with evolving carbon market standards.

## Workflow

1. **Data Collection and Preprocessing**: Crawling PDDs from the Verra Registry and preprocessing them into structured formats.
2. **Knowledge Base Construction**: Utilizing a pre-trained BERT model for vectorization and storing embeddings in a FAISS vector database.
3. **RAG Framework Integration**: Combining semantic retrieval and contextual generation to produce accurate, VCS-compliant outputs.
4. **Evaluation and Benchmarking**: Conducting comparative experiments with multiple LLMs to optimize model performance.

## Technical Details

- **Models Used**: Experiments included Llama 3.2, GPT-4o Mini, and Gemini 1.5 Pro. 
  - **Gemini 1.5 Pro with RAG** achieved the highest accuracy.
- **Development Platform**: The system leverages **Dify** for model integration and **Docker** for containerization, ensuring seamless deployment across various environments.
- **Evaluation Metrics**:
  - **Completeness and Relevance**: Assessing if PDDs contain all essential sections, such as methodology and monitoring plans.
  - **Alignment with VCS Guidelines**: Verifying adherence to VCS standards, template compliance, and methodology application.
  - **Clarity and Professionalism**: Reviewing document structure, tone, and coherence.
  - **Technical and Methodological Accuracy**: Ensuring robust methodology and monitoring details.

For more detailed insights, please refer to our [ClimateAI Final Report](./Team3-ClimateAI-Final_Report.pdf).

## Demo

Experience ClimateAI's capabilities through the interactive demo:

- [Climate AI Demo](https://udify.app/chat/97DNoMzdrbiYHzkN)


## Acknowledgments

This project was made possible with the support of [California Climate Exchange Company (CCEX)](https://ccex.co) and the dedicated contributions of the UCI Master of Data Science team.


