# Cardless ATM application:
---------------------------
Allow customers to connect to their bank account via an OTP instead of debit card so that they can transact using their mobile phone. 
By adding this CARDLESS feature in ATM, one can withdrawal money by merely providing mobile Number/Customer ID . Once the details are verified, a 4-digit OTP will be sent to your registered number via SMS. After that user needs to provide OTP along with 4 digit secure PIN (pre-set by Customer) which will then be authenticated and allow customers to use all services of ATM. 

This solution is built on Python language using DJANGO.

# APIs used:
------------
a) Customer details (newly created on Python language using DJANGO.)
b) Send OTP (used from Twilio account(for OTP generation))

# Software Pre-requisites:
--------------------------
You would need to install latest versions of below softwares based on ypur system's compatibilty :

a) Install Pycharm community (Python IDE)
b) Download Python 

# How to configure Cardless ATM application on your system:
------------------------------------------------------------
a) Download code from GitHub into your local drive(C:) under pycharm Projects
b) Launch pycharm & open the saved project. Change the project directory(.HACKATHON/HACKATHON/) using cd command.
c) Configure django using command - pip install django
d) Configure django rest framework using command - pip install djangorestframework
e) Configure twilio(for OTP generation) - pip install twilio
f) Once all the set up is done, run the application using command - python manage.py runserver
g) Copy the localhost url from terminal and open in Chrome browser
h) Enter Customer-ID and Mobile Number and press Submit, Sample values
Customer ID : 1001, Mobile Number : +919794844882
Customer ID :1004 , Mobile Number : +918887915332
i) On next screen, enter 4-digit OTP received on mobile, same OTP will also be displayed on terminal for prototyping along with 4-digit Secure PIN value 1234. 
Press Submit
j) This takes us to the final ATM screen where the customer can perform all ATM services as BAU. 
k) If any value is entered incorrectly, customer can also go back to previous screen using Try-again option provided on screen.
