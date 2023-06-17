<h1 align="center">

  CGPA Predictor Web Application with Flask and Power BI Integration
</h1>

 <p align="center">
  <img width="600" src="![51EWaIih3GL](https://github.com/codingcog23/YoloV7-Object-Detection-in-Windows/assets/134972060/34cf1fd2-21fe-484b-ba6b-2f06aa2c42bb)
">
</p> 

<p align="center">
  This project is a web application that predicts the Cumulative Grade Point Average (CGPA) of students based on various input parameters. It utilizes the Flask framework for the backend implementation and integrates with Power BI for data visualization.
</p>

## Prerequisites

Before running the application, ensure that you have the following dependencies installed:

- Python 3
- Flask
- pandas
- scikit-learn
- matplotlib
- Power BI Desktop (for Power BI integration)

## Getting Started

1. Clone the repository to your local machine or download the source code files.
2. Install the required dependencies using <code>pip</code> or any package manager of your choice. You can use the following command:

## pip install -r requirements.txt
3. Download the pre-trained machine learning model file (<code>regressor_CGPA.pkl</code>) and place it in the project directory.

## Usage

1. Run the Flask application by executing the following command:

## python app.py
2. Access the web application by opening your web browser and entering the URL <code>http://localhost:5000</code>.

### Home

The home page (<code>home.html</code>) provides an interface for users to input the required parameters for CGPA prediction.

### Prediction

- Upon submitting the input parameters on the home page, the Flask route <code>/predict</code> is triggered.
- The machine learning model (<code>regressor_CGPA.pkl</code>) is loaded and used to predict the CGPA based on the input parameters.
- The predicted CGPA is then displayed on the result page (<code>result.html</code>).

### File Upload

- The file upload functionality allows users to upload CSV or Excel files containing multiple sets of input parameters for CGPA prediction.
- The uploaded file is processed, cleaned, and predictions are made for each set of parameters.
- The processed file with the predicted CGPA values is available for download.

### Power BI Integration

- The web application integrates with Power BI for data visualization and analysis.
- The <code>dashboard.html</code> page provides a link to access the Power BI dashboard.
- Upon clicking the link, the Power BI dashboard opens, providing visual representations of the CGPA data.

## Contributing

Contributions to this project are welcome. If you find any issues or have suggestions for improvements, please submit a pull request or open an issue on the GitHub repository.


## Acknowledgements

- The project utilizes Flask, an open-source web framework for Python.
- The machine learning model used for CGPA prediction is built using scikit-learn.
- Power BI is a business analytics tool developed by Microsoft for data visualization and reporting.



