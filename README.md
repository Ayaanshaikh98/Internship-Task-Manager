# Internship Management System 🗂️

This repository contains a simple Python-based **Internship Management System** that helps manage interns, assign tasks, collect weekly updates, and provide feedback. It demonstrates the use of basic Python data structures and functions.

## 🔧 Features

- Add new interns with unique IDs.
- Assign tasks with automatic date tracking.
- Submit weekly updates.
- Provide week-wise feedback.
- Generate a complete intern report with tasks, updates, and feedback.

## 🧠 Technologies Used

- Python 3
- `datetime` module

## 📁 Code Overview

```python
# Add an intern
add_interns("i01", "Kundan Bhagat")

# Assign task
assigning_tasks("i01", "Complete Major_project proposal")

# Weekly update
submit_weekly_update("i01", "Finished initial draft of the proposal.")

# Give feedback
give_feedback("i01", 1, "Good start, refine your objectives.")

# Generate report
generate_report("i01")
```

## 📤 Output Snapshot

```
---$$ Internship Report $$---
Intern's name: Kundan Bhagat

Tasks:
 - Complete Major_project proposal (Pending)

Weekly Updates:
 Week 1: Finished initial draft of the proposal.

Feedback:
 Week 1: Good start, refine your objectives.
^------*--------*-----------*--------*-------^
```

## 📌 How to Use

1. Clone this repository.
2. Run the script in a Python environment.
3. Modify or expand functionality as needed for more interns and use cases.

## 📄 License

This project is open-source and available under the [MIT License](LICENSE).

---

### 👤 Author

**Shaikh Ayaan Jameel Ahmad**

Feel free to contribute or connect with me!