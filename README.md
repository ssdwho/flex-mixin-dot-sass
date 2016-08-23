## Kullanım

``` sass
+display-flex         // display: flex;
+display-inline-flex  // display: inline-flex;

+flex-direction()     // flex-direction: row;
+flex-direction(row-reverse|column|column-reverse|inherit)

+flex-wrap()          // flex-wrap: nowrap;
+flex-wrap(wrap|wrap-reverse|inherit)

+flex-flow(flex-direction, flex-wrap)     // ↑↑↑

+order(number)

+flex-grow(number|initial|inherit)

+flex-shrink(number|initial|inherit)

+flex-basis(number|auto|initial|inherit)

+flex(flex-grow, flex-shrink, flex-basis) // ↑↑↑

+justify-content()    // justify-content: flex-start;
+justify-content(flex-end|center|space-between|space-around|inherit)

+align-items()        // align-items: stretch;
+align-items(flex-start|flex-end|center|baseline|inherit)

+align-content()      // align-content: stretch;
+align-content(flex-start|flex-end|center|space-between|space-around|inherit)

+align-self()         // align-self: auto;
+align-self(flex-start|flex-end|center|baseline|stretch|inherit)
```
