Genesis
1. Project Title and Description:
Prompt Engineering Lab - AI study Companion
The project is designed to:
- Experiment with Zero-shot, Few-shot, Chain-of-Thought (CoT), self_consistency, prompt_template and meta prompting.
- Improve response accuracy by tuning model parameters.
- Implement automated prompt generation for workflow automation.

2. Installation and setup
i. Clone the repository : git clone https://github.com/genilab-fau/prompt-eng.git prompt-eng
ii. Install Dependencies: pip3 install -r requirements.txt
iii. set up the _config file:
URL_GENERATE=https://chat.hpc.fau.edu/api/chat/completions
API_KEY=eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpZCI6IjE3ZWJmZGI3LWRjYjMtNDM4Ni05ZTQwLTRiNzdmMTM4OGVmNCJ9.nNBzaptzH5-OnJMnLCEbclCmCqMThx5E7_claEeQk_0

3. Usage Instructions:
i. Running the AI Tutor with Zero-Shot Prompting:
python pipeline.py
ii. Running with custom model and settings:
payload = create_payload(
                         target="ollama",
                         model="llama3.2:latest", 
                         prompt=PROMPT, 
                         temperature=1.0, 
                         num_ctx=100, 
                         num_predict=100)

4. Experimentation and Results
We conducted various prompt engineering technique experiments:
i. Zero-shot
ii. Few-shot
iii. Chain-of-Thought (CoT)
iv. self_consistency
v. prompt_template
vi. meta prompting


