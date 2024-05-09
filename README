# Running otel locally

The purpose of this repository is to make it possible to run simulate sending event to otel collector then viewing it on jaeger UI locally

The reason for doing this is to make it easier to test out the otel config.yaml and also make this as a base for potential future workshop

__note__: this is work in progress and I am aware that we can have lots of improvement though i rather record current progress first.

# Prereq
You need docker installed

# Installation
Run `./go` to 
- install otel-cli
- create a docker network called `otel` so that containers within the same network can talk to each other
- run jaeger container
- run otel-collector container

# Sample cli command

```
otel span -a "my.foo=bar" -a "my.bar=baz" -a "card=select * where password=abc123" "span name"
```
