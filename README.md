# Data Processing in Python (JEM207)
The repo is for the course Data Processing in Python from [IES](https://is.cuni.cz/studium/predmety/index.php?do=predmet&kod=JEM207) (Charles University) WS/2022.

## Midterm exam
[My midterm exam](https://github.com/MyAscii/JEM207-IES/blob/main/midterm.ipynb)

## Project
A machine learning algorithm that uses scikit-learn to determine if someone is eligible for a loan using this [dataset](https://www.kaggle.com/datasets/vikasukani/loan-eligible-dataset).

### Installing

#### Github

Cloning the repo:

``` git clone https://github.com/MyAscii/JEM207-IES.git ```

Installing the required packages: 

``` pip install -r requirements.txt ```

#### Google colab (Recommended)

Get the files: 

Clicking on this [link](https://colab.research.google.com/drive/1bAhrFHGRXw4KsPsdkjvXENHZyvaBHt0I?usp=sharing).

After go to Files -> Save a copy in Drive, don't forget to upload the dataset in the side widget in the tab file.

Installing the required packages: 

Remove the Number signs/Hashtags in the second code cell. 

### Usage

To run the loan eligibility algorithm with the GitHub methode, execute this command: 

``` python Loan_Eligibility_Prediction.py ```

If you followed the Google colab method, click on Runtime -> Run all or do ctrl+F9.

The API is here simulated/faked to change the user input directly change the values in the JSON Objects/List of dictionaries found the in part API, the result of this will be given the part API result with JSON Objects/List of dictionaries.

### Contributing 

We welcome contributions to this project. If you want to contribute, please follow these steps:

1. Fork the repository.
2. Create a new branch for your changes.
3. Make the changes and commit them to your branch.
4. Submit a pull request to the development branch.

Here are some ideas:

-Create a real API (with the capture of email for marketing purposes)

-Create a GUI version

-Optimize some of the supervised learning models to get higher accuracy.

### License

This project is licensed under the MIT License. See the [LICENSE](https://github.com/MyAscii/JEM207-IES/blob/main/LICENSE) file for details.
