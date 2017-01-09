# what-on-earth-is-a-callback

If you've ever used Javascript array methods such as .filter .reduce .map etc, then you've already used callbacks.

A callback is a function, which we pass as an argument to another function where it will be called.

```
var callback = function () {
  return 'Hello'
}

var caller = function (cb) {
  cb()
}

caller(callback); // 'Hello'
```

In this contrived example our callback function is passed to our caller function. 

This can be very useful in other situations. We can set up simple functions, and use them for wildy different things depending on which callback we pass.
