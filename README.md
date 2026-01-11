📌 Multi-Agent Career Assistant (5-Agent System)

This project is a multi-agent career assistant built using FastAPI, Anthropic Claude, and SerpAPI.
It processes a user’s resume and generates end-to-end career guidance using five fully independent AI agents, each handling a specific task.

<img width="962" height="643" alt="image" src="https://github.com/user-attachments/assets/dd9067aa-43c8-4d54-9739-19f85528d633" />
<img width="962" height="642" alt="image" src="https://github.com/user-attachments/assets/de421b9c-4f26-4e4e-b28d-478531f59fa8" />
<img width="972" height="513" alt="image" src="https://github.com/user-attachments/assets/10c2c5ac-9165-4b78-b0fa-b84b8fda1cef" />
<img width="1080" height="572" alt="image" src="https://github.com/user-attachments/assets/f18ae282-bb7b-4fdf-8a39-37854bd6130c" />


🔧 Agents Included

Resume Agent
Extracts text from PDF resumes and identifies the most likely job role.

Job-Match Agent
Searches real, recent job listings using SerpAPI Google Jobs for any profession (tech, sales, nursing, teaching, labor, etc.).

Tailor-Agent
Generates a customized, job-specific rewritten version of the resume.

Interview-Agent
Produces tailored interview questions and preparation notes based on the selected job.

Project-Agent
Suggests portfolio projects relevant to the job role for strengthening applications.

🚀 Key Features

Works for any job role, not just tech.

Provides real job listings, not hard-coded or fake ones.

Clean modular architecture → easy to deploy, extend, or convert into A2A agents.

Ready for local testing and cloud deployment (Linode/NEST/Nanda).
