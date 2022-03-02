# conditional rendering !
# use [] for dynamic property name of an object [computed property syntax]
# event.target is a dom obj
# onChange
# controlled elements !
# 
# for => html & htmlFor in JS 
# radio buttons can have the prop of only 1 being set at a time by giving them all the same name !
# A single source of truth ! so value prop should be set to the state of component 
- any buttton found inside a form is by default a type submit !
- if you want to change this , change the type of button to button
<!-- <input type="submit" value="Send it in"> -->
- it will trigger form's onSubmit handler !
- when dependancy array is an empty array it only runs once 
# why does useEffect run infiniitely if not given a dependancy array?
It only happens if the state is changing inside of useeffect , because when state changes component is re rendered & so useEffect is called again
