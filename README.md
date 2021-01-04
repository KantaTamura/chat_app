## build setup

### server
```bash
> cd chat-server && cargo run

# if client run
Client 127.0.0.1:49274 connected
```

### client
```bash
> cd chat-client && cargo run

Write a Message:
```

## example

```bash
#client
> test
message sent "test"
message recv [116, 101, 115, 116]

#server
127.0.0.1:49533: "test"
```
