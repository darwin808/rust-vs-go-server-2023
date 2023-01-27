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
