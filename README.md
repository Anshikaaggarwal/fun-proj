# 🎓 Student Eligibility Filter for Placement Cells

This project helps **placement cell coordinators** filter eligible students from a single master database instead of repeatedly asking students to fill out forms for each company.  

---

## ✨ Why This Project?
- 📋 Collect student details **once** in a master Excel file.  
- 🏢 For each company → just update the eligibility criteria in the script.  
- ⚡ Get an instant shortlist of eligible students in Excel format.  
- 🚫 No more multiple Google Forms or manual filtering!  

---

## 🛠 Tech Stack
- **Python 3**  
- **pandas** → to handle Excel data  
- **pandasql** → to run SQL queries on DataFrames  
- **openpyxl** → to write Excel output  

---

## 📂 Project Structure
├── master_db.xlsx # Master student database (not included here)
├── student_filter.py # Main script
├── eligible_students.xlsx # Output file (generated after running)

## ▶️ How to Use (Google Colab)

You can use this project directly in Google Colab without installing anything:  
👉 [Open Colab Notebook](https://colab.research.google.com/drive/1wOap4MXSRjxNTME18RuvjFRfqcpVHEPa?usp=sharing)

### Steps:
1. Run all three sections in the Colab notebook.  
2. Upload your Excel file (`master_db.xlsx`) – this is the master database of all students.  
3. Edit the SQL query inside the notebook to match the company’s eligibility criteria.  
4. Run the filter → download the generated `eligible_students.xlsx`.  

