```lua
self.imgw, self.imgh = tex:getWidth(), tex:getHeight()

self.imgw, self.imgw = tex:getWidth(), tex:getHeight()
-- какой-то способ различисть двойное использование imgw ?
```

```lua
local abs, ceil, resume, yield = math.abs, math.ceil, coroutine.resume, coroutine.yield
-- oops!
local abs, ceil, resume, yield = math.ceil, coroutine.resume, coroutine.yield
```
