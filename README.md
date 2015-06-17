# TodoExpressDocs
- This is light weight documentation for a Todo app using built in ExpressDocs

# Installing Express-Docs
- npm install express-mongoose-docs

# Using Express-Docs
- Add These lines to your app.js file:
	- var docs = require("express-mongoose-docs");
	- docs(app, mongoose); // 2nd param is optional, and make sure this comes after all the express middleware.
- Use: http://localhost:3000/apiDocs to view docs
