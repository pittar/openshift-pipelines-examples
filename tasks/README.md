# Custom Tasks

OpenShift Pipelines is infinitely extensible, since you can create your own tasks to handle any task specific to your own environment or process. You can find a handy [list of recommendations for creating your own tasks](https://github.com/tektoncd/catalog/blob/main/recommendations.md) here.

Rather than copy/paste Task YAML (nobody wants that), some of the Tasks used in these examples are sourced from the [Red Hat Canada GitOps Catalog](https://github.com/redhat-canada-gitops/catalog) - an *unofficial* catalog of reusable GitOps resources... including Pipelines Tasks!  These include:
* [Maven 3.6 / OpenJDK 11](https://github.com/redhat-canada-gitops/catalog/tree/master/openshift-pipelines-tasks/maven/base)
* [.Net Core](https://github.com/redhat-canada-gitops/catalog/tree/master/openshift-pipelines-tasks/dotnet)
* [Rollout and Restart Deployment](https://github.com/redhat-canada-gitops/catalog/tree/master/openshift-pipelines-tasks/rollout-restart/base)