# 📧 Automatic Detection of Email Phishing Attacks 🚫🎣

This project aims to automatically detect email phishing attacks using multiple models:

- **Model 1: NLP-based classification** uses natural language processing techniques to classify emails as phishing or not phishing based on the email's content.
- **Model 2: Abnormality detection based on email headers** checks for abnormalities in the email headers that might indicate a phishing attempt.
- **Model 3: Unwanted content detection** checks for unwanted or suspicious content, such as malicious links or attachments, that might indicate a phishing attempt.

## 🚀 Getting Started

1. Clone this repository.

```bash
git clone https://github.com/marwenkouidhi/automatic-detection-of-email-phishing-attacks
cd automatic-detection-of-email-phishing-attacks
```

2. Install the required packages.

```bash
pip install -r requirements.txt
```

## 📁 Repository Structure

The repository is structured as follows:

`preprocess`: Contains scripts used to preprocess the collected data to DataFrames.

`models`: Contains the implementation of the three models.

## 📊 Datasets

This project uses multiple datasets to train and evaluate the models:

`Nazario phishing corpus`: The Nazario Phishing Corpus consists of up to 7315 emails that were initially collected from 2004 to 2007 and last updated in 2022.

`TREC phishing corpus`: The TREC corpus is extensively used datase in the field of spam detection. The copyright of this dataset is held by the Waterloo University.

Both of these datasets can be downloaded from the following links:

`Nazario phishing corpus`: https://monkey.org/~jose/phishing/

`TREC phishing corpus`: https://plg.uwaterloo.ca/cgi-bin/cgiwrap/gvcormac/foo07
