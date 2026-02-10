# JSON-server

## Build

```sh
docker build -t monogram/json-server .
```

---

## Futtatás Linuxon (VM/BASE)

```sh
docker run -d --rm -p 8888:3000 -v $(pwd):/app -v /app/node_modules monogram/json-server
```

## Futtatás Windowson (PowerShell / Docker Desktop-WSL)

```sh
docker run -d --rm -p 8888:3000 -v ${PWD}:/app -v /app/node_modules monogram/json-server
```

## Futtatás Windowson (Command Prompt - cmd.exe)

```sh
docker run -d --rm -p 8888:3000 -v %cd%:/app -v /app/node_modules monogram/json-server
```
