Describe the difference between a cookie, sessionStorage and localStorage

While a cookie, sessionStorage and localStorage are all ways of storing data on the client side, each one of them has it's own storage and expiration limit.

localStorage: stores data with no expiration date and gets cleared only through JavaScript, or clearing the Browser Cache / Locally Stored Data.

sessionStorage: similar to localStorage but expires when the browser closed (not the tab).

Cookie: stores data that has to be sent back to the server with subsequent requests. Its expiration varies based on the type and the expiration duration can be set from either server-side or client-side (normally from server-side).

Cookies are primarily for server-side reading (can also be read on client-side), localStorage and sessionStorage can only be read on client-side.