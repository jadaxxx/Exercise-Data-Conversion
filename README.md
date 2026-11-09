Exercise – Data Conversion

A simple web application that converts an uploaded CSV file into structured JSON data based on the provided Data Mapping specifications.

🌐 Live Application

Website: https://dacanayjadme.dcism.org/

🎯 Objectives
Upload an existing CSV file.
Read and process CSV records.
Transform CSV fields into their corresponding JSON properties.
Apply the required data types and transformation rules.
Generate structured JSON output.
📂 Required CSV File

Download the provided CSV file before using the application:

Download exercise_datamap.csv

🗺️ Data Mapping Specifications

The following table defines how the CSV fields should be converted into JSON properties.

Source Field (CSV)	Target Field (JSON)	Target Data Type	Transformation Rule
student_id	studentId	Integer	Convert string to integer
first_name	firstName	String	Capitalize the first letter
last_name	lastName	String	Capitalize the first letter
course	program	String	Convert to full program name
year_level	yearLevel	Integer	Convert string to integer
email	emailAddress	String	Convert to lowercase
tuition_balance	outstandingBalance	Number	Convert to decimal with 2 decimal places
⚙️ How to Use
Open the live application.
Upload the provided exercise_datamap.csv file.
Allow the application to process and transform the CSV records.
Review the generated JSON output.
Download or copy the resulting JSON data, if supported by the application.
🚀 Deployment

The application is hosted on the DCISM server.

Required hosting format:

[lastname + first 2 letters of first name + dme].dcism.org

Example:

First Name: John
Last Name: Doe
Hosting Domain: doejome.dcism.org


