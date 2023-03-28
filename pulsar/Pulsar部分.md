# pulsar部分

要与 Pulsar 交互，您首先需要一个 `Client` 对象。您可以使用 `NewClient` 函数创建一个客户端对象，传入一个 `ClientOptions` 对象。





创建成功一个 `Client` 对象之后，再去基于这个Client对象创建Producers或者是Consumers来进行生产消费。





```go
Q：在想为什么要创建了客户端对象之后才创建server或者client？为什么不去直接创建一个server或者client?
```



