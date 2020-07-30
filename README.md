# notes-careertrack-34.md
## Context 
* helps with the global state and this would be very helpful so you don't have to prop-drill. 
* use 'createContext' to apply it all the components. ```ex const MyContext = React.createContext(defaultValue);```
* use .Provider to pass. ex ``` <MyContext.Provider value={/* some value */}> ```
* can be in a class component``` MyClass.contextType = MyContext```
* The context object and the Provider allow for the component to have this context change everywhere the component is called. 


