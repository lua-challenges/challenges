# Challenge #17 (Hard)

### Goal
Make the equality check evaluate to true. 

### Rules
- The function call `not_two()` cannot return `2`.
- You cannot change or set any metatables.
- You cannot use load, loadstring, loadfile, etc.
- You cannot edit bytecode or use debug hooks.
- Your solution must be **before** the code.

### Code
```lua
assert(2 == not_two())
```