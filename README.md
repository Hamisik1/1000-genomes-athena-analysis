# 🧬 1000 Genomes Project Analysis with Amazon Athena + PyAthena

This project demonstrates how to use **Amazon Athena** and **PyAthena** to query real genetic variant data from the [1000 Genomes Project](https://www.internationalgenome.org/).  
The analysis focuses on **allele frequencies** and how specific **SNPs (single-nucleotide polymorphisms)** vary across populations.

---

## 📁 Contents

- `analysis.ipynb` — Jupyter Notebook containing full analysis, Athena queries, and visualizations  
- `histogram_allele_frequencies.png` — Histogram of allele frequency distribution  
- `snp_bar_chart_population.png` — Bar chart showing SNP frequencies across different populations  

---

## 🔧 Tools Used

- **Amazon Athena** — SQL query engine for S3 data  
- **PyAthena** — Python client to connect to Athena  
- **Pandas** — Data analysis in Python  
- **Matplotlib** — Data visualization  
- **Jupyter Notebook** — Interactive coding environment  

---

## 🧪 What’s Covered in the Notebook

- Connecting to AWS Athena using PyAthena  
- Querying Variant Call Format (VCF) data from the 1000 Genomes Project  
- Extracting allele frequencies from the INFO column  
- Visualizing the distribution of variants  
- Comparing SNP frequencies across ethnic populations  

---

## 🚀 How to Run It

1. **Clone the repository**:
   ```bash
   git clone https://github.com/your-username/your-repo-name.git
   cd your-repo-name

2. **Install required libraries**:
   ```bash
   pip install -r requirements.txt

3. Launch the notebook:
   jupyter notebook analysis.ipynb

💡 Make sure your AWS credentials are configured and you have access to the S3 bucket + Athena environment.

✅ requirements.txt
       pandas
       matplotlib
       pyathena
       jupyter

📬 Contact
Created by Kelly Hamisi-McGuya
📧 Email: [kellyhamisi0@gmail.com](mailto:kellyhamisi0@gmail.com)




