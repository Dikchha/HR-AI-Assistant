#  HR AI Assistant – Intelligent Automation using UiPath

This project presents an **AI-powered HR automation system** built using UiPath Agentic AI.  
It automates the complete lifecycle of HR email handling — from **classification and data extraction to decision-making and response generation**.The solution demonstrates how **AI + RPA + Excel-based structured data** can be combined to create efficient, scalable, and business-ready workflows.

---

##  Overview

Manual HR email processing is time-consuming and inconsistent. This system solves that by introducing:

- Automated email classification  
- Structured data extraction from unstructured inputs  
- Excel-based data lookup for decision-making  
- Human-in-the-loop approval for validation  
- AI-generated professional responses  

---

##  Objectives

- Reduce manual effort in HR operations  
- Enable **data-backed decision-making**  
- Improve response consistency and speed  
- Build a scalable and modular automation solution  

---

##  System Architecture

The solution is designed using multiple AI agents working together:

### 1. HR Helpdesk Processor
- Captures incoming emails  
- Extracts sender, subject, and body  
- Prepares data for further processing  

---

### 2. Request Category Agent
- Classifies emails into categories:
  - Leave Request  
  - HR Policy Query  
  - Expense Query  
  - Other  
- Helps in routing and applying correct business logic  

---

### 3. Data Extraction Agent
- Extracts important fields like:
  - Leave date  
  - Leave balance  
- Connects with an **Excel data source** to fetch employee-specific information  
- Performs data mapping and transformation  
- Converts unstructured email content into structured format  

---

### 4. HR Approval Application
- Uses UiPath Action Center  
- Allows human validation before final decision  
- Ensures accuracy and business compliance  

---

### 5. Mail Response Agent
- Generates response based on:
  - Category  
  - Extracted data  
  - Business rules  
- Ensures professional HR tone  

---

### 6. Send Response
- Automatically sends the final email  
- Completes the end-to-end workflow  

---

##  Workflow

1. Email is received  
2. AI classifies the request  
3. Data is extracted and matched with Excel records  
4. Decision is reviewed by HR 
5. Response is generated using AI  
6. Final email is sent  

---

##  Business Logic

- Leave approval depends on **available leave balance (Excel data)**  
- Different categories trigger different response logic  
- Human approval ensures control and reliability  
- Structured rules reduce errors and improve consistency  

---

##  Technologies Used

- UiPath Studio (Agentic AI)  
- UiPath Action Center  
- Large Language Models (LLMs)  
- Robotic Process Automation (RPA)  
- JSON (for structured data handling)  
- Microsoft Excel (as backend data source)  

---

##  Sample Flow

### Input
Employee requests leave via email  

### Process
- Classified as *Leave Request*  
- Leave balance fetched from Excel  
- Approval decision applied  

### Output

**Subject:** Leave Request Approval  

**Body:**

Dear Employee,  

Your leave request has been approved based on your available leave balance.  

Best Regards,  
HR Team  

---

##  Key Highlights

- End-to-end **automation solution design**  
- Strong use of **data extraction and transformation**  
- Excel integration for real-time decision-making  
- Combination of **AI + RPA + Human validation**  
- Clean, modular, and scalable architecture  

---

##  Requirements

- UiPath Studio  
- UiPath Orchestrator  
- Action Center access  
- Microsoft Excel (for employee data)  
- Internet connection (for AI model)  

---

##  Note for Users

- Ensure agents are properly configured before running  
- Verify extracted data before approval  
- Keep Excel data updated for accurate decisions  
- Review generated responses before sending  

---

##  Conclusion

This project showcases how **AI-driven automation and data integration** can transform traditional HR processes.

It highlights a strong combination of:
- **Automation consulting skills**
- **Data analysis capabilities**
- **Practical implementation using industry tools**

---