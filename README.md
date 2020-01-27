## React Context

[Learning] - [React Context](https://reactjs.org/docs/context.html#reactcreatecontext)

- React.createContext

```sh
const MyContext = React.createContext(defaultValue);
```

- Context.Consumer

```sh
<MyContext.Consumer>
  {value => /* render something based on the context value */}
</MyContext.Consumer>
```

- Context.Provider 

```sh
<MyContext.Provider value={/* some value */}>
```

