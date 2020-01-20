# helmfile-diff-repro

```bash
$ helmfile apply

Building dependency release=knative, chart=knative
Comparing release=knative, chart=knative
in ./helmfile.yaml: failed processing release knative: helm exited with status 1:
  Error: Failed to render chart: exit status 1: Error: template: knative/templates/serving.yaml:1614:43: executing "knative/templates/serving.yaml" at <index .Annotations "sub">: error calling index: index of untyped nil
  
  Error: plugin "diff" exited with error
```

