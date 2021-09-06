
# React
- Dclarative 声明式 || Imperative 命令式   
- Component-Based  
- Learn Once, Write Anywhere  
- state driven



JSX = JavaScript XML
props   
state

class & function 

### Thinking in React
1. Break The UI into a Component Hierarchy 
2. Buil A Static Version in React 
3. Identify The Minimal (but complete) Representation of UI State
4. Identify Where Your State Should Live 
5. Add Inverse Data Flow  

The Job of  A React Developer  
1. Decide on Components  
2. Decide the State and where it lives   
3. What changes when state changes   

### Class component vs Functional component
Functional component (stateless)  
Class component(stateful)  
Pure components

### DOM VS Virtual DOM
<a>https://reactkungfu.com/2015/10/the-difference-between-virtual-dom-and-dom/</a>


### Lifecycle
Mounting - When an instance of a component is being created and inserted into the DOM: 
> **constructor()**  
> static getDerivedStateFromProps()  
> **render()**  
> **componentDidMount()**   
 
Updating - An update can be caused by changes to props or state.    
> static getDerivedStateFromProps()  
> shouldComponentUpdate()  
> **render()**  
> getSnapshotBeforeUpdate()
> **componentDidMount()**   

Unmounting - This method is called when a component is being removed from the DOM
> **componentWillUnmount()**

Error Handling - 
> static getDerivedStateFromError()  
> componentDidCatch()

componentDidMount()  
> is invoked immiediately after a component is mounted(inserted into the tree).
 
render()
> is the only required method in a class component  
> should be pure
 
constructor()


componentDidUpdate()



### route  
<https://reactrouter.com/web/guides/quick-start>

svg file in react  
<https://create-react-app.dev/docs/adding-images-fonts-and-files/>

firebase  
<https://firebase.google.com/docs>

###Redux
Redux allows React state to be more scalable 
good for managing large state  
useful for sharing data between components
principle:  
1. single source of truth  
2. state is read only  
3. changes use pure functions 
 
flux pattern 
 



