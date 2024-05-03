# testapi end points and payloads

URL https://api.ousttestapi.online/public/

**REGISTRATION PAYLOAOD**
*Response 201

*End Point:  /public/register*
            
           req: {  firstname,
                   lastname,
                   email,
                   phone
           }

           res: {
           userID
                }

endpoint to verify otp


      *End Point:  /public/otp*
            
           req: {  otpcode,
                   
           }

           res: {
           message: Successs
                }

endpoint for Login
https://api.ousttestapi.online/public/api/v1/login
      **Reg payload**
        1. email
     
        //
        Response: token




