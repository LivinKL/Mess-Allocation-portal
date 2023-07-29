# Mess-Allocation-portal
Welcome to the Python Flask App! This is a simple web application built using the Flask framework. The app streamlines mess allocation for hostel students based on a "first come, first serve" to their preferences. Administrators can review messes and student details, optimising the allocation process. 


## Getting Started
To get the Flask app up and running on your local machine, follow the steps below

## Prerequisites
1. Python: Make sure you have Python version 3.5 or higher installed on your system.
2. (Optional) Virtual Environment: It is recommended to use a virtual environment to manage dependencies for your project. You can install virtualenv using pip:
```
pip install virtualenv
```
### Installation

1. Clone this repository to your local machine or download the ZIP archive and extract it.


2. (Optional) Create and activate a virtual environment:

```bash
virtualenv venv
source venv/bin/activate   # On Windows, use: venv\Scripts\activate
```

3. Install the required dependencies:

```bash
pip install -r requirements.txt
```

## Usage

To start the Flask app, run the following command:

```bash
export FLASK_APP=app
export FLASK_ENV=development
flask run
```

Once the app is running, open your web browser and navigate to [http://localhost:5000](http://localhost:5000) to access the app.

### Login Credentials:

To access certain features of the app, you need to log in with the following credentials:

#### Admin User:

- Username: A01
- Password: A01
#### Student User:

- Username: Institue roll no (Eg : B200744CS)
- Password: student_password ( Roll no if not changed by user )   
Please use these credentials to log in as either an admin or a student and explore the additional functionalities available to each user type.

## Features

### Students:

1. **Edit Profile:**
   Students can edit their profile information, including their name, hostel details, and other relevant information.

2. **Mess Preference:**
   Students can specify their preference for each mess available in the system. This allows them to choose their preferred option for daily meals.

3. **Change Password:**
   Students have the option to change their account password to ensure account security.

4. **Reset Forgotten Password:**
   In case a student forgets their password, there will be a password reset mechanism that allows them to regain access to their account via email verification .

### Admin:

1. **View Student Profiles:**
   Admin users can view the profiles of all the registered students. This feature helps the admin to manage student information efficiently.

2. **View and Edit Mess Details:**
   Admin users have access to view and modify the details of each mess, such as contractor, category, and capacity. This capability enables the admin to update mess-related information as needed.
   
---

Thank you for using our Flask app! If you have any questions, feedback, or encounter any issues, please feel free to [contact us](mailto:livinlumin123@gmail.com). We hope you find this app helpful for your web development journey in Python!
