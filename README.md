# Admission_Enquiry_Form
## Date: 07.07.2025

## Objective:
To design a simple Admission Enquiry Form using basic HTML that collects student details such as name, contact, program of interest, and a message for further communication.

## Tasks:
#### 1. Set Up the HTML Structure:
Use ```<!DOCTYPE html>```, ```<html>```, ```<head>```, and ```<body>``` tags to define the document structure.
Set the ```<title>``` as "Admission Enquiry Form".

#### 2. Add a Page Heading:
Use ```<h1>``` to title the page as “Admission Enquiry”.

#### 3. Create the Form Layout:
Use the ```<form>``` tag to wrap all input elements. Set method="post" for structure.

#### 4. Add Input Fields:
Include the following fields using appropriate HTML elements:

Full Name

Email Address

Phone Number 

Program of Interest 

Message

#### 5. Add Submit and Reset Buttons:
Use submit and reset at the bottom of the form.

#### 6. Use HTML-only:
No CSS or JavaScript is to be included. Focus on structure and accessibility.

## HTML Code:
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Admission Enquiry-SEC</title>
</head>
<body>
    <form>
        <h1>Saveetha Engineering College</h1>
        <h2>Admission Enquiry Form</h2>
        <lavel>Full Name : </lavel> <input type="text">
        <br><br>
        <label>Email Address : </label> <input type="text">
        <br><br>
        <label>Phone : </label> <input type = "text" maxlength = 10>
        <br><br>
        <label name = "gender">Gender : </label>
        <input type="radio" name = "gender">Male
        <input type="radio" name = "gender">Female
        <input type="radio" name = "gender">Others
        <br><br>
        <label>D.O.B : </label> <input type = "date"><br><br>
        <label>Department Interested : </label>
        <Select>
            <option >Select Department</option>
            <option >CSE</option>
            <option >ECE</option>
            <option >AIDS</option>
            <option >AIML</option>
            <option >CSE(Iot)</option>
            <option >CSE(Cyber Security)</option>
            <option >Mechanical</option>
            <option >Civil</option>
        </Select>
        <br><br>
        <label>Academic Qualification : </label>
        <textArea cols = 50 rows = 4></textArea>
        <br><br>
        <label>Address : </label>
        <textArea cols = 50 rows = 4></textArea>
        <br><br>
        <label>Preferred Mode of Contact : </label>
        <input type = "checkbox">Email
        <input type = "checkbox">Phone
        <br><br>
        <button>Submit</button>
        <button type="reset">Clear</button>
    </form>
</body>
</html>
```
## Output:
![Screenshot 2025-07-07 141620](https://github.com/user-attachments/assets/24eed6c4-ddb6-427a-9cfa-7c40e9e4ac00)


## Live Web Page:
https://roshanr-git.github.io/Admission_Enquiry_Form/

## Result:
An Admission Enquiry Form using HTML that collects student details and message for institutional follow-up is successfully created using semantic and readable HTML.
