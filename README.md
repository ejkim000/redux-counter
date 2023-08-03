# Redux Counter
## install react-redux
npm install @reduxjs/toolkit react-redux

## Summary
Create a Redux store with configureStore

configureStoreaccepts a reducerfunction as a named argument
configureStoreautomatically sets up the store with good default settings
Provide the Redux store to the React application components

Put a React Redux <Provider>component around your <App />
Pass the Redux store as <Provider store={store}>
Create a Redux "slice" reducer with createSlice

Call createSlicewith a string name, an initial state, and named reducer functions
Reducer functions may "mutate" the state using Immer
Export the generated slice reducer and action creators
Use the React Redux useSelector/useDispatchhooks in React components

Read data from the store with the useSelectorhook
Get the dispatchfunction with the useDispatchhook, and dispatch actions as needed