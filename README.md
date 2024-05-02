# testapi end points and payloads

URL https://api.ousttestapi.online/public/

**REGISTRATION PAYLOAOD**


*End Point:  /api/v1/register*
            
           req: {  firstname,
                   lastname,
                   email,
                   phone
           }

           res: {userID,
                token}

endpoint to verify otp
https://api.ousttestapi.online/public/api/v1/otp

      **Otp payload**
        1. otpcode
      
        //
        Response: message : success


endpoint for Login
https://api.ousttestapi.online/public/api/v1/login
      **Reg payload**
        1. email
     
        //
        Response: token




