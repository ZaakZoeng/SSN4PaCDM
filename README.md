# SSN4PaCDM
Constructing sample-specific networks (SSN) for different sample types to analyze pancreatic cancer (PaC)-associated diabetes mellitus (PaCDM)

## Overview
Understanding the pathogenesis of pancreatic cancer (PaC)-associated diabetes mellitus (PaCDM) is pivotal for the early detection of PaC in individuals with new-onset diabetes. However, the comprehensive identification of driver genes contributing to PaCDM pathogenesis remains a significant challenge, primarily due to the limitations of traditional bioinformatics methods.

In this study, we introduce an innovative approach by leveraging Sample-Specific Network (SSN) theory, a novel mathematical framework, to construct functional gene networks tailored to individual samples. Through rigorous statistical and network analyses, we identified PLK1 and NEK2 as potential driver genes. Their overexpression in PaC exacerbates paraneoplastic beta cell dysfunction, leading to endoplasmic reticulum stress and impaired glucose tolerance in vivo.

Our findings suggest that PLK1 and NEK2 are key drivers in PaCDM pathogenesis. Moreover, molecules downstream of these genes could serve as promising biomarkers for PaCDM screening, thereby advancing early detection strategies for PaC.

## Key Features
- Innovative Methodology: Application of Sample-Specific Network theory for personalized gene network analysis.
- Identified Driver Genes: PLK1 and NEK2, crucial in PaCDM pathogenesis.
- Clinical Relevance: Potential biomarkers for early screening and detection of pancreatic cancer.

## Clone the repository
You can run the network construction and analysis scripts provided in this repository. Follow the steps below:
```
git clone https://github.com/ZaakZoeng/SSN4PaCDM.git
cd SSN4PaCDM
```
The pipeline codes are all in `SSN4PaCDM.ipynb` script.

## Data Preparation
### Step 1: Data Decompression
Before running the analysis, ensure the required data files are properly extracted. Use the following command to decompress the data:
```
cd data/
tar -xzvf string-db-9606.protein.tar.gz
```

### Step 2: Download Data directly (Optional)
Alternatively, you can download the necessary files directly using the links below and place them in the `/data/string-db-9606.protein` directory:
```
https://stringdb-downloads.org/download/protein.links.v11.5/9606.protein.links.v11.5.txt.gz
https://stringdb-downloads.org/download/protein.info.v11.5/9606.protein.info.v11.5.txt.gz
gzip -d /data/string-db-9606.protein/9606.protein.links.v11.5.txt.gz
gzip -d /data/string-db-9606.protein/9606.protein.info.v11.5.txt.gz
```

## Results
The analysis will generate:
- Sample-specific gene networks.
- Statistical validation reports for PLK1 and NEK2.
- Visualizations of network dynamics and beta cell dysfunction pathways.

## Contribution
Contributions to improve and extend this project are welcome. Please submit a pull request or open an issue for discussion.

## License
This project is licensed under the MIT License. See the LICENSE file for details.