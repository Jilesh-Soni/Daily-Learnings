# useMemo
- any of the state changes - causes component to re render
- re render means calling of all functions called in comp

## used when ? (benefit)
- slow function => faster by storing the results in hashmap
- for refernetial equality 
  - value vs reference in js
  - comparing 2 variables in js it compares their reference in the case of obj & arrays
  - 2 obj with same values are still not equal ???
  - so we can usememo here too somehow they refer the exact same object after using it
  - idk how
## how 1st one works ?        
- memoization
  - caching the value
  - no recomputation
  - input => output
  - key => value
- it accepts a function which needs to be memoized ()=>slowFun()
- & takes a dependancy array
## cons
- performance & memory overheads
- useMemo is called every single render
- + caching
