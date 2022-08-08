# Login Authentication to React Applications

https://www.digitalocean.com/community/tutorials/how-to-add-login-authentication-to-react-applications
https://www.digitalocean.com/community/tutorials/how-to-build-forms-in-react

## Steps

### Step 1 — Building a Login Page (React)

```
npx create-react-app auth-tutorial

cd auth-tutorial
npm install react-router-dom

mkdir src/components
mv src/App.* src/components/App

# In index.js, add the following lines: import App from './components/App/App';

npm start
```

### Step 2 — Creating a Token API (Express)

```
npm install --save-dev express cors

# Create server.js
# Warning: Do not enable CORS for all routes in a production application. This can lead to security vulnerabilities.

node server.js
```

### Step 3 — Storing a User Token with sessionStorage and localStorage

