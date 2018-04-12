Learn+Try Rust in the Browser via WebAssembly
=============================================

[April 12, 2018 talk at Rust DC meetup](https://www.meetup.com/RustDC/events/248552247/)

Should _mostly_ function if you cd into the directory and run

```
ruby -run -e httpd . --port 8080
```

and navigate to localhost:8080 in a recent web browser.

One particular piece, the wasm-bindgen demo, requires that you are serving the
example at the head of the `wasm-bindgen` branch of
https://github.com/scooter-dangle/rust-wasm
