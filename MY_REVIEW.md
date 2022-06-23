This operator is started by this script (found in docker file)

```shell
cmd/operator/main.go
```

which kicks off operators like this.

```go
po, err := prometheuscontroller.New(ctx, cfg, log.With(logger, "component", "prometheusoperator"), r)
```

and  start an controller like this maybe?
pkg/prometheus/operator.go





pkg/prometheus/operator.go