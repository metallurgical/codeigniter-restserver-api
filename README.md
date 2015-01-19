# Extra - Codeigniter Restserver API

Process:

 * Including CORS
 * In one url line, e.g domain.com/x/dataAll/type/users/format/json
 * Depend on the model


Compatible with :

 * Apache (dav mod need to be enable)
 * nginx

And here's some example handling cors

```php
        header('Access-Control-Allow-Origin: *');
        header('Access-Control-Allow-Credentials: true');
        header('Access-Control-Allow-Method: POST, GET, OPTIONS, PUT, DELETE');
        header("Access-Control-Allow-Headers: X-Custom-Header, X-API-KEY, Origin, X-Requested-With, Content-Type, Accept, Access-Control-Request-Method, Authorization");
```

This is [on GitHub](https://github.com/metallurgical/codeigniter-restserver-api) so let me know if I've forked it somewhere.


### Stuff used to make this:

 * [codeigniter](http://www.codeigniter.com/) PHP Framework
 * [nginx](http://nginx.org/) Web Server
 * [apache](http://www.apache.org/) Web Server
