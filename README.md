

HTML provides two objects for storing data on the browser
 - `window.localStorage` - stores data with no expiration date
 - `window.sessionStorage` - stores data for one session (data is lost when the browser tab is closed)

 ## Write
 ```js
const result = localStorage.getItem("key")
// result: "something"
 ```

 ## Read
 ```js
localStorage.setItem("key","something")
 ```