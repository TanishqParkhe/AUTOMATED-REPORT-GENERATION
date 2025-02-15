# AUTOMATED-REPORT-GENERATION

COMPANY: CODTECH IT SOLUTIONS

NAME: TANISHQ PARKHE

INTERN ID: CT08ROX

DOMAIN: PYTHON

DURATION: 4 WEEKS

MENTOR: NEELA SANTOSH

# OVERVIEW OF THE PROJECT

This Python script is designed to read, analyze, and generate a report from a dataset stored in a CSV file. It performs statistical computations on numerical data and presents the findings in a structured PDF document. The script utilizes essential Python libraries such as `csv` for data handling, `statistics` for numerical computations, and `reportlab` for PDF generation.

### **Purpose of the Script**
The primary goal of this script is to automate the process of analyzing numerical datasets and presenting the insights in a professional, readable format. This is particularly useful for businesses, researchers, and analysts who need quick insights from structured data.

### **Key Functionalities**
1. **Creating a Sample CSV File**  
   The script begins by generating a sample CSV file (`data.csv`) with predefined data. The file consists of three columns: `Category`, `Sales`, and `Profit`. This ensures that users have a working dataset to test the script without requiring an external file.

2. **Reading Data from CSV**  
   The script reads data from the CSV file and organizes it into a dictionary, where column headers serve as keys and corresponding values are stored in lists. It handles missing or non-numeric data by skipping them, ensuring that only valid numerical values are processed.

3. **Analyzing the Data**  
   The script computes essential statistical metrics for each numerical column, including:
   - **Count**: The number of valid entries in the column.
   - **Mean**: The average value of the column.
   - **Median**: The middle value when the data is sorted.
   - **Standard Deviation**: A measure of data variability.

4. **Generating a PDF Report**  
   The `reportlab` library is used to create a well-formatted PDF file (`report.pdf`) that presents the analysis results. The report includes:
   - A title indicating that it is a data analysis report.
   - A section for each column that provides the computed statistical values.
   - Proper spacing and formatting to enhance readability.

### **How the Script Works**
1. **Creating the CSV File**  
   When executed, the script first generates a sample CSV file with sales and profit data for different product categories. The function `create_sample_csv()` is responsible for writing the sample data to `data.csv`.

2. **Reading the Data**  
   The `read_csv()` function opens the CSV file and reads its contents into a dictionary structure. It ensures that only numerical data is considered for analysis, filtering out text values.

3. **Performing Analysis**  
   The `analyze_data()` function processes the numerical columns and calculates key statistical measures. The results are stored in a dictionary where each column name maps to its respective statistics.

4. **Generating the PDF Report**  
   The `generate_pdf_report()` function takes the computed statistics and formats them into a visually appealing PDF document. The PDF includes headers, column-wise analysis, and pagination support to maintain structure.

### **Applications and Use Cases**
- **Business Analysis**: Companies can use this script to quickly analyze sales and profit data.
- **Research & Academia**: Researchers can use it to process experimental data.
- **Finance & Accounting**: Accountants can analyze financial transactions and trends.
- **Automation & Reporting**: Organizations can integrate this script into automated workflows to generate periodic reports.

### **Conclusion**
This Python script simplifies data analysis and reporting by automating the entire workflow. By integrating file handling, data processing, statistical computation, and PDF generation, it provides a seamless solution for users who need structured insights from numerical datasets. With potential enhancements, it can serve as a powerful tool for various professional and academic applications.

# OUTPUT

![Image](https://github.com/user-attachments/assets/0911ebf4-222c-46b4-89da-4d311ab08e82)



