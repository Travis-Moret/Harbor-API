# Harbor-API
A RESTful API build with Python and Flask and Hosted on GCP. Requires Authentication and Authorization through Auth0 to use with Postman. 

# Instructions for use:

Getting a JWT: 

1. To use the program, first navigate to https://final-api-morett.uc.r.appspot.com/

2. On the home page, click the 'Log in or create an account' button

3. When the log in page appears, sign in, or create a new account. New accounts can be created with an email or password, or by clicking 'Continue with Google' 

4. If 'Continue with Google' is clicked, permissions will be requested. Please accept the permissions. 

5. Once signed in or if a new account is created, a valid JWT and authentication will be displayed on the screen. This JWT and a JWT from a second account you create will be needed to access protected elements in the Harbor API. 

Setting up Postman: 

1. Running the API with authentication requires some knowledge of Postman for Desktop. 

2. If Postman for Desktop is installed, click import in the upper lefthand corner. 

3. Use the import button to import the environment file morett_project.postman_environment.json from the Postman folder in these source files. 

4. Next, use import to import the Postman collection morett_project.postman_collection.json from the Postman folder in these source files. 

5. Modify the values of JWT_1 and JWT_2 in the environment with the values of the JWTs gained from the previous steps of the authentication process. 

6. Click 'Run collection' to run the collection with the environment. 

7. Output of the test suite will be shown on the screen, and request and response body output can be seen by clicking 'Console' on the bottom left of the screen. 

Viewing Documentation: 

1. The documentation for proper output ane error handling of the API can be viewed under morett_project.pdf in the docs folder