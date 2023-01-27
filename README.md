# Actix(Rust) vs Fiber(Go) 2023

## Actix API

-  Start server

```bash
cd actix-api
cargo run
```

-  Load test

```bash
wrk -c 10000 -d 60 -t 4 http://localhost:4000
```
- Result

![image](https://user-images.githubusercontent.com/71545960/215142198-072675a5-62dd-4ec2-a650-67fffb149f5d.png)

## Fiber API

-  Start server

```bash
cd fiber-api
go run main.go

```

-  Load test

```bash
wrk -c 10000 -d 60 -t 4 http://localhost:3000
```
- Result 

![image](https://user-images.githubusercontent.com/71545960/215142606-d3bfccaa-2b92-4f22-a4a4-b175cb802f2b.png)
