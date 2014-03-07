
# google-client-login

  Get a Google client login token from node.

## Example

```js
var login = require('google-client-login');

login('user@gmail.com', 'password', 'analytics', function (err, token) {
  // use the token
});
```
