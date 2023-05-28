Monthly Sales Report


This R Markdown script generates a monthly sales report for different divisions (RCD, ECD ,PTC, SPK, KSD). The report provides insights into the top bookings, top invoices, and top quotes for each division. The script utilizes data from the bookings, invoices, and quotes datasets to generate visualizations and tables.

Instructions
To run the script and generate the monthly sales report, follow these steps:

Install R and RStudio.
Clone or download the project repository from GitHub.
Open the monthly_sales_report.Rmd file in RStudio.
Make sure the necessary R packages are installed by running install.packages(c("tidyverse", "prophet", "kableExtra", "prophet")) in the R console.
Set the appropriate working directory or adjust file paths as needed.
Run the R code chunks in the R Markdown file to execute the analysis and generate the report.
The generated report will be saved as an HTML document with the filename monthly_sales_report.html.
Open the monthly_sales_report.html file in a web browser to view the report.
File Description
monthly_sales_report.Rmd: R Markdown script that contains the code and documentation for generating the monthly sales report.
bookings.csv: CSV file containing the sales bookings data.
invoices.csv: CSV file containing the sales invoices data.
quotes.csv: CSV file containing the sales quotes data.
images/: Directory containing images used in the report.
Data Description
bookings.csv: The bookings dataset contains information about sales bookings, including item numbers, quantities, prices, and dates.
invoices.csv: The invoices dataset includes details about sales invoices, such as item numbers, quantities, prices, and dates.
quotes.csv: The quotes dataset provides information about sales quotes, including item numbers, descriptions, quantities, prices, and dates.
Requirements
The following R packages are required to run the script:

tidyverse
prophet
kableExtra
These packages can be installed by running install.packages(c("tidyverse", "prophet", "kableExtra")) in the R console.

Additional Notes
This script assumes that the necessary data files (bookings.csv, invoices.csv, quotes.csv) are available in the same directory as the R Markdown file. Adjust the file paths accordingly if the data files are located elsewhere.
The script uses the prophet package for time series forecasting. If the package is not installed, run install.packages("prophet") in the R console to install it.
Feel free to customize and modify the script as needed to suit your requirements.

Note: Make sure to replace the placeholder descriptions and instructions with the actual details specific to your project.
