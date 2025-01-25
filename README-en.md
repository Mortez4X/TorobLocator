# Torob Store Position Finder (Executable Version)

**Version:** 1.0.0

A simple and efficient tool designed to help you find your store's position in the Torob marketplace and compare your product prices with other sellers. This tool processes your CSV file, fetches real-time pricing data from Torob, and provides you with a detailed comparison in an easy-to-read Excel report.

This version is a standalone executable (`.exe`), meaning no setup or additional dependencies are required. Simply run the `.exe` file to get started!

## Features
- **CSV File Processing:** Import your product data from a CSV file.
- **Real-Time Data Fetching:** Retrieves live pricing and availability data from the Torob API.
- **Price Comparison:** Compares your store's product prices with those of other sellers.
- **Shop Ranking:** Displays your store's ranking relative to other sellers in the marketplace.
- **Export Results:** Outputs the results to an Excel file for easy access and reporting.
- **No Installation Needed:** Simply download and run the executable.

## Usage

### Step 1: Download the Executable
1. Download the `.exe` file from the release section of this repository.

### Step 2: Run the Executable
1. Simply double-click on the `store_position_finder.exe` file to launch the application.
2. The application will open a simple graphical interface created with Tkinter.

### Step 3: Input Store and File Information
- The interface will prompt you for two pieces of information:
  - **Store Name:** Enter your store's name exactly as registered in Torob.
  - **File Name:** Enter the name of your CSV file (without the `.csv` extension) that contains the product data. The CSV file should be placed in the `import` folder next to the `.exe` file.

### Step 4: Processing the Data
- After entering the required information, click the **Send** button to begin processing the data.
- The tool will read the CSV file, fetch live data from the Torob API, and calculate your store's ranking and price comparison against other sellers.

### Step 5: Output the Results
- Once the processing is complete, the results will be saved in an Excel file inside the `export` folder.
- The output Excel file will contain:
  - Product name
  - Torob low and high prices
  - Your store's price
  - Price difference between your store and the first seller
  - Your store's position relative to all sellers
  - Product links (both your store and Torob)

## Example Output
The output Excel file will have the following columns:
- **Product Name**
- **Torob Low Price**
- **Torob High Price**
- **Your Store's Price**
- **Price Difference with First Seller**
- **Your Store's Position**
- **Product Link**
- **Torob Link**

## License Information
This executable version of the Torob Store Position Finder is provided to you for **personal use only**. By using this tool, you agree to the following:

- **No modification:** You may not reverse-engineer, modify, or redistribute the executable file.
- **Personal use only:** This tool is licensed for personal or business use, but it may not be resold or repackaged.
- **Use at your own risk:** We are not responsible for any loss of data, system failure, or issues caused by using the tool.

**License Type:** Proprietary (for personal use only)

## Troubleshooting

1. **File Not Found:**  
   Make sure the CSV file is placed in the `import` folder and that the file name is entered correctly.

2. **Invalid Inputs:**  
   Ensure that both the store name and file name are correctly filled out in the Tkinter interface. If any field is empty, the tool will show a warning message.

3. **API or Connectivity Issues:**  
   If there are issues fetching data from the Torob API, check your internet connection and try running the tool again.

## Contact

For any issues or inquiries, feel free to contact:
- **Email:** morteza_monfared@yahoo.com
- **Developed by:** @Mortez4X

## License

This project is licensed under the Proprietary License - you may only use the software for personal or business purposes. Redistribution, modification, or resale is not allowed.
