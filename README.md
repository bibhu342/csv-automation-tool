# 🧠 CSV Automation Tool (Python + AI Mock)

A lightweight and extensible Python script for automating prompt-response workflows using CSV files. Effortlessly read prompts from a CSV, generate mock (or real AI) responses, and export results—complete with logging and safe error handling.

---

## 🚀 Features

- **Easy CSV Processing**: Reads input prompts from CSV and writes responses to a new CSV file.
- **Mock & AI Responses**: Uses mock responses by default; ready for real AI API integration.
- **Robust Logging**: Detailed logs with timestamps ensure transparency and traceability.
- **Flexible CLI**: Command-line arguments for custom input/output paths and configurations.
- **Timestamped Outputs**: Option to create uniquely timestamped output files for each run.
- **Safe & Repeatable**: Comprehensive error handling for reliable automation.

---

## 🗂️ Project Structure

```
csv-automation-tool/
│
├── ai_responses_from_csv.py      # Main script
├── prompts.csv                   # Sample input prompts
├── sample_output.csv             # Example output
├── requirements.txt              # Dependencies
└── README.md                     # Project documentation
```

---

## ⚙️ Usage

### Basic Run

```bash
python ai_responses_from_csv.py
```

### Custom Input/Output

```bash
python ai_responses_from_csv.py --input my_prompts.csv --output results.csv
```

### Timestamped Output

```bash
python ai_responses_from_csv.py --timestamped
```

---

## 🧪 Sample Input/Output

### Input (`prompts.csv`)

| prompt                       |
|------------------------------|
| Hello world                  |
| Summarize AI in one line     |

### Output (`sample_output.csv`)

| Prompt                     | AI Response                              |
|----------------------------|------------------------------------------|
| Hello world                | Mock response for: Hello world           |
| Summarize AI in one line   | Mock response for: Summarize AI in one line |

---

## 🔮 Future Enhancements

- Integrate with real AI APIs (OpenAI, LangChain, etc.)
- Add JSON output support
- Develop a web interface (e.g., using Streamlit)

---

## 👤 Author

**Bibhudendu Behera**  
Python & AI Automation Enthusiast  
[LinkedIn Profile](https://www.linkedin.com/in/bibhudendu-behera-b5375b5b)

---
