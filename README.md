# Ketikode Executor

## Time limit

Implemented using `timeout`

```
timeout 3s ./exec
```

## Sandboxing running time

The program execution was sandboxed using `firejail`

```
firejail --whitelist=$(pwd) --private bash
```