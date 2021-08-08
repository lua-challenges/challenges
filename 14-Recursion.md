# Challenge 14 (Easy)

### Goal
Print "Hello, world!" 

### Rules
- You cannot call print nor can you use anything else to print.
- You cannot use the `table` library, `rawset` or table contructor expressions. (`{}`)
- You cannot change or set `nil`'s metatable. 
- You cannot use `=` in your code code.
- Your solution must be **after** the code.

### Code
```lua
debug, os, io, _G = nil;
pcall(function()
    print(hello.world);
end);
```
