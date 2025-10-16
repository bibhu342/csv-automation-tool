🧠 CSV Automation Tool (Python + AI Mock)

A lightweight Python script that reads prompts from a CSV file, generates mock AI responses, and writes them into a new CSV output file.
Includes CLI arguments, timestamped runs, and logging for safe and repeatable automation.

🚀 Features

Read and process input CSVs

Generate mock or AI-based responses

Logging with timestamps

CLI arguments for input/output paths

Optional timestamped output file creation

Error handling for safe runs

🧩 Project Structure
csv-automation-tool/
│
├── ai_responses_from_csv.py
├── prompts.csv
├── sample_output.csv
├── requirements.txt
└── README.md

⚙️ Usage

Run default:
python ai_responses_from_csv.py
Custom input/output:
python ai_responses_from_csv.py --input my_prompts.csv --output results.csv
Timestamped output:
python ai_responses_from_csv.py --timestamped

🧪 Sample Input

prompts.csv
prompt
Hello world
Summarize AI in one line

Output (sample_output.csv)
Prompt,AI Response
Hello world,Mock response for: Hello world
Summarize AI in one line,Mock response for: Summarize AI in one line

🧠 Future Work

Add real AI API integration (OpenAI / LangChain)

Create JSON output option

Add web interface version (Streamlit)

👨‍💻 Author

Bibhudendu Behera
Python & AI Automation Learner
[LinkedIn Profile](https://www.linkedin.com/in/bibhudendu-behera-b5375b5b)
