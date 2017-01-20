# angularStudy
Self study for anguarJS 

var connect = require('connect');
serveStatic = require('serve-static');

var app = connect();

app.use(serveStatic("./chapter1"));
app.listen(5000);

