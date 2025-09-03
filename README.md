# Ex-4.-Scenario-Based-Report-Development-Utilizing-Diverse-Prompting-Techniques
Objective: The goal of this experiment is to design and develop an AI-powered chatbot that can handle customer inquiries, provide support, and improve customer experience in a retail environment. Create prompts using various AI prompting techniques to guide your experiment, data collection, analysis, and report creation.

## Aim: 
To evaluate how diverse AI prompting techniques can be applied to create an effective scenario-based customer service chatbot for a retail environment, and to compare the quality of responses generated through these different prompting methods.

## Algorithm: 

Step 1: Identify Use Cases
Select common healthcare virtual assistant scenarios:

Symptom Inquiry

Appointment Scheduling

Prescription Refill

Health Tips Guidance

Step 2: Define Prompting Techniques
Choose diverse prompting strategies to test:

Zero-shot prompting

One-shot prompting

Few-shot prompting

Role-based prompting

Persona-driven prompting

Instruction-based prompting

Chain-of-thought prompting

Socratic prompting

Step 3: Design Prompts
Frame patient queries for each scenario and apply every prompting technique.

Step 4: Execute Prompts
Use AI models (ChatGPT, Claude, Bard, Cohere Command, Meta AI) to generate responses.

Step 5: Collect Outputs
Document responses produced by each prompting style.

Step 6: Analyze Responses
Evaluate based on:

Clarity

Accuracy

Empathy

Personalization

Effectiveness

Step 7: Compare Techniques
Identify strengths/weaknesses of each prompting style.

Step 8: Conclude
Recommend the best hybrid approach for healthcare chatbots.

## Prompts, Outputs & Results:

## Scenario 1: Symptom Inquiry

Patient Query: “I have a sore throat and mild fever. What could it be?”

## (a) Zero-shot Prompting
Prompt: “Answer the patient’s question about their symptoms.”
Output: “A sore throat and fever may be signs of an infection. You should consult a doctor if symptoms persist.”
Result: Safe but generic; lacks detail.

## (b) Few-shot Prompting
Prompt: Q: “I have a headache and cough.” A: “It may be a common cold, but see a doctor if severe.”
Q: “I feel chest pain when breathing.” A: “This can be serious; seek urgent medical care.”
Q: “I have a sore throat and mild fever.”
Output: “It may be a throat infection or cold. Drink warm fluids and rest, but see a doctor if symptoms worsen.”
Result: Contextual and reassuring.

## (c) Role-based Prompting
Prompt: “You are a licensed nurse. Provide guidance for sore throat and fever symptoms.”
Output: “Your symptoms may indicate a mild viral infection. Stay hydrated, rest, and monitor your temperature. If the fever rises or persists, consult a healthcare professional.”
Result: Empathetic and practical; trustworthy tone.

## Scenario 2: Appointment Scheduling

Patient Query: “Can I book a doctor’s appointment for tomorrow at 10 AM?”

## (a) One-shot Prompting
Prompt: “Example: If a patient asks for an appointment at 2 PM, respond: ‘Yes, I have booked your appointment for 2 PM.’ Now answer: Can I book for tomorrow at 10 AM?”
Output: “Yes, your appointment has been scheduled for tomorrow at 10 AM.”
Result: Quick and clear but assumes availability.

## (b) Instruction-based Prompting
Prompt: “Check availability before confirming the appointment.”
Output: “Let me check availability… Yes, the 10 AM slot is open tomorrow. Would you like me to confirm the booking?”
Result: More natural and safe; doesn’t assume without verification.

## (c) Persona-driven Prompting
Prompt: “Act as a friendly hospital receptionist and schedule the appointment.”
Output: “Of course! Let me see… Yes, we have an opening at 10 AM tomorrow. Shall I go ahead and book it for you?”
Result: Polite, engaging, and customer-centric.

## Scenario 3: Prescription Refill

Patient Query: “Can I get a refill for my blood pressure medicine?”

## (a) Zero-shot Prompting
Prompt: “Respond to the patient’s request about prescription refill.”
Output: “Please contact your pharmacy or doctor for refills of prescription medicine.”
Result: Generic and safe, but not helpful enough.

## (b) Role-based Prompting
Prompt: “You are a virtual healthcare assistant. Provide safe advice for prescription refills.”
Output: “For prescription medicines like blood pressure tablets, refills must be authorized by your doctor or pharmacy. Would you like me to connect you with the prescription team?”
Result: Clear, safe, and helpful next step.

## (c) Socratic Prompting
Prompt: “Guide the patient with questions about their prescription refill request.”
Output: “When was your last refill? Has your doctor authorized automatic refills? Is your prescription still valid? If yes, you may contact the pharmacy to process it.”
Result: Encourages self-check but feels indirect.

## Scenario 4: Health Tips Guidance

Patient Query: “How can I improve my sleep quality?”

## (a) Instruction-based Prompting
Prompt: “Provide 3 clear, evidence-based tips for better sleep.”
Output: “1. Maintain a consistent bedtime. 2. Avoid caffeine before sleep. 3. Keep your bedroom dark and quiet.”
Result: Simple and actionable.

## (b) Chain-of-Thought Prompting
Prompt: “Think step by step and give structured advice for sleep improvement.”
Output: “Good sleep depends on habits. First, set a consistent schedule. Second, reduce screen time an hour before bed. Third, avoid caffeine late in the day. Finally, create a dark, quiet environment. Together, these steps improve sleep quality.”
Result: Logical, structured, and more explanatory.

## (c) Persona-driven Prompting
Prompt: “Act as a wellness coach and give personalized sleep tips.”
Output: “Great question! Try setting a bedtime routine, like reading or meditation. Also, avoid coffee after 5 PM and make your bedroom cozy and quiet. With these small changes, your sleep should improve!”
Result: Friendly, motivational, and human-like.

Analysis of Results

Zero-shot prompting: Safe, functional, but often generic.

One-shot & few-shot prompting: Improved clarity and natural flow by learning from examples.

Role-based & persona-driven prompting: Added empathy, trust, and engagement.

Instruction-based prompting: Great for concise, factual responses.

Chain-of-thought prompting: Best for structured problem-solving and logical explanations.

Socratic prompting: Encouraged self-assessment but felt less convenient.

## Conclusion

For a healthcare virtual assistant, the most effective approach is a hybrid strategy:

Few-shot prompting for accuracy and contextual understanding.

Role-based prompting for empathy and trustworthiness.

Chain-of-thought prompting for structured guidance in troubleshooting and health tips.

This blend ensures responses are safe, informative, empathetic, and customer-friendly, improving patient trust and satisfaction.

## Result:

The results show that **few-shot prompting ensures accuracy**, **role-based prompting adds empathy**, and **chain-of-thought prompting supports structured problem-solving** — making a **hybrid approach the most effective** for healthcare chatbots.

