
# Hostel Allotment System
This software is intended to make the hostel allotment an easier task for 
an institution.



## Features

- It allows the admin(for ex: warden) to register and then login using the username and password.
- Notify confirmation of registration to warden via email.
- On succesfull login warden will be able to.
   - Download the excel format for student registration.
   - Set the number of rooms,no of students in one room and preference criteria of the allotment.
   - Upload the students excel data to the database using read-excel-file package.
   - Start the allotment.
   - Generate and download the report of both the alloted and not alloted students.
   - Notify the allotment status to the students via email.

- Students can also login using the username and password provided via email to them
  after allotment of rooms.
-  Students can use this feature to know about their allotment details.


## Run Locally

Clone the project

```bash
  git clone https://github.com/nitishup94/Fynd_Final_Project_Hostel_Allotment_Sysytem
```

## Backend
Go to the project directory

```bash
  cd backend
```
Install dependencies

```bash
  npm install
```
```bash
  npm install cors
```
```bash
  npm install express --save
```
```bash
  npm install dotenv --save
```
```bash
  npm install mongoose
```
```bash
  npm install nodemailer
```
```bash
  npm install --save-dev nodemon
```
Start server
```bash
  nodemon index.js
```
## Frontend
Go to the project directory

```bash
 cd frontend
```

```bash
 npm install
```
```bash
 npm install -S vue-router@3
```
```bash
 npm install axios
```
```bash
 npm install jspdf --save
```
```bash
 npm install jspdf jspdf-autotable
```
```bash
 npm install read-excel-file --save
```
Start the frontend
```bash
npm run serve
```

## Tech Stack

**Client:** HTML,Bootstrap, CSS, JavaCcript,VueJs

**Server:** Node, Express

**Database:** MongoDB

## Project Live link
https://hostel-allotment.onrender.com/

