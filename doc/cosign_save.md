## cosign save

Save the container image and associated signatures to disk at the specified directory.

### Synopsis

Save the container image and associated signatures to disk at the specified directory.

```
cosign save [flags]
```

### Examples

```
  cosign save --dir <path to directory> <IMAGE>
```

### Options

```
  -c, --cache-path string   path to cache image layers
      --dir string          path to dir where the signed image should be stored on disk
  -h, --help                help for save
      --platform string     only save container image and its signatures for a specific platform image
```

### Options inherited from parent commands

```
      --output-file string   log output to a file
  -t, --timeout duration     timeout for commands (default 3m0s)
  -d, --verbose              log debug output
```

### SEE ALSO

* [cosign](cosign.md)	 - A tool for Container Signing, Verification and Storage in an OCI registry.

