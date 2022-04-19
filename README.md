## Features:  
- Login/Logout using Auth0
- SPA Routing with React Router DOM
- Searching for Github User using Github API
- Display charts using Fusion Charts

## Technologies:  
- Github API
- React Router DOM
- Axios
- Styled Components
- React Icons
- Fusion Charts (Pie Chart, Column Chart,...)
- Context API
- Searching
- Auth0

#### Redirects with react-router-dom

In order for routing to work on netlify, redirects was added to the public folder

- \_redirects file in public

```

/*    /index.html   200

```

[Redirects Blog Post](https://dev.to/dance2die/page-not-found-on-netlify-with-react-router-58mc)

#### Warnings and create-react-app

package.json

```js
"build": "CI= react-scripts build",
```

[create-react-app Warning Fix Blog Post](https://community.netlify.com/t/how-to-fix-build-failures-with-create-react-app-in-production/17752)
