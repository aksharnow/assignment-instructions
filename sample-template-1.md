# NextTrip

### Implementation details: 

1. Used react-create-app to create the boilerplate code and I build on top of this boilerplate code
2. Since the focus of the assignment is not on the CSS, I used a lot of out of box Material UI components with few extra props to layout the components, I considered adding responsiveness to smaller screens as well by doing % values on CSS where ever needed.
3. Used React-Router for navigation flow, since the application does not have any navigation, I leveraged React-Router Hooks to respect the browser back and forth. 
4. Leveraged all the new features of React 16(especially hooks like useState,useEffect etc)
5. Used Prettier with standard rules for formatting the code
6. User latest react testing library to test the functionality
   1. Though I add only one test suite for Options.js because of limited time I have now, I added tests that focus on functionality than implementation details
   2. The test should still be intact if the implementation details change(The philosophy behind react testing library)
7. Created re usable tab panel with props documentation


Building the Application:

###  Install the dependencies 

> yarn install or npm install


### Running Test Cases: 

> npm run test



### Libraries:
```
 "@material-ui/core": "^4.9.7",
 "react": "^16.12.0",
 "react-router-dom": "^5.1.2",
 "@testing-library/react": "^9.3.2",
```

### Challenges 
1. I had challenges around the  `useRouteMatch()` hook which I have not used it before. 

