## Texas Wholesaler Distributer Database Capstone

**Project description:** For this capstone project, I improve the Texas Wholesaler Distributer Database and achieve the process of partial automation for the Prescription Monitoring Program (PMP) of Texas State Board of Pharmacy. Currently, PMP staff manage prescription data manually. This project improves this database by migrating increasing functionality to allow PMP staff the ability to manage and import wholesaler data updates with some level of automation. My work is to develop a website to upload files, validate uploaded files in ARCOS format, inform wholesalers of files upload status and clean out previously loaded files automatically. 

### 1. Interview with workers to know the whole work process

<img src="images/Flow chart.png?raw=true"/>


### 2. Study the specific ARCOS format requirement.

In terms of ARCOS format, I study the following two files.
* <a href="https://www.deadiversion.usdoj.gov/arcos/handbook/section5.htm">ARCOS Registrant Handbook</a>
* <a href= "pdf/TWDD FAQ.pdf">TWDD FAQ</a>

### 3. Develop a public website to upload a file
* Sale files: uploading the file directly; 
* No-sale files: uploading the file that the transaction code is 7 or checking the no-sale box directly;
<img src="images/public.png?raw=true"/>
<img src="images/public code.png?raw=true"/>

### 4. Validate the file uploaded to public server and save the file to a specified folder through PHP 

<img src="images/validate1.png?raw=true"/>
<img src="images/validate2.png?raw=true"/>

### 5. Inform wholesaler of the file upload status 

<img src="images/5.jpg?raw=true"/>

### 6. Clean out previously loaded files automatically

<img src="images/delete files.png?raw=true"/>


