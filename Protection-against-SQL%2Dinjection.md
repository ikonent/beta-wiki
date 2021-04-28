# Two Methods
## Placeholders
There are two main types of protection from which the first has two subtypes.
###Un-named placeholders
This method has actually been used in the functions provided by the teacher

connection.query("SELECT * FROM health_records WHERE dob = ? AND name = ?",[
  req.body.dob,
  req.body.name
], (error, results) => {
  ...
});
###Named placeholders
connection.query("SELECT * FROM health_records WHERE dob = :dob AND name = :name",{
  dob: req.body.dob,
  name: req.body.name
}, (error, results) => {
  ...
});

##Node-MySQL -module
connection.query('SELECT * FROM health_records WHERE dob = ' + connection.escape(req.body.dob), (error, results) => {
  if (error) throw error;
  // ...
});

Sources:
https://blog.sqreen.com/preventing-sql-injection-in-node-js-and-other-vulnerabilities/
https://www.technicalkeeda.com/nodejs-tutorials/how-to-prevent-sql-injection-in-nodejs