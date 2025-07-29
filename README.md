# Automated-Report-Generation-
*COMPANY*: CODTECH IT SOLUTIONS 
*DOMAIN*: PYTHON 
*NAME*: NEHA NITIN BANKAR 
*INTERN ID*: 
*MENTOR*: NEELA SANTOSH
*DURATION*: 4 WEEKS 

#DESCRIPTION:

This Python script generates a PDF sales report using the fpdf library. It starts by defining a sample dataset containing sales records, where each record includes a Date, Region, and Sales amount. The script then calculates key statistics from this data: average sales, maximum sales, and minimum sales, using Python's built-in functions (sum(), max(), min()).

A custom class PDF is created, inheriting from FPDF, with two methods: header() and footer(). The header() method adds a title "Sales Report" centered at the top of each page, while the footer() method adds a page number at the bottom.

The PDF generation process begins by creating an instance of the PDF class and adding a new page. The script then sets the font style and size before adding a summary section that displays the computed average, maximum, and minimum sales values.

Following the summary, a table is constructed to present the detailed sales records. The table header (Date, Region, Sales) is added with bold fonts and cell borders. Each sales record from the data list is then inserted into the table with borders for proper alignment and readability.

After the content is generated, the PDF file is saved with the filename sales_report.pdf. To enhance usability, the script includes functionality to automatically open the generated PDF. Depending on the user's operating system, it uses os.startfile() for Windows, open command for macOS, or xdg-open for Linux systems to open the file immediately after creation.

#OUTPUT:






