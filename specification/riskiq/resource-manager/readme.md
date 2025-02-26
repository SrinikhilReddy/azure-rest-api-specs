# easm

> see https://aka.ms/autorest
This is the AutoRest configuration file for easm.

## Getting Started

To build the SDKs for My API, simply install AutoRest via `npm` (`npm install -g autorest`) and then run:

> `autorest readme.md`
To see additional help and options, run:

> `autorest --help`
For other options on installation see [Installing AutoRest](https://aka.ms/autorest/install) on the AutoRest github page.

---

## Configuration

### Basic Information

These are the global settings for the easm.

``` yaml
openapi-type: arm
openapi-subtype: rpaas
tag: package-preview-2022-04-01
```

### Tag: package-preview-2022-04-01

These settings apply only when `--tag=package-preview-2022-04-01` is specified on the command line.

```yaml $(tag) == 'package-preview-2022-04-01'
input-file:
  - Microsoft.Easm/preview/2022-04-01-preview/easm.json
```

---

# Code Generation

## Swagger to SDK

This section describes what SDK should be generated by the automatic system.
This is not used by Autorest itself.

``` yaml $(swagger-to-sdk)
swagger-to-sdk:
  - repo: azure-sdk-for-python-track2
  - repo: azure-sdk-for-java
```
## Python

See configuration in [readme.python.md](./readme.python.md)
