Great! Now you are done learning about major concepts of GraphQL and how it can be useful for development. So let's get started on the application that we are going to build. 

Without wasting any more time, we can directly jump into the GraphQL code as we already have the boilerplate UI ready [here](). You can clone it and start your GraphQL journery immediatedly.

This tutorial uses `create-react-app` with a few other essential modules for styles (`react-bootstrap`) , routing (`react-router`) and workflow tooling (`eslint`, `prettier`, `prop-types`). And for authentication we use `Auth0`.

The backend is already built and available here - <link>. You will make use of this for testing and building your frontend app with graphql integration.

Once you have cloned the boilerplate, create a `.env` file in the root directory and paste the following:

```
REACT_APP_GRAPHQL_URL=https://hasura-todo-test.herokuapp.com/v1alpha1/graphql
REACT_APP_REALTIME_GRAPHQL_URL=wss://hasura-todo-test.herokuapp.com/v1alpha1/graphql
```

Here we are setting up environment variables to be used inside our todo app. Since we have our backend ready (powered by Hasura), we will use the graphql endpoint and the realtime websocket endpoint.

#### Directory Structure

    This is the typical directory structure of the app.

The final app is available [here](). If you are stuck anywhere in the tutorial, you can always go to the final app to see the working code snippet to debug your code.
