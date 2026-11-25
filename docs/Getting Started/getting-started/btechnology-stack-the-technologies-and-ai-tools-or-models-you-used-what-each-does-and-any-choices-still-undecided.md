---
title: >-
  B)Technology stack: The technologies and AI tools or models you used, what
  each does and any choices still undecided
deprecated: false
hidden: false
metadata:
  robots: index
---
## **Technology Stack**

The Intelligent Clinical Support System (ICSS) is designed around a combination of Large Language Models (LLMs), Retrieval-Augmented Generation (RAG), context engineering, structured questionnaires, diagnostic information processing and human–computer interaction (HCI).

The current technology stack primarily supports system design and prototyping, while several technical components remain proposed or require further implementation.

### **1. Core technologies and their purpose**

| Technology                                | Purpose within ICSS                                                                                                                | Current status                                   |
| ----------------------------------------- | ---------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------ |
| **Large Language Models (LLMs)**          | Interpret patient information, generate personalised follow-up questions and produce structured health information summaries.      | Proposed integration                             |
| **Retrieval-Augmented Generation (RAG)**  | Retrieve relevant healthcare knowledge to support evidence-informed AI responses.                                                  | Architecture designed; implementation unverified |
| **Context engineering**                   | Combine symptoms, questionnaire responses, medical history, diagnostic reports and retrieved knowledge into relevant model inputs. | Design established                               |
| **Prompt engineering**                    | Define AI tasks, instructions, constraints, safety boundaries and output formats.                                                  | Design approach established                      |
| **Structured questionnaires**             | Collect consistent and relevant patient health information.                                                                        | Prototype designed                               |
| **Personalised question generation**      | Identify missing or ambiguous information and generate context-dependent follow-up questions.                                      | Prototype illustrated; automation unverified     |
| **Conversational AI**                     | Support natural-language healthcare interactions and clarification.                                                                | Interface prototype                              |
| **Medical image and document processing** | Extract relevant information from diagnostic reports and medical images.                                                           | Proposed                                         |
| **Clinical decision support**             | Present patient information, potential concerns and supporting evidence for professional review.                                   | Interface prototype                              |
| **Human–computer interaction (HCI)**      | Support usability, accessibility, error recovery, transparency and user control.                                                   | Incorporated into interface designs              |

### **2. Proposed RAG and LLM technology architecture**

#### **Patient information collection**

Symptoms

Questionnaires

Medical history

Diagnostic reports

#### **Context and prompt engineering**

Information preparation, completeness checks and task specification

#### **RAG knowledge retrieval**

Healthcare knowledge base

Document parsing and chunking

Embedding model and vector index

Retrieval, filtering and reranking

#### **Large Language Model**

Contextual processing, summarisation and grounded generation

#### **Output and safety layer**

Source references · Uncertainty · Safety guidance · Health information summary

**Healthcare professional review**

Human oversight and final clinical judgement

Conceptual technology architecture derived from the supplied system designs and report, rather than a verified deployed stack.

### **3. AI tools used during project development**

| AI tool             | Application                                                                            | Status                   |
| ------------------- | -------------------------------------------------------------------------------------- | ------------------------ |
| **OpenAI ChatGPT**  | Project documentation, design analysis, technical explanations and report refinement.  | Confirmed use            |
| **OpenAI ChatGPT**  | Reviewing architecture, storyboards, interface designs and system workflows.           | Confirmed use            |
| **OpenAI ChatGPT**  | Identifying inconsistencies, safety considerations and implementation limitations.     | Confirmed use            |
| **Clinical LLM**    | Proposed model for processing patient information and generating contextual summaries. | Specific model undecided |
| **Embedding model** | Convert healthcare documents and queries into vector representations for retrieval.    | Specific model undecided |

ChatGPT's use as a development and documentation assistant is separate from the proposed clinical LLM integrated into ICSS.

### **4. Technical choices still undecided**

The following technologies are required for further development, but specific products, frameworks and models have not been confirmed in the supplied project materials.

| Technology category | Potential options                               | Purpose                                        |
| ------------------- | ----------------------------------------------- | ---------------------------------------------- |
| Frontend framework  | React, Next.js or Flutter                       | Interactive patient and clinician interfaces   |
| Backend framework   | Python FastAPI, Flask or Django                 | Application logic and API integration          |
| LLM                 | GPT, Gemini, Claude or Llama                    | Contextual AI processing and summarisation     |
| Embedding model     | OpenAI embeddings or Sentence Transformers      | Semantic document and query representation     |
| Vector database     | FAISS, Chroma, Pinecone or Qdrant               | Storage and retrieval of document embeddings   |
| RAG framework       | LangChain, LlamaIndex or custom implementation  | Retrieval and generation orchestration         |
| Patient database    | PostgreSQL or another suitable secure database  | Structured patient information storage         |
| Document processing | PyMuPDF or equivalent tools                     | Diagnostic report text extraction              |
| Image processing    | OpenCV, PyTorch or TensorFlow                   | Proposed medical image-processing capabilities |
| Authentication      | Suitable identity and access-management service | Secure role-based access                       |
| Deployment          | Local server or suitable cloud infrastructure   | Application hosting and operation              |
| Version control     | Git and GitHub                                  | Development tracking and reproducibility       |

These are **potential technology choices, not claims of technologies already used**.

### **5. Technology selection rationale**

| Design decision                                 | Rationale                                                                         |
| ----------------------------------------------- | --------------------------------------------------------------------------------- |
| LLM-based processing                            | Support flexible natural-language interaction and contextual summarisation.       |
| RAG rather than relying solely on LLM knowledge | Provide relevant external healthcare information and improve source traceability. |
| Structured questionnaires                       | Improve consistency and organisation of patient information.                      |
| Personalised follow-up questions                | Clarify incomplete information and construct more relevant context.               |
| Hybrid interaction                              | Combine structured forms with conversational AI.                                  |
| Multiple information sources                    | Incorporate medical history and diagnostic information alongside symptoms.        |
| Human-in-the-loop architecture                  | Maintain professional responsibility for clinical decisions.                      |
| Modular system architecture                     | Allow individual components to be developed, evaluated and extended separately.   |

### **6. Future technology integrations**

The following integrations remain outside the current prototype scope:

- **Medical insurance APIs:** Authorised insurance-related information exchange.
- **Emergency healthcare APIs:** Location-based healthcare service discovery and emergency assistance.
- **AI-powered robotics:** Guided patient information collection through robotic interfaces.
- **Multimodal AI:** Potential processing of text, voice, medical images and diagnostic documents.
- **Longitudinal health monitoring:** Recording changes in patient symptoms and health information over time.

### **7. Current technology stack summary**

The current ICSS project establishes a conceptual technology architecture and visual prototype combining questionnaire-based information collection, context engineering, LLMs, RAG and clinical decision support.

The final selection of programming languages, development frameworks, AI models, databases, authentication services and deployment infrastructure remains subject to technical feasibility, privacy requirements, reliability, cost and clinical safety evaluation.

##
