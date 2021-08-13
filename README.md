# How To use this project

## Important Files
- test.py
    - This is where all the code that connects to google calendar is located at
        - the /test route is acting is a main() function
- credential.json
    - This is my credentials for my google app I had to create(using the google console)to interact with their api's 

## Steps
- Start up the env (source env/bin/activate)
- Run your server on port 8080
- Go to the '/' route
    - go to the '/test' route (This is where you will test the authentication and you can use this route to test other functions I worked on)
    - This is where you authenticate yourself(with your gmail)
        - Flask saves your credentials in its session
    - Only a few emails will work since this is test application(A test application is an appplication not verified by google)
        - I will add memeos and marks codepaths emails to the test emails
- Once you have authenticated yourselves
- You can now test other functions in the '/test' route
- check out the `read_calender()` and `create_event()` functions.
- You can create more functions and test in `test()`function
    - I was testinf `read_calender`
