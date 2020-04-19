# reactive-programming
**Reactive programming** is a programming paradigm oriented around data flows and the propagation of change. This means that it should be possible to express static or dynamic data flows with ease in the programming languages used, and that the underlying execution model will automatically propagate changes through the data flow.

## Conceptual meanings

**Fluent API**: refers to a pattern of programming where method calls are chained together with the end result being certainly      less   verbose and arguably more readable than a series of statements. Example below:

```
Flowable<Integer> flow = Flowable
.range(1,5)
.map(v -> v * v)
.filter(v -> v % 3 == 0)
;
```


## Links

https://github.com/ReactiveX/RxJava

What is reactive programming: 
https://medium.com/@kevalpatel2106/what-is-reactive-programming-da37c1611382
