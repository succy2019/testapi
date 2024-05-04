# testapi end points and payloads

**URL https://api.ousttestapi.online/**

**Account Registration**

*Endpoint:  /public/register*

_request_ 

            {firstname,
             lastname,
             email,
             phone}
_response_

           {
           	userID
            }


**Verify otp**


*Endpoint:  /public/otp*

_request_ 

            { 
            otpcode             
            }
_response_     

           { Successs
            }



**Login**

*End Point:  /public/login*

_response_ 

           
           {  email
           }
           
_response_  

           {
           	userId
            }




