# Actix(Rust) vs Fiber(Go) vs Express(Nodejs) 2023

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

![image](https://user-images.githubusercontent.com/71545960/215148138-c3193c67-bf1a-4769-a174-6a8945df3a60.png)

