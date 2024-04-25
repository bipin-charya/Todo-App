# Use of useContext
- first we create Context and then we use "useContext" to declare variable globally so that components can access it directly without making any unnecessary data passing/handling by outer components  

- First, we create a Context using React.createContext(). Then, we provide it to the component tree using <Context.Provider>. Components within this provider can use the useContext hook to access the Context value. This setup allows components to access shared data directly without needing to pass data through props at every level of the component hierarchy, thereby avoiding unnecessary prop drilling.

# Use of LocalStorage
- As items store in localstorage are in strings : JSON.parse(localStorage.getItem("keys"))
- And we need to convert any value to string before storing it in Localstorage
- set Items to store in localstorage: localStorage.setItem("keys", JSON.stringigy(value))




# React + Vite

This template provides a minimal setup to get React working in Vite with HMR and some ESLint rules.

Currently, two official plugins are available:

- [@vitejs/plugin-react](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react/README.md) uses [Babel](https://babeljs.io/) for Fast Refresh
- [@vitejs/plugin-react-swc](https://github.com/vitejs/vite-plugin-react-swc) uses [SWC](https://swc.rs/) for Fast Refresh
