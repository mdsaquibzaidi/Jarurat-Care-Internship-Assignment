# 📊 Lead Generation Automation (Python Project)

## 👨‍💻 About the Project

This project is a simple lead generation automation script built using Python.
The goal is to collect data from a public website, clean it, and store it in an Excel file for easy use.

I created this as part of an internship assignment to show basic automation and data handling skills.

---

## 🔗 Google Colab Link

You can view and run the full project here:
https://colab.research.google.com/drive/1VxJpsbeTJ1z4uxamvG3bSCNKcNQBIzfF?usp=sharing

---

## ⚙️ Tools & Technologies Used

* Python
* requests (for fetching website data)
* BeautifulSoup (for scraping HTML content)
* pandas (for data cleaning and structuring)
* openpyxl (for saving Excel files)

---

## 🚀 Features

* Scrapes data from a public website
* Collects key fields:

  * Name
  * Website
  * Location
* Handles missing values
* Removes duplicate entries
* Generates sample email IDs (bonus feature)
* Saves final data into an Excel file

---

## 🧠 How It Works

1. The script sends a request to the website.
2. It extracts data like names using BeautifulSoup.
3. The data is stored in a pandas DataFrame.
4. Cleaning is performed (duplicates removed, null values handled).
5. Email IDs are generated based on name and domain.
6. The final dataset is exported to an Excel file.

---

## 📁 Output

* The output is saved as: `leads.xlsx`
* It contains 100+ entries collected automatically

---

## 📌 Note

* The website used is a demo/public site for learning scraping.
* This same approach can be applied to real business or NGO directories.

---

## 🎯 What I Learned

* Basics of web scraping
* Working with real-world data
* Data cleaning using pandas
* Automating repetitive tasks
* Exporting structured data

---

## 🙌 Conclusion

This project helped me understand how automation can simplify lead generation tasks.
I am still learning and improving my Python skills, and this is one of my practical projects.

---
