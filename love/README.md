# Love

Draw a heart using a name.

![heart](./heart.png)

## How to build

When build, set main.love or "Love" will be used as default.

`go build -ldflags="-X main.love=<name>" love.go`

## How to run

**go version**

`go run -ldflags="-X main.love=<name>" love.go`

**python version**

`python love.py`
