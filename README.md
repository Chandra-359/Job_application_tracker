# Job Application Tracker

The Job Application Tracker is a Python application that helps you track and organize your job applications. It stores information such as company name, job role, contact information, job status, job portal, and interview date in an Excel file.

## Features

- Save job details with a single click
- Track job status with a dropdown menu (Save for Later, Applied, Interviewed, Offer Received, Rejected)
- Store contact information and job portal/source
- Record scheduled interview dates
- Data is saved in an Excel file for easy access and analysis

## Requirements

- Python 3.x
- tkinter (built-in Python library for GUI)
- openpyxl (Python library for working with Excel files)

## Installation

1. Clone or download the repository to your local machine.
2. Install the required Python library by running the following command: pip install openpyxl

## Usage

1. Run the `job_tracker.py` script from the command line or an IDE.
2. A window with a "Save Job" button will appear.
3. Click the "Save Job" button and enter the required details when prompted:
   - Company Name
   - Job Role
   - Contact Information
   - Job Portal or Source
   - Interview Date (if applicable)
4. A dropdown window will appear asking you to select the job status. Choose the appropriate option from the list.
5. Click "Select" in the dropdown window.
6. The job details will be saved in the `job_applications.xlsx` file in the same directory as the script.
7. Repeat step 3 to add more job applications.

## Customization

- You can modify the column headers and order in the Excel file by updating the code in the `save_job` function.
- Additional columns or features can be added based on your specific requirements.

## Contributing

Contributions are welcome! If you find any issues or have suggestions for improvements, please open an issue or submit a pull request.

## License

This project is licensed under the [MIT License](LICENSE).
