# Blog:  TTCROFTCE Prompt Engineering
Published: 2025-10-04 | Updated: 2025-10-05

---

This prompt template is a variation of the template which was originally developed and explained in the book "The Prompt Recipe:  A Practical Guide to Prompt Engineering" by Alden Vale and Ahmed Bouchentouf.  
This is an excellent reference and comes highly recommended to better understand prompt engineering.

> Vale, A., & Bouchentouf, A. (2025, April 6). *The Prompt Recipe: A Practical Guide to Prompt Engineering and AI Interaction.*  
> Retrieved from [https://a.co/d/b85p4fm](https://a.co/d/b85p4fm)

---

## Instructions for Use  
1. Build your prompt in a text editor (e.g., Notepad), then paste it into the LLM prompt window.
2. Answer 5W and 1H questions as input to your prompt.
3. Answer the follow up questions asked by the LLM to better clarify your prompt objectives; not required, but will make responses more accurate.
4. Record and keep frequently used prompts in a "prompt library" in a notebook application, e.g., OneNote, Obisian, Evernote, etc.
5. See the bottom for the short TCROFTCE tempate.

---

The original CROFTC template outlined in The Prompt Recipe, was modified to add the following enrichments:

Title (T), Temperature (T), ..., Examples (E)

I find that adding a Title allows me to refer to the original prompt later in the dialog with the LLM (sometimes the LLM needs to be reminded about the original intent, this reminds it).
Temperature is an important setting depending on what your end gaol.
Examples is a key feature to ensure you get the output or reference to provide context.  The more detail like this the closer to your vision.

---

### **TTCROFTCE Framework**

To clarify your prompt, before implementing the TCROFTCE framework, answer the 5W and 1H (who, what, when, where, why, and how) critical thinking questions:

| **Question** | **Purpose in Prompt Building** | **Example (IT Context)** |
|---------------|--------------------------------|--------------------------|
| **Who?** | Defines *the audience or role* — who is involved or impacted. | “You are an IT operations manager preparing a report for the CIO.” |
| **What?** | Specifies *the task or objective* — what needs to be done. | “Identify automation opportunities for improving system uptime.” |
| **When?** | Establishes *the timeline or timeframe* for relevance. | “Focus on optimization strategies that can be implemented within the next 6 months.” |
| **Where?** | Sets *the scope or environment* where the task applies. | “Consider a hybrid IT infrastructure spanning on-premise and cloud systems.” |
| **Why?** | Clarifies *the purpose or goal* — why this task matters. | “The goal is to reduce operational costs while improving reliability and performance.” |
| **How?** | Describes *the approach or format* the response should follow. | “Provide the output as a numbered list with short explanations and implementation steps.  Provide the output as factual or creative.” |

The *key* fields to send the LLM are **CROFTC** sections for the best possible response from the model.  
**T** and **E** are optional but recommended to help reference the prompt and guide the LLM’s context understanding.  
If a CROFTC field is left blank, the model may produce **hallucinations** or slightly inaccurate information. 

| **Field** | **Purpose** | **Description / Example** |
|------------|--------------|----------------------------|
| **T — Title** | Descriptive name for the prompt *(optional but valuable)* | Useful for later reference in the chat (e.g., *Vendor Risk Brainstorming Prompt*). |
| **T — Temperature** | Changes the creativitiy, 0.1-1.5 (lower more deterministic, higher more creative) | Defined by use case |
| **C — Context** | Provide background and situational details | Example: “I am a cybersecurity analyst working in enterprise risk management to determine potential third-party security gaps.” |
| **R — Role** | Assign a role to the AI | Example: “You are a cybersecurity strategist with expertise in vendor risk and governance.” |
| **O — Objective** | Clearly state what you want the AI to achieve or produce | Example: “Generate a list of AI/ML project ideas for improving vendor risk management.” |
| **F — Format** | Define output structure | Examples: *bullet points, table, numbered list, step-by-step, markdown, Python code.* |
| **T — Tone** | Specify style or tone | Examples: *formal, analytical, persuasive, professional.* |
| **C — Constraints** | List limitations or rules | Examples: *word count limits, avoid jargon, focus on regulated industries, no emojis.* |
| **E — Examples** | Provide sample inputs or outputs *(optional but valuable)* | Example: *Include a short example of the desired structure or tone to guide the AI.* |

Always include a line like this at the end of your prompt:  
> *Acknowledge your understanding of the prompt and ask any follow-up questions for clarification.*

This allows the LLM to confirm understanding before generating a response — improving accuracy and alignment.

---

## Example Prompt — Cybersecurity Professional Brainstorming Vendor Risk Management

**T — Title:**  
Brainstorming Vendor Risk Management Ideas  

**T - Temperature**<br>
Tempearture=1.0

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

## TTCROFTCE Prompt Template

> Copy and paste the following into a text editor to build out the prompt, after creating prompt, copy and paste it into the LLM prompt input text box.

Who? <br>
What? <br>
When? <br>
Where? <br>
Why? <br>
How? <br>

----- START PROMPT

Title: <br>
Temperature=<br>
Context: <br> 
Role: <br> 
Objective: <br> 
Format: <br> 
Tone: <br> 
Constraints: <br>
Examples:  <br> 

Acknowledge your understanding of the prompt and ask any follow-up questions for clarification.

----- END PROMPT

---

© 2025 Brock Frary. All rights reserved.

