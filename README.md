# DevOps Final Project – Semester 1

## Overview
This project demonstrates a complete CI pipeline using Jenkins, GitHub, and scripting.  
The pipeline runs on a Master/Agent setup, executes a parameterized script, generates HTML output, and archives logs.

---

## Technologies Used
- Jenkins (Master + Agent)
- GitHub
- Visual Studio
- [Your Script Language Here]

---

## Repository Structure
```
/project-folder
  ├── script.[ext]
  ├── Jenkinsfile
  ├── output.html
  ├── log.txt
  ├── screenshots/
  └── README.md
```

---

## How to Run the Script Manually
Explain how to run your script locally:

```
python script.py --name John --score 90 --operation average
```

---

## Jenkins Job Instructions

### 1. Parameters
List your parameters:

| Name | Type | Description |
|------|------|-------------|
| runOn | Choice | Master/Agent |
| studentName | String | Example parameter |
| score | Number | Example parameter |

---

### 2. Pipeline Stages
Explain each stage:

- **Checkout** – Pulls code from GitHub  
- **Validate Parameters** – Ensures input is correct  
- **Run Script** – Executes the script on Master/Agent  
- **Generate HTML** – Creates output.html  
- **Archive Artifacts** – Saves HTML + log  

---

## Logging
The script generates a log file containing:

- Timestamp  
- Input parameters  
- Steps performed  
- Errors  
- Final result  

Example:

```
[2026-01-04 10:32] Starting script
[2026-01-04 10:32] Parameters: name=John, score=90
[2026-01-04 10:32] Calculated average: 90
[2026-01-04 10:32] Finished successfully
```

---

## Screenshots
All required screenshots are located in the `screenshots/` folder:

- Jenkins job configuration  
- Parameter input  
- Pipeline execution  
- Console output  
- HTML result  
- Log file  
- GitHub repository  
- Master/Agent configuration  

---

## Example Output
Include a sample HTML output and log file.

---

## Conclusion
Summarize what you learned and any challenges you solved.

---

## Bonus (If Implemented)
- - Notifications  
- Charts  
