# go-htmx (WIP)
golang htmx with tailwindcss template

# Getting started 
## Development
Note: You need to run in a separate terminal
```bash
$ air # to watch the go files
$ templ generate --watch # to generate view files
```

## Production
```bash
$ go build -ldflags="-s -w" -o ./bin/main ./cmd/
$ # run the application
$ # ./bin/main 
```

