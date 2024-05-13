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


**Send otp to email**


*Endpoint:  /sendotp*

_request_ 

            { 
            email             
            }
_response_     

           { 
           sucess
            }



*Endpoint:  /login*
_request_ 

            {
             email,
             }
_response_

           {
           	userID
            pin
            }


            
*Endpoint:  /SessionLog*
_request_ 

            {
             UserId,
             pin
             }
_response_

           {
           Success
            }



                  
 *Endpoint:  /SessionStart*
_request_ 

            {
             UserId,
             pin
             }
_response_

           {
           Session
           Token
            }






