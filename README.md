# MENTAL_WELLBEING_CHATBOT_MOODMATE
Moodmate is an innovative application designed to assist users in managing their mental wellbeing by leveraging machine learning models. It integrates two robust models—an Emotion Classifier and a Suicide Detection Classifier—to provide empathetic support and meaningful interactions. The project includes Kaggle-based code and detailed reports to showcase its design and implementation.

**Repository Structure**
 ``` bash
Moodmate/
├── GoEmotionsdataset.zip                                    # Dataset used for emotion classification
├── Mid Term Report Sushant Goyal.pdf                        # Comprehensive mid-term project report
├── dsg BYOP proposal sushantgoyal final.pdf                 # Proposal document outlining the project
├── integration-of-model-mental-wellbeing-chatbot_final.ipynb
│    - Notebook to integrate the chatbot and models
├── mental-wellbeing-chatbot_model_train_final.ipynb
│    - Notebook for training the emotion and suicide detection models
├── README.md                                                # Project documentation
```
## **Project Highlights**
**Key Features**
**Emotion Classifier**: Accurately predicts emotions such as happiness, sadness, anger, and more, allowing personalized interactions.

**Suicide Detection Classifier**: Identifies potentially harmful or alarming patterns in user inputs, enabling prompt support.

**Predefined Response System**: Responds empathetically to detected emotions, creating a helpful and user-friendly experience.

**Scalable Framework**: The chatbot and models can be easily extended or improved to include additional functionalities.


## **Included Files**
**Model Training Notebook (mental-wellbeing-chatbot_model_train_final.ipynb)** :
This notebook covers preprocessing, training, and evaluating the machine learning models using Kaggle datasets.

**Model Integration Notebook (integration-of-model-mental-wellbeing-chatbot_final.ipynb)** :
Demonstrates how the trained models are deployed in the chatbot framework.

**GoEmotions Dataset (GoEmotionsdataset.zip)** : 
The dataset used to train the Emotion Classifier, sourced from Kaggle.

**Reports (Mid Term Report.pdf and Proposal.pdf)** :
Detailed insights into the project's planning, methodologies, and results.

Other files such as Suicide watch dataset were > 100mb, and hence I am not able to upload them here. ( Kindly view on Kaggle).


## **Getting Started**
**Prerequisites**

Ensure you have the following installed:
1) Python 3.8+
2) Jupyter Notebook or Google Colab
3) Required Python libraries (install via requirements.txt if available)

**Steps to Run**
1) Clone this repository to your local machine:
``` bash
git clone https://github.com/Sushant1703/Moodmate_mENTAL_wELLBEING_cHATBOT.git
cd Moodmate_mENTAL_wELLBEING_cHATBOT
```
2) Extract the dataset (GoEmotionsdataset.zip) to the same directory.

3) Open the notebooks:
   a)Use mental-wellbeing-chatbot_model_train_final.ipynb to train the models.
   b)Use integration-of-model-mental-wellbeing-chatbot_final.ipynb to test and run the chatbot.
   
4) Install dependencies if required:
```bash
pip install -r requirements.txt
```
5)Follow the instructions in the notebooks to execute the code.


