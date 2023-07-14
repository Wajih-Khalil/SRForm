<!---Student Registration form Assignment--->
<!DOCTYPE >
<html>
<head>
<title>Student Registration Form</title>
<style>
    h3{
    font-family: Calibri; 
    font-size: 24pt;         
    font-style: normal; 
    font-weight: bold; 
    color:rgb(105, 88, 205);
    text-align: center; 
    text-decoration: underline
  }
  
  table{
    font-family: Calibri; 
    color:white; 
    font-size: 10pt; 
    font-style: normal;
    font-weight: bold;
    text-align:; 
    background-color: rgb(105, 88, 205); 
    border-collapse: collapse; 
    
  }
  table.inner{
    border: 0px;
  }
</style>
</head>
<body>
<h3>STUDENT REGISTRATION FORM</h3>

<form id="myForm">
<table margin="center" cellpadding="10">
 
<!-- First Name -->
<tr>
<td>FIRST NAME</td>
<td><input type="text" name="first_Name" maxlength="30"/>
(max 30 characters a-z and A-Z)
</td>
</tr>
 
<!-- Last Name -->
<tr>
<td>LAST NAME</td>
<td><input type="text" name="last_Name" maxlength="30"/>
(max 30 characters a-z and A-Z)
</td>
</tr>
 
<!-- DoB-->
<tr>
<td>DATE OF BIRTH</td>
 
<td>
<select name="Birthday_day" id="Birthday_Day">
<option value="-1">Day:</option>
<option value="1">1</option>
<option value="2">2</option>
<option value="3">3</option>
<!-- Rest of the options -->
</select>
 
<select id="Birthday_Month" name="Birthday_Month">
<option value="-1">Month:</option>
<option value="January">Jan</option>
<option value="February">Feb</option>
<option value="March">Mar</option>
<!-- Rest of the options -->
</select>
 
<select name="Birthday_Year" id="Birthday_Year">
<option value="-1">Year:</option>
<option value="2012">2012</option>
<option value="2011">2011</option>
<option value="2010">2010</option>
<!-- Rest of the options -->
</select>
</td>
</tr>
 
<!--email Id-->
<tr>
<td>EMAIL ID</td>
<td><input type="text" name="Email_Id" maxlength="100" /></td>
</tr>
 
<!--mobile num -->
<tr>
<td>MOBILE NUMBER</td>
<td>
<input type="text" name="Mobile_Number" maxlength="10" />
(10 digit number)
</td>
</tr>
 
<!-- gender -->
<tr>
<td>GENDER</td>
<td>
Male <input type="radio" name="Gender" value="Male" />
Female <input type="radio" name="Gender" value="Female" />
</td>
</tr>
 
<!-- address -->
<tr>
<td>ADDRESS <br /><br /><br /></td>
<td><textarea name="Address" rows="4" cols="30"></textarea></td>
</tr>
 
<!-- city -->
<tr>
<td>CITY</td>
<td><input type="text" name="City" maxlength="30" />
(max 30 characters a-z and A-Z)
</td>
</tr>
 
<!-- pincode -->
<tr>
<td>PIN CODE</td>
<td><input type="text" name="Pin_Code" maxlength="6" />
(6 digit number)
</td>
</tr>
 
<!--state -->
<tr>
<td>STATE</td>
<td><input type="text" name="State" maxlength="30" />
(max 30 characters a-z and A-Z)
</td>
</tr>
 
<!-- country -->
<tr>
<td>COUNTRY</td>
<td><input type="text" name="Country" value="Pakistan" readonly="readonly" /></td>
</tr>
 
<!-- hobbies -->
<tr>
<td>HOBBIES <br /><br /><br /></td>
<td>
Drawing
<input type="checkbox" name="Hobby_Drawing" value="Drawing" />
Singing
<input type="checkbox" name="Hobby_Singing" value="Singing" />
Dancing
<input type="checkbox" name="Hobby_Dancing" value="Dancing" />
Sketching
<input type="checkbox" name="Hobby_Cooking" value="Cooking" />
<br />
Others
<input type="checkbox" name="Hobby_Other" value="Other">
<input type="text" name="Other_Hobby" maxlength="30" />
</td>
</tr>
 
<!-- qualification-->
<tr>
<td>QUALIFICATION <br /><br /><br /><br /><br /><br /><br /></td>
 
<td>
<table>
<!-- Qualification table rows -->
<tr>
    <td>QUALIFICATION <br /><br /><br /><br /><br /><br /><br /></td>
     
    <td>
    <table>
     
    <tr>
    <td align="center"><b>Sl.No.</b></td>
    <td align="center"><b>Examination</b></td>
    <td align="center"><b>Board</b></td>
    <td align="center"><b>Percentage</b></td>
    <td align="center"><b>Year of Passing</b></td>
    </tr>
     
    <tr>
    <td>1</td>
    <td>Class X</td>
    <td><input type="text" name="ClassX_Board" maxlength="30" /></td>
    <td><input type="text" name="ClassX_Percentage" maxlength="30" /></td>
    <td><input type="text" name="ClassX_YrOfPassing" maxlength="30" /></td>
    </tr>
     
    <tr>
    <td>2</td>
    <td>Class XII</td>
    <td><input type="text" name="ClassXII_Board" maxlength="30" /></td>
    <td><input type="text" name="ClassXII_Percentage" maxlength="30" /></td>
    <td><input type="text" name="ClassXII_YrOfPassing" maxlength="30" /></td>
    </tr>
     
    <tr>
    <td>3</td>
    <td>Graduation</td>
    <td><input type="text" name="Graduation_Board" maxlength="30" /></td>
    <td><input type="text" name="Graduation_Percentage" maxlength="30" /></td>
    <td><input type="text" name="Graduation_YrOfPassing" maxlength="30" /></td>
    </tr>
     
    <tr>
    <td>4</td>
    <td>Masters</td>
    <td><input type="text" name="Masters_Board" maxlength="30" /></td>
    <td><input type="text" name="Masters_Percentage" maxlength="30" /></td>
    <td><input type="text" name="Masters_YrOfPassing" maxlength="30" /></td>
    </tr>
     
    <tr>
    <td></td>
    <td></td>
    <td align="center">(10 char max)</td>
    <td align="center">(upto 2 decimal)</td>
    </tr>
    </table>
     
    </td>
    </tr>
<!-- course -->
<tr>
<td>COURSES<br />APPLIED FOR</td>
<td>
BCA
<input type="radio" name="Course_BCA" value="BCA">
B.Com
<input type="radio" name="Course_BCom" value="B.Com">
B.Sc
<input type="radio" name="Course_BSc" value="B.Sc">
B.A
<input type="radio" name="Course_BA" value="B.A">
</td>
</tr>
 
<!-- submit-->
<tr>
<td colspan="2" align="center">
<input type="submit" value="Submit">
<!-- reset -->
<input type="reset" value="Reset">
</td>
</tr>
</table>
</form>
 
</body>
</html>
