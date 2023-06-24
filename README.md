# PapyrusNebulae 2023 Document Cloud Hackathon: Round 1

## Problem Statement

The goal of this hackathon round is to extract information from PDF invoices using the Adobe PDF Services Extract API. 

## Description

This project provides a user-friendly interface where users can upload PDF invoices from the frontend. The PDF files are then sent to the backend for further processing. The backend utilizes the Adobe PDF Services Extract API to extract relevant information from the invoices.

The Extract API processes the PDF documents and returns a response containing the extracted data. The backend server reads this response and extracts the necessary information using appropriate parsing techniques.

Once the relevant information is extracted, it is written into a CSV (Comma-Separated Values) file. The CSV file follows the same format as the provided `ExtractedData.csv` file, ensuring consistency and compatibility.



## Features

- User-friendly interface for uploading PDF invoices.
- Seamless integration with the Adobe PDF Services Extract API.
- Parsing of the API response to extract relevant invoice information.
- Writing the extracted data into a CSV file in the specified format.


## Installation and Setup
Technologies Used : React , Express 
To set up the project locally, follow these steps:

1. Clone the repository:
   ```shell
   git clone https://github.com/nipunarora098/Adobe-Project.git

2. GO to client directory 
	cd client
3. Install Dependancies
	npm init
	npm i react-router-dom axios
4. Start Frontend
	npm start
5. Go to server Directory
	cd server
6. Install Dependancies
	npm init
	npm i express multer cors fs @adobe/pdfservices-node-sdk csv-writer adm-zip


7. Start backend
	npm run dev
8. On Frontend Interface -> Select Invoices
  ![image](https://github.com/nipunarora098/Adobe-Project/assets/74128691/223cfc91-a6b2-4589-a716-5cc945ab8ab1)

9. After submitted Invoices Extracted_data.csv file will be downloaded.


