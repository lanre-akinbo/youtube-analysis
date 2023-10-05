# YouTube Data Analysis Project

## Overview

This repository contains the code and documentation for a comprehensive data analysis project focused on YouTube data, with a specific emphasis on the channels and content of Marques Brownlee (MKBHD). The project utilizes the YouTube Data API, exploratory data analysis (EDA), sentiment analysis and machine learning to derive insights and recommendations for content creators.

## Data Collection

The project begins with the collection of data through the YouTube Data API, allowing for the retrieval of essential information such as video details, comments and related metadata. This extensive dataset forms the basis for subsequent analyses.

## Data Cleaning and Preprocessing

The collected YouTube data undergoes a series of cleaning and preprocessing steps to ensure its quality and suitability for analysis. This includes dropping unnecessary columns, converting data types, date and time processing, text data analysis and comment data transformation.

## Exploratory Data Analysis (EDA)

EDA involves visualizing and analyzing the data to identify patterns, trends and relationships. The analysis covers channel insights, video metrics analysis, video duration analysis, publishing patterns, text data analysis and sentiment analysis.

## Sentiment Analysis

Sentiment analysis is performed on user comments associated with YouTube videos. This analysis provides insights into the emotions and opinions expressed by viewers, helping to gauge audience sentiment towards the content.

## Machine Learning Model

The project includes the construction of a Multinomial Naive Bayes classifier model for sentiment analysis. This section covers encoding sentiment labels, data splitting, text vectorization, model training and model evaluation.

## Getting Started

To get started with this project, follow the steps below:

### Prerequisites

Make sure you have the following software and tools installed on your system:

- Python 3.7+
- Git
- Jupyter Notebook (for running the analysis notebooks)

### Installation

1. Clone the repository to your local machine:

   ```bash
   git clone https://github.com/lanre-akinbo/youtube-analysis.git
   ```

2. Navigate to the project directory.

3. Create a virtual environment (optional but recommended):

   ```bash
   python -m venv venv
   ```

4. Activate the virtual environment.

5. Install the required Python packages:

   ```bash
   pip install -r requirements.txt
   ```

6. Obtain YouTube Data API credentials:

   - Visit the [Google Developers Console](https://console.developers.google.com/).
   - Create a new project and enable the YouTube Data API for it.
   - Generate an API key and configure it in your project.

7. Run the Jupyter notebooks to perform data analysis:

   ```bash
   jupyter notebook "Youtube Analytics.ipynb"
   ```

### Configuration

Before running the Jupyter notebooks, make sure to configure the API key and any other necessary credentials in the appropriate configuration files. These files are usually found in the `config` directory.

## Usage

This project provides a comprehensive analysis of YouTube data, specifically focusing on MKBHD's channels. You can utilize this analysis as follows:

1. Data Collection: Use the provided code to collect YouTube data for your preferred channels or topics of interest. Replace the channel IDs and query parameters as needed.

2. Data Analysis: Explore the Jupyter notebook in the project directory to conduct your data analysis. The notebooks cover various aspects such as exploratory data analysis (EDA), sentiment analysis and machine learning modeling. Modify and adapt these notebooks to suit your specific analysis requirements.

3. Extract Insights: Analyze the results and insights obtained from your data analysis. Use these insights to make data-driven decisions for content creation or any other relevant purposes.

4. Customize the Project: This project is designed to be a flexible template. You can adapt and extend it to analyze data from different YouTube channels, industries or domains by modifying the code and configuration files.

Please feel free to contribute to this project or modify it to meet your specific needs. Contributions, bug fixes and enhancements from the community are all welcome.

## License

This project is licensed under the [MIT License](LICENSE).
