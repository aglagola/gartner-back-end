# gartner-back-end
Spring Boot Endpoint

This is a Sprint Boot Application. This application creates an endpoint on localhost:8080/api that fetches json data from
"https://www.alphavantage.co/query?function=TIME_SERIES_DAILY&symbol=IBM&apikey=demo"
For the sake of this application I have removed the api key and used a demo url for the endpoint.
This app allows cors from origin port 3000 to make api calls to the endpoint, so when running your front end make sure it is running on port 3000

Steps
--------

1. clone repository to local machine
2. open with ide such as intellij
3. Run Application
4. Test endpoint localhost:8080/api (optional)
5. Clone front end to local machine
6. Run front end React Application using command 'npm start'
7. Done.


GitHub Repo: https://github.com/aglagola/gartner-back-end