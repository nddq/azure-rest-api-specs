## Python

These settings apply only when `--python` is specified on the command line.
Please also specify `--python-sdks-folder=<path to the root directory of your azure-sdk-for-python clone>`.
Use `--python-mode=update` if you already have a setup.py and just want to update the code itself.

``` yaml $(python)
azure-arm: true
title: QuotaMgmtClient
license-header: MICROSOFT_MIT_NO_VERSION
namespace: azure.mgmt.quota
package-name: azure-mgmt-quota
package-version: 1.0.0b4
clear-output-folder: true
```

``` yaml $(python)
no-namespace-folders: true
output-folder: $(python-sdks-folder)/quota/azure-mgmt-quota/azure/mgmt/quota
```
