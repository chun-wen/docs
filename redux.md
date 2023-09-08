## Actions
1. 通常在大型專案下會統一放在一個資料夾底下管理。這有助於命名的統一


## Action Creators
def: a function creates and returns an action object
```jsx
const todoAdded = (text) => {
  return {
    type: 'todos/todoAdded',
    payload: text
  }
}
```
Two main purpose:
1. prepare and format the contents of action objects
2. encapsulate any additional work needed



## Reducers
Reducers is a pure function therefore we should not use 

