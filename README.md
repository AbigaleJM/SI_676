This readme file was generated on 2022-10-08 by Abigale Mumby

GENERAL INFORMATION

Title of Dataset: File inventory for "Data" in Networked Services Labs Data

Author/Investigator Information
Name: Abigale Mumby
Institution: University of Michigan
Email: abigalem@umich.edu

Date of data collection: 2022-10-07

Geographic location of data collection: Ann Arbor, MI

SHARING AND ACCESS INFORMATION
Licenses/restriction placed on this data: None

Publicly accessible location of the data source: https://github.com/morskyjezek/networked-services-labs/tree/main/data

DATA & FILE OVERVIEW

File List:
	READMEmd: This README file
	file-metadata-manifest.csv: manifest of files in the data directory of "networked-services-labs-main"
	Assignment1.ipynb: Python script that created file-metadata-manifest.csv, stored in a Juptyer Notebook

File source: networked-services-labs-main, morskyjezek (GitHub)

METHODOLOGICAL INFORMATION

Description of Methods used for Collection/Generation of Data:
	Data was accessed by cloning the data source repository
	Python script created to access the "data" directory, iterate through subdirectories and create a list containing the metadata for files found in the subdirectories of "data."
	Metadata written out to a csv file: file-metadata-manifest.csv

DATA-SPECIFIC INFORMATION FOR: file-metadata-manifest-from-list.csv

Date of creation: 2022-10-07

Creator: Abigale Mumby

Created using: Python script found in Assignment1.ipynb

Number of rows: 49

Header List: 
	filename: name of file
	folder: folder inside "networked-services-labs-main" where file is located
	extension: file extension (ex. csv, pdb, pdf, txt, html, json, jpg, tif, ram, wma, mp3, t12z, asx) 
	size(bytes): file size in bytes
	absolute_path: the absolute file path 
	modification time: time of last modification according to the system
	md5_checksum: written function that produces the MD5 hash for each file in the dataset
	sha256_checksum: written function that produces the SHA256 hash for each file in the dataset

