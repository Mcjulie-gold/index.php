# index.php
var s ='{"first_name":"Temitayo", "last_name":"Jegede", "id":"HNG-00200", "email":"oluwadarasiwa@gmail.com", "language":"Javascripts"}';
        var obj = JSON.parse(s);
        console.log=("Hello World, this is "+obj.first_name+" "+obj.last_name +" with HNGi7 ID "+obj.id +" using "+obj.language+"for stage2 task Email "+obj.email);
