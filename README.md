- š Hi, Iām @qeex1
- š Iām interested in ...
- š± Iām currently learning ...
- šļø Iām looking to collaborate on ...
- š« How to reach me ...

<!---
qeex1/qeex1 is a āØ special āØ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->hi
var axios = require("axios").default;

var options = {
  method: 'GET',
  url: 'https://translated-mymemory---translation-memory.p.rapidapi.com/createkey',
  headers: {
    'x-rapidapi-host': 'translated-mymemory---translation-memory.p.rapidapi.com',
    'x-rapidapi-key': 'SIGN-UP-FOR-KEY'
  }
};

axios.request(options).then(function (response) {
	console.log(response.data);
}).catch(function (error) {
	console.error(error);
});
