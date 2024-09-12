Basic Python Application
This is a command-line Python application that provides two functionalities:

Prime Factorization: Given an integer, the program performs prime factorization and returns the prime factors along with their exponents.
Weather Data Aggregation: The program allows you to input weather data (temperature and humidity) for multiple cities and calculates the average temperature and humidity for each city.
Table of Contents
Features
Requirements
How to Run
Usage
Example Interaction
Features
Prime Factorization: Input an integer greater than 1, and the application will compute its prime factors and their corresponding exponents.
Weather Data Aggregation: Input multiple cities with optional temperature and humidity data, and the app will compute the average temperature and humidity for each city.
Requirements
Python 3.x (preferably 3.6 or higher)
How to Run
Step 1: Clone or Download the Repository
You can clone this repository using Git:

bash
Copy code
git clone https://github.com/Developer-ronie/python_app.git
Alternatively, download the ZIP file from the repository and extract it.

Step 2: Navigate to the Application Directory
Open a terminal or command prompt, then navigate to the folder containing the Python script:

bash
Copy code
cd path/to/application
Step 3: Run the Application
Run the Python script using the command below:

bash
Copy code
python app.py
This will launch the application and present you with a menu of options.

Usage
Once the application starts, you will be presented with a simple menu with three options:

Prime Factorization: Enter an integer to perform prime factorization.
Weather Data Aggregation: Enter city names with corresponding temperature and humidity data to compute averages.
Exit: Exit the application.
Option 1: Prime Factorization
You will be prompted to enter a positive integer.
The program will output the prime factorization in the form of a list of tuples (prime factor, exponent).
Option 2: Weather Data Aggregation
You will be asked to enter a city name, then optionally enter temperature and humidity data.
The program will allow you to enter multiple records. When you are done, type done.
The program will then compute the average temperature and humidity for each city entered.
Option 3: Exit
Select this option to exit the program.
Example Interaction
Prime Factorization Example
mathematica
Copy code
Welcome to the Basic Application
1. Prime Factorization
2. Weather Data Aggregation
3. Exit
Choose an option (1, 2, or 3): 1
Enter a number to factorize: 60
Prime factorization of 60: [(2, 2), (3, 1), (5, 1)]
Weather Data Aggregation Example
vbnet
Copy code
Welcome to the Basic Application
1. Prime Factorization
2. Weather Data Aggregation
3. Exit
Choose an option (1, 2, or 3): 2
Enter city name (or 'done' to finish): New York
Enter temperature for New York (or press Enter to skip): 25
Enter humidity for New York (or press Enter to skip): 65
Enter city name (or 'done' to finish): Los Angeles
Enter temperature for Los Angeles (or press Enter to skip): 30
Enter humidity for Los Angeles (or press Enter to skip): 55
Enter city name (or 'done' to finish): done

Aggregated Weather Data:
New York - Average Temperature: 25.0, Average Humidity: 65.0
Los Angeles - Average Temperature: 30.0, Average Humidity: 55.0
Exiting the Application
markdown
Copy code
Welcome to the Basic Application
1. Prime Factorization
2. Weather Data Aggregation
3. Exit
Choose an option (1, 2, or 3): 3
Exiting the application. Goodbye!
License
This project is open-source and available under the MIT License.