![logo_ironhack_blue 7](https://user-images.githubusercontent.com/23629340/40541063-a07a0a8a-601a-11e8-91b5-2f13e4e6b441.png)

# LAB | Synthetic Data Generation Practice

## Learning Goals

This exercise will help you:

- Practice generating synthetic datasets in different formats
- Work with both tabular (CSV) and image data
- Learn how to create and manage datasets using external tools and cloud platforms

## Requirements

- Fork this repository
- Clone it to your local machine

## Getting Started

In this lab, you will generate two types of synthetic datasets:

### A. Generate a CSV Dataset using [generatedata.com](https://generatedata.com/)

1. Visit [generatedata.com](https://generatedata.com/), a free open-source tool for generating custom synthetic data.
2. Configure the types of data you want to generate (e.g., names, addresses, phone numbers).
3. Select CSV as the output format.
4. Generate and download your dataset for further use.

*Tip:* Explore the various data type options and customize the dataset size based on your needs.

### B. Generate an Image Dataset using Google Vertex AI

1. Open the [Google Cloud Console](https://console.cloud.google.com/vertex-ai/datasets).
2. Navigate to the **Vertex AI** section and then to the **Datasets** page.
3. Click **Create** to open the dataset creation page.
4. Provide a descriptive **Dataset name**.
5. Select the **Image** tab.
6. Choose the objective: **Single-label** or **Multi-label image classification**.
7. Select your desired **Region** from the drop-down menu.
8. Click **Create** to create the empty dataset and proceed to the data import page.
9. Import your images from either your computer or a Cloud Storage bucket. Follow the prompts to upload and associate your image data with the dataset.

*Note:* Data import may take some time depending on the dataset size. You will receive a notification when your import is complete.

## Submission

- Upon completion, add your deliverables to git. 
- Then commit git and push your branch to the remote.
- Make a pull request and paste the PR link in the submission field in the Student Portal.

<br>

**Good luck!**