# Knowledge Injection in the era of LLMs
## knowledge injection in the fine-tuning process
The approach in this part mainly involves fine-tuning LLMs using domain-specific data, thereby resulting in numerous vertical domain LLMs. The generation of their dataset can be sourced from domain-specific knowledge graphs or online data, and so on. Here, we mainly list some open-source large models in the medical field.
1. [BioGPT: Generative Pre-trained Transformer for Biomedical Text Generation and Mining](https://arxiv.org/pdf/2210.10341.pdf), Briefings in Bioinformatics, 2022
2. [DoctorGLM: Fine-tuning your Chinese Doctor is not a Herculean Task](https://arxiv.org/pdf/2304.01097.pdf), Arxiv
3. [ChatDoctor: A Medical Chat Model Fine-Tuned on a Large Language Model Meta-AI (LLaMA) Using Medical Domain Knowledge](https://arxiv.org/ftp/arxiv/papers/2303/2303.14070.pdf), Arxiv
4. [PMC-LLaMA: Towards Building Open-source Language Models for Medicine](https://arxiv.org/pdf/2304.14454.pdf), Arxiv
5. [HuatuoGPT, Towards Taming Language Models To Be a Doctor](https://arxiv.org/pdf/2305.15075.pdf), Arxiv

## knowledge injection with KB
The approach in this part is mainly to integrate the domain knowledge base into LLMs, usually involving the graph related algorithms and the retrieval way from the knowledge base.
1. [DecAF: Joint Decoding of Answers and Logical Forms for Question Answering over Knowledge Bases](https://arxiv.org/abs/2210.00063), ICLR2023
2. [Knowledge Solver: Teaching LLMs to Search for Domain Knowledge from Knowledge Graphs](https://arxiv.org/pdf/2309.03118.pdf), Arxiv
3. [KnowledGPT: Enhancing Large Language Models with Retrieval and Storage Access on Knowledge Bases](https://arxiv.org/pdf/2308.11761.pdf), Arxiv
4. [MindMap: Knowledge Graph Prompting Sparks Graph of Thoughts in Large Language Models](https://arxiv.org/pdf/2308.09729.pdf), Arxiv
5. [Augmenting Black-box LLMs with Medical Textbooks for Clinical Question Answering](https://arxiv.org/pdf/2309.02233.pdf), Arxiv
6. [Chain of Knowledge: A Framework for Grounding Large Language Models with Structured Knowledge Bases](https://arxiv.org/pdf/2305.13269.pdf), Arxiv
7. [KITLM: Domain-Specific Knowledge InTegration into Language Models for Question Answering](https://arxiv.org/abs/2308.03638), Arxiv

## knowlege injection with external knowledge (Wiki or documents that is different from KB)
The method in this part mainly integrates externally available domain knowledge into LLMs. Note that this external knowledge is different from the knowledge graph. It is generally presented in the form of natural text (not a graph), so there is no need to use graphs to retrieve or query.
1. [Verify-and-Edit: A Knowledge-Enhanced Chain-of-Thought Framework](https://arxiv.org/abs/2305.03268), ACL2023
2. [Unified Demonstration Retriever for In-Context Learning](https://arxiv.org/abs/2305.04320), ACL2023

## knowledge injection with model self-driving
This part organizes the methods of model self-driving to obtain domain knowledge. Specifically, this type of method designs prompts to allow the LLM to generate the required domain-related text by itself, and then uses the generated text to perform in-domain tasks.
1. [Generate rather than Retrieve: Large Language Models are Strong Context Generators](https://arxiv.org/abs/2209.10063), ICLR2023
2. [Least-to-Most Prompting Enables Complex Reasoning in Large Language Models](https://arxiv.org/abs/2205.10625), ICLR2023
3. [Large Language Models Are Reasoning Teachers](https://arxiv.org/abs/2212.10071), ACL2023
4. [Symbolic Chain-of-Thought Distillation: Small Models Can Also “Think” Step-by-Step](https://aclanthology.org/2023.acl-long.150.pdf), ACL2023
5. [Chain-of-Thought Prompting Elicits Reasoning in Large Language Models](https://arxiv.org/abs/2201.11903), Arxiv

## knowledge probing benchmarks
1. [When Not to Trust Language Models: Investigating Effectiveness of Parametric and Non-Parametric Memories](https://aclanthology.org/2023.acl-long.546/), ACL2023
2. [Do Large Language Models Know What They Don’t Know?](https://arxiv.org/abs/2305.18153), findings of ACL2023
3. [Few-shot Fine-tuning vs. In-context Learning: A Fair Comparison and Evaluation](https://arxiv.org/abs/2305.16938), ACL2023