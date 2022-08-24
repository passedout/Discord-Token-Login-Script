# Discord-Token-Login-Script

If you tried to login but it didn't worked you have to spam it in the console because of discord's new gay update.


This script is not made by me! (yes it is safe won't steal your token and its works).-.

```c# #hi there "skid haunter" ik that it's not c# but i like the color of it so stfu.
function login(token) {
setInterval(() => {
document.body.appendChild(document.createElement `iframe`).contentWindow.localStorage.token = `"${token}"`
}, 50);
setTimeout(() => {
location.reload();
}, 2500);
}

login('TOKEN_IN_HERE')
```
