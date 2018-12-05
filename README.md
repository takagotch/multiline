### multiline
---
https://github.com/sindresorhus/multiline

```js
const str = '' +
'<!doctype html>' +
'<html>' + 
'  <body>' +
'    <h1> unicorns</h1>' +
'  </body>' +
'</html>' +
'';

const str = multiline(()=>{/*
<!doctype html>
<html>
  <body>
    <h1> unicorns</h1>
  </body>
</html>
*/);

const str = multiline(()=>{/*
<!doctype>
<html>
  <body>
    <h1> unicorns</h1>
  </body>
</html>
*/});

const str = 'unicorns';
console.log(multiline(()=>{/*
  I love %s
*/}), str);

const str = 'foo\n' +
'bar';
```

```
npm install multiline
```

```
```
