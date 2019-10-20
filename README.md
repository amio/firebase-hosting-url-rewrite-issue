## Source

- Function Source: [functions/index.js](functions/index.js)
- Hosting Config: [firebase.json](firebase.json)

## Result

Different output from function endpoint and firebase hosting:

- https://us-central1-hi-ninox.cloudfunctions.net/echo/ei%2fc
    => `/ei%2Fc`

- https://hi-ninox.firebaseapp.com/echo/ei%2fc
    => `/echo/ei/c`
