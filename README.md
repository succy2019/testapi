# testapi end points and payloads

URL https://api.ousttestapi.online/


*Response code 200

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



endpoint to verify otp

      *End Point:  /public/login*
            response 200
           req: {  email,
                   
           }

           res: {
           	token
                }




