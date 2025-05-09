% ramalama-logout 1

## NAME
ramalama\-logout - logout from remote registry

## SYNOPSIS
**ramalama logout** [*options*] [*registry*]

## DESCRIPTION
Logout to remote model registry

## OPTIONS

Options are specific to registry types.

#### **--help**, **-h**
Print usage message

#### **--token**

Token to be passed to Model registry

## EXAMPLE

Logout to quay.io/username oci repository
```
$ ramalama logout quay.io/username
```

Logout from ollama repository
```
$ ramalama logout ollama
```

Logout from huggingface
```
$ ramalama logout huggingface
```
## SEE ALSO
**[ramalama(1)](ramalama.1.md)**

## HISTORY
Aug 2024, Originally compiled by Dan Walsh <dwalsh@redhat.com>
