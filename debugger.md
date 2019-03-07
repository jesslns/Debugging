## Debugger

#### Introducction
JavaScript can be powerful due to its ability to work asynchronously via callback functions. Async callbacks allow one to write event-driven code but it makes tracking down bugs very hair-pulling due to its non-linear execution.

Luckily, you can use the `debugger` statement to sets a breakpoint int he code, and with the help of Chrome DevTools, you can drill into the state of your web app at various points in time!

### How to use

The google dev tool allows async stack traces by default (since 2017). So you can just go to the `Sources` panel of Chrome DevTools and walk the full stack trace. the `debugger` statement works similarly with `binding.pry`.
