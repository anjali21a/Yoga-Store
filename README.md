# Yoga Classes

## Features
* Accepts the user data, does basic validations.
* Only people within the age limit of 18-65 can enroll for the monthly classes and they will
be paying the fees on a month on month basis. I.e. an individual will have to pay the fees
every month and he can pay it any time of the month.
* They can enroll any day but they will have to pay for the entire month. The monthly fee is
500/- Rs INR.
* There are a total of 4 batches a day namely 6-7AM, 7-8AM, 8-9AM and 5-6PM. The
participants can choose any batch in a month and can move to any other batch next
month. I.e. participants can shift from one batch to another in different months but in
same month they need to be in same batch.
* Return the response to front-end depending on the payment response from
CompletePayment() function.
* Use of REST-API


## ENVIRONMENT VARIABLE REQUIRED FOR RUNNING THIS APPLICATION LOCALLY
* MONGODB_URI 
* JWT_SECRET
* PORT

## API USED :
1. /home    (Home page)
2. /signin (Page for Existing user to sign in again)
3. /signup (Page for Registering)
4. /chooseplan ( Page for choosing the batch and payment)
5. /profile ( Display all the users data in Profile Page) 


## ER DIAGRAM
![ER DIAGRAM](https://user-images.githubusercontent.com/65064180/207200877-92968c81-e896-4116-abb0-3988624f745e.png)



## Screen shots 📸
[Signup]: ![Screenshot (243)](https://github.com/user-attachments/assets/5bf6d94e-dfe8-48be-a1d8-7a4af4a0446d)

[SignIn]: 
![Screenshot (244)](https://github.com/user-attachments/assets/39dcf8ae-504a-4a74-8968-2d91d83fa417)

[Home]: 
[Cho![Screenshot (243)](https://github.com/user-attachments/assets/619870a4-65a3-4b25-92c2-bf37f89a087c)
ose Pla![Screenshot (243)](https://github.com/user-attachments/assets/a822247e-8934-4dcb-ad13-a84d1954abf0)
n]: https://user-images.githubusercontent.com/65064180/207203802-7d6c5ca2-1098-41af-970e-e97b3ce2ee38.png
[After Choosing Plan]: https://user-images.githubusercontent.com/65064180/207203804-5bba86e5-6af5-4a48-843d-741afa84870f.png
[Profile]: 



|   Home     |    
| ------------- |
|![alt text][Home]  | 

|    Sign up      |    
| ------------- | 
|![alt text][Signup]  | 


|    Sign In     |    
| ------------- |
|![alt text][SignIn]  | 



|    Choose Plan    |    
| ------------- |
|![alt text][Choose Plan]  | 



|   After Choosing Plan     |    
| ------------- |
|![alt text][After Choosing Plan]  | 



|   Profile     |    
| ------------- |
|![alt text][Profile]  | 

