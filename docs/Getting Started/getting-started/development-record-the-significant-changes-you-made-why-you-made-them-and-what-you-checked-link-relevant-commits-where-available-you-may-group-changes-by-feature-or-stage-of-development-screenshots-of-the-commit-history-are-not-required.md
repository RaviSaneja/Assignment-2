---
title: >-
  D)Development record: The significant changes you made, why you made them and
  what you checked. Link relevant commits where available. You may group changes
  by feature or stage of development; screenshots of the commit history are not
  required.
deprecated: false
hidden: false
metadata:
  robots: index
---
## **Development Record**

The development of the Intelligent Clinical Support System (ICSS) followed an iterative, human-centred design approach. The initial broad healthcare AI concept was refined into a focused clinical support prototype, prioritising structured information collection, contextual AI processing, patient safety and human oversight.

The significant development decisions are grouped below by feature and development stage.

### **1. Significant development changes**

| Development stage                         | Changes made                                                                                                            | Rationale                                                                                     | Checks and review criteria                                                                                   |
| ----------------------------------------- | ----------------------------------------------------------------------------------------------------------------------- | --------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------ |
| **1. Project scope refinement**           | Refined the broad healthcare AI concept into a focused clinical support system.                                         | Maintain a manageable project scope and avoid unsupported diagnostic claims.                  | Alignment between project objectives, prototype functionality and scope boundaries.                          |
| **2. System architecture**                | Designed an architecture incorporating questionnaires, LLM, RAG, diagnostic information and clinical review.            | Establish a structured approach to context engineering and healthcare information processing. | Component relationships, information flow and separation of proposed integrations.                           |
| **3. User roles and authentication**      | Designed separate entry points for patients, healthcare professionals and administrators.                               | Support role-appropriate interactions and information access.                                 | Navigation clarity and role consistency.                                                                     |
| **4. Consent and privacy**                | Introduced a dedicated consent and privacy screen before symptom collection.                                            | Address the sensitivity of reproductive, sexual and general health information.               | Consent clarity, AI limitation notices and user control.                                                     |
| **5. Structured questionnaire mechanism** | Divided information collection into symptom entry, patient history and structured questionnaires.                       | Reduce cognitive load and improve the organisation of patient information.                    | Question relevance, readability, completeness and navigation.                                                |
| **6. Personalised follow-up questions**   | Introduced context-dependent questions to clarify incomplete or ambiguous responses.                                    | Improve context construction rather than relying on a single open-ended prompt.               | Relevance of follow-up questions and opportunities to correct responses.                                     |
| **7. RAG and context engineering**        | Designed a proposed retrieval pipeline incorporating knowledge ingestion, retrieval, reranking and grounded generation. | Address outdated knowledge and unsupported LLM responses.                                     | Retrieval relevance, source traceability and insufficient-evidence handling as proposed evaluation criteria. |
| **8. Diagnostic information integration** | Designed diagnostic report upload and patient history interfaces.                                                       | Consider multiple information sources rather than relying exclusively on symptoms.            | Information organisation, upload requirements and professional review boundaries.                            |
| **9. Chatbot interaction**                | Introduced a conversational interface alongside structured questionnaires.                                              | Support hybrid and mixed-initiative human–AI interactions.                                    | Clarification, confirmation, correction and communication of AI limitations.                                 |
| **10. AI-generated summaries**            | Designed structured health information summaries containing symptoms, possible explanations and next steps.             | Improve readability and support informed conversations with healthcare professionals.         | Information clarity, uncertainty communication and non-diagnostic language.                                  |
| **11. Clinical decision support**         | Designed a clinician workspace containing patient context, AI insights, supporting evidence and safety checks.          | Maintain human oversight and professional decision-making authority.                          | Separation of AI-generated observations from clinical conclusions.                                           |
| **12. Success and failure recovery**      | Introduced dedicated success and failure screens with retry and answer-review options.                                  | Improve system transparency, error recovery and interaction reliability.                      | Visibility of system status and availability of recovery options.                                            |
| **13. Feedback and user control**         | Designed feedback, answer correction, summary download, privacy preferences and session deletion options.               | Strengthen human agency and responsible AI interaction.                                       | Visibility and accessibility of user control mechanisms.                                                     |
| **14. Future service integrations**       | Designed emergency assistance and insurance integration interfaces while retaining them as future extensions.           | Explore broader healthcare applications without overstating current implementation.           | Consistency with project scope and safety boundaries.                                                        |
| **15. Workflow documentation**            | Produced three illustrated storyboards and an overall system flowchart.                                                 | Communicate intended system behaviour and support reproducibility of user journeys.           | Consistency between interface designs, architecture and interaction scenarios.                               |

### **2. Development stages and supporting evidence**

1. **Concept development and scope definition**

   Identification of healthcare information collection challenges and project objectives.

   Evidence: Pre-Final Report — Abstract and Design Rationale.
2. **System architecture and technical design**

   Definition of the proposed LLM, RAG, questionnaire and clinical support architecture.

   Evidence: Files 4.1 and 10.
3. **Patient interaction design**

   Development of role selection, authentication, consent, symptom entry and questionnaire interfaces.

   Evidence: Interface files 1–6.
4. **AI and clinical support design**

   Development of diagnostic upload, health summaries, clinical decision support and chatbot interfaces.

   Evidence: Interface files 7–11.
5. **Reliability, recovery and user control**

   Introduction of failure notifications, successful completion states and feedback mechanisms.

   Evidence: Interface files 12, 13 and 16.
6. **Future healthcare extensions**

   Exploration of emergency assistance and insurance integration.

   Evidence: Interface files 14 and 15.
7. **Workflow consolidation**

   Documentation of healthcare use cases, user interaction scenarios and overall system navigation.

   Evidence: Files 4.2–4.5.

Grouped by development stage for reporting purposes; exact chronological dates have not been supplied.

### **3. What was checked**

The supplied design artefacts support a design-level inspection of the following areas.

| Evaluation area                   | Evidence status                                |
| --------------------------------- | ---------------------------------------------- |
| Interface navigation              | Visually demonstrated                          |
| Questionnaire structure           | Visually demonstrated                          |
| Personalised follow-up questions  | Illustrative prototype                         |
| Consent and privacy communication | Visually demonstrated                          |
| Human–AI interaction              | Illustrated through interfaces and storyboards |
| Success and failure recovery      | Illustrated through dedicated screens          |
| Human oversight                   | Represented in clinical support designs        |
| RAG retrieval accuracy            | Further testing required                       |
| LLM response reliability          | Further testing required                       |
| Diagnostic accuracy               | Not clinically validated                       |
| Backend security                  | Implementation unverified                      |
| Formal usability testing          | Results not supplied                           |

The distinction between design-level inspection and completed technical testing is important. The prototype illustrates intended interactions, but does not establish that every technical capability has been implemented or evaluated.

### **4. Significant development decisions and compromises**

One of the most significant development decisions was to refine the initial broad healthcare AI concept into a manageable clinical support prototype.

The interface was divided into separate consent, symptom entry, patient history and personalised follow-up stages to improve information organisation and user control. Success and failure states were introduced to communicate system outcomes and support interaction recovery.

Operational RAG, automated diagnostic processing and external healthcare integrations remain proposed capabilities requiring further implementation, security assessment and clinical validation.

This compromise prioritised meaningful human–AI interactions, responsible AI and a defensible project scope over implementing numerous unverified features.

### **5. Version control and commit references**

The development record is currently supported by 22 supplied artefacts, comprising 16 interface designs, three storyboards, one system architecture diagram, one system flowchart and the pre-final report.

Git commit references, repository links, dated design revisions and version history have not been supplied. Consequently, the development record references the available design artefacts rather than inventing commit identifiers or development dates.

Relevant repository commits or design version-history links should be included where available.