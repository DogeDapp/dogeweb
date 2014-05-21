## dogeweb

asyncio + [aiohttp](https://github.com/KeepSafe/aiohttp) + anonymous functions.

And [the best language ever](https://pyos.github.io/dg/).

### Usage

```dg
import '/dogeweb'
import '/dogeweb/r'


app = dogeweb.app $ r.file
  '/', ~> 'Hello, World!'
```

See [this example](https://github.com/pyos/dogeweb/blob/master/examples/simple.dg)
for something slightly more complex.
