# Quick_credit
Description
Countries is a RESTful API for getting loans.

Table of Contents
Technologies
Features
Installation
Technologies
Nodejs (Express framework)
Features
User (client) can sign up.
2. User (client) can login.
3. User (client) can request for only one loan at a time.
4. User (client) can view loan repayment history, to keep track of his/her liability or
responsibilities.
5. Admin can mark a client as verified, after confirming his/her home and work address.
6. Admin can view a specific loan application.
7. Admin can approve or reject a client’s loan application.
8. Admin can post loan repayment transaction in favour of a client.
9. Admin can view all loan applications.
10. Admin can view all current loans (not fully repaid).
11. Admin can view all repaid loans.
git clone https://github.com/Naimaoye/Quick_credit.git
cd Quick_credit
git checkout develop
run npm install
PORT
SECRET_KEY
USER
PASSWORD
run npm start
Test with Postman
install POSTMAN app
navigate to localhost:PORT/endpoints on POSTMAN
Request body for Login is username AND password while for POST and DELET is countryName
Request header token must be set to access all the routes except login
API Endpoint Route
Currently,

HTTP VERB	ENDPOINT	TASK
POST	api/login/	User Login
POST	api/countries	Add Country to the list
GET	api/countries	Get All Country
DELETE	api/countries	Delete a specific country base on the name
Author
Akinyele Oluwatosin
