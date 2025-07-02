# AUTOMATED-REPORT-GENERATION

*COMPANY* : CODTECH IT SOLUTIONS

*NAME* : SAM NIKITH SINGH R

*INTERN ID* : CT04DF1181

*DOMAIN NAME* : PYTHON PROGRAMMIMG

*DURATION* : 4 WEEKS

*MENTOR NAME* : NEELA SANTHOSH


 *Project Overview*

This project demonstrates how to build an **automated data analysis and reporting tool** using Python. The program takes a CSV dataset as input, performs essential statistical analysis, visualizes feature correlations, and automatically generates a **multi-page PDF report** summarizing the findings.

The project is designed with simplicity and efficiency in mind. It uses widely adopted Python libraries like `pandas` for data manipulation, `seaborn` and `matplotlib` for data visualization, and `fpdf2` for structured PDF generation. Users can run the notebook in **Google Colab**, upload their dataset, and get a downloadable **PDF report** with just one click — no coding experience required.

This tool is ideal for students, data analysts, and professionals who want a quick summary of any dataset without manually writing code for each step. It can be customized and extended for various domains such as business analytics, academic research, survey analysis, and more.

 *Technologies Used*

* **Python 3**: The programming language used to create the entire solution.
* **Google Colab**: Platform used for hosting and executing the notebook interactively.
* **pandas**: For reading the dataset and generating descriptive statistics like mean, standard deviation, min, max, etc.
* **matplotlib** & **seaborn**: For plotting a correlation heatmap that visually represents relationships between numeric variables.
* **fpdf2**: To dynamically build and export the analysis into a clean and readable PDF document.

 *Key Features*

* **Interactive File Upload**: Allows users to upload any CSV file directly in the Colab interface.
* **Automatic Summary Generation**: Uses `pandas.describe()` to summarize all numerical features.
* **Correlation Heatmap**: A visually informative heatmap showing feature interrelationships using Pearson correlation.
* **Professional PDF Output**:

  * Page 1: Project title, description, dataset name, and basic structure.
  * Page 2: A full descriptive statistics table with rows and columns.
  * Page 3: Embedded correlation heatmap image.
* **One-click PDF download**: After analysis, the PDF is saved and automatically downloaded.

 *Workflow*

1. **Upload your CSV dataset** through the file upload interface in Colab.
2. The notebook reads the file, extracts key statistics, and computes pairwise correlations.
3. A correlation heatmap is generated and saved as a PNG image.
4. A multi-page PDF is assembled using the FPDF library:

   * The first page includes a summary and metadata.
   * The second page displays a detailed table of descriptive statistics.
   * The third page contains the visual heatmap.
5. The final report is automatically downloaded as `data_analysis_report.pdf`.

 *How to Use*

1. Open the notebook in Google Colab.
2. Run all cells step by step.
3. Upload your CSV dataset when prompted.
4. Wait for the report to generate and download automatically.
5. You’ll find a complete PDF containing all the insights from your data.

 *Use Cases*

* Quick exploration of any dataset
* University or school projects involving data analysis
* Survey result reporting
* Business reports and internal presentations
* Automated data profiling tools

 *Customization Ideas*

* Add plots for value counts or missing values.
* Support more statistical tests (e.g., skewness, kurtosis).
* Include time-series plots if a `date` column is present.
* Generate a summary in other formats like Excel or HTML.
* Add support for multiple file inputs or merging.

**OUPUT**

![Image](https://github.com/user-attachments/assets/e085a2eb-c8de-4790-b2d8-f2ce1c40906d)
![Image](https://github.com/user-attachments/assets/752c1f9f-f69b-4b3c-bdd8-dce0871f7cc9)
![Image](https://github.com/user-attachments/assets/e20c68b3-78fb-4a38-84fd-aec254b73384)

