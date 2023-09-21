# FoodieDestination
# FoodieDestination Web Application

FoodieDestination is a web application designed to cater to all your foodie needs. Whether you're looking for the hottest restaurants in town, craving a particular cuisine, or want to order food for delivery, FoodieDestination has you covered.

# Live Demo 
Live Demo: https://foodiedestination.netlify.app/
## Features

FoodieDestination offers a wide range of features to enhance your food discovery and ordering experience:

1. **Parcel**: The application is bundled and served using Parcel, a fast and efficient web application bundler.

2. **Dev Build**: The development build of the application is optimized for ease of development and debugging.

3. **Local Server**: FoodieDestination utilizes a local server to provide a seamless user experience during development.

4. **HMR (Hot Module Replacement)**: Hot Module Replacement ensures that changes made to the code are reflected instantly in the application, eliminating the need for manual refreshing.

5. **File Watching Algorithm (C++)**: A custom file-watching algorithm, written in C++, ensures efficient monitoring of files for changes, improving development speed.

6. **Caching**: Caching is implemented to speed up builds and reduce redundant operations.

7. **Image Optimization**: Images used in the application are optimized for fast loading.

8. **Minification**: Code is minified to reduce file sizes and improve application performance.

9. **Bundling**: Code is bundled for efficient delivery to the client-side.

10. **Compression**: Resources are compressed to reduce network latency and improve loading times.

11. **Consistent Hashing**: Consistent hashing is used for load balancing and distribution.

12. **Code Splitting**: Code splitting is employed to optimize the loading of different parts of the application.

13. **Differential Bundling**: Support for older browsers is provided through differential bundling.

14. **Diagnostic Error Handling**: Comprehensive error handling and diagnostics are implemented to facilitate debugging.

15. **HTTPs**: The application is served over HTTPS for enhanced security.

16. **Tree Shaking**: Unused code is automatically removed from the application to reduce its size.

17. **Different Dev and Prod Bundles**: Separate development and production bundles are generated for optimal performance.

18. **Namaste Food**: A user-friendly and visually appealing UI with a header, logo, navigation items, search functionality, restaurant listings, and a footer with copyright, links, address, and contact information.

## Export/Import

The application supports both default and named exports/imports:

**Default Export/Import:**
```javascript
export default Component;
import Component from "path";
```

**Named Export/Import:**
```javascript
export const Component;
import { Component } from "path";
```

## React Hooks

FoodieDestination utilizes React hooks for managing state and side effects:

1. `useState()`: Provides powerful state variable management in React.

2. `useEffect()`: Enables handling side effects in functional components.

## Routing

The application supports two types of routing:

1. **Client-Side Routing**: Allows for dynamic navigation within the application without a full page reload.

2. **Server-Side Routing**: Facilitates navigation by requesting new pages from the server.

## Redux Toolkit

To manage application state, FoodieDestination uses Redux Toolkit. The following steps outline its integration:

1. Install `@reduxjs/toolkit` and `react-redux`.

2. Build the Redux store.

3. Connect the store to the application.

4. Define slices (e.g., `cartSlice`) to manage specific parts of the state.

5. Dispatch actions to update the state.

6. Use selectors to access and retrieve data from the state.

## Testing

Developers can perform various types of testing in FoodieDestination:

1. **Unit Testing**: Isolates and tests individual units of code.

2. **Integration Testing**: Ensures that different parts of the application work together seamlessly.

3. **End-to-End Testing (E2E)**: Tests the application's functionality as a whole.

To set up testing in the application:

1. Install `React Testing Library`.

2. Install `jest`.

3. Install Babel dependencies and configure Babel.

4. Configure the Parcel config file to disable default Babel transpilation.

5. Set up Jest by running `npx jest --init`.

6. Install `jsdom` library for browser-like testing.

7. Include `@babel/preset-react` inside the Babel configuration for JSX support.

8. Install `@testing-library/jest-dom` for additional testing utilities.

## Tech Stack

FoodieDestination is built using the following technology stack:

- **React**: A popular JavaScript library for building user interfaces.

- **Parcel**: A fast and efficient web application bundler.

- **Tailwind CSS**: A utility-first CSS framework for building responsive web designs.

- **Jest (Testing)**: A JavaScript testing framework.

- **Redux Toolkit**: A Redux library that simplifies state management.

## Additional Features

In addition to the mentioned features, FoodieDestination offers the following functionalities:

- **Search**: Allows users to search for restaurants and cuisines.

- **Sort**: Enables sorting of restaurant listings.

- **Filter**: Provides filtering options for refining search results.

- **Shimmer UI**: A loading UI for a better user experience.

- **Lazy Loading**: Efficiently loads resources as needed for improved performance.

---

Thank you for using FoodieDestination!. If you have any questions or need further assistance, please feel free to reach out. Happy coding and happy eating! 🍔🍕🍰


