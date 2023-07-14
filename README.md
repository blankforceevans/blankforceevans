### Hi there 👋<!DOCTYPE HTML>
<html>
 <head>
  <title>Course Registration Form</title>
  <stle>
   body{background-color: #f1f1f1;
    font-family: Arial, sans-serif;}
    h2{colour: #333333;}
    .form-container{
     width: 400px;
     margin: 0 auto;
     background-color: #ffffff;
     padding: 20px;
     border-radius:5px;
     box-shadow: 0px 0px 10px rgba(0, 0, 0.1);
    }

     .form-container lable{
       display: block;
       margin-bottom: 10px;
    }

    .form-container input[type="text"],
    .form-container input[type="tel"],
    .form-container input[type="number"]
{
      width: 100%;
      padding: 10px;
      margin-bottom:20px;
      border-radius: 30px;
      border: 1px solid #cccccc;
     }

     .form-container input[type=:"radio"]
}
       margin-right: 5px;
     }  
      
     .form-container .submit-btn{
       background-color: #333333;
       color #ffffff;
       border: none;
       padding: 10px 20px;
       cursor: pointer;
     }
   </style>
 </head>
 <body>
   <div class="form-container">
     <h2>Student Registration Form<h2>
     <form>
       <lable for=studentName:</lable>
       <input type="text"
id="studentName" name="studentName" required>

       <lable for="telephone">Telephone
Number:</lable> 
       <input type="tel" id="telepone"
name="telphone" required>

       <lable for="dob">Date of Birth:</lable>
       <input type="text" id="dob"
name="dob placeholder="YYYY-MM-DD" required>

       <label
for="admissionNumber">Amission
Number:</lable>
      <input type="text"
id="admissionNumber"
name="admissionNumber" required>

       <lable for="course">course:</lable>
       <select id="course" name="course">
        <option value="CBIT">CBIT</OPTION>
        <option value ="CIT">CIT</option>
       <lable for="gender">Gender:</lable>
       <input type="radio" id="male"
name="gender" value="male" required>
       <lable for="male">Male</lable>
       <input type="radio" id="female"
name="gender" value="female" required>
       <lable for ="female">Female</lable>

       <input type="submit"
value="Submit" class="submit-btn">
     </form>
   </div>
 </body>
 </html> 



