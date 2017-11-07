# api-manager
#### hostname=bvvy.free.ngrok.cc

###### login
const CLIENT = "eagleeye"
const SECRET = "thisissecret"
 ```
  获取token:
    post <hostname>api/auth/oauth/token
          header: 
            headers: {
              "Authorization":"Basic "+ btoa(CLIENT + ":"+ SECRET)
            }
          body: 
            grant_type: password
            scope: webclient
            username: john.carnell
            passwrod: password1
  
 ```
