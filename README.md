# helm-charts

## Usage

```
helm repo add sdm4fzi https://sdm4fzi.github.io/helm-charts/
helm repo update sdm4fzi
helm install --create-namespace --namespace sdm4fzi hello-world sdm4fzi/hello-world
```

## Packaging & Indexing

```
helm package hello-world
helm repo index --url https://sdm4fzi.github.io/helm-charts .
```
