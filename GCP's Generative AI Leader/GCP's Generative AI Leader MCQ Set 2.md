# Section 1: Fundamentals of gen AI

## 1. A marketing team wants to understand the difference between traditional AI and generative AI before implementing a new content creation strategy. What is the key characteristic that distinguishes generative AI from traditional AI?
*   **A) Generative AI requires less computational power than traditional AI.**
*   **B) Generative AI focuses primarily on classification tasks while traditional AI creates content.**
*   **C) Generative AI can create new content that wasn’t explicitly programmed, while traditional AI typically focuses on prediction and classification.**
*   **D) Generative AI always requires human supervision, while traditional AI operates autonomously.**

**Correct Answer: C**
> Generative AI can create new content that wasn’t explicitly programmed, while traditional AI typically focuses on prediction and classification. This is the defining characteristic that distinguishes generative AI from traditional AI approaches.

---

## 2. A company is selecting a foundation model for a customer service chatbot that needs to understand and respond to complex customer queries about their products. Which factor should be their primary consideration when choosing the appropriate model?
*   **A) The model’s ability to generate images**
*   **B) The model’s context window size**
*   **C) The model’s training data size**
*   **D) The model’s hardware requirements**

**Correct Answer: B**
> The context window size determines how much previous conversation and product information the model can consider when generating responses. A larger context window allows the chatbot to maintain coherence over longer conversations and reference specific product details mentioned earlier, which is crucial for complex customer service interactions.

---

## 3. A company is developing a virtual assistant that needs to understand both text and image inputs from users. Which Google foundation model would be most appropriate for this multimodal application?
*   **A) Gemma**
*   **B) Imagen**
*   **C) Gemini**
*   **D) Veo**

**Correct Answer: C**
> Gemini is Google’s multimodal foundation model capable of understanding and reasoning across different types of information, including text and images. This makes it ideal for a virtual assistant that needs to process both text queries and image inputs from users.

---

## 4. A retail company wants to use generative AI to create product descriptions. Which Google foundation model would be most appropriate for this text generation task?
*   **A) Imagen**
*   **B) Veo**
*   **C) Gemini**
*   **D) Cloud Vision API**

**Correct Answer: C**
> Gemini is well-suited for text generation tasks like creating product descriptions because it can understand context, generate coherent and relevant text, and adapt to specific writing styles or requirements.

---

## 5. A company is implementing a generative AI system to analyze customer feedback. Which of the following would be classified as unstructured data in this context?
*   **A) Customer satisfaction ratings on a scale of 1–5**
*   **B) Multiple-choice survey responses**
*   **C) Open-ended written comments from customers**
*   **D) Demographic information stored in a database**

**Correct Answer: C**
> Open-ended written comments from customers are unstructured data because they don’t follow a predefined format or structure. Unlike the other options which have clear formats (ratings, multiple-choice responses, or database fields), free-form text requires specialized processing techniques to extract meaning.

---

# Section 2: Google Cloud’s gen AI offerings

## 6. A company wants to leverage Google Cloud’s AI-optimized infrastructure for their generative AI workloads. Which of the following is a key component of this infrastructure?
*   **A) Traditional CPU-only servers**
*   **B) Google’s custom-designed TPUs**
*   **C) On-premises data centers**
*   **D) Manual scaling systems**

**Correct Answer: B**
> Google’s custom-designed Tensor Processing Units (TPUs) are a key component of Google Cloud’s AI-optimized infrastructure. These specialized chips are designed specifically for machine learning workloads and provide significant performance advantages for training and running generative AI models compared to traditional computing hardware.

---

## 7. A company wants to enhance their employees’ productivity by integrating generative AI capabilities into their everyday work tools. Which Google Cloud offering would best meet this need?
*   **A) Gemini for Google Workspace**
*   **B) Vertex AI Platform**
*   **C) Google Agentspace**
*   **D) Conversational Agents**

**Correct Answer: A**
> Gemini for Google Workspace integrates generative AI capabilities directly into everyday productivity tools like Gmail, Docs, Sheets, Slides, and Meet. This integration allows employees to leverage AI assistance within their familiar work environment, enhancing productivity without requiring them to switch to separate applications.

---

## 8. A company wants to create a virtual agent that can help customers find information about their products and services. Which Google Cloud offering would be most appropriate for building this custom agent?
*   **A) Vertex AI Agent Builder**
*   **B) Gemini app**
*   **C) NotebookLM**
*   **D) Gemini for Google Workspace**

**Correct Answer: A**
> Vertex AI Agent Builder is specifically designed for creating, deploying, and managing virtual agents that can help customers find information and complete tasks. It provides the tools needed to build custom agents that can understand natural language, access relevant information, and provide helpful responses to customer queries.

---

## 9. A company wants to leverage Google Cloud’s strengths in generative AI. Which of the following best describes a key advantage of Google’s comprehensive AI ecosystem?
*   **A) It works exclusively with Google’s proprietary data formats**
*   **B) It requires users to replace all existing non-Google tools**
*   **C) It integrates generative AI across Google products and services**
*   **D) It only supports basic AI capabilities for simple use cases**

**Correct Answer: C**
> A key advantage of Google’s comprehensive AI ecosystem is that it integrates generative AI across Google products and services. This integration allows organizations to leverage AI capabilities within familiar tools and workflows, creating a cohesive experience and maximizing the value of generative AI across different business functions.

---

## 10. A company wants to implement a solution that can automatically extract information from documents like invoices and receipts. Which Google Cloud AI API would be most appropriate for this purpose?
*   **A) Cloud Vision API**
*   **B) Natural Language API**
*   **C) Document AI API**
*   **D) Translation API**

**Correct Answer: C**
> Document AI API is specifically designed for extracting structured information from documents like invoices, receipts, and forms. It can identify and extract key fields, tables, and text from documents, making it ideal for automating document processing workflows.

---

# Section 3: Techniques to improve gen AI model output

## 11. A financial services company is implementing a generative AI system to provide investment advice. They are concerned about the model potentially generating misleading or incorrect financial information. Which Google Cloud-recommended practice would best address this concern?
*   **A) Increasing the model’s temperature setting**
*   **B) Implementing retrieval-augmented generation (RAG)**
*   **C) Reducing the model’s context window**
*   **D) Limiting the model to zero-shot prompting**

**Correct Answer: B**
> Implementing retrieval-augmented generation (RAG) would best address the concern about misleading financial information. RAG enhances the model’s responses by retrieving relevant, accurate information from trusted sources before generating content, helping to ground the investment advice in factual, up-to-date financial information rather than relying solely on the model’s pre-trained knowledge.

---

## 12. A company is implementing a generative AI system for customer service. They want the AI to respond in a consistent brand voice and follow specific guidelines. Which prompt engineering technique would be most effective for this purpose?
*   **A) Role prompting**
*   **B) Zero-shot prompting**
*   **C) Using a higher temperature setting**
*   **D) Avoiding few-shot examples**

**Correct Answer: A**
> Role prompting is most effective for ensuring consistent brand voice and guideline adherence. By defining a specific role for the AI (e.g., “You are a customer service representative for [Company] who always maintains a friendly, professional tone and follows these guidelines…”), you can establish the expected communication style and boundaries for the AI’s responses.

---

## 13. A company is using a generative AI model to generate creative marketing content. They want the content to be diverse and imaginative while still being coherent. Which sampling parameter should they adjust to achieve this balance?
*   **A) Token count**
*   **B) Temperature**
*   **C) Top-p (nucleus sampling)**
*   **D) Safety settings**

**Correct Answer: B**
> Temperature is the sampling parameter that controls the randomness and creativity of the model’s outputs. A higher temperature (e.g., 0.7–0.9) increases diversity and creativity, while a lower temperature (e.g., 0.2–0.3) produces more focused, deterministic responses. For creative marketing content that needs to balance imagination with coherence, adjusting the temperature is key.

---

## 14. A company is implementing prompt engineering for their generative AI application. Which of the following is an example of role prompting?
*   **A) “Generate a product description for our new wireless headphones.”**
*   **B) “You are a marketing expert with 20 years of experience in the tech industry. Create a compelling product description for our new wireless headphones that highlights their unique features and benefits.”**
*   **C) “Here are three examples of good product descriptions: [Example 1] [Example 2] [Example 3]. Now, generate a product description for our new wireless headphones.”**
*   **D) “Think step by step to create a marketing strategy for our new wireless headphones.”**

**Correct Answer: B**
> Role prompting involves assigning a specific identity, expertise level, or character to the AI model. The example “You are a marketing expert with 20 years of experience…” clearly establishes a role for the AI to adopt, which influences how it approaches the task of creating a product description.

---

## 15. A company is implementing a generative AI system and wants to ensure it provides accurate responses about their products and services. Which limitation of foundation models should they be most concerned about addressing?
*   **A) Hallucinations**
*   **B) Knowledge cutoff**
*   **C) Data dependency**
*   **D) Edge cases**

**Correct Answer: A**
> Hallucinations — the tendency of generative AI models to produce plausible-sounding but factually incorrect information — is the most critical limitation to address when ensuring accurate responses about products and services. Hallucinations could lead to misinformation being provided to customers, potentially damaging trust and reputation.

---

# Section 4: Business strategies for a successful gen AI solution

## 16. A company has successfully implemented a generative AI solution for their marketing department. According to Google Cloud-recommended steps, what should they do to measure the impact of this initiative?
*   **A) Compare the solution’s performance against predefined business metrics and KPIs**
*   **B) Count the number of times the solution is used without regard to outcomes**
*   **C) Assume the impact is positive without measurement**
*   **D) Only measure technical metrics like processing speed and uptime**

**Correct Answer: A**
> Comparing the solution’s performance against predefined business metrics and KPIs is the recommended approach to measure the impact of a generative AI initiative. This ensures that the assessment is tied to actual business outcomes like increased efficiency, improved customer satisfaction, or revenue growth, providing meaningful insights into the solution’s value.

---

## 17. A company is implementing a generative AI solution and wants to ensure it aligns with responsible AI principles. Which of the following is most important for ensuring accountability in their AI system?
*   **A) Making the system completely autonomous with no human oversight**
*   **B) Implementing explainability features that help users understand how the system reaches its conclusions**
*   **C) Keeping the AI decision-making process completely opaque**
*   **D) Maximizing the system’s creativity without regard for accuracy**

**Correct Answer: B**
> Implementing explainability features that help users understand how the system reaches its conclusions is most important for ensuring accountability in AI systems. When users can understand the factors and reasoning behind AI-generated outputs, they can better evaluate their appropriateness, identify potential issues, and determine when human judgment should override automated recommendations.

---

## 18. A company is implementing a generative AI solution for automated decision-making. Which aspect of responsible AI is most important for maintaining user trust in this context?
*   **A) Making the decision-making process completely opaque**
*   **B) Ensuring the system makes decisions as quickly as possible regardless of accuracy**
*   **C) Providing transparency and explainability about how decisions are made**
*   **D) Collecting unnecessary data from users**

**Correct Answer: C**
> Providing transparency and explainability about how decisions are made is crucial for maintaining user trust in automated decision-making systems. When users understand the factors and reasoning behind AI-generated decisions, they’re more likely to trust the outcomes, even when they don’t agree with them.

---

## 19. A company is planning to integrate generative AI into their business processes. According to Google Cloud-recommended steps, what should they do to prepare their organization for this change?
*   **A) Implement the technology without informing employees or stakeholders**
*   **B) Develop a comprehensive change management and training plan**
*   **C) Assume all employees will immediately understand how to use the new technology**
*   **D) Focus exclusively on technical implementation, ignoring organizational impacts**

**Correct Answer: B**
> Developing a comprehensive change management and training plan is essential for preparing an organization for generative AI integration. This approach ensures that employees understand the purpose and benefits of the new technology, know how to use it effectively, and are prepared for changes to their workflows, increasing adoption and maximizing value.

---

## 20. A healthcare company is implementing a generative AI solution to assist with patient diagnosis. Which aspect of responsible AI is most critical for this application?
*   **A) Maximizing the system’s creativity regardless of accuracy**
*   **B) Ensuring the system provides explanations for its recommendations**
*   **C) Making the system completely autonomous with no human oversight**
*   **D) Keeping the AI decision-making process completely opaque**

**Correct Answer: B**
> Ensuring the system provides explanations for its recommendations is critical for responsible AI in healthcare diagnosis. Explainability allows healthcare professionals to understand the factors and reasoning behind AI-suggested diagnoses, verify their medical validity, identify potential errors or limitations, and maintain their professional judgment and responsibility for patient care decisions.

---

## 21. A company wants to use generative AI to create a chatbot that can answer customer questions about their products and services. They need to ensure that the chatbot only uses information from the company’s official documentation. What should the company do?
*   **A) Use role prompting.**
*   **B) Adjust the temperature parameter.**
*   **C) Use prompt chaining.**
*   **D) Use grounding.**

**Correct Answer: D**
> Grounding is the technique of “grounding” the LLM’s responses in specific, authoritative data sources (like the company’s official documentation). This prevents the model from “hallucinating” or providing information outside of the approved knowledge base, ensuring accuracy and relevance to the company’s specific products and services.

---

## 22. A large e-commerce company with a vast and frequently updated product catalog finds that customers struggle to find products on their website, and support agents spend too much time finding detailed product information. The company wants to improve search accuracy and efficiency for both customers and support. What Google Cloud solution should they use?
*   **A) Vertex AI Conversation**
*   **B) Vertex AI Natural Language API**
*   **C) Pre-built RAG with Vertex AI Search**
*   **D) Vertex AI Model Garden**

**Correct Answer: C**
> This scenario strongly points to the need for accurate and up-to-date information retrieval from a product catalog. Pre-built RAG (Retrieval-Augmented Generation) combined with Vertex AI Search is the ideal solution. Vertex AI Search can index the product catalog, and RAG can then use this indexed data to ground the responses of a generative AI model, ensuring that both customer searches and support agent queries retrieve precise and relevant product information.

---

## 23. A company has a machine learning project that involves diverse data types like streaming data and structured databases. How does Google Cloud support data gathering for this project?
*   **A) Google Cloud provides tools such as Pub/Sub, Cloud Storage, and Cloud SQL.**
*   **B) The Gemini app is the primary Google Cloud tool for directly collecting data.**
*   **C) Google Cloud’s strengths are in the data analysis tools such as BigQuery.**
*   **D) Google Cloud relies on Vertex AI to connect to external data.**

**Correct Answer: A**
> Google Cloud offers a comprehensive suite of services for data ingestion and storage. Pub/Sub is for streaming data, Cloud Storage for various file types (including unstructured), and Cloud SQL for relational structured databases. These are fundamental for gathering diverse data. Gemini is a model, BigQuery is for analysis, and Vertex AI is for ML platform, not primary data collection tools themselves.

---

## 24. A company’s large learning model (LLM) is producing hallucinations that are a result of the Knowledge cutoff. How does retrieval-augmented generation (RAG) overcome this limitation?
*   **A) RAG fine-tunes the LLM on specific customer query patterns to improve the speed and efficiency of response generation.**
*   **B) RAG enhances the creative writing capabilities of the LLM to generate more engaging and informative responses.**
*   **C) RAG enables the LLM to retrieve relevant and up-to-date information from knowledge sources.**
*   **D) RAG uses human oversight to ensure accuracy before presenting information to the customer.**

**Correct Answer: C**
> The primary purpose of RAG is to address the “knowledge cutoff” and hallucination issues of LLMs. It does this by retrieving relevant, up-to-date information from external knowledge sources (like databases or documents) at inference time and then using this retrieved information to ground the LLM’s generation, ensuring factual accuracy and relevance to the specific query.

---

## 25. A security team needs a centralized platform to gain a comprehensive overview of their organization’s security health across their entire Google Cloud environment, including potential threats to their generative AI deployments. Which Google Cloud security offering is specifically for this purpose?
*   **A) Workload monitoring tools**
*   **B) Security Command Center**
*   **C) Identity and Access Management**
*   **D) Secure-by-design infrastructure**

**Correct Answer: B**
> Security Command Center is Google Cloud’s comprehensive security management and data risk platform. It provides centralized visibility into security posture, identifies vulnerabilities, detects threats, and helps manage compliance across the entire Google Cloud environment, including services and deployments like generative AI.
