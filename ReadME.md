# NTUNS-CourseUpdate

## config

Add cofig in cofig folder `config/config.js`

Content:
```javascript
module.exports =
{
    HTTPServer:
    {
        "viewsRoot": "./views",
        "httpPort": 30087,
        "httpsPort": 7878,
        "host" : "127.0.0.1" ,
        "timeout": 30000
    },
    MONGODB: {
        "host" : "127.0.0.1" , 
        "port" : 27017 , 
        "db" : "My_ntunhs" , 
        "ssl" : false ,
        "username" : "user" , 
        "password" : "password" , 
        "authDB" : "admin"
    }
};
```