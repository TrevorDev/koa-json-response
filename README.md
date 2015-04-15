koa-json-response
=================

Easily generate json response with error code
```
var koa = require('koa')
var app = koa()
var jsonResp = require('koa-json-response')
app.use(jsonResp())
app.get('/test', function*(){
	return this.jsonResp(200, {msg: "HELLO_WORLD"});
})
```
