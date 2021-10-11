# Advanced-Redux

## Steps to start a new redux project.


 Installing React toolkit and react redux 

              npm i @reduxjs/toolkit
              npm i react-redux
            
 Providing redux store to entire application
 
              import { Provider } from "react-redux";
              import store from "./store/index";
              
              ReactDOM.render(
              <Provider store={store}>
                   <App />
              </Provider>,
              document.getElementById("root")
              );

## What is createSlice & configureStore in redux-toolkit

              CreateSlice : Used to store separate reducers for various different functinalities.
              configureStore : Used to combine various slices together.
              
## useDispatch Hook in react-redux

              const dispatch = useDispatch();
              dispatch(uiActions.toggle());
              
              
              This method dispatches action with returning object with type property as a unique identification 
              code which helps in which action is dispatched from the component. 
