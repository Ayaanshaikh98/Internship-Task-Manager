# Internship-Task-Manager
The need for a lightweight and efficient tool to manage intern activities, such as task assignments, weekly progress, and mentor feedback, is common in educational and training institutions. Manual methods or spreadsheets often lead to inefficiencies.
 2. Tools & Technologies
Component Description
Language Python 3.x
Modules Used datetime (built-in)
Data Structures Dictionaries and Lists
IDE Any Python-supported IDE (e.g., VS Code, IDLE)
Platform Cross-platform (runs in any terminal)
 3. Objectives
To manage intern records using Python.
 To assign and monitor task completion.
 To collect weekly progress reports.
 To provide week-wise feedback.
 To build a minimal yet functional CLI-based tracking system.
🗂 4. Functional Overview
 Features:
• Register new interns with ID and name
• Assign tasks and track their status
• Submit weekly progress updates
• Give personalized weekly feedback
• Generate final reports summarizing intern activities
 5. Working Mechanism
 Step-by-step Workflow:
1. Intern Registration:
The add_interns() function stores intern details in a dictionary.
2. Task Assignment:
The assigning_tasks() function adds a task with status and date to the intern’s record.
3. Weekly Update:
The submit_weekly_update() function allows interns to log weekly work done.
4. Feedback Entry:
The give_feedback() function stores feedback linked to a specific week.
5. Report Generation:
The generate_report() function prints tasks, updates, and feedback in a clean format.
 6. Code Overview
import datetime
interns = {}
tasks = {}
updates = {}
feedback = {}
 Core Functions
def add_interns(intern_id, name):
 ...
def assigning_tasks(intern_id, task_description):
 ...
def submit_weekly_update(intern_id, update_text):
 ...
def give_feedback(intern_id, week, feedback_text):
 ...
def generate_report(intern_id):
 ...
 7. Output Example
 Sample Output of Report:
---$$ Internship Report $$---
Intern's name: KUNDAN BHAGAT
Tasks:
- Complete Major_project proposal (Pending)
Weekly Updates:
Week 1: Finished initial draft of the proposal.
Feedback:
Week 1: Good start, refine your objectives.
^------*--------*-----------*--------*-------^
 10. Learnings & Outcomes
 Learned structured data management using Python dictionaries and lists.
 Understood function-driven modular programming.
 Practiced organizing and generating human-readable reports.
 11. Conclusion
The Internship Task Manager successfully demonstrates basic yet effective management of
intern records using Python. The project promotes understanding of data organization, modular
coding, and real-time reporting using simple logic without reliance on external libraries.
 12. References
 Stack Overflow (for syntax clarifications)
 ChatGPT (for co
