Drone plugin to build Docker images via buildx. You are able to build
multi-architecture images within a single pipeline on a plain amd64
architecture.

## Examples

```yaml
kind: pipeline
name: default

steps:
- name: step name
  image: dronehippie/buildx:1
  settings: []
```

## Parameters

dummy
: dummy
