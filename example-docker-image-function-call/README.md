This example uses a dockerimage to add a annotation to a configmap.

To run within this directory:
```bash
docker build . -t demo.goharbor.io/jake/annotator:1.0.0

kustomize build --enable-alpha-plugins --enable-exec .
```
