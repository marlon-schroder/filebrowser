# FileBrowser Helm Chart

This repository provides a Helm chart to easily install FileBrowser on Kubernetes. The included values.yaml file contains example settings that can be customized for your environment. To get started, clone this repository and run the following commands:

```bash
git clone https://github.com/marlon-schroder/filebrowser.git
cd filebrowser
helm install filebrowser ./ -n example --create-namespace -f values.yaml
```

After changing values.yaml, you can update your deployment using:

```bash
helm upgrade filebrowser ./ -n example -f values.yaml
```

This chart makes it simple to deploy FileBrowser with flexible and configurable options, even if you are new to Kubernetes or Helm.

## Pre-requisites

- Kubernetes 1.20+
- Helm 3.x
