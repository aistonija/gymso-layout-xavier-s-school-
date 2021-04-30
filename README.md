### Initial setup

- npm init
- npm install express
- add all files to src folder
- create index.js and add following code:

```javascript
const express = require("express");
const app = express();
const port = 3000;

app.use(express.static("src"));

app.listen(port, () => {
  console.log(`Example app listening at http://localhost:${port}`);
});
```

- node index.js

### Clone setup

- npm install
- node index.js
