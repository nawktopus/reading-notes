# OAuth

## What is OAuth 
  
1. What is OAuth?
    
    OAuth is open standard authorization protocol or framework that safely allows authenticated access to assets without single logon credentials. 
    
2. Give an example of what using OAuth would look like.
    
    QR code access is a big one. You scan the QR code on a different device from the application and it authenticates it automatically.
    
3. How does OAuth work? What are the steps that it takes to authenticate the user?
    
    1. First website connects to second website using OAuth. 2. Second website generates a one time token and secret; client software presents it. 3. user approves and given an approved acces token. 4. Access token to first site, second website appoves. 5. Gain access to new second site.
    
4. What is OpenID?
  
  OpenID is authentication, single sign on. 
  
## Authorization and Authentication flows

1. What is the difference between authorization and authentication?
    
    Authorization determines whether or not someone has access. Authentication determines if user is who they claim to be. 
    
2. What is Authorization Code Flow?
    
    Authorization Code Flow exchanges an authorization code for a token to access the web app.
    
3. What is Authorization Code Flow with Proof Key for Code Exchange (PKCE)?
    
    An Authorization Code Flow with PKCE is an additional security measure when transfering tokens.
    
4. What is Implicit Flow with Form Post?
    
    The web app requests and obtains tokesn through the front channel . You don't need to obtain maintain, use and protect a secret. 
    
5. What is Client Credentials Flow?
    
    Passing along client ID and client secret to authenticate themselves and get a token.
    
6. What is Device Authorization Flow?
    
    This pushes another way to authorize a device via user device. It is usually in the form of a link. 
    
7. What is Resource Owner Password Flow?

  Requests username/password in an interactive form. Highly trusted as it holds the credentials for future use. Possibliity for abuse.
  
## Things I want to know more about

## Resources
[OAuth](https://www.csoonline.com/article/3216404/what-is-oauth-how-the-open-authorization-framework-works.html)
[Auth0](https://auth0.com/docs/get-started/authentication-and-authorization-flow)
