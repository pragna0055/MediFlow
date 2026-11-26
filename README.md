MediFlow AI
Project Overview
An AI-powered SmartHealthAI system that automates patient symptom
collection, emergency detection, doctor recommendation, and health report
generation using n8n as the automation engine.
It helps patients enter symptoms, checks emergency conditions, suggests the
right doctor, and sends patient health reports through Gmail for communication
and alert purposes.
Problem Statement
Basic health guidance is often manual and slow. Patients may not know which
doctor to consult based on symptoms like fever, cough, chest pain, nausea, or
breathing difficulty.
Emergency symptoms can be missed, and appointment handling may require
manual communication. This creates delays in patient support and doctor
recommendation.
Solution Built
A no-code AI-powered healthcare automation system that:
Collects patient symptoms through chat or webhook input
Uses n8n workflow to process symptom data
Detects emergency cases like chest pain, difficulty breathing, or fainting
Recommends suitable doctors based on symptoms
Sends structured output such as risk level, doctor type, and advice
Sends alerts and patient health reports using Gmail
Supports frontend connection through webhook
Reduces manual effort through automated healthcare workflows
MediFlow Workflow Sequence
Day / Event System Action Output / Content
MediFlow AI 1
Patient Input
Patient enters
symptoms
Symptoms received in
workflow
Webhook / Chat Trigger n8n workflow starts JSON input loaded
AI Agent Processing Symptoms analyzed Risk level generated
Emergency Check
Checks chest pain,
breathing issue,
fainting
Emergency: Yes / No
Doctor
Recommendation
Chooses correct doctor
General Physician /
Cardiologist /
Gastroenterologist et
Alert Flow
Optional Gmail
notification
Patient details sent
Tech Stack
Tool Purpose
n8n Cloud
Workflow automation
engine
Webhook
Connect frontend with
n8n
AI Agent / openRouter
Symptom analysis and
doctor
recommendation
Gmail
Sending alerts or
patient details
VS Code Frontend development
HTML / CSS / JS
Patient symptom input
UI
Workflow Architecture
Patient Symptom Input (Frontend / Webhook)
↓
Webhook Trigger (n8n)
↓
Edit Fields & Data Processing
MediFlow AI 2
↓
Symptom Checker Agent
↓
Risk Classifier Agent
↓
Emergency Alert Agent
↓
Doctor Recommendation Agent
↓
Report Analyzer Agent
↓
Medicine Reminder Agent
↓
Diet & Nutrition Agent
↓
Fitness Agent
↓
Mental Health Agent
↓
AI Agent (Final Health Summary Generation)
↓
Gmail Integration (Send Health Report)
↓
Respond to Webhook (Frontend Response)
MediFlow AI 3
Input Fields
Patient Name
Email Address
Symptoms
Output — Sample System Responses
Sample Doctor Recommendation
Symptoms : fever and cold
Here is the response:
Final Health Summary:
The patient has a mild fever and cold symptoms.
Emergency Status:
Emergency: No
Recommended Doctor: General Physician
Medicine Reminder: Rest and hydration are essential to recovering from a fever
and cold.
Diet & Nutrition: Drink plenty of warm fluids and follow a balanced diet.
Fitness Advice: Avoid strenuous activities until the patient fully recovers.
Mental Wellness: The patient should focus on stress-reducing activities and
get enough sleep.
Impact
Metric Impact
MediFlow AI 4
Symptom collection
Automated through
chat/webhook
Doctor
recommendation
Faster and structured
Emergency detection
Helps identify high-risk
cases
Manual work
Reduced through n8n
workflow
Scalability Scalability
Enhancements Planned
Better frontend UI for patients
WhatsApp integration for health alerts
Hospital database connection
Doctor availability checking
Patient report generation
Voice-based symptom input
Medicine reminder workflow
Admin dashboard for doctors
How to Use
Enter patient name, email address, and symptoms in the frontend interface.
The data is sent to the n8n webhook automatically.
AI agents analyze the symptoms and identify the risk level.
Emergency conditions are checked for critical symptoms.
The system generates doctor recommendations and health guidance.
A complete health report is created automatically.
The final report is sent to the patient through Gmail.
Result:
MediFlow AI 5
With Input and output :
MediFlow AI 6
Gmail :
pragna_coverletter
MediFlow AI 7