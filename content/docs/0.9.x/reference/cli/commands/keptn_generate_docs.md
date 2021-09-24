---
date: "2021-06-16T14:50:20+02:00"
title: "keptn generate docs"
slug: keptn_generate_docs
---
## keptn generate docs

Generates the markdown documentation for the Keptn CLI

### Synopsis

Generates markdown documentation for the Keptn CLI.

This command can be used to create an up-to-date documentation of the Keptn CLI and as published on: https://keptn.sh/docs

It creates one markdown file per command, suitable for rendering in Hugo.


```
keptn generate docs [flags]
```

### Examples

```
keptn generate docs

keptn generate docs --dir=/some/directory
```

### Options

```
      --dir string   directory where the docs should be written to (default "./docs")
```

### Options inherited from parent commands

```
  -h, --help               help
      --mock               Disables communication to a Keptn endpoint
  -n, --namespace string   Specify the namespace where Keptn should be installed, used and uninstalled in (default "keptn")
  -q, --quiet              Suppresses debug and info messages
  -v, --verbose            Enables verbose logging to print debug messages
  -y, --yes                Assume yes for all user prompts
```

### SEE ALSO

* [keptn generate](../keptn_generate/)	 - Generates the markdown CLI documentation or a support archive

###### Auto generated by spf13/cobra on 16-Jun-2021