## ctlptl apply

Apply a cluster config to the currently running clusters

```
ctlptl apply -f FILENAME [flags]
```

### Examples

```
  ctlptl apply -f cluster.yaml
  cat cluster.yaml | ctlptl apply -f -
```

### Options

```
  -f, --filename strings   
  -h, --help               help for apply
```

### SEE ALSO

* [ctlptl](ctlptl.md)	 - Mess around with local Kubernetes clusters without consequences

###### Auto generated by spf13/cobra on 16-Nov-2020