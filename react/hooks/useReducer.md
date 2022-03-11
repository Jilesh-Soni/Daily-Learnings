# idea
concrete way to handle complex state
similar pattern to Redux
takes away lot of boilerplate associated with redux

# counter app
```js
// current state
function reducer(state,action){
  return {count:state.count+1}
}
// generally use obj instead of values
const [state,dispatch] = useReducer(reducer,{count:0})

```
- will complete later
