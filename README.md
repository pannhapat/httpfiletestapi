# httpfiletestapi
file http test rest api

Install extention vs code REST-CLIENT

https://marketplace.visualstudio.com/items?itemName=humao.rest-client

# start POST copy to filename

@baseUrl = http://localhost:5000

@apiname = users


POST {{baseUrl}}/{{apiname}} HTTP/1.1

Content-Type: application/json

 

{

  "fname":"fname",

  "lname":"lname",

  "username":"test@email.com",

  "password":"*****",

  "avatar":"http://localhost:5000/public/images/users/user1.jpg"

}

# end

 
