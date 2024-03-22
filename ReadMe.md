
# LAWLINKS: Legal Accuracy With Language Intelligence & Natural Knowledge Suite

In today’s digital world, the need for enhanced accessibility to legal cases has become of utmost importance. Legal documents in various languages often hinder efficient comprehension and retrieval. This project seeks to develop a state-of-the-art system using NLP and LLM technology to overcome language barriers, enabling the translation of legal case PDFs into English and their secure storage. Additionally, if the user needs to inquire or gain specific info related to the legal cases, the LLM extracts the most pertinent data from the translated PDFs.

## Code Files

### Translation Using Marian NMT
- *File Name*: MarianMT.ipynb
- *Description*: Contains code for translating legal case PDFs using the Marian NMT integration. Focuses on translation quality, is open-source, scalable, and ensures privacy and security.
- *Usage*: Run the MarianMT.ipynb script to translate legal case PDFs into English.

### Search Query Answering with FLAN-T5
- *File Name*: queryprocess_final.ipynb
- *Description*: Contains code for search query answering using the FLAN-T5 model. The model is fine-tuned to extract information and generate answers related to legal cases from the uploaded document.
- *Usage*: Run the queryprocess_final.ipynb script to fine-tune the FLAN-T5 model and answer questions related to legal cases.

## Dataset
The dataset used in this project was curated using the elder brother method. A stronger Language Model (LLM) was used to generate data based on actual cases provided by an international law firm, LawYantra. This dataset includes cases used for both document summarization and question-answering tasks, providing a comprehensive set of examples for training and fine-tuning the model.

## Usage

*LawLinks Legal Case Question Answering* is a project that utilizes a fine-tuned FLAN-T5 model to extract information and generate answers related to legal cases. It includes scripts for preprocessing data, fine-tuning the model, and using the model to answer questions.

## Setup

1. *Clone the repository*:

   bash
   git clone https://github.com/vyasylum/LawLinks.git
   

2. *Install dependencies*:

   bash
   pip install -r requirements.txt
   

3. *Download preprocessed data*:

   - Download the preprocessed data file from the provided folder and place it in the project directory.

4. *Download the pre-trained model*:

   - Download the pre-trained T5 model from the [Google Drive link](https://drive.google.com/drive/folders/1t6pZmlwNSl5pVANqPJBz_jVJxyg02jzv?usp=sharing) and place it in the project directory.

5. *Set up environment variables*:

   - Set the environment variable PYTORCH_CUDA_ALLOC_CONF to max_split_size_mb:128 to optimize CUDA memory usage.

## Future Scope

The future scope of this case summarization tool is promising. It can be further enhanced by integrating additional language models, expanding the dataset to include more diverse legal cases, and refining the question-answering capabilities. Moreover, the tool can be adapted for use in other domains requiring language translation and information extraction, such as medical records or academic papers.

- **Enhanced Preprocessing:** Improve text preprocessing techniques to handle legal language nuances more effectively.
- **Interactive User Interface:** Develop a user-friendly interface to allow users to input questions and view summaries.
- **Customized Summaries:** Implement functionality to allow users to specify the length or focus of the generated summaries.
- **Scalability:** Explore methods to improve the model's scalability for processing large volumes of legal documents.
