var http = require('http');

var serverku = http.createServer(function (req,res){
	res.end("Selalu ada di nodejs");
});

serverku.listen(1234);
console.log("Alwasys in 1234 server");
