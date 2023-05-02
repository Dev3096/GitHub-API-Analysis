Angular Material GitHub API Analysis

This project uses the GitHub API and Postman to retrieve and analyze data from the Angular Material repository. The goal is to gather and display statistics about the number of issues, forks, and pulls created during the year 2022, as well as the distribution of these events across the days of the week and the months of the year.

Usage

To use this project, simply download or clone the repository and run the script in Python 3. You will need to have the requests and networkx packages installed.

Copy code

python3 github_analysis.py

Data Collection

The GitHub API was used to retrieve information about the Angular Material repository, specifically the list of issues, pulls, and forks. The API requires an access token, which can be generated from your GitHub account settings.

The response data from the API was reviewed in Postman to ensure that the correct data was being retrieved.

Data Analysis

The script uses Python to perform the following analyses on the data:

Total number of issues, forks, and pulls created in 2022

Total number of issues, forks, and pulls created in each month of 2022

Total number of issues, forks, and pulls created on each day of the week in 2022

The networkx package is then used to display the results in graphical form.

