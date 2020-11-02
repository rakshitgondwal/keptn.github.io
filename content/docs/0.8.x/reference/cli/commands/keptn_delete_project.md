---
date: "2020-09-02T17:04:24+02:00"
title: "keptn delete project"
slug: keptn_delete_project
---
## keptn delete project

Deletes a project identified by project name

### Synopsis

Deletes a project identified by project name. 

**Notes:**
* If a Git upstream is configured for this project, the referenced upstream repository (e.g., on GitHub) will not be deleted. 
* Services that have been deployed to the Kubernetes cluster are not deleted.
* Namespaces that have been created on the Kubernetes cluster are not deleted.
* Helm-releases created for deployments are not deleted. To clean-up deployed Helm releases, pelease see [Clean-up after deleting a project](https://keptn.sh/docs/0.7.x/continuous_delivery/deployment_helm/#clean-up-after-deleting-a-project)


```
keptn delete project PROJECTNAME [flags]
```

### Examples

```
keptn delete project sockshop
```

### Options

```
  -h, --help            help for project
      --keep-services   Indicate whether the helm releases that are part of the project should be deleted as well, or not
```

### Options inherited from parent commands

```
      --mock                 Disables communication to a Keptn endpoint
  -q, --quiet                Suppresses debug and info messages
      --suppress-websocket   Disables WebSocket communication to suppress info messages from services running inside Keptn
  -v, --verbose              Enables verbose logging to print debug messages
```

### SEE ALSO

* [keptn delete](../keptn_delete/)	 - Deletes a project

###### Auto generated by spf13/cobra on 2-Sep-2020