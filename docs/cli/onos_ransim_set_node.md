## onos ransim set node

Update an E2 node

```
onos ransim set node <enbid> [field options] [flags]
```

### Options

```
      --cells uints              cell NCGIs (default [])
      --controllers strings      E2T controller
  -h, --help                     help for node
      --service-models strings   supported service models
```

### Options inherited from parent commands

```
      --auth-header string       Auth header in the form 'Bearer <base64>'
      --no-tls                   if present, do not use TLS
      --service-address string   the gRPC endpoint (default "ran-simulator:5150")
      --tls-cert-path string     the path to the TLS certificate
      --tls-key-path string      the path to the TLS key
```

### SEE ALSO

* [onos ransim set](onos_ransim_set.md)	 - Commands for setting RAN simulator model metrics and other information

###### Auto generated by spf13/cobra on 25-Oct-2021
