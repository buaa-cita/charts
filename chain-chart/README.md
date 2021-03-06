# chain-chart

![Version: 0.1.0](https://img.shields.io/badge/Version-0.1.0-informational?style=flat-square) ![Type: application](https://img.shields.io/badge/Type-application-informational?style=flat-square) ![AppVersion: 6.0.0](https://img.shields.io/badge/AppVersion-6.0.0-informational?style=flat-square)

Used to initialize the chain and its attribute configuration

## Maintainers

| Name | Email | Url |
| ---- | ------ | --- |
| Rivtower Technologies | contact@rivtower.com |  |
| BUAA | contact@buaa.edu.cn |  |

## Values

| Key | Type | Default | Description |
|-----|------|---------|-------------|
| chain_name | string | `"chainconfig-sample"` | Name of chain |
| authorities | string | "" | Addresses of all consensus nodes |
| super_admin | string | `""` | Address of all SuperAdmin |
| timestamp | string | `""` | Time of chain starting |
| network_image | string | `"citacloud/network_direct:v6.0.0"` | Image of network container and version |
| consensus_image | string | `"citacloud/consensus_bft:v6.0.0"` | Image of consensus container and version |
| executor_image | string | `"citacloud/executor_evm:v6.1.0"` | Image of executor container and version |
| storage_image | string | `"citacloud/storage_rocksdb:v6.1.0"` | Image of storage container and version |
| controller_image | string | `"citacloud/controller:v6.2.0"` | Image of controller container and version |
| kms_image | string | `"citacloud/kms_sm:v6.0.0"` | Image of kms container |
| pvc_path | string | `"/root/cita-cloud-datadir"` | Path of PVC |
| hostname | string | `""` | - |

#### nodes

| Key | Type | Default | Description |
|-----|------|---------|-------------|
| hosts | string | `""` | Used to locate the host in the case of multiple clusters |
| port | string | `""` | Used to locate the port of host in the case of multiple clusters |



----------------------------------------------
Autogenerated from chart metadata using [helm-docs v1.4.0](https://github.com/norwoodj/helm-docs/releases/v1.4.0)
