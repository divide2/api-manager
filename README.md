# api-manager
#### hostname=bvvy.free.ngrok.cc

###### login
 ```
  获取token:
    post <hostname>api/auth/oauth/token
          header: username:eagleeye  password:thisissecret  Basic Auth
          body: 
            grant_type: password
            scope: webclient
            username: john.carnell
            passwrod: password1
  
 ```
