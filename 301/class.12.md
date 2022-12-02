# CRUD

## Status Codes Based On REST Methods

1. In your own words, describe what each group of status code represents:
        100’s = Informational status codes; usually tell the client that the header part of the request and the server will try to comply before sending the rest.
        200’s = Success codes.
        300’s = Redirection codes, telling the client that the request is in another location.
        400’s = Client error codes, usually wrong URI, timeouts or missing authentication.
        500’s = Server error codes, problems with the server and requests.

2. What is a status code 202?

    202 is accepted, usually used for asynchronous processing. The request is valid and processing is finishing.

3. What is a status code 308?

    308 is permanent redirect, tells client to use a different URL.

4. What code would you use if an update didn’t return data to a client?

    204

5. What code would you use if a resource used to exist but no longer does?

    410

6. What is the ‘Forbidden’ status code?

    403
  
## Build A REST API With Node.js, Express, & MongoDB - Quick

1. Why do we need to pull our MongoDB database string out of our server and put it into our .env?

    It's to maintain the privacy of sensitive data.

2. What is middleware?

    Software that is between the OS and the application running on the OS.

3. What does app.use(express.json()) do?

    Allows express to accept .json files as a body.

4. What does the /:id mean in a route?

    A parameter that we can access by typing request.params.id.

5. What is the difference between PUT and PATCH?

    Patch will update on what the user will pass us. Put would update all the information.

6. How do you make a default value in a schema?

    Default to type.now

7. What does a 500 error status code mean?

    Internal Server Error can be missing header field to unreachable third party service.

8. What is the difference between a status 200 and a status 201?

    200 request was received and processed. 201 successful request and new resource has been created.

## Things I want to know more about

## Resources

[Status Codes Based On REST Methods](https://www.moesif.com/blog/technical/api-design/Which-HTTP-Status-Code-To-Use-For-Every-CRUD-App/)
[Build A REST API](https://www.youtube.com/channel/UCFbNIlppjAuEX4znoulh0Cw)
