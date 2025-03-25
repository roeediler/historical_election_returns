# 🗳️ Historical Election Returns (1824-1968)  

This project analyzes **county-level election returns** in the United States from **1824 to 1968**, using data from the **Inter-university Consortium for Political and Social Research (ICPSR 1)**. The dataset provides election results for **presidential, gubernatorial, senatorial, and congressional races**, including votes for over **1,000 political parties and independent candidates**.  

## 🏛️ Project Background  
This project processes **historical election returns** from the **ICPSR dataset**, handling **ASCII-formatted data**, cleaning it, and generating structured **CSV files** for further analysis.  

The work was part of an **economic history project** I collaborated on with a professor at the **Hebrew University of Jerusalem**. The goal was to **analyze historical election data** to uncover **voting patterns** and **political trends** in the United States. By structuring this data properly, we aimed to facilitate deeper **quantitative research** into historical electoral behavior.

## 📌 Project Goals  
- **Clean and structure** the raw ASCII data using SAS setup files  
- **Correct data errors** (e.g., missing congressional district names, mislabeled variables)  
- **Merge and analyze** historical election trends across different time periods  
- **Create reproducible workflows** for processing ICPSR datasets in R  

## 📊 Data Source  
This project uses data from:  
**Inter-university Consortium for Political and Social Research (ICPSR 1)**  
[United States Historical Election Returns, 1824-1968](https://doi.org/10.3886/ICPSR00001.v3)  

## 📂 Data Availability  
The processed dataset is available **upon request** or can be accessed on my **Kaggle profile**:  
📌 **[Kaggle: roeediler](https://www.kaggle.com/roeediler)**  

Due to ICPSR's terms of use, the raw dataset may require **researcher approval**. However, the cleaned and structured data, along with the processing scripts, are provided for **replication and further analysis**. If you need access or have any questions, feel free to **reach out**!

🛠️ Key Features
📂 Handling ASCII Data & SAS Setup Files
Uses SAScii and asciiSetupReader to read fixed-width ASCII files

Extracts metadata (variable names, formats, missing values) from SAS setup files

📈 Output
A cleaned dataset containing all election returns in a long format CSV

R scripts that allow reproducible data processing for future election datasets

🏛️ Citation
If you use this project, please cite the original dataset:

Inter-university Consortium for Political and Social Research.
United States Historical Election Returns, 1824-1968.
ICPSR [distributor], 1999-04-26.
https://doi.org/10.3886/ICPSR00001.v3

👨‍💻 Author
Ro'ee Diler

📧 [Contact Me](mailto:roeediler8@gmail.com)

🌍 [GitHub Profile](https://github.com/roeediler)

