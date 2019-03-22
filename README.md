# jsforwordpress_bootcamp
JavaScript for Wordpress Bootacamp project Jan-March 2019

•	Overview
Accesing to the Ranch Systems online database through its JSON web service interface. 

The RS web services implementation is RESTful, it uses simple HTTP requests like GET and POST, I’m going to focus on GET requests though so that I can fetch and show the required information.

• Fetch information using GET requests

1. Get all properties that a particular user is authorized to access:
```
https://app.ranchsystems.com/rsapp15/jsp?uname=jdoe&pword=qwerty&reqtype=props
```

2. Will return something like:

```
{  
   "props"    : [{"title":"Test Ranch 1","lasttime":1342565519000,"rsuname":"TRANCH1"},
                 {"title":"Test Ranch 2","lasttime":1342565519000,"rsuname":"TRANCH2"}],
   "lastprop" : "JCTEST",
   "auth"     : true
}
```


