# Actix(Rust) vs Fiber(Go) 2023

## Actix(Rust) API 🦀

-  Start server

```bash
cd actix-api
cargo run
```

-  Load test

```bash
wrk -c 10000 -d 60 -t 4 http://localhost:4000
```

-  Result

![image](https://user-images.githubusercontent.com/71545960/215142198-072675a5-62dd-4ec2-a650-67fffb149f5d.png)

## Fiber(Go) API

-  Start server

```bash
cd fiber-api
go run main.go

```

-  Load test

```bash
wrk -c 10000 -d 60 -t 4 http://localhost:3000
```

-  Result

![image](https://user-images.githubusercontent.com/71545960/215142606-d3bfccaa-2b92-4f22-a4a4-b175cb802f2b.png)

## Express(NodeJs) API

-  Start server

```bash
cd node-api
node src/index.js

```

-  Load test

```bash
wrk -c 10000 -d 60 -t 4 http://localhost:2000
```

-Result

![image](https://user-images.githubusercontent.com/71545960/215147391-30225d36-c05c-424f-a81c-40af9796518e.png)
