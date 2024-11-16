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
|   Home     |    


![Screenshot (243)](https://github.com/user-attachments/assets/6236f43f-64b5-474a-8ef4-a1d4c50921c4)




|    Sign up      |    
| ------------- | 


![Screenshot (244)](https://github.com/user-attachments/assets/bb320530-5402-4ebc-ae43-17ada69561b4)

|    Sign In     |    
| ------------- |


![Screenshot (245)](https://github.com/user-attachments/assets/5433a726-5cd3-4d66-90e1-1b62632030f8)


|    Choose Plan    |    
| ------------- |




|   After Choosing Plan     |    
| ------------- |


![Screenshot (242)](https://github.com/user-attachments/assets/00250209-9a86-4b78-951c-e32ae5658e55)


|   Profile     |    
| ------------- |


![Screenshot (240)](https://github.com/user-attachments/assets/3a3b221a-6daf-4080-9f9d-73a94ac69426)
