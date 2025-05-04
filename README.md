# Netflix-Content-Analysis
# <p align="center">Netflix Data Engineering Pipeline </p>
# <p align="center">![Pic](https://i.ibb.co/Q81WwRN/92399716.jpg)</p>

🔧 Tools & Technologies
Python (Pandas) – Data cleaning and transformation

AWS S3 – Cloud storage for processed data

📊 Dataset
Source: Netflix Titles Dataset (Kaggle)

Size: ~8,000+ rows

Columns include: title, type, genre, release_year, rating, country, date_added, etc.


🔄 ETL Pipeline Workflow

CSV File (Raw Data)
      ↓
Python (Data Cleaning with Pandas)
      ↓
CSV File (Cleaned Data)
      ↓
AWS S3 (Cloud Storage for Scalability)


⚙️ Steps Performed
Extract: Loaded raw CSV data from the local source

Transform:

Handled missing values

Converted date_added to datetime format

Standardized column formats

Load:

Exported cleaned data as CSV

Uploaded to AWS S3 for persistent cloud storage




👨‍💻 Author
Krishna Wankhade – Aspiring Data Engineer

[LinkedIn](www.linkedin.com/in/krishnawankhade)



