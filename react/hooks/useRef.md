# thoughts
- there are so many ways of doing the same thing !
and everything we feel happens like when we interact with a website  looks so simple 
the intuitive way how things must have happened is not actually how things happen !
u might think you pressed edit , an edit dialog box opened , u edited it , & saved
all of this actually required a get call , a put call , a get call again just to do a simple edit
not to mention the numerous no. of rendering that happened !

# useRef
- doesn't cause component re render
# a simple usecase
## count no. of times component has re rendered !

```js
//{current : 0}
const renderCount = useRef(0)
useEffect(()=>{renderCount.current=renderCount.current + 1})
```
## UseCases
refer an html element
so popular that each element has a ref attrib
it acts like a doc query selector !!?

### want prevState
```js
const prevName = useRef('')

useEffect(()=>{prevName.current = name},[name])
```
an additional re render is saved !



# How to use ? 
```js
function focus(){
  inputRef.current.focus()
  inputRef.current.value = "hey" // should be avoided
}
```
```html
<!-- <input ref={inputRef}/> -->
```
# important
- handle all state in jsx only ! like appendchild or changing state should not be done using useref

# doubts
- 2 state changes in 1 click
- (1 function is called)
- 1 render will happen or 2 ?


# ad
https://youtu.be/lILfD-fYO-k
https://youtu.be/1pgIjKDYxc4
