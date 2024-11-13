# `api-cli`

**Usage**:

```console
$ api-cli [OPTIONS] COMMAND [ARGS]...
```

**Options**:

* `--install-completion`: Install completion for the current shell.
* `--show-completion`: Show completion for the current shell, to copy it or customize the installation.
* `--help`: Show this message and exit.

**Commands**:

* `api`
* `type`: Gen api type file

## `api-cli api`

**Usage**:

```console
$ api-cli api [OPTIONS]
```

**Options**:

* `--host TEXT`: [default: 127.0.0.1]
* `--port TEXT`: [default: 8000]
* `--path TEXT`: [default: /api/openapi.json]
* `--url TEXT`
* `--output TEXT`: [default: ./dist]
* `--name TEXT`: [default: dbApi.ts]
* `--help`: Show this message and exit.

## `api-cli type`

Gen api type file

Args:
    host (str, optional): api server ip. Defaults to "127.0.0.1".
    port (str, optional): api server port. Defaults to "8000".
    path (str, optional): api server openapi.json path. Defaults to "/api/openapi.json".
    url (_type_, optional): api server ip:port. Defaults to None.
    output (str, optional): gen file out path. Defaults to "./dist".
    name (str, optional): _description_. Defaults to "api.types.d.ts".

**Usage**:

```console
$ api-cli type [OPTIONS]
```

**Options**:

* `--host TEXT`: [default: 127.0.0.1]
* `--port TEXT`: [default: 8000]
* `--path TEXT`: [default: /api/openapi.json]
* `--url TEXT`
* `--output TEXT`: [default: ./dist]
* `--name TEXT`: [default: api.types.d.ts]
* `--help`: Show this message and exit.
