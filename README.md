# Integrating Agentic AI and LLMs with TOGAF in the Enterprise

#### These set of project demonstrates how an Agentic AI system — powered by OpenAI's GPT-4o LLM, OpenAI vector embeddings, Pinecone vector database, Google Cloud Storage, Azure Kubernetes Services, Azure CLI, Langchain, Streamlit, Prometheus, Grafana, Google Cloud Platform and n8n orchestration — can be effectively mapped to the TOGAF ADM (Architecture Development Method) to support intelligent automation within an enterprise context. 

#### Rather than viewing AI as an isolated capability, this implementation positions it as a modular, governable, and incrementally scalable architecture component that aligns directly with the enterprise TOGAF (Open Group Architecture Framework) principles.

<ins>Projects</ins>: 

* (I) Automating Complex Enterprise Business & Financial Decisions Using Agentic AI in n8n ( manuelbomi/Automating-Complex-Enterprise-Business-Financial-Decisions-Using-Agentic-AI-in-n8n )

* (2) Enterprise Agentic AI: Scalable Meeting Orchestration with n8n ( manuelbomi/Enterprise-Agentic-AI---Scalable-Meeting-Orchestration-with-n8n )

* (3) Agentic AI Workflow: Enterprise Data Integration Pipeline and Vector Storage with n8n ( manuelbomi/Agentic-AI-Workflow----Enterprise-Data-Integration-Pipeline-and-Vector-Storage-with-n8n )

* (4) Scalable Agentic AI System: Enterprise Data Orchestration & Event Coordination with n8n, Pinecone & OpenAI  ( https://github.com/manuelbomi/Scalable-Agentic-AI-System-Enterprise-Data-Orchestration-Event-Coordination-with-n8n-Pinecone-OpenAI )

* (5) An Enterprise Generative-AI LLM System for Manufacturing and Business Applications ( manuelbomi/An-Enterprise-Generative-AI-LLM-System-for-Manufacturing-and-Business-Applications- )
  
- Deployed implementation  of project 5 (on Azure Kubernetes Services & Namecheap): (https://app.emmanueloyekanluprojects.com) – Here , you can upload your own pdf files and then chat with the system
  
- Deployed implementation of project 5 (Prometheus & Grafana monitoring): https://grafana.emmanueloyekanluprojects.com/login 
  
* (6) An Enterprise LLM System for Healthcare Applications (manuelbomi/An-Enterprise-LLM-System-for-HealthCare-Applications)


#### A tabular summary of the TOGAF-based implementation is shown below:

| TOGAF Phases | AI Workflow Component |
|-------------|------------------------|
| **A. Architecture Vision** | Real-time intelligent automation using LLMs + Agentic AI + Vector databases |
| **B. Business Architecture** | Gen-AI, LLMs, RAGs, Agentic AI as business enablers |
| **C. Information Systems** | Vector databases (e.g. Pinecone), AI agent nodes in low-code (n8n) and code-based applications |
| **D. Technology Architecture** | Cloud-native deployment (n8n, Docker, AKS) |
| **E. Opportunities & Solutions** | ERPs + CRMs + Manufacturing + Business projects + extensible tools |
| **F. Migration Planning** | Start with data pipeline orchestration & event coordination, then scale out |
| **G. Implementation Governance** | Secure, traceable workflow deployment |
| **H. Change Management** | Continuous update of embeddings without retraining |


---

## Phase A: Architecture Vision  🧭
#### The goal of the Agentic AI system is to advance the enterprise vision of real-time intelligent automation with autonomous AI Agents that learns from the environments and increases its intelligence and capabilities. 

#### By leveraging vector databases like Pinecone in combination with large language models (LLMs), the agent dynamically interacts with business knowledge and user context without requiring model retraining. 

#### This directly supports enterprise-level goals such as business agility, self-service intelligence, and lower time-to-decision. 

#### The n8n-based agentic and LLM workflow thus becomes a tangible proof-of-concept for broader enterprise AI adoption. In a nutshell, in these set of projects, in the architecture vision phase, we:

        ◦ Show how Agentic AI supports the vision of enterprise-wide intelligent automation by connecting business goals with AI capabilities.
		
        ◦ Example: Using Pinecone + LLMs in several contexts ensures real-time knowledge integration without retraining, aligning with “business agility” goals.

---

## Phase B: Business Architecture  🏛️ 
#### From a business perspective, the AI agent acts as an intelligent assistant capable of handling real workflows — such as enterprise data pipeline orchestration and event/meeting scheduling — using the enterprise data. 

#### It supports Retrieval-Augmented Generation (RAG) from the Pinecone vector store, allowing the reuse of internal documentation and knowledge assets across teams. 

#### This breaks down data silos and aligns with TOGAF's vision of reusable, shared capabilities. The agent is designed to be extensible — future versions could handle financial analysis, aid enterprise-wide troubleshooting and project assistance, or detailed customer interactions (as shown in project 5).  

#### In a nutshell, in the business architecture phase, across all the projects (1 – 6), we:

        ◦ Position the AI agent as a business enabler that can handle RAG workflows, event scheduling & management, or financial analysis.
		
        ◦ Emphasize enterprise data reuse: no silos, just embeddings across shared knowledge bases.

--- 

## Phase C: Information Systems Architecture  🧩 
#### Data Architecture is centered around Pinecone, which acts as a semantic memory layer for the enterprise. Embeddings are generated using OpenAI and stored in indexes (databases), enabling accurate retrieval and contextual understanding across workflows. 

#### On the Application Architecture side, the agent is decomposed into modular services: language models, memory buffers, vector tools, data storage APIs, and calendar interfaces. 

#### These nodes are reusable, low-code (except for projects 5 and 6 that was developed using VSCode); and loosely coupled. This workflows seamlessly aligns with TOGAF’s principles of service orientation and modularity. 

#### In a nutshell, in the information system architecture phase, we designed:

        ◦ Data Architecture → vector databases like Pinecone become the data backbone for semantic search and enterprise knowledge.
		
        ◦ Application Architecture → agent nodes (LLM, memory, tools) become modular “AI services” that plug into different enterprise workflows.
---

## Phase D: Technology Architecture  ☁️ 
#### The implementation is fully cloud-native, orchestrated within n8n, and designed to run in Docker, Kubernetes (AKS, EKS), or serverless environments. This ensures horizontal scalability, uptime, and operational reliability. 

#### The use of credentials management (for example in AKS Secrets/Vaults; as in project 5), logging, and reusable nodes supports enterprise-grade governance, monitoring, and security, which are essential components of a compliant technology stack. 

#### In a nutshell, in the technological architecture phase, we:

        ◦ We designed AI Agents to run on scalable, cloud-native platforms (e.g., n8n, Docker, AKS).
		
        ◦ This ensures elasticity, reliability, and governance at scale.
---

## Phase E: Opportunities & Solutions  🚀 
#### As shown here: tmanuelbomi/Designing-an-Enterprise-Agentic-AI-Scheduler-in-n8n  the Agentic AI system already integrates with Google Drive and Google Calendar to check availability and create events, showcasing seamless integration with enterprise productivity tools. This serves as a template for future integrations with enterprise ERP, CRM, or ticketing systems. 

#### We show how we can vary the design of the Agentic AI Scheduler to perform the function of an enterprise data pipeline orchestrator here: manuelbomi/Agentic-AI-Workflow----Enterprise-Data-Integration-Pipeline-and-Vector-Storage-with-n8n . 

#### With that solution, The Agentic AI system can automatically warehouse any enterprise data from any source into the Pinecone vector database. Hence, all enterprise data can be located in a single source of truth. 

#### We also used a slight variation of the base Agentic AI system for complex enterprise financial and business decision here: manuelbomi/Automating-Complex-Enterprise-Business-Financial-Decisions-Using-Agentic-AI-in-n8n    

#### We fully discussed how the base Agentic AI system can be scaled up for various other enterprise use cases here: manuelbomi/Enterprise-Agentic-AI---Scalable-Meeting-Orchestration-with-n8n   

#### All the above-mentioned projects are all low-code designs with n8n. The full code counterparts with variations of the same base agents for other use-cases such as for business/manufacturing and for healthcare applications are shown in projects 5 and 6.

#### The variations in use cases for the base Agentic AI system demonstrates how re-usability and scalability can be achieved for LLM and Agentic AI use cases in the enterprise domain. 

#### We also demonstrate how the system can be made to scale up with the number of users by deploying a variation of the system via the use on an Azure Kubernetes cluster (AKS) here: manuelbomi/An-Enterprise-Generative-AI-LLM-System-for-Manufacturing-and-Business-Applications-   

#### The system described in this instance was extended from the base Agentic AI system to include Langchain, and monitoring tools such as Prometheus and Grafana.

#### Interested readers can use the system to upload their own pdf files and chat with the system here: https://app.emmanueloyekanluprojects.com 

#### Each connected service can be viewed as a target capability within the enterprise portfolio — one that automates manual tasks, improves user experience, and maintains compliance. In a nutshell, in the opportunities and solution phase, we:

        ◦ Demonstrate integration with existing enterprise apps like Google Drive, Google Calendar, and how to scale up by integrating ERP systems, CRM and other enterprise systems.
		
        ◦ Use the same base Agentic AI system for complex financial/business decision
		
        ◦ Show how it reduces manual effort while ensuring compliance.

  ---

## Phases F–H: Migration, Implementation & Change    🧭
#### This solution is built to be incrementally adopted. An organization might begin with a single use case — event coordination — and then progressively extend the agent to other departments or workflows. 

#### Governance policies and versioning within n8n ensure traceability and compliance with implementation standards. Finally, the use of vector embeddings enables continuous improvement of the knowledge base without retraining models, aligning with Phase H's focus on evolution and adaptability.  

#### In a nutshell, in the migration, implementation and change  phase, we how AI projects can:

        ◦ Start small (one agent for scheduling or knowledge retrieval) → then scale to multiple workflows.
		
        ◦ Governance ensures each step is secure, compliant, and aligned with enterprise standards.
		
        ◦ As business needs evolve, embeddings can be updated without retraining models.
		
        ◦ This matches TOGAF’s principle of continuous improvement, lowering cost of ownership.

----
## Architecture Mapping Diagram
#### Below is a visual representation of the TOGAF ADM Phases & Agentic AI/LLM Workflow Integration —the diagram illustrates the TOGAF Architecture Development Method. 

<img width="1024" height="1536" alt="Image" src="https://github.com/user-attachments/assets/54701ccc-5a93-4c2f-a393-20f70c6a065a" />

#### Each phase corresponds to key stages of architecture creation, governance, migration, and continuous improvement  diagram that illustrates the iterative of the phases, including:

    • Phase A – Architecture Vision: Your proof-of-concept for intelligent enterprise automation, centered on real-time knowledge retrieval using vector search.
	
    • Phase B – Business Architecture: Positioning the AI agent as a business enabler for tasks like calendar automation and RAG-based workflows.
	
    • Phase C – Information Systems (Data & Application): The technical mapping of Pinecone as semantic memory and modular AI nodes as reusable enterprise services.
	
    • Phase D – Technology Architecture: Emphasis on cloud-native deployment, scalability, and enterprise-grade governance via n8n, Docker/Kubernetes.
	
    • Phase E – Opportunities & Solutions: Demonstration of actionable integrations (e.g., Google Calendar) and the blueprint for future ERP/CRM connectors.
	
    • Phases F & G – Migration Planning & Implementation Governance: A low-risk rollout starting with a limited use case and layering governance structures for compliance, traceability, and security.
	
    • Phase H – Architecture Change Management: Continuous adaptability through updating embeddings, supporting agile architecture evolution aligned with business needs.

---



## Why This Architecture Matters  ✅ 
#### This project bridges the gap between AI innovation and enterprise architecture. 

#### By framing the agentic AI and LLM workflows through the lens of TOGAF, it becomes more than a prototype — it becomes a strategic enabler that fits cleanly into existing enterprise roadmaps. 

#### With strong foundations in modularity, governance, and scalability, this approach de-risks AI adoption and makes it ready for enterprise production environments.

    • It translates AI terminologies into enterprise architecture language.
	
    • It shows that your AI agent is not just a toy demo, but a strategic capability that fits into existing enterprise roadmaps.
	
    • It demonstrates scalability and governance, which are always key blockers in enterprise adoption.

--- 

## Conclusion
#### As the project progresses, we shall be updating how each developed components fit the overall business architecture, and how it fits into the overall TOGAF framework



##### Thank you for reading 

---


### **AUTHOR'S BACKGROUND**
### Author's Name:  Emmanuel Oyekanlu
```
Skillset:   I have experience spanning several years in data science, developing scalable enterprise data pipelines,
enterprise solution architecture, architecting enterprise systems data and AI applications,
software and AI solution design and deployments, data engineering, high performance computing (GPU, CUDA), machine learning,
NLP, Agentic-AI and LLM applications as well as deploying scalable solutions (apps) on-prem and in the cloud.

I can be reached through: manuelbomi@yahoo.com

Websites (professional):  http://emmanueloyekanlu.com/
Websites (application):  https://app.emmanueloyekanluprojects.com/
Publications:  https://scholar.google.com/citations?user=S-jTMfkAAAAJ&hl=en
LinkedIn:  https://www.linkedin.com/in/emmanuel-oyekanlu-6ba98616
Github:  https://github.com/manuelbomi

```
[![Icons](https://skillicons.dev/icons?i=aws,azure,gcp,scala,mongodb,redis,cassandra,kafka,anaconda,matlab,nodejs,django,py,c,anaconda,git,github,mysql,docker,kubernetes&theme=dark)](https://skillicons.dev)




	
