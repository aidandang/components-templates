This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app).

## React Router DOM Dependency Setup

1. Install `react-router-dom` dependency:
- In the application directory open terminal type: `npm install react-router-dom --save`

2. Setup RouterBrowser component to wrap all router components inside:
- Open index.js file from the root application directory.
- Import RouterBrowser component: `import { BrowserRouter } from 'react-router-dom';`
- Wrap <App /> with <RouterBrowser />: `<RouterBrowser><App /></RouterBrowser>`