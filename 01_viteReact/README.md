# Install React Application in vite

1. Visit website - https://vitejs.dev/
2. Create Project - npm create vite@latest

# File Structure in React(Vite) Application
/src
  /assets
    /images
    /styles

  /components
    /Button
      Button.js
      Button.css
      Button.test.js
    /Header
      Header.js
      Header.css
      Header.test.js
    ...

  /containers
    /HomePage
      HomePage.js
      HomePage.css
      HomePage.test.js
    /UserPage
      UserPage.js
      UserPage.css
      UserPage.test.js
    ...

  /contexts
    AuthContext.js
    ThemeContext.js
    
  /hooks
    useFetch.js
    useForm.js
    ...

  /utils
    api.js
    helpers.js
    ...

  /services
    authService.js
    userService.js
    ...

  /redux
    /actions
      userActions.js
      authActions.js
      ...
    /reducers
      userReducer.js
      authReducer.js
      ...
    /selectors
      userSelectors.js
      authSelectors.js
      ...
    /store
      configureStore.js

  /routes
    AppRouter.js
    PrivateRoute.js
    PublicRoute.js

  /tests
    /unit
      Button.test.js
      Header.test.js
      ...
    /integration
      authIntegration.test.js
      userIntegration.test.js
      ...

  index.js
  App.js
  config.js
  setupTests.js
                               