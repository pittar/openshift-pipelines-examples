# Quarkus Native Basic Pipeline Example

## Create Namespace and Pipeline Resources

```
oc apply -k .
```

## Run the Pipeline

```
oc create -f basic-pipeline-run.yaml -n quarkus-native-basic-pipeline
```