# Two Methods
## Placeholders
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

Source:
https://blog.sqreen.com/preventing-sql-injection-in-node-js-and-other-vulnerabilities/