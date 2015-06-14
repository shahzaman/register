<!doctype html>
<html>
<head>
    <title>Register</title>
    <link href="style.css" rel="stylesheet">
</head>

<body>


<div class="header">
     <div class="header_bar">
        <img src="images/logo.jpg" width="150" height="100">
        
</div>
    
</div>

   <section data-role="content">
            <div class="content">
                
<form action="Register.php" name="myForm"  enctype="multipart/form-data" id="Form1" method="post" >

    <h2>Registration</h2>
    <p>To register, fill in the form below and click on the Confirm button at the bottom of the form.</p>
    <div class="reg_head_bar">Entry of contact details <small style="font-weight: normal">(The fields followed by an * are mandatory)</small></div>
    <div class="content_reg3" style="background: none">
        <div class="inline" style="margin-top: 5px">
            <input  id="NullUserID" name="NullUserID" type="hidden" value=""  />
            <div class="label">Company</div>
            <div class="control">
                <input class="txt_box" id="txtCompany" maxlength="50" name="Company" placeholder="Company" type="text" value="" />
               
            </div>
        </div>
        <div class="inline">
            <div class="label">First name *</div>
            <div class="control">
                <input class="txt_box"  id="txtFirstName" maxlength="25" name="FirstName" placeholder="Firstname" type="text" value="" required />
               
            </div>
        </div>
        <div class="inline">
            <div class="label">Last name *</div>
            <div class="control">
                <input class="txt_box"  id="txtLastName" maxlength="25" name="LastName" placeholder="Lastname" type="text" value="" required />
               
            </div>
        </div>
        <div class="inline">
            <div class="label">Address *</div>
            <div class="control">
                <input class="txt_box"  id="txtAddress" maxlength="250" name="Address" placeholder="Address" type="text" value="" required />
                
            </div>
        </div>
       
        <div class="inline">
            <div class="label">Country *</div>
            <div class="control">
                <select class="reg3 drop" name="Country">
                    <option>Pakistan</option>
                </select>
            </div>
        </div>
        <div class="inline">
            <div class="label">Punjab *</div>
            <div class="control">
                <select class="drop"  id="ddlProvince" name="City" ><option value="Null">City</option>
<option value="Lahore">Lahore</option>
<option value="Gujranwala">Gujranwala</option>
<option value="Islamabad">Islamabad</option>
<option value="Faislabad">Fasilabad</option>

</select>
               
            </div>
        </div>
        
        <div class="inline">
            <div class="label">Email *</div>
            <div class="control">
                <input class="txt_box"  id="txtEmail" maxlength="50" name="Email" placeholder="Email" type="text" value="" required />
               
            </div>
        </div>
        <div class="inline">
            <div class="label">Mobile *</div>
            <div class="control">
                <input class="txt_box"   id="txtMobile" maxlength="20" name="Mobile" type="text" value="" placeholder="Mobile" required />
               
            </div>
        </div>
    

     
   
      
    </div>
    <div class="content_reg3" style="background: none">
        <div class="reg3_head_bar" style="background: #eee">Choose an ID and password to access your account</div>
        <div class="inline" style="margin-top: 5px">
            <div class="label">Username *</div>
            <div class="control">
<input class="txt_box"  id="txtUserName" maxlength="15" name="UserName" type="text" value="" placeholder="Username" required/>                    
<div class="username_avail_result" id="username_avail_result"></div>
        </div>
        </div>
                        <div class="inline">
                <div class="label">Password *</div>
                <div class="control">
                    <input class="txt_box"    id="txtPassword" maxlength="15" name="Pass_word" type="Password" value="" placeholder="Password" required/>
                    <div class="password_strength" id="password_strength"></div>
                    
                </div>
            </div>
            <div class="inline">
                <div class="label">Password confirmation *</div>
                <div class="control">
                    <input class="txt_box"   id="txtConfirmPass" maxlength="15" name="ConfirmPassword" type="Password" value="" placeholder="Repassword" required/>
                   
                </div>
            </div>
			
			 <div class="inline">
            <div class="label">&nbsp;</div>
            <div class="control">
                <p class="comment">
                        <input type="submit" id="btnSubmit" class="reg3_validate btn_dark"  />
                </p>
            </div>
			</div>

       
                
        </div>
    </div>
    
</form>




            </div>
        </section>
<section data-role="footer" class="footer">
            <footer>
                <div class="footer">
                        
                </div>
            </footer>
        </section>
    </div>

</body>
</html>
