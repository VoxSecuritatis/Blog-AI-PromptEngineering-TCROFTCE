# Blog:  TCROFTCE Prompt Engineering
2025-10-04

---

This prompt template was originally developed and explained in the book "The Prompt Recipe:  A Practical Guide to Prompt Engineering" by Alden Vale and Ahmed Bouchentouf.  
This is an excellent reference and comes highly recommended to better understand prompt engineering.

> Vale, A., & Bouchentouf, A. (2025, April 6). *The Prompt Recipe: A Practical Guide to Prompt Engineering and AI Interaction.*  
> Retrieved from [https://a.co/d/b85p4fm](https://a.co/d/b85p4fm)

---

## Instructions for Use  
1. Build your prompt in a text editor (e.g., Notepad), then paste it into the LLM prompt window.
2. Answer clarifying questions asked by the LLM to better clarify your prompt objectives; not required, but will make responses more accurate.
3. Keep frequently used prompts in a "prompt library" in a notebook application, e.g., OneNote, Obisian, Evernote, etc.
4. See the bottom for the short TCROFTCE tempate.

---

### **CROFTC Framework**

The *key* fields to send the LLM are **CROFTC** sections for the best possible response from the model.  
**T** and **E** are optional but recommended to help reference the prompt and guide the LLM’s context understanding.  
If a CROFTC field is left blank, the model may produce **hallucinations** or slightly inaccurate information. 

| **Field** | **Purpose** | **Description / Example** |
|------------|--------------|----------------------------|
| **T — Title** | Descriptive name for the prompt | Useful for later reference in the chat (e.g., *Vendor Risk Brainstorming Prompt*). |
| **C — Context** | Provide background and situational details | Example: “I am a cybersecurity analyst working in enterprise risk management to determine potential third-party security gaps.” |
| **R — Role** | Assign a role to the AI | Example: “You are a cybersecurity strategist with expertise in vendor risk and governance.” |
| **O — Objective** | Clearly state what you want the AI to achieve or produce | Example: “Generate a list of AI/ML project ideas for improving vendor risk management.” |
| **F — Format** | Define output structure | Examples: *bullet points, table, numbered list, step-by-step, markdown, Python code.* |
| **T — Tone** | Specify style or tone | Examples: *formal, analytical, persuasive, professional.* |
| **C — Constraints** | List limitations or rules | Examples: *word count limits, avoid jargon, focus on regulated industries, no emojis.* |
| **E — Examples** | Provide sample inputs or outputs *(optional but valuable)* | Example: *Include a short example of the desired structure or tone to guide the AI.* |

---

### **Acknowledgment**
Always include a line like this at the end of your prompt:  
> *Acknowledge your understanding of the prompt and ask any follow-up questions for clarification.*

This allows the LLM to confirm understanding before generating a response — improving accuracy and alignment.

---

## Example Prompt — Cybersecurity Professional Brainstorming Vendor Risk Management

**T — Title:**  
Brainstorming Vendor Risk Management Ideas  

**C — Context:**  
I am a cybersecurity professional working at a large enterprise. My task is to explore potential AI/ML project ideas for enhancing vendor risk management processes. These ideas will be presented to executive management as part of a strategic innovation initiative.  

**R — Role:**  
You are an experienced cybersecurity strategist and AI/ML innovation consultant with expertise in vendor risk management and enterprise security operations.  

**O — Objective:**  
Brainstorm a list of innovative AI/ML projects that could improve vendor risk assessments, monitoring, and governance. The concepts should be practical, high-impact, and aligned with enterprise security priorities.  

**F — Format:**  
Provide a numbered list of 10–12 project ideas. For each idea, include:  
- **Project Name** (short and descriptive)  
- **Description** (2–3 sentences explaining the concept)  
- **Potential Business Value** (1–2 sentences on ROI, efficiency, or risk reduction)  

**T — Tone:**  
Professional, forward-looking, and persuasive — suitable for presentation to senior executives.  

**C — Constraints:**  
- Focus on realistic AI/ML applications feasible within 12–24 months.  
- Avoid overly technical jargon so non-technical executives can understand.  
- Prioritize solutions with measurable security and compliance benefits.  

**E — Examples:**  
Example of desired output style:  
- **Predictive Vendor Risk Scoring** — Use AI models to predict vendor risk based on historical incidents, compliance certifications, and financial health indicators.  
  *Value:* Improves risk forecasting accuracy and prioritizes vendor oversight efforts.  

Acknowledge your understanding of the prompt and ask any follow-up questions for clarification.

---

## TCROFTCE Template Prompt

Title: 
Context: 
Role: 
Objective: 
Format: 
Tone: 
Constraints: 
Examples:   

Acknowledge your understanding of the prompt and ask any follow-up questions for clarification.

---



