### What Does .filter() Do?
.filter() creates a new array by keeping only the items that pass the condition.
It does not modify the original array but instead returns a new filtered version.

todo.id !== id

- useeffect:
    If the todo.id is not equal to the id we want to delete → keep it. ✅
    If the todo.id matches the id we want to delete → remove it. ❌

    The empty array [] means it runs once when the component mounts.
    If we didn’t pass [], the effect would run after every re-render (which we don’t want).


