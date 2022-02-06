# ws-bash
A JavaScript library for running Bash using WebSocket connections only.

# Usage (synchronous)
```javascript
run(<command here>).then((res) => {
console.log(res);
})
```
# Usage (asynchronous)
```javascript
var result = await run(<command here>);
console.log(result);
```
