<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Resume form</title>
</head>
<body>
  <h1>Resume submission form</h1>
  <hr/>
<form>
  <label>Full name</label>
  <input type="text" name="full name">
  <br><br/>

  <label>Email</label>
  <input type="text" name="Email">
  <br><br/>
  <label>Address</label>
  <input type="text" name="Address">
  <br><br/>
  <label>Phone number</label>
  <input type="integer" name="phone number">

  <br><br/>
  <label>Date of birth</label>
  <input type="Date" name="Date of birth">
  <br><br/>
  <label>Gender</label>
  <input type="radio"name="gender"value=Male required>Male
  <input type="radio"name="gender"value=female required>Female
  <br></br>
  
  <label>Marital status</label>
  <input type="radio"name="marital status"value=single required>single
  <input type="radio"name="marital status"value=Married required>married
  <br></br>

  <label>Nationality</label>
  <input type="text"name=natinoality>
  <br></br>
  <label>Address</label>
  <input type="text"name=Adress Rows="3"required></textarea>
  <br></br>
  <label>Linkdin profile url</label>
  <input type="url" name="Linkdin">
  <br></br>
  <label>GitHub profile url</label>
  <input type="url" name="Github">
  <br></br>
  <label>Upload profile photo</label>
  <input type="File"name=photo accept="image/*">
  <br></br>
  <label>Upload Resume (Pdf only)</label>
  <input type="File"name=Resume accept=".pdf">
  <br> </br>
  <label>Career objective</label>
  <input type="text"name="career objective" rows="4" required></textarea>
  <br></br>
  <label>Highest qualification</label>
<input type="ext"name=Qualification>
<br></br>
<label>Name of the college/University</label>
<input type="text"name=college>
<br></br>
<label>Year of graduation</label>
<input type="number"name=graduationyear min="1960" max="2099"required>
<br></br>
<label>Technical skils (HTML,CSS,JS,etc.)</label>
<input type="text"name="skills" rows="3">
<br></br>
<label>Programing languages known</label>
<input type="text" name="languages" rows="3">
<br></br>
<label>Certifications(if any)</label>
<input type="text"name=certifications>
<br></br>
<label>Work experience(Years)</label>
<input type="numbers"name=experience>
<br></br>
<label>Last company worked at</label>
<input type="text"name= "last company worked at">
<br></br>
<label>Your job role/Designation</label>
<input type="text"name="job role">
<br></br>
<label>Language known</label>
<input type="text"name="language known">
<br></br>
<label>Hobbies</label>
<input type="text"name=Hobbies>
<br></br>
<label>Declaration(Checkbox to agree to authenticity)</label>
<input type="checkbox"name=declaration>
<br></br>
        I hereby declare that all the information provided is true to the best of my knowledge
<br></br>
<input type="Submit"value="Submit resume">
</form>



  
</body>
</html>
