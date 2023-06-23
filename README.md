# Breast Cancer Detection Application

This project focuses on developing a machine learning model for breast cancer detection and creating a user-friendly web application to facilitate its usage. The application utilizes various machine learning algorithms on a breast cancer dataset to achieve accurate results. 
Breast cancer is the most common type of cancer among women. Early detection plays a crucial role in successful treatment. However, false positives from certain detection devices can lead to unnecessary surgeries, causing physical and financial burdens on patients. This project aims to reduce unnecessary surgeries by utilizing machine learning techniques. By training a model on a dataset of previous breast cancer patients, we can predict whether a cancer is benign or malignant. These predictions can assist doctors in making informed decisions, minimizing unnecessary surgeries for women.

## Dataset and Model
We utilized the Wisconsin Breast Cancer dataset, consisting of 569 samples, with 357 classified as benign and 212 as malignant. The dataset underwent preprocessing and scaling. We trained seven different algorithms, among which the SVM with RBF kernel achieved the highest accuracy of 98.6% and a recall score of 0.9894. These results demonstrate the effectiveness of machine learning in predicting breast cancer type.

## Features

- **ML Model:** The project includes the development of a machine learning model using a range of algorithms specifically designed for breast cancer detection. These algorithms are trained on a well-curated breast cancer dataset to ensure reliable results.

- **Web Application:** A user-friendly web application is built using the Flask framework. It provides a simple and intuitive interface for users to interact with the breast cancer detection model.

- **Deployment:** The application is deployed on the Heroku platform, ensuring accessibility and availability to users from anywhere. This deployment enables seamless usage without the need for local installations or setups.

## Usage

To use the breast cancer detection application, follow these steps:

1. Clone the repository to your local machine.
2. Install the necessary dependencies and libraries listed in the requirements.txt file.
3. Run the Flask application locally using the command `python app.py`.
4. Open your web browser and access the application at `http://localhost:5000`.
5. Upload an input image or provide the required data for breast cancer detection.
6. Receive the detection results, which will indicate the presence or absence of breast cancer.

## License
This project is licensed under the [MIT License](https://opensource.org/licenses/MIT).

## Acknowledgments
Special thanks to the creators of the breast cancer dataset used in this project, as well as the Flask and Heroku communities for their valuable resources and documentation.

## Summary of results:

![image](https://user-images.githubusercontent.com/107847530/195638562-21730760-a479-4ff6-98e1-ed22f5ba1bbb.png)
