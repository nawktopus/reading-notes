# APIs

## API Design Best Practices

1. What does REST stand for?

REST stands for Representational State Transfer.

2. REST APIs are designed around a ____.

Resources.

3. What is an identifier of a resource? Give an example.

They're a type of URI, Uniformed Resource Identifier. For example a RUI for a particular customer order can be `https://adventure-works.com/orders/1`.

4. What are the most common HTTP verbs?

The most common HTTP Verbs are **GET**, **POST**, **PUT**, **PATCH**, and **DELETE**.

5. What should the URIs be based on?
    
The URI should be nouns(the resource) and not verbs (the operations on the resource).

6. Give an example of a good URI.
    
`https://adventure-works.com/orders`

7. What does it mean to have a ‘chatty’ web API? Is this a good or a bad thing?
    
It is when multiple amounts of small data is requested, rather than one large amount of data in one request. It's bad because it adds a big load on the server. 

8. What status code does a successful GET request return?
    
200(OK)

9. What status code does an unsuccessful GET request return?
    
404(Not Found)

10. What status code does a successful POST request return?
    
200(OK) or 201(Created)

11. What status code does a successful DELETE request return?

204(No Content)

## Things I want to know more about

## Resources

[API](https://learn.microsoft.com/en-us/azure/architecture/best-practices/api-design)
