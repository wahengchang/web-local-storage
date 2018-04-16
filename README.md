

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

 ![image](https://user-images.githubusercontent.com/5538753/38788424-263e6aae-4166-11e8-9643-a9c0ec200a6a.png)
