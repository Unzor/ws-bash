# Not usable anymore
ws-bash has been deleted off of Heroku to save space for the Elephant Runtime package indexer named "erpi". You can still set your project up with Heroku at https://github.com/Unzor/bashbox and replace the URLs in wsbash.min.js with your Heroku project URL.

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
