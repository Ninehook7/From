<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Form</title>
</head>
<body>
    <h4 style="background-color: powderblue">Technique Individual Registration</h4>
    <form name="frm">
    
        <table cellpadding="7">
            <tr>
                <td>User ID*</td>
                <td><input type="text" name="user_id" required placeholder="Enter user id"></td>
            </tr>
            <tr>
                <td>Password*</td>
                <td><input type="password" id="password" pattern=".{8,}" name="password" required></td>
            </tr>
            <tr>
                <td>Confirm Password*</td>
                <td><input type="password" id="confirm_password" pattern=".{8,}" name="confirm_password" required></td>
            </tr>
        </table>
         <h4 style="background-color: powderblue">Fill Personal Details</h4>
        <table cellpadding="8">
            <tr>
                <td>Name*</td>
                <td><input type="text" name="fname" required placeholder="Enter First name"></td>
            </tr>
            <tr>
                <td>Middle Name</td>
                <td><input type="text" name="mname" placeholder="Enter Middle name">(optional)</td>
            </tr>
            <tr>
                <td>Last Name*</td>
                <td><input type="text" name="lname" required placeholder="Enter Last name"></td>
            </tr>
            <tr>
                <td>Gender*</td>
                <td>
                    <input type="radio" name="gender" value="Male" checked>Male
                    <input type="radio" name="gender" value="Female">Female
                </td>
            </tr>
            <tr>
                <td>Marital Status*</td>
                <td>
                    <input type="radio" name="marital_status" value="Married">Married
                    <input type="radio" name="marital_status" value="Unmarried" checked>Unmarried
                </td>
            </tr>
            <tr>
                <td>Date of Birth*</td>
                <td><input type="date" name="dob" required></td>
            </tr>
            <tr>
                <td>Aadhar Number*</td>
                <td><input type="text" id="txtAadhar"  pattern="[0-9]{4}-[0-9]{4}-[0-9]{4}" placeholder="XXXX-XXXX-XXXX" ></td>
            </tr>
            <tr>
                <td>Pan Card</td>
                <td><input type="text" id="txtpancard" placeholder="Valid pan card No">(optional)</td>
            </tr>
            <tr>
                <td>Email-ID*</td>
                <td><input type="email" name="email" placeholder="Enter your email id"></td>
            </tr>
            <tr>
                <td>Mobile No*</td>
                <td> 
                    <select name="country_code">
                        <option value="+91">+91</option>
                        <option value="+1">+1</option>
                        <option value="+7">+7</option>
                        <option value="+86">+86</option>
                        <option value="+44">+44</option>
                        <option value="+972">+972</option>
                    </select> 
                    <input type="text" name="mobile_no"  size="10" placeholder="Enter your number" required> 
                </td>
            </tr>
            <tr>
                <td>Nationality*</td>
                <td><input type="text" name="nationality" placeholder="Write down your Nationality" required></td>
            </tr>
        </table>
        <table cellpadding="20">
            <h4 style="background-color: powderblue">Residential Address</h4>
            <tr>
                <td>Country Name*</td>
                <td>
                   <select name="country_name" required> 
                        <option value="India">India</option>
                        <option value="USA">USA</option>
                        <option value="Russia">Russia</option>
                        <option value="China">China</option>
                        <option value="UK">UK</option>
                        <option value="Israel">Israel</option>
                    </select> 

                </td>
            </tr>
            <tr>
                <td>Area/Locality</td>
                <td><input type="text" name="area_locality" placeholder="Write down your area/locality">(optional)</td>
            </tr>
            <tr> 
                <td>State*</td>
                <td><input type="text" name="state" placeholder="Enter your state name" required></td>
            </tr>
            <tr> 
                <td>City/Town*</td>
                <td><input type="text" name="city_town" placeholder="Enter your City/Town" required></td>
            </tr>
            <tr> 
                <td>Post Office*</td>
                <td><input type="text" name="post_office" placeholder="Enter your Post Office" required></td>
            </tr>
            <tr> 
                <td>Pin Code*</td>
                <td><input type="text" name="pin_code" placeholder="Enter your Pin Code" required></td>
            </tr>
            <tr>
                <td colspan="2">
                    <input type="submit" value="Submit">
                </td>
            </tr>
        </table>
        
            
    </form>
</body>
</html>
