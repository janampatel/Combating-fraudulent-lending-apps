# Combating Fraudulent Digital Lending Apps

## Overview
This repository contains the code and documentation for our project presented at the Finovate Hackathon organized by IIT Gandhinagar. Our solution aims to identify and analyze fraudulent Digital Lending Apps. 

### Project Components
1. **Web Scraping**: Extracts apps with specific keywords using BeautifulSoup.
2. **Security Analysis**: Utilizes the Mobile Security Framework (MobSF) to generate detailed security reports on the downloaded apps.
3. **Clustering and Explainability**: Applies KMeans clustering and LIME to classify and explain app behavior.


**Set up MobSF**:
Follow the [MobSF installation guide](https://github.com/MobSF/Mobile-Security-Framework-MobSF) to set up the Mobile Security Framework.

## Usage
1. Run `v0_scraping.ipynb` and download apks
2. Ensure MobSF is running, and input apk files to it to get desired report in form of json or pdf.
3. Run `v2_clustering_and_xai` to perform clustering and generate explanations
    

```

# Contributing
Contributions are welcome! Please fork the repository and create a pull request with your changes.

