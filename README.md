## 🏥स्वास्थ्य सहायक (Swasthya Sahayak)

## OVERVIEW

The Problem Statement was to develop a comprehensive healthcare recommendation system, essentially serving as a doctor-finder platform. This system operates by analyzing symptoms provided by users to pinpoint potential health conditions, which are then matched with doctors specializing in relevant fields and offering available appointments. Additionally, the system factors in user ratings to recommend highly regarded healthcare providers. Leveraging datasets encompassing disease-symptom correlations and extensive profiles of healthcare practitioners, including specialties, ratings, and availability, ensures precise and efficient recommendations tailored to individual needs.


## FEATURES

- 🩺 **Symptom Analysis:** Machine learning algorithms analyze user-entered symptoms to identify potential health conditions. The system utilizes a dataset containing disease-symptom correlations to make accurate predictions.
  
- 📋**Doctor Recommendation:** Recommended doctors are matched with user symptoms based on specialties and availability. The recommendation engine prioritizes doctors with high ratings and aligned schedules to ensure quality and convenience for users.

### PREREQUISITES

- The latest version of Python installed on your system
- Jupyter Notebook installed (optional) or access to Google Colab for running code files

### INSTALLATION

1. Download the project files from the repository.

2. Ensure you have the latest version of Python installed on your system.

3. Install Jupyter Notebook (optional) or open the code file in Google Colab.

4. Upload the dataset named `updated_dataset.csv` along with the code files in your working environment.

### USAGE

1. Open the `main_updated.ipynb` file in your Jupyter Notebook or Google Colab.

2. Run the code file.

3. Enter your symptoms when prompted. Ensure the symptoms match those available in the dataset.

4. The system will output the most relevant diseases and recommend a doctor specializing in the corresponding field. The recommendation will consider the doctor's availability and user ratings.

## FUTURE SCOPE

- **Updation of User Ratings:** Implement a feature to allow users to update doctor ratings over time, ensuring the recommendations remain relevant and accurate.
  
- **Updating Doctor Schedules:** Integrate functionality to update doctor schedules dynamically, reflecting real-time availability.

- **Emergency Button:** Incorporate an emergency button feature that, when activated, provides immediate access to nearby healthcare facilities based on geolocation.

- **Multilingual Chatbot Assistant:** Recognizing the linguistic diversity of our country, integrate a multilingual chatbot assistant using NLP. This chatbot will enable users to input symptoms in their preferred language, ensuring accessibility for everyone.

- **Interactive UI:** Develop an interactive user interface that is easy to navigate and supports accessibility features such as text-to-speech conversion and alternative text for images. This will ensure that the system is usable by individuals with disabilities.

## REFERENCES

- Symptom-Disease Dataset: [Kaggle Dataset](https://www.kaggle.com/datasets/kaushil268/disease-prediction-using-machine-learning)
- Healthcare-Provider Dataset: Web scrapped from [DrData](https://www.drdata.in/listdoctors.php?search=Doctor&state=&state=Uttar%20Pradesh&page=2)
- Review paper on Healthcare Recommendation System: [ScienceDirect](https://www.sciencedirect.com/science/article/abs/pii/S0957417422018413)

## CONTRIBUTING

👩‍💻 Contributions to the project are welcome! If you encounter any issues or have ideas for improvements, please submit a GitHub issue or create a pull request with your changes.

