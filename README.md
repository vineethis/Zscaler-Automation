# Knowledge Base (KB) and README:

# Purpose:
# The script is designed to automate the process of setting up Zscaler locations with associated static IP addresses and VPN credentials. It reads data from an Excel file, interacts with the Zscaler API to create records, and finds the nearest data centers based on geographical coordinates.

#  Requirements:
# - Python 3.x
# - `requests` library for making API calls
# - `pandas` library for data manipulation
# - `geopy` library for calculating distances
# - `openpyxl` library if dealing with `.xlsx` files
# - Access to Zscaler API with valid credentials

#  Usage:
# 1. Place the script in a directory with the Excel file containing the necessary data.
# 2. Ensure that the Zscaler API credentials are set as environment variables or hardcoded in the script.
# 3. Run the script. It will prompt you to select the required files and proceed with the operations.

#  Steps to Execute:
# 1. Open a terminal or command prompt.
# 2. Navigate to the directory containing the script.
# 3. Run the script using the command `python script_name.py`.
# 4. Follow the on-screen prompts to select files and perform operations.


#  README:

#  Script Name:
# Zscaler Location Setup Script

#  Description:
# This script automates the creation of Zscaler locations with static IP addresses and VPN credentials. It reads from an Excel file, interacts with the Zscaler API, and identifies the nearest data centers based on geographical coordinates.

#  How to Run:
# 1. Ensure Python 3.x and required libraries are installed.
# 2. Set Zscaler API credentials as environment variables.
# 3. Place the script in the same directory as the Excel file.
# 4. Run the script using `python script_name.py`.
# 5. Select the required files when prompted.

#  File Selection:
# The script will prompt you to select:
# - Excel file with location data.
# - Text file with the pre-shared key.
# - JSON file with data center information.

#  Output:
# - The script will create Zscaler locations and associated records.
# - It will generate CSV files with the nearest data center information.

#  Notes:
# - The script logs important information for debugging purposes.
# - Ensure that the Excel file follows the required format with specific sheets and columns.
