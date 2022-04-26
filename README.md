# `react-portfolio`

> react based portfolio website

## What's Used?

![shield-nodejs][shield-nodejs]
![shield-react][shield-react]
![shield-react-router][shield-react-router]

## Quickstart

To run the app, execute the following script below.  Your react app will be launched in `http://localhost:3000`

```bash
npm start
```

## To Enable EmailJs

- Register an account for [EmailJs][emailJs]
- Create followings afterwards
    - Email Service (`REACT_APP_EMAILJS_SERVICE_ID`)
    - Email Template (`REACT_APP_EMAILJS_TEMPLATE_ID`)
- Retrieve Public Key(`REACT_APP_EMAILJS_PUBLIC_KEY`) from Account section
- Create file named `.env` in root directory.
- Fill up following variables

```
REACT_APP_EMAILJS_PUBLIC_KEY=...
REACT_APP_EMAILJS_SERVICE_ID=...
REACT_APP_EMAILJS_TEMPLATE_ID=...
```


[shield-nodejs]: https://img.shields.io/badge/node.js-16.x-339933?logo=nodedotjs&logoColor=339933&style=flat-square
[shield-react]: https://img.shields.io/badge/react-18.x-61DAFB?logo=react&logoColor=61DAFB&style=flat-square
[shield-react-router]: https://img.shields.io/badge/reactRouter-6.x-CA4245?logo=reactrouter&logoColor=CA4245&style=flat-square
[emailJs]: https://emailjs.com

[youtube]: https://youtu.be/ESHaail1eGc