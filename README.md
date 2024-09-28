# Breathe

**Breathe** is a web application built with Flask that incorporates a Deep Learning model. The project consists of both machine learning code and standard web development components for a dynamic website. This application enables interaction with a pre-trained model, allowing users to utilize the power of AI through a web interface.

## Table of Contents

- [Project Structure](#project-structure)
- [Setup](#setup)
- [Usage](#usage)
- [Deep Learning Model](#deep-learning-model)
- [Flask Web Application](#flask-web-application)
<!-- - [License](#license) -->

## Project Structure

```bash
├── ml_code/          # Contains code to develop and train the deep learning model
├── models/           # Trained model for prediction
├── static/           # Static files used in the website
│   └── images/       # Images for the website
├── templates/        # HTML templates for the Flask web app
├── .gitattributes    # Configuration for Git LFS (Large File Storage)
├── app.py            # Main Flask application code
├── database.db       # SQLite database file for the app
├── requirements.txt  # Dependencies for the project
```

## Setup

To run this project locally, follow these steps:

1. **Clone the repository**:

    ```bash
    git clone https://github.com/Subhanshu20101/Breatheeeeee.git
    cd Breatheeeeee
    ```

2. **Install the required dependencies**:  
   Ensure you have Python installed. Then, install the dependencies using the following command:

    ```bash
    pip install -r requirements.txt
    ```

3. **Run the Flask application**:  
   To start the Flask server, run:

    ```bash
    flask run
    ```

4. **Access the web application**:  
   Once the server is running, open your browser and go to `http://127.0.0.1:5000/` to view the website on local server.

---

## Usage

- The web interface allows users to interact with the deep learning model trained for this project.
- User can upload breathing audio data in `.wav` format to get prediction.

---

## Deep Learning Model

- The deep learning code is stored under the `ml_code/` directory. This folder contains the scripts for building and training the model.
- Pre-trained models are available in the `models/` folder.

### Training or Modifying the Model

To train or modify the model:

1. Navigate to the `ml_code/` directory:

    ```bash
    cd ml_code
    ```

2. Execute the training script or update the model configuration based on the files inside this folder.

---

## Flask Web Application

This application is built using the Flask framework. It handles the backend logic and serves the frontend through HTML templates.

- **Static files** (images) are located in the `static/` folder.
- **HTML templates** used for rendering the web pages are located in the `templates/` folder.
- The main backend logic is in `app.py`.

---

<!-- ## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more information. -->
