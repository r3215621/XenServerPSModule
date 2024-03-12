# XenServerPSModule
## Add-XenBond

### Synopsis
None

### Description
None

### Syntax
```
Add-XenBond [-Bond] <Bond> [[-PassThru]] [[-OtherConfig] <KeyValuePair[string,string]>] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]] [-Ref] <XenRef[Bond]> [[-PassThru]] [[-OtherConfig] <KeyValuePair[string,string]>] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]] [-Uuid] <guid> [[-PassThru]] [[-OtherConfig] <KeyValuePair[string,string]>] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]]
```
### Parameters
| Name | Type | Required | Default Value | Description |
| :--- | :--- | :------- | :------------ | :---------- |
| BestEffort | switch | False |  |  |
| Bond | Bond | True |  |  |
| Confirm | switch | False |  |  |
| OtherConfig | KeyValuePair[string,string] | False |  |  |
| PassThru | switch | False |  |  |
| Ref | XenRef[Bond] | True |  |  |
| SessionOpaqueRef | string | False |  |  |
| Uuid | guid | True |  |  |
| WhatIf | switch | False |  |  |
### Procedure
None

### Inputs
```
XenAPI.Bond
XenAPI.XenRef`1[[XenAPI.Bond, XenServer, Version=8.2.3.0, Culture=neutral, PublicKeyToken=d247b8b0ac7959e9]]
System.Guid

```
### Outputs
```
XenAPI.Bond
System.Void

```
### Links
None

### Examples

Add-XenBond [-Bond] <Bond> [-PassThru] [-OtherConfig <KeyValuePair[string,string]>] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [<CommonParameters>]

Add-XenBond [-Ref] <XenRef[Bond]> [-PassThru] [-OtherConfig <KeyValuePair[string,string]>] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [<CommonParameters>]

Add-XenBond [-Uuid] <guid> [-PassThru] [-OtherConfig <KeyValuePair[string,string]>] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [<CommonParameters>]


## Add-XenCluster

### Synopsis
None

### Description
None

### Syntax
```
Add-XenCluster [-Cluster] <Cluster> [[-PassThru]] [[-OtherConfig] <KeyValuePair[string,string]>] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]] [-Ref] <XenRef[Cluster]> [[-PassThru]] [[-OtherConfig] <KeyValuePair[string,string]>] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]] [-Uuid] <guid> [[-PassThru]] [[-OtherConfig] <KeyValuePair[string,string]>] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]]
```
### Parameters
| Name | Type | Required | Default Value | Description |
| :--- | :--- | :------- | :------------ | :---------- |
| BestEffort | switch | False |  |  |
| Cluster | Cluster | True |  |  |
| Confirm | switch | False |  |  |
| OtherConfig | KeyValuePair[string,string] | False |  |  |
| PassThru | switch | False |  |  |
| Ref | XenRef[Cluster] | True |  |  |
| SessionOpaqueRef | string | False |  |  |
| Uuid | guid | True |  |  |
| WhatIf | switch | False |  |  |
### Procedure
None

### Inputs
```
XenAPI.Cluster
XenAPI.XenRef`1[[XenAPI.Cluster, XenServer, Version=8.2.3.0, Culture=neutral, PublicKeyToken=d247b8b0ac7959e9]]
System.Guid

```
### Outputs
```
XenAPI.Cluster
System.Void

```
### Links
None

### Examples

Add-XenCluster [-Cluster] <Cluster> [-PassThru] [-OtherConfig <KeyValuePair[string,string]>] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [<CommonParameters>]

Add-XenCluster [-Ref] <XenRef[Cluster]> [-PassThru] [-OtherConfig <KeyValuePair[string,string]>] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [<CommonParameters>]

Add-XenCluster [-Uuid] <guid> [-PassThru] [-OtherConfig <KeyValuePair[string,string]>] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [<CommonParameters>]


## Add-XenConsole

### Synopsis
None

### Description
None

### Syntax
```
Add-XenConsole [-Console] <Console> [[-PassThru]] [[-OtherConfig] <KeyValuePair[string,string]>] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]] [-Ref] <XenRef[Console]> [[-PassThru]] [[-OtherConfig] <KeyValuePair[string,string]>] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]] [-Uuid] <guid> [[-PassThru]] [[-OtherConfig] <KeyValuePair[string,string]>] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]]
```
### Parameters
| Name | Type | Required | Default Value | Description |
| :--- | :--- | :------- | :------------ | :---------- |
| BestEffort | switch | False |  |  |
| Confirm | switch | False |  |  |
| Console | Console | True |  |  |
| OtherConfig | KeyValuePair[string,string] | False |  |  |
| PassThru | switch | False |  |  |
| Ref | XenRef[Console] | True |  |  |
| SessionOpaqueRef | string | False |  |  |
| Uuid | guid | True |  |  |
| WhatIf | switch | False |  |  |
### Procedure
None

### Inputs
```
XenAPI.Console
XenAPI.XenRef`1[[XenAPI.Console, XenServer, Version=8.2.3.0, Culture=neutral, PublicKeyToken=d247b8b0ac7959e9]]
System.Guid

```
### Outputs
```
XenAPI.Console
System.Void

```
### Links
None

### Examples

Add-XenConsole [-Console] <Console> [-PassThru] [-OtherConfig <KeyValuePair[string,string]>] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [<CommonParameters>]

Add-XenConsole [-Ref] <XenRef[Console]> [-PassThru] [-OtherConfig <KeyValuePair[string,string]>] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [<CommonParameters>]

Add-XenConsole [-Uuid] <guid> [-PassThru] [-OtherConfig <KeyValuePair[string,string]>] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [<CommonParameters>]


## Add-XenCrashdump

### Synopsis
None

### Description
None

### Syntax
```
Add-XenCrashdump [-Crashdump] <Crashdump> [[-PassThru]] [[-OtherConfig] <KeyValuePair[string,string]>] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]] [-Ref] <XenRef[Crashdump]> [[-PassThru]] [[-OtherConfig] <KeyValuePair[string,string]>] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]] [-Uuid] <guid> [[-PassThru]] [[-OtherConfig] <KeyValuePair[string,string]>] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]]
```
### Parameters
| Name | Type | Required | Default Value | Description |
| :--- | :--- | :------- | :------------ | :---------- |
| BestEffort | switch | False |  |  |
| Confirm | switch | False |  |  |
| Crashdump | Crashdump | True |  |  |
| OtherConfig | KeyValuePair[string,string] | False |  |  |
| PassThru | switch | False |  |  |
| Ref | XenRef[Crashdump] | True |  |  |
| SessionOpaqueRef | string | False |  |  |
| Uuid | guid | True |  |  |
| WhatIf | switch | False |  |  |
### Procedure
None

### Inputs
```
XenAPI.Crashdump
XenAPI.XenRef`1[[XenAPI.Crashdump, XenServer, Version=8.2.3.0, Culture=neutral, PublicKeyToken=d247b8b0ac7959e9]]
System.Guid

```
### Outputs
```
XenAPI.Crashdump
System.Void

```
### Links
None

### Examples

Add-XenCrashdump [-Crashdump] <Crashdump> [-PassThru] [-OtherConfig <KeyValuePair[string,string]>] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [<CommonParameters>]

Add-XenCrashdump [-Ref] <XenRef[Crashdump]> [-PassThru] [-OtherConfig <KeyValuePair[string,string]>] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [<CommonParameters>]

Add-XenCrashdump [-Uuid] <guid> [-PassThru] [-OtherConfig <KeyValuePair[string,string]>] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [<CommonParameters>]


## Add-XenGPUGroup

### Synopsis
None

### Description
None

### Syntax
```
Add-XenGPUGroup [-GPUGroup] <GPU_group> [[-PassThru]] [[-OtherConfig] <KeyValuePair[string,string]>] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]] [-Ref] <XenRef[GPU_group]> [[-PassThru]] [[-OtherConfig] <KeyValuePair[string,string]>] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]] [-Uuid] <guid> [[-PassThru]] [[-OtherConfig] <KeyValuePair[string,string]>] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]] [-Name] <string> [[-PassThru]] [[-OtherConfig] <KeyValuePair[string,string]>] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]]
```
### Parameters
| Name | Type | Required | Default Value | Description |
| :--- | :--- | :------- | :------------ | :---------- |
| BestEffort | switch | False |  |  |
| Confirm | switch | False |  |  |
| GPUGroup | GPU_group | True |  |  |
| Name | string | True |  |  |
| OtherConfig | KeyValuePair[string,string] | False |  |  |
| PassThru | switch | False |  |  |
| Ref | XenRef[GPU_group] | True |  |  |
| SessionOpaqueRef | string | False |  |  |
| Uuid | guid | True |  |  |
| WhatIf | switch | False |  |  |
### Procedure
None

### Inputs
```
XenAPI.GPU_group
XenAPI.XenRef`1[[XenAPI.GPU_group, XenServer, Version=8.2.3.0, Culture=neutral, PublicKeyToken=d247b8b0ac7959e9]]
System.Guid
System.String

```
### Outputs
```
XenAPI.GPU_group
System.Void

```
### Links
None

### Examples

Add-XenGPUGroup [-GPUGroup] <GPU_group> [-PassThru] [-OtherConfig <KeyValuePair[string,string]>] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [<CommonParameters>]

Add-XenGPUGroup [-Ref] <XenRef[GPU_group]> [-PassThru] [-OtherConfig <KeyValuePair[string,string]>] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [<CommonParameters>]

Add-XenGPUGroup [-Uuid] <guid> [-PassThru] [-OtherConfig <KeyValuePair[string,string]>] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [<CommonParameters>]

Add-XenGPUGroup [-Name] <string> [-PassThru] [-OtherConfig <KeyValuePair[string,string]>] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [<CommonParameters>]


## Add-XenHost

### Synopsis
None

### Description
None

### Syntax
```
Add-XenHost [-XenHost] <Host> [[-PassThru]] [[-OtherConfig] <KeyValuePair[string,string]>] [[-Logging] <KeyValuePair[string,string]>] [[-Tags] <string>] [[-LicenseServer] <KeyValuePair[string,string]>] [[-GuestVCPUsParams] <KeyValuePair[string,string]>] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]] [-Ref] <XenRef[Host]> [[-PassThru]] [[-OtherConfig] <KeyValuePair[string,string]>] [[-Logging] <KeyValuePair[string,string]>] [[-Tags] <string>] [[-LicenseServer] <KeyValuePair[string,string]>] [[-GuestVCPUsParams] <KeyValuePair[string,string]>] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]] [-Uuid] <guid> [[-PassThru]] [[-OtherConfig] <KeyValuePair[string,string]>] [[-Logging] <KeyValuePair[string,string]>] [[-Tags] <string>] [[-LicenseServer] <KeyValuePair[string,string]>] [[-GuestVCPUsParams] <KeyValuePair[string,string]>] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]] [-Name] <string> [[-PassThru]] [[-OtherConfig] <KeyValuePair[string,string]>] [[-Logging] <KeyValuePair[string,string]>] [[-Tags] <string>] [[-LicenseServer] <KeyValuePair[string,string]>] [[-GuestVCPUsParams] <KeyValuePair[string,string]>] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]]
```
### Parameters
| Name | Type | Required | Default Value | Description |
| :--- | :--- | :------- | :------------ | :---------- |
| BestEffort | switch | False |  |  |
| Confirm | switch | False |  |  |
| GuestVCPUsParams | KeyValuePair[string,string] | False |  |  |
| LicenseServer | KeyValuePair[string,string] | False |  |  |
| Logging | KeyValuePair[string,string] | False |  |  |
| Name | string | True |  |  |
| OtherConfig | KeyValuePair[string,string] | False |  |  |
| PassThru | switch | False |  |  |
| Ref | XenRef[Host] | True |  |  |
| SessionOpaqueRef | string | False |  |  |
| Tags | string | False |  |  |
| Uuid | guid | True |  |  |
| WhatIf | switch | False |  |  |
| XenHost | Host | True |  |  |
### Procedure
None

### Inputs
```
XenAPI.Host
XenAPI.XenRef`1[[XenAPI.Host, XenServer, Version=8.2.3.0, Culture=neutral, PublicKeyToken=d247b8b0ac7959e9]]
System.Guid
System.String

```
### Outputs
```
XenAPI.Host
System.Void

```
### Links
None

### Examples

Add-XenHost [-XenHost] <Host> [-PassThru] [-OtherConfig <KeyValuePair[string,string]>] [-Logging <KeyValuePair[string,string]>] [-Tags <string>] [-LicenseServer <KeyValuePair[string,string]>] [-GuestVCPUsParams <KeyValuePair[string,string]>] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [<CommonParameters>]

Add-XenHost [-Ref] <XenRef[Host]> [-PassThru] [-OtherConfig <KeyValuePair[string,string]>] [-Logging <KeyValuePair[string,string]>] [-Tags <string>] [-LicenseServer <KeyValuePair[string,string]>] [-GuestVCPUsParams <KeyValuePair[string,string]>] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [<CommonParameters>]

Add-XenHost [-Uuid] <guid> [-PassThru] [-OtherConfig <KeyValuePair[string,string]>] [-Logging <KeyValuePair[string,string]>] [-Tags <string>] [-LicenseServer <KeyValuePair[string,string]>] [-GuestVCPUsParams <KeyValuePair[string,string]>] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [<CommonParameters>]

Add-XenHost [-Name] <string> [-PassThru] [-OtherConfig <KeyValuePair[string,string]>] [-Logging <KeyValuePair[string,string]>] [-Tags <string>] [-LicenseServer <KeyValuePair[string,string]>] [-GuestVCPUsParams <KeyValuePair[string,string]>] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [<CommonParameters>]


## Add-XenHostCpu

### Synopsis
None

### Description
None

### Syntax
```
Add-XenHostCpu [-HostCpu] <Host_cpu> [[-PassThru]] [[-OtherConfig] <KeyValuePair[string,string]>] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]] [-Ref] <XenRef[Host_cpu]> [[-PassThru]] [[-OtherConfig] <KeyValuePair[string,string]>] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]] [-Uuid] <guid> [[-PassThru]] [[-OtherConfig] <KeyValuePair[string,string]>] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]]
```
### Parameters
| Name | Type | Required | Default Value | Description |
| :--- | :--- | :------- | :------------ | :---------- |
| BestEffort | switch | False |  |  |
| Confirm | switch | False |  |  |
| HostCpu | Host_cpu | True |  |  |
| OtherConfig | KeyValuePair[string,string] | False |  |  |
| PassThru | switch | False |  |  |
| Ref | XenRef[Host_cpu] | True |  |  |
| SessionOpaqueRef | string | False |  |  |
| Uuid | guid | True |  |  |
| WhatIf | switch | False |  |  |
### Procedure
None

### Inputs
```
XenAPI.Host_cpu
XenAPI.XenRef`1[[XenAPI.Host_cpu, XenServer, Version=8.2.3.0, Culture=neutral, PublicKeyToken=d247b8b0ac7959e9]]
System.Guid

```
### Outputs
```
XenAPI.Host_cpu
System.Void

```
### Links
None

### Examples

Add-XenHostCpu [-HostCpu] <Host_cpu> [-PassThru] [-OtherConfig <KeyValuePair[string,string]>] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [<CommonParameters>]

Add-XenHostCpu [-Ref] <XenRef[Host_cpu]> [-PassThru] [-OtherConfig <KeyValuePair[string,string]>] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [<CommonParameters>]

Add-XenHostCpu [-Uuid] <guid> [-PassThru] [-OtherConfig <KeyValuePair[string,string]>] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [<CommonParameters>]


## Add-XenHostCrashdump

### Synopsis
None

### Description
None

### Syntax
```
Add-XenHostCrashdump [-HostCrashdump] <Host_crashdump> [[-PassThru]] [[-OtherConfig] <KeyValuePair[string,string]>] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]] [-Ref] <XenRef[Host_crashdump]> [[-PassThru]] [[-OtherConfig] <KeyValuePair[string,string]>] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]] [-Uuid] <guid> [[-PassThru]] [[-OtherConfig] <KeyValuePair[string,string]>] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]]
```
### Parameters
| Name | Type | Required | Default Value | Description |
| :--- | :--- | :------- | :------------ | :---------- |
| BestEffort | switch | False |  |  |
| Confirm | switch | False |  |  |
| HostCrashdump | Host_crashdump | True |  |  |
| OtherConfig | KeyValuePair[string,string] | False |  |  |
| PassThru | switch | False |  |  |
| Ref | XenRef[Host_crashdump] | True |  |  |
| SessionOpaqueRef | string | False |  |  |
| Uuid | guid | True |  |  |
| WhatIf | switch | False |  |  |
### Procedure
None

### Inputs
```
XenAPI.Host_crashdump
XenAPI.XenRef`1[[XenAPI.Host_crashdump, XenServer, Version=8.2.3.0, Culture=neutral, PublicKeyToken=d247b8b0ac7959e9]]
System.Guid

```
### Outputs
```
XenAPI.Host_crashdump
System.Void

```
### Links
None

### Examples

Add-XenHostCrashdump [-HostCrashdump] <Host_crashdump> [-PassThru] [-OtherConfig <KeyValuePair[string,string]>] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [<CommonParameters>]

Add-XenHostCrashdump [-Ref] <XenRef[Host_crashdump]> [-PassThru] [-OtherConfig <KeyValuePair[string,string]>] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [<CommonParameters>]

Add-XenHostCrashdump [-Uuid] <guid> [-PassThru] [-OtherConfig <KeyValuePair[string,string]>] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [<CommonParameters>]


## Add-XenHostMetrics

### Synopsis
None

### Description
None

### Syntax
```
Add-XenHostMetrics [-HostMetrics] <Host_metrics> [[-PassThru]] [[-OtherConfig] <KeyValuePair[string,string]>] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]] [-Ref] <XenRef[Host_metrics]> [[-PassThru]] [[-OtherConfig] <KeyValuePair[string,string]>] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]] [-Uuid] <guid> [[-PassThru]] [[-OtherConfig] <KeyValuePair[string,string]>] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]]
```
### Parameters
| Name | Type | Required | Default Value | Description |
| :--- | :--- | :------- | :------------ | :---------- |
| BestEffort | switch | False |  |  |
| Confirm | switch | False |  |  |
| HostMetrics | Host_metrics | True |  |  |
| OtherConfig | KeyValuePair[string,string] | False |  |  |
| PassThru | switch | False |  |  |
| Ref | XenRef[Host_metrics] | True |  |  |
| SessionOpaqueRef | string | False |  |  |
| Uuid | guid | True |  |  |
| WhatIf | switch | False |  |  |
### Procedure
None

### Inputs
```
XenAPI.Host_metrics
XenAPI.XenRef`1[[XenAPI.Host_metrics, XenServer, Version=8.2.3.0, Culture=neutral, PublicKeyToken=d247b8b0ac7959e9]]
System.Guid

```
### Outputs
```
XenAPI.Host_metrics
System.Void

```
### Links
None

### Examples

Add-XenHostMetrics [-HostMetrics] <Host_metrics> [-PassThru] [-OtherConfig <KeyValuePair[string,string]>] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [<CommonParameters>]

Add-XenHostMetrics [-Ref] <XenRef[Host_metrics]> [-PassThru] [-OtherConfig <KeyValuePair[string,string]>] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [<CommonParameters>]

Add-XenHostMetrics [-Uuid] <guid> [-PassThru] [-OtherConfig <KeyValuePair[string,string]>] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [<CommonParameters>]


## Add-XenHostPatch

### Synopsis
None

### Description
None

### Syntax
```
Add-XenHostPatch [-HostPatch] <Host_patch> [[-PassThru]] [[-OtherConfig] <KeyValuePair[string,string]>] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]] [-Ref] <XenRef[Host_patch]> [[-PassThru]] [[-OtherConfig] <KeyValuePair[string,string]>] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]] [-Uuid] <guid> [[-PassThru]] [[-OtherConfig] <KeyValuePair[string,string]>] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]] [-Name] <string> [[-PassThru]] [[-OtherConfig] <KeyValuePair[string,string]>] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]]
```
### Parameters
| Name | Type | Required | Default Value | Description |
| :--- | :--- | :------- | :------------ | :---------- |
| BestEffort | switch | False |  |  |
| Confirm | switch | False |  |  |
| HostPatch | Host_patch | True |  |  |
| Name | string | True |  |  |
| OtherConfig | KeyValuePair[string,string] | False |  |  |
| PassThru | switch | False |  |  |
| Ref | XenRef[Host_patch] | True |  |  |
| SessionOpaqueRef | string | False |  |  |
| Uuid | guid | True |  |  |
| WhatIf | switch | False |  |  |
### Procedure
None

### Inputs
```
XenAPI.Host_patch
XenAPI.XenRef`1[[XenAPI.Host_patch, XenServer, Version=8.2.3.0, Culture=neutral, PublicKeyToken=d247b8b0ac7959e9]]
System.Guid
System.String

```
### Outputs
```
XenAPI.Host_patch
System.Void

```
### Links
None

### Examples

Add-XenHostPatch [-HostPatch] <Host_patch> [-PassThru] [-OtherConfig <KeyValuePair[string,string]>] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [<CommonParameters>]

Add-XenHostPatch [-Ref] <XenRef[Host_patch]> [-PassThru] [-OtherConfig <KeyValuePair[string,string]>] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [<CommonParameters>]

Add-XenHostPatch [-Uuid] <guid> [-PassThru] [-OtherConfig <KeyValuePair[string,string]>] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [<CommonParameters>]

Add-XenHostPatch [-Name] <string> [-PassThru] [-OtherConfig <KeyValuePair[string,string]>] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [<CommonParameters>]


## Add-XenNetwork

### Synopsis
None

### Description
None

### Syntax
```
Add-XenNetwork [-Network] <Network> [[-PassThru]] [[-OtherConfig] <KeyValuePair[string,string]>] [[-Tags] <string>] [[-Purpose] <network_purpose>] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]] [-Ref] <XenRef[Network]> [[-PassThru]] [[-OtherConfig] <KeyValuePair[string,string]>] [[-Tags] <string>] [[-Purpose] <network_purpose>] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]] [-Uuid] <guid> [[-PassThru]] [[-OtherConfig] <KeyValuePair[string,string]>] [[-Tags] <string>] [[-Purpose] <network_purpose>] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]] [-Name] <string> [[-PassThru]] [[-OtherConfig] <KeyValuePair[string,string]>] [[-Tags] <string>] [[-Purpose] <network_purpose>] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]]
```
### Parameters
| Name | Type | Required | Default Value | Description |
| :--- | :--- | :------- | :------------ | :---------- |
| BestEffort | switch | False |  |  |
| Confirm | switch | False |  |  |
| Name | string | True |  |  |
| Network | Network | True |  |  |
| OtherConfig | KeyValuePair[string,string] | False |  |  |
| PassThru | switch | False |  |  |
| Purpose | network_purpose | False |  |  |
| Ref | XenRef[Network] | True |  |  |
| SessionOpaqueRef | string | False |  |  |
| Tags | string | False |  |  |
| Uuid | guid | True |  |  |
| WhatIf | switch | False |  |  |
### Procedure
None

### Inputs
```
XenAPI.Network
XenAPI.XenRef`1[[XenAPI.Network, XenServer, Version=8.2.3.0, Culture=neutral, PublicKeyToken=d247b8b0ac7959e9]]
System.Guid
System.String

```
### Outputs
```
XenAPI.Network
XenAPI.Task
System.Void

```
### Links
None

### Examples

Add-XenNetwork [-Network] <Network> [-PassThru] [-OtherConfig <KeyValuePair[string,string]>] [-Tags <string>] [-Purpose <network_purpose>] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [<CommonParameters>]

Add-XenNetwork [-Ref] <XenRef[Network]> [-PassThru] [-OtherConfig <KeyValuePair[string,string]>] [-Tags <string>] [-Purpose <network_purpose>] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [<CommonParameters>]

Add-XenNetwork [-Uuid] <guid> [-PassThru] [-OtherConfig <KeyValuePair[string,string]>] [-Tags <string>] [-Purpose <network_purpose>] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [<CommonParameters>]

Add-XenNetwork [-Name] <string> [-PassThru] [-OtherConfig <KeyValuePair[string,string]>] [-Tags <string>] [-Purpose <network_purpose>] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [<CommonParameters>]


## Add-XenPBD

### Synopsis
None

### Description
None

### Syntax
```
Add-XenPBD [-PBD] <PBD> [[-PassThru]] [[-OtherConfig] <KeyValuePair[string,string]>] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]] [-Ref] <XenRef[PBD]> [[-PassThru]] [[-OtherConfig] <KeyValuePair[string,string]>] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]] [-Uuid] <guid> [[-PassThru]] [[-OtherConfig] <KeyValuePair[string,string]>] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]]
```
### Parameters
| Name | Type | Required | Default Value | Description |
| :--- | :--- | :------- | :------------ | :---------- |
| BestEffort | switch | False |  |  |
| Confirm | switch | False |  |  |
| OtherConfig | KeyValuePair[string,string] | False |  |  |
| PBD | PBD | True |  |  |
| PassThru | switch | False |  |  |
| Ref | XenRef[PBD] | True |  |  |
| SessionOpaqueRef | string | False |  |  |
| Uuid | guid | True |  |  |
| WhatIf | switch | False |  |  |
### Procedure
None

### Inputs
```
XenAPI.PBD
XenAPI.XenRef`1[[XenAPI.PBD, XenServer, Version=8.2.3.0, Culture=neutral, PublicKeyToken=d247b8b0ac7959e9]]
System.Guid

```
### Outputs
```
XenAPI.PBD
System.Void

```
### Links
None

### Examples

Add-XenPBD [-PBD] <PBD> [-PassThru] [-OtherConfig <KeyValuePair[string,string]>] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [<CommonParameters>]

Add-XenPBD [-Ref] <XenRef[PBD]> [-PassThru] [-OtherConfig <KeyValuePair[string,string]>] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [<CommonParameters>]

Add-XenPBD [-Uuid] <guid> [-PassThru] [-OtherConfig <KeyValuePair[string,string]>] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [<CommonParameters>]


## Add-XenPCI

### Synopsis
None

### Description
None

### Syntax
```
Add-XenPCI [-PCI] <PCI> [[-PassThru]] [[-OtherConfig] <KeyValuePair[string,string]>] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]] [-Ref] <XenRef[PCI]> [[-PassThru]] [[-OtherConfig] <KeyValuePair[string,string]>] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]] [-Uuid] <guid> [[-PassThru]] [[-OtherConfig] <KeyValuePair[string,string]>] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]]
```
### Parameters
| Name | Type | Required | Default Value | Description |
| :--- | :--- | :------- | :------------ | :---------- |
| BestEffort | switch | False |  |  |
| Confirm | switch | False |  |  |
| OtherConfig | KeyValuePair[string,string] | False |  |  |
| PCI | PCI | True |  |  |
| PassThru | switch | False |  |  |
| Ref | XenRef[PCI] | True |  |  |
| SessionOpaqueRef | string | False |  |  |
| Uuid | guid | True |  |  |
| WhatIf | switch | False |  |  |
### Procedure
None

### Inputs
```
XenAPI.PCI
XenAPI.XenRef`1[[XenAPI.PCI, XenServer, Version=8.2.3.0, Culture=neutral, PublicKeyToken=d247b8b0ac7959e9]]
System.Guid

```
### Outputs
```
XenAPI.PCI
System.Void

```
### Links
None

### Examples

Add-XenPCI [-PCI] <PCI> [-PassThru] [-OtherConfig <KeyValuePair[string,string]>] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [<CommonParameters>]

Add-XenPCI [-Ref] <XenRef[PCI]> [-PassThru] [-OtherConfig <KeyValuePair[string,string]>] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [<CommonParameters>]

Add-XenPCI [-Uuid] <guid> [-PassThru] [-OtherConfig <KeyValuePair[string,string]>] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [<CommonParameters>]


## Add-XenPGPU

### Synopsis
None

### Description
None

### Syntax
```
Add-XenPGPU [-PGPU] <PGPU> [[-PassThru]] [[-OtherConfig] <KeyValuePair[string,string]>] [[-EnabledVGPUTypes] <XenRef[VGPU_type]>] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]] [-Ref] <XenRef[PGPU]> [[-PassThru]] [[-OtherConfig] <KeyValuePair[string,string]>] [[-EnabledVGPUTypes] <XenRef[VGPU_type]>] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]] [-Uuid] <guid> [[-PassThru]] [[-OtherConfig] <KeyValuePair[string,string]>] [[-EnabledVGPUTypes] <XenRef[VGPU_type]>] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]]
```
### Parameters
| Name | Type | Required | Default Value | Description |
| :--- | :--- | :------- | :------------ | :---------- |
| BestEffort | switch | False |  |  |
| Confirm | switch | False |  |  |
| EnabledVGPUTypes | XenRef[VGPU_type] | False |  |  |
| OtherConfig | KeyValuePair[string,string] | False |  |  |
| PGPU | PGPU | True |  |  |
| PassThru | switch | False |  |  |
| Ref | XenRef[PGPU] | True |  |  |
| SessionOpaqueRef | string | False |  |  |
| Uuid | guid | True |  |  |
| WhatIf | switch | False |  |  |
### Procedure
None

### Inputs
```
XenAPI.PGPU
XenAPI.XenRef`1[[XenAPI.PGPU, XenServer, Version=8.2.3.0, Culture=neutral, PublicKeyToken=d247b8b0ac7959e9]]
System.Guid

```
### Outputs
```
XenAPI.PGPU
XenAPI.Task
System.Void

```
### Links
None

### Examples

Add-XenPGPU [-PGPU] <PGPU> [-PassThru] [-OtherConfig <KeyValuePair[string,string]>] [-EnabledVGPUTypes <XenRef[VGPU_type]>] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [<CommonParameters>]

Add-XenPGPU [-Ref] <XenRef[PGPU]> [-PassThru] [-OtherConfig <KeyValuePair[string,string]>] [-EnabledVGPUTypes <XenRef[VGPU_type]>] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [<CommonParameters>]

Add-XenPGPU [-Uuid] <guid> [-PassThru] [-OtherConfig <KeyValuePair[string,string]>] [-EnabledVGPUTypes <XenRef[VGPU_type]>] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [<CommonParameters>]


## Add-XenPIF

### Synopsis
None

### Description
None

### Syntax
```
Add-XenPIF [-PIF] <PIF> [[-PassThru]] [[-OtherConfig] <KeyValuePair[string,string]>] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]] [-Ref] <XenRef[PIF]> [[-PassThru]] [[-OtherConfig] <KeyValuePair[string,string]>] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]] [-Uuid] <guid> [[-PassThru]] [[-OtherConfig] <KeyValuePair[string,string]>] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]]
```
### Parameters
| Name | Type | Required | Default Value | Description |
| :--- | :--- | :------- | :------------ | :---------- |
| BestEffort | switch | False |  |  |
| Confirm | switch | False |  |  |
| OtherConfig | KeyValuePair[string,string] | False |  |  |
| PIF | PIF | True |  |  |
| PassThru | switch | False |  |  |
| Ref | XenRef[PIF] | True |  |  |
| SessionOpaqueRef | string | False |  |  |
| Uuid | guid | True |  |  |
| WhatIf | switch | False |  |  |
### Procedure
None

### Inputs
```
XenAPI.PIF
XenAPI.XenRef`1[[XenAPI.PIF, XenServer, Version=8.2.3.0, Culture=neutral, PublicKeyToken=d247b8b0ac7959e9]]
System.Guid

```
### Outputs
```
XenAPI.PIF
System.Void

```
### Links
None

### Examples

Add-XenPIF [-PIF] <PIF> [-PassThru] [-OtherConfig <KeyValuePair[string,string]>] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [<CommonParameters>]

Add-XenPIF [-Ref] <XenRef[PIF]> [-PassThru] [-OtherConfig <KeyValuePair[string,string]>] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [<CommonParameters>]

Add-XenPIF [-Uuid] <guid> [-PassThru] [-OtherConfig <KeyValuePair[string,string]>] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [<CommonParameters>]


## Add-XenPIFMetrics

### Synopsis
None

### Description
None

### Syntax
```
Add-XenPIFMetrics [-PIFMetrics] <PIF_metrics> [[-PassThru]] [[-OtherConfig] <KeyValuePair[string,string]>] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]] [-Ref] <XenRef[PIF_metrics]> [[-PassThru]] [[-OtherConfig] <KeyValuePair[string,string]>] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]] [-Uuid] <guid> [[-PassThru]] [[-OtherConfig] <KeyValuePair[string,string]>] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]]
```
### Parameters
| Name | Type | Required | Default Value | Description |
| :--- | :--- | :------- | :------------ | :---------- |
| BestEffort | switch | False |  |  |
| Confirm | switch | False |  |  |
| OtherConfig | KeyValuePair[string,string] | False |  |  |
| PIFMetrics | PIF_metrics | True |  |  |
| PassThru | switch | False |  |  |
| Ref | XenRef[PIF_metrics] | True |  |  |
| SessionOpaqueRef | string | False |  |  |
| Uuid | guid | True |  |  |
| WhatIf | switch | False |  |  |
### Procedure
None

### Inputs
```
XenAPI.PIF_metrics
XenAPI.XenRef`1[[XenAPI.PIF_metrics, XenServer, Version=8.2.3.0, Culture=neutral, PublicKeyToken=d247b8b0ac7959e9]]
System.Guid

```
### Outputs
```
XenAPI.PIF_metrics
System.Void

```
### Links
None

### Examples

Add-XenPIFMetrics [-PIFMetrics] <PIF_metrics> [-PassThru] [-OtherConfig <KeyValuePair[string,string]>] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [<CommonParameters>]

Add-XenPIFMetrics [-Ref] <XenRef[PIF_metrics]> [-PassThru] [-OtherConfig <KeyValuePair[string,string]>] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [<CommonParameters>]

Add-XenPIFMetrics [-Uuid] <guid> [-PassThru] [-OtherConfig <KeyValuePair[string,string]>] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [<CommonParameters>]


## Add-XenPool

### Synopsis
None

### Description
None

### Syntax
```
Add-XenPool [-Pool] <Pool> [[-PassThru]] [[-OtherConfig] <KeyValuePair[string,string]>] [[-Tags] <string>] [[-GuiConfig] <KeyValuePair[string,string]>] [[-HealthCheckConfig] <KeyValuePair[string,string]>] [[-GuestAgentConfig] <KeyValuePair[string,string]>] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]] [-Ref] <XenRef[Pool]> [[-PassThru]] [[-OtherConfig] <KeyValuePair[string,string]>] [[-Tags] <string>] [[-GuiConfig] <KeyValuePair[string,string]>] [[-HealthCheckConfig] <KeyValuePair[string,string]>] [[-GuestAgentConfig] <KeyValuePair[string,string]>] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]] [-Uuid] <guid> [[-PassThru]] [[-OtherConfig] <KeyValuePair[string,string]>] [[-Tags] <string>] [[-GuiConfig] <KeyValuePair[string,string]>] [[-HealthCheckConfig] <KeyValuePair[string,string]>] [[-GuestAgentConfig] <KeyValuePair[string,string]>] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]]
```
### Parameters
| Name | Type | Required | Default Value | Description |
| :--- | :--- | :------- | :------------ | :---------- |
| BestEffort | switch | False |  |  |
| Confirm | switch | False |  |  |
| GuestAgentConfig | KeyValuePair[string,string] | False |  |  |
| GuiConfig | KeyValuePair[string,string] | False |  |  |
| HealthCheckConfig | KeyValuePair[string,string] | False |  |  |
| OtherConfig | KeyValuePair[string,string] | False |  |  |
| PassThru | switch | False |  |  |
| Pool | Pool | True |  |  |
| Ref | XenRef[Pool] | True |  |  |
| SessionOpaqueRef | string | False |  |  |
| Tags | string | False |  |  |
| Uuid | guid | True |  |  |
| WhatIf | switch | False |  |  |
### Procedure
None

### Inputs
```
XenAPI.Pool
XenAPI.XenRef`1[[XenAPI.Pool, XenServer, Version=8.2.3.0, Culture=neutral, PublicKeyToken=d247b8b0ac7959e9]]
System.Guid

```
### Outputs
```
XenAPI.Pool
XenAPI.Task
System.Void

```
### Links
None

### Examples

Add-XenPool [-Pool] <Pool> [-PassThru] [-OtherConfig <KeyValuePair[string,string]>] [-Tags <string>] [-GuiConfig <KeyValuePair[string,string]>] [-HealthCheckConfig <KeyValuePair[string,string]>] [-GuestAgentConfig <KeyValuePair[string,string]>] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [<CommonParameters>]

Add-XenPool [-Ref] <XenRef[Pool]> [-PassThru] [-OtherConfig <KeyValuePair[string,string]>] [-Tags <string>] [-GuiConfig <KeyValuePair[string,string]>] [-HealthCheckConfig <KeyValuePair[string,string]>] [-GuestAgentConfig <KeyValuePair[string,string]>] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [<CommonParameters>]

Add-XenPool [-Uuid] <guid> [-PassThru] [-OtherConfig <KeyValuePair[string,string]>] [-Tags <string>] [-GuiConfig <KeyValuePair[string,string]>] [-HealthCheckConfig <KeyValuePair[string,string]>] [-GuestAgentConfig <KeyValuePair[string,string]>] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [<CommonParameters>]


## Add-XenPoolPatch

### Synopsis
None

### Description
None

### Syntax
```
Add-XenPoolPatch [-PoolPatch] <Pool_patch> [[-PassThru]] [[-OtherConfig] <KeyValuePair[string,string]>] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]] [-Ref] <XenRef[Pool_patch]> [[-PassThru]] [[-OtherConfig] <KeyValuePair[string,string]>] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]] [-Uuid] <guid> [[-PassThru]] [[-OtherConfig] <KeyValuePair[string,string]>] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]] [-Name] <string> [[-PassThru]] [[-OtherConfig] <KeyValuePair[string,string]>] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]]
```
### Parameters
| Name | Type | Required | Default Value | Description |
| :--- | :--- | :------- | :------------ | :---------- |
| BestEffort | switch | False |  |  |
| Confirm | switch | False |  |  |
| Name | string | True |  |  |
| OtherConfig | KeyValuePair[string,string] | False |  |  |
| PassThru | switch | False |  |  |
| PoolPatch | Pool_patch | True |  |  |
| Ref | XenRef[Pool_patch] | True |  |  |
| SessionOpaqueRef | string | False |  |  |
| Uuid | guid | True |  |  |
| WhatIf | switch | False |  |  |
### Procedure
None

### Inputs
```
XenAPI.Pool_patch
XenAPI.XenRef`1[[XenAPI.Pool_patch, XenServer, Version=8.2.3.0, Culture=neutral, PublicKeyToken=d247b8b0ac7959e9]]
System.Guid
System.String

```
### Outputs
```
XenAPI.Pool_patch
System.Void

```
### Links
None

### Examples

Add-XenPoolPatch [-PoolPatch] <Pool_patch> [-PassThru] [-OtherConfig <KeyValuePair[string,string]>] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [<CommonParameters>]

Add-XenPoolPatch [-Ref] <XenRef[Pool_patch]> [-PassThru] [-OtherConfig <KeyValuePair[string,string]>] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [<CommonParameters>]

Add-XenPoolPatch [-Uuid] <guid> [-PassThru] [-OtherConfig <KeyValuePair[string,string]>] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [<CommonParameters>]

Add-XenPoolPatch [-Name] <string> [-PassThru] [-OtherConfig <KeyValuePair[string,string]>] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [<CommonParameters>]


## Add-XenPoolUpdate

### Synopsis
None

### Description
None

### Syntax
```
Add-XenPoolUpdate [-PoolUpdate] <Pool_update> [[-PassThru]] [[-OtherConfig] <KeyValuePair[string,string]>] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]] [-Ref] <XenRef[Pool_update]> [[-PassThru]] [[-OtherConfig] <KeyValuePair[string,string]>] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]] [-Uuid] <guid> [[-PassThru]] [[-OtherConfig] <KeyValuePair[string,string]>] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]] [-Name] <string> [[-PassThru]] [[-OtherConfig] <KeyValuePair[string,string]>] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]]
```
### Parameters
| Name | Type | Required | Default Value | Description |
| :--- | :--- | :------- | :------------ | :---------- |
| BestEffort | switch | False |  |  |
| Confirm | switch | False |  |  |
| Name | string | True |  |  |
| OtherConfig | KeyValuePair[string,string] | False |  |  |
| PassThru | switch | False |  |  |
| PoolUpdate | Pool_update | True |  |  |
| Ref | XenRef[Pool_update] | True |  |  |
| SessionOpaqueRef | string | False |  |  |
| Uuid | guid | True |  |  |
| WhatIf | switch | False |  |  |
### Procedure
None

### Inputs
```
XenAPI.Pool_update
XenAPI.XenRef`1[[XenAPI.Pool_update, XenServer, Version=8.2.3.0, Culture=neutral, PublicKeyToken=d247b8b0ac7959e9]]
System.Guid
System.String

```
### Outputs
```
XenAPI.Pool_update
System.Void

```
### Links
None

### Examples

Add-XenPoolUpdate [-PoolUpdate] <Pool_update> [-PassThru] [-OtherConfig <KeyValuePair[string,string]>] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [<CommonParameters>]

Add-XenPoolUpdate [-Ref] <XenRef[Pool_update]> [-PassThru] [-OtherConfig <KeyValuePair[string,string]>] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [<CommonParameters>]

Add-XenPoolUpdate [-Uuid] <guid> [-PassThru] [-OtherConfig <KeyValuePair[string,string]>] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [<CommonParameters>]

Add-XenPoolUpdate [-Name] <string> [-PassThru] [-OtherConfig <KeyValuePair[string,string]>] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [<CommonParameters>]


## Add-XenPUSB

### Synopsis
None

### Description
None

### Syntax
```
Add-XenPUSB [-PUSB] <PUSB> [[-PassThru]] [[-OtherConfig] <KeyValuePair[string,string]>] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]] [-Ref] <XenRef[PUSB]> [[-PassThru]] [[-OtherConfig] <KeyValuePair[string,string]>] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]] [-Uuid] <guid> [[-PassThru]] [[-OtherConfig] <KeyValuePair[string,string]>] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]]
```
### Parameters
| Name | Type | Required | Default Value | Description |
| :--- | :--- | :------- | :------------ | :---------- |
| BestEffort | switch | False |  |  |
| Confirm | switch | False |  |  |
| OtherConfig | KeyValuePair[string,string] | False |  |  |
| PUSB | PUSB | True |  |  |
| PassThru | switch | False |  |  |
| Ref | XenRef[PUSB] | True |  |  |
| SessionOpaqueRef | string | False |  |  |
| Uuid | guid | True |  |  |
| WhatIf | switch | False |  |  |
### Procedure
None

### Inputs
```
XenAPI.PUSB
XenAPI.XenRef`1[[XenAPI.PUSB, XenServer, Version=8.2.3.0, Culture=neutral, PublicKeyToken=d247b8b0ac7959e9]]
System.Guid

```
### Outputs
```
XenAPI.PUSB
System.Void

```
### Links
None

### Examples

Add-XenPUSB [-PUSB] <PUSB> [-PassThru] [-OtherConfig <KeyValuePair[string,string]>] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [<CommonParameters>]

Add-XenPUSB [-Ref] <XenRef[PUSB]> [-PassThru] [-OtherConfig <KeyValuePair[string,string]>] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [<CommonParameters>]

Add-XenPUSB [-Uuid] <guid> [-PassThru] [-OtherConfig <KeyValuePair[string,string]>] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [<CommonParameters>]


## Add-XenSecret

### Synopsis
None

### Description
None

### Syntax
```
Add-XenSecret [-Secret] <Secret> [[-PassThru]] [[-OtherConfig] <KeyValuePair[string,string]>] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]] [-Ref] <XenRef[Secret]> [[-PassThru]] [[-OtherConfig] <KeyValuePair[string,string]>] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]] [-Uuid] <guid> [[-PassThru]] [[-OtherConfig] <KeyValuePair[string,string]>] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]]
```
### Parameters
| Name | Type | Required | Default Value | Description |
| :--- | :--- | :------- | :------------ | :---------- |
| BestEffort | switch | False |  |  |
| Confirm | switch | False |  |  |
| OtherConfig | KeyValuePair[string,string] | False |  |  |
| PassThru | switch | False |  |  |
| Ref | XenRef[Secret] | True |  |  |
| Secret | Secret | True |  |  |
| SessionOpaqueRef | string | False |  |  |
| Uuid | guid | True |  |  |
| WhatIf | switch | False |  |  |
### Procedure
None

### Inputs
```
XenAPI.Secret
XenAPI.XenRef`1[[XenAPI.Secret, XenServer, Version=8.2.3.0, Culture=neutral, PublicKeyToken=d247b8b0ac7959e9]]
System.Guid

```
### Outputs
```
XenAPI.Secret
System.Void

```
### Links
None

### Examples

Add-XenSecret [-Secret] <Secret> [-PassThru] [-OtherConfig <KeyValuePair[string,string]>] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [<CommonParameters>]

Add-XenSecret [-Ref] <XenRef[Secret]> [-PassThru] [-OtherConfig <KeyValuePair[string,string]>] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [<CommonParameters>]

Add-XenSecret [-Uuid] <guid> [-PassThru] [-OtherConfig <KeyValuePair[string,string]>] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [<CommonParameters>]


## Add-XenSM

### Synopsis
None

### Description
None

### Syntax
```
Add-XenSM [-SM] <SM> [[-PassThru]] [[-OtherConfig] <KeyValuePair[string,string]>] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]] [-Ref] <XenRef[SM]> [[-PassThru]] [[-OtherConfig] <KeyValuePair[string,string]>] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]] [-Uuid] <guid> [[-PassThru]] [[-OtherConfig] <KeyValuePair[string,string]>] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]] [-Name] <string> [[-PassThru]] [[-OtherConfig] <KeyValuePair[string,string]>] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]]
```
### Parameters
| Name | Type | Required | Default Value | Description |
| :--- | :--- | :------- | :------------ | :---------- |
| BestEffort | switch | False |  |  |
| Confirm | switch | False |  |  |
| Name | string | True |  |  |
| OtherConfig | KeyValuePair[string,string] | False |  |  |
| PassThru | switch | False |  |  |
| Ref | XenRef[SM] | True |  |  |
| SM | SM | True |  |  |
| SessionOpaqueRef | string | False |  |  |
| Uuid | guid | True |  |  |
| WhatIf | switch | False |  |  |
### Procedure
None

### Inputs
```
XenAPI.SM
XenAPI.XenRef`1[[XenAPI.SM, XenServer, Version=8.2.3.0, Culture=neutral, PublicKeyToken=d247b8b0ac7959e9]]
System.Guid
System.String

```
### Outputs
```
XenAPI.SM
System.Void

```
### Links
None

### Examples

Add-XenSM [-SM] <SM> [-PassThru] [-OtherConfig <KeyValuePair[string,string]>] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [<CommonParameters>]

Add-XenSM [-Ref] <XenRef[SM]> [-PassThru] [-OtherConfig <KeyValuePair[string,string]>] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [<CommonParameters>]

Add-XenSM [-Uuid] <guid> [-PassThru] [-OtherConfig <KeyValuePair[string,string]>] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [<CommonParameters>]

Add-XenSM [-Name] <string> [-PassThru] [-OtherConfig <KeyValuePair[string,string]>] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [<CommonParameters>]


## Add-XenSR

### Synopsis
None

### Description
None

### Syntax
```
Add-XenSR [-SR] <SR> [[-PassThru]] [[-OtherConfig] <KeyValuePair[string,string]>] [[-Tags] <string>] [[-SmConfig] <KeyValuePair[string,string]>] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]] [-Ref] <XenRef[SR]> [[-PassThru]] [[-OtherConfig] <KeyValuePair[string,string]>] [[-Tags] <string>] [[-SmConfig] <KeyValuePair[string,string]>] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]] [-Uuid] <guid> [[-PassThru]] [[-OtherConfig] <KeyValuePair[string,string]>] [[-Tags] <string>] [[-SmConfig] <KeyValuePair[string,string]>] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]] [-Name] <string> [[-PassThru]] [[-OtherConfig] <KeyValuePair[string,string]>] [[-Tags] <string>] [[-SmConfig] <KeyValuePair[string,string]>] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]]
```
### Parameters
| Name | Type | Required | Default Value | Description |
| :--- | :--- | :------- | :------------ | :---------- |
| BestEffort | switch | False |  |  |
| Confirm | switch | False |  |  |
| Name | string | True |  |  |
| OtherConfig | KeyValuePair[string,string] | False |  |  |
| PassThru | switch | False |  |  |
| Ref | XenRef[SR] | True |  |  |
| SR | SR | True |  |  |
| SessionOpaqueRef | string | False |  |  |
| SmConfig | KeyValuePair[string,string] | False |  |  |
| Tags | string | False |  |  |
| Uuid | guid | True |  |  |
| WhatIf | switch | False |  |  |
### Procedure
None

### Inputs
```
XenAPI.SR
XenAPI.XenRef`1[[XenAPI.SR, XenServer, Version=8.2.3.0, Culture=neutral, PublicKeyToken=d247b8b0ac7959e9]]
System.Guid
System.String

```
### Outputs
```
XenAPI.SR
System.Void

```
### Links
None

### Examples

Add-XenSR [-SR] <SR> [-PassThru] [-OtherConfig <KeyValuePair[string,string]>] [-Tags <string>] [-SmConfig <KeyValuePair[string,string]>] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [<CommonParameters>]

Add-XenSR [-Ref] <XenRef[SR]> [-PassThru] [-OtherConfig <KeyValuePair[string,string]>] [-Tags <string>] [-SmConfig <KeyValuePair[string,string]>] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [<CommonParameters>]

Add-XenSR [-Uuid] <guid> [-PassThru] [-OtherConfig <KeyValuePair[string,string]>] [-Tags <string>] [-SmConfig <KeyValuePair[string,string]>] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [<CommonParameters>]

Add-XenSR [-Name] <string> [-PassThru] [-OtherConfig <KeyValuePair[string,string]>] [-Tags <string>] [-SmConfig <KeyValuePair[string,string]>] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [<CommonParameters>]


## Add-XenSubject

### Synopsis
None

### Description
None

### Syntax
```
Add-XenSubject [-Subject] <Subject> [[-PassThru]] [[-Roles] <XenRef[Role]>] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]] [-Ref] <XenRef[Subject]> [[-PassThru]] [[-Roles] <XenRef[Role]>] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]] [-Uuid] <guid> [[-PassThru]] [[-Roles] <XenRef[Role]>] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]]
```
### Parameters
| Name | Type | Required | Default Value | Description |
| :--- | :--- | :------- | :------------ | :---------- |
| BestEffort | switch | False |  |  |
| Confirm | switch | False |  |  |
| PassThru | switch | False |  |  |
| Ref | XenRef[Subject] | True |  |  |
| Roles | XenRef[Role] | False |  |  |
| SessionOpaqueRef | string | False |  |  |
| Subject | Subject | True |  |  |
| Uuid | guid | True |  |  |
| WhatIf | switch | False |  |  |
### Procedure
None

### Inputs
```
XenAPI.Subject
XenAPI.XenRef`1[[XenAPI.Subject, XenServer, Version=8.2.3.0, Culture=neutral, PublicKeyToken=d247b8b0ac7959e9]]
System.Guid

```
### Outputs
```
XenAPI.Subject
System.Void

```
### Links
None

### Examples

Add-XenSubject [-Subject] <Subject> [-PassThru] [-Roles <XenRef[Role]>] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [<CommonParameters>]

Add-XenSubject [-Ref] <XenRef[Subject]> [-PassThru] [-Roles <XenRef[Role]>] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [<CommonParameters>]

Add-XenSubject [-Uuid] <guid> [-PassThru] [-Roles <XenRef[Role]>] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [<CommonParameters>]


## Add-XenTask

### Synopsis
None

### Description
None

### Syntax
```
Add-XenTask [-Task] <Task> [[-PassThru]] [[-OtherConfig] <KeyValuePair[string,string]>] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]] [-Ref] <XenRef[Task]> [[-PassThru]] [[-OtherConfig] <KeyValuePair[string,string]>] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]] [-Uuid] <guid> [[-PassThru]] [[-OtherConfig] <KeyValuePair[string,string]>] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]] [-Name] <string> [[-PassThru]] [[-OtherConfig] <KeyValuePair[string,string]>] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]]
```
### Parameters
| Name | Type | Required | Default Value | Description |
| :--- | :--- | :------- | :------------ | :---------- |
| BestEffort | switch | False |  |  |
| Confirm | switch | False |  |  |
| Name | string | True |  |  |
| OtherConfig | KeyValuePair[string,string] | False |  |  |
| PassThru | switch | False |  |  |
| Ref | XenRef[Task] | True |  |  |
| SessionOpaqueRef | string | False |  |  |
| Task | Task | True |  |  |
| Uuid | guid | True |  |  |
| WhatIf | switch | False |  |  |
### Procedure
None

### Inputs
```
XenAPI.Task
XenAPI.XenRef`1[[XenAPI.Task, XenServer, Version=8.2.3.0, Culture=neutral, PublicKeyToken=d247b8b0ac7959e9]]
System.Guid
System.String

```
### Outputs
```
XenAPI.Task
System.Void

```
### Links
None

### Examples

Add-XenTask [-Task] <Task> [-PassThru] [-OtherConfig <KeyValuePair[string,string]>] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [<CommonParameters>]

Add-XenTask [-Ref] <XenRef[Task]> [-PassThru] [-OtherConfig <KeyValuePair[string,string]>] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [<CommonParameters>]

Add-XenTask [-Uuid] <guid> [-PassThru] [-OtherConfig <KeyValuePair[string,string]>] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [<CommonParameters>]

Add-XenTask [-Name] <string> [-PassThru] [-OtherConfig <KeyValuePair[string,string]>] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [<CommonParameters>]


## Add-XenTunnel

### Synopsis
None

### Description
None

### Syntax
```
Add-XenTunnel [-Tunnel] <Tunnel> [[-PassThru]] [[-Status] <KeyValuePair[string,string]>] [[-OtherConfig] <KeyValuePair[string,string]>] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]] [-Ref] <XenRef[Tunnel]> [[-PassThru]] [[-Status] <KeyValuePair[string,string]>] [[-OtherConfig] <KeyValuePair[string,string]>] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]] [-Uuid] <guid> [[-PassThru]] [[-Status] <KeyValuePair[string,string]>] [[-OtherConfig] <KeyValuePair[string,string]>] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]]
```
### Parameters
| Name | Type | Required | Default Value | Description |
| :--- | :--- | :------- | :------------ | :---------- |
| BestEffort | switch | False |  |  |
| Confirm | switch | False |  |  |
| OtherConfig | KeyValuePair[string,string] | False |  |  |
| PassThru | switch | False |  |  |
| Ref | XenRef[Tunnel] | True |  |  |
| SessionOpaqueRef | string | False |  |  |
| Status | KeyValuePair[string,string] | False |  |  |
| Tunnel | Tunnel | True |  |  |
| Uuid | guid | True |  |  |
| WhatIf | switch | False |  |  |
### Procedure
None

### Inputs
```
XenAPI.Tunnel
XenAPI.XenRef`1[[XenAPI.Tunnel, XenServer, Version=8.2.3.0, Culture=neutral, PublicKeyToken=d247b8b0ac7959e9]]
System.Guid

```
### Outputs
```
XenAPI.Tunnel
System.Void

```
### Links
None

### Examples

Add-XenTunnel [-Tunnel] <Tunnel> [-PassThru] [-Status <KeyValuePair[string,string]>] [-OtherConfig <KeyValuePair[string,string]>] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [<CommonParameters>]

Add-XenTunnel [-Ref] <XenRef[Tunnel]> [-PassThru] [-Status <KeyValuePair[string,string]>] [-OtherConfig <KeyValuePair[string,string]>] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [<CommonParameters>]

Add-XenTunnel [-Uuid] <guid> [-PassThru] [-Status <KeyValuePair[string,string]>] [-OtherConfig <KeyValuePair[string,string]>] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [<CommonParameters>]


## Add-XenUSBGroup

### Synopsis
None

### Description
None

### Syntax
```
Add-XenUSBGroup [-USBGroup] <USB_group> [[-PassThru]] [[-OtherConfig] <KeyValuePair[string,string]>] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]] [-Ref] <XenRef[USB_group]> [[-PassThru]] [[-OtherConfig] <KeyValuePair[string,string]>] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]] [-Uuid] <guid> [[-PassThru]] [[-OtherConfig] <KeyValuePair[string,string]>] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]] [-Name] <string> [[-PassThru]] [[-OtherConfig] <KeyValuePair[string,string]>] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]]
```
### Parameters
| Name | Type | Required | Default Value | Description |
| :--- | :--- | :------- | :------------ | :---------- |
| BestEffort | switch | False |  |  |
| Confirm | switch | False |  |  |
| Name | string | True |  |  |
| OtherConfig | KeyValuePair[string,string] | False |  |  |
| PassThru | switch | False |  |  |
| Ref | XenRef[USB_group] | True |  |  |
| SessionOpaqueRef | string | False |  |  |
| USBGroup | USB_group | True |  |  |
| Uuid | guid | True |  |  |
| WhatIf | switch | False |  |  |
### Procedure
None

### Inputs
```
XenAPI.USB_group
XenAPI.XenRef`1[[XenAPI.USB_group, XenServer, Version=8.2.3.0, Culture=neutral, PublicKeyToken=d247b8b0ac7959e9]]
System.Guid
System.String

```
### Outputs
```
XenAPI.USB_group
System.Void

```
### Links
None

### Examples

Add-XenUSBGroup [-USBGroup] <USB_group> [-PassThru] [-OtherConfig <KeyValuePair[string,string]>] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [<CommonParameters>]

Add-XenUSBGroup [-Ref] <XenRef[USB_group]> [-PassThru] [-OtherConfig <KeyValuePair[string,string]>] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [<CommonParameters>]

Add-XenUSBGroup [-Uuid] <guid> [-PassThru] [-OtherConfig <KeyValuePair[string,string]>] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [<CommonParameters>]

Add-XenUSBGroup [-Name] <string> [-PassThru] [-OtherConfig <KeyValuePair[string,string]>] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [<CommonParameters>]


## Add-XenUser

### Synopsis
None

### Description
None

### Syntax
```
Add-XenUser [-User] <User> [[-PassThru]] [[-OtherConfig] <KeyValuePair[string,string]>] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]] [-Ref] <XenRef[User]> [[-PassThru]] [[-OtherConfig] <KeyValuePair[string,string]>] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]] [-Uuid] <guid> [[-PassThru]] [[-OtherConfig] <KeyValuePair[string,string]>] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]]
```
### Parameters
| Name | Type | Required | Default Value | Description |
| :--- | :--- | :------- | :------------ | :---------- |
| BestEffort | switch | False |  |  |
| Confirm | switch | False |  |  |
| OtherConfig | KeyValuePair[string,string] | False |  |  |
| PassThru | switch | False |  |  |
| Ref | XenRef[User] | True |  |  |
| SessionOpaqueRef | string | False |  |  |
| User | User | True |  |  |
| Uuid | guid | True |  |  |
| WhatIf | switch | False |  |  |
### Procedure
None

### Inputs
```
XenAPI.User
XenAPI.XenRef`1[[XenAPI.User, XenServer, Version=8.2.3.0, Culture=neutral, PublicKeyToken=d247b8b0ac7959e9]]
System.Guid

```
### Outputs
```
XenAPI.User
System.Void

```
### Links
None

### Examples

Add-XenUser [-User] <User> [-PassThru] [-OtherConfig <KeyValuePair[string,string]>] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [<CommonParameters>]

Add-XenUser [-Ref] <XenRef[User]> [-PassThru] [-OtherConfig <KeyValuePair[string,string]>] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [<CommonParameters>]

Add-XenUser [-Uuid] <guid> [-PassThru] [-OtherConfig <KeyValuePair[string,string]>] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [<CommonParameters>]


## Add-XenVBD

### Synopsis
None

### Description
None

### Syntax
```
Add-XenVBD [-VBD] <VBD> [[-PassThru]] [[-OtherConfig] <KeyValuePair[string,string]>] [[-QosAlgorithmParams] <KeyValuePair[string,string]>] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]] [-Ref] <XenRef[VBD]> [[-PassThru]] [[-OtherConfig] <KeyValuePair[string,string]>] [[-QosAlgorithmParams] <KeyValuePair[string,string]>] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]] [-Uuid] <guid> [[-PassThru]] [[-OtherConfig] <KeyValuePair[string,string]>] [[-QosAlgorithmParams] <KeyValuePair[string,string]>] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]]
```
### Parameters
| Name | Type | Required | Default Value | Description |
| :--- | :--- | :------- | :------------ | :---------- |
| BestEffort | switch | False |  |  |
| Confirm | switch | False |  |  |
| OtherConfig | KeyValuePair[string,string] | False |  |  |
| PassThru | switch | False |  |  |
| QosAlgorithmParams | KeyValuePair[string,string] | False |  |  |
| Ref | XenRef[VBD] | True |  |  |
| SessionOpaqueRef | string | False |  |  |
| Uuid | guid | True |  |  |
| VBD | VBD | True |  |  |
| WhatIf | switch | False |  |  |
### Procedure
None

### Inputs
```
XenAPI.VBD
XenAPI.XenRef`1[[XenAPI.VBD, XenServer, Version=8.2.3.0, Culture=neutral, PublicKeyToken=d247b8b0ac7959e9]]
System.Guid

```
### Outputs
```
XenAPI.VBD
System.Void

```
### Links
None

### Examples

Add-XenVBD [-VBD] <VBD> [-PassThru] [-OtherConfig <KeyValuePair[string,string]>] [-QosAlgorithmParams <KeyValuePair[string,string]>] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [<CommonParameters>]

Add-XenVBD [-Ref] <XenRef[VBD]> [-PassThru] [-OtherConfig <KeyValuePair[string,string]>] [-QosAlgorithmParams <KeyValuePair[string,string]>] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [<CommonParameters>]

Add-XenVBD [-Uuid] <guid> [-PassThru] [-OtherConfig <KeyValuePair[string,string]>] [-QosAlgorithmParams <KeyValuePair[string,string]>] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [<CommonParameters>]


## Add-XenVBDMetrics

### Synopsis
None

### Description
None

### Syntax
```
Add-XenVBDMetrics [-VBDMetrics] <VBD_metrics> [[-PassThru]] [[-OtherConfig] <KeyValuePair[string,string]>] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]] [-Ref] <XenRef[VBD_metrics]> [[-PassThru]] [[-OtherConfig] <KeyValuePair[string,string]>] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]] [-Uuid] <guid> [[-PassThru]] [[-OtherConfig] <KeyValuePair[string,string]>] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]]
```
### Parameters
| Name | Type | Required | Default Value | Description |
| :--- | :--- | :------- | :------------ | :---------- |
| BestEffort | switch | False |  |  |
| Confirm | switch | False |  |  |
| OtherConfig | KeyValuePair[string,string] | False |  |  |
| PassThru | switch | False |  |  |
| Ref | XenRef[VBD_metrics] | True |  |  |
| SessionOpaqueRef | string | False |  |  |
| Uuid | guid | True |  |  |
| VBDMetrics | VBD_metrics | True |  |  |
| WhatIf | switch | False |  |  |
### Procedure
None

### Inputs
```
XenAPI.VBD_metrics
XenAPI.XenRef`1[[XenAPI.VBD_metrics, XenServer, Version=8.2.3.0, Culture=neutral, PublicKeyToken=d247b8b0ac7959e9]]
System.Guid

```
### Outputs
```
XenAPI.VBD_metrics
System.Void

```
### Links
None

### Examples

Add-XenVBDMetrics [-VBDMetrics] <VBD_metrics> [-PassThru] [-OtherConfig <KeyValuePair[string,string]>] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [<CommonParameters>]

Add-XenVBDMetrics [-Ref] <XenRef[VBD_metrics]> [-PassThru] [-OtherConfig <KeyValuePair[string,string]>] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [<CommonParameters>]

Add-XenVBDMetrics [-Uuid] <guid> [-PassThru] [-OtherConfig <KeyValuePair[string,string]>] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [<CommonParameters>]


## Add-XenVDI

### Synopsis
None

### Description
None

### Syntax
```
Add-XenVDI [-VDI] <VDI> [[-PassThru]] [[-OtherConfig] <KeyValuePair[string,string]>] [[-XenstoreData] <KeyValuePair[string,string]>] [[-SmConfig] <KeyValuePair[string,string]>] [[-Tags] <string>] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]] [-Ref] <XenRef[VDI]> [[-PassThru]] [[-OtherConfig] <KeyValuePair[string,string]>] [[-XenstoreData] <KeyValuePair[string,string]>] [[-SmConfig] <KeyValuePair[string,string]>] [[-Tags] <string>] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]] [-Uuid] <guid> [[-PassThru]] [[-OtherConfig] <KeyValuePair[string,string]>] [[-XenstoreData] <KeyValuePair[string,string]>] [[-SmConfig] <KeyValuePair[string,string]>] [[-Tags] <string>] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]] [-Name] <string> [[-PassThru]] [[-OtherConfig] <KeyValuePair[string,string]>] [[-XenstoreData] <KeyValuePair[string,string]>] [[-SmConfig] <KeyValuePair[string,string]>] [[-Tags] <string>] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]]
```
### Parameters
| Name | Type | Required | Default Value | Description |
| :--- | :--- | :------- | :------------ | :---------- |
| BestEffort | switch | False |  |  |
| Confirm | switch | False |  |  |
| Name | string | True |  |  |
| OtherConfig | KeyValuePair[string,string] | False |  |  |
| PassThru | switch | False |  |  |
| Ref | XenRef[VDI] | True |  |  |
| SessionOpaqueRef | string | False |  |  |
| SmConfig | KeyValuePair[string,string] | False |  |  |
| Tags | string | False |  |  |
| Uuid | guid | True |  |  |
| VDI | VDI | True |  |  |
| WhatIf | switch | False |  |  |
| XenstoreData | KeyValuePair[string,string] | False |  |  |
### Procedure
None

### Inputs
```
XenAPI.VDI
XenAPI.XenRef`1[[XenAPI.VDI, XenServer, Version=8.2.3.0, Culture=neutral, PublicKeyToken=d247b8b0ac7959e9]]
System.Guid
System.String

```
### Outputs
```
XenAPI.VDI
System.Void

```
### Links
None

### Examples

Add-XenVDI [-VDI] <VDI> [-PassThru] [-OtherConfig <KeyValuePair[string,string]>] [-XenstoreData <KeyValuePair[string,string]>] [-SmConfig <KeyValuePair[string,string]>] [-Tags <string>] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [<CommonParameters>]

Add-XenVDI [-Ref] <XenRef[VDI]> [-PassThru] [-OtherConfig <KeyValuePair[string,string]>] [-XenstoreData <KeyValuePair[string,string]>] [-SmConfig <KeyValuePair[string,string]>] [-Tags <string>] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [<CommonParameters>]

Add-XenVDI [-Uuid] <guid> [-PassThru] [-OtherConfig <KeyValuePair[string,string]>] [-XenstoreData <KeyValuePair[string,string]>] [-SmConfig <KeyValuePair[string,string]>] [-Tags <string>] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [<CommonParameters>]

Add-XenVDI [-Name] <string> [-PassThru] [-OtherConfig <KeyValuePair[string,string]>] [-XenstoreData <KeyValuePair[string,string]>] [-SmConfig <KeyValuePair[string,string]>] [-Tags <string>] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [<CommonParameters>]


## Add-XenVGPU

### Synopsis
None

### Description
None

### Syntax
```
Add-XenVGPU [-VGPU] <VGPU> [[-PassThru]] [[-OtherConfig] <KeyValuePair[string,string]>] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]] [-Ref] <XenRef[VGPU]> [[-PassThru]] [[-OtherConfig] <KeyValuePair[string,string]>] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]] [-Uuid] <guid> [[-PassThru]] [[-OtherConfig] <KeyValuePair[string,string]>] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]]
```
### Parameters
| Name | Type | Required | Default Value | Description |
| :--- | :--- | :------- | :------------ | :---------- |
| BestEffort | switch | False |  |  |
| Confirm | switch | False |  |  |
| OtherConfig | KeyValuePair[string,string] | False |  |  |
| PassThru | switch | False |  |  |
| Ref | XenRef[VGPU] | True |  |  |
| SessionOpaqueRef | string | False |  |  |
| Uuid | guid | True |  |  |
| VGPU | VGPU | True |  |  |
| WhatIf | switch | False |  |  |
### Procedure
None

### Inputs
```
XenAPI.VGPU
XenAPI.XenRef`1[[XenAPI.VGPU, XenServer, Version=8.2.3.0, Culture=neutral, PublicKeyToken=d247b8b0ac7959e9]]
System.Guid

```
### Outputs
```
XenAPI.VGPU
System.Void

```
### Links
None

### Examples

Add-XenVGPU [-VGPU] <VGPU> [-PassThru] [-OtherConfig <KeyValuePair[string,string]>] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [<CommonParameters>]

Add-XenVGPU [-Ref] <XenRef[VGPU]> [-PassThru] [-OtherConfig <KeyValuePair[string,string]>] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [<CommonParameters>]

Add-XenVGPU [-Uuid] <guid> [-PassThru] [-OtherConfig <KeyValuePair[string,string]>] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [<CommonParameters>]


## Add-XenVIF

### Synopsis
None

### Description
None

### Syntax
```
Add-XenVIF [-VIF] <VIF> [[-PassThru]] [[-OtherConfig] <KeyValuePair[string,string]>] [[-QosAlgorithmParams] <KeyValuePair[string,string]>] [[-Ipv4Allowed] <string>] [[-Ipv6Allowed] <string>] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]] [-Ref] <XenRef[VIF]> [[-PassThru]] [[-OtherConfig] <KeyValuePair[string,string]>] [[-QosAlgorithmParams] <KeyValuePair[string,string]>] [[-Ipv4Allowed] <string>] [[-Ipv6Allowed] <string>] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]] [-Uuid] <guid> [[-PassThru]] [[-OtherConfig] <KeyValuePair[string,string]>] [[-QosAlgorithmParams] <KeyValuePair[string,string]>] [[-Ipv4Allowed] <string>] [[-Ipv6Allowed] <string>] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]]
```
### Parameters
| Name | Type | Required | Default Value | Description |
| :--- | :--- | :------- | :------------ | :---------- |
| BestEffort | switch | False |  |  |
| Confirm | switch | False |  |  |
| Ipv4Allowed | string | False |  |  |
| Ipv6Allowed | string | False |  |  |
| OtherConfig | KeyValuePair[string,string] | False |  |  |
| PassThru | switch | False |  |  |
| QosAlgorithmParams | KeyValuePair[string,string] | False |  |  |
| Ref | XenRef[VIF] | True |  |  |
| SessionOpaqueRef | string | False |  |  |
| Uuid | guid | True |  |  |
| VIF | VIF | True |  |  |
| WhatIf | switch | False |  |  |
### Procedure
None

### Inputs
```
XenAPI.VIF
XenAPI.XenRef`1[[XenAPI.VIF, XenServer, Version=8.2.3.0, Culture=neutral, PublicKeyToken=d247b8b0ac7959e9]]
System.Guid

```
### Outputs
```
XenAPI.VIF
XenAPI.Task
System.Void

```
### Links
None

### Examples

Add-XenVIF [-VIF] <VIF> [-PassThru] [-OtherConfig <KeyValuePair[string,string]>] [-QosAlgorithmParams <KeyValuePair[string,string]>] [-Ipv4Allowed <string>] [-Ipv6Allowed <string>] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [<CommonParameters>]

Add-XenVIF [-Ref] <XenRef[VIF]> [-PassThru] [-OtherConfig <KeyValuePair[string,string]>] [-QosAlgorithmParams <KeyValuePair[string,string]>] [-Ipv4Allowed <string>] [-Ipv6Allowed <string>] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [<CommonParameters>]

Add-XenVIF [-Uuid] <guid> [-PassThru] [-OtherConfig <KeyValuePair[string,string]>] [-QosAlgorithmParams <KeyValuePair[string,string]>] [-Ipv4Allowed <string>] [-Ipv6Allowed <string>] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [<CommonParameters>]


## Add-XenVIFMetrics

### Synopsis
None

### Description
None

### Syntax
```
Add-XenVIFMetrics [-VIFMetrics] <VIF_metrics> [[-PassThru]] [[-OtherConfig] <KeyValuePair[string,string]>] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]] [-Ref] <XenRef[VIF_metrics]> [[-PassThru]] [[-OtherConfig] <KeyValuePair[string,string]>] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]] [-Uuid] <guid> [[-PassThru]] [[-OtherConfig] <KeyValuePair[string,string]>] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]]
```
### Parameters
| Name | Type | Required | Default Value | Description |
| :--- | :--- | :------- | :------------ | :---------- |
| BestEffort | switch | False |  |  |
| Confirm | switch | False |  |  |
| OtherConfig | KeyValuePair[string,string] | False |  |  |
| PassThru | switch | False |  |  |
| Ref | XenRef[VIF_metrics] | True |  |  |
| SessionOpaqueRef | string | False |  |  |
| Uuid | guid | True |  |  |
| VIFMetrics | VIF_metrics | True |  |  |
| WhatIf | switch | False |  |  |
### Procedure
None

### Inputs
```
XenAPI.VIF_metrics
XenAPI.XenRef`1[[XenAPI.VIF_metrics, XenServer, Version=8.2.3.0, Culture=neutral, PublicKeyToken=d247b8b0ac7959e9]]
System.Guid

```
### Outputs
```
XenAPI.VIF_metrics
System.Void

```
### Links
None

### Examples

Add-XenVIFMetrics [-VIFMetrics] <VIF_metrics> [-PassThru] [-OtherConfig <KeyValuePair[string,string]>] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [<CommonParameters>]

Add-XenVIFMetrics [-Ref] <XenRef[VIF_metrics]> [-PassThru] [-OtherConfig <KeyValuePair[string,string]>] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [<CommonParameters>]

Add-XenVIFMetrics [-Uuid] <guid> [-PassThru] [-OtherConfig <KeyValuePair[string,string]>] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [<CommonParameters>]


## Add-XenVLAN

### Synopsis
None

### Description
None

### Syntax
```
Add-XenVLAN [-VLAN] <VLAN> [[-PassThru]] [[-OtherConfig] <KeyValuePair[string,string]>] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]] [-Ref] <XenRef[VLAN]> [[-PassThru]] [[-OtherConfig] <KeyValuePair[string,string]>] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]] [-Uuid] <guid> [[-PassThru]] [[-OtherConfig] <KeyValuePair[string,string]>] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]]
```
### Parameters
| Name | Type | Required | Default Value | Description |
| :--- | :--- | :------- | :------------ | :---------- |
| BestEffort | switch | False |  |  |
| Confirm | switch | False |  |  |
| OtherConfig | KeyValuePair[string,string] | False |  |  |
| PassThru | switch | False |  |  |
| Ref | XenRef[VLAN] | True |  |  |
| SessionOpaqueRef | string | False |  |  |
| Uuid | guid | True |  |  |
| VLAN | VLAN | True |  |  |
| WhatIf | switch | False |  |  |
### Procedure
None

### Inputs
```
XenAPI.VLAN
XenAPI.XenRef`1[[XenAPI.VLAN, XenServer, Version=8.2.3.0, Culture=neutral, PublicKeyToken=d247b8b0ac7959e9]]
System.Guid

```
### Outputs
```
XenAPI.VLAN
System.Void

```
### Links
None

### Examples

Add-XenVLAN [-VLAN] <VLAN> [-PassThru] [-OtherConfig <KeyValuePair[string,string]>] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [<CommonParameters>]

Add-XenVLAN [-Ref] <XenRef[VLAN]> [-PassThru] [-OtherConfig <KeyValuePair[string,string]>] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [<CommonParameters>]

Add-XenVLAN [-Uuid] <guid> [-PassThru] [-OtherConfig <KeyValuePair[string,string]>] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [<CommonParameters>]


## Add-XenVM

### Synopsis
None

### Description
None

### Syntax
```
Add-XenVM [-VM] <VM> [[-PassThru]] [[-VCPUsParams] <KeyValuePair[string,string]>] [[-HVMBootParams] <KeyValuePair[string,string]>] [[-Platform] <KeyValuePair[string,string]>] [[-OtherConfig] <KeyValuePair[string,string]>] [[-XenstoreData] <KeyValuePair[string,string]>] [[-Tags] <string>] [[-BlockedOperations] <KeyValuePair[vm_operations,string]>] [[-VCPUsParamsLive] <KeyValuePair[string,string]>] [[-NVRAM] <KeyValuePair[string,string]>] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]] [-Ref] <XenRef[VM]> [[-PassThru]] [[-VCPUsParams] <KeyValuePair[string,string]>] [[-HVMBootParams] <KeyValuePair[string,string]>] [[-Platform] <KeyValuePair[string,string]>] [[-OtherConfig] <KeyValuePair[string,string]>] [[-XenstoreData] <KeyValuePair[string,string]>] [[-Tags] <string>] [[-BlockedOperations] <KeyValuePair[vm_operations,string]>] [[-VCPUsParamsLive] <KeyValuePair[string,string]>] [[-NVRAM] <KeyValuePair[string,string]>] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]] [-Uuid] <guid> [[-PassThru]] [[-VCPUsParams] <KeyValuePair[string,string]>] [[-HVMBootParams] <KeyValuePair[string,string]>] [[-Platform] <KeyValuePair[string,string]>] [[-OtherConfig] <KeyValuePair[string,string]>] [[-XenstoreData] <KeyValuePair[string,string]>] [[-Tags] <string>] [[-BlockedOperations] <KeyValuePair[vm_operations,string]>] [[-VCPUsParamsLive] <KeyValuePair[string,string]>] [[-NVRAM] <KeyValuePair[string,string]>] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]] [-Name] <string> [[-PassThru]] [[-VCPUsParams] <KeyValuePair[string,string]>] [[-HVMBootParams] <KeyValuePair[string,string]>] [[-Platform] <KeyValuePair[string,string]>] [[-OtherConfig] <KeyValuePair[string,string]>] [[-XenstoreData] <KeyValuePair[string,string]>] [[-Tags] <string>] [[-BlockedOperations] <KeyValuePair[vm_operations,string]>] [[-VCPUsParamsLive] <KeyValuePair[string,string]>] [[-NVRAM] <KeyValuePair[string,string]>] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]]
```
### Parameters
| Name | Type | Required | Default Value | Description |
| :--- | :--- | :------- | :------------ | :---------- |
| BestEffort | switch | False |  |  |
| BlockedOperations | KeyValuePair[vm_operations,string] | False |  |  |
| Confirm | switch | False |  |  |
| HVMBootParams | KeyValuePair[string,string] | False |  |  |
| NVRAM | KeyValuePair[string,string] | False |  |  |
| Name | string | True |  |  |
| OtherConfig | KeyValuePair[string,string] | False |  |  |
| PassThru | switch | False |  |  |
| Platform | KeyValuePair[string,string] | False |  |  |
| Ref | XenRef[VM] | True |  |  |
| SessionOpaqueRef | string | False |  |  |
| Tags | string | False |  |  |
| Uuid | guid | True |  |  |
| VCPUsParams | KeyValuePair[string,string] | False |  |  |
| VCPUsParamsLive | KeyValuePair[string,string] | False |  |  |
| VM | VM | True |  |  |
| WhatIf | switch | False |  |  |
| XenstoreData | KeyValuePair[string,string] | False |  |  |
### Procedure
None

### Inputs
```
XenAPI.VM
XenAPI.XenRef`1[[XenAPI.VM, XenServer, Version=8.2.3.0, Culture=neutral, PublicKeyToken=d247b8b0ac7959e9]]
System.Guid
System.String

```
### Outputs
```
XenAPI.VM
XenAPI.Task
System.Void

```
### Links
None

### Examples

Add-XenVM [-VM] <VM> [-PassThru] [-VCPUsParams <KeyValuePair[string,string]>] [-HVMBootParams <KeyValuePair[string,string]>] [-Platform <KeyValuePair[string,string]>] [-OtherConfig <KeyValuePair[string,string]>] [-XenstoreData <KeyValuePair[string,string]>] [-Tags <string>] [-BlockedOperations <KeyValuePair[vm_operations,string]>] [-VCPUsParamsLive <KeyValuePair[string,string]>] [-NVRAM <KeyValuePair[string,string]>] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [<CommonParameters>]

Add-XenVM [-Ref] <XenRef[VM]> [-PassThru] [-VCPUsParams <KeyValuePair[string,string]>] [-HVMBootParams <KeyValuePair[string,string]>] [-Platform <KeyValuePair[string,string]>] [-OtherConfig <KeyValuePair[string,string]>] [-XenstoreData <KeyValuePair[string,string]>] [-Tags <string>] [-BlockedOperations <KeyValuePair[vm_operations,string]>] [-VCPUsParamsLive <KeyValuePair[string,string]>] [-NVRAM <KeyValuePair[string,string]>] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [<CommonParameters>]

Add-XenVM [-Uuid] <guid> [-PassThru] [-VCPUsParams <KeyValuePair[string,string]>] [-HVMBootParams <KeyValuePair[string,string]>] [-Platform <KeyValuePair[string,string]>] [-OtherConfig <KeyValuePair[string,string]>] [-XenstoreData <KeyValuePair[string,string]>] [-Tags <string>] [-BlockedOperations <KeyValuePair[vm_operations,string]>] [-VCPUsParamsLive <KeyValuePair[string,string]>] [-NVRAM <KeyValuePair[string,string]>] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [<CommonParameters>]

Add-XenVM [-Name] <string> [-PassThru] [-VCPUsParams <KeyValuePair[string,string]>] [-HVMBootParams <KeyValuePair[string,string]>] [-Platform <KeyValuePair[string,string]>] [-OtherConfig <KeyValuePair[string,string]>] [-XenstoreData <KeyValuePair[string,string]>] [-Tags <string>] [-BlockedOperations <KeyValuePair[vm_operations,string]>] [-VCPUsParamsLive <KeyValuePair[string,string]>] [-NVRAM <KeyValuePair[string,string]>] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [<CommonParameters>]


## Add-XenVMGuestMetrics

### Synopsis
None

### Description
None

### Syntax
```
Add-XenVMGuestMetrics [-VMGuestMetrics] <VM_guest_metrics> [[-PassThru]] [[-OtherConfig] <KeyValuePair[string,string]>] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]] [-Ref] <XenRef[VM_guest_metrics]> [[-PassThru]] [[-OtherConfig] <KeyValuePair[string,string]>] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]] [-Uuid] <guid> [[-PassThru]] [[-OtherConfig] <KeyValuePair[string,string]>] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]]
```
### Parameters
| Name | Type | Required | Default Value | Description |
| :--- | :--- | :------- | :------------ | :---------- |
| BestEffort | switch | False |  |  |
| Confirm | switch | False |  |  |
| OtherConfig | KeyValuePair[string,string] | False |  |  |
| PassThru | switch | False |  |  |
| Ref | XenRef[VM_guest_metrics] | True |  |  |
| SessionOpaqueRef | string | False |  |  |
| Uuid | guid | True |  |  |
| VMGuestMetrics | VM_guest_metrics | True |  |  |
| WhatIf | switch | False |  |  |
### Procedure
None

### Inputs
```
XenAPI.VM_guest_metrics
XenAPI.XenRef`1[[XenAPI.VM_guest_metrics, XenServer, Version=8.2.3.0, Culture=neutral, PublicKeyToken=d247b8b0ac7959e9]]
System.Guid

```
### Outputs
```
XenAPI.VM_guest_metrics
System.Void

```
### Links
None

### Examples

Add-XenVMGuestMetrics [-VMGuestMetrics] <VM_guest_metrics> [-PassThru] [-OtherConfig <KeyValuePair[string,string]>] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [<CommonParameters>]

Add-XenVMGuestMetrics [-Ref] <XenRef[VM_guest_metrics]> [-PassThru] [-OtherConfig <KeyValuePair[string,string]>] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [<CommonParameters>]

Add-XenVMGuestMetrics [-Uuid] <guid> [-PassThru] [-OtherConfig <KeyValuePair[string,string]>] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [<CommonParameters>]


## Add-XenVMMetrics

### Synopsis
None

### Description
None

### Syntax
```
Add-XenVMMetrics [-VMMetrics] <VM_metrics> [[-PassThru]] [[-OtherConfig] <KeyValuePair[string,string]>] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]] [-Ref] <XenRef[VM_metrics]> [[-PassThru]] [[-OtherConfig] <KeyValuePair[string,string]>] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]] [-Uuid] <guid> [[-PassThru]] [[-OtherConfig] <KeyValuePair[string,string]>] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]]
```
### Parameters
| Name | Type | Required | Default Value | Description |
| :--- | :--- | :------- | :------------ | :---------- |
| BestEffort | switch | False |  |  |
| Confirm | switch | False |  |  |
| OtherConfig | KeyValuePair[string,string] | False |  |  |
| PassThru | switch | False |  |  |
| Ref | XenRef[VM_metrics] | True |  |  |
| SessionOpaqueRef | string | False |  |  |
| Uuid | guid | True |  |  |
| VMMetrics | VM_metrics | True |  |  |
| WhatIf | switch | False |  |  |
### Procedure
None

### Inputs
```
XenAPI.VM_metrics
XenAPI.XenRef`1[[XenAPI.VM_metrics, XenServer, Version=8.2.3.0, Culture=neutral, PublicKeyToken=d247b8b0ac7959e9]]
System.Guid

```
### Outputs
```
XenAPI.VM_metrics
System.Void

```
### Links
None

### Examples

Add-XenVMMetrics [-VMMetrics] <VM_metrics> [-PassThru] [-OtherConfig <KeyValuePair[string,string]>] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [<CommonParameters>]

Add-XenVMMetrics [-Ref] <XenRef[VM_metrics]> [-PassThru] [-OtherConfig <KeyValuePair[string,string]>] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [<CommonParameters>]

Add-XenVMMetrics [-Uuid] <guid> [-PassThru] [-OtherConfig <KeyValuePair[string,string]>] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [<CommonParameters>]


## Add-XenVMPP

### Synopsis
None

### Description
None

### Syntax
```
Add-XenVMPP [-VMPP] <VMPP> [[-PassThru]] [[-BackupSchedule] <KeyValuePair[string,string]>] [[-ArchiveTargetConfig] <KeyValuePair[string,string]>] [[-ArchiveSchedule] <KeyValuePair[string,string]>] [[-AlarmConfig] <KeyValuePair[string,string]>] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]] [-Ref] <XenRef[VMPP]> [[-PassThru]] [[-BackupSchedule] <KeyValuePair[string,string]>] [[-ArchiveTargetConfig] <KeyValuePair[string,string]>] [[-ArchiveSchedule] <KeyValuePair[string,string]>] [[-AlarmConfig] <KeyValuePair[string,string]>] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]] [-Uuid] <guid> [[-PassThru]] [[-BackupSchedule] <KeyValuePair[string,string]>] [[-ArchiveTargetConfig] <KeyValuePair[string,string]>] [[-ArchiveSchedule] <KeyValuePair[string,string]>] [[-AlarmConfig] <KeyValuePair[string,string]>] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]] [-Name] <string> [[-PassThru]] [[-BackupSchedule] <KeyValuePair[string,string]>] [[-ArchiveTargetConfig] <KeyValuePair[string,string]>] [[-ArchiveSchedule] <KeyValuePair[string,string]>] [[-AlarmConfig] <KeyValuePair[string,string]>] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]]
```
### Parameters
| Name | Type | Required | Default Value | Description |
| :--- | :--- | :------- | :------------ | :---------- |
| AlarmConfig | KeyValuePair[string,string] | False |  |  |
| ArchiveSchedule | KeyValuePair[string,string] | False |  |  |
| ArchiveTargetConfig | KeyValuePair[string,string] | False |  |  |
| BackupSchedule | KeyValuePair[string,string] | False |  |  |
| BestEffort | switch | False |  |  |
| Confirm | switch | False |  |  |
| Name | string | True |  |  |
| PassThru | switch | False |  |  |
| Ref | XenRef[VMPP] | True |  |  |
| SessionOpaqueRef | string | False |  |  |
| Uuid | guid | True |  |  |
| VMPP | VMPP | True |  |  |
| WhatIf | switch | False |  |  |
### Procedure
None

### Inputs
```
XenAPI.VMPP
XenAPI.XenRef`1[[XenAPI.VMPP, XenServer, Version=8.2.3.0, Culture=neutral, PublicKeyToken=d247b8b0ac7959e9]]
System.Guid
System.String

```
### Outputs
```
XenAPI.VMPP
System.Void

```
### Links
None

### Examples

Add-XenVMPP [-VMPP] <VMPP> [-PassThru] [-BackupSchedule <KeyValuePair[string,string]>] [-ArchiveTargetConfig <KeyValuePair[string,string]>] [-ArchiveSchedule <KeyValuePair[string,string]>] [-AlarmConfig <KeyValuePair[string,string]>] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [<CommonParameters>]

Add-XenVMPP [-Ref] <XenRef[VMPP]> [-PassThru] [-BackupSchedule <KeyValuePair[string,string]>] [-ArchiveTargetConfig <KeyValuePair[string,string]>] [-ArchiveSchedule <KeyValuePair[string,string]>] [-AlarmConfig <KeyValuePair[string,string]>] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [<CommonParameters>]

Add-XenVMPP [-Uuid] <guid> [-PassThru] [-BackupSchedule <KeyValuePair[string,string]>] [-ArchiveTargetConfig <KeyValuePair[string,string]>] [-ArchiveSchedule <KeyValuePair[string,string]>] [-AlarmConfig <KeyValuePair[string,string]>] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [<CommonParameters>]

Add-XenVMPP [-Name] <string> [-PassThru] [-BackupSchedule <KeyValuePair[string,string]>] [-ArchiveTargetConfig <KeyValuePair[string,string]>] [-ArchiveSchedule <KeyValuePair[string,string]>] [-AlarmConfig <KeyValuePair[string,string]>] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [<CommonParameters>]


## Add-XenVMSS

### Synopsis
None

### Description
None

### Syntax
```
Add-XenVMSS [-VMSS] <VMSS> [[-PassThru]] [[-Schedule] <KeyValuePair[string,string]>] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]] [-Ref] <XenRef[VMSS]> [[-PassThru]] [[-Schedule] <KeyValuePair[string,string]>] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]] [-Uuid] <guid> [[-PassThru]] [[-Schedule] <KeyValuePair[string,string]>] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]] [-Name] <string> [[-PassThru]] [[-Schedule] <KeyValuePair[string,string]>] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]]
```
### Parameters
| Name | Type | Required | Default Value | Description |
| :--- | :--- | :------- | :------------ | :---------- |
| BestEffort | switch | False |  |  |
| Confirm | switch | False |  |  |
| Name | string | True |  |  |
| PassThru | switch | False |  |  |
| Ref | XenRef[VMSS] | True |  |  |
| Schedule | KeyValuePair[string,string] | False |  |  |
| SessionOpaqueRef | string | False |  |  |
| Uuid | guid | True |  |  |
| VMSS | VMSS | True |  |  |
| WhatIf | switch | False |  |  |
### Procedure
None

### Inputs
```
XenAPI.VMSS
XenAPI.XenRef`1[[XenAPI.VMSS, XenServer, Version=8.2.3.0, Culture=neutral, PublicKeyToken=d247b8b0ac7959e9]]
System.Guid
System.String

```
### Outputs
```
XenAPI.VMSS
System.Void

```
### Links
None

### Examples

Add-XenVMSS [-VMSS] <VMSS> [-PassThru] [-Schedule <KeyValuePair[string,string]>] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [<CommonParameters>]

Add-XenVMSS [-Ref] <XenRef[VMSS]> [-PassThru] [-Schedule <KeyValuePair[string,string]>] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [<CommonParameters>]

Add-XenVMSS [-Uuid] <guid> [-PassThru] [-Schedule <KeyValuePair[string,string]>] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [<CommonParameters>]

Add-XenVMSS [-Name] <string> [-PassThru] [-Schedule <KeyValuePair[string,string]>] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [<CommonParameters>]


## Add-XenVUSB

### Synopsis
None

### Description
None

### Syntax
```
Add-XenVUSB [-VUSB] <VUSB> [[-PassThru]] [[-OtherConfig] <KeyValuePair[string,string]>] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]] [-Ref] <XenRef[VUSB]> [[-PassThru]] [[-OtherConfig] <KeyValuePair[string,string]>] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]] [-Uuid] <guid> [[-PassThru]] [[-OtherConfig] <KeyValuePair[string,string]>] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]]
```
### Parameters
| Name | Type | Required | Default Value | Description |
| :--- | :--- | :------- | :------------ | :---------- |
| BestEffort | switch | False |  |  |
| Confirm | switch | False |  |  |
| OtherConfig | KeyValuePair[string,string] | False |  |  |
| PassThru | switch | False |  |  |
| Ref | XenRef[VUSB] | True |  |  |
| SessionOpaqueRef | string | False |  |  |
| Uuid | guid | True |  |  |
| VUSB | VUSB | True |  |  |
| WhatIf | switch | False |  |  |
### Procedure
None

### Inputs
```
XenAPI.VUSB
XenAPI.XenRef`1[[XenAPI.VUSB, XenServer, Version=8.2.3.0, Culture=neutral, PublicKeyToken=d247b8b0ac7959e9]]
System.Guid

```
### Outputs
```
XenAPI.VUSB
System.Void

```
### Links
None

### Examples

Add-XenVUSB [-VUSB] <VUSB> [-PassThru] [-OtherConfig <KeyValuePair[string,string]>] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [<CommonParameters>]

Add-XenVUSB [-Ref] <XenRef[VUSB]> [-PassThru] [-OtherConfig <KeyValuePair[string,string]>] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [<CommonParameters>]

Add-XenVUSB [-Uuid] <guid> [-PassThru] [-OtherConfig <KeyValuePair[string,string]>] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [<CommonParameters>]


## Connect-XenServer

### Synopsis
None

### Description
None

### Syntax
```
Connect-XenServer [-Url] <string[]> [[-UserName] <string>] [[-Password] <string>] [[-Creds] <pscredential>] [[-OpaqueRef] <string[]>] [[-Originator] <string>] [[-PassThru]] [[-NoWarnNewCertificates]] [[-NoWarnCertificates]] [[-SetDefaultSession]] [[-Force]] [-Server] <string[]> [[-UserName] <string>] [[-Password] <string>] [[-Port] <int>] [[-Creds] <pscredential>] [[-OpaqueRef] <string[]>] [[-Originator] <string>] [[-PassThru]] [[-NoWarnNewCertificates]] [[-NoWarnCertificates]] [[-SetDefaultSession]] [[-Force]]
```
### Parameters
| Name | Type | Required | Default Value | Description |
| :--- | :--- | :------- | :------------ | :---------- |
| Creds | pscredential | False |  |  |
| Force | switch | False |  |  |
| NoWarnCertificates | switch | False |  |  |
| NoWarnNewCertificates | switch | False |  |  |
| OpaqueRef | string[] | False |  |  |
| Originator | string | False |  |  |
| PassThru | switch | False |  |  |
| Password | string | False |  |  |
| Port | int | False |  |  |
| Server | string[] | True |  |  |
| SetDefaultSession | switch | False |  |  |
| Url | string[] | True |  |  |
| UserName | string | False |  |  |
### Procedure
None

### Inputs
```
System.Management.Automation.PSCredential

```
### Outputs
```
System.Object
```
### Links
None

### Examples

Connect-XenServer [-Url] <string[]> [[-UserName] <string>] [[-Password] <string>] [-Creds <pscredential>] [-OpaqueRef <string[]>] [-Originator <string>] [-PassThru] [-NoWarnNewCertificates] [-NoWarnCertificates] [-SetDefaultSession] [-Force] [<CommonParameters>]

Connect-XenServer [-Server] <string[]> [[-UserName] <string>] [[-Password] <string>] [-Port <int>] [-Creds <pscredential>] [-OpaqueRef <string[]>] [-Originator <string>] [-PassThru] [-NoWarnNewCertificates] [-NoWarnCertificates] [-SetDefaultSession] [-Force] [<CommonParameters>]


## ConvertTo-XenRef

### Synopsis
None

### Description
None

### Syntax
```
ConvertTo-XenRef [-XenObject] <IXenObject>
```
### Parameters
| Name | Type | Required | Default Value | Description |
| :--- | :--- | :------- | :------------ | :---------- |
| XenObject | IXenObject | True |  |  |
### Procedure
None

### Inputs
```
XenAPI.IXenObject

```
### Outputs
```
XenAPI.IXenObject

```
### Links
None

### Examples

ConvertTo-XenRef [-XenObject] <IXenObject> [<CommonParameters>]


## Disconnect-XenServer

### Synopsis
None

### Description
None

### Syntax
```
Disconnect-XenServer [[-Session] <Session>] [[-Ref] <XenRef[Session]>]
```
### Parameters
| Name | Type | Required | Default Value | Description |
| :--- | :--- | :------- | :------------ | :---------- |
| Ref | XenRef[Session] | False |  |  |
| Session | Session | False |  |  |
### Procedure
None

### Inputs
```
XenAPI.Session
XenAPI.XenRef`1[[XenAPI.Session, XenServer, Version=8.2.3.0, Culture=neutral, PublicKeyToken=d247b8b0ac7959e9]]

```
### Outputs
```
System.Object
```
### Links
None

### Examples

Disconnect-XenServer [[-Session] <Session>] [<CommonParameters>]

Disconnect-XenServer [[-Ref] <XenRef[Session]>] [<CommonParameters>]


## Export-XenMetadata

### Synopsis
None

### Description
None

### Syntax
```
Export-XenMetadata [-XenHost] <string> [-Path] <string> [[-DataCopiedDelegate] <HTTP+DataCopiedDelegate>] [[-Uuid] <string>] [[-CancellingDelegate] <HTTP+FuncBool>] [[-TimeoutMs] <int>] [[-Proxy] <IWebProxy>] [[-TaskRef] <string>] [[-BestEffort]] [[-SessionOpaqueRef] <string>]
```
### Parameters
| Name | Type | Required | Default Value | Description |
| :--- | :--- | :------- | :------------ | :---------- |
| BestEffort | switch | False |  |  |
| CancellingDelegate | HTTP+FuncBool | False |  |  |
| DataCopiedDelegate | HTTP+DataCopiedDelegate | False |  |  |
| Path | string | True |  |  |
| Proxy | IWebProxy | False |  |  |
| SessionOpaqueRef | string | False |  |  |
| TaskRef | string | False |  |  |
| TimeoutMs | int | False |  |  |
| Uuid | string | False |  |  |
| XenHost | string | True |  |  |
### Procedure
None

### Inputs
```
System.String

```
### Outputs
```
System.Void

```
### Links
None

### Examples

Export-XenMetadata -XenHost <string> -Path <string> [-DataCopiedDelegate <HTTP+DataCopiedDelegate>] [-Uuid <string>] [-CancellingDelegate <HTTP+FuncBool>] [-TimeoutMs <int>] [-Proxy <IWebProxy>] [-TaskRef <string>] [-BestEffort] [-SessionOpaqueRef <string>] [<CommonParameters>]


## Export-XenRawVdi

### Synopsis
None

### Description
None

### Syntax
```
Export-XenRawVdi [-XenHost] <string> [-Path] <string> [[-DataCopiedDelegate] <HTTP+DataCopiedDelegate>] [[-Vdi] <string>] [[-CancellingDelegate] <HTTP+FuncBool>] [[-TimeoutMs] <int>] [[-Proxy] <IWebProxy>] [[-TaskRef] <string>] [[-BestEffort]] [[-SessionOpaqueRef] <string>]
```
### Parameters
| Name | Type | Required | Default Value | Description |
| :--- | :--- | :------- | :------------ | :---------- |
| BestEffort | switch | False |  |  |
| CancellingDelegate | HTTP+FuncBool | False |  |  |
| DataCopiedDelegate | HTTP+DataCopiedDelegate | False |  |  |
| Path | string | True |  |  |
| Proxy | IWebProxy | False |  |  |
| SessionOpaqueRef | string | False |  |  |
| TaskRef | string | False |  |  |
| TimeoutMs | int | False |  |  |
| Vdi | string | False |  |  |
| XenHost | string | True |  |  |
### Procedure
None

### Inputs
```
None

```
### Outputs
```
System.Void

```
### Links
None

### Examples

Export-XenRawVdi -XenHost <string> -Path <string> [-DataCopiedDelegate <HTTP+DataCopiedDelegate>] [-Vdi <string>] [-CancellingDelegate <HTTP+FuncBool>] [-TimeoutMs <int>] [-Proxy <IWebProxy>] [-TaskRef <string>] [-BestEffort] [-SessionOpaqueRef <string>] [<CommonParameters>]


## Export-XenVm

### Synopsis
None

### Description
None

### Syntax
```
Export-XenVm [-XenHost] <string> [-Path] <string> [[-DataCopiedDelegate] <HTTP+DataCopiedDelegate>] [[-Uuid] <string>] [[-CancellingDelegate] <HTTP+FuncBool>] [[-TimeoutMs] <int>] [[-Proxy] <IWebProxy>] [[-TaskRef] <string>] [[-BestEffort]] [[-SessionOpaqueRef] <string>]
```
### Parameters
| Name | Type | Required | Default Value | Description |
| :--- | :--- | :------- | :------------ | :---------- |
| BestEffort | switch | False |  |  |
| CancellingDelegate | HTTP+FuncBool | False |  |  |
| DataCopiedDelegate | HTTP+DataCopiedDelegate | False |  |  |
| Path | string | True |  |  |
| Proxy | IWebProxy | False |  |  |
| SessionOpaqueRef | string | False |  |  |
| TaskRef | string | False |  |  |
| TimeoutMs | int | False |  |  |
| Uuid | string | False |  |  |
| XenHost | string | True |  |  |
### Procedure
None

### Inputs
```
System.String

```
### Outputs
```
System.Void

```
### Links
None

### Examples

Export-XenVm -XenHost <string> -Path <string> [-DataCopiedDelegate <HTTP+DataCopiedDelegate>] [-Uuid <string>] [-CancellingDelegate <HTTP+FuncBool>] [-TimeoutMs <int>] [-Proxy <IWebProxy>] [-TaskRef <string>] [-BestEffort] [-SessionOpaqueRef <string>] [<CommonParameters>]


## Get-XenAuthProperty

### Synopsis
None

### Description
None

### Syntax
```
Get-XenAuthProperty [-Auth] <Auth> [-XenProperty] <XenAuthProperty> [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-SubjectName] <string>] [-Ref] <XenRef[Auth]> [-XenProperty] <XenAuthProperty> [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-SubjectName] <string>]
```
### Parameters
| Name | Type | Required | Default Value | Description |
| :--- | :--- | :------- | :------------ | :---------- |
| Auth | Auth | True |  |  |
| BestEffort | switch | False |  |  |
| Ref | XenRef[Auth] | True |  |  |
| SessionOpaqueRef | string | False |  |  |
| SubjectName | string | False |  |  |
| XenProperty | XenAuthProperty | True |  |  |
### Procedure
None

### Inputs
```
XenAPI.Auth
XenAPI.XenRef`1[[XenAPI.Auth, XenServer, Version=8.2.3.0, Culture=neutral, PublicKeyToken=d247b8b0ac7959e9]]

```
### Outputs
```
System.Object
```
### Links
None

### Examples

Get-XenAuthProperty [-Auth] <Auth> -XenProperty <XenAuthProperty> [-BestEffort] [-SessionOpaqueRef <string>] [-SubjectName <string>] [<CommonParameters>]

Get-XenAuthProperty [-Ref] <XenRef[Auth]> -XenProperty <XenAuthProperty> [-BestEffort] [-SessionOpaqueRef <string>] [-SubjectName <string>] [<CommonParameters>]


## Get-XenBond

### Synopsis
None

### Description
None

### Syntax
```
Get-XenBond [[-Ref] <XenRef[Bond]>] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [-Uuid] <guid> [[-BestEffort]] [[-SessionOpaqueRef] <string>]
```
### Parameters
| Name | Type | Required | Default Value | Description |
| :--- | :--- | :------- | :------------ | :---------- |
| BestEffort | switch | False |  |  |
| Ref | XenRef[Bond] | False |  |  |
| SessionOpaqueRef | string | False |  |  |
| Uuid | guid | True |  |  |
### Procedure
None

### Inputs
```
XenAPI.XenRef`1[[XenAPI.Bond, XenServer, Version=8.2.3.0, Culture=neutral, PublicKeyToken=d247b8b0ac7959e9]]
System.Guid

```
### Outputs
```
XenAPI.Bond[]

```
### Links
None

### Examples

Get-XenBond [[-Ref] <XenRef[Bond]>] [-BestEffort] [-SessionOpaqueRef <string>] [<CommonParameters>]

Get-XenBond [-Uuid] <guid> [-BestEffort] [-SessionOpaqueRef <string>] [<CommonParameters>]


## Get-XenBondProperty

### Synopsis
None

### Description
None

### Syntax
```
Get-XenBondProperty [-Bond] <Bond> [-XenProperty] <XenBondProperty> [[-BestEffort]] [[-SessionOpaqueRef] <string>] [-Ref] <XenRef[Bond]> [-XenProperty] <XenBondProperty> [[-BestEffort]] [[-SessionOpaqueRef] <string>]
```
### Parameters
| Name | Type | Required | Default Value | Description |
| :--- | :--- | :------- | :------------ | :---------- |
| BestEffort | switch | False |  |  |
| Bond | Bond | True |  |  |
| Ref | XenRef[Bond] | True |  |  |
| SessionOpaqueRef | string | False |  |  |
| XenProperty | XenBondProperty | True |  |  |
### Procedure
None

### Inputs
```
XenAPI.Bond
XenAPI.XenRef`1[[XenAPI.Bond, XenServer, Version=8.2.3.0, Culture=neutral, PublicKeyToken=d247b8b0ac7959e9]]

```
### Outputs
```
System.Object
```
### Links
None

### Examples

Get-XenBondProperty [-Bond] <Bond> -XenProperty <XenBondProperty> [-BestEffort] [-SessionOpaqueRef <string>] [<CommonParameters>]

Get-XenBondProperty [-Ref] <XenRef[Bond]> -XenProperty <XenBondProperty> [-BestEffort] [-SessionOpaqueRef <string>] [<CommonParameters>]


## Get-XenCertificate

### Synopsis
None

### Description
None

### Syntax
```
Get-XenCertificate [[-Ref] <XenRef[Certificate]>] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [-Uuid] <guid> [[-BestEffort]] [[-SessionOpaqueRef] <string>]
```
### Parameters
| Name | Type | Required | Default Value | Description |
| :--- | :--- | :------- | :------------ | :---------- |
| BestEffort | switch | False |  |  |
| Ref | XenRef[Certificate] | False |  |  |
| SessionOpaqueRef | string | False |  |  |
| Uuid | guid | True |  |  |
### Procedure
None

### Inputs
```
XenAPI.XenRef`1[[XenAPI.Certificate, XenServer, Version=8.2.3.0, Culture=neutral, PublicKeyToken=d247b8b0ac7959e9]]
System.Guid

```
### Outputs
```
XenAPI.Certificate[]

```
### Links
None

### Examples

Get-XenCertificate [[-Ref] <XenRef[Certificate]>] [-BestEffort] [-SessionOpaqueRef <string>] [<CommonParameters>]

Get-XenCertificate [-Uuid] <guid> [-BestEffort] [-SessionOpaqueRef <string>] [<CommonParameters>]


## Get-XenCertificateProperty

### Synopsis
None

### Description
None

### Syntax
```
Get-XenCertificateProperty [-Certificate] <Certificate> [-XenProperty] <XenCertificateProperty> [[-BestEffort]] [[-SessionOpaqueRef] <string>] [-Ref] <XenRef[Certificate]> [-XenProperty] <XenCertificateProperty> [[-BestEffort]] [[-SessionOpaqueRef] <string>]
```
### Parameters
| Name | Type | Required | Default Value | Description |
| :--- | :--- | :------- | :------------ | :---------- |
| BestEffort | switch | False |  |  |
| Certificate | Certificate | True |  |  |
| Ref | XenRef[Certificate] | True |  |  |
| SessionOpaqueRef | string | False |  |  |
| XenProperty | XenCertificateProperty | True |  |  |
### Procedure
None

### Inputs
```
XenAPI.Certificate
XenAPI.XenRef`1[[XenAPI.Certificate, XenServer, Version=8.2.3.0, Culture=neutral, PublicKeyToken=d247b8b0ac7959e9]]

```
### Outputs
```
System.Object
```
### Links
None

### Examples

Get-XenCertificateProperty [-Certificate] <Certificate> -XenProperty <XenCertificateProperty> [-BestEffort] [-SessionOpaqueRef <string>] [<CommonParameters>]

Get-XenCertificateProperty [-Ref] <XenRef[Certificate]> -XenProperty <XenCertificateProperty> [-BestEffort] [-SessionOpaqueRef <string>] [<CommonParameters>]


## Get-XenCluster

### Synopsis
None

### Description
None

### Syntax
```
Get-XenCluster [[-Ref] <XenRef[Cluster]>] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [-Uuid] <guid> [[-BestEffort]] [[-SessionOpaqueRef] <string>]
```
### Parameters
| Name | Type | Required | Default Value | Description |
| :--- | :--- | :------- | :------------ | :---------- |
| BestEffort | switch | False |  |  |
| Ref | XenRef[Cluster] | False |  |  |
| SessionOpaqueRef | string | False |  |  |
| Uuid | guid | True |  |  |
### Procedure
None

### Inputs
```
XenAPI.XenRef`1[[XenAPI.Cluster, XenServer, Version=8.2.3.0, Culture=neutral, PublicKeyToken=d247b8b0ac7959e9]]
System.Guid

```
### Outputs
```
XenAPI.Cluster[]

```
### Links
None

### Examples

Get-XenCluster [[-Ref] <XenRef[Cluster]>] [-BestEffort] [-SessionOpaqueRef <string>] [<CommonParameters>]

Get-XenCluster [-Uuid] <guid> [-BestEffort] [-SessionOpaqueRef <string>] [<CommonParameters>]


## Get-XenClusterHost

### Synopsis
None

### Description
None

### Syntax
```
Get-XenClusterHost [[-Ref] <XenRef[Cluster_host]>] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [-Uuid] <guid> [[-BestEffort]] [[-SessionOpaqueRef] <string>]
```
### Parameters
| Name | Type | Required | Default Value | Description |
| :--- | :--- | :------- | :------------ | :---------- |
| BestEffort | switch | False |  |  |
| Ref | XenRef[Cluster_host] | False |  |  |
| SessionOpaqueRef | string | False |  |  |
| Uuid | guid | True |  |  |
### Procedure
None

### Inputs
```
XenAPI.XenRef`1[[XenAPI.Cluster_host, XenServer, Version=8.2.3.0, Culture=neutral, PublicKeyToken=d247b8b0ac7959e9]]
System.Guid

```
### Outputs
```
XenAPI.Cluster_host[]

```
### Links
None

### Examples

Get-XenClusterHost [[-Ref] <XenRef[Cluster_host]>] [-BestEffort] [-SessionOpaqueRef <string>] [<CommonParameters>]

Get-XenClusterHost [-Uuid] <guid> [-BestEffort] [-SessionOpaqueRef <string>] [<CommonParameters>]


## Get-XenClusterHostProperty

### Synopsis
None

### Description
None

### Syntax
```
Get-XenClusterHostProperty [-ClusterHost] <Cluster_host> [-XenProperty] <XenClusterHostProperty> [[-BestEffort]] [[-SessionOpaqueRef] <string>] [-Ref] <XenRef[Cluster_host]> [-XenProperty] <XenClusterHostProperty> [[-BestEffort]] [[-SessionOpaqueRef] <string>]
```
### Parameters
| Name | Type | Required | Default Value | Description |
| :--- | :--- | :------- | :------------ | :---------- |
| BestEffort | switch | False |  |  |
| ClusterHost | Cluster_host | True |  |  |
| Ref | XenRef[Cluster_host] | True |  |  |
| SessionOpaqueRef | string | False |  |  |
| XenProperty | XenClusterHostProperty | True |  |  |
### Procedure
None

### Inputs
```
XenAPI.Cluster_host
XenAPI.XenRef`1[[XenAPI.Cluster_host, XenServer, Version=8.2.3.0, Culture=neutral, PublicKeyToken=d247b8b0ac7959e9]]

```
### Outputs
```
System.Object
```
### Links
None

### Examples

Get-XenClusterHostProperty [-ClusterHost] <Cluster_host> -XenProperty <XenClusterHostProperty> [-BestEffort] [-SessionOpaqueRef <string>] [<CommonParameters>]

Get-XenClusterHostProperty [-Ref] <XenRef[Cluster_host]> -XenProperty <XenClusterHostProperty> [-BestEffort] [-SessionOpaqueRef <string>] [<CommonParameters>]


## Get-XenClusterProperty

### Synopsis
None

### Description
None

### Syntax
```
Get-XenClusterProperty [-Cluster] <Cluster> [-XenProperty] <XenClusterProperty> [[-BestEffort]] [[-SessionOpaqueRef] <string>] [-Ref] <XenRef[Cluster]> [-XenProperty] <XenClusterProperty> [[-BestEffort]] [[-SessionOpaqueRef] <string>]
```
### Parameters
| Name | Type | Required | Default Value | Description |
| :--- | :--- | :------- | :------------ | :---------- |
| BestEffort | switch | False |  |  |
| Cluster | Cluster | True |  |  |
| Ref | XenRef[Cluster] | True |  |  |
| SessionOpaqueRef | string | False |  |  |
| XenProperty | XenClusterProperty | True |  |  |
### Procedure
None

### Inputs
```
XenAPI.Cluster
XenAPI.XenRef`1[[XenAPI.Cluster, XenServer, Version=8.2.3.0, Culture=neutral, PublicKeyToken=d247b8b0ac7959e9]]

```
### Outputs
```
System.Object
```
### Links
None

### Examples

Get-XenClusterProperty [-Cluster] <Cluster> -XenProperty <XenClusterProperty> [-BestEffort] [-SessionOpaqueRef <string>] [<CommonParameters>]

Get-XenClusterProperty [-Ref] <XenRef[Cluster]> -XenProperty <XenClusterProperty> [-BestEffort] [-SessionOpaqueRef <string>] [<CommonParameters>]


## Get-XenConsole

### Synopsis
None

### Description
None

### Syntax
```
Get-XenConsole [[-Ref] <XenRef[Console]>] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [-Uuid] <guid> [[-BestEffort]] [[-SessionOpaqueRef] <string>]
```
### Parameters
| Name | Type | Required | Default Value | Description |
| :--- | :--- | :------- | :------------ | :---------- |
| BestEffort | switch | False |  |  |
| Ref | XenRef[Console] | False |  |  |
| SessionOpaqueRef | string | False |  |  |
| Uuid | guid | True |  |  |
### Procedure
None

### Inputs
```
XenAPI.XenRef`1[[XenAPI.Console, XenServer, Version=8.2.3.0, Culture=neutral, PublicKeyToken=d247b8b0ac7959e9]]
System.Guid

```
### Outputs
```
XenAPI.Console[]

```
### Links
None

### Examples

Get-XenConsole [[-Ref] <XenRef[Console]>] [-BestEffort] [-SessionOpaqueRef <string>] [<CommonParameters>]

Get-XenConsole [-Uuid] <guid> [-BestEffort] [-SessionOpaqueRef <string>] [<CommonParameters>]


## Get-XenConsoleProperty

### Synopsis
None

### Description
None

### Syntax
```
Get-XenConsoleProperty [-Console] <Console> [-XenProperty] <XenConsoleProperty> [[-BestEffort]] [[-SessionOpaqueRef] <string>] [-Ref] <XenRef[Console]> [-XenProperty] <XenConsoleProperty> [[-BestEffort]] [[-SessionOpaqueRef] <string>]
```
### Parameters
| Name | Type | Required | Default Value | Description |
| :--- | :--- | :------- | :------------ | :---------- |
| BestEffort | switch | False |  |  |
| Console | Console | True |  |  |
| Ref | XenRef[Console] | True |  |  |
| SessionOpaqueRef | string | False |  |  |
| XenProperty | XenConsoleProperty | True |  |  |
### Procedure
None

### Inputs
```
XenAPI.Console
XenAPI.XenRef`1[[XenAPI.Console, XenServer, Version=8.2.3.0, Culture=neutral, PublicKeyToken=d247b8b0ac7959e9]]

```
### Outputs
```
System.Object
```
### Links
None

### Examples

Get-XenConsoleProperty [-Console] <Console> -XenProperty <XenConsoleProperty> [-BestEffort] [-SessionOpaqueRef <string>] [<CommonParameters>]

Get-XenConsoleProperty [-Ref] <XenRef[Console]> -XenProperty <XenConsoleProperty> [-BestEffort] [-SessionOpaqueRef <string>] [<CommonParameters>]


## Get-XenCrashdump

### Synopsis
None

### Description
None

### Syntax
```
Get-XenCrashdump [[-Ref] <XenRef[Crashdump]>] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [-Uuid] <guid> [[-BestEffort]] [[-SessionOpaqueRef] <string>]
```
### Parameters
| Name | Type | Required | Default Value | Description |
| :--- | :--- | :------- | :------------ | :---------- |
| BestEffort | switch | False |  |  |
| Ref | XenRef[Crashdump] | False |  |  |
| SessionOpaqueRef | string | False |  |  |
| Uuid | guid | True |  |  |
### Procedure
None

### Inputs
```
XenAPI.XenRef`1[[XenAPI.Crashdump, XenServer, Version=8.2.3.0, Culture=neutral, PublicKeyToken=d247b8b0ac7959e9]]
System.Guid

```
### Outputs
```
XenAPI.Crashdump[]

```
### Links
None

### Examples

Get-XenCrashdump [[-Ref] <XenRef[Crashdump]>] [-BestEffort] [-SessionOpaqueRef <string>] [<CommonParameters>]

Get-XenCrashdump [-Uuid] <guid> [-BestEffort] [-SessionOpaqueRef <string>] [<CommonParameters>]


## Get-XenCrashdumpProperty

### Synopsis
None

### Description
None

### Syntax
```
Get-XenCrashdumpProperty [-Crashdump] <Crashdump> [-XenProperty] <XenCrashdumpProperty> [[-BestEffort]] [[-SessionOpaqueRef] <string>] [-Ref] <XenRef[Crashdump]> [-XenProperty] <XenCrashdumpProperty> [[-BestEffort]] [[-SessionOpaqueRef] <string>]
```
### Parameters
| Name | Type | Required | Default Value | Description |
| :--- | :--- | :------- | :------------ | :---------- |
| BestEffort | switch | False |  |  |
| Crashdump | Crashdump | True |  |  |
| Ref | XenRef[Crashdump] | True |  |  |
| SessionOpaqueRef | string | False |  |  |
| XenProperty | XenCrashdumpProperty | True |  |  |
### Procedure
None

### Inputs
```
XenAPI.Crashdump
XenAPI.XenRef`1[[XenAPI.Crashdump, XenServer, Version=8.2.3.0, Culture=neutral, PublicKeyToken=d247b8b0ac7959e9]]

```
### Outputs
```
System.Object
```
### Links
None

### Examples

Get-XenCrashdumpProperty [-Crashdump] <Crashdump> -XenProperty <XenCrashdumpProperty> [-BestEffort] [-SessionOpaqueRef <string>] [<CommonParameters>]

Get-XenCrashdumpProperty [-Ref] <XenRef[Crashdump]> -XenProperty <XenCrashdumpProperty> [-BestEffort] [-SessionOpaqueRef <string>] [<CommonParameters>]


## Get-XenDRTask

### Synopsis
None

### Description
None

### Syntax
```
Get-XenDRTask [[-Ref] <XenRef[DR_task]>] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [-Uuid] <guid> [[-BestEffort]] [[-SessionOpaqueRef] <string>]
```
### Parameters
| Name | Type | Required | Default Value | Description |
| :--- | :--- | :------- | :------------ | :---------- |
| BestEffort | switch | False |  |  |
| Ref | XenRef[DR_task] | False |  |  |
| SessionOpaqueRef | string | False |  |  |
| Uuid | guid | True |  |  |
### Procedure
None

### Inputs
```
XenAPI.XenRef`1[[XenAPI.DR_task, XenServer, Version=8.2.3.0, Culture=neutral, PublicKeyToken=d247b8b0ac7959e9]]
System.Guid

```
### Outputs
```
XenAPI.DR_task[]

```
### Links
None

### Examples

Get-XenDRTask [[-Ref] <XenRef[DR_task]>] [-BestEffort] [-SessionOpaqueRef <string>] [<CommonParameters>]

Get-XenDRTask [-Uuid] <guid> [-BestEffort] [-SessionOpaqueRef <string>] [<CommonParameters>]


## Get-XenDRTaskProperty

### Synopsis
None

### Description
None

### Syntax
```
Get-XenDRTaskProperty [-DRTask] <DR_task> [-XenProperty] <XenDRTaskProperty> [[-BestEffort]] [[-SessionOpaqueRef] <string>] [-Ref] <XenRef[DR_task]> [-XenProperty] <XenDRTaskProperty> [[-BestEffort]] [[-SessionOpaqueRef] <string>]
```
### Parameters
| Name | Type | Required | Default Value | Description |
| :--- | :--- | :------- | :------------ | :---------- |
| BestEffort | switch | False |  |  |
| DRTask | DR_task | True |  |  |
| Ref | XenRef[DR_task] | True |  |  |
| SessionOpaqueRef | string | False |  |  |
| XenProperty | XenDRTaskProperty | True |  |  |
### Procedure
None

### Inputs
```
XenAPI.DR_task
XenAPI.XenRef`1[[XenAPI.DR_task, XenServer, Version=8.2.3.0, Culture=neutral, PublicKeyToken=d247b8b0ac7959e9]]

```
### Outputs
```
System.Object
```
### Links
None

### Examples

Get-XenDRTaskProperty [-DRTask] <DR_task> -XenProperty <XenDRTaskProperty> [-BestEffort] [-SessionOpaqueRef <string>] [<CommonParameters>]

Get-XenDRTaskProperty [-Ref] <XenRef[DR_task]> -XenProperty <XenDRTaskProperty> [-BestEffort] [-SessionOpaqueRef <string>] [<CommonParameters>]


## Get-XenFeature

### Synopsis
None

### Description
None

### Syntax
```
Get-XenFeature [[-Ref] <XenRef[Feature]>] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [-Uuid] <guid> [[-BestEffort]] [[-SessionOpaqueRef] <string>] [-Name] <string> [[-BestEffort]] [[-SessionOpaqueRef] <string>]
```
### Parameters
| Name | Type | Required | Default Value | Description |
| :--- | :--- | :------- | :------------ | :---------- |
| BestEffort | switch | False |  |  |
| Name | string | True |  |  |
| Ref | XenRef[Feature] | False |  |  |
| SessionOpaqueRef | string | False |  |  |
| Uuid | guid | True |  |  |
### Procedure
None

### Inputs
```
XenAPI.XenRef`1[[XenAPI.Feature, XenServer, Version=8.2.3.0, Culture=neutral, PublicKeyToken=d247b8b0ac7959e9]]
System.Guid
System.String

```
### Outputs
```
XenAPI.Feature[]

```
### Links
None

### Examples

Get-XenFeature [[-Ref] <XenRef[Feature]>] [-BestEffort] [-SessionOpaqueRef <string>] [<CommonParameters>]

Get-XenFeature [-Uuid] <guid> [-BestEffort] [-SessionOpaqueRef <string>] [<CommonParameters>]

Get-XenFeature [-Name] <string> [-BestEffort] [-SessionOpaqueRef <string>] [<CommonParameters>]


## Get-XenFeatureProperty

### Synopsis
None

### Description
None

### Syntax
```
Get-XenFeatureProperty [-Feature] <Feature> [-XenProperty] <XenFeatureProperty> [[-BestEffort]] [[-SessionOpaqueRef] <string>] [-Ref] <XenRef[Feature]> [-XenProperty] <XenFeatureProperty> [[-BestEffort]] [[-SessionOpaqueRef] <string>]
```
### Parameters
| Name | Type | Required | Default Value | Description |
| :--- | :--- | :------- | :------------ | :---------- |
| BestEffort | switch | False |  |  |
| Feature | Feature | True |  |  |
| Ref | XenRef[Feature] | True |  |  |
| SessionOpaqueRef | string | False |  |  |
| XenProperty | XenFeatureProperty | True |  |  |
### Procedure
None

### Inputs
```
XenAPI.Feature
XenAPI.XenRef`1[[XenAPI.Feature, XenServer, Version=8.2.3.0, Culture=neutral, PublicKeyToken=d247b8b0ac7959e9]]

```
### Outputs
```
System.Object
```
### Links
None

### Examples

Get-XenFeatureProperty [-Feature] <Feature> -XenProperty <XenFeatureProperty> [-BestEffort] [-SessionOpaqueRef <string>] [<CommonParameters>]

Get-XenFeatureProperty [-Ref] <XenRef[Feature]> -XenProperty <XenFeatureProperty> [-BestEffort] [-SessionOpaqueRef <string>] [<CommonParameters>]


## Get-XenGPUGroup

### Synopsis
None

### Description
None

### Syntax
```
Get-XenGPUGroup [[-Ref] <XenRef[GPU_group]>] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [-Uuid] <guid> [[-BestEffort]] [[-SessionOpaqueRef] <string>] [-Name] <string> [[-BestEffort]] [[-SessionOpaqueRef] <string>]
```
### Parameters
| Name | Type | Required | Default Value | Description |
| :--- | :--- | :------- | :------------ | :---------- |
| BestEffort | switch | False |  |  |
| Name | string | True |  |  |
| Ref | XenRef[GPU_group] | False |  |  |
| SessionOpaqueRef | string | False |  |  |
| Uuid | guid | True |  |  |
### Procedure
None

### Inputs
```
XenAPI.XenRef`1[[XenAPI.GPU_group, XenServer, Version=8.2.3.0, Culture=neutral, PublicKeyToken=d247b8b0ac7959e9]]
System.Guid
System.String

```
### Outputs
```
XenAPI.GPU_group[]

```
### Links
None

### Examples

Get-XenGPUGroup [[-Ref] <XenRef[GPU_group]>] [-BestEffort] [-SessionOpaqueRef <string>] [<CommonParameters>]

Get-XenGPUGroup [-Uuid] <guid> [-BestEffort] [-SessionOpaqueRef <string>] [<CommonParameters>]

Get-XenGPUGroup [-Name] <string> [-BestEffort] [-SessionOpaqueRef <string>] [<CommonParameters>]


## Get-XenGPUGroupProperty

### Synopsis
None

### Description
None

### Syntax
```
Get-XenGPUGroupProperty [-GPUGroup] <GPU_group> [-XenProperty] <XenGPUGroupProperty> [[-BestEffort]] [[-SessionOpaqueRef] <string>] [-Ref] <XenRef[GPU_group]> [-XenProperty] <XenGPUGroupProperty> [[-BestEffort]] [[-SessionOpaqueRef] <string>]
```
### Parameters
| Name | Type | Required | Default Value | Description |
| :--- | :--- | :------- | :------------ | :---------- |
| BestEffort | switch | False |  |  |
| GPUGroup | GPU_group | True |  |  |
| Ref | XenRef[GPU_group] | True |  |  |
| SessionOpaqueRef | string | False |  |  |
| XenProperty | XenGPUGroupProperty | True |  |  |
### Procedure
None

### Inputs
```
XenAPI.GPU_group
XenAPI.XenRef`1[[XenAPI.GPU_group, XenServer, Version=8.2.3.0, Culture=neutral, PublicKeyToken=d247b8b0ac7959e9]]

```
### Outputs
```
System.Object
```
### Links
None

### Examples

Get-XenGPUGroupProperty [-GPUGroup] <GPU_group> -XenProperty <XenGPUGroupProperty> [-BestEffort] [-SessionOpaqueRef <string>] [<CommonParameters>]

Get-XenGPUGroupProperty [-Ref] <XenRef[GPU_group]> -XenProperty <XenGPUGroupProperty> [-BestEffort] [-SessionOpaqueRef <string>] [<CommonParameters>]


## Get-XenHost

### Synopsis
None

### Description
None

### Syntax
```
Get-XenHost [[-Ref] <XenRef[Host]>] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [-Uuid] <guid> [[-BestEffort]] [[-SessionOpaqueRef] <string>] [-Name] <string> [[-BestEffort]] [[-SessionOpaqueRef] <string>]
```
### Parameters
| Name | Type | Required | Default Value | Description |
| :--- | :--- | :------- | :------------ | :---------- |
| BestEffort | switch | False |  |  |
| Name | string | True |  |  |
| Ref | XenRef[Host] | False |  |  |
| SessionOpaqueRef | string | False |  |  |
| Uuid | guid | True |  |  |
### Procedure
None

### Inputs
```
XenAPI.XenRef`1[[XenAPI.Host, XenServer, Version=8.2.3.0, Culture=neutral, PublicKeyToken=d247b8b0ac7959e9]]
System.Guid
System.String

```
### Outputs
```
XenAPI.Host[]

```
### Links
None

### Examples

Get-XenHost [[-Ref] <XenRef[Host]>] [-BestEffort] [-SessionOpaqueRef <string>] [<CommonParameters>]

Get-XenHost [-Uuid] <guid> [-BestEffort] [-SessionOpaqueRef <string>] [<CommonParameters>]

Get-XenHost [-Name] <string> [-BestEffort] [-SessionOpaqueRef <string>] [<CommonParameters>]


## Get-XenHostCpu

### Synopsis
None

### Description
None

### Syntax
```
Get-XenHostCpu [[-Ref] <XenRef[Host_cpu]>] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [-Uuid] <guid> [[-BestEffort]] [[-SessionOpaqueRef] <string>]
```
### Parameters
| Name | Type | Required | Default Value | Description |
| :--- | :--- | :------- | :------------ | :---------- |
| BestEffort | switch | False |  |  |
| Ref | XenRef[Host_cpu] | False |  |  |
| SessionOpaqueRef | string | False |  |  |
| Uuid | guid | True |  |  |
### Procedure
None

### Inputs
```
XenAPI.XenRef`1[[XenAPI.Host_cpu, XenServer, Version=8.2.3.0, Culture=neutral, PublicKeyToken=d247b8b0ac7959e9]]
System.Guid

```
### Outputs
```
XenAPI.Host_cpu[]

```
### Links
None

### Examples

Get-XenHostCpu [[-Ref] <XenRef[Host_cpu]>] [-BestEffort] [-SessionOpaqueRef <string>] [<CommonParameters>]

Get-XenHostCpu [-Uuid] <guid> [-BestEffort] [-SessionOpaqueRef <string>] [<CommonParameters>]


## Get-XenHostCpuProperty

### Synopsis
None

### Description
None

### Syntax
```
Get-XenHostCpuProperty [-HostCpu] <Host_cpu> [-XenProperty] <XenHostCpuProperty> [[-BestEffort]] [[-SessionOpaqueRef] <string>] [-Ref] <XenRef[Host_cpu]> [-XenProperty] <XenHostCpuProperty> [[-BestEffort]] [[-SessionOpaqueRef] <string>]
```
### Parameters
| Name | Type | Required | Default Value | Description |
| :--- | :--- | :------- | :------------ | :---------- |
| BestEffort | switch | False |  |  |
| HostCpu | Host_cpu | True |  |  |
| Ref | XenRef[Host_cpu] | True |  |  |
| SessionOpaqueRef | string | False |  |  |
| XenProperty | XenHostCpuProperty | True |  |  |
### Procedure
None

### Inputs
```
XenAPI.Host_cpu
XenAPI.XenRef`1[[XenAPI.Host_cpu, XenServer, Version=8.2.3.0, Culture=neutral, PublicKeyToken=d247b8b0ac7959e9]]

```
### Outputs
```
System.Object
```
### Links
None

### Examples

Get-XenHostCpuProperty [-HostCpu] <Host_cpu> -XenProperty <XenHostCpuProperty> [-BestEffort] [-SessionOpaqueRef <string>] [<CommonParameters>]

Get-XenHostCpuProperty [-Ref] <XenRef[Host_cpu]> -XenProperty <XenHostCpuProperty> [-BestEffort] [-SessionOpaqueRef <string>] [<CommonParameters>]


## Get-XenHostCrashdump

### Synopsis
None

### Description
None

### Syntax
```
Get-XenHostCrashdump [[-Ref] <XenRef[Host_crashdump]>] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [-Uuid] <guid> [[-BestEffort]] [[-SessionOpaqueRef] <string>]
```
### Parameters
| Name | Type | Required | Default Value | Description |
| :--- | :--- | :------- | :------------ | :---------- |
| BestEffort | switch | False |  |  |
| Ref | XenRef[Host_crashdump] | False |  |  |
| SessionOpaqueRef | string | False |  |  |
| Uuid | guid | True |  |  |
### Procedure
None

### Inputs
```
XenAPI.XenRef`1[[XenAPI.Host_crashdump, XenServer, Version=8.2.3.0, Culture=neutral, PublicKeyToken=d247b8b0ac7959e9]]
System.Guid

```
### Outputs
```
XenAPI.Host_crashdump[]

```
### Links
None

### Examples

Get-XenHostCrashdump [[-Ref] <XenRef[Host_crashdump]>] [-BestEffort] [-SessionOpaqueRef <string>] [<CommonParameters>]

Get-XenHostCrashdump [-Uuid] <guid> [-BestEffort] [-SessionOpaqueRef <string>] [<CommonParameters>]


## Get-XenHostCrashdumpProperty

### Synopsis
None

### Description
None

### Syntax
```
Get-XenHostCrashdumpProperty [-HostCrashdump] <Host_crashdump> [-XenProperty] <XenHostCrashdumpProperty> [[-BestEffort]] [[-SessionOpaqueRef] <string>] [-Ref] <XenRef[Host_crashdump]> [-XenProperty] <XenHostCrashdumpProperty> [[-BestEffort]] [[-SessionOpaqueRef] <string>]
```
### Parameters
| Name | Type | Required | Default Value | Description |
| :--- | :--- | :------- | :------------ | :---------- |
| BestEffort | switch | False |  |  |
| HostCrashdump | Host_crashdump | True |  |  |
| Ref | XenRef[Host_crashdump] | True |  |  |
| SessionOpaqueRef | string | False |  |  |
| XenProperty | XenHostCrashdumpProperty | True |  |  |
### Procedure
None

### Inputs
```
XenAPI.Host_crashdump
XenAPI.XenRef`1[[XenAPI.Host_crashdump, XenServer, Version=8.2.3.0, Culture=neutral, PublicKeyToken=d247b8b0ac7959e9]]

```
### Outputs
```
System.Object
```
### Links
None

### Examples

Get-XenHostCrashdumpProperty [-HostCrashdump] <Host_crashdump> -XenProperty <XenHostCrashdumpProperty> [-BestEffort] [-SessionOpaqueRef <string>] [<CommonParameters>]

Get-XenHostCrashdumpProperty [-Ref] <XenRef[Host_crashdump]> -XenProperty <XenHostCrashdumpProperty> [-BestEffort] [-SessionOpaqueRef <string>] [<CommonParameters>]


## Get-XenHostMetrics

### Synopsis
None

### Description
None

### Syntax
```
Get-XenHostMetrics [[-Ref] <XenRef[Host_metrics]>] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [-Uuid] <guid> [[-BestEffort]] [[-SessionOpaqueRef] <string>]
```
### Parameters
| Name | Type | Required | Default Value | Description |
| :--- | :--- | :------- | :------------ | :---------- |
| BestEffort | switch | False |  |  |
| Ref | XenRef[Host_metrics] | False |  |  |
| SessionOpaqueRef | string | False |  |  |
| Uuid | guid | True |  |  |
### Procedure
None

### Inputs
```
XenAPI.XenRef`1[[XenAPI.Host_metrics, XenServer, Version=8.2.3.0, Culture=neutral, PublicKeyToken=d247b8b0ac7959e9]]
System.Guid

```
### Outputs
```
XenAPI.Host_metrics[]

```
### Links
None

### Examples

Get-XenHostMetrics [[-Ref] <XenRef[Host_metrics]>] [-BestEffort] [-SessionOpaqueRef <string>] [<CommonParameters>]

Get-XenHostMetrics [-Uuid] <guid> [-BestEffort] [-SessionOpaqueRef <string>] [<CommonParameters>]


## Get-XenHostMetricsProperty

### Synopsis
None

### Description
None

### Syntax
```
Get-XenHostMetricsProperty [-HostMetrics] <Host_metrics> [-XenProperty] <XenHostMetricsProperty> [[-BestEffort]] [[-SessionOpaqueRef] <string>] [-Ref] <XenRef[Host_metrics]> [-XenProperty] <XenHostMetricsProperty> [[-BestEffort]] [[-SessionOpaqueRef] <string>]
```
### Parameters
| Name | Type | Required | Default Value | Description |
| :--- | :--- | :------- | :------------ | :---------- |
| BestEffort | switch | False |  |  |
| HostMetrics | Host_metrics | True |  |  |
| Ref | XenRef[Host_metrics] | True |  |  |
| SessionOpaqueRef | string | False |  |  |
| XenProperty | XenHostMetricsProperty | True |  |  |
### Procedure
None

### Inputs
```
XenAPI.Host_metrics
XenAPI.XenRef`1[[XenAPI.Host_metrics, XenServer, Version=8.2.3.0, Culture=neutral, PublicKeyToken=d247b8b0ac7959e9]]

```
### Outputs
```
System.Object
```
### Links
None

### Examples

Get-XenHostMetricsProperty [-HostMetrics] <Host_metrics> -XenProperty <XenHostMetricsProperty> [-BestEffort] [-SessionOpaqueRef <string>] [<CommonParameters>]

Get-XenHostMetricsProperty [-Ref] <XenRef[Host_metrics]> -XenProperty <XenHostMetricsProperty> [-BestEffort] [-SessionOpaqueRef <string>] [<CommonParameters>]


## Get-XenHostPatch

### Synopsis
None

### Description
None

### Syntax
```
Get-XenHostPatch [[-Ref] <XenRef[Host_patch]>] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [-Uuid] <guid> [[-BestEffort]] [[-SessionOpaqueRef] <string>] [-Name] <string> [[-BestEffort]] [[-SessionOpaqueRef] <string>]
```
### Parameters
| Name | Type | Required | Default Value | Description |
| :--- | :--- | :------- | :------------ | :---------- |
| BestEffort | switch | False |  |  |
| Name | string | True |  |  |
| Ref | XenRef[Host_patch] | False |  |  |
| SessionOpaqueRef | string | False |  |  |
| Uuid | guid | True |  |  |
### Procedure
None

### Inputs
```
XenAPI.XenRef`1[[XenAPI.Host_patch, XenServer, Version=8.2.3.0, Culture=neutral, PublicKeyToken=d247b8b0ac7959e9]]
System.Guid
System.String

```
### Outputs
```
XenAPI.Host_patch[]

```
### Links
None

### Examples

Get-XenHostPatch [[-Ref] <XenRef[Host_patch]>] [-BestEffort] [-SessionOpaqueRef <string>] [<CommonParameters>]

Get-XenHostPatch [-Uuid] <guid> [-BestEffort] [-SessionOpaqueRef <string>] [<CommonParameters>]

Get-XenHostPatch [-Name] <string> [-BestEffort] [-SessionOpaqueRef <string>] [<CommonParameters>]


## Get-XenHostPatchProperty

### Synopsis
None

### Description
None

### Syntax
```
Get-XenHostPatchProperty [-HostPatch] <Host_patch> [-XenProperty] <XenHostPatchProperty> [[-BestEffort]] [[-SessionOpaqueRef] <string>] [-Ref] <XenRef[Host_patch]> [-XenProperty] <XenHostPatchProperty> [[-BestEffort]] [[-SessionOpaqueRef] <string>]
```
### Parameters
| Name | Type | Required | Default Value | Description |
| :--- | :--- | :------- | :------------ | :---------- |
| BestEffort | switch | False |  |  |
| HostPatch | Host_patch | True |  |  |
| Ref | XenRef[Host_patch] | True |  |  |
| SessionOpaqueRef | string | False |  |  |
| XenProperty | XenHostPatchProperty | True |  |  |
### Procedure
None

### Inputs
```
XenAPI.Host_patch
XenAPI.XenRef`1[[XenAPI.Host_patch, XenServer, Version=8.2.3.0, Culture=neutral, PublicKeyToken=d247b8b0ac7959e9]]

```
### Outputs
```
System.Object
```
### Links
None

### Examples

Get-XenHostPatchProperty [-HostPatch] <Host_patch> -XenProperty <XenHostPatchProperty> [-BestEffort] [-SessionOpaqueRef <string>] [<CommonParameters>]

Get-XenHostPatchProperty [-Ref] <XenRef[Host_patch]> -XenProperty <XenHostPatchProperty> [-BestEffort] [-SessionOpaqueRef <string>] [<CommonParameters>]


## Get-XenHostProperty

### Synopsis
None

### Description
None

### Syntax
```
Get-XenHostProperty [-XenHost] <Host> [-XenProperty] <XenHostProperty> [[-BestEffort]] [[-SessionOpaqueRef] <string>] [-Ref] <XenRef[Host]> [-XenProperty] <XenHostProperty> [[-BestEffort]] [[-SessionOpaqueRef] <string>]
```
### Parameters
| Name | Type | Required | Default Value | Description |
| :--- | :--- | :------- | :------------ | :---------- |
| BestEffort | switch | False |  |  |
| Ref | XenRef[Host] | True |  |  |
| SessionOpaqueRef | string | False |  |  |
| XenHost | Host | True |  |  |
| XenProperty | XenHostProperty | True |  |  |
### Procedure
None

### Inputs
```
XenAPI.Host
XenAPI.XenRef`1[[XenAPI.Host, XenServer, Version=8.2.3.0, Culture=neutral, PublicKeyToken=d247b8b0ac7959e9]]

```
### Outputs
```
System.Object
```
### Links
None

### Examples

Get-XenHostProperty [-XenHost] <Host> -XenProperty <XenHostProperty> [-BestEffort] [-SessionOpaqueRef <string>] [<CommonParameters>]

Get-XenHostProperty [-Ref] <XenRef[Host]> -XenProperty <XenHostProperty> [-BestEffort] [-SessionOpaqueRef <string>] [<CommonParameters>]


## Get-XenLVHDProperty

### Synopsis
None

### Description
None

### Syntax
```
Get-XenLVHDProperty [-LVHD] <LVHD> [-XenProperty] <XenLVHDProperty> [[-BestEffort]] [[-SessionOpaqueRef] <string>] [-Ref] <XenRef[LVHD]> [-XenProperty] <XenLVHDProperty> [[-BestEffort]] [[-SessionOpaqueRef] <string>]
```
### Parameters
| Name | Type | Required | Default Value | Description |
| :--- | :--- | :------- | :------------ | :---------- |
| BestEffort | switch | False |  |  |
| LVHD | LVHD | True |  |  |
| Ref | XenRef[LVHD] | True |  |  |
| SessionOpaqueRef | string | False |  |  |
| XenProperty | XenLVHDProperty | True |  |  |
### Procedure
None

### Inputs
```
XenAPI.LVHD
XenAPI.XenRef`1[[XenAPI.LVHD, XenServer, Version=8.2.3.0, Culture=neutral, PublicKeyToken=d247b8b0ac7959e9]]

```
### Outputs
```
System.Object
```
### Links
None

### Examples

Get-XenLVHDProperty [-LVHD] <LVHD> -XenProperty <XenLVHDProperty> [-BestEffort] [-SessionOpaqueRef <string>] [<CommonParameters>]

Get-XenLVHDProperty [-Ref] <XenRef[LVHD]> -XenProperty <XenLVHDProperty> [-BestEffort] [-SessionOpaqueRef <string>] [<CommonParameters>]


## Get-XenMessage

### Synopsis
None

### Description
None

### Syntax
```
Get-XenMessage [[-Ref] <XenRef[Message]>] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [-Uuid] <guid> [[-BestEffort]] [[-SessionOpaqueRef] <string>]
```
### Parameters
| Name | Type | Required | Default Value | Description |
| :--- | :--- | :------- | :------------ | :---------- |
| BestEffort | switch | False |  |  |
| Ref | XenRef[Message] | False |  |  |
| SessionOpaqueRef | string | False |  |  |
| Uuid | guid | True |  |  |
### Procedure
None

### Inputs
```
XenAPI.XenRef`1[[XenAPI.Message, XenServer, Version=8.2.3.0, Culture=neutral, PublicKeyToken=d247b8b0ac7959e9]]
System.Guid

```
### Outputs
```
XenAPI.Message[]

```
### Links
None

### Examples

Get-XenMessage [[-Ref] <XenRef[Message]>] [-BestEffort] [-SessionOpaqueRef <string>] [<CommonParameters>]

Get-XenMessage [-Uuid] <guid> [-BestEffort] [-SessionOpaqueRef <string>] [<CommonParameters>]


## Get-XenMessageProperty

### Synopsis
None

### Description
None

### Syntax
```
Get-XenMessageProperty [-Message] <Message> [-XenProperty] <XenMessageProperty> [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-Since] <datetime>] [-Ref] <XenRef[Message]> [-XenProperty] <XenMessageProperty> [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-Since] <datetime>]
```
### Parameters
| Name | Type | Required | Default Value | Description |
| :--- | :--- | :------- | :------------ | :---------- |
| BestEffort | switch | False |  |  |
| Message | Message | True |  |  |
| Ref | XenRef[Message] | True |  |  |
| SessionOpaqueRef | string | False |  |  |
| Since | datetime | False |  |  |
| XenProperty | XenMessageProperty | True |  |  |
### Procedure
None

### Inputs
```
XenAPI.Message
XenAPI.XenRef`1[[XenAPI.Message, XenServer, Version=8.2.3.0, Culture=neutral, PublicKeyToken=d247b8b0ac7959e9]]

```
### Outputs
```
System.Object
```
### Links
None

### Examples

Get-XenMessageProperty [-Message] <Message> -XenProperty <XenMessageProperty> [-BestEffort] [-SessionOpaqueRef <string>] [-Since <datetime>] [<CommonParameters>]

Get-XenMessageProperty [-Ref] <XenRef[Message]> -XenProperty <XenMessageProperty> [-BestEffort] [-SessionOpaqueRef <string>] [-Since <datetime>] [<CommonParameters>]


## Get-XenNetwork

### Synopsis
None

### Description
None

### Syntax
```
Get-XenNetwork [[-Ref] <XenRef[Network]>] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [-Uuid] <guid> [[-BestEffort]] [[-SessionOpaqueRef] <string>] [-Name] <string> [[-BestEffort]] [[-SessionOpaqueRef] <string>]
```
### Parameters
| Name | Type | Required | Default Value | Description |
| :--- | :--- | :------- | :------------ | :---------- |
| BestEffort | switch | False |  |  |
| Name | string | True |  |  |
| Ref | XenRef[Network] | False |  |  |
| SessionOpaqueRef | string | False |  |  |
| Uuid | guid | True |  |  |
### Procedure
None

### Inputs
```
XenAPI.XenRef`1[[XenAPI.Network, XenServer, Version=8.2.3.0, Culture=neutral, PublicKeyToken=d247b8b0ac7959e9]]
System.Guid
System.String

```
### Outputs
```
XenAPI.Network[]

```
### Links
None

### Examples

Get-XenNetwork [[-Ref] <XenRef[Network]>] [-BestEffort] [-SessionOpaqueRef <string>] [<CommonParameters>]

Get-XenNetwork [-Uuid] <guid> [-BestEffort] [-SessionOpaqueRef <string>] [<CommonParameters>]

Get-XenNetwork [-Name] <string> [-BestEffort] [-SessionOpaqueRef <string>] [<CommonParameters>]


## Get-XenNetworkProperty

### Synopsis
None

### Description
None

### Syntax
```
Get-XenNetworkProperty [-Network] <Network> [-XenProperty] <XenNetworkProperty> [[-BestEffort]] [[-SessionOpaqueRef] <string>] [-Ref] <XenRef[Network]> [-XenProperty] <XenNetworkProperty> [[-BestEffort]] [[-SessionOpaqueRef] <string>]
```
### Parameters
| Name | Type | Required | Default Value | Description |
| :--- | :--- | :------- | :------------ | :---------- |
| BestEffort | switch | False |  |  |
| Network | Network | True |  |  |
| Ref | XenRef[Network] | True |  |  |
| SessionOpaqueRef | string | False |  |  |
| XenProperty | XenNetworkProperty | True |  |  |
### Procedure
None

### Inputs
```
XenAPI.Network
XenAPI.XenRef`1[[XenAPI.Network, XenServer, Version=8.2.3.0, Culture=neutral, PublicKeyToken=d247b8b0ac7959e9]]

```
### Outputs
```
System.Object
```
### Links
None

### Examples

Get-XenNetworkProperty [-Network] <Network> -XenProperty <XenNetworkProperty> [-BestEffort] [-SessionOpaqueRef <string>] [<CommonParameters>]

Get-XenNetworkProperty [-Ref] <XenRef[Network]> -XenProperty <XenNetworkProperty> [-BestEffort] [-SessionOpaqueRef <string>] [<CommonParameters>]


## Get-XenNetworkSriov

### Synopsis
None

### Description
None

### Syntax
```
Get-XenNetworkSriov [[-Ref] <XenRef[Network_sriov]>] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [-Uuid] <guid> [[-BestEffort]] [[-SessionOpaqueRef] <string>]
```
### Parameters
| Name | Type | Required | Default Value | Description |
| :--- | :--- | :------- | :------------ | :---------- |
| BestEffort | switch | False |  |  |
| Ref | XenRef[Network_sriov] | False |  |  |
| SessionOpaqueRef | string | False |  |  |
| Uuid | guid | True |  |  |
### Procedure
None

### Inputs
```
XenAPI.XenRef`1[[XenAPI.Network_sriov, XenServer, Version=8.2.3.0, Culture=neutral, PublicKeyToken=d247b8b0ac7959e9]]
System.Guid

```
### Outputs
```
XenAPI.Network_sriov[]

```
### Links
None

### Examples

Get-XenNetworkSriov [[-Ref] <XenRef[Network_sriov]>] [-BestEffort] [-SessionOpaqueRef <string>] [<CommonParameters>]

Get-XenNetworkSriov [-Uuid] <guid> [-BestEffort] [-SessionOpaqueRef <string>] [<CommonParameters>]


## Get-XenNetworkSriovProperty

### Synopsis
None

### Description
None

### Syntax
```
Get-XenNetworkSriovProperty [-NetworkSriov] <Network_sriov> [-XenProperty] <XenNetworkSriovProperty> [[-BestEffort]] [[-SessionOpaqueRef] <string>] [-Ref] <XenRef[Network_sriov]> [-XenProperty] <XenNetworkSriovProperty> [[-BestEffort]] [[-SessionOpaqueRef] <string>]
```
### Parameters
| Name | Type | Required | Default Value | Description |
| :--- | :--- | :------- | :------------ | :---------- |
| BestEffort | switch | False |  |  |
| NetworkSriov | Network_sriov | True |  |  |
| Ref | XenRef[Network_sriov] | True |  |  |
| SessionOpaqueRef | string | False |  |  |
| XenProperty | XenNetworkSriovProperty | True |  |  |
### Procedure
None

### Inputs
```
XenAPI.Network_sriov
XenAPI.XenRef`1[[XenAPI.Network_sriov, XenServer, Version=8.2.3.0, Culture=neutral, PublicKeyToken=d247b8b0ac7959e9]]

```
### Outputs
```
System.Object
```
### Links
None

### Examples

Get-XenNetworkSriovProperty [-NetworkSriov] <Network_sriov> -XenProperty <XenNetworkSriovProperty> [-BestEffort] [-SessionOpaqueRef <string>] [<CommonParameters>]

Get-XenNetworkSriovProperty [-Ref] <XenRef[Network_sriov]> -XenProperty <XenNetworkSriovProperty> [-BestEffort] [-SessionOpaqueRef <string>] [<CommonParameters>]


## Get-XenPBD

### Synopsis
None

### Description
None

### Syntax
```
Get-XenPBD [[-Ref] <XenRef[PBD]>] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [-Uuid] <guid> [[-BestEffort]] [[-SessionOpaqueRef] <string>]
```
### Parameters
| Name | Type | Required | Default Value | Description |
| :--- | :--- | :------- | :------------ | :---------- |
| BestEffort | switch | False |  |  |
| Ref | XenRef[PBD] | False |  |  |
| SessionOpaqueRef | string | False |  |  |
| Uuid | guid | True |  |  |
### Procedure
None

### Inputs
```
XenAPI.XenRef`1[[XenAPI.PBD, XenServer, Version=8.2.3.0, Culture=neutral, PublicKeyToken=d247b8b0ac7959e9]]
System.Guid

```
### Outputs
```
XenAPI.PBD[]

```
### Links
None

### Examples

Get-XenPBD [[-Ref] <XenRef[PBD]>] [-BestEffort] [-SessionOpaqueRef <string>] [<CommonParameters>]

Get-XenPBD [-Uuid] <guid> [-BestEffort] [-SessionOpaqueRef <string>] [<CommonParameters>]


## Get-XenPBDProperty

### Synopsis
None

### Description
None

### Syntax
```
Get-XenPBDProperty [-PBD] <PBD> [-XenProperty] <XenPBDProperty> [[-BestEffort]] [[-SessionOpaqueRef] <string>] [-Ref] <XenRef[PBD]> [-XenProperty] <XenPBDProperty> [[-BestEffort]] [[-SessionOpaqueRef] <string>]
```
### Parameters
| Name | Type | Required | Default Value | Description |
| :--- | :--- | :------- | :------------ | :---------- |
| BestEffort | switch | False |  |  |
| PBD | PBD | True |  |  |
| Ref | XenRef[PBD] | True |  |  |
| SessionOpaqueRef | string | False |  |  |
| XenProperty | XenPBDProperty | True |  |  |
### Procedure
None

### Inputs
```
XenAPI.PBD
XenAPI.XenRef`1[[XenAPI.PBD, XenServer, Version=8.2.3.0, Culture=neutral, PublicKeyToken=d247b8b0ac7959e9]]

```
### Outputs
```
System.Object
```
### Links
None

### Examples

Get-XenPBDProperty [-PBD] <PBD> -XenProperty <XenPBDProperty> [-BestEffort] [-SessionOpaqueRef <string>] [<CommonParameters>]

Get-XenPBDProperty [-Ref] <XenRef[PBD]> -XenProperty <XenPBDProperty> [-BestEffort] [-SessionOpaqueRef <string>] [<CommonParameters>]


## Get-XenPCI

### Synopsis
None

### Description
None

### Syntax
```
Get-XenPCI [[-Ref] <XenRef[PCI]>] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [-Uuid] <guid> [[-BestEffort]] [[-SessionOpaqueRef] <string>]
```
### Parameters
| Name | Type | Required | Default Value | Description |
| :--- | :--- | :------- | :------------ | :---------- |
| BestEffort | switch | False |  |  |
| Ref | XenRef[PCI] | False |  |  |
| SessionOpaqueRef | string | False |  |  |
| Uuid | guid | True |  |  |
### Procedure
None

### Inputs
```
XenAPI.XenRef`1[[XenAPI.PCI, XenServer, Version=8.2.3.0, Culture=neutral, PublicKeyToken=d247b8b0ac7959e9]]
System.Guid

```
### Outputs
```
XenAPI.PCI[]

```
### Links
None

### Examples

Get-XenPCI [[-Ref] <XenRef[PCI]>] [-BestEffort] [-SessionOpaqueRef <string>] [<CommonParameters>]

Get-XenPCI [-Uuid] <guid> [-BestEffort] [-SessionOpaqueRef <string>] [<CommonParameters>]


## Get-XenPCIProperty

### Synopsis
None

### Description
None

### Syntax
```
Get-XenPCIProperty [-PCI] <PCI> [-XenProperty] <XenPCIProperty> [[-BestEffort]] [[-SessionOpaqueRef] <string>] [-Ref] <XenRef[PCI]> [-XenProperty] <XenPCIProperty> [[-BestEffort]] [[-SessionOpaqueRef] <string>]
```
### Parameters
| Name | Type | Required | Default Value | Description |
| :--- | :--- | :------- | :------------ | :---------- |
| BestEffort | switch | False |  |  |
| PCI | PCI | True |  |  |
| Ref | XenRef[PCI] | True |  |  |
| SessionOpaqueRef | string | False |  |  |
| XenProperty | XenPCIProperty | True |  |  |
### Procedure
None

### Inputs
```
XenAPI.PCI
XenAPI.XenRef`1[[XenAPI.PCI, XenServer, Version=8.2.3.0, Culture=neutral, PublicKeyToken=d247b8b0ac7959e9]]

```
### Outputs
```
System.Object
```
### Links
None

### Examples

Get-XenPCIProperty [-PCI] <PCI> -XenProperty <XenPCIProperty> [-BestEffort] [-SessionOpaqueRef <string>] [<CommonParameters>]

Get-XenPCIProperty [-Ref] <XenRef[PCI]> -XenProperty <XenPCIProperty> [-BestEffort] [-SessionOpaqueRef <string>] [<CommonParameters>]


## Get-XenPGPU

### Synopsis
None

### Description
None

### Syntax
```
Get-XenPGPU [[-Ref] <XenRef[PGPU]>] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [-Uuid] <guid> [[-BestEffort]] [[-SessionOpaqueRef] <string>]
```
### Parameters
| Name | Type | Required | Default Value | Description |
| :--- | :--- | :------- | :------------ | :---------- |
| BestEffort | switch | False |  |  |
| Ref | XenRef[PGPU] | False |  |  |
| SessionOpaqueRef | string | False |  |  |
| Uuid | guid | True |  |  |
### Procedure
None

### Inputs
```
XenAPI.XenRef`1[[XenAPI.PGPU, XenServer, Version=8.2.3.0, Culture=neutral, PublicKeyToken=d247b8b0ac7959e9]]
System.Guid

```
### Outputs
```
XenAPI.PGPU[]

```
### Links
None

### Examples

Get-XenPGPU [[-Ref] <XenRef[PGPU]>] [-BestEffort] [-SessionOpaqueRef <string>] [<CommonParameters>]

Get-XenPGPU [-Uuid] <guid> [-BestEffort] [-SessionOpaqueRef <string>] [<CommonParameters>]


## Get-XenPGPUProperty

### Synopsis
None

### Description
None

### Syntax
```
Get-XenPGPUProperty [-PGPU] <PGPU> [-XenProperty] <XenPGPUProperty> [[-BestEffort]] [[-SessionOpaqueRef] <string>] [-Ref] <XenRef[PGPU]> [-XenProperty] <XenPGPUProperty> [[-BestEffort]] [[-SessionOpaqueRef] <string>]
```
### Parameters
| Name | Type | Required | Default Value | Description |
| :--- | :--- | :------- | :------------ | :---------- |
| BestEffort | switch | False |  |  |
| PGPU | PGPU | True |  |  |
| Ref | XenRef[PGPU] | True |  |  |
| SessionOpaqueRef | string | False |  |  |
| XenProperty | XenPGPUProperty | True |  |  |
### Procedure
None

### Inputs
```
XenAPI.PGPU
XenAPI.XenRef`1[[XenAPI.PGPU, XenServer, Version=8.2.3.0, Culture=neutral, PublicKeyToken=d247b8b0ac7959e9]]

```
### Outputs
```
System.Object
```
### Links
None

### Examples

Get-XenPGPUProperty [-PGPU] <PGPU> -XenProperty <XenPGPUProperty> [-BestEffort] [-SessionOpaqueRef <string>] [<CommonParameters>]

Get-XenPGPUProperty [-Ref] <XenRef[PGPU]> -XenProperty <XenPGPUProperty> [-BestEffort] [-SessionOpaqueRef <string>] [<CommonParameters>]


## Get-XenPIF

### Synopsis
None

### Description
None

### Syntax
```
Get-XenPIF [[-Ref] <XenRef[PIF]>] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [-Uuid] <guid> [[-BestEffort]] [[-SessionOpaqueRef] <string>]
```
### Parameters
| Name | Type | Required | Default Value | Description |
| :--- | :--- | :------- | :------------ | :---------- |
| BestEffort | switch | False |  |  |
| Ref | XenRef[PIF] | False |  |  |
| SessionOpaqueRef | string | False |  |  |
| Uuid | guid | True |  |  |
### Procedure
None

### Inputs
```
XenAPI.XenRef`1[[XenAPI.PIF, XenServer, Version=8.2.3.0, Culture=neutral, PublicKeyToken=d247b8b0ac7959e9]]
System.Guid

```
### Outputs
```
XenAPI.PIF[]

```
### Links
None

### Examples

Get-XenPIF [[-Ref] <XenRef[PIF]>] [-BestEffort] [-SessionOpaqueRef <string>] [<CommonParameters>]

Get-XenPIF [-Uuid] <guid> [-BestEffort] [-SessionOpaqueRef <string>] [<CommonParameters>]


## Get-XenPIFMetrics

### Synopsis
None

### Description
None

### Syntax
```
Get-XenPIFMetrics [[-Ref] <XenRef[PIF_metrics]>] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [-Uuid] <guid> [[-BestEffort]] [[-SessionOpaqueRef] <string>]
```
### Parameters
| Name | Type | Required | Default Value | Description |
| :--- | :--- | :------- | :------------ | :---------- |
| BestEffort | switch | False |  |  |
| Ref | XenRef[PIF_metrics] | False |  |  |
| SessionOpaqueRef | string | False |  |  |
| Uuid | guid | True |  |  |
### Procedure
None

### Inputs
```
XenAPI.XenRef`1[[XenAPI.PIF_metrics, XenServer, Version=8.2.3.0, Culture=neutral, PublicKeyToken=d247b8b0ac7959e9]]
System.Guid

```
### Outputs
```
XenAPI.PIF_metrics[]

```
### Links
None

### Examples

Get-XenPIFMetrics [[-Ref] <XenRef[PIF_metrics]>] [-BestEffort] [-SessionOpaqueRef <string>] [<CommonParameters>]

Get-XenPIFMetrics [-Uuid] <guid> [-BestEffort] [-SessionOpaqueRef <string>] [<CommonParameters>]


## Get-XenPIFMetricsProperty

### Synopsis
None

### Description
None

### Syntax
```
Get-XenPIFMetricsProperty [-PIFMetrics] <PIF_metrics> [-XenProperty] <XenPIFMetricsProperty> [[-BestEffort]] [[-SessionOpaqueRef] <string>] [-Ref] <XenRef[PIF_metrics]> [-XenProperty] <XenPIFMetricsProperty> [[-BestEffort]] [[-SessionOpaqueRef] <string>]
```
### Parameters
| Name | Type | Required | Default Value | Description |
| :--- | :--- | :------- | :------------ | :---------- |
| BestEffort | switch | False |  |  |
| PIFMetrics | PIF_metrics | True |  |  |
| Ref | XenRef[PIF_metrics] | True |  |  |
| SessionOpaqueRef | string | False |  |  |
| XenProperty | XenPIFMetricsProperty | True |  |  |
### Procedure
None

### Inputs
```
XenAPI.PIF_metrics
XenAPI.XenRef`1[[XenAPI.PIF_metrics, XenServer, Version=8.2.3.0, Culture=neutral, PublicKeyToken=d247b8b0ac7959e9]]

```
### Outputs
```
System.Object
```
### Links
None

### Examples

Get-XenPIFMetricsProperty [-PIFMetrics] <PIF_metrics> -XenProperty <XenPIFMetricsProperty> [-BestEffort] [-SessionOpaqueRef <string>] [<CommonParameters>]

Get-XenPIFMetricsProperty [-Ref] <XenRef[PIF_metrics]> -XenProperty <XenPIFMetricsProperty> [-BestEffort] [-SessionOpaqueRef <string>] [<CommonParameters>]


## Get-XenPIFProperty

### Synopsis
None

### Description
None

### Syntax
```
Get-XenPIFProperty [-PIF] <PIF> [-XenProperty] <XenPIFProperty> [[-BestEffort]] [[-SessionOpaqueRef] <string>] [-Ref] <XenRef[PIF]> [-XenProperty] <XenPIFProperty> [[-BestEffort]] [[-SessionOpaqueRef] <string>]
```
### Parameters
| Name | Type | Required | Default Value | Description |
| :--- | :--- | :------- | :------------ | :---------- |
| BestEffort | switch | False |  |  |
| PIF | PIF | True |  |  |
| Ref | XenRef[PIF] | True |  |  |
| SessionOpaqueRef | string | False |  |  |
| XenProperty | XenPIFProperty | True |  |  |
### Procedure
None

### Inputs
```
XenAPI.PIF
XenAPI.XenRef`1[[XenAPI.PIF, XenServer, Version=8.2.3.0, Culture=neutral, PublicKeyToken=d247b8b0ac7959e9]]

```
### Outputs
```
System.Object
```
### Links
None

### Examples

Get-XenPIFProperty [-PIF] <PIF> -XenProperty <XenPIFProperty> [-BestEffort] [-SessionOpaqueRef <string>] [<CommonParameters>]

Get-XenPIFProperty [-Ref] <XenRef[PIF]> -XenProperty <XenPIFProperty> [-BestEffort] [-SessionOpaqueRef <string>] [<CommonParameters>]


## Get-XenPool

### Synopsis
None

### Description
None

### Syntax
```
Get-XenPool [[-Ref] <XenRef[Pool]>] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [-Uuid] <guid> [[-BestEffort]] [[-SessionOpaqueRef] <string>]
```
### Parameters
| Name | Type | Required | Default Value | Description |
| :--- | :--- | :------- | :------------ | :---------- |
| BestEffort | switch | False |  |  |
| Ref | XenRef[Pool] | False |  |  |
| SessionOpaqueRef | string | False |  |  |
| Uuid | guid | True |  |  |
### Procedure
None

### Inputs
```
XenAPI.XenRef`1[[XenAPI.Pool, XenServer, Version=8.2.3.0, Culture=neutral, PublicKeyToken=d247b8b0ac7959e9]]
System.Guid

```
### Outputs
```
XenAPI.Pool[]

```
### Links
None

### Examples

Get-XenPool [[-Ref] <XenRef[Pool]>] [-BestEffort] [-SessionOpaqueRef <string>] [<CommonParameters>]

Get-XenPool [-Uuid] <guid> [-BestEffort] [-SessionOpaqueRef <string>] [<CommonParameters>]


## Get-XenPoolPatch

### Synopsis
None

### Description
None

### Syntax
```
Get-XenPoolPatch [[-Ref] <XenRef[Pool_patch]>] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [-Uuid] <guid> [[-BestEffort]] [[-SessionOpaqueRef] <string>] [-Name] <string> [[-BestEffort]] [[-SessionOpaqueRef] <string>]
```
### Parameters
| Name | Type | Required | Default Value | Description |
| :--- | :--- | :------- | :------------ | :---------- |
| BestEffort | switch | False |  |  |
| Name | string | True |  |  |
| Ref | XenRef[Pool_patch] | False |  |  |
| SessionOpaqueRef | string | False |  |  |
| Uuid | guid | True |  |  |
### Procedure
None

### Inputs
```
XenAPI.XenRef`1[[XenAPI.Pool_patch, XenServer, Version=8.2.3.0, Culture=neutral, PublicKeyToken=d247b8b0ac7959e9]]
System.Guid
System.String

```
### Outputs
```
XenAPI.Pool_patch[]

```
### Links
None

### Examples

Get-XenPoolPatch [[-Ref] <XenRef[Pool_patch]>] [-BestEffort] [-SessionOpaqueRef <string>] [<CommonParameters>]

Get-XenPoolPatch [-Uuid] <guid> [-BestEffort] [-SessionOpaqueRef <string>] [<CommonParameters>]

Get-XenPoolPatch [-Name] <string> [-BestEffort] [-SessionOpaqueRef <string>] [<CommonParameters>]


## Get-XenPoolPatchProperty

### Synopsis
None

### Description
None

### Syntax
```
Get-XenPoolPatchProperty [-PoolPatch] <Pool_patch> [-XenProperty] <XenPoolPatchProperty> [[-BestEffort]] [[-SessionOpaqueRef] <string>] [-Ref] <XenRef[Pool_patch]> [-XenProperty] <XenPoolPatchProperty> [[-BestEffort]] [[-SessionOpaqueRef] <string>]
```
### Parameters
| Name | Type | Required | Default Value | Description |
| :--- | :--- | :------- | :------------ | :---------- |
| BestEffort | switch | False |  |  |
| PoolPatch | Pool_patch | True |  |  |
| Ref | XenRef[Pool_patch] | True |  |  |
| SessionOpaqueRef | string | False |  |  |
| XenProperty | XenPoolPatchProperty | True |  |  |
### Procedure
None

### Inputs
```
XenAPI.Pool_patch
XenAPI.XenRef`1[[XenAPI.Pool_patch, XenServer, Version=8.2.3.0, Culture=neutral, PublicKeyToken=d247b8b0ac7959e9]]

```
### Outputs
```
System.Object
```
### Links
None

### Examples

Get-XenPoolPatchProperty [-PoolPatch] <Pool_patch> -XenProperty <XenPoolPatchProperty> [-BestEffort] [-SessionOpaqueRef <string>] [<CommonParameters>]

Get-XenPoolPatchProperty [-Ref] <XenRef[Pool_patch]> -XenProperty <XenPoolPatchProperty> [-BestEffort] [-SessionOpaqueRef <string>] [<CommonParameters>]


## Get-XenPoolProperty

### Synopsis
None

### Description
None

### Syntax
```
Get-XenPoolProperty [-Pool] <Pool> [-XenProperty] <XenPoolProperty> [[-BestEffort]] [[-SessionOpaqueRef] <string>] [-Ref] <XenRef[Pool]> [-XenProperty] <XenPoolProperty> [[-BestEffort]] [[-SessionOpaqueRef] <string>]
```
### Parameters
| Name | Type | Required | Default Value | Description |
| :--- | :--- | :------- | :------------ | :---------- |
| BestEffort | switch | False |  |  |
| Pool | Pool | True |  |  |
| Ref | XenRef[Pool] | True |  |  |
| SessionOpaqueRef | string | False |  |  |
| XenProperty | XenPoolProperty | True |  |  |
### Procedure
None

### Inputs
```
XenAPI.Pool
XenAPI.XenRef`1[[XenAPI.Pool, XenServer, Version=8.2.3.0, Culture=neutral, PublicKeyToken=d247b8b0ac7959e9]]

```
### Outputs
```
System.Object
```
### Links
None

### Examples

Get-XenPoolProperty [-Pool] <Pool> -XenProperty <XenPoolProperty> [-BestEffort] [-SessionOpaqueRef <string>] [<CommonParameters>]

Get-XenPoolProperty [-Ref] <XenRef[Pool]> -XenProperty <XenPoolProperty> [-BestEffort] [-SessionOpaqueRef <string>] [<CommonParameters>]


## Get-XenPoolUpdate

### Synopsis
None

### Description
None

### Syntax
```
Get-XenPoolUpdate [[-Ref] <XenRef[Pool_update]>] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [-Uuid] <guid> [[-BestEffort]] [[-SessionOpaqueRef] <string>] [-Name] <string> [[-BestEffort]] [[-SessionOpaqueRef] <string>]
```
### Parameters
| Name | Type | Required | Default Value | Description |
| :--- | :--- | :------- | :------------ | :---------- |
| BestEffort | switch | False |  |  |
| Name | string | True |  |  |
| Ref | XenRef[Pool_update] | False |  |  |
| SessionOpaqueRef | string | False |  |  |
| Uuid | guid | True |  |  |
### Procedure
None

### Inputs
```
XenAPI.XenRef`1[[XenAPI.Pool_update, XenServer, Version=8.2.3.0, Culture=neutral, PublicKeyToken=d247b8b0ac7959e9]]
System.Guid
System.String

```
### Outputs
```
XenAPI.Pool_update[]

```
### Links
None

### Examples

Get-XenPoolUpdate [[-Ref] <XenRef[Pool_update]>] [-BestEffort] [-SessionOpaqueRef <string>] [<CommonParameters>]

Get-XenPoolUpdate [-Uuid] <guid> [-BestEffort] [-SessionOpaqueRef <string>] [<CommonParameters>]

Get-XenPoolUpdate [-Name] <string> [-BestEffort] [-SessionOpaqueRef <string>] [<CommonParameters>]


## Get-XenPoolUpdateProperty

### Synopsis
None

### Description
None

### Syntax
```
Get-XenPoolUpdateProperty [-PoolUpdate] <Pool_update> [-XenProperty] <XenPoolUpdateProperty> [[-BestEffort]] [[-SessionOpaqueRef] <string>] [-Ref] <XenRef[Pool_update]> [-XenProperty] <XenPoolUpdateProperty> [[-BestEffort]] [[-SessionOpaqueRef] <string>]
```
### Parameters
| Name | Type | Required | Default Value | Description |
| :--- | :--- | :------- | :------------ | :---------- |
| BestEffort | switch | False |  |  |
| PoolUpdate | Pool_update | True |  |  |
| Ref | XenRef[Pool_update] | True |  |  |
| SessionOpaqueRef | string | False |  |  |
| XenProperty | XenPoolUpdateProperty | True |  |  |
### Procedure
None

### Inputs
```
XenAPI.Pool_update
XenAPI.XenRef`1[[XenAPI.Pool_update, XenServer, Version=8.2.3.0, Culture=neutral, PublicKeyToken=d247b8b0ac7959e9]]

```
### Outputs
```
System.Object
```
### Links
None

### Examples

Get-XenPoolUpdateProperty [-PoolUpdate] <Pool_update> -XenProperty <XenPoolUpdateProperty> [-BestEffort] [-SessionOpaqueRef <string>] [<CommonParameters>]

Get-XenPoolUpdateProperty [-Ref] <XenRef[Pool_update]> -XenProperty <XenPoolUpdateProperty> [-BestEffort] [-SessionOpaqueRef <string>] [<CommonParameters>]


## Get-XenPUSB

### Synopsis
None

### Description
None

### Syntax
```
Get-XenPUSB [[-Ref] <XenRef[PUSB]>] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [-Uuid] <guid> [[-BestEffort]] [[-SessionOpaqueRef] <string>]
```
### Parameters
| Name | Type | Required | Default Value | Description |
| :--- | :--- | :------- | :------------ | :---------- |
| BestEffort | switch | False |  |  |
| Ref | XenRef[PUSB] | False |  |  |
| SessionOpaqueRef | string | False |  |  |
| Uuid | guid | True |  |  |
### Procedure
None

### Inputs
```
XenAPI.XenRef`1[[XenAPI.PUSB, XenServer, Version=8.2.3.0, Culture=neutral, PublicKeyToken=d247b8b0ac7959e9]]
System.Guid

```
### Outputs
```
XenAPI.PUSB[]

```
### Links
None

### Examples

Get-XenPUSB [[-Ref] <XenRef[PUSB]>] [-BestEffort] [-SessionOpaqueRef <string>] [<CommonParameters>]

Get-XenPUSB [-Uuid] <guid> [-BestEffort] [-SessionOpaqueRef <string>] [<CommonParameters>]


## Get-XenPUSBProperty

### Synopsis
None

### Description
None

### Syntax
```
Get-XenPUSBProperty [-PUSB] <PUSB> [-XenProperty] <XenPUSBProperty> [[-BestEffort]] [[-SessionOpaqueRef] <string>] [-Ref] <XenRef[PUSB]> [-XenProperty] <XenPUSBProperty> [[-BestEffort]] [[-SessionOpaqueRef] <string>]
```
### Parameters
| Name | Type | Required | Default Value | Description |
| :--- | :--- | :------- | :------------ | :---------- |
| BestEffort | switch | False |  |  |
| PUSB | PUSB | True |  |  |
| Ref | XenRef[PUSB] | True |  |  |
| SessionOpaqueRef | string | False |  |  |
| XenProperty | XenPUSBProperty | True |  |  |
### Procedure
None

### Inputs
```
XenAPI.PUSB
XenAPI.XenRef`1[[XenAPI.PUSB, XenServer, Version=8.2.3.0, Culture=neutral, PublicKeyToken=d247b8b0ac7959e9]]

```
### Outputs
```
System.Object
```
### Links
None

### Examples

Get-XenPUSBProperty [-PUSB] <PUSB> -XenProperty <XenPUSBProperty> [-BestEffort] [-SessionOpaqueRef <string>] [<CommonParameters>]

Get-XenPUSBProperty [-Ref] <XenRef[PUSB]> -XenProperty <XenPUSBProperty> [-BestEffort] [-SessionOpaqueRef <string>] [<CommonParameters>]


## Get-XenPVSCacheStorage

### Synopsis
None

### Description
None

### Syntax
```
Get-XenPVSCacheStorage [[-Ref] <XenRef[PVS_cache_storage]>] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [-Uuid] <guid> [[-BestEffort]] [[-SessionOpaqueRef] <string>]
```
### Parameters
| Name | Type | Required | Default Value | Description |
| :--- | :--- | :------- | :------------ | :---------- |
| BestEffort | switch | False |  |  |
| Ref | XenRef[PVS_cache_storage] | False |  |  |
| SessionOpaqueRef | string | False |  |  |
| Uuid | guid | True |  |  |
### Procedure
None

### Inputs
```
XenAPI.XenRef`1[[XenAPI.PVS_cache_storage, XenServer, Version=8.2.3.0, Culture=neutral, PublicKeyToken=d247b8b0ac7959e9]]
System.Guid

```
### Outputs
```
XenAPI.PVS_cache_storage[]

```
### Links
None

### Examples

Get-XenPVSCacheStorage [[-Ref] <XenRef[PVS_cache_storage]>] [-BestEffort] [-SessionOpaqueRef <string>] [<CommonParameters>]

Get-XenPVSCacheStorage [-Uuid] <guid> [-BestEffort] [-SessionOpaqueRef <string>] [<CommonParameters>]


## Get-XenPVSCacheStorageProperty

### Synopsis
None

### Description
None

### Syntax
```
Get-XenPVSCacheStorageProperty [-PVSCacheStorage] <PVS_cache_storage> [-XenProperty] <XenPVSCacheStorageProperty> [[-BestEffort]] [[-SessionOpaqueRef] <string>] [-Ref] <XenRef[PVS_cache_storage]> [-XenProperty] <XenPVSCacheStorageProperty> [[-BestEffort]] [[-SessionOpaqueRef] <string>]
```
### Parameters
| Name | Type | Required | Default Value | Description |
| :--- | :--- | :------- | :------------ | :---------- |
| BestEffort | switch | False |  |  |
| PVSCacheStorage | PVS_cache_storage | True |  |  |
| Ref | XenRef[PVS_cache_storage] | True |  |  |
| SessionOpaqueRef | string | False |  |  |
| XenProperty | XenPVSCacheStorageProperty | True |  |  |
### Procedure
None

### Inputs
```
XenAPI.PVS_cache_storage
XenAPI.XenRef`1[[XenAPI.PVS_cache_storage, XenServer, Version=8.2.3.0, Culture=neutral, PublicKeyToken=d247b8b0ac7959e9]]

```
### Outputs
```
System.Object
```
### Links
None

### Examples

Get-XenPVSCacheStorageProperty [-PVSCacheStorage] <PVS_cache_storage> -XenProperty <XenPVSCacheStorageProperty> [-BestEffort] [-SessionOpaqueRef <string>] [<CommonParameters>]

Get-XenPVSCacheStorageProperty [-Ref] <XenRef[PVS_cache_storage]> -XenProperty <XenPVSCacheStorageProperty> [-BestEffort] [-SessionOpaqueRef <string>] [<CommonParameters>]


## Get-XenPVSProxy

### Synopsis
None

### Description
None

### Syntax
```
Get-XenPVSProxy [[-Ref] <XenRef[PVS_proxy]>] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [-Uuid] <guid> [[-BestEffort]] [[-SessionOpaqueRef] <string>]
```
### Parameters
| Name | Type | Required | Default Value | Description |
| :--- | :--- | :------- | :------------ | :---------- |
| BestEffort | switch | False |  |  |
| Ref | XenRef[PVS_proxy] | False |  |  |
| SessionOpaqueRef | string | False |  |  |
| Uuid | guid | True |  |  |
### Procedure
None

### Inputs
```
XenAPI.XenRef`1[[XenAPI.PVS_proxy, XenServer, Version=8.2.3.0, Culture=neutral, PublicKeyToken=d247b8b0ac7959e9]]
System.Guid

```
### Outputs
```
XenAPI.PVS_proxy[]

```
### Links
None

### Examples

Get-XenPVSProxy [[-Ref] <XenRef[PVS_proxy]>] [-BestEffort] [-SessionOpaqueRef <string>] [<CommonParameters>]

Get-XenPVSProxy [-Uuid] <guid> [-BestEffort] [-SessionOpaqueRef <string>] [<CommonParameters>]


## Get-XenPVSProxyProperty

### Synopsis
None

### Description
None

### Syntax
```
Get-XenPVSProxyProperty [-PVSProxy] <PVS_proxy> [-XenProperty] <XenPVSProxyProperty> [[-BestEffort]] [[-SessionOpaqueRef] <string>] [-Ref] <XenRef[PVS_proxy]> [-XenProperty] <XenPVSProxyProperty> [[-BestEffort]] [[-SessionOpaqueRef] <string>]
```
### Parameters
| Name | Type | Required | Default Value | Description |
| :--- | :--- | :------- | :------------ | :---------- |
| BestEffort | switch | False |  |  |
| PVSProxy | PVS_proxy | True |  |  |
| Ref | XenRef[PVS_proxy] | True |  |  |
| SessionOpaqueRef | string | False |  |  |
| XenProperty | XenPVSProxyProperty | True |  |  |
### Procedure
None

### Inputs
```
XenAPI.PVS_proxy
XenAPI.XenRef`1[[XenAPI.PVS_proxy, XenServer, Version=8.2.3.0, Culture=neutral, PublicKeyToken=d247b8b0ac7959e9]]

```
### Outputs
```
System.Object
```
### Links
None

### Examples

Get-XenPVSProxyProperty [-PVSProxy] <PVS_proxy> -XenProperty <XenPVSProxyProperty> [-BestEffort] [-SessionOpaqueRef <string>] [<CommonParameters>]

Get-XenPVSProxyProperty [-Ref] <XenRef[PVS_proxy]> -XenProperty <XenPVSProxyProperty> [-BestEffort] [-SessionOpaqueRef <string>] [<CommonParameters>]


## Get-XenPVSServer

### Synopsis
None

### Description
None

### Syntax
```
Get-XenPVSServer [[-Ref] <XenRef[PVS_server]>] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [-Uuid] <guid> [[-BestEffort]] [[-SessionOpaqueRef] <string>]
```
### Parameters
| Name | Type | Required | Default Value | Description |
| :--- | :--- | :------- | :------------ | :---------- |
| BestEffort | switch | False |  |  |
| Ref | XenRef[PVS_server] | False |  |  |
| SessionOpaqueRef | string | False |  |  |
| Uuid | guid | True |  |  |
### Procedure
None

### Inputs
```
XenAPI.XenRef`1[[XenAPI.PVS_server, XenServer, Version=8.2.3.0, Culture=neutral, PublicKeyToken=d247b8b0ac7959e9]]
System.Guid

```
### Outputs
```
XenAPI.PVS_server[]

```
### Links
None

### Examples

Get-XenPVSServer [[-Ref] <XenRef[PVS_server]>] [-BestEffort] [-SessionOpaqueRef <string>] [<CommonParameters>]

Get-XenPVSServer [-Uuid] <guid> [-BestEffort] [-SessionOpaqueRef <string>] [<CommonParameters>]


## Get-XenPVSServerProperty

### Synopsis
None

### Description
None

### Syntax
```
Get-XenPVSServerProperty [-PVSServer] <PVS_server> [-XenProperty] <XenPVSServerProperty> [[-BestEffort]] [[-SessionOpaqueRef] <string>] [-Ref] <XenRef[PVS_server]> [-XenProperty] <XenPVSServerProperty> [[-BestEffort]] [[-SessionOpaqueRef] <string>]
```
### Parameters
| Name | Type | Required | Default Value | Description |
| :--- | :--- | :------- | :------------ | :---------- |
| BestEffort | switch | False |  |  |
| PVSServer | PVS_server | True |  |  |
| Ref | XenRef[PVS_server] | True |  |  |
| SessionOpaqueRef | string | False |  |  |
| XenProperty | XenPVSServerProperty | True |  |  |
### Procedure
None

### Inputs
```
XenAPI.PVS_server
XenAPI.XenRef`1[[XenAPI.PVS_server, XenServer, Version=8.2.3.0, Culture=neutral, PublicKeyToken=d247b8b0ac7959e9]]

```
### Outputs
```
System.Object
```
### Links
None

### Examples

Get-XenPVSServerProperty [-PVSServer] <PVS_server> -XenProperty <XenPVSServerProperty> [-BestEffort] [-SessionOpaqueRef <string>] [<CommonParameters>]

Get-XenPVSServerProperty [-Ref] <XenRef[PVS_server]> -XenProperty <XenPVSServerProperty> [-BestEffort] [-SessionOpaqueRef <string>] [<CommonParameters>]


## Get-XenPVSSite

### Synopsis
None

### Description
None

### Syntax
```
Get-XenPVSSite [[-Ref] <XenRef[PVS_site]>] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [-Uuid] <guid> [[-BestEffort]] [[-SessionOpaqueRef] <string>] [-Name] <string> [[-BestEffort]] [[-SessionOpaqueRef] <string>]
```
### Parameters
| Name | Type | Required | Default Value | Description |
| :--- | :--- | :------- | :------------ | :---------- |
| BestEffort | switch | False |  |  |
| Name | string | True |  |  |
| Ref | XenRef[PVS_site] | False |  |  |
| SessionOpaqueRef | string | False |  |  |
| Uuid | guid | True |  |  |
### Procedure
None

### Inputs
```
XenAPI.XenRef`1[[XenAPI.PVS_site, XenServer, Version=8.2.3.0, Culture=neutral, PublicKeyToken=d247b8b0ac7959e9]]
System.Guid
System.String

```
### Outputs
```
XenAPI.PVS_site[]

```
### Links
None

### Examples

Get-XenPVSSite [[-Ref] <XenRef[PVS_site]>] [-BestEffort] [-SessionOpaqueRef <string>] [<CommonParameters>]

Get-XenPVSSite [-Uuid] <guid> [-BestEffort] [-SessionOpaqueRef <string>] [<CommonParameters>]

Get-XenPVSSite [-Name] <string> [-BestEffort] [-SessionOpaqueRef <string>] [<CommonParameters>]


## Get-XenPVSSiteProperty

### Synopsis
None

### Description
None

### Syntax
```
Get-XenPVSSiteProperty [-PVSSite] <PVS_site> [-XenProperty] <XenPVSSiteProperty> [[-BestEffort]] [[-SessionOpaqueRef] <string>] [-Ref] <XenRef[PVS_site]> [-XenProperty] <XenPVSSiteProperty> [[-BestEffort]] [[-SessionOpaqueRef] <string>]
```
### Parameters
| Name | Type | Required | Default Value | Description |
| :--- | :--- | :------- | :------------ | :---------- |
| BestEffort | switch | False |  |  |
| PVSSite | PVS_site | True |  |  |
| Ref | XenRef[PVS_site] | True |  |  |
| SessionOpaqueRef | string | False |  |  |
| XenProperty | XenPVSSiteProperty | True |  |  |
### Procedure
None

### Inputs
```
XenAPI.PVS_site
XenAPI.XenRef`1[[XenAPI.PVS_site, XenServer, Version=8.2.3.0, Culture=neutral, PublicKeyToken=d247b8b0ac7959e9]]

```
### Outputs
```
System.Object
```
### Links
None

### Examples

Get-XenPVSSiteProperty [-PVSSite] <PVS_site> -XenProperty <XenPVSSiteProperty> [-BestEffort] [-SessionOpaqueRef <string>] [<CommonParameters>]

Get-XenPVSSiteProperty [-Ref] <XenRef[PVS_site]> -XenProperty <XenPVSSiteProperty> [-BestEffort] [-SessionOpaqueRef <string>] [<CommonParameters>]


## Get-XenRole

### Synopsis
None

### Description
None

### Syntax
```
Get-XenRole [[-Ref] <XenRef[Role]>] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [-Uuid] <guid> [[-BestEffort]] [[-SessionOpaqueRef] <string>] [-Name] <string> [[-BestEffort]] [[-SessionOpaqueRef] <string>]
```
### Parameters
| Name | Type | Required | Default Value | Description |
| :--- | :--- | :------- | :------------ | :---------- |
| BestEffort | switch | False |  |  |
| Name | string | True |  |  |
| Ref | XenRef[Role] | False |  |  |
| SessionOpaqueRef | string | False |  |  |
| Uuid | guid | True |  |  |
### Procedure
None

### Inputs
```
XenAPI.XenRef`1[[XenAPI.Role, XenServer, Version=8.2.3.0, Culture=neutral, PublicKeyToken=d247b8b0ac7959e9]]
System.Guid
System.String

```
### Outputs
```
XenAPI.Role[]

```
### Links
None

### Examples

Get-XenRole [[-Ref] <XenRef[Role]>] [-BestEffort] [-SessionOpaqueRef <string>] [<CommonParameters>]

Get-XenRole [-Uuid] <guid> [-BestEffort] [-SessionOpaqueRef <string>] [<CommonParameters>]

Get-XenRole [-Name] <string> [-BestEffort] [-SessionOpaqueRef <string>] [<CommonParameters>]


## Get-XenRoleProperty

### Synopsis
None

### Description
None

### Syntax
```
Get-XenRoleProperty [-Role] <Role> [-XenProperty] <XenRoleProperty> [[-BestEffort]] [[-SessionOpaqueRef] <string>] [-Ref] <XenRef[Role]> [-XenProperty] <XenRoleProperty> [[-BestEffort]] [[-SessionOpaqueRef] <string>]
```
### Parameters
| Name | Type | Required | Default Value | Description |
| :--- | :--- | :------- | :------------ | :---------- |
| BestEffort | switch | False |  |  |
| Ref | XenRef[Role] | True |  |  |
| Role | Role | True |  |  |
| SessionOpaqueRef | string | False |  |  |
| XenProperty | XenRoleProperty | True |  |  |
### Procedure
None

### Inputs
```
XenAPI.Role
XenAPI.XenRef`1[[XenAPI.Role, XenServer, Version=8.2.3.0, Culture=neutral, PublicKeyToken=d247b8b0ac7959e9]]

```
### Outputs
```
System.Object
```
### Links
None

### Examples

Get-XenRoleProperty [-Role] <Role> -XenProperty <XenRoleProperty> [-BestEffort] [-SessionOpaqueRef <string>] [<CommonParameters>]

Get-XenRoleProperty [-Ref] <XenRef[Role]> -XenProperty <XenRoleProperty> [-BestEffort] [-SessionOpaqueRef <string>] [<CommonParameters>]


## Get-XenSDNController

### Synopsis
None

### Description
None

### Syntax
```
Get-XenSDNController [[-Ref] <XenRef[SDN_controller]>] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [-Uuid] <guid> [[-BestEffort]] [[-SessionOpaqueRef] <string>]
```
### Parameters
| Name | Type | Required | Default Value | Description |
| :--- | :--- | :------- | :------------ | :---------- |
| BestEffort | switch | False |  |  |
| Ref | XenRef[SDN_controller] | False |  |  |
| SessionOpaqueRef | string | False |  |  |
| Uuid | guid | True |  |  |
### Procedure
None

### Inputs
```
XenAPI.XenRef`1[[XenAPI.SDN_controller, XenServer, Version=8.2.3.0, Culture=neutral, PublicKeyToken=d247b8b0ac7959e9]]
System.Guid

```
### Outputs
```
XenAPI.SDN_controller[]

```
### Links
None

### Examples

Get-XenSDNController [[-Ref] <XenRef[SDN_controller]>] [-BestEffort] [-SessionOpaqueRef <string>] [<CommonParameters>]

Get-XenSDNController [-Uuid] <guid> [-BestEffort] [-SessionOpaqueRef <string>] [<CommonParameters>]


## Get-XenSDNControllerProperty

### Synopsis
None

### Description
None

### Syntax
```
Get-XenSDNControllerProperty [-SDNController] <SDN_controller> [-XenProperty] <XenSDNControllerProperty> [[-BestEffort]] [[-SessionOpaqueRef] <string>] [-Ref] <XenRef[SDN_controller]> [-XenProperty] <XenSDNControllerProperty> [[-BestEffort]] [[-SessionOpaqueRef] <string>]
```
### Parameters
| Name | Type | Required | Default Value | Description |
| :--- | :--- | :------- | :------------ | :---------- |
| BestEffort | switch | False |  |  |
| Ref | XenRef[SDN_controller] | True |  |  |
| SDNController | SDN_controller | True |  |  |
| SessionOpaqueRef | string | False |  |  |
| XenProperty | XenSDNControllerProperty | True |  |  |
### Procedure
None

### Inputs
```
XenAPI.SDN_controller
XenAPI.XenRef`1[[XenAPI.SDN_controller, XenServer, Version=8.2.3.0, Culture=neutral, PublicKeyToken=d247b8b0ac7959e9]]

```
### Outputs
```
System.Object
```
### Links
None

### Examples

Get-XenSDNControllerProperty [-SDNController] <SDN_controller> -XenProperty <XenSDNControllerProperty> [-BestEffort] [-SessionOpaqueRef <string>] [<CommonParameters>]

Get-XenSDNControllerProperty [-Ref] <XenRef[SDN_controller]> -XenProperty <XenSDNControllerProperty> [-BestEffort] [-SessionOpaqueRef <string>] [<CommonParameters>]


## Get-XenSecret

### Synopsis
None

### Description
None

### Syntax
```
Get-XenSecret [[-Ref] <XenRef[Secret]>] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [-Uuid] <guid> [[-BestEffort]] [[-SessionOpaqueRef] <string>]
```
### Parameters
| Name | Type | Required | Default Value | Description |
| :--- | :--- | :------- | :------------ | :---------- |
| BestEffort | switch | False |  |  |
| Ref | XenRef[Secret] | False |  |  |
| SessionOpaqueRef | string | False |  |  |
| Uuid | guid | True |  |  |
### Procedure
None

### Inputs
```
XenAPI.XenRef`1[[XenAPI.Secret, XenServer, Version=8.2.3.0, Culture=neutral, PublicKeyToken=d247b8b0ac7959e9]]
System.Guid

```
### Outputs
```
XenAPI.Secret[]

```
### Links
None

### Examples

Get-XenSecret [[-Ref] <XenRef[Secret]>] [-BestEffort] [-SessionOpaqueRef <string>] [<CommonParameters>]

Get-XenSecret [-Uuid] <guid> [-BestEffort] [-SessionOpaqueRef <string>] [<CommonParameters>]


## Get-XenSecretProperty

### Synopsis
None

### Description
None

### Syntax
```
Get-XenSecretProperty [-Secret] <Secret> [-XenProperty] <XenSecretProperty> [[-BestEffort]] [[-SessionOpaqueRef] <string>] [-Ref] <XenRef[Secret]> [-XenProperty] <XenSecretProperty> [[-BestEffort]] [[-SessionOpaqueRef] <string>]
```
### Parameters
| Name | Type | Required | Default Value | Description |
| :--- | :--- | :------- | :------------ | :---------- |
| BestEffort | switch | False |  |  |
| Ref | XenRef[Secret] | True |  |  |
| Secret | Secret | True |  |  |
| SessionOpaqueRef | string | False |  |  |
| XenProperty | XenSecretProperty | True |  |  |
### Procedure
None

### Inputs
```
XenAPI.Secret
XenAPI.XenRef`1[[XenAPI.Secret, XenServer, Version=8.2.3.0, Culture=neutral, PublicKeyToken=d247b8b0ac7959e9]]

```
### Outputs
```
System.Object
```
### Links
None

### Examples

Get-XenSecretProperty [-Secret] <Secret> -XenProperty <XenSecretProperty> [-BestEffort] [-SessionOpaqueRef <string>] [<CommonParameters>]

Get-XenSecretProperty [-Ref] <XenRef[Secret]> -XenProperty <XenSecretProperty> [-BestEffort] [-SessionOpaqueRef <string>] [<CommonParameters>]


## Get-XenSession

### Synopsis
None

### Description
None

### Syntax
```
Get-XenSession [[-Ref] <XenRef[Session]>] [-Url] <string> [-Server] <string> [[-Port] <int>] [-UserName] <string>
```
### Parameters
| Name | Type | Required | Default Value | Description |
| :--- | :--- | :------- | :------------ | :---------- |
| Port | int | False |  |  |
| Ref | XenRef[Session] | False |  |  |
| Server | string | True |  |  |
| Url | string | True |  |  |
| UserName | string | True |  |  |
### Procedure
None

### Inputs
```
XenAPI.XenRef`1[[XenAPI.Session, XenServer, Version=8.2.3.0, Culture=neutral, PublicKeyToken=d247b8b0ac7959e9]]

```
### Outputs
```
XenAPI.Session[]

```
### Links
None

### Examples

Get-XenSession [-Ref <XenRef[Session]>] [<CommonParameters>]

Get-XenSession -Url <string> [<CommonParameters>]

Get-XenSession -Server <string> [-Port <int>] [<CommonParameters>]

Get-XenSession -UserName <string> [<CommonParameters>]


## Get-XenSM

### Synopsis
None

### Description
None

### Syntax
```
Get-XenSM [[-Ref] <XenRef[SM]>] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [-Uuid] <guid> [[-BestEffort]] [[-SessionOpaqueRef] <string>] [-Name] <string> [[-BestEffort]] [[-SessionOpaqueRef] <string>]
```
### Parameters
| Name | Type | Required | Default Value | Description |
| :--- | :--- | :------- | :------------ | :---------- |
| BestEffort | switch | False |  |  |
| Name | string | True |  |  |
| Ref | XenRef[SM] | False |  |  |
| SessionOpaqueRef | string | False |  |  |
| Uuid | guid | True |  |  |
### Procedure
None

### Inputs
```
XenAPI.XenRef`1[[XenAPI.SM, XenServer, Version=8.2.3.0, Culture=neutral, PublicKeyToken=d247b8b0ac7959e9]]
System.Guid
System.String

```
### Outputs
```
XenAPI.SM[]

```
### Links
None

### Examples

Get-XenSM [[-Ref] <XenRef[SM]>] [-BestEffort] [-SessionOpaqueRef <string>] [<CommonParameters>]

Get-XenSM [-Uuid] <guid> [-BestEffort] [-SessionOpaqueRef <string>] [<CommonParameters>]

Get-XenSM [-Name] <string> [-BestEffort] [-SessionOpaqueRef <string>] [<CommonParameters>]


## Get-XenSMProperty

### Synopsis
None

### Description
None

### Syntax
```
Get-XenSMProperty [-SM] <SM> [-XenProperty] <XenSMProperty> [[-BestEffort]] [[-SessionOpaqueRef] <string>] [-Ref] <XenRef[SM]> [-XenProperty] <XenSMProperty> [[-BestEffort]] [[-SessionOpaqueRef] <string>]
```
### Parameters
| Name | Type | Required | Default Value | Description |
| :--- | :--- | :------- | :------------ | :---------- |
| BestEffort | switch | False |  |  |
| Ref | XenRef[SM] | True |  |  |
| SM | SM | True |  |  |
| SessionOpaqueRef | string | False |  |  |
| XenProperty | XenSMProperty | True |  |  |
### Procedure
None

### Inputs
```
XenAPI.SM
XenAPI.XenRef`1[[XenAPI.SM, XenServer, Version=8.2.3.0, Culture=neutral, PublicKeyToken=d247b8b0ac7959e9]]

```
### Outputs
```
System.Object
```
### Links
None

### Examples

Get-XenSMProperty [-SM] <SM> -XenProperty <XenSMProperty> [-BestEffort] [-SessionOpaqueRef <string>] [<CommonParameters>]

Get-XenSMProperty [-Ref] <XenRef[SM]> -XenProperty <XenSMProperty> [-BestEffort] [-SessionOpaqueRef <string>] [<CommonParameters>]


## Get-XenSR

### Synopsis
None

### Description
None

### Syntax
```
Get-XenSR [[-Ref] <XenRef[SR]>] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [-Uuid] <guid> [[-BestEffort]] [[-SessionOpaqueRef] <string>] [-Name] <string> [[-BestEffort]] [[-SessionOpaqueRef] <string>]
```
### Parameters
| Name | Type | Required | Default Value | Description |
| :--- | :--- | :------- | :------------ | :---------- |
| BestEffort | switch | False |  |  |
| Name | string | True |  |  |
| Ref | XenRef[SR] | False |  |  |
| SessionOpaqueRef | string | False |  |  |
| Uuid | guid | True |  |  |
### Procedure
None

### Inputs
```
XenAPI.XenRef`1[[XenAPI.SR, XenServer, Version=8.2.3.0, Culture=neutral, PublicKeyToken=d247b8b0ac7959e9]]
System.Guid
System.String

```
### Outputs
```
XenAPI.SR[]

```
### Links
None

### Examples

Get-XenSR [[-Ref] <XenRef[SR]>] [-BestEffort] [-SessionOpaqueRef <string>] [<CommonParameters>]

Get-XenSR [-Uuid] <guid> [-BestEffort] [-SessionOpaqueRef <string>] [<CommonParameters>]

Get-XenSR [-Name] <string> [-BestEffort] [-SessionOpaqueRef <string>] [<CommonParameters>]


## Get-XenSRProperty

### Synopsis
None

### Description
None

### Syntax
```
Get-XenSRProperty [-SR] <SR> [-XenProperty] <XenSRProperty> [[-BestEffort]] [[-SessionOpaqueRef] <string>] [-Ref] <XenRef[SR]> [-XenProperty] <XenSRProperty> [[-BestEffort]] [[-SessionOpaqueRef] <string>]
```
### Parameters
| Name | Type | Required | Default Value | Description |
| :--- | :--- | :------- | :------------ | :---------- |
| BestEffort | switch | False |  |  |
| Ref | XenRef[SR] | True |  |  |
| SR | SR | True |  |  |
| SessionOpaqueRef | string | False |  |  |
| XenProperty | XenSRProperty | True |  |  |
### Procedure
None

### Inputs
```
XenAPI.SR
XenAPI.XenRef`1[[XenAPI.SR, XenServer, Version=8.2.3.0, Culture=neutral, PublicKeyToken=d247b8b0ac7959e9]]

```
### Outputs
```
System.Object
```
### Links
None

### Examples

Get-XenSRProperty [-SR] <SR> -XenProperty <XenSRProperty> [-BestEffort] [-SessionOpaqueRef <string>] [<CommonParameters>]

Get-XenSRProperty [-Ref] <XenRef[SR]> -XenProperty <XenSRProperty> [-BestEffort] [-SessionOpaqueRef <string>] [<CommonParameters>]


## Get-XenSubject

### Synopsis
None

### Description
None

### Syntax
```
Get-XenSubject [[-Ref] <XenRef[Subject]>] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [-Uuid] <guid> [[-BestEffort]] [[-SessionOpaqueRef] <string>]
```
### Parameters
| Name | Type | Required | Default Value | Description |
| :--- | :--- | :------- | :------------ | :---------- |
| BestEffort | switch | False |  |  |
| Ref | XenRef[Subject] | False |  |  |
| SessionOpaqueRef | string | False |  |  |
| Uuid | guid | True |  |  |
### Procedure
None

### Inputs
```
XenAPI.XenRef`1[[XenAPI.Subject, XenServer, Version=8.2.3.0, Culture=neutral, PublicKeyToken=d247b8b0ac7959e9]]
System.Guid

```
### Outputs
```
XenAPI.Subject[]

```
### Links
None

### Examples

Get-XenSubject [[-Ref] <XenRef[Subject]>] [-BestEffort] [-SessionOpaqueRef <string>] [<CommonParameters>]

Get-XenSubject [-Uuid] <guid> [-BestEffort] [-SessionOpaqueRef <string>] [<CommonParameters>]


## Get-XenSubjectProperty

### Synopsis
None

### Description
None

### Syntax
```
Get-XenSubjectProperty [-Subject] <Subject> [-XenProperty] <XenSubjectProperty> [[-BestEffort]] [[-SessionOpaqueRef] <string>] [-Ref] <XenRef[Subject]> [-XenProperty] <XenSubjectProperty> [[-BestEffort]] [[-SessionOpaqueRef] <string>]
```
### Parameters
| Name | Type | Required | Default Value | Description |
| :--- | :--- | :------- | :------------ | :---------- |
| BestEffort | switch | False |  |  |
| Ref | XenRef[Subject] | True |  |  |
| SessionOpaqueRef | string | False |  |  |
| Subject | Subject | True |  |  |
| XenProperty | XenSubjectProperty | True |  |  |
### Procedure
None

### Inputs
```
XenAPI.Subject
XenAPI.XenRef`1[[XenAPI.Subject, XenServer, Version=8.2.3.0, Culture=neutral, PublicKeyToken=d247b8b0ac7959e9]]

```
### Outputs
```
System.Object
```
### Links
None

### Examples

Get-XenSubjectProperty [-Subject] <Subject> -XenProperty <XenSubjectProperty> [-BestEffort] [-SessionOpaqueRef <string>] [<CommonParameters>]

Get-XenSubjectProperty [-Ref] <XenRef[Subject]> -XenProperty <XenSubjectProperty> [-BestEffort] [-SessionOpaqueRef <string>] [<CommonParameters>]


## Get-XenTask

### Synopsis
None

### Description
None

### Syntax
```
Get-XenTask [[-Ref] <XenRef[Task]>] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [-Uuid] <guid> [[-BestEffort]] [[-SessionOpaqueRef] <string>] [-Name] <string> [[-BestEffort]] [[-SessionOpaqueRef] <string>]
```
### Parameters
| Name | Type | Required | Default Value | Description |
| :--- | :--- | :------- | :------------ | :---------- |
| BestEffort | switch | False |  |  |
| Name | string | True |  |  |
| Ref | XenRef[Task] | False |  |  |
| SessionOpaqueRef | string | False |  |  |
| Uuid | guid | True |  |  |
### Procedure
None

### Inputs
```
XenAPI.XenRef`1[[XenAPI.Task, XenServer, Version=8.2.3.0, Culture=neutral, PublicKeyToken=d247b8b0ac7959e9]]
System.Guid
System.String

```
### Outputs
```
XenAPI.Task[]

```
### Links
None

### Examples

Get-XenTask [[-Ref] <XenRef[Task]>] [-BestEffort] [-SessionOpaqueRef <string>] [<CommonParameters>]

Get-XenTask [-Uuid] <guid> [-BestEffort] [-SessionOpaqueRef <string>] [<CommonParameters>]

Get-XenTask [-Name] <string> [-BestEffort] [-SessionOpaqueRef <string>] [<CommonParameters>]


## Get-XenTaskProperty

### Synopsis
None

### Description
None

### Syntax
```
Get-XenTaskProperty [-Task] <Task> [-XenProperty] <XenTaskProperty> [[-BestEffort]] [[-SessionOpaqueRef] <string>] [-Ref] <XenRef[Task]> [-XenProperty] <XenTaskProperty> [[-BestEffort]] [[-SessionOpaqueRef] <string>]
```
### Parameters
| Name | Type | Required | Default Value | Description |
| :--- | :--- | :------- | :------------ | :---------- |
| BestEffort | switch | False |  |  |
| Ref | XenRef[Task] | True |  |  |
| SessionOpaqueRef | string | False |  |  |
| Task | Task | True |  |  |
| XenProperty | XenTaskProperty | True |  |  |
### Procedure
None

### Inputs
```
XenAPI.Task
XenAPI.XenRef`1[[XenAPI.Task, XenServer, Version=8.2.3.0, Culture=neutral, PublicKeyToken=d247b8b0ac7959e9]]

```
### Outputs
```
System.Object
```
### Links
None

### Examples

Get-XenTaskProperty [-Task] <Task> -XenProperty <XenTaskProperty> [-BestEffort] [-SessionOpaqueRef <string>] [<CommonParameters>]

Get-XenTaskProperty [-Ref] <XenRef[Task]> -XenProperty <XenTaskProperty> [-BestEffort] [-SessionOpaqueRef <string>] [<CommonParameters>]


## Get-XenTunnel

### Synopsis
None

### Description
None

### Syntax
```
Get-XenTunnel [[-Ref] <XenRef[Tunnel]>] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [-Uuid] <guid> [[-BestEffort]] [[-SessionOpaqueRef] <string>]
```
### Parameters
| Name | Type | Required | Default Value | Description |
| :--- | :--- | :------- | :------------ | :---------- |
| BestEffort | switch | False |  |  |
| Ref | XenRef[Tunnel] | False |  |  |
| SessionOpaqueRef | string | False |  |  |
| Uuid | guid | True |  |  |
### Procedure
None

### Inputs
```
XenAPI.XenRef`1[[XenAPI.Tunnel, XenServer, Version=8.2.3.0, Culture=neutral, PublicKeyToken=d247b8b0ac7959e9]]
System.Guid

```
### Outputs
```
XenAPI.Tunnel[]

```
### Links
None

### Examples

Get-XenTunnel [[-Ref] <XenRef[Tunnel]>] [-BestEffort] [-SessionOpaqueRef <string>] [<CommonParameters>]

Get-XenTunnel [-Uuid] <guid> [-BestEffort] [-SessionOpaqueRef <string>] [<CommonParameters>]


## Get-XenTunnelProperty

### Synopsis
None

### Description
None

### Syntax
```
Get-XenTunnelProperty [-Tunnel] <Tunnel> [-XenProperty] <XenTunnelProperty> [[-BestEffort]] [[-SessionOpaqueRef] <string>] [-Ref] <XenRef[Tunnel]> [-XenProperty] <XenTunnelProperty> [[-BestEffort]] [[-SessionOpaqueRef] <string>]
```
### Parameters
| Name | Type | Required | Default Value | Description |
| :--- | :--- | :------- | :------------ | :---------- |
| BestEffort | switch | False |  |  |
| Ref | XenRef[Tunnel] | True |  |  |
| SessionOpaqueRef | string | False |  |  |
| Tunnel | Tunnel | True |  |  |
| XenProperty | XenTunnelProperty | True |  |  |
### Procedure
None

### Inputs
```
XenAPI.Tunnel
XenAPI.XenRef`1[[XenAPI.Tunnel, XenServer, Version=8.2.3.0, Culture=neutral, PublicKeyToken=d247b8b0ac7959e9]]

```
### Outputs
```
System.Object
```
### Links
None

### Examples

Get-XenTunnelProperty [-Tunnel] <Tunnel> -XenProperty <XenTunnelProperty> [-BestEffort] [-SessionOpaqueRef <string>] [<CommonParameters>]

Get-XenTunnelProperty [-Ref] <XenRef[Tunnel]> -XenProperty <XenTunnelProperty> [-BestEffort] [-SessionOpaqueRef <string>] [<CommonParameters>]


## Get-XenUSBGroup

### Synopsis
None

### Description
None

### Syntax
```
Get-XenUSBGroup [[-Ref] <XenRef[USB_group]>] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [-Uuid] <guid> [[-BestEffort]] [[-SessionOpaqueRef] <string>] [-Name] <string> [[-BestEffort]] [[-SessionOpaqueRef] <string>]
```
### Parameters
| Name | Type | Required | Default Value | Description |
| :--- | :--- | :------- | :------------ | :---------- |
| BestEffort | switch | False |  |  |
| Name | string | True |  |  |
| Ref | XenRef[USB_group] | False |  |  |
| SessionOpaqueRef | string | False |  |  |
| Uuid | guid | True |  |  |
### Procedure
None

### Inputs
```
XenAPI.XenRef`1[[XenAPI.USB_group, XenServer, Version=8.2.3.0, Culture=neutral, PublicKeyToken=d247b8b0ac7959e9]]
System.Guid
System.String

```
### Outputs
```
XenAPI.USB_group[]

```
### Links
None

### Examples

Get-XenUSBGroup [[-Ref] <XenRef[USB_group]>] [-BestEffort] [-SessionOpaqueRef <string>] [<CommonParameters>]

Get-XenUSBGroup [-Uuid] <guid> [-BestEffort] [-SessionOpaqueRef <string>] [<CommonParameters>]

Get-XenUSBGroup [-Name] <string> [-BestEffort] [-SessionOpaqueRef <string>] [<CommonParameters>]


## Get-XenUSBGroupProperty

### Synopsis
None

### Description
None

### Syntax
```
Get-XenUSBGroupProperty [-USBGroup] <USB_group> [-XenProperty] <XenUSBGroupProperty> [[-BestEffort]] [[-SessionOpaqueRef] <string>] [-Ref] <XenRef[USB_group]> [-XenProperty] <XenUSBGroupProperty> [[-BestEffort]] [[-SessionOpaqueRef] <string>]
```
### Parameters
| Name | Type | Required | Default Value | Description |
| :--- | :--- | :------- | :------------ | :---------- |
| BestEffort | switch | False |  |  |
| Ref | XenRef[USB_group] | True |  |  |
| SessionOpaqueRef | string | False |  |  |
| USBGroup | USB_group | True |  |  |
| XenProperty | XenUSBGroupProperty | True |  |  |
### Procedure
None

### Inputs
```
XenAPI.USB_group
XenAPI.XenRef`1[[XenAPI.USB_group, XenServer, Version=8.2.3.0, Culture=neutral, PublicKeyToken=d247b8b0ac7959e9]]

```
### Outputs
```
System.Object
```
### Links
None

### Examples

Get-XenUSBGroupProperty [-USBGroup] <USB_group> -XenProperty <XenUSBGroupProperty> [-BestEffort] [-SessionOpaqueRef <string>] [<CommonParameters>]

Get-XenUSBGroupProperty [-Ref] <XenRef[USB_group]> -XenProperty <XenUSBGroupProperty> [-BestEffort] [-SessionOpaqueRef <string>] [<CommonParameters>]


## Get-XenUserProperty

### Synopsis
None

### Description
None

### Syntax
```
Get-XenUserProperty [-User] <User> [-XenProperty] <XenUserProperty> [[-BestEffort]] [[-SessionOpaqueRef] <string>] [-Ref] <XenRef[User]> [-XenProperty] <XenUserProperty> [[-BestEffort]] [[-SessionOpaqueRef] <string>]
```
### Parameters
| Name | Type | Required | Default Value | Description |
| :--- | :--- | :------- | :------------ | :---------- |
| BestEffort | switch | False |  |  |
| Ref | XenRef[User] | True |  |  |
| SessionOpaqueRef | string | False |  |  |
| User | User | True |  |  |
| XenProperty | XenUserProperty | True |  |  |
### Procedure
None

### Inputs
```
XenAPI.User
XenAPI.XenRef`1[[XenAPI.User, XenServer, Version=8.2.3.0, Culture=neutral, PublicKeyToken=d247b8b0ac7959e9]]

```
### Outputs
```
System.Object
```
### Links
None

### Examples

Get-XenUserProperty [-User] <User> -XenProperty <XenUserProperty> [-BestEffort] [-SessionOpaqueRef <string>] [<CommonParameters>]

Get-XenUserProperty [-Ref] <XenRef[User]> -XenProperty <XenUserProperty> [-BestEffort] [-SessionOpaqueRef <string>] [<CommonParameters>]


## Get-XenVBD

### Synopsis
None

### Description
None

### Syntax
```
Get-XenVBD [[-Ref] <XenRef[VBD]>] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [-Uuid] <guid> [[-BestEffort]] [[-SessionOpaqueRef] <string>]
```
### Parameters
| Name | Type | Required | Default Value | Description |
| :--- | :--- | :------- | :------------ | :---------- |
| BestEffort | switch | False |  |  |
| Ref | XenRef[VBD] | False |  |  |
| SessionOpaqueRef | string | False |  |  |
| Uuid | guid | True |  |  |
### Procedure
None

### Inputs
```
XenAPI.XenRef`1[[XenAPI.VBD, XenServer, Version=8.2.3.0, Culture=neutral, PublicKeyToken=d247b8b0ac7959e9]]
System.Guid

```
### Outputs
```
XenAPI.VBD[]

```
### Links
None

### Examples

Get-XenVBD [[-Ref] <XenRef[VBD]>] [-BestEffort] [-SessionOpaqueRef <string>] [<CommonParameters>]

Get-XenVBD [-Uuid] <guid> [-BestEffort] [-SessionOpaqueRef <string>] [<CommonParameters>]


## Get-XenVBDMetrics

### Synopsis
None

### Description
None

### Syntax
```
Get-XenVBDMetrics [[-Ref] <XenRef[VBD_metrics]>] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [-Uuid] <guid> [[-BestEffort]] [[-SessionOpaqueRef] <string>]
```
### Parameters
| Name | Type | Required | Default Value | Description |
| :--- | :--- | :------- | :------------ | :---------- |
| BestEffort | switch | False |  |  |
| Ref | XenRef[VBD_metrics] | False |  |  |
| SessionOpaqueRef | string | False |  |  |
| Uuid | guid | True |  |  |
### Procedure
None

### Inputs
```
XenAPI.XenRef`1[[XenAPI.VBD_metrics, XenServer, Version=8.2.3.0, Culture=neutral, PublicKeyToken=d247b8b0ac7959e9]]
System.Guid

```
### Outputs
```
XenAPI.VBD_metrics[]

```
### Links
None

### Examples

Get-XenVBDMetrics [[-Ref] <XenRef[VBD_metrics]>] [-BestEffort] [-SessionOpaqueRef <string>] [<CommonParameters>]

Get-XenVBDMetrics [-Uuid] <guid> [-BestEffort] [-SessionOpaqueRef <string>] [<CommonParameters>]


## Get-XenVBDMetricsProperty

### Synopsis
None

### Description
None

### Syntax
```
Get-XenVBDMetricsProperty [-VBDMetrics] <VBD_metrics> [-XenProperty] <XenVBDMetricsProperty> [[-BestEffort]] [[-SessionOpaqueRef] <string>] [-Ref] <XenRef[VBD_metrics]> [-XenProperty] <XenVBDMetricsProperty> [[-BestEffort]] [[-SessionOpaqueRef] <string>]
```
### Parameters
| Name | Type | Required | Default Value | Description |
| :--- | :--- | :------- | :------------ | :---------- |
| BestEffort | switch | False |  |  |
| Ref | XenRef[VBD_metrics] | True |  |  |
| SessionOpaqueRef | string | False |  |  |
| VBDMetrics | VBD_metrics | True |  |  |
| XenProperty | XenVBDMetricsProperty | True |  |  |
### Procedure
None

### Inputs
```
XenAPI.VBD_metrics
XenAPI.XenRef`1[[XenAPI.VBD_metrics, XenServer, Version=8.2.3.0, Culture=neutral, PublicKeyToken=d247b8b0ac7959e9]]

```
### Outputs
```
System.Object
```
### Links
None

### Examples

Get-XenVBDMetricsProperty [-VBDMetrics] <VBD_metrics> -XenProperty <XenVBDMetricsProperty> [-BestEffort] [-SessionOpaqueRef <string>] [<CommonParameters>]

Get-XenVBDMetricsProperty [-Ref] <XenRef[VBD_metrics]> -XenProperty <XenVBDMetricsProperty> [-BestEffort] [-SessionOpaqueRef <string>] [<CommonParameters>]


## Get-XenVBDProperty

### Synopsis
None

### Description
None

### Syntax
```
Get-XenVBDProperty [-VBD] <VBD> [-XenProperty] <XenVBDProperty> [[-BestEffort]] [[-SessionOpaqueRef] <string>] [-Ref] <XenRef[VBD]> [-XenProperty] <XenVBDProperty> [[-BestEffort]] [[-SessionOpaqueRef] <string>]
```
### Parameters
| Name | Type | Required | Default Value | Description |
| :--- | :--- | :------- | :------------ | :---------- |
| BestEffort | switch | False |  |  |
| Ref | XenRef[VBD] | True |  |  |
| SessionOpaqueRef | string | False |  |  |
| VBD | VBD | True |  |  |
| XenProperty | XenVBDProperty | True |  |  |
### Procedure
None

### Inputs
```
XenAPI.VBD
XenAPI.XenRef`1[[XenAPI.VBD, XenServer, Version=8.2.3.0, Culture=neutral, PublicKeyToken=d247b8b0ac7959e9]]

```
### Outputs
```
System.Object
```
### Links
None

### Examples

Get-XenVBDProperty [-VBD] <VBD> -XenProperty <XenVBDProperty> [-BestEffort] [-SessionOpaqueRef <string>] [<CommonParameters>]

Get-XenVBDProperty [-Ref] <XenRef[VBD]> -XenProperty <XenVBDProperty> [-BestEffort] [-SessionOpaqueRef <string>] [<CommonParameters>]


## Get-XenVDI

### Synopsis
None

### Description
None

### Syntax
```
Get-XenVDI [[-Ref] <XenRef[VDI]>] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [-Uuid] <guid> [[-BestEffort]] [[-SessionOpaqueRef] <string>] [-Name] <string> [[-BestEffort]] [[-SessionOpaqueRef] <string>]
```
### Parameters
| Name | Type | Required | Default Value | Description |
| :--- | :--- | :------- | :------------ | :---------- |
| BestEffort | switch | False |  |  |
| Name | string | True |  |  |
| Ref | XenRef[VDI] | False |  |  |
| SessionOpaqueRef | string | False |  |  |
| Uuid | guid | True |  |  |
### Procedure
None

### Inputs
```
XenAPI.XenRef`1[[XenAPI.VDI, XenServer, Version=8.2.3.0, Culture=neutral, PublicKeyToken=d247b8b0ac7959e9]]
System.Guid
System.String

```
### Outputs
```
XenAPI.VDI[]

```
### Links
None

### Examples

Get-XenVDI [[-Ref] <XenRef[VDI]>] [-BestEffort] [-SessionOpaqueRef <string>] [<CommonParameters>]

Get-XenVDI [-Uuid] <guid> [-BestEffort] [-SessionOpaqueRef <string>] [<CommonParameters>]

Get-XenVDI [-Name] <string> [-BestEffort] [-SessionOpaqueRef <string>] [<CommonParameters>]


## Get-XenVDIProperty

### Synopsis
None

### Description
None

### Syntax
```
Get-XenVDIProperty [-VDI] <VDI> [-XenProperty] <XenVDIProperty> [[-BestEffort]] [[-SessionOpaqueRef] <string>] [-Ref] <XenRef[VDI]> [-XenProperty] <XenVDIProperty> [[-BestEffort]] [[-SessionOpaqueRef] <string>]
```
### Parameters
| Name | Type | Required | Default Value | Description |
| :--- | :--- | :------- | :------------ | :---------- |
| BestEffort | switch | False |  |  |
| Ref | XenRef[VDI] | True |  |  |
| SessionOpaqueRef | string | False |  |  |
| VDI | VDI | True |  |  |
| XenProperty | XenVDIProperty | True |  |  |
### Procedure
None

### Inputs
```
XenAPI.VDI
XenAPI.XenRef`1[[XenAPI.VDI, XenServer, Version=8.2.3.0, Culture=neutral, PublicKeyToken=d247b8b0ac7959e9]]

```
### Outputs
```
System.Object
```
### Links
None

### Examples

Get-XenVDIProperty [-VDI] <VDI> -XenProperty <XenVDIProperty> [-BestEffort] [-SessionOpaqueRef <string>] [<CommonParameters>]

Get-XenVDIProperty [-Ref] <XenRef[VDI]> -XenProperty <XenVDIProperty> [-BestEffort] [-SessionOpaqueRef <string>] [<CommonParameters>]


## Get-XenVGPU

### Synopsis
None

### Description
None

### Syntax
```
Get-XenVGPU [[-Ref] <XenRef[VGPU]>] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [-Uuid] <guid> [[-BestEffort]] [[-SessionOpaqueRef] <string>]
```
### Parameters
| Name | Type | Required | Default Value | Description |
| :--- | :--- | :------- | :------------ | :---------- |
| BestEffort | switch | False |  |  |
| Ref | XenRef[VGPU] | False |  |  |
| SessionOpaqueRef | string | False |  |  |
| Uuid | guid | True |  |  |
### Procedure
None

### Inputs
```
XenAPI.XenRef`1[[XenAPI.VGPU, XenServer, Version=8.2.3.0, Culture=neutral, PublicKeyToken=d247b8b0ac7959e9]]
System.Guid

```
### Outputs
```
XenAPI.VGPU[]

```
### Links
None

### Examples

Get-XenVGPU [[-Ref] <XenRef[VGPU]>] [-BestEffort] [-SessionOpaqueRef <string>] [<CommonParameters>]

Get-XenVGPU [-Uuid] <guid> [-BestEffort] [-SessionOpaqueRef <string>] [<CommonParameters>]


## Get-XenVGPUProperty

### Synopsis
None

### Description
None

### Syntax
```
Get-XenVGPUProperty [-VGPU] <VGPU> [-XenProperty] <XenVGPUProperty> [[-BestEffort]] [[-SessionOpaqueRef] <string>] [-Ref] <XenRef[VGPU]> [-XenProperty] <XenVGPUProperty> [[-BestEffort]] [[-SessionOpaqueRef] <string>]
```
### Parameters
| Name | Type | Required | Default Value | Description |
| :--- | :--- | :------- | :------------ | :---------- |
| BestEffort | switch | False |  |  |
| Ref | XenRef[VGPU] | True |  |  |
| SessionOpaqueRef | string | False |  |  |
| VGPU | VGPU | True |  |  |
| XenProperty | XenVGPUProperty | True |  |  |
### Procedure
None

### Inputs
```
XenAPI.VGPU
XenAPI.XenRef`1[[XenAPI.VGPU, XenServer, Version=8.2.3.0, Culture=neutral, PublicKeyToken=d247b8b0ac7959e9]]

```
### Outputs
```
System.Object
```
### Links
None

### Examples

Get-XenVGPUProperty [-VGPU] <VGPU> -XenProperty <XenVGPUProperty> [-BestEffort] [-SessionOpaqueRef <string>] [<CommonParameters>]

Get-XenVGPUProperty [-Ref] <XenRef[VGPU]> -XenProperty <XenVGPUProperty> [-BestEffort] [-SessionOpaqueRef <string>] [<CommonParameters>]


## Get-XenVGPUType

### Synopsis
None

### Description
None

### Syntax
```
Get-XenVGPUType [[-Ref] <XenRef[VGPU_type]>] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [-Uuid] <guid> [[-BestEffort]] [[-SessionOpaqueRef] <string>]
```
### Parameters
| Name | Type | Required | Default Value | Description |
| :--- | :--- | :------- | :------------ | :---------- |
| BestEffort | switch | False |  |  |
| Ref | XenRef[VGPU_type] | False |  |  |
| SessionOpaqueRef | string | False |  |  |
| Uuid | guid | True |  |  |
### Procedure
None

### Inputs
```
XenAPI.XenRef`1[[XenAPI.VGPU_type, XenServer, Version=8.2.3.0, Culture=neutral, PublicKeyToken=d247b8b0ac7959e9]]
System.Guid

```
### Outputs
```
XenAPI.VGPU_type[]

```
### Links
None

### Examples

Get-XenVGPUType [[-Ref] <XenRef[VGPU_type]>] [-BestEffort] [-SessionOpaqueRef <string>] [<CommonParameters>]

Get-XenVGPUType [-Uuid] <guid> [-BestEffort] [-SessionOpaqueRef <string>] [<CommonParameters>]


## Get-XenVGPUTypeProperty

### Synopsis
None

### Description
None

### Syntax
```
Get-XenVGPUTypeProperty [-VGPUType] <VGPU_type> [-XenProperty] <XenVGPUTypeProperty> [[-BestEffort]] [[-SessionOpaqueRef] <string>] [-Ref] <XenRef[VGPU_type]> [-XenProperty] <XenVGPUTypeProperty> [[-BestEffort]] [[-SessionOpaqueRef] <string>]
```
### Parameters
| Name | Type | Required | Default Value | Description |
| :--- | :--- | :------- | :------------ | :---------- |
| BestEffort | switch | False |  |  |
| Ref | XenRef[VGPU_type] | True |  |  |
| SessionOpaqueRef | string | False |  |  |
| VGPUType | VGPU_type | True |  |  |
| XenProperty | XenVGPUTypeProperty | True |  |  |
### Procedure
None

### Inputs
```
XenAPI.VGPU_type
XenAPI.XenRef`1[[XenAPI.VGPU_type, XenServer, Version=8.2.3.0, Culture=neutral, PublicKeyToken=d247b8b0ac7959e9]]

```
### Outputs
```
System.Object
```
### Links
None

### Examples

Get-XenVGPUTypeProperty [-VGPUType] <VGPU_type> -XenProperty <XenVGPUTypeProperty> [-BestEffort] [-SessionOpaqueRef <string>] [<CommonParameters>]

Get-XenVGPUTypeProperty [-Ref] <XenRef[VGPU_type]> -XenProperty <XenVGPUTypeProperty> [-BestEffort] [-SessionOpaqueRef <string>] [<CommonParameters>]


## Get-XenVIF

### Synopsis
None

### Description
None

### Syntax
```
Get-XenVIF [[-Ref] <XenRef[VIF]>] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [-Uuid] <guid> [[-BestEffort]] [[-SessionOpaqueRef] <string>]
```
### Parameters
| Name | Type | Required | Default Value | Description |
| :--- | :--- | :------- | :------------ | :---------- |
| BestEffort | switch | False |  |  |
| Ref | XenRef[VIF] | False |  |  |
| SessionOpaqueRef | string | False |  |  |
| Uuid | guid | True |  |  |
### Procedure
None

### Inputs
```
XenAPI.XenRef`1[[XenAPI.VIF, XenServer, Version=8.2.3.0, Culture=neutral, PublicKeyToken=d247b8b0ac7959e9]]
System.Guid

```
### Outputs
```
XenAPI.VIF[]

```
### Links
None

### Examples

Get-XenVIF [[-Ref] <XenRef[VIF]>] [-BestEffort] [-SessionOpaqueRef <string>] [<CommonParameters>]

Get-XenVIF [-Uuid] <guid> [-BestEffort] [-SessionOpaqueRef <string>] [<CommonParameters>]


## Get-XenVIFMetrics

### Synopsis
None

### Description
None

### Syntax
```
Get-XenVIFMetrics [[-Ref] <XenRef[VIF_metrics]>] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [-Uuid] <guid> [[-BestEffort]] [[-SessionOpaqueRef] <string>]
```
### Parameters
| Name | Type | Required | Default Value | Description |
| :--- | :--- | :------- | :------------ | :---------- |
| BestEffort | switch | False |  |  |
| Ref | XenRef[VIF_metrics] | False |  |  |
| SessionOpaqueRef | string | False |  |  |
| Uuid | guid | True |  |  |
### Procedure
None

### Inputs
```
XenAPI.XenRef`1[[XenAPI.VIF_metrics, XenServer, Version=8.2.3.0, Culture=neutral, PublicKeyToken=d247b8b0ac7959e9]]
System.Guid

```
### Outputs
```
XenAPI.VIF_metrics[]

```
### Links
None

### Examples

Get-XenVIFMetrics [[-Ref] <XenRef[VIF_metrics]>] [-BestEffort] [-SessionOpaqueRef <string>] [<CommonParameters>]

Get-XenVIFMetrics [-Uuid] <guid> [-BestEffort] [-SessionOpaqueRef <string>] [<CommonParameters>]


## Get-XenVIFMetricsProperty

### Synopsis
None

### Description
None

### Syntax
```
Get-XenVIFMetricsProperty [-VIFMetrics] <VIF_metrics> [-XenProperty] <XenVIFMetricsProperty> [[-BestEffort]] [[-SessionOpaqueRef] <string>] [-Ref] <XenRef[VIF_metrics]> [-XenProperty] <XenVIFMetricsProperty> [[-BestEffort]] [[-SessionOpaqueRef] <string>]
```
### Parameters
| Name | Type | Required | Default Value | Description |
| :--- | :--- | :------- | :------------ | :---------- |
| BestEffort | switch | False |  |  |
| Ref | XenRef[VIF_metrics] | True |  |  |
| SessionOpaqueRef | string | False |  |  |
| VIFMetrics | VIF_metrics | True |  |  |
| XenProperty | XenVIFMetricsProperty | True |  |  |
### Procedure
None

### Inputs
```
XenAPI.VIF_metrics
XenAPI.XenRef`1[[XenAPI.VIF_metrics, XenServer, Version=8.2.3.0, Culture=neutral, PublicKeyToken=d247b8b0ac7959e9]]

```
### Outputs
```
System.Object
```
### Links
None

### Examples

Get-XenVIFMetricsProperty [-VIFMetrics] <VIF_metrics> -XenProperty <XenVIFMetricsProperty> [-BestEffort] [-SessionOpaqueRef <string>] [<CommonParameters>]

Get-XenVIFMetricsProperty [-Ref] <XenRef[VIF_metrics]> -XenProperty <XenVIFMetricsProperty> [-BestEffort] [-SessionOpaqueRef <string>] [<CommonParameters>]


## Get-XenVIFProperty

### Synopsis
None

### Description
None

### Syntax
```
Get-XenVIFProperty [-VIF] <VIF> [-XenProperty] <XenVIFProperty> [[-BestEffort]] [[-SessionOpaqueRef] <string>] [-Ref] <XenRef[VIF]> [-XenProperty] <XenVIFProperty> [[-BestEffort]] [[-SessionOpaqueRef] <string>]
```
### Parameters
| Name | Type | Required | Default Value | Description |
| :--- | :--- | :------- | :------------ | :---------- |
| BestEffort | switch | False |  |  |
| Ref | XenRef[VIF] | True |  |  |
| SessionOpaqueRef | string | False |  |  |
| VIF | VIF | True |  |  |
| XenProperty | XenVIFProperty | True |  |  |
### Procedure
None

### Inputs
```
XenAPI.VIF
XenAPI.XenRef`1[[XenAPI.VIF, XenServer, Version=8.2.3.0, Culture=neutral, PublicKeyToken=d247b8b0ac7959e9]]

```
### Outputs
```
System.Object
```
### Links
None

### Examples

Get-XenVIFProperty [-VIF] <VIF> -XenProperty <XenVIFProperty> [-BestEffort] [-SessionOpaqueRef <string>] [<CommonParameters>]

Get-XenVIFProperty [-Ref] <XenRef[VIF]> -XenProperty <XenVIFProperty> [-BestEffort] [-SessionOpaqueRef <string>] [<CommonParameters>]


## Get-XenVLAN

### Synopsis
None

### Description
None

### Syntax
```
Get-XenVLAN [[-Ref] <XenRef[VLAN]>] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [-Uuid] <guid> [[-BestEffort]] [[-SessionOpaqueRef] <string>]
```
### Parameters
| Name | Type | Required | Default Value | Description |
| :--- | :--- | :------- | :------------ | :---------- |
| BestEffort | switch | False |  |  |
| Ref | XenRef[VLAN] | False |  |  |
| SessionOpaqueRef | string | False |  |  |
| Uuid | guid | True |  |  |
### Procedure
None

### Inputs
```
XenAPI.XenRef`1[[XenAPI.VLAN, XenServer, Version=8.2.3.0, Culture=neutral, PublicKeyToken=d247b8b0ac7959e9]]
System.Guid

```
### Outputs
```
XenAPI.VLAN[]

```
### Links
None

### Examples

Get-XenVLAN [[-Ref] <XenRef[VLAN]>] [-BestEffort] [-SessionOpaqueRef <string>] [<CommonParameters>]

Get-XenVLAN [-Uuid] <guid> [-BestEffort] [-SessionOpaqueRef <string>] [<CommonParameters>]


## Get-XenVLANProperty

### Synopsis
None

### Description
None

### Syntax
```
Get-XenVLANProperty [-VLAN] <VLAN> [-XenProperty] <XenVLANProperty> [[-BestEffort]] [[-SessionOpaqueRef] <string>] [-Ref] <XenRef[VLAN]> [-XenProperty] <XenVLANProperty> [[-BestEffort]] [[-SessionOpaqueRef] <string>]
```
### Parameters
| Name | Type | Required | Default Value | Description |
| :--- | :--- | :------- | :------------ | :---------- |
| BestEffort | switch | False |  |  |
| Ref | XenRef[VLAN] | True |  |  |
| SessionOpaqueRef | string | False |  |  |
| VLAN | VLAN | True |  |  |
| XenProperty | XenVLANProperty | True |  |  |
### Procedure
None

### Inputs
```
XenAPI.VLAN
XenAPI.XenRef`1[[XenAPI.VLAN, XenServer, Version=8.2.3.0, Culture=neutral, PublicKeyToken=d247b8b0ac7959e9]]

```
### Outputs
```
System.Object
```
### Links
None

### Examples

Get-XenVLANProperty [-VLAN] <VLAN> -XenProperty <XenVLANProperty> [-BestEffort] [-SessionOpaqueRef <string>] [<CommonParameters>]

Get-XenVLANProperty [-Ref] <XenRef[VLAN]> -XenProperty <XenVLANProperty> [-BestEffort] [-SessionOpaqueRef <string>] [<CommonParameters>]


## Get-XenVM

### Synopsis
None

### Description
None

### Syntax
```
Get-XenVM [[-Ref] <XenRef[VM]>] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [-Uuid] <guid> [[-BestEffort]] [[-SessionOpaqueRef] <string>] [-Name] <string> [[-BestEffort]] [[-SessionOpaqueRef] <string>]
```
### Parameters
| Name | Type | Required | Default Value | Description |
| :--- | :--- | :------- | :------------ | :---------- |
| BestEffort | switch | False |  |  |
| Name | string | True |  |  |
| Ref | XenRef[VM] | False |  |  |
| SessionOpaqueRef | string | False |  |  |
| Uuid | guid | True |  |  |
### Procedure
None

### Inputs
```
XenAPI.XenRef`1[[XenAPI.VM, XenServer, Version=8.2.3.0, Culture=neutral, PublicKeyToken=d247b8b0ac7959e9]]
System.Guid
System.String

```
### Outputs
```
XenAPI.VM[]

```
### Links
None

### Examples

Get-XenVM [[-Ref] <XenRef[VM]>] [-BestEffort] [-SessionOpaqueRef <string>] [<CommonParameters>]

Get-XenVM [-Uuid] <guid> [-BestEffort] [-SessionOpaqueRef <string>] [<CommonParameters>]

Get-XenVM [-Name] <string> [-BestEffort] [-SessionOpaqueRef <string>] [<CommonParameters>]


## Get-XenVMAppliance

### Synopsis
None

### Description
None

### Syntax
```
Get-XenVMAppliance [[-Ref] <XenRef[VM_appliance]>] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [-Uuid] <guid> [[-BestEffort]] [[-SessionOpaqueRef] <string>] [-Name] <string> [[-BestEffort]] [[-SessionOpaqueRef] <string>]
```
### Parameters
| Name | Type | Required | Default Value | Description |
| :--- | :--- | :------- | :------------ | :---------- |
| BestEffort | switch | False |  |  |
| Name | string | True |  |  |
| Ref | XenRef[VM_appliance] | False |  |  |
| SessionOpaqueRef | string | False |  |  |
| Uuid | guid | True |  |  |
### Procedure
None

### Inputs
```
XenAPI.XenRef`1[[XenAPI.VM_appliance, XenServer, Version=8.2.3.0, Culture=neutral, PublicKeyToken=d247b8b0ac7959e9]]
System.Guid
System.String

```
### Outputs
```
XenAPI.VM_appliance[]

```
### Links
None

### Examples

Get-XenVMAppliance [[-Ref] <XenRef[VM_appliance]>] [-BestEffort] [-SessionOpaqueRef <string>] [<CommonParameters>]

Get-XenVMAppliance [-Uuid] <guid> [-BestEffort] [-SessionOpaqueRef <string>] [<CommonParameters>]

Get-XenVMAppliance [-Name] <string> [-BestEffort] [-SessionOpaqueRef <string>] [<CommonParameters>]


## Get-XenVMApplianceProperty

### Synopsis
None

### Description
None

### Syntax
```
Get-XenVMApplianceProperty [-VMAppliance] <VM_appliance> [-XenProperty] <XenVMApplianceProperty> [[-BestEffort]] [[-SessionOpaqueRef] <string>] [-Ref] <XenRef[VM_appliance]> [-XenProperty] <XenVMApplianceProperty> [[-BestEffort]] [[-SessionOpaqueRef] <string>]
```
### Parameters
| Name | Type | Required | Default Value | Description |
| :--- | :--- | :------- | :------------ | :---------- |
| BestEffort | switch | False |  |  |
| Ref | XenRef[VM_appliance] | True |  |  |
| SessionOpaqueRef | string | False |  |  |
| VMAppliance | VM_appliance | True |  |  |
| XenProperty | XenVMApplianceProperty | True |  |  |
### Procedure
None

### Inputs
```
XenAPI.VM_appliance
XenAPI.XenRef`1[[XenAPI.VM_appliance, XenServer, Version=8.2.3.0, Culture=neutral, PublicKeyToken=d247b8b0ac7959e9]]

```
### Outputs
```
System.Object
```
### Links
None

### Examples

Get-XenVMApplianceProperty [-VMAppliance] <VM_appliance> -XenProperty <XenVMApplianceProperty> [-BestEffort] [-SessionOpaqueRef <string>] [<CommonParameters>]

Get-XenVMApplianceProperty [-Ref] <XenRef[VM_appliance]> -XenProperty <XenVMApplianceProperty> [-BestEffort] [-SessionOpaqueRef <string>] [<CommonParameters>]


## Get-XenVMGuestMetrics

### Synopsis
None

### Description
None

### Syntax
```
Get-XenVMGuestMetrics [[-Ref] <XenRef[VM_guest_metrics]>] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [-Uuid] <guid> [[-BestEffort]] [[-SessionOpaqueRef] <string>]
```
### Parameters
| Name | Type | Required | Default Value | Description |
| :--- | :--- | :------- | :------------ | :---------- |
| BestEffort | switch | False |  |  |
| Ref | XenRef[VM_guest_metrics] | False |  |  |
| SessionOpaqueRef | string | False |  |  |
| Uuid | guid | True |  |  |
### Procedure
None

### Inputs
```
XenAPI.XenRef`1[[XenAPI.VM_guest_metrics, XenServer, Version=8.2.3.0, Culture=neutral, PublicKeyToken=d247b8b0ac7959e9]]
System.Guid

```
### Outputs
```
XenAPI.VM_guest_metrics[]

```
### Links
None

### Examples

Get-XenVMGuestMetrics [[-Ref] <XenRef[VM_guest_metrics]>] [-BestEffort] [-SessionOpaqueRef <string>] [<CommonParameters>]

Get-XenVMGuestMetrics [-Uuid] <guid> [-BestEffort] [-SessionOpaqueRef <string>] [<CommonParameters>]


## Get-XenVMGuestMetricsProperty

### Synopsis
None

### Description
None

### Syntax
```
Get-XenVMGuestMetricsProperty [-VMGuestMetrics] <VM_guest_metrics> [-XenProperty] <XenVMGuestMetricsProperty> [[-BestEffort]] [[-SessionOpaqueRef] <string>] [-Ref] <XenRef[VM_guest_metrics]> [-XenProperty] <XenVMGuestMetricsProperty> [[-BestEffort]] [[-SessionOpaqueRef] <string>]
```
### Parameters
| Name | Type | Required | Default Value | Description |
| :--- | :--- | :------- | :------------ | :---------- |
| BestEffort | switch | False |  |  |
| Ref | XenRef[VM_guest_metrics] | True |  |  |
| SessionOpaqueRef | string | False |  |  |
| VMGuestMetrics | VM_guest_metrics | True |  |  |
| XenProperty | XenVMGuestMetricsProperty | True |  |  |
### Procedure
None

### Inputs
```
XenAPI.VM_guest_metrics
XenAPI.XenRef`1[[XenAPI.VM_guest_metrics, XenServer, Version=8.2.3.0, Culture=neutral, PublicKeyToken=d247b8b0ac7959e9]]

```
### Outputs
```
System.Object
```
### Links
None

### Examples

Get-XenVMGuestMetricsProperty [-VMGuestMetrics] <VM_guest_metrics> -XenProperty <XenVMGuestMetricsProperty> [-BestEffort] [-SessionOpaqueRef <string>] [<CommonParameters>]

Get-XenVMGuestMetricsProperty [-Ref] <XenRef[VM_guest_metrics]> -XenProperty <XenVMGuestMetricsProperty> [-BestEffort] [-SessionOpaqueRef <string>] [<CommonParameters>]


## Get-XenVMMetrics

### Synopsis
None

### Description
None

### Syntax
```
Get-XenVMMetrics [[-Ref] <XenRef[VM_metrics]>] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [-Uuid] <guid> [[-BestEffort]] [[-SessionOpaqueRef] <string>]
```
### Parameters
| Name | Type | Required | Default Value | Description |
| :--- | :--- | :------- | :------------ | :---------- |
| BestEffort | switch | False |  |  |
| Ref | XenRef[VM_metrics] | False |  |  |
| SessionOpaqueRef | string | False |  |  |
| Uuid | guid | True |  |  |
### Procedure
None

### Inputs
```
XenAPI.XenRef`1[[XenAPI.VM_metrics, XenServer, Version=8.2.3.0, Culture=neutral, PublicKeyToken=d247b8b0ac7959e9]]
System.Guid

```
### Outputs
```
XenAPI.VM_metrics[]

```
### Links
None

### Examples

Get-XenVMMetrics [[-Ref] <XenRef[VM_metrics]>] [-BestEffort] [-SessionOpaqueRef <string>] [<CommonParameters>]

Get-XenVMMetrics [-Uuid] <guid> [-BestEffort] [-SessionOpaqueRef <string>] [<CommonParameters>]


## Get-XenVMMetricsProperty

### Synopsis
None

### Description
None

### Syntax
```
Get-XenVMMetricsProperty [-VMMetrics] <VM_metrics> [-XenProperty] <XenVMMetricsProperty> [[-BestEffort]] [[-SessionOpaqueRef] <string>] [-Ref] <XenRef[VM_metrics]> [-XenProperty] <XenVMMetricsProperty> [[-BestEffort]] [[-SessionOpaqueRef] <string>]
```
### Parameters
| Name | Type | Required | Default Value | Description |
| :--- | :--- | :------- | :------------ | :---------- |
| BestEffort | switch | False |  |  |
| Ref | XenRef[VM_metrics] | True |  |  |
| SessionOpaqueRef | string | False |  |  |
| VMMetrics | VM_metrics | True |  |  |
| XenProperty | XenVMMetricsProperty | True |  |  |
### Procedure
None

### Inputs
```
XenAPI.VM_metrics
XenAPI.XenRef`1[[XenAPI.VM_metrics, XenServer, Version=8.2.3.0, Culture=neutral, PublicKeyToken=d247b8b0ac7959e9]]

```
### Outputs
```
System.Object
```
### Links
None

### Examples

Get-XenVMMetricsProperty [-VMMetrics] <VM_metrics> -XenProperty <XenVMMetricsProperty> [-BestEffort] [-SessionOpaqueRef <string>] [<CommonParameters>]

Get-XenVMMetricsProperty [-Ref] <XenRef[VM_metrics]> -XenProperty <XenVMMetricsProperty> [-BestEffort] [-SessionOpaqueRef <string>] [<CommonParameters>]


## Get-XenVMPP

### Synopsis
None

### Description
None

### Syntax
```
Get-XenVMPP [[-Ref] <XenRef[VMPP]>] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [-Uuid] <guid> [[-BestEffort]] [[-SessionOpaqueRef] <string>] [-Name] <string> [[-BestEffort]] [[-SessionOpaqueRef] <string>]
```
### Parameters
| Name | Type | Required | Default Value | Description |
| :--- | :--- | :------- | :------------ | :---------- |
| BestEffort | switch | False |  |  |
| Name | string | True |  |  |
| Ref | XenRef[VMPP] | False |  |  |
| SessionOpaqueRef | string | False |  |  |
| Uuid | guid | True |  |  |
### Procedure
None

### Inputs
```
XenAPI.XenRef`1[[XenAPI.VMPP, XenServer, Version=8.2.3.0, Culture=neutral, PublicKeyToken=d247b8b0ac7959e9]]
System.Guid
System.String

```
### Outputs
```
XenAPI.VMPP[]

```
### Links
None

### Examples

Get-XenVMPP [[-Ref] <XenRef[VMPP]>] [-BestEffort] [-SessionOpaqueRef <string>] [<CommonParameters>]

Get-XenVMPP [-Uuid] <guid> [-BestEffort] [-SessionOpaqueRef <string>] [<CommonParameters>]

Get-XenVMPP [-Name] <string> [-BestEffort] [-SessionOpaqueRef <string>] [<CommonParameters>]


## Get-XenVMPPProperty

### Synopsis
None

### Description
None

### Syntax
```
Get-XenVMPPProperty [-VMPP] <VMPP> [-XenProperty] <XenVMPPProperty> [[-BestEffort]] [[-SessionOpaqueRef] <string>] [-Ref] <XenRef[VMPP]> [-XenProperty] <XenVMPPProperty> [[-BestEffort]] [[-SessionOpaqueRef] <string>]
```
### Parameters
| Name | Type | Required | Default Value | Description |
| :--- | :--- | :------- | :------------ | :---------- |
| BestEffort | switch | False |  |  |
| Ref | XenRef[VMPP] | True |  |  |
| SessionOpaqueRef | string | False |  |  |
| VMPP | VMPP | True |  |  |
| XenProperty | XenVMPPProperty | True |  |  |
### Procedure
None

### Inputs
```
XenAPI.VMPP
XenAPI.XenRef`1[[XenAPI.VMPP, XenServer, Version=8.2.3.0, Culture=neutral, PublicKeyToken=d247b8b0ac7959e9]]

```
### Outputs
```
System.Object
```
### Links
None

### Examples

Get-XenVMPPProperty [-VMPP] <VMPP> -XenProperty <XenVMPPProperty> [-BestEffort] [-SessionOpaqueRef <string>] [<CommonParameters>]

Get-XenVMPPProperty [-Ref] <XenRef[VMPP]> -XenProperty <XenVMPPProperty> [-BestEffort] [-SessionOpaqueRef <string>] [<CommonParameters>]


## Get-XenVMProperty

### Synopsis
None

### Description
None

### Syntax
```
Get-XenVMProperty [-VM] <VM> [-XenProperty] <XenVMProperty> [[-BestEffort]] [[-SessionOpaqueRef] <string>] [-Ref] <XenRef[VM]> [-XenProperty] <XenVMProperty> [[-BestEffort]] [[-SessionOpaqueRef] <string>]
```
### Parameters
| Name | Type | Required | Default Value | Description |
| :--- | :--- | :------- | :------------ | :---------- |
| BestEffort | switch | False |  |  |
| Ref | XenRef[VM] | True |  |  |
| SessionOpaqueRef | string | False |  |  |
| VM | VM | True |  |  |
| XenProperty | XenVMProperty | True |  |  |
### Procedure
None

### Inputs
```
XenAPI.VM
XenAPI.XenRef`1[[XenAPI.VM, XenServer, Version=8.2.3.0, Culture=neutral, PublicKeyToken=d247b8b0ac7959e9]]

```
### Outputs
```
System.Object
```
### Links
None

### Examples

Get-XenVMProperty [-VM] <VM> -XenProperty <XenVMProperty> [-BestEffort] [-SessionOpaqueRef <string>] [<CommonParameters>]

Get-XenVMProperty [-Ref] <XenRef[VM]> -XenProperty <XenVMProperty> [-BestEffort] [-SessionOpaqueRef <string>] [<CommonParameters>]


## Get-XenVMSS

### Synopsis
None

### Description
None

### Syntax
```
Get-XenVMSS [[-Ref] <XenRef[VMSS]>] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [-Uuid] <guid> [[-BestEffort]] [[-SessionOpaqueRef] <string>] [-Name] <string> [[-BestEffort]] [[-SessionOpaqueRef] <string>]
```
### Parameters
| Name | Type | Required | Default Value | Description |
| :--- | :--- | :------- | :------------ | :---------- |
| BestEffort | switch | False |  |  |
| Name | string | True |  |  |
| Ref | XenRef[VMSS] | False |  |  |
| SessionOpaqueRef | string | False |  |  |
| Uuid | guid | True |  |  |
### Procedure
None

### Inputs
```
XenAPI.XenRef`1[[XenAPI.VMSS, XenServer, Version=8.2.3.0, Culture=neutral, PublicKeyToken=d247b8b0ac7959e9]]
System.Guid
System.String

```
### Outputs
```
XenAPI.VMSS[]

```
### Links
None

### Examples

Get-XenVMSS [[-Ref] <XenRef[VMSS]>] [-BestEffort] [-SessionOpaqueRef <string>] [<CommonParameters>]

Get-XenVMSS [-Uuid] <guid> [-BestEffort] [-SessionOpaqueRef <string>] [<CommonParameters>]

Get-XenVMSS [-Name] <string> [-BestEffort] [-SessionOpaqueRef <string>] [<CommonParameters>]


## Get-XenVMSSProperty

### Synopsis
None

### Description
None

### Syntax
```
Get-XenVMSSProperty [-VMSS] <VMSS> [-XenProperty] <XenVMSSProperty> [[-BestEffort]] [[-SessionOpaqueRef] <string>] [-Ref] <XenRef[VMSS]> [-XenProperty] <XenVMSSProperty> [[-BestEffort]] [[-SessionOpaqueRef] <string>]
```
### Parameters
| Name | Type | Required | Default Value | Description |
| :--- | :--- | :------- | :------------ | :---------- |
| BestEffort | switch | False |  |  |
| Ref | XenRef[VMSS] | True |  |  |
| SessionOpaqueRef | string | False |  |  |
| VMSS | VMSS | True |  |  |
| XenProperty | XenVMSSProperty | True |  |  |
### Procedure
None

### Inputs
```
XenAPI.VMSS
XenAPI.XenRef`1[[XenAPI.VMSS, XenServer, Version=8.2.3.0, Culture=neutral, PublicKeyToken=d247b8b0ac7959e9]]

```
### Outputs
```
System.Object
```
### Links
None

### Examples

Get-XenVMSSProperty [-VMSS] <VMSS> -XenProperty <XenVMSSProperty> [-BestEffort] [-SessionOpaqueRef <string>] [<CommonParameters>]

Get-XenVMSSProperty [-Ref] <XenRef[VMSS]> -XenProperty <XenVMSSProperty> [-BestEffort] [-SessionOpaqueRef <string>] [<CommonParameters>]


## Get-XenVTPMProperty

### Synopsis
None

### Description
None

### Syntax
```
Get-XenVTPMProperty [-VTPM] <VTPM> [-XenProperty] <XenVTPMProperty> [[-BestEffort]] [[-SessionOpaqueRef] <string>] [-Ref] <XenRef[VTPM]> [-XenProperty] <XenVTPMProperty> [[-BestEffort]] [[-SessionOpaqueRef] <string>]
```
### Parameters
| Name | Type | Required | Default Value | Description |
| :--- | :--- | :------- | :------------ | :---------- |
| BestEffort | switch | False |  |  |
| Ref | XenRef[VTPM] | True |  |  |
| SessionOpaqueRef | string | False |  |  |
| VTPM | VTPM | True |  |  |
| XenProperty | XenVTPMProperty | True |  |  |
### Procedure
None

### Inputs
```
XenAPI.VTPM
XenAPI.XenRef`1[[XenAPI.VTPM, XenServer, Version=8.2.3.0, Culture=neutral, PublicKeyToken=d247b8b0ac7959e9]]

```
### Outputs
```
System.Object
```
### Links
None

### Examples

Get-XenVTPMProperty [-VTPM] <VTPM> -XenProperty <XenVTPMProperty> [-BestEffort] [-SessionOpaqueRef <string>] [<CommonParameters>]

Get-XenVTPMProperty [-Ref] <XenRef[VTPM]> -XenProperty <XenVTPMProperty> [-BestEffort] [-SessionOpaqueRef <string>] [<CommonParameters>]


## Get-XenVUSB

### Synopsis
None

### Description
None

### Syntax
```
Get-XenVUSB [[-Ref] <XenRef[VUSB]>] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [-Uuid] <guid> [[-BestEffort]] [[-SessionOpaqueRef] <string>]
```
### Parameters
| Name | Type | Required | Default Value | Description |
| :--- | :--- | :------- | :------------ | :---------- |
| BestEffort | switch | False |  |  |
| Ref | XenRef[VUSB] | False |  |  |
| SessionOpaqueRef | string | False |  |  |
| Uuid | guid | True |  |  |
### Procedure
None

### Inputs
```
XenAPI.XenRef`1[[XenAPI.VUSB, XenServer, Version=8.2.3.0, Culture=neutral, PublicKeyToken=d247b8b0ac7959e9]]
System.Guid

```
### Outputs
```
XenAPI.VUSB[]

```
### Links
None

### Examples

Get-XenVUSB [[-Ref] <XenRef[VUSB]>] [-BestEffort] [-SessionOpaqueRef <string>] [<CommonParameters>]

Get-XenVUSB [-Uuid] <guid> [-BestEffort] [-SessionOpaqueRef <string>] [<CommonParameters>]


## Get-XenVUSBProperty

### Synopsis
None

### Description
None

### Syntax
```
Get-XenVUSBProperty [-VUSB] <VUSB> [-XenProperty] <XenVUSBProperty> [[-BestEffort]] [[-SessionOpaqueRef] <string>] [-Ref] <XenRef[VUSB]> [-XenProperty] <XenVUSBProperty> [[-BestEffort]] [[-SessionOpaqueRef] <string>]
```
### Parameters
| Name | Type | Required | Default Value | Description |
| :--- | :--- | :------- | :------------ | :---------- |
| BestEffort | switch | False |  |  |
| Ref | XenRef[VUSB] | True |  |  |
| SessionOpaqueRef | string | False |  |  |
| VUSB | VUSB | True |  |  |
| XenProperty | XenVUSBProperty | True |  |  |
### Procedure
None

### Inputs
```
XenAPI.VUSB
XenAPI.XenRef`1[[XenAPI.VUSB, XenServer, Version=8.2.3.0, Culture=neutral, PublicKeyToken=d247b8b0ac7959e9]]

```
### Outputs
```
System.Object
```
### Links
None

### Examples

Get-XenVUSBProperty [-VUSB] <VUSB> -XenProperty <XenVUSBProperty> [-BestEffort] [-SessionOpaqueRef <string>] [<CommonParameters>]

Get-XenVUSBProperty [-Ref] <XenRef[VUSB]> -XenProperty <XenVUSBProperty> [-BestEffort] [-SessionOpaqueRef <string>] [<CommonParameters>]


## Import-XenMetadata

### Synopsis
None

### Description
None

### Syntax
```
Import-XenMetadata [-XenHost] <string> [-Path] <string> [[-ProgressDelegate] <HTTP+UpdateProgressDelegate>] [[-Restore] <bool>] [[-Force] <bool>] [[-CancellingDelegate] <HTTP+FuncBool>] [[-TimeoutMs] <int>] [[-Proxy] <IWebProxy>] [[-TaskRef] <string>] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]]
```
### Parameters
| Name | Type | Required | Default Value | Description |
| :--- | :--- | :------- | :------------ | :---------- |
| BestEffort | switch | False |  |  |
| CancellingDelegate | HTTP+FuncBool | False |  |  |
| Confirm | switch | False |  |  |
| Force | bool | False |  |  |
| Path | string | True |  |  |
| ProgressDelegate | HTTP+UpdateProgressDelegate | False |  |  |
| Proxy | IWebProxy | False |  |  |
| Restore | bool | False |  |  |
| SessionOpaqueRef | string | False |  |  |
| TaskRef | string | False |  |  |
| TimeoutMs | int | False |  |  |
| WhatIf | switch | False |  |  |
| XenHost | string | True |  |  |
### Procedure
None

### Inputs
```
None

```
### Outputs
```
System.Void

```
### Links
None

### Examples

Import-XenMetadata -XenHost <string> -Path <string> [-ProgressDelegate <HTTP+UpdateProgressDelegate>] [-Restore <bool>] [-Force <bool>] [-CancellingDelegate <HTTP+FuncBool>] [-TimeoutMs <int>] [-Proxy <IWebProxy>] [-TaskRef <string>] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [<CommonParameters>]


## Import-XenRawVdi

### Synopsis
None

### Description
None

### Syntax
```
Import-XenRawVdi [-XenHost] <string> [-Path] <string> [[-ProgressDelegate] <HTTP+UpdateProgressDelegate>] [[-Vdi] <string>] [[-CancellingDelegate] <HTTP+FuncBool>] [[-TimeoutMs] <int>] [[-Proxy] <IWebProxy>] [[-TaskRef] <string>] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]]
```
### Parameters
| Name | Type | Required | Default Value | Description |
| :--- | :--- | :------- | :------------ | :---------- |
| BestEffort | switch | False |  |  |
| CancellingDelegate | HTTP+FuncBool | False |  |  |
| Confirm | switch | False |  |  |
| Path | string | True |  |  |
| ProgressDelegate | HTTP+UpdateProgressDelegate | False |  |  |
| Proxy | IWebProxy | False |  |  |
| SessionOpaqueRef | string | False |  |  |
| TaskRef | string | False |  |  |
| TimeoutMs | int | False |  |  |
| Vdi | string | False |  |  |
| WhatIf | switch | False |  |  |
| XenHost | string | True |  |  |
### Procedure
None

### Inputs
```
None

```
### Outputs
```
System.Void

```
### Links
None

### Examples

Import-XenRawVdi -XenHost <string> -Path <string> [-ProgressDelegate <HTTP+UpdateProgressDelegate>] [-Vdi <string>] [-CancellingDelegate <HTTP+FuncBool>] [-TimeoutMs <int>] [-Proxy <IWebProxy>] [-TaskRef <string>] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [<CommonParameters>]


## Import-XenVm

### Synopsis
None

### Description
None

### Syntax
```
Import-XenVm [-XenHost] <string> [-Path] <string> [[-ProgressDelegate] <HTTP+UpdateProgressDelegate>] [[-Restore] <bool>] [[-Force] <bool>] [[-SrId] <string>] [[-CancellingDelegate] <HTTP+FuncBool>] [[-TimeoutMs] <int>] [[-Proxy] <IWebProxy>] [[-TaskRef] <string>] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]]
```
### Parameters
| Name | Type | Required | Default Value | Description |
| :--- | :--- | :------- | :------------ | :---------- |
| BestEffort | switch | False |  |  |
| CancellingDelegate | HTTP+FuncBool | False |  |  |
| Confirm | switch | False |  |  |
| Force | bool | False |  |  |
| Path | string | True |  |  |
| ProgressDelegate | HTTP+UpdateProgressDelegate | False |  |  |
| Proxy | IWebProxy | False |  |  |
| Restore | bool | False |  |  |
| SessionOpaqueRef | string | False |  |  |
| SrId | string | False |  |  |
| TaskRef | string | False |  |  |
| TimeoutMs | int | False |  |  |
| WhatIf | switch | False |  |  |
| XenHost | string | True |  |  |
### Procedure
None

### Inputs
```
None

```
### Outputs
```
System.Void

```
### Links
None

### Examples

Import-XenVm -XenHost <string> -Path <string> [-ProgressDelegate <HTTP+UpdateProgressDelegate>] [-Restore <bool>] [-Force <bool>] [-SrId <string>] [-CancellingDelegate <HTTP+FuncBool>] [-TimeoutMs <int>] [-Proxy <IWebProxy>] [-TaskRef <string>] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [<CommonParameters>]


## Invoke-XenCluster

### Synopsis
None

### Description
None

### Syntax
```
Invoke-XenCluster [-Cluster] <Cluster> [-XenAction] <XenClusterAction> [[-PassThru]] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]] [[-Async]] [[-Network] <XenRef[Network]>] [[-ClusterStack] <string>] [[-TokenTimeout] <double>] [[-TokenTimeoutCoefficient] <double>] [-Ref] <XenRef[Cluster]> [-XenAction] <XenClusterAction> [[-PassThru]] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]] [[-Async]] [[-Network] <XenRef[Network]>] [[-ClusterStack] <string>] [[-TokenTimeout] <double>] [[-TokenTimeoutCoefficient] <double>] [-Uuid] <guid> [-XenAction] <XenClusterAction> [[-PassThru]] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]] [[-Async]] [[-Network] <XenRef[Network]>] [[-ClusterStack] <string>] [[-TokenTimeout] <double>] [[-TokenTimeoutCoefficient] <double>]
```
### Parameters
| Name | Type | Required | Default Value | Description |
| :--- | :--- | :------- | :------------ | :---------- |
| Async | switch | False |  |  |
| BestEffort | switch | False |  |  |
| Cluster | Cluster | True |  |  |
| ClusterStack | string | False |  |  |
| Confirm | switch | False |  |  |
| Network | XenRef[Network] | False |  |  |
| PassThru | switch | False |  |  |
| Ref | XenRef[Cluster] | True |  |  |
| SessionOpaqueRef | string | False |  |  |
| TokenTimeout | double | False |  |  |
| TokenTimeoutCoefficient | double | False |  |  |
| Uuid | guid | True |  |  |
| WhatIf | switch | False |  |  |
| XenAction | XenClusterAction | True |  |  |
### Procedure
None

### Inputs
```
XenAPI.Cluster
XenAPI.XenRef`1[[XenAPI.Cluster, XenServer, Version=8.2.3.0, Culture=neutral, PublicKeyToken=d247b8b0ac7959e9]]
System.Guid

```
### Outputs
```
System.Object
```
### Links
None

### Examples

Invoke-XenCluster [-Cluster] <Cluster> -XenAction <XenClusterAction> [-PassThru] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [-Async] [-Network <XenRef[Network]>] [-ClusterStack <string>] [-TokenTimeout <double>] [-TokenTimeoutCoefficient <double>] [<CommonParameters>]

Invoke-XenCluster [-Ref] <XenRef[Cluster]> -XenAction <XenClusterAction> [-PassThru] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [-Async] [-Network <XenRef[Network]>] [-ClusterStack <string>] [-TokenTimeout <double>] [-TokenTimeoutCoefficient <double>] [<CommonParameters>]

Invoke-XenCluster [-Uuid] <guid> -XenAction <XenClusterAction> [-PassThru] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [-Async] [-Network <XenRef[Network]>] [-ClusterStack <string>] [-TokenTimeout <double>] [-TokenTimeoutCoefficient <double>] [<CommonParameters>]


## Invoke-XenClusterHost

### Synopsis
None

### Description
None

### Syntax
```
Invoke-XenClusterHost [-ClusterHost] <Cluster_host> [-XenAction] <XenClusterHostAction> [[-PassThru]] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]] [[-Async]] [-Ref] <XenRef[Cluster_host]> [-XenAction] <XenClusterHostAction> [[-PassThru]] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]] [[-Async]] [-Uuid] <guid> [-XenAction] <XenClusterHostAction> [[-PassThru]] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]] [[-Async]]
```
### Parameters
| Name | Type | Required | Default Value | Description |
| :--- | :--- | :------- | :------------ | :---------- |
| Async | switch | False |  |  |
| BestEffort | switch | False |  |  |
| ClusterHost | Cluster_host | True |  |  |
| Confirm | switch | False |  |  |
| PassThru | switch | False |  |  |
| Ref | XenRef[Cluster_host] | True |  |  |
| SessionOpaqueRef | string | False |  |  |
| Uuid | guid | True |  |  |
| WhatIf | switch | False |  |  |
| XenAction | XenClusterHostAction | True |  |  |
### Procedure
None

### Inputs
```
XenAPI.Cluster_host
XenAPI.XenRef`1[[XenAPI.Cluster_host, XenServer, Version=8.2.3.0, Culture=neutral, PublicKeyToken=d247b8b0ac7959e9]]
System.Guid

```
### Outputs
```
System.Object
```
### Links
None

### Examples

Invoke-XenClusterHost [-ClusterHost] <Cluster_host> -XenAction <XenClusterHostAction> [-PassThru] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [-Async] [<CommonParameters>]

Invoke-XenClusterHost [-Ref] <XenRef[Cluster_host]> -XenAction <XenClusterHostAction> [-PassThru] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [-Async] [<CommonParameters>]

Invoke-XenClusterHost [-Uuid] <guid> -XenAction <XenClusterHostAction> [-PassThru] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [-Async] [<CommonParameters>]


## Invoke-XenHost

### Synopsis
None

### Description
None

### Syntax
```
Invoke-XenHost [-XenHost] <Host> [-XenAction] <XenHostAction> [[-PassThru]] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]] [[-Async]] [-Ref] <XenRef[Host]> [-XenAction] <XenHostAction> [[-PassThru]] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]] [[-Async]] [-Uuid] <guid> [-XenAction] <XenHostAction> [[-PassThru]] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]] [[-Async]] [-Name] <string> [-XenAction] <XenHostAction> [[-PassThru]] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]] [[-Async]]
```
### Parameters
| Name | Type | Required | Default Value | Description |
| :--- | :--- | :------- | :------------ | :---------- |
| Async | switch | False |  |  |
| BestEffort | switch | False |  |  |
| Confirm | switch | False |  |  |
| Name | string | True |  |  |
| PassThru | switch | False |  |  |
| Ref | XenRef[Host] | True |  |  |
| SessionOpaqueRef | string | False |  |  |
| Uuid | guid | True |  |  |
| WhatIf | switch | False |  |  |
| XenAction | XenHostAction | True |  |  |
| XenHost | Host | True |  |  |
### Procedure
None

### Inputs
```
XenAPI.Host
XenAPI.XenRef`1[[XenAPI.Host, XenServer, Version=8.2.3.0, Culture=neutral, PublicKeyToken=d247b8b0ac7959e9]]
System.Guid
System.String

```
### Outputs
```
System.Object
```
### Links
None

### Examples

Invoke-XenHost [-XenHost] <Host> -XenAction <XenHostAction> [-PassThru] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [-Async] [<CommonParameters>]

Invoke-XenHost [-Ref] <XenRef[Host]> -XenAction <XenHostAction> [-PassThru] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [-Async] [<CommonParameters>]

Invoke-XenHost [-Uuid] <guid> -XenAction <XenHostAction> [-PassThru] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [-Async] [<CommonParameters>]

Invoke-XenHost [-Name] <string> -XenAction <XenHostAction> [-PassThru] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [-Async] [<CommonParameters>]


## Invoke-XenHostCrashdump

### Synopsis
None

### Description
None

### Syntax
```
Invoke-XenHostCrashdump [-HostCrashdump] <Host_crashdump> [-XenAction] <XenHostCrashdumpAction> [[-PassThru]] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]] [[-Async]] [[-Url_] <string>] [[-Options] <hashtable>] [-Ref] <XenRef[Host_crashdump]> [-XenAction] <XenHostCrashdumpAction> [[-PassThru]] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]] [[-Async]] [[-Url_] <string>] [[-Options] <hashtable>] [-Uuid] <guid> [-XenAction] <XenHostCrashdumpAction> [[-PassThru]] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]] [[-Async]] [[-Url_] <string>] [[-Options] <hashtable>]
```
### Parameters
| Name | Type | Required | Default Value | Description |
| :--- | :--- | :------- | :------------ | :---------- |
| Async | switch | False |  |  |
| BestEffort | switch | False |  |  |
| Confirm | switch | False |  |  |
| HostCrashdump | Host_crashdump | True |  |  |
| Options | hashtable | False |  |  |
| PassThru | switch | False |  |  |
| Ref | XenRef[Host_crashdump] | True |  |  |
| SessionOpaqueRef | string | False |  |  |
| Url_ | string | False |  |  |
| Uuid | guid | True |  |  |
| WhatIf | switch | False |  |  |
| XenAction | XenHostCrashdumpAction | True |  |  |
### Procedure
None

### Inputs
```
XenAPI.Host_crashdump
XenAPI.XenRef`1[[XenAPI.Host_crashdump, XenServer, Version=8.2.3.0, Culture=neutral, PublicKeyToken=d247b8b0ac7959e9]]
System.Guid

```
### Outputs
```
System.Object
```
### Links
None

### Examples

Invoke-XenHostCrashdump [-HostCrashdump] <Host_crashdump> -XenAction <XenHostCrashdumpAction> [-PassThru] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [-Async] [-Url_ <string>] [-Options <hashtable>] [<CommonParameters>]

Invoke-XenHostCrashdump [-Ref] <XenRef[Host_crashdump]> -XenAction <XenHostCrashdumpAction> [-PassThru] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [-Async] [-Url_ <string>] [-Options <hashtable>] [<CommonParameters>]

Invoke-XenHostCrashdump [-Uuid] <guid> -XenAction <XenHostCrashdumpAction> [-PassThru] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [-Async] [-Url_ <string>] [-Options <hashtable>] [<CommonParameters>]


## Invoke-XenHostPatch

### Synopsis
None

### Description
None

### Syntax
```
Invoke-XenHostPatch [-HostPatch] <Host_patch> [-XenAction] <XenHostPatchAction> [[-PassThru]] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]] [[-Async]] [-Ref] <XenRef[Host_patch]> [-XenAction] <XenHostPatchAction> [[-PassThru]] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]] [[-Async]] [-Uuid] <guid> [-XenAction] <XenHostPatchAction> [[-PassThru]] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]] [[-Async]] [-Name] <string> [-XenAction] <XenHostPatchAction> [[-PassThru]] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]] [[-Async]]
```
### Parameters
| Name | Type | Required | Default Value | Description |
| :--- | :--- | :------- | :------------ | :---------- |
| Async | switch | False |  |  |
| BestEffort | switch | False |  |  |
| Confirm | switch | False |  |  |
| HostPatch | Host_patch | True |  |  |
| Name | string | True |  |  |
| PassThru | switch | False |  |  |
| Ref | XenRef[Host_patch] | True |  |  |
| SessionOpaqueRef | string | False |  |  |
| Uuid | guid | True |  |  |
| WhatIf | switch | False |  |  |
| XenAction | XenHostPatchAction | True |  |  |
### Procedure
None

### Inputs
```
XenAPI.Host_patch
XenAPI.XenRef`1[[XenAPI.Host_patch, XenServer, Version=8.2.3.0, Culture=neutral, PublicKeyToken=d247b8b0ac7959e9]]
System.Guid
System.String

```
### Outputs
```
System.Object
```
### Links
None

### Examples

Invoke-XenHostPatch [-HostPatch] <Host_patch> -XenAction <XenHostPatchAction> [-PassThru] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [-Async] [<CommonParameters>]

Invoke-XenHostPatch [-Ref] <XenRef[Host_patch]> -XenAction <XenHostPatchAction> [-PassThru] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [-Async] [<CommonParameters>]

Invoke-XenHostPatch [-Uuid] <guid> -XenAction <XenHostPatchAction> [-PassThru] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [-Async] [<CommonParameters>]

Invoke-XenHostPatch [-Name] <string> -XenAction <XenHostPatchAction> [-PassThru] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [-Async] [<CommonParameters>]


## Invoke-XenLVHD

### Synopsis
None

### Description
None

### Syntax
```
Invoke-XenLVHD [-LVHD] <LVHD> [-XenAction] <XenLVHDAction> [[-PassThru]] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]] [[-Async]] [[-XenHost] <XenRef[Host]>] [[-SR] <XenRef[SR]>] [[-InitialAllocation] <long>] [[-AllocationQuantum] <long>] [-Ref] <XenRef[LVHD]> [-XenAction] <XenLVHDAction> [[-PassThru]] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]] [[-Async]] [[-XenHost] <XenRef[Host]>] [[-SR] <XenRef[SR]>] [[-InitialAllocation] <long>] [[-AllocationQuantum] <long>] [-Uuid] <guid> [-XenAction] <XenLVHDAction> [[-PassThru]] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]] [[-Async]] [[-XenHost] <XenRef[Host]>] [[-SR] <XenRef[SR]>] [[-InitialAllocation] <long>] [[-AllocationQuantum] <long>]
```
### Parameters
| Name | Type | Required | Default Value | Description |
| :--- | :--- | :------- | :------------ | :---------- |
| AllocationQuantum | long | False |  |  |
| Async | switch | False |  |  |
| BestEffort | switch | False |  |  |
| Confirm | switch | False |  |  |
| InitialAllocation | long | False |  |  |
| LVHD | LVHD | True |  |  |
| PassThru | switch | False |  |  |
| Ref | XenRef[LVHD] | True |  |  |
| SR | XenRef[SR] | False |  |  |
| SessionOpaqueRef | string | False |  |  |
| Uuid | guid | True |  |  |
| WhatIf | switch | False |  |  |
| XenAction | XenLVHDAction | True |  |  |
| XenHost | XenRef[Host] | False |  |  |
### Procedure
None

### Inputs
```
XenAPI.LVHD
XenAPI.XenRef`1[[XenAPI.LVHD, XenServer, Version=8.2.3.0, Culture=neutral, PublicKeyToken=d247b8b0ac7959e9]]
System.Guid

```
### Outputs
```
System.Object
```
### Links
None

### Examples

Invoke-XenLVHD [-LVHD] <LVHD> -XenAction <XenLVHDAction> [-PassThru] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [-Async] [-XenHost <XenRef[Host]>] [-SR <XenRef[SR]>] [-InitialAllocation <long>] [-AllocationQuantum <long>] [<CommonParameters>]

Invoke-XenLVHD [-Ref] <XenRef[LVHD]> -XenAction <XenLVHDAction> [-PassThru] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [-Async] [-XenHost <XenRef[Host]>] [-SR <XenRef[SR]>] [-InitialAllocation <long>] [-AllocationQuantum <long>] [<CommonParameters>]

Invoke-XenLVHD [-Uuid] <guid> -XenAction <XenLVHDAction> [-PassThru] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [-Async] [-XenHost <XenRef[Host]>] [-SR <XenRef[SR]>] [-InitialAllocation <long>] [-AllocationQuantum <long>] [<CommonParameters>]


## Invoke-XenNetwork

### Synopsis
None

### Description
None

### Syntax
```
Invoke-XenNetwork [-Network] <Network> [-XenAction] <XenNetworkAction> [[-PassThru]] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]] [[-Async]] [[-NameParam] <string>] [[-MimeType] <string>] [[-Public] <bool>] [-Ref] <XenRef[Network]> [-XenAction] <XenNetworkAction> [[-PassThru]] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]] [[-Async]] [[-NameParam] <string>] [[-MimeType] <string>] [[-Public] <bool>] [-Uuid] <guid> [-XenAction] <XenNetworkAction> [[-PassThru]] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]] [[-Async]] [[-NameParam] <string>] [[-MimeType] <string>] [[-Public] <bool>] [-Name] <string> [-XenAction] <XenNetworkAction> [[-PassThru]] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]] [[-Async]] [[-NameParam] <string>] [[-MimeType] <string>] [[-Public] <bool>]
```
### Parameters
| Name | Type | Required | Default Value | Description |
| :--- | :--- | :------- | :------------ | :---------- |
| Async | switch | False |  |  |
| BestEffort | switch | False |  |  |
| Confirm | switch | False |  |  |
| MimeType | string | False |  |  |
| Name | string | True |  |  |
| NameParam | string | False |  |  |
| Network | Network | True |  |  |
| PassThru | switch | False |  |  |
| Public | bool | False |  |  |
| Ref | XenRef[Network] | True |  |  |
| SessionOpaqueRef | string | False |  |  |
| Uuid | guid | True |  |  |
| WhatIf | switch | False |  |  |
| XenAction | XenNetworkAction | True |  |  |
### Procedure
None

### Inputs
```
XenAPI.Network
XenAPI.XenRef`1[[XenAPI.Network, XenServer, Version=8.2.3.0, Culture=neutral, PublicKeyToken=d247b8b0ac7959e9]]
System.Guid
System.String

```
### Outputs
```
System.Object
```
### Links
None

### Examples

Invoke-XenNetwork [-Network] <Network> -XenAction <XenNetworkAction> [-PassThru] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [-Async] [-NameParam <string>] [-MimeType <string>] [-Public <bool>] [<CommonParameters>]

Invoke-XenNetwork [-Ref] <XenRef[Network]> -XenAction <XenNetworkAction> [-PassThru] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [-Async] [-NameParam <string>] [-MimeType <string>] [-Public <bool>] [<CommonParameters>]

Invoke-XenNetwork [-Uuid] <guid> -XenAction <XenNetworkAction> [-PassThru] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [-Async] [-NameParam <string>] [-MimeType <string>] [-Public <bool>] [<CommonParameters>]

Invoke-XenNetwork [-Name] <string> -XenAction <XenNetworkAction> [-PassThru] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [-Async] [-NameParam <string>] [-MimeType <string>] [-Public <bool>] [<CommonParameters>]


## Invoke-XenPBD

### Synopsis
None

### Description
None

### Syntax
```
Invoke-XenPBD [-PBD] <PBD> [-XenAction] <XenPBDAction> [[-PassThru]] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]] [[-Async]] [-Ref] <XenRef[PBD]> [-XenAction] <XenPBDAction> [[-PassThru]] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]] [[-Async]] [-Uuid] <guid> [-XenAction] <XenPBDAction> [[-PassThru]] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]] [[-Async]]
```
### Parameters
| Name | Type | Required | Default Value | Description |
| :--- | :--- | :------- | :------------ | :---------- |
| Async | switch | False |  |  |
| BestEffort | switch | False |  |  |
| Confirm | switch | False |  |  |
| PBD | PBD | True |  |  |
| PassThru | switch | False |  |  |
| Ref | XenRef[PBD] | True |  |  |
| SessionOpaqueRef | string | False |  |  |
| Uuid | guid | True |  |  |
| WhatIf | switch | False |  |  |
| XenAction | XenPBDAction | True |  |  |
### Procedure
None

### Inputs
```
XenAPI.PBD
XenAPI.XenRef`1[[XenAPI.PBD, XenServer, Version=8.2.3.0, Culture=neutral, PublicKeyToken=d247b8b0ac7959e9]]
System.Guid

```
### Outputs
```
System.Object
```
### Links
None

### Examples

Invoke-XenPBD [-PBD] <PBD> -XenAction <XenPBDAction> [-PassThru] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [-Async] [<CommonParameters>]

Invoke-XenPBD [-Ref] <XenRef[PBD]> -XenAction <XenPBDAction> [-PassThru] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [-Async] [<CommonParameters>]

Invoke-XenPBD [-Uuid] <guid> -XenAction <XenPBDAction> [-PassThru] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [-Async] [<CommonParameters>]


## Invoke-XenPGPU

### Synopsis
None

### Description
None

### Syntax
```
Invoke-XenPGPU [-PGPU] <PGPU> [-XenAction] <XenPGPUAction> [[-PassThru]] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]] [[-Async]] [-Ref] <XenRef[PGPU]> [-XenAction] <XenPGPUAction> [[-PassThru]] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]] [[-Async]] [-Uuid] <guid> [-XenAction] <XenPGPUAction> [[-PassThru]] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]] [[-Async]]
```
### Parameters
| Name | Type | Required | Default Value | Description |
| :--- | :--- | :------- | :------------ | :---------- |
| Async | switch | False |  |  |
| BestEffort | switch | False |  |  |
| Confirm | switch | False |  |  |
| PGPU | PGPU | True |  |  |
| PassThru | switch | False |  |  |
| Ref | XenRef[PGPU] | True |  |  |
| SessionOpaqueRef | string | False |  |  |
| Uuid | guid | True |  |  |
| WhatIf | switch | False |  |  |
| XenAction | XenPGPUAction | True |  |  |
### Procedure
None

### Inputs
```
XenAPI.PGPU
XenAPI.XenRef`1[[XenAPI.PGPU, XenServer, Version=8.2.3.0, Culture=neutral, PublicKeyToken=d247b8b0ac7959e9]]
System.Guid

```
### Outputs
```
System.Object
```
### Links
None

### Examples

Invoke-XenPGPU [-PGPU] <PGPU> -XenAction <XenPGPUAction> [-PassThru] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [-Async] [<CommonParameters>]

Invoke-XenPGPU [-Ref] <XenRef[PGPU]> -XenAction <XenPGPUAction> [-PassThru] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [-Async] [<CommonParameters>]

Invoke-XenPGPU [-Uuid] <guid> -XenAction <XenPGPUAction> [-PassThru] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [-Async] [<CommonParameters>]


## Invoke-XenPIF

### Synopsis
None

### Description
None

### Syntax
```
Invoke-XenPIF [-PIF] <PIF> [-XenAction] <XenPIFAction> [[-PassThru]] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]] [[-Async]] [[-Device] <string>] [[-Network] <XenRef[Network]>] [[-XenHost] <XenRef[Host]>] [[-VLAN] <long>] [-Ref] <XenRef[PIF]> [-XenAction] <XenPIFAction> [[-PassThru]] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]] [[-Async]] [[-Device] <string>] [[-Network] <XenRef[Network]>] [[-XenHost] <XenRef[Host]>] [[-VLAN] <long>] [-Uuid] <guid> [-XenAction] <XenPIFAction> [[-PassThru]] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]] [[-Async]] [[-Device] <string>] [[-Network] <XenRef[Network]>] [[-XenHost] <XenRef[Host]>] [[-VLAN] <long>]
```
### Parameters
| Name | Type | Required | Default Value | Description |
| :--- | :--- | :------- | :------------ | :---------- |
| Async | switch | False |  |  |
| BestEffort | switch | False |  |  |
| Confirm | switch | False |  |  |
| Device | string | False |  |  |
| Network | XenRef[Network] | False |  |  |
| PIF | PIF | True |  |  |
| PassThru | switch | False |  |  |
| Ref | XenRef[PIF] | True |  |  |
| SessionOpaqueRef | string | False |  |  |
| Uuid | guid | True |  |  |
| VLAN | long | False |  |  |
| WhatIf | switch | False |  |  |
| XenAction | XenPIFAction | True |  |  |
| XenHost | XenRef[Host] | False |  |  |
### Procedure
None

### Inputs
```
XenAPI.PIF
XenAPI.XenRef`1[[XenAPI.PIF, XenServer, Version=8.2.3.0, Culture=neutral, PublicKeyToken=d247b8b0ac7959e9]]
System.Guid

```
### Outputs
```
System.Object
```
### Links
None

### Examples

Invoke-XenPIF [-PIF] <PIF> -XenAction <XenPIFAction> [-PassThru] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [-Async] [-Device <string>] [-Network <XenRef[Network]>] [-XenHost <XenRef[Host]>] [-VLAN <long>] [<CommonParameters>]

Invoke-XenPIF [-Ref] <XenRef[PIF]> -XenAction <XenPIFAction> [-PassThru] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [-Async] [-Device <string>] [-Network <XenRef[Network]>] [-XenHost <XenRef[Host]>] [-VLAN <long>] [<CommonParameters>]

Invoke-XenPIF [-Uuid] <guid> -XenAction <XenPIFAction> [-PassThru] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [-Async] [-Device <string>] [-Network <XenRef[Network]>] [-XenHost <XenRef[Host]>] [-VLAN <long>] [<CommonParameters>]


## Invoke-XenPool

### Synopsis
None

### Description
None

### Syntax
```
Invoke-XenPool [-Pool] <Pool> [-XenAction] <XenPoolAction> [[-PassThru]] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]] [[-Async]] [[-MasterAddress] <string>] [[-MasterUsername] <string>] [[-MasterPassword] <string>] [-Ref] <XenRef[Pool]> [-XenAction] <XenPoolAction> [[-PassThru]] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]] [[-Async]] [[-MasterAddress] <string>] [[-MasterUsername] <string>] [[-MasterPassword] <string>] [-Uuid] <guid> [-XenAction] <XenPoolAction> [[-PassThru]] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]] [[-Async]] [[-MasterAddress] <string>] [[-MasterUsername] <string>] [[-MasterPassword] <string>]
```
### Parameters
| Name | Type | Required | Default Value | Description |
| :--- | :--- | :------- | :------------ | :---------- |
| Async | switch | False |  |  |
| BestEffort | switch | False |  |  |
| Confirm | switch | False |  |  |
| MasterAddress | string | False |  |  |
| MasterPassword | string | False |  |  |
| MasterUsername | string | False |  |  |
| PassThru | switch | False |  |  |
| Pool | Pool | True |  |  |
| Ref | XenRef[Pool] | True |  |  |
| SessionOpaqueRef | string | False |  |  |
| Uuid | guid | True |  |  |
| WhatIf | switch | False |  |  |
| XenAction | XenPoolAction | True |  |  |
### Procedure
None

### Inputs
```
XenAPI.Pool
XenAPI.XenRef`1[[XenAPI.Pool, XenServer, Version=8.2.3.0, Culture=neutral, PublicKeyToken=d247b8b0ac7959e9]]
System.Guid

```
### Outputs
```
System.Object
```
### Links
None

### Examples

Invoke-XenPool [-Pool] <Pool> -XenAction <XenPoolAction> [-PassThru] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [-Async] [-MasterAddress <string>] [-MasterUsername <string>] [-MasterPassword <string>] [<CommonParameters>]

Invoke-XenPool [-Ref] <XenRef[Pool]> -XenAction <XenPoolAction> [-PassThru] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [-Async] [-MasterAddress <string>] [-MasterUsername <string>] [-MasterPassword <string>] [<CommonParameters>]

Invoke-XenPool [-Uuid] <guid> -XenAction <XenPoolAction> [-PassThru] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [-Async] [-MasterAddress <string>] [-MasterUsername <string>] [-MasterPassword <string>] [<CommonParameters>]


## Invoke-XenPoolPatch

### Synopsis
None

### Description
None

### Syntax
```
Invoke-XenPoolPatch [-PoolPatch] <Pool_patch> [-XenAction] <XenPoolPatchAction> [[-PassThru]] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]] [[-Async]] [[-XenHost] <XenRef[Host]>] [-Ref] <XenRef[Pool_patch]> [-XenAction] <XenPoolPatchAction> [[-PassThru]] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]] [[-Async]] [[-XenHost] <XenRef[Host]>] [-Uuid] <guid> [-XenAction] <XenPoolPatchAction> [[-PassThru]] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]] [[-Async]] [[-XenHost] <XenRef[Host]>] [-Name] <string> [-XenAction] <XenPoolPatchAction> [[-PassThru]] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]] [[-Async]] [[-XenHost] <XenRef[Host]>]
```
### Parameters
| Name | Type | Required | Default Value | Description |
| :--- | :--- | :------- | :------------ | :---------- |
| Async | switch | False |  |  |
| BestEffort | switch | False |  |  |
| Confirm | switch | False |  |  |
| Name | string | True |  |  |
| PassThru | switch | False |  |  |
| PoolPatch | Pool_patch | True |  |  |
| Ref | XenRef[Pool_patch] | True |  |  |
| SessionOpaqueRef | string | False |  |  |
| Uuid | guid | True |  |  |
| WhatIf | switch | False |  |  |
| XenAction | XenPoolPatchAction | True |  |  |
| XenHost | XenRef[Host] | False |  |  |
### Procedure
None

### Inputs
```
XenAPI.Pool_patch
XenAPI.XenRef`1[[XenAPI.Pool_patch, XenServer, Version=8.2.3.0, Culture=neutral, PublicKeyToken=d247b8b0ac7959e9]]
System.Guid
System.String

```
### Outputs
```
System.Object
```
### Links
None

### Examples

Invoke-XenPoolPatch [-PoolPatch] <Pool_patch> -XenAction <XenPoolPatchAction> [-PassThru] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [-Async] [-XenHost <XenRef[Host]>] [<CommonParameters>]

Invoke-XenPoolPatch [-Ref] <XenRef[Pool_patch]> -XenAction <XenPoolPatchAction> [-PassThru] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [-Async] [-XenHost <XenRef[Host]>] [<CommonParameters>]

Invoke-XenPoolPatch [-Uuid] <guid> -XenAction <XenPoolPatchAction> [-PassThru] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [-Async] [-XenHost <XenRef[Host]>] [<CommonParameters>]

Invoke-XenPoolPatch [-Name] <string> -XenAction <XenPoolPatchAction> [-PassThru] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [-Async] [-XenHost <XenRef[Host]>] [<CommonParameters>]


## Invoke-XenPoolUpdate

### Synopsis
None

### Description
None

### Syntax
```
Invoke-XenPoolUpdate [-PoolUpdate] <Pool_update> [-XenAction] <XenPoolUpdateAction> [[-PassThru]] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]] [[-Async]] [[-VDI] <XenRef[VDI]>] [-Ref] <XenRef[Pool_update]> [-XenAction] <XenPoolUpdateAction> [[-PassThru]] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]] [[-Async]] [[-VDI] <XenRef[VDI]>] [-Uuid] <guid> [-XenAction] <XenPoolUpdateAction> [[-PassThru]] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]] [[-Async]] [[-VDI] <XenRef[VDI]>] [-Name] <string> [-XenAction] <XenPoolUpdateAction> [[-PassThru]] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]] [[-Async]] [[-VDI] <XenRef[VDI]>]
```
### Parameters
| Name | Type | Required | Default Value | Description |
| :--- | :--- | :------- | :------------ | :---------- |
| Async | switch | False |  |  |
| BestEffort | switch | False |  |  |
| Confirm | switch | False |  |  |
| Name | string | True |  |  |
| PassThru | switch | False |  |  |
| PoolUpdate | Pool_update | True |  |  |
| Ref | XenRef[Pool_update] | True |  |  |
| SessionOpaqueRef | string | False |  |  |
| Uuid | guid | True |  |  |
| VDI | XenRef[VDI] | False |  |  |
| WhatIf | switch | False |  |  |
| XenAction | XenPoolUpdateAction | True |  |  |
### Procedure
None

### Inputs
```
XenAPI.Pool_update
XenAPI.XenRef`1[[XenAPI.Pool_update, XenServer, Version=8.2.3.0, Culture=neutral, PublicKeyToken=d247b8b0ac7959e9]]
System.Guid
System.String

```
### Outputs
```
System.Object
```
### Links
None

### Examples

Invoke-XenPoolUpdate [-PoolUpdate] <Pool_update> -XenAction <XenPoolUpdateAction> [-PassThru] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [-Async] [-VDI <XenRef[VDI]>] [<CommonParameters>]

Invoke-XenPoolUpdate [-Ref] <XenRef[Pool_update]> -XenAction <XenPoolUpdateAction> [-PassThru] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [-Async] [-VDI <XenRef[VDI]>] [<CommonParameters>]

Invoke-XenPoolUpdate [-Uuid] <guid> -XenAction <XenPoolUpdateAction> [-PassThru] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [-Async] [-VDI <XenRef[VDI]>] [<CommonParameters>]

Invoke-XenPoolUpdate [-Name] <string> -XenAction <XenPoolUpdateAction> [-PassThru] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [-Async] [-VDI <XenRef[VDI]>] [<CommonParameters>]


## Invoke-XenPUSB

### Synopsis
None

### Description
None

### Syntax
```
Invoke-XenPUSB [-PUSB] <PUSB> [-XenAction] <XenPUSBAction> [[-PassThru]] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]] [[-Async]] [[-XenHost] <XenRef[Host]>] [-Ref] <XenRef[PUSB]> [-XenAction] <XenPUSBAction> [[-PassThru]] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]] [[-Async]] [[-XenHost] <XenRef[Host]>] [-Uuid] <guid> [-XenAction] <XenPUSBAction> [[-PassThru]] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]] [[-Async]] [[-XenHost] <XenRef[Host]>]
```
### Parameters
| Name | Type | Required | Default Value | Description |
| :--- | :--- | :------- | :------------ | :---------- |
| Async | switch | False |  |  |
| BestEffort | switch | False |  |  |
| Confirm | switch | False |  |  |
| PUSB | PUSB | True |  |  |
| PassThru | switch | False |  |  |
| Ref | XenRef[PUSB] | True |  |  |
| SessionOpaqueRef | string | False |  |  |
| Uuid | guid | True |  |  |
| WhatIf | switch | False |  |  |
| XenAction | XenPUSBAction | True |  |  |
| XenHost | XenRef[Host] | False |  |  |
### Procedure
None

### Inputs
```
XenAPI.PUSB
XenAPI.XenRef`1[[XenAPI.PUSB, XenServer, Version=8.2.3.0, Culture=neutral, PublicKeyToken=d247b8b0ac7959e9]]
System.Guid

```
### Outputs
```
System.Object
```
### Links
None

### Examples

Invoke-XenPUSB [-PUSB] <PUSB> -XenAction <XenPUSBAction> [-PassThru] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [-Async] [-XenHost <XenRef[Host]>] [<CommonParameters>]

Invoke-XenPUSB [-Ref] <XenRef[PUSB]> -XenAction <XenPUSBAction> [-PassThru] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [-Async] [-XenHost <XenRef[Host]>] [<CommonParameters>]

Invoke-XenPUSB [-Uuid] <guid> -XenAction <XenPUSBAction> [-PassThru] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [-Async] [-XenHost <XenRef[Host]>] [<CommonParameters>]


## Invoke-XenPVSServer

### Synopsis
None

### Description
None

### Syntax
```
Invoke-XenPVSServer [-PVSServer] <PVS_server> [-XenAction] <XenPVSServerAction> [[-PassThru]] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]] [[-Async]] [[-Addresses] <string[]>] [[-FirstPort] <long>] [[-LastPort] <long>] [[-Site] <XenRef[PVS_site]>] [-Ref] <XenRef[PVS_server]> [-XenAction] <XenPVSServerAction> [[-PassThru]] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]] [[-Async]] [[-Addresses] <string[]>] [[-FirstPort] <long>] [[-LastPort] <long>] [[-Site] <XenRef[PVS_site]>] [-Uuid] <guid> [-XenAction] <XenPVSServerAction> [[-PassThru]] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]] [[-Async]] [[-Addresses] <string[]>] [[-FirstPort] <long>] [[-LastPort] <long>] [[-Site] <XenRef[PVS_site]>]
```
### Parameters
| Name | Type | Required | Default Value | Description |
| :--- | :--- | :------- | :------------ | :---------- |
| Addresses | string[] | False |  |  |
| Async | switch | False |  |  |
| BestEffort | switch | False |  |  |
| Confirm | switch | False |  |  |
| FirstPort | long | False |  |  |
| LastPort | long | False |  |  |
| PVSServer | PVS_server | True |  |  |
| PassThru | switch | False |  |  |
| Ref | XenRef[PVS_server] | True |  |  |
| SessionOpaqueRef | string | False |  |  |
| Site | XenRef[PVS_site] | False |  |  |
| Uuid | guid | True |  |  |
| WhatIf | switch | False |  |  |
| XenAction | XenPVSServerAction | True |  |  |
### Procedure
None

### Inputs
```
XenAPI.PVS_server
XenAPI.XenRef`1[[XenAPI.PVS_server, XenServer, Version=8.2.3.0, Culture=neutral, PublicKeyToken=d247b8b0ac7959e9]]
System.Guid

```
### Outputs
```
System.Object
```
### Links
None

### Examples

Invoke-XenPVSServer [-PVSServer] <PVS_server> -XenAction <XenPVSServerAction> [-PassThru] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [-Async] [-Addresses <string[]>] [-FirstPort <long>] [-LastPort <long>] [-Site <XenRef[PVS_site]>] [<CommonParameters>]

Invoke-XenPVSServer [-Ref] <XenRef[PVS_server]> -XenAction <XenPVSServerAction> [-PassThru] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [-Async] [-Addresses <string[]>] [-FirstPort <long>] [-LastPort <long>] [-Site <XenRef[PVS_site]>] [<CommonParameters>]

Invoke-XenPVSServer [-Uuid] <guid> -XenAction <XenPVSServerAction> [-PassThru] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [-Async] [-Addresses <string[]>] [-FirstPort <long>] [-LastPort <long>] [-Site <XenRef[PVS_site]>] [<CommonParameters>]


## Invoke-XenPVSSite

### Synopsis
None

### Description
None

### Syntax
```
Invoke-XenPVSSite [-PVSSite] <PVS_site> [-XenAction] <XenPVSSiteAction> [[-PassThru]] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]] [[-Async]] [[-NameLabel] <string>] [[-NameDescription] <string>] [[-PVSUuid] <string>] [-Ref] <XenRef[PVS_site]> [-XenAction] <XenPVSSiteAction> [[-PassThru]] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]] [[-Async]] [[-NameLabel] <string>] [[-NameDescription] <string>] [[-PVSUuid] <string>] [-Uuid] <guid> [-XenAction] <XenPVSSiteAction> [[-PassThru]] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]] [[-Async]] [[-NameLabel] <string>] [[-NameDescription] <string>] [[-PVSUuid] <string>] [-Name] <string> [-XenAction] <XenPVSSiteAction> [[-PassThru]] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]] [[-Async]] [[-NameLabel] <string>] [[-NameDescription] <string>] [[-PVSUuid] <string>]
```
### Parameters
| Name | Type | Required | Default Value | Description |
| :--- | :--- | :------- | :------------ | :---------- |
| Async | switch | False |  |  |
| BestEffort | switch | False |  |  |
| Confirm | switch | False |  |  |
| Name | string | True |  |  |
| NameDescription | string | False |  |  |
| NameLabel | string | False |  |  |
| PVSSite | PVS_site | True |  |  |
| PVSUuid | string | False |  |  |
| PassThru | switch | False |  |  |
| Ref | XenRef[PVS_site] | True |  |  |
| SessionOpaqueRef | string | False |  |  |
| Uuid | guid | True |  |  |
| WhatIf | switch | False |  |  |
| XenAction | XenPVSSiteAction | True |  |  |
### Procedure
None

### Inputs
```
XenAPI.PVS_site
XenAPI.XenRef`1[[XenAPI.PVS_site, XenServer, Version=8.2.3.0, Culture=neutral, PublicKeyToken=d247b8b0ac7959e9]]
System.Guid
System.String

```
### Outputs
```
System.Object
```
### Links
None

### Examples

Invoke-XenPVSSite [-PVSSite] <PVS_site> -XenAction <XenPVSSiteAction> [-PassThru] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [-Async] [-NameLabel <string>] [-NameDescription <string>] [-PVSUuid <string>] [<CommonParameters>]

Invoke-XenPVSSite [-Ref] <XenRef[PVS_site]> -XenAction <XenPVSSiteAction> [-PassThru] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [-Async] [-NameLabel <string>] [-NameDescription <string>] [-PVSUuid <string>] [<CommonParameters>]

Invoke-XenPVSSite [-Uuid] <guid> -XenAction <XenPVSSiteAction> [-PassThru] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [-Async] [-NameLabel <string>] [-NameDescription <string>] [-PVSUuid <string>] [<CommonParameters>]

Invoke-XenPVSSite [-Name] <string> -XenAction <XenPVSSiteAction> [-PassThru] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [-Async] [-NameLabel <string>] [-NameDescription <string>] [-PVSUuid <string>] [<CommonParameters>]


## Invoke-XenSDNController

### Synopsis
None

### Description
None

### Syntax
```
Invoke-XenSDNController [-SDNController] <SDN_controller> [-XenAction] <XenSDNControllerAction> [[-PassThru]] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]] [[-Async]] [[-Protocol] <sdn_controller_protocol>] [[-Address] <string>] [[-Port] <long>] [-Ref] <XenRef[SDN_controller]> [-XenAction] <XenSDNControllerAction> [[-PassThru]] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]] [[-Async]] [[-Protocol] <sdn_controller_protocol>] [[-Address] <string>] [[-Port] <long>] [-Uuid] <guid> [-XenAction] <XenSDNControllerAction> [[-PassThru]] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]] [[-Async]] [[-Protocol] <sdn_controller_protocol>] [[-Address] <string>] [[-Port] <long>]
```
### Parameters
| Name | Type | Required | Default Value | Description |
| :--- | :--- | :------- | :------------ | :---------- |
| Address | string | False |  |  |
| Async | switch | False |  |  |
| BestEffort | switch | False |  |  |
| Confirm | switch | False |  |  |
| PassThru | switch | False |  |  |
| Port | long | False |  |  |
| Protocol | sdn_controller_protocol | False |  |  |
| Ref | XenRef[SDN_controller] | True |  |  |
| SDNController | SDN_controller | True |  |  |
| SessionOpaqueRef | string | False |  |  |
| Uuid | guid | True |  |  |
| WhatIf | switch | False |  |  |
| XenAction | XenSDNControllerAction | True |  |  |
### Procedure
None

### Inputs
```
XenAPI.SDN_controller
XenAPI.XenRef`1[[XenAPI.SDN_controller, XenServer, Version=8.2.3.0, Culture=neutral, PublicKeyToken=d247b8b0ac7959e9]]
System.Guid

```
### Outputs
```
System.Object
```
### Links
None

### Examples

Invoke-XenSDNController [-SDNController] <SDN_controller> -XenAction <XenSDNControllerAction> [-PassThru] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [-Async] [-Protocol <sdn_controller_protocol>] [-Address <string>] [-Port <long>] [<CommonParameters>]

Invoke-XenSDNController [-Ref] <XenRef[SDN_controller]> -XenAction <XenSDNControllerAction> [-PassThru] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [-Async] [-Protocol <sdn_controller_protocol>] [-Address <string>] [-Port <long>] [<CommonParameters>]

Invoke-XenSDNController [-Uuid] <guid> -XenAction <XenSDNControllerAction> [-PassThru] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [-Async] [-Protocol <sdn_controller_protocol>] [-Address <string>] [-Port <long>] [<CommonParameters>]


## Invoke-XenSR

### Synopsis
None

### Description
None

### Syntax
```
Invoke-XenSR [-SR] <SR> [-XenAction] <XenSRAction> [[-PassThru]] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]] [[-Async]] [[-UuidParam] <string>] [[-NameLabel] <string>] [[-NameDescription] <string>] [[-Type] <string>] [[-ContentType] <string>] [[-Shared] <bool>] [[-SmConfig] <hashtable>] [-Ref] <XenRef[SR]> [-XenAction] <XenSRAction> [[-PassThru]] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]] [[-Async]] [[-UuidParam] <string>] [[-NameLabel] <string>] [[-NameDescription] <string>] [[-Type] <string>] [[-ContentType] <string>] [[-Shared] <bool>] [[-SmConfig] <hashtable>] [-Uuid] <guid> [-XenAction] <XenSRAction> [[-PassThru]] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]] [[-Async]] [[-UuidParam] <string>] [[-NameLabel] <string>] [[-NameDescription] <string>] [[-Type] <string>] [[-ContentType] <string>] [[-Shared] <bool>] [[-SmConfig] <hashtable>] [-Name] <string> [-XenAction] <XenSRAction> [[-PassThru]] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]] [[-Async]] [[-UuidParam] <string>] [[-NameLabel] <string>] [[-NameDescription] <string>] [[-Type] <string>] [[-ContentType] <string>] [[-Shared] <bool>] [[-SmConfig] <hashtable>]
```
### Parameters
| Name | Type | Required | Default Value | Description |
| :--- | :--- | :------- | :------------ | :---------- |
| Async | switch | False |  |  |
| BestEffort | switch | False |  |  |
| Confirm | switch | False |  |  |
| ContentType | string | False |  |  |
| Name | string | True |  |  |
| NameDescription | string | False |  |  |
| NameLabel | string | False |  |  |
| PassThru | switch | False |  |  |
| Ref | XenRef[SR] | True |  |  |
| SR | SR | True |  |  |
| SessionOpaqueRef | string | False |  |  |
| Shared | bool | False |  |  |
| SmConfig | hashtable | False |  |  |
| Type | string | False |  |  |
| Uuid | guid | True |  |  |
| UuidParam | string | False |  |  |
| WhatIf | switch | False |  |  |
| XenAction | XenSRAction | True |  |  |
### Procedure
None

### Inputs
```
XenAPI.SR
XenAPI.XenRef`1[[XenAPI.SR, XenServer, Version=8.2.3.0, Culture=neutral, PublicKeyToken=d247b8b0ac7959e9]]
System.Guid
System.String

```
### Outputs
```
System.Object
```
### Links
None

### Examples

Invoke-XenSR [-SR] <SR> -XenAction <XenSRAction> [-PassThru] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [-Async] [-UuidParam <string>] [-NameLabel <string>] [-NameDescription <string>] [-Type <string>] [-ContentType <string>] [-Shared <bool>] [-SmConfig <hashtable>] [<CommonParameters>]

Invoke-XenSR [-Ref] <XenRef[SR]> -XenAction <XenSRAction> [-PassThru] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [-Async] [-UuidParam <string>] [-NameLabel <string>] [-NameDescription <string>] [-Type <string>] [-ContentType <string>] [-Shared <bool>] [-SmConfig <hashtable>] [<CommonParameters>]

Invoke-XenSR [-Uuid] <guid> -XenAction <XenSRAction> [-PassThru] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [-Async] [-UuidParam <string>] [-NameLabel <string>] [-NameDescription <string>] [-Type <string>] [-ContentType <string>] [-Shared <bool>] [-SmConfig <hashtable>] [<CommonParameters>]

Invoke-XenSR [-Name] <string> -XenAction <XenSRAction> [-PassThru] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [-Async] [-UuidParam <string>] [-NameLabel <string>] [-NameDescription <string>] [-Type <string>] [-ContentType <string>] [-Shared <bool>] [-SmConfig <hashtable>] [<CommonParameters>]


## Invoke-XenTask

### Synopsis
None

### Description
None

### Syntax
```
Invoke-XenTask [-Task] <Task> [-XenAction] <XenTaskAction> [[-PassThru]] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]] [[-Async]] [-Ref] <XenRef[Task]> [-XenAction] <XenTaskAction> [[-PassThru]] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]] [[-Async]] [-Uuid] <guid> [-XenAction] <XenTaskAction> [[-PassThru]] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]] [[-Async]] [-Name] <string> [-XenAction] <XenTaskAction> [[-PassThru]] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]] [[-Async]]
```
### Parameters
| Name | Type | Required | Default Value | Description |
| :--- | :--- | :------- | :------------ | :---------- |
| Async | switch | False |  |  |
| BestEffort | switch | False |  |  |
| Confirm | switch | False |  |  |
| Name | string | True |  |  |
| PassThru | switch | False |  |  |
| Ref | XenRef[Task] | True |  |  |
| SessionOpaqueRef | string | False |  |  |
| Task | Task | True |  |  |
| Uuid | guid | True |  |  |
| WhatIf | switch | False |  |  |
| XenAction | XenTaskAction | True |  |  |
### Procedure
None

### Inputs
```
XenAPI.Task
XenAPI.XenRef`1[[XenAPI.Task, XenServer, Version=8.2.3.0, Culture=neutral, PublicKeyToken=d247b8b0ac7959e9]]
System.Guid
System.String

```
### Outputs
```
System.Object
```
### Links
None

### Examples

Invoke-XenTask [-Task] <Task> -XenAction <XenTaskAction> [-PassThru] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [-Async] [<CommonParameters>]

Invoke-XenTask [-Ref] <XenRef[Task]> -XenAction <XenTaskAction> [-PassThru] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [-Async] [<CommonParameters>]

Invoke-XenTask [-Uuid] <guid> -XenAction <XenTaskAction> [-PassThru] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [-Async] [<CommonParameters>]

Invoke-XenTask [-Name] <string> -XenAction <XenTaskAction> [-PassThru] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [-Async] [<CommonParameters>]


## Invoke-XenVBD

### Synopsis
None

### Description
None

### Syntax
```
Invoke-XenVBD [-VBD] <VBD> [-XenAction] <XenVBDAction> [[-PassThru]] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]] [[-Async]] [-Ref] <XenRef[VBD]> [-XenAction] <XenVBDAction> [[-PassThru]] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]] [[-Async]] [-Uuid] <guid> [-XenAction] <XenVBDAction> [[-PassThru]] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]] [[-Async]]
```
### Parameters
| Name | Type | Required | Default Value | Description |
| :--- | :--- | :------- | :------------ | :---------- |
| Async | switch | False |  |  |
| BestEffort | switch | False |  |  |
| Confirm | switch | False |  |  |
| PassThru | switch | False |  |  |
| Ref | XenRef[VBD] | True |  |  |
| SessionOpaqueRef | string | False |  |  |
| Uuid | guid | True |  |  |
| VBD | VBD | True |  |  |
| WhatIf | switch | False |  |  |
| XenAction | XenVBDAction | True |  |  |
### Procedure
None

### Inputs
```
XenAPI.VBD
XenAPI.XenRef`1[[XenAPI.VBD, XenServer, Version=8.2.3.0, Culture=neutral, PublicKeyToken=d247b8b0ac7959e9]]
System.Guid

```
### Outputs
```
System.Object
```
### Links
None

### Examples

Invoke-XenVBD [-VBD] <VBD> -XenAction <XenVBDAction> [-PassThru] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [-Async] [<CommonParameters>]

Invoke-XenVBD [-Ref] <XenRef[VBD]> -XenAction <XenVBDAction> [-PassThru] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [-Async] [<CommonParameters>]

Invoke-XenVBD [-Uuid] <guid> -XenAction <XenVBDAction> [-PassThru] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [-Async] [<CommonParameters>]


## Invoke-XenVDI

### Synopsis
None

### Description
None

### Syntax
```
Invoke-XenVDI [-VDI] <VDI> [-XenAction] <XenVDIAction> [[-PassThru]] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]] [[-Async]] [[-DriverParams] <hashtable>] [-Ref] <XenRef[VDI]> [-XenAction] <XenVDIAction> [[-PassThru]] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]] [[-Async]] [[-DriverParams] <hashtable>] [-Uuid] <guid> [-XenAction] <XenVDIAction> [[-PassThru]] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]] [[-Async]] [[-DriverParams] <hashtable>] [-Name] <string> [-XenAction] <XenVDIAction> [[-PassThru]] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]] [[-Async]] [[-DriverParams] <hashtable>]
```
### Parameters
| Name | Type | Required | Default Value | Description |
| :--- | :--- | :------- | :------------ | :---------- |
| Async | switch | False |  |  |
| BestEffort | switch | False |  |  |
| Confirm | switch | False |  |  |
| DriverParams | hashtable | False |  |  |
| Name | string | True |  |  |
| PassThru | switch | False |  |  |
| Ref | XenRef[VDI] | True |  |  |
| SessionOpaqueRef | string | False |  |  |
| Uuid | guid | True |  |  |
| VDI | VDI | True |  |  |
| WhatIf | switch | False |  |  |
| XenAction | XenVDIAction | True |  |  |
### Procedure
None

### Inputs
```
XenAPI.VDI
XenAPI.XenRef`1[[XenAPI.VDI, XenServer, Version=8.2.3.0, Culture=neutral, PublicKeyToken=d247b8b0ac7959e9]]
System.Guid
System.String

```
### Outputs
```
System.Object
```
### Links
None

### Examples

Invoke-XenVDI [-VDI] <VDI> -XenAction <XenVDIAction> [-PassThru] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [-Async] [-DriverParams <hashtable>] [<CommonParameters>]

Invoke-XenVDI [-Ref] <XenRef[VDI]> -XenAction <XenVDIAction> [-PassThru] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [-Async] [-DriverParams <hashtable>] [<CommonParameters>]

Invoke-XenVDI [-Uuid] <guid> -XenAction <XenVDIAction> [-PassThru] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [-Async] [-DriverParams <hashtable>] [<CommonParameters>]

Invoke-XenVDI [-Name] <string> -XenAction <XenVDIAction> [-PassThru] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [-Async] [-DriverParams <hashtable>] [<CommonParameters>]


## Invoke-XenVIF

### Synopsis
None

### Description
None

### Syntax
```
Invoke-XenVIF [-VIF] <VIF> [-XenAction] <XenVIFAction> [[-PassThru]] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]] [[-Async]] [-Ref] <XenRef[VIF]> [-XenAction] <XenVIFAction> [[-PassThru]] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]] [[-Async]] [-Uuid] <guid> [-XenAction] <XenVIFAction> [[-PassThru]] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]] [[-Async]]
```
### Parameters
| Name | Type | Required | Default Value | Description |
| :--- | :--- | :------- | :------------ | :---------- |
| Async | switch | False |  |  |
| BestEffort | switch | False |  |  |
| Confirm | switch | False |  |  |
| PassThru | switch | False |  |  |
| Ref | XenRef[VIF] | True |  |  |
| SessionOpaqueRef | string | False |  |  |
| Uuid | guid | True |  |  |
| VIF | VIF | True |  |  |
| WhatIf | switch | False |  |  |
| XenAction | XenVIFAction | True |  |  |
### Procedure
None

### Inputs
```
XenAPI.VIF
XenAPI.XenRef`1[[XenAPI.VIF, XenServer, Version=8.2.3.0, Culture=neutral, PublicKeyToken=d247b8b0ac7959e9]]
System.Guid

```
### Outputs
```
System.Object
```
### Links
None

### Examples

Invoke-XenVIF [-VIF] <VIF> -XenAction <XenVIFAction> [-PassThru] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [-Async] [<CommonParameters>]

Invoke-XenVIF [-Ref] <XenRef[VIF]> -XenAction <XenVIFAction> [-PassThru] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [-Async] [<CommonParameters>]

Invoke-XenVIF [-Uuid] <guid> -XenAction <XenVIFAction> [-PassThru] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [-Async] [<CommonParameters>]


## Invoke-XenVM

### Synopsis
None

### Description
None

### Syntax
```
Invoke-XenVM [-VM] <VM> [-XenAction] <XenVMAction> [[-PassThru]] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]] [[-Async]] [[-NewName] <string>] [-Ref] <XenRef[VM]> [-XenAction] <XenVMAction> [[-PassThru]] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]] [[-Async]] [[-NewName] <string>] [-Uuid] <guid> [-XenAction] <XenVMAction> [[-PassThru]] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]] [[-Async]] [[-NewName] <string>] [-Name] <string> [-XenAction] <XenVMAction> [[-PassThru]] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]] [[-Async]] [[-NewName] <string>]
```
### Parameters
| Name | Type | Required | Default Value | Description |
| :--- | :--- | :------- | :------------ | :---------- |
| Async | switch | False |  |  |
| BestEffort | switch | False |  |  |
| Confirm | switch | False |  |  |
| Name | string | True |  |  |
| NewName | string | False |  |  |
| PassThru | switch | False |  |  |
| Ref | XenRef[VM] | True |  |  |
| SessionOpaqueRef | string | False |  |  |
| Uuid | guid | True |  |  |
| VM | VM | True |  |  |
| WhatIf | switch | False |  |  |
| XenAction | XenVMAction | True |  |  |
### Procedure
None

### Inputs
```
XenAPI.VM
XenAPI.XenRef`1[[XenAPI.VM, XenServer, Version=8.2.3.0, Culture=neutral, PublicKeyToken=d247b8b0ac7959e9]]
System.Guid
System.String

```
### Outputs
```
System.Object
```
### Links
None

### Examples

Invoke-XenVM [-VM] <VM> -XenAction <XenVMAction> [-PassThru] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [-Async] [-NewName <string>] [<CommonParameters>]

Invoke-XenVM [-Ref] <XenRef[VM]> -XenAction <XenVMAction> [-PassThru] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [-Async] [-NewName <string>] [<CommonParameters>]

Invoke-XenVM [-Uuid] <guid> -XenAction <XenVMAction> [-PassThru] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [-Async] [-NewName <string>] [<CommonParameters>]

Invoke-XenVM [-Name] <string> -XenAction <XenVMAction> [-PassThru] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [-Async] [-NewName <string>] [<CommonParameters>]


## Invoke-XenVMAppliance

### Synopsis
None

### Description
None

### Syntax
```
Invoke-XenVMAppliance [-VMAppliance] <VM_appliance> [-XenAction] <XenVMApplianceAction> [[-PassThru]] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]] [[-Async]] [[-Paused] <bool>] [-Ref] <XenRef[VM_appliance]> [-XenAction] <XenVMApplianceAction> [[-PassThru]] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]] [[-Async]] [[-Paused] <bool>] [-Uuid] <guid> [-XenAction] <XenVMApplianceAction> [[-PassThru]] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]] [[-Async]] [[-Paused] <bool>] [-Name] <string> [-XenAction] <XenVMApplianceAction> [[-PassThru]] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]] [[-Async]] [[-Paused] <bool>]
```
### Parameters
| Name | Type | Required | Default Value | Description |
| :--- | :--- | :------- | :------------ | :---------- |
| Async | switch | False |  |  |
| BestEffort | switch | False |  |  |
| Confirm | switch | False |  |  |
| Name | string | True |  |  |
| PassThru | switch | False |  |  |
| Paused | bool | False |  |  |
| Ref | XenRef[VM_appliance] | True |  |  |
| SessionOpaqueRef | string | False |  |  |
| Uuid | guid | True |  |  |
| VMAppliance | VM_appliance | True |  |  |
| WhatIf | switch | False |  |  |
| XenAction | XenVMApplianceAction | True |  |  |
### Procedure
None

### Inputs
```
XenAPI.VM_appliance
XenAPI.XenRef`1[[XenAPI.VM_appliance, XenServer, Version=8.2.3.0, Culture=neutral, PublicKeyToken=d247b8b0ac7959e9]]
System.Guid
System.String

```
### Outputs
```
System.Object
```
### Links
None

### Examples

Invoke-XenVMAppliance [-VMAppliance] <VM_appliance> -XenAction <XenVMApplianceAction> [-PassThru] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [-Async] [-Paused <bool>] [<CommonParameters>]

Invoke-XenVMAppliance [-Ref] <XenRef[VM_appliance]> -XenAction <XenVMApplianceAction> [-PassThru] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [-Async] [-Paused <bool>] [<CommonParameters>]

Invoke-XenVMAppliance [-Uuid] <guid> -XenAction <XenVMApplianceAction> [-PassThru] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [-Async] [-Paused <bool>] [<CommonParameters>]

Invoke-XenVMAppliance [-Name] <string> -XenAction <XenVMApplianceAction> [-PassThru] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [-Async] [-Paused <bool>] [<CommonParameters>]


## Invoke-XenVMPP

### Synopsis
None

### Description
None

### Syntax
```
Invoke-XenVMPP [-VMPP] <VMPP> [-XenAction] <XenVMPPAction> [[-PassThru]] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]] [-Ref] <XenRef[VMPP]> [-XenAction] <XenVMPPAction> [[-PassThru]] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]] [-Uuid] <guid> [-XenAction] <XenVMPPAction> [[-PassThru]] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]] [-Name] <string> [-XenAction] <XenVMPPAction> [[-PassThru]] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]]
```
### Parameters
| Name | Type | Required | Default Value | Description |
| :--- | :--- | :------- | :------------ | :---------- |
| BestEffort | switch | False |  |  |
| Confirm | switch | False |  |  |
| Name | string | True |  |  |
| PassThru | switch | False |  |  |
| Ref | XenRef[VMPP] | True |  |  |
| SessionOpaqueRef | string | False |  |  |
| Uuid | guid | True |  |  |
| VMPP | VMPP | True |  |  |
| WhatIf | switch | False |  |  |
| XenAction | XenVMPPAction | True |  |  |
### Procedure
None

### Inputs
```
XenAPI.VMPP
XenAPI.XenRef`1[[XenAPI.VMPP, XenServer, Version=8.2.3.0, Culture=neutral, PublicKeyToken=d247b8b0ac7959e9]]
System.Guid
System.String

```
### Outputs
```
System.Object
```
### Links
None

### Examples

Invoke-XenVMPP [-VMPP] <VMPP> -XenAction <XenVMPPAction> [-PassThru] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [<CommonParameters>]

Invoke-XenVMPP [-Ref] <XenRef[VMPP]> -XenAction <XenVMPPAction> [-PassThru] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [<CommonParameters>]

Invoke-XenVMPP [-Uuid] <guid> -XenAction <XenVMPPAction> [-PassThru] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [<CommonParameters>]

Invoke-XenVMPP [-Name] <string> -XenAction <XenVMPPAction> [-PassThru] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [<CommonParameters>]


## Invoke-XenVMSS

### Synopsis
None

### Description
None

### Syntax
```
Invoke-XenVMSS [-VMSS] <VMSS> [-XenAction] <XenVMSSAction> [[-PassThru]] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]] [-Ref] <XenRef[VMSS]> [-XenAction] <XenVMSSAction> [[-PassThru]] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]] [-Uuid] <guid> [-XenAction] <XenVMSSAction> [[-PassThru]] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]] [-Name] <string> [-XenAction] <XenVMSSAction> [[-PassThru]] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]]
```
### Parameters
| Name | Type | Required | Default Value | Description |
| :--- | :--- | :------- | :------------ | :---------- |
| BestEffort | switch | False |  |  |
| Confirm | switch | False |  |  |
| Name | string | True |  |  |
| PassThru | switch | False |  |  |
| Ref | XenRef[VMSS] | True |  |  |
| SessionOpaqueRef | string | False |  |  |
| Uuid | guid | True |  |  |
| VMSS | VMSS | True |  |  |
| WhatIf | switch | False |  |  |
| XenAction | XenVMSSAction | True |  |  |
### Procedure
None

### Inputs
```
XenAPI.VMSS
XenAPI.XenRef`1[[XenAPI.VMSS, XenServer, Version=8.2.3.0, Culture=neutral, PublicKeyToken=d247b8b0ac7959e9]]
System.Guid
System.String

```
### Outputs
```
System.Object
```
### Links
None

### Examples

Invoke-XenVMSS [-VMSS] <VMSS> -XenAction <XenVMSSAction> [-PassThru] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [<CommonParameters>]

Invoke-XenVMSS [-Ref] <XenRef[VMSS]> -XenAction <XenVMSSAction> [-PassThru] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [<CommonParameters>]

Invoke-XenVMSS [-Uuid] <guid> -XenAction <XenVMSSAction> [-PassThru] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [<CommonParameters>]

Invoke-XenVMSS [-Name] <string> -XenAction <XenVMSSAction> [-PassThru] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [<CommonParameters>]


## Invoke-XenVUSB

### Synopsis
None

### Description
None

### Syntax
```
Invoke-XenVUSB [-VUSB] <VUSB> [-XenAction] <XenVUSBAction> [[-PassThru]] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]] [[-Async]] [-Ref] <XenRef[VUSB]> [-XenAction] <XenVUSBAction> [[-PassThru]] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]] [[-Async]] [-Uuid] <guid> [-XenAction] <XenVUSBAction> [[-PassThru]] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]] [[-Async]]
```
### Parameters
| Name | Type | Required | Default Value | Description |
| :--- | :--- | :------- | :------------ | :---------- |
| Async | switch | False |  |  |
| BestEffort | switch | False |  |  |
| Confirm | switch | False |  |  |
| PassThru | switch | False |  |  |
| Ref | XenRef[VUSB] | True |  |  |
| SessionOpaqueRef | string | False |  |  |
| Uuid | guid | True |  |  |
| VUSB | VUSB | True |  |  |
| WhatIf | switch | False |  |  |
| XenAction | XenVUSBAction | True |  |  |
### Procedure
None

### Inputs
```
XenAPI.VUSB
XenAPI.XenRef`1[[XenAPI.VUSB, XenServer, Version=8.2.3.0, Culture=neutral, PublicKeyToken=d247b8b0ac7959e9]]
System.Guid

```
### Outputs
```
System.Object
```
### Links
None

### Examples

Invoke-XenVUSB [-VUSB] <VUSB> -XenAction <XenVUSBAction> [-PassThru] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [-Async] [<CommonParameters>]

Invoke-XenVUSB [-Ref] <XenRef[VUSB]> -XenAction <XenVUSBAction> [-PassThru] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [-Async] [<CommonParameters>]

Invoke-XenVUSB [-Uuid] <guid> -XenAction <XenVUSBAction> [-PassThru] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [-Async] [<CommonParameters>]


## New-XenBond

### Synopsis
None

### Description
None

### Syntax
```
New-XenBond [-HashTable] <hashtable> [[-PassThru]] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]] [[-Async]] [-Record] <Bond> [[-PassThru]] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]] [[-Async]] [[-PassThru]] [[-Network] <XenRef[Network]>] [[-Members] <List[XenRef[PIF]]>] [[-MAC] <string>] [[-Mode] <bond_mode>] [[-Properties] <hashtable>] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]] [[-Async]]
```
### Parameters
| Name | Type | Required | Default Value | Description |
| :--- | :--- | :------- | :------------ | :---------- |
| Async | switch | False |  |  |
| BestEffort | switch | False |  |  |
| Confirm | switch | False |  |  |
| HashTable | hashtable | True |  |  |
| MAC | string | False |  |  |
| Members | List[XenRef[PIF]] | False |  |  |
| Mode | bond_mode | False |  |  |
| Network | XenRef[Network] | False |  |  |
| PassThru | switch | False |  |  |
| Properties | hashtable | False |  |  |
| Record | Bond | True |  |  |
| SessionOpaqueRef | string | False |  |  |
| WhatIf | switch | False |  |  |
### Procedure
None

### Inputs
```
None

```
### Outputs
```
XenAPI.Bond
XenAPI.Task
System.Void

```
### Links
None

### Examples

New-XenBond -HashTable <hashtable> [-PassThru] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [-Async] [<CommonParameters>]

New-XenBond -Record <Bond> [-PassThru] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [-Async] [<CommonParameters>]

New-XenBond [-PassThru] [-Network <XenRef[Network]>] [-Members <List[XenRef[PIF]]>] [-MAC <string>] [-Mode <bond_mode>] [-Properties <hashtable>] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [-Async] [<CommonParameters>]


## New-XenCluster

### Synopsis
None

### Description
None

### Syntax
```
New-XenCluster [-HashTable] <hashtable> [[-PassThru]] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]] [[-Async]] [-Record] <Cluster> [[-PassThru]] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]] [[-Async]] [[-PassThru]] [[-PIF] <XenRef[PIF]>] [[-ClusterStack] <string>] [[-PoolAutoJoin] <bool>] [[-TokenTimeout] <double>] [[-TokenTimeoutCoefficient] <double>] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]] [[-Async]]
```
### Parameters
| Name | Type | Required | Default Value | Description |
| :--- | :--- | :------- | :------------ | :---------- |
| Async | switch | False |  |  |
| BestEffort | switch | False |  |  |
| ClusterStack | string | False |  |  |
| Confirm | switch | False |  |  |
| HashTable | hashtable | True |  |  |
| PIF | XenRef[PIF] | False |  |  |
| PassThru | switch | False |  |  |
| PoolAutoJoin | bool | False |  |  |
| Record | Cluster | True |  |  |
| SessionOpaqueRef | string | False |  |  |
| TokenTimeout | double | False |  |  |
| TokenTimeoutCoefficient | double | False |  |  |
| WhatIf | switch | False |  |  |
### Procedure
None

### Inputs
```
None

```
### Outputs
```
XenAPI.Cluster
XenAPI.Task
System.Void

```
### Links
None

### Examples

New-XenCluster -HashTable <hashtable> [-PassThru] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [-Async] [<CommonParameters>]

New-XenCluster -Record <Cluster> [-PassThru] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [-Async] [<CommonParameters>]

New-XenCluster [-PassThru] [-PIF <XenRef[PIF]>] [-ClusterStack <string>] [-PoolAutoJoin <bool>] [-TokenTimeout <double>] [-TokenTimeoutCoefficient <double>] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [-Async] [<CommonParameters>]


## New-XenClusterHost

### Synopsis
None

### Description
None

### Syntax
```
New-XenClusterHost [-HashTable] <hashtable> [[-PassThru]] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]] [[-Async]] [-Record] <Cluster_host> [[-PassThru]] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]] [[-Async]] [[-PassThru]] [[-Cluster] <XenRef[Cluster]>] [[-XenHost] <XenRef[Host]>] [[-PIF] <XenRef[PIF]>] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]] [[-Async]]
```
### Parameters
| Name | Type | Required | Default Value | Description |
| :--- | :--- | :------- | :------------ | :---------- |
| Async | switch | False |  |  |
| BestEffort | switch | False |  |  |
| Cluster | XenRef[Cluster] | False |  |  |
| Confirm | switch | False |  |  |
| HashTable | hashtable | True |  |  |
| PIF | XenRef[PIF] | False |  |  |
| PassThru | switch | False |  |  |
| Record | Cluster_host | True |  |  |
| SessionOpaqueRef | string | False |  |  |
| WhatIf | switch | False |  |  |
| XenHost | XenRef[Host] | False |  |  |
### Procedure
None

### Inputs
```
None

```
### Outputs
```
XenAPI.Cluster_host
XenAPI.Task
System.Void

```
### Links
None

### Examples

New-XenClusterHost -HashTable <hashtable> [-PassThru] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [-Async] [<CommonParameters>]

New-XenClusterHost -Record <Cluster_host> [-PassThru] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [-Async] [<CommonParameters>]

New-XenClusterHost [-PassThru] [-Cluster <XenRef[Cluster]>] [-XenHost <XenRef[Host]>] [-PIF <XenRef[PIF]>] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [-Async] [<CommonParameters>]


## New-XenConsole

### Synopsis
None

### Description
None

### Syntax
```
New-XenConsole [-HashTable] <hashtable> [[-PassThru]] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]] [[-Async]] [-Record] <Console> [[-PassThru]] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]] [[-Async]] [[-PassThru]] [[-OtherConfig] <hashtable>] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]] [[-Async]]
```
### Parameters
| Name | Type | Required | Default Value | Description |
| :--- | :--- | :------- | :------------ | :---------- |
| Async | switch | False |  |  |
| BestEffort | switch | False |  |  |
| Confirm | switch | False |  |  |
| HashTable | hashtable | True |  |  |
| OtherConfig | hashtable | False |  |  |
| PassThru | switch | False |  |  |
| Record | Console | True |  |  |
| SessionOpaqueRef | string | False |  |  |
| WhatIf | switch | False |  |  |
### Procedure
None

### Inputs
```
None

```
### Outputs
```
XenAPI.Console
XenAPI.Task
System.Void

```
### Links
None

### Examples

New-XenConsole -HashTable <hashtable> [-PassThru] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [-Async] [<CommonParameters>]

New-XenConsole -Record <Console> [-PassThru] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [-Async] [<CommonParameters>]

New-XenConsole [-PassThru] [-OtherConfig <hashtable>] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [-Async] [<CommonParameters>]


## New-XenDRTask

### Synopsis
None

### Description
None

### Syntax
```
New-XenDRTask [-HashTable] <hashtable> [[-PassThru]] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]] [[-Async]] [-Record] <DR_task> [[-PassThru]] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]] [[-Async]] [[-PassThru]] [[-Type] <string>] [[-DeviceConfig] <hashtable>] [[-Whitelist] <string[]>] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]] [[-Async]]
```
### Parameters
| Name | Type | Required | Default Value | Description |
| :--- | :--- | :------- | :------------ | :---------- |
| Async | switch | False |  |  |
| BestEffort | switch | False |  |  |
| Confirm | switch | False |  |  |
| DeviceConfig | hashtable | False |  |  |
| HashTable | hashtable | True |  |  |
| PassThru | switch | False |  |  |
| Record | DR_task | True |  |  |
| SessionOpaqueRef | string | False |  |  |
| Type | string | False |  |  |
| WhatIf | switch | False |  |  |
| Whitelist | string[] | False |  |  |
### Procedure
None

### Inputs
```
None

```
### Outputs
```
XenAPI.DR_task
XenAPI.Task
System.Void

```
### Links
None

### Examples

New-XenDRTask -HashTable <hashtable> [-PassThru] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [-Async] [<CommonParameters>]

New-XenDRTask -Record <DR_task> [-PassThru] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [-Async] [<CommonParameters>]

New-XenDRTask [-PassThru] [-Type <string>] [-DeviceConfig <hashtable>] [-Whitelist <string[]>] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [-Async] [<CommonParameters>]


## New-XenGPUGroup

### Synopsis
None

### Description
None

### Syntax
```
New-XenGPUGroup [-HashTable] <hashtable> [[-PassThru]] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]] [[-Async]] [-Record] <GPU_group> [[-PassThru]] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]] [[-Async]] [[-PassThru]] [[-NameLabel] <string>] [[-NameDescription] <string>] [[-OtherConfig] <hashtable>] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]] [[-Async]]
```
### Parameters
| Name | Type | Required | Default Value | Description |
| :--- | :--- | :------- | :------------ | :---------- |
| Async | switch | False |  |  |
| BestEffort | switch | False |  |  |
| Confirm | switch | False |  |  |
| HashTable | hashtable | True |  |  |
| NameDescription | string | False |  |  |
| NameLabel | string | False |  |  |
| OtherConfig | hashtable | False |  |  |
| PassThru | switch | False |  |  |
| Record | GPU_group | True |  |  |
| SessionOpaqueRef | string | False |  |  |
| WhatIf | switch | False |  |  |
### Procedure
None

### Inputs
```
None

```
### Outputs
```
XenAPI.GPU_group
XenAPI.Task
System.Void

```
### Links
None

### Examples

New-XenGPUGroup -HashTable <hashtable> [-PassThru] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [-Async] [<CommonParameters>]

New-XenGPUGroup -Record <GPU_group> [-PassThru] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [-Async] [<CommonParameters>]

New-XenGPUGroup [-PassThru] [-NameLabel <string>] [-NameDescription <string>] [-OtherConfig <hashtable>] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [-Async] [<CommonParameters>]


## New-XenMessage

### Synopsis
None

### Description
None

### Syntax
```
New-XenMessage [-HashTable] <hashtable> [[-PassThru]] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]] [-Record] <Message> [[-PassThru]] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]] [[-PassThru]] [[-Name] <string>] [[-Priority] <long>] [[-Cls] <cls>] [[-ObjUuid] <string>] [[-Body] <string>] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]]
```
### Parameters
| Name | Type | Required | Default Value | Description |
| :--- | :--- | :------- | :------------ | :---------- |
| BestEffort | switch | False |  |  |
| Body | string | False |  |  |
| Cls | cls | False |  |  |
| Confirm | switch | False |  |  |
| HashTable | hashtable | True |  |  |
| Name | string | False |  |  |
| ObjUuid | string | False |  |  |
| PassThru | switch | False |  |  |
| Priority | long | False |  |  |
| Record | Message | True |  |  |
| SessionOpaqueRef | string | False |  |  |
| WhatIf | switch | False |  |  |
### Procedure
None

### Inputs
```
None

```
### Outputs
```
XenAPI.Message
System.Void

```
### Links
None

### Examples

New-XenMessage -HashTable <hashtable> [-PassThru] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [<CommonParameters>]

New-XenMessage -Record <Message> [-PassThru] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [<CommonParameters>]

New-XenMessage [-PassThru] [-Name <string>] [-Priority <long>] [-Cls <cls>] [-ObjUuid <string>] [-Body <string>] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [<CommonParameters>]


## New-XenNetwork

### Synopsis
None

### Description
None

### Syntax
```
New-XenNetwork [-HashTable] <hashtable> [[-PassThru]] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]] [[-Async]] [-Record] <Network> [[-PassThru]] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]] [[-Async]] [[-PassThru]] [[-NameLabel] <string>] [[-NameDescription] <string>] [[-MTU] <long>] [[-OtherConfig] <hashtable>] [[-Bridge] <string>] [[-Managed] <bool>] [[-Tags] <string[]>] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]] [[-Async]]
```
### Parameters
| Name | Type | Required | Default Value | Description |
| :--- | :--- | :------- | :------------ | :---------- |
| Async | switch | False |  |  |
| BestEffort | switch | False |  |  |
| Bridge | string | False |  |  |
| Confirm | switch | False |  |  |
| HashTable | hashtable | True |  |  |
| MTU | long | False |  |  |
| Managed | bool | False |  |  |
| NameDescription | string | False |  |  |
| NameLabel | string | False |  |  |
| OtherConfig | hashtable | False |  |  |
| PassThru | switch | False |  |  |
| Record | Network | True |  |  |
| SessionOpaqueRef | string | False |  |  |
| Tags | string[] | False |  |  |
| WhatIf | switch | False |  |  |
### Procedure
None

### Inputs
```
None

```
### Outputs
```
XenAPI.Network
XenAPI.Task
System.Void

```
### Links
None

### Examples

New-XenNetwork -HashTable <hashtable> [-PassThru] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [-Async] [<CommonParameters>]

New-XenNetwork -Record <Network> [-PassThru] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [-Async] [<CommonParameters>]

New-XenNetwork [-PassThru] [-NameLabel <string>] [-NameDescription <string>] [-MTU <long>] [-OtherConfig <hashtable>] [-Bridge <string>] [-Managed <bool>] [-Tags <string[]>] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [-Async] [<CommonParameters>]


## New-XenNetworkSriov

### Synopsis
None

### Description
None

### Syntax
```
New-XenNetworkSriov [-HashTable] <hashtable> [[-PassThru]] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]] [[-Async]] [-Record] <Network_sriov> [[-PassThru]] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]] [[-Async]] [[-PassThru]] [[-PIF] <XenRef[PIF]>] [[-Network] <XenRef[Network]>] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]] [[-Async]]
```
### Parameters
| Name | Type | Required | Default Value | Description |
| :--- | :--- | :------- | :------------ | :---------- |
| Async | switch | False |  |  |
| BestEffort | switch | False |  |  |
| Confirm | switch | False |  |  |
| HashTable | hashtable | True |  |  |
| Network | XenRef[Network] | False |  |  |
| PIF | XenRef[PIF] | False |  |  |
| PassThru | switch | False |  |  |
| Record | Network_sriov | True |  |  |
| SessionOpaqueRef | string | False |  |  |
| WhatIf | switch | False |  |  |
### Procedure
None

### Inputs
```
None

```
### Outputs
```
XenAPI.Network_sriov
XenAPI.Task
System.Void

```
### Links
None

### Examples

New-XenNetworkSriov -HashTable <hashtable> [-PassThru] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [-Async] [<CommonParameters>]

New-XenNetworkSriov -Record <Network_sriov> [-PassThru] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [-Async] [<CommonParameters>]

New-XenNetworkSriov [-PassThru] [-PIF <XenRef[PIF]>] [-Network <XenRef[Network]>] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [-Async] [<CommonParameters>]


## New-XenPBD

### Synopsis
None

### Description
None

### Syntax
```
New-XenPBD [-HashTable] <hashtable> [[-PassThru]] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]] [[-Async]] [-Record] <PBD> [[-PassThru]] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]] [[-Async]] [[-PassThru]] [[-XenHost] <XenRef[Host]>] [[-SR] <XenRef[SR]>] [[-DeviceConfig] <hashtable>] [[-OtherConfig] <hashtable>] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]] [[-Async]]
```
### Parameters
| Name | Type | Required | Default Value | Description |
| :--- | :--- | :------- | :------------ | :---------- |
| Async | switch | False |  |  |
| BestEffort | switch | False |  |  |
| Confirm | switch | False |  |  |
| DeviceConfig | hashtable | False |  |  |
| HashTable | hashtable | True |  |  |
| OtherConfig | hashtable | False |  |  |
| PassThru | switch | False |  |  |
| Record | PBD | True |  |  |
| SR | XenRef[SR] | False |  |  |
| SessionOpaqueRef | string | False |  |  |
| WhatIf | switch | False |  |  |
| XenHost | XenRef[Host] | False |  |  |
### Procedure
None

### Inputs
```
None

```
### Outputs
```
XenAPI.PBD
XenAPI.Task
System.Void

```
### Links
None

### Examples

New-XenPBD -HashTable <hashtable> [-PassThru] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [-Async] [<CommonParameters>]

New-XenPBD -Record <PBD> [-PassThru] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [-Async] [<CommonParameters>]

New-XenPBD [-PassThru] [-XenHost <XenRef[Host]>] [-SR <XenRef[SR]>] [-DeviceConfig <hashtable>] [-OtherConfig <hashtable>] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [-Async] [<CommonParameters>]


## New-XenPVSCacheStorage

### Synopsis
None

### Description
None

### Syntax
```
New-XenPVSCacheStorage [-HashTable] <hashtable> [[-PassThru]] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]] [[-Async]] [-Record] <PVS_cache_storage> [[-PassThru]] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]] [[-Async]] [[-PassThru]] [[-XenHost] <XenRef[Host]>] [[-SR] <XenRef[SR]>] [[-Site] <XenRef[PVS_site]>] [[-Size] <long>] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]] [[-Async]]
```
### Parameters
| Name | Type | Required | Default Value | Description |
| :--- | :--- | :------- | :------------ | :---------- |
| Async | switch | False |  |  |
| BestEffort | switch | False |  |  |
| Confirm | switch | False |  |  |
| HashTable | hashtable | True |  |  |
| PassThru | switch | False |  |  |
| Record | PVS_cache_storage | True |  |  |
| SR | XenRef[SR] | False |  |  |
| SessionOpaqueRef | string | False |  |  |
| Site | XenRef[PVS_site] | False |  |  |
| Size | long | False |  |  |
| WhatIf | switch | False |  |  |
| XenHost | XenRef[Host] | False |  |  |
### Procedure
None

### Inputs
```
None

```
### Outputs
```
XenAPI.PVS_cache_storage
XenAPI.Task
System.Void

```
### Links
None

### Examples

New-XenPVSCacheStorage -HashTable <hashtable> [-PassThru] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [-Async] [<CommonParameters>]

New-XenPVSCacheStorage -Record <PVS_cache_storage> [-PassThru] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [-Async] [<CommonParameters>]

New-XenPVSCacheStorage [-PassThru] [-XenHost <XenRef[Host]>] [-SR <XenRef[SR]>] [-Site <XenRef[PVS_site]>] [-Size <long>] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [-Async] [<CommonParameters>]


## New-XenPVSProxy

### Synopsis
None

### Description
None

### Syntax
```
New-XenPVSProxy [-HashTable] <hashtable> [[-PassThru]] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]] [[-Async]] [-Record] <PVS_proxy> [[-PassThru]] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]] [[-Async]] [[-PassThru]] [[-Site] <XenRef[PVS_site]>] [[-VIF] <XenRef[VIF]>] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]] [[-Async]]
```
### Parameters
| Name | Type | Required | Default Value | Description |
| :--- | :--- | :------- | :------------ | :---------- |
| Async | switch | False |  |  |
| BestEffort | switch | False |  |  |
| Confirm | switch | False |  |  |
| HashTable | hashtable | True |  |  |
| PassThru | switch | False |  |  |
| Record | PVS_proxy | True |  |  |
| SessionOpaqueRef | string | False |  |  |
| Site | XenRef[PVS_site] | False |  |  |
| VIF | XenRef[VIF] | False |  |  |
| WhatIf | switch | False |  |  |
### Procedure
None

### Inputs
```
None

```
### Outputs
```
XenAPI.PVS_proxy
XenAPI.Task
System.Void

```
### Links
None

### Examples

New-XenPVSProxy -HashTable <hashtable> [-PassThru] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [-Async] [<CommonParameters>]

New-XenPVSProxy -Record <PVS_proxy> [-PassThru] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [-Async] [<CommonParameters>]

New-XenPVSProxy [-PassThru] [-Site <XenRef[PVS_site]>] [-VIF <XenRef[VIF]>] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [-Async] [<CommonParameters>]


## New-XenSecret

### Synopsis
None

### Description
None

### Syntax
```
New-XenSecret [-HashTable] <hashtable> [[-PassThru]] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]] [[-Async]] [-Record] <Secret> [[-PassThru]] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]] [[-Async]] [[-PassThru]] [[-Value] <string>] [[-OtherConfig] <hashtable>] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]] [[-Async]]
```
### Parameters
| Name | Type | Required | Default Value | Description |
| :--- | :--- | :------- | :------------ | :---------- |
| Async | switch | False |  |  |
| BestEffort | switch | False |  |  |
| Confirm | switch | False |  |  |
| HashTable | hashtable | True |  |  |
| OtherConfig | hashtable | False |  |  |
| PassThru | switch | False |  |  |
| Record | Secret | True |  |  |
| SessionOpaqueRef | string | False |  |  |
| Value | string | False |  |  |
| WhatIf | switch | False |  |  |
### Procedure
None

### Inputs
```
None

```
### Outputs
```
XenAPI.Secret
XenAPI.Task
System.Void

```
### Links
None

### Examples

New-XenSecret -HashTable <hashtable> [-PassThru] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [-Async] [<CommonParameters>]

New-XenSecret -Record <Secret> [-PassThru] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [-Async] [<CommonParameters>]

New-XenSecret [-PassThru] [-Value <string>] [-OtherConfig <hashtable>] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [-Async] [<CommonParameters>]


## New-XenSR

### Synopsis
None

### Description
None

### Syntax
```
New-XenSR [-HashTable] <hashtable> [[-PassThru]] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]] [[-Async]] [-Record] <SR> [[-PassThru]] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]] [[-Async]] [[-PassThru]] [[-XenHost] <XenRef[Host]>] [[-DeviceConfig] <hashtable>] [[-PhysicalSize] <long>] [[-NameLabel] <string>] [[-NameDescription] <string>] [[-Type] <string>] [[-ContentType] <string>] [[-Shared] <bool>] [[-SmConfig] <hashtable>] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]] [[-Async]]
```
### Parameters
| Name | Type | Required | Default Value | Description |
| :--- | :--- | :------- | :------------ | :---------- |
| Async | switch | False |  |  |
| BestEffort | switch | False |  |  |
| Confirm | switch | False |  |  |
| ContentType | string | False |  |  |
| DeviceConfig | hashtable | False |  |  |
| HashTable | hashtable | True |  |  |
| NameDescription | string | False |  |  |
| NameLabel | string | False |  |  |
| PassThru | switch | False |  |  |
| PhysicalSize | long | False |  |  |
| Record | SR | True |  |  |
| SessionOpaqueRef | string | False |  |  |
| Shared | bool | False |  |  |
| SmConfig | hashtable | False |  |  |
| Type | string | False |  |  |
| WhatIf | switch | False |  |  |
| XenHost | XenRef[Host] | False |  |  |
### Procedure
None

### Inputs
```
None

```
### Outputs
```
XenAPI.SR
XenAPI.Task
System.Void

```
### Links
None

### Examples

New-XenSR -HashTable <hashtable> [-PassThru] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [-Async] [<CommonParameters>]

New-XenSR -Record <SR> [-PassThru] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [-Async] [<CommonParameters>]

New-XenSR [-PassThru] [-XenHost <XenRef[Host]>] [-DeviceConfig <hashtable>] [-PhysicalSize <long>] [-NameLabel <string>] [-NameDescription <string>] [-Type <string>] [-ContentType <string>] [-Shared <bool>] [-SmConfig <hashtable>] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [-Async] [<CommonParameters>]


## New-XenSubject

### Synopsis
None

### Description
None

### Syntax
```
New-XenSubject [-HashTable] <hashtable> [[-PassThru]] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]] [[-Async]] [-Record] <Subject> [[-PassThru]] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]] [[-Async]] [[-PassThru]] [[-SubjectIdentifier] <string>] [[-OtherConfig] <hashtable>] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]] [[-Async]]
```
### Parameters
| Name | Type | Required | Default Value | Description |
| :--- | :--- | :------- | :------------ | :---------- |
| Async | switch | False |  |  |
| BestEffort | switch | False |  |  |
| Confirm | switch | False |  |  |
| HashTable | hashtable | True |  |  |
| OtherConfig | hashtable | False |  |  |
| PassThru | switch | False |  |  |
| Record | Subject | True |  |  |
| SessionOpaqueRef | string | False |  |  |
| SubjectIdentifier | string | False |  |  |
| WhatIf | switch | False |  |  |
### Procedure
None

### Inputs
```
None

```
### Outputs
```
XenAPI.Subject
XenAPI.Task
System.Void

```
### Links
None

### Examples

New-XenSubject -HashTable <hashtable> [-PassThru] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [-Async] [<CommonParameters>]

New-XenSubject -Record <Subject> [-PassThru] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [-Async] [<CommonParameters>]

New-XenSubject [-PassThru] [-SubjectIdentifier <string>] [-OtherConfig <hashtable>] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [-Async] [<CommonParameters>]


## New-XenTask

### Synopsis
None

### Description
None

### Syntax
```
New-XenTask [-HashTable] <hashtable> [[-PassThru]] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]] [-Record] <Task> [[-PassThru]] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]] [[-PassThru]] [[-Label] <string>] [[-Description] <string>] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]]
```
### Parameters
| Name | Type | Required | Default Value | Description |
| :--- | :--- | :------- | :------------ | :---------- |
| BestEffort | switch | False |  |  |
| Confirm | switch | False |  |  |
| Description | string | False |  |  |
| HashTable | hashtable | True |  |  |
| Label | string | False |  |  |
| PassThru | switch | False |  |  |
| Record | Task | True |  |  |
| SessionOpaqueRef | string | False |  |  |
| WhatIf | switch | False |  |  |
### Procedure
None

### Inputs
```
None

```
### Outputs
```
XenAPI.Task
System.Void

```
### Links
None

### Examples

New-XenTask -HashTable <hashtable> [-PassThru] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [<CommonParameters>]

New-XenTask -Record <Task> [-PassThru] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [<CommonParameters>]

New-XenTask [-PassThru] [-Label <string>] [-Description <string>] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [<CommonParameters>]


## New-XenTunnel

### Synopsis
None

### Description
None

### Syntax
```
New-XenTunnel [-HashTable] <hashtable> [[-PassThru]] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]] [[-Async]] [-Record] <Tunnel> [[-PassThru]] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]] [[-Async]] [[-PassThru]] [[-TransportPIF] <XenRef[PIF]>] [[-Network] <XenRef[Network]>] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]] [[-Async]]
```
### Parameters
| Name | Type | Required | Default Value | Description |
| :--- | :--- | :------- | :------------ | :---------- |
| Async | switch | False |  |  |
| BestEffort | switch | False |  |  |
| Confirm | switch | False |  |  |
| HashTable | hashtable | True |  |  |
| Network | XenRef[Network] | False |  |  |
| PassThru | switch | False |  |  |
| Record | Tunnel | True |  |  |
| SessionOpaqueRef | string | False |  |  |
| TransportPIF | XenRef[PIF] | False |  |  |
| WhatIf | switch | False |  |  |
### Procedure
None

### Inputs
```
None

```
### Outputs
```
XenAPI.Tunnel
XenAPI.Task
System.Void

```
### Links
None

### Examples

New-XenTunnel -HashTable <hashtable> [-PassThru] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [-Async] [<CommonParameters>]

New-XenTunnel -Record <Tunnel> [-PassThru] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [-Async] [<CommonParameters>]

New-XenTunnel [-PassThru] [-TransportPIF <XenRef[PIF]>] [-Network <XenRef[Network]>] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [-Async] [<CommonParameters>]


## New-XenUSBGroup

### Synopsis
None

### Description
None

### Syntax
```
New-XenUSBGroup [-HashTable] <hashtable> [[-PassThru]] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]] [[-Async]] [-Record] <USB_group> [[-PassThru]] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]] [[-Async]] [[-PassThru]] [[-NameLabel] <string>] [[-NameDescription] <string>] [[-OtherConfig] <hashtable>] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]] [[-Async]]
```
### Parameters
| Name | Type | Required | Default Value | Description |
| :--- | :--- | :------- | :------------ | :---------- |
| Async | switch | False |  |  |
| BestEffort | switch | False |  |  |
| Confirm | switch | False |  |  |
| HashTable | hashtable | True |  |  |
| NameDescription | string | False |  |  |
| NameLabel | string | False |  |  |
| OtherConfig | hashtable | False |  |  |
| PassThru | switch | False |  |  |
| Record | USB_group | True |  |  |
| SessionOpaqueRef | string | False |  |  |
| WhatIf | switch | False |  |  |
### Procedure
None

### Inputs
```
None

```
### Outputs
```
XenAPI.USB_group
XenAPI.Task
System.Void

```
### Links
None

### Examples

New-XenUSBGroup -HashTable <hashtable> [-PassThru] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [-Async] [<CommonParameters>]

New-XenUSBGroup -Record <USB_group> [-PassThru] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [-Async] [<CommonParameters>]

New-XenUSBGroup [-PassThru] [-NameLabel <string>] [-NameDescription <string>] [-OtherConfig <hashtable>] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [-Async] [<CommonParameters>]


## New-XenUser

### Synopsis
None

### Description
None

### Syntax
```
New-XenUser [-HashTable] <hashtable> [[-PassThru]] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]] [[-Async]] [-Record] <User> [[-PassThru]] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]] [[-Async]] [[-PassThru]] [[-ShortName] <string>] [[-Fullname] <string>] [[-OtherConfig] <hashtable>] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]] [[-Async]]
```
### Parameters
| Name | Type | Required | Default Value | Description |
| :--- | :--- | :------- | :------------ | :---------- |
| Async | switch | False |  |  |
| BestEffort | switch | False |  |  |
| Confirm | switch | False |  |  |
| Fullname | string | False |  |  |
| HashTable | hashtable | True |  |  |
| OtherConfig | hashtable | False |  |  |
| PassThru | switch | False |  |  |
| Record | User | True |  |  |
| SessionOpaqueRef | string | False |  |  |
| ShortName | string | False |  |  |
| WhatIf | switch | False |  |  |
### Procedure
None

### Inputs
```
None

```
### Outputs
```
XenAPI.User
XenAPI.Task
System.Void

```
### Links
None

### Examples

New-XenUser -HashTable <hashtable> [-PassThru] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [-Async] [<CommonParameters>]

New-XenUser -Record <User> [-PassThru] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [-Async] [<CommonParameters>]

New-XenUser [-PassThru] [-ShortName <string>] [-Fullname <string>] [-OtherConfig <hashtable>] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [-Async] [<CommonParameters>]


## New-XenVBD

### Synopsis
None

### Description
None

### Syntax
```
New-XenVBD [-HashTable] <hashtable> [[-PassThru]] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]] [[-Async]] [-Record] <VBD> [[-PassThru]] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]] [[-Async]] [[-PassThru]] [[-VM] <XenRef[VM]>] [[-VDI] <XenRef[VDI]>] [[-Userdevice] <string>] [[-Bootable] <bool>] [[-Mode] <vbd_mode>] [[-Type] <vbd_type>] [[-Unpluggable] <bool>] [[-Empty] <bool>] [[-OtherConfig] <hashtable>] [[-QosAlgorithmType] <string>] [[-QosAlgorithmParams] <hashtable>] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]] [[-Async]]
```
### Parameters
| Name | Type | Required | Default Value | Description |
| :--- | :--- | :------- | :------------ | :---------- |
| Async | switch | False |  |  |
| BestEffort | switch | False |  |  |
| Bootable | bool | False |  |  |
| Confirm | switch | False |  |  |
| Empty | bool | False |  |  |
| HashTable | hashtable | True |  |  |
| Mode | vbd_mode | False |  |  |
| OtherConfig | hashtable | False |  |  |
| PassThru | switch | False |  |  |
| QosAlgorithmParams | hashtable | False |  |  |
| QosAlgorithmType | string | False |  |  |
| Record | VBD | True |  |  |
| SessionOpaqueRef | string | False |  |  |
| Type | vbd_type | False |  |  |
| Unpluggable | bool | False |  |  |
| Userdevice | string | False |  |  |
| VDI | XenRef[VDI] | False |  |  |
| VM | XenRef[VM] | False |  |  |
| WhatIf | switch | False |  |  |
### Procedure
None

### Inputs
```
None

```
### Outputs
```
XenAPI.VBD
XenAPI.Task
System.Void

```
### Links
None

### Examples

New-XenVBD -HashTable <hashtable> [-PassThru] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [-Async] [<CommonParameters>]

New-XenVBD -Record <VBD> [-PassThru] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [-Async] [<CommonParameters>]

New-XenVBD [-PassThru] [-VM <XenRef[VM]>] [-VDI <XenRef[VDI]>] [-Userdevice <string>] [-Bootable <bool>] [-Mode <vbd_mode>] [-Type <vbd_type>] [-Unpluggable <bool>] [-Empty <bool>] [-OtherConfig <hashtable>] [-QosAlgorithmType <string>] [-QosAlgorithmParams <hashtable>] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [-Async] [<CommonParameters>]


## New-XenVDI

### Synopsis
None

### Description
None

### Syntax
```
New-XenVDI [-HashTable] <hashtable> [[-PassThru]] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]] [[-Async]] [-Record] <VDI> [[-PassThru]] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]] [[-Async]] [[-PassThru]] [[-NameLabel] <string>] [[-NameDescription] <string>] [[-SR] <XenRef[SR]>] [[-VirtualSize] <long>] [[-Type] <vdi_type>] [[-Sharable] <bool>] [[-ReadOnly] <bool>] [[-OtherConfig] <hashtable>] [[-XenstoreData] <hashtable>] [[-SmConfig] <hashtable>] [[-Tags] <string[]>] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]] [[-Async]]
```
### Parameters
| Name | Type | Required | Default Value | Description |
| :--- | :--- | :------- | :------------ | :---------- |
| Async | switch | False |  |  |
| BestEffort | switch | False |  |  |
| Confirm | switch | False |  |  |
| HashTable | hashtable | True |  |  |
| NameDescription | string | False |  |  |
| NameLabel | string | False |  |  |
| OtherConfig | hashtable | False |  |  |
| PassThru | switch | False |  |  |
| ReadOnly | bool | False |  |  |
| Record | VDI | True |  |  |
| SR | XenRef[SR] | False |  |  |
| SessionOpaqueRef | string | False |  |  |
| Sharable | bool | False |  |  |
| SmConfig | hashtable | False |  |  |
| Tags | string[] | False |  |  |
| Type | vdi_type | False |  |  |
| VirtualSize | long | False |  |  |
| WhatIf | switch | False |  |  |
| XenstoreData | hashtable | False |  |  |
### Procedure
None

### Inputs
```
None

```
### Outputs
```
XenAPI.VDI
XenAPI.Task
System.Void

```
### Links
None

### Examples

New-XenVDI -HashTable <hashtable> [-PassThru] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [-Async] [<CommonParameters>]

New-XenVDI -Record <VDI> [-PassThru] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [-Async] [<CommonParameters>]

New-XenVDI [-PassThru] [-NameLabel <string>] [-NameDescription <string>] [-SR <XenRef[SR]>] [-VirtualSize <long>] [-Type <vdi_type>] [-Sharable <bool>] [-ReadOnly <bool>] [-OtherConfig <hashtable>] [-XenstoreData <hashtable>] [-SmConfig <hashtable>] [-Tags <string[]>] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [-Async] [<CommonParameters>]


## New-XenVGPU

### Synopsis
None

### Description
None

### Syntax
```
New-XenVGPU [-HashTable] <hashtable> [[-PassThru]] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]] [[-Async]] [-Record] <VGPU> [[-PassThru]] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]] [[-Async]] [[-PassThru]] [[-VM] <XenRef[VM]>] [[-GPUGroup] <XenRef[GPU_group]>] [[-Device] <string>] [[-OtherConfig] <hashtable>] [[-Type] <XenRef[VGPU_type]>] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]] [[-Async]]
```
### Parameters
| Name | Type | Required | Default Value | Description |
| :--- | :--- | :------- | :------------ | :---------- |
| Async | switch | False |  |  |
| BestEffort | switch | False |  |  |
| Confirm | switch | False |  |  |
| Device | string | False |  |  |
| GPUGroup | XenRef[GPU_group] | False |  |  |
| HashTable | hashtable | True |  |  |
| OtherConfig | hashtable | False |  |  |
| PassThru | switch | False |  |  |
| Record | VGPU | True |  |  |
| SessionOpaqueRef | string | False |  |  |
| Type | XenRef[VGPU_type] | False |  |  |
| VM | XenRef[VM] | False |  |  |
| WhatIf | switch | False |  |  |
### Procedure
None

### Inputs
```
None

```
### Outputs
```
XenAPI.VGPU
XenAPI.Task
System.Void

```
### Links
None

### Examples

New-XenVGPU -HashTable <hashtable> [-PassThru] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [-Async] [<CommonParameters>]

New-XenVGPU -Record <VGPU> [-PassThru] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [-Async] [<CommonParameters>]

New-XenVGPU [-PassThru] [-VM <XenRef[VM]>] [-GPUGroup <XenRef[GPU_group]>] [-Device <string>] [-OtherConfig <hashtable>] [-Type <XenRef[VGPU_type]>] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [-Async] [<CommonParameters>]


## New-XenVIF

### Synopsis
None

### Description
None

### Syntax
```
New-XenVIF [-HashTable] <hashtable> [[-PassThru]] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]] [[-Async]] [-Record] <VIF> [[-PassThru]] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]] [[-Async]] [[-PassThru]] [[-Device] <string>] [[-Network] <XenRef[Network]>] [[-VM] <XenRef[VM]>] [[-MAC] <string>] [[-MTU] <long>] [[-OtherConfig] <hashtable>] [[-QosAlgorithmType] <string>] [[-QosAlgorithmParams] <hashtable>] [[-LockingMode] <vif_locking_mode>] [[-Ipv4Allowed] <string[]>] [[-Ipv6Allowed] <string[]>] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]] [[-Async]]
```
### Parameters
| Name | Type | Required | Default Value | Description |
| :--- | :--- | :------- | :------------ | :---------- |
| Async | switch | False |  |  |
| BestEffort | switch | False |  |  |
| Confirm | switch | False |  |  |
| Device | string | False |  |  |
| HashTable | hashtable | True |  |  |
| Ipv4Allowed | string[] | False |  |  |
| Ipv6Allowed | string[] | False |  |  |
| LockingMode | vif_locking_mode | False |  |  |
| MAC | string | False |  |  |
| MTU | long | False |  |  |
| Network | XenRef[Network] | False |  |  |
| OtherConfig | hashtable | False |  |  |
| PassThru | switch | False |  |  |
| QosAlgorithmParams | hashtable | False |  |  |
| QosAlgorithmType | string | False |  |  |
| Record | VIF | True |  |  |
| SessionOpaqueRef | string | False |  |  |
| VM | XenRef[VM] | False |  |  |
| WhatIf | switch | False |  |  |
### Procedure
None

### Inputs
```
None

```
### Outputs
```
XenAPI.VIF
XenAPI.Task
System.Void

```
### Links
None

### Examples

New-XenVIF -HashTable <hashtable> [-PassThru] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [-Async] [<CommonParameters>]

New-XenVIF -Record <VIF> [-PassThru] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [-Async] [<CommonParameters>]

New-XenVIF [-PassThru] [-Device <string>] [-Network <XenRef[Network]>] [-VM <XenRef[VM]>] [-MAC <string>] [-MTU <long>] [-OtherConfig <hashtable>] [-QosAlgorithmType <string>] [-QosAlgorithmParams <hashtable>] [-LockingMode <vif_locking_mode>] [-Ipv4Allowed <string[]>] [-Ipv6Allowed <string[]>] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [-Async] [<CommonParameters>]


## New-XenVLAN

### Synopsis
None

### Description
None

### Syntax
```
New-XenVLAN [-HashTable] <hashtable> [[-PassThru]] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]] [[-Async]] [-Record] <VLAN> [[-PassThru]] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]] [[-Async]] [[-PassThru]] [[-TaggedPIF] <XenRef[PIF]>] [[-Tag] <long>] [[-Network] <XenRef[Network]>] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]] [[-Async]]
```
### Parameters
| Name | Type | Required | Default Value | Description |
| :--- | :--- | :------- | :------------ | :---------- |
| Async | switch | False |  |  |
| BestEffort | switch | False |  |  |
| Confirm | switch | False |  |  |
| HashTable | hashtable | True |  |  |
| Network | XenRef[Network] | False |  |  |
| PassThru | switch | False |  |  |
| Record | VLAN | True |  |  |
| SessionOpaqueRef | string | False |  |  |
| Tag | long | False |  |  |
| TaggedPIF | XenRef[PIF] | False |  |  |
| WhatIf | switch | False |  |  |
### Procedure
None

### Inputs
```
None

```
### Outputs
```
XenAPI.VLAN
XenAPI.Task
System.Void

```
### Links
None

### Examples

New-XenVLAN -HashTable <hashtable> [-PassThru] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [-Async] [<CommonParameters>]

New-XenVLAN -Record <VLAN> [-PassThru] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [-Async] [<CommonParameters>]

New-XenVLAN [-PassThru] [-TaggedPIF <XenRef[PIF]>] [-Tag <long>] [-Network <XenRef[Network]>] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [-Async] [<CommonParameters>]


## New-XenVM

### Synopsis
None

### Description
None

### Syntax
```
New-XenVM [-HashTable] <hashtable> [[-PassThru]] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]] [[-Async]] [-Record] <VM> [[-PassThru]] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]] [[-Async]] [[-PassThru]] [[-NameLabel] <string>] [[-NameDescription] <string>] [[-UserVersion] <long>] [[-IsATemplate] <bool>] [[-Affinity] <XenRef[Host]>] [[-MemoryTarget] <long>] [[-MemoryStaticMax] <long>] [[-MemoryDynamicMax] <long>] [[-MemoryDynamicMin] <long>] [[-MemoryStaticMin] <long>] [[-VCPUsParams] <hashtable>] [[-VCPUsMax] <long>] [[-VCPUsAtStartup] <long>] [[-ActionsAfterShutdown] <on_normal_exit>] [[-ActionsAfterReboot] <on_normal_exit>] [[-ActionsAfterCrash] <on_crash_behaviour>] [[-PVBootloader] <string>] [[-PVKernel] <string>] [[-PVRamdisk] <string>] [[-PVArgs] <string>] [[-PVBootloaderArgs] <string>] [[-PVLegacyArgs] <string>] [[-HVMBootPolicy] <string>] [[-HVMBootParams] <hashtable>] [[-HVMShadowMultiplier] <double>] [[-Platform] <hashtable>] [[-PCIBus] <string>] [[-OtherConfig] <hashtable>] [[-Recommendations] <string>] [[-XenstoreData] <hashtable>] [[-HaAlwaysRun] <bool>] [[-HaRestartPriority] <string>] [[-Tags] <string[]>] [[-BlockedOperations] <hashtable>] [[-ProtectionPolicy] <XenRef[VMPP]>] [[-IsSnapshotFromVmpp] <bool>] [[-SnapshotSchedule] <XenRef[VMSS]>] [[-IsVmssSnapshot] <bool>] [[-Appliance] <XenRef[VM_appliance]>] [[-StartDelay] <long>] [[-ShutdownDelay] <long>] [[-Order] <long>] [[-SuspendSR] <XenRef[SR]>] [[-Version] <long>] [[-GenerationId] <string>] [[-HardwarePlatformVersion] <long>] [[-HasVendorDevice] <bool>] [[-ReferenceLabel] <string>] [[-DomainType] <domain_type>] [[-NVRAM] <hashtable>] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]] [[-Async]]
```
### Parameters
| Name | Type | Required | Default Value | Description |
| :--- | :--- | :------- | :------------ | :---------- |
| ActionsAfterCrash | on_crash_behaviour | False |  |  |
| ActionsAfterReboot | on_normal_exit | False |  |  |
| ActionsAfterShutdown | on_normal_exit | False |  |  |
| Affinity | XenRef[Host] | False |  |  |
| Appliance | XenRef[VM_appliance] | False |  |  |
| Async | switch | False |  |  |
| BestEffort | switch | False |  |  |
| BlockedOperations | hashtable | False |  |  |
| Confirm | switch | False |  |  |
| DomainType | domain_type | False |  |  |
| GenerationId | string | False |  |  |
| HVMBootParams | hashtable | False |  |  |
| HVMBootPolicy | string | False |  |  |
| HVMShadowMultiplier | double | False |  |  |
| HaAlwaysRun | bool | False |  |  |
| HaRestartPriority | string | False |  |  |
| HardwarePlatformVersion | long | False |  |  |
| HasVendorDevice | bool | False |  |  |
| HashTable | hashtable | True |  |  |
| IsATemplate | bool | False |  |  |
| IsSnapshotFromVmpp | bool | False |  |  |
| IsVmssSnapshot | bool | False |  |  |
| MemoryDynamicMax | long | False |  |  |
| MemoryDynamicMin | long | False |  |  |
| MemoryStaticMax | long | False |  |  |
| MemoryStaticMin | long | False |  |  |
| MemoryTarget | long | False |  |  |
| NVRAM | hashtable | False |  |  |
| NameDescription | string | False |  |  |
| NameLabel | string | False |  |  |
| Order | long | False |  |  |
| OtherConfig | hashtable | False |  |  |
| PCIBus | string | False |  |  |
| PVArgs | string | False |  |  |
| PVBootloader | string | False |  |  |
| PVBootloaderArgs | string | False |  |  |
| PVKernel | string | False |  |  |
| PVLegacyArgs | string | False |  |  |
| PVRamdisk | string | False |  |  |
| PassThru | switch | False |  |  |
| Platform | hashtable | False |  |  |
| ProtectionPolicy | XenRef[VMPP] | False |  |  |
| Recommendations | string | False |  |  |
| Record | VM | True |  |  |
| ReferenceLabel | string | False |  |  |
| SessionOpaqueRef | string | False |  |  |
| ShutdownDelay | long | False |  |  |
| SnapshotSchedule | XenRef[VMSS] | False |  |  |
| StartDelay | long | False |  |  |
| SuspendSR | XenRef[SR] | False |  |  |
| Tags | string[] | False |  |  |
| UserVersion | long | False |  |  |
| VCPUsAtStartup | long | False |  |  |
| VCPUsMax | long | False |  |  |
| VCPUsParams | hashtable | False |  |  |
| Version | long | False |  |  |
| WhatIf | switch | False |  |  |
| XenstoreData | hashtable | False |  |  |
### Procedure
None

### Inputs
```
None

```
### Outputs
```
XenAPI.VM
XenAPI.Task
System.Void

```
### Links
None

### Examples

New-XenVM -HashTable <hashtable> [-PassThru] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [-Async] [<CommonParameters>]

New-XenVM -Record <VM> [-PassThru] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [-Async] [<CommonParameters>]

New-XenVM [-PassThru] [-NameLabel <string>] [-NameDescription <string>] [-UserVersion <long>] [-IsATemplate <bool>] [-Affinity <XenRef[Host]>] [-MemoryTarget <long>] [-MemoryStaticMax <long>] [-MemoryDynamicMax <long>] [-MemoryDynamicMin <long>] [-MemoryStaticMin <long>] [-VCPUsParams <hashtable>] [-VCPUsMax <long>] [-VCPUsAtStartup <long>] [-ActionsAfterShutdown <on_normal_exit>] [-ActionsAfterReboot <on_normal_exit>] [-ActionsAfterCrash <on_crash_behaviour>] [-PVBootloader <string>] [-PVKernel <string>] [-PVRamdisk <string>] [-PVArgs <string>] [-PVBootloaderArgs <string>] [-PVLegacyArgs <string>] [-HVMBootPolicy <string>] [-HVMBootParams <hashtable>] [-HVMShadowMultiplier <double>] [-Platform <hashtable>] [-PCIBus <string>] [-OtherConfig <hashtable>] [-Recommendations <string>] [-XenstoreData <hashtable>] [-HaAlwaysRun <bool>] [-HaRestartPriority <string>] [-Tags <string[]>] [-BlockedOperations <hashtable>] [-ProtectionPolicy <XenRef[VMPP]>] [-IsSnapshotFromVmpp <bool>] [-SnapshotSchedule <XenRef[VMSS]>] [-IsVmssSnapshot <bool>] [-Appliance <XenRef[VM_appliance]>] [-StartDelay <long>] [-ShutdownDelay <long>] [-Order <long>] [-SuspendSR <XenRef[SR]>] [-Version <long>] [-GenerationId <string>] [-HardwarePlatformVersion <long>] [-HasVendorDevice <bool>] [-ReferenceLabel <string>] [-DomainType <domain_type>] [-NVRAM <hashtable>] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [-Async] [<CommonParameters>]


## New-XenVMAppliance

### Synopsis
None

### Description
None

### Syntax
```
New-XenVMAppliance [-HashTable] <hashtable> [[-PassThru]] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]] [[-Async]] [-Record] <VM_appliance> [[-PassThru]] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]] [[-Async]] [[-PassThru]] [[-NameLabel] <string>] [[-NameDescription] <string>] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]] [[-Async]]
```
### Parameters
| Name | Type | Required | Default Value | Description |
| :--- | :--- | :------- | :------------ | :---------- |
| Async | switch | False |  |  |
| BestEffort | switch | False |  |  |
| Confirm | switch | False |  |  |
| HashTable | hashtable | True |  |  |
| NameDescription | string | False |  |  |
| NameLabel | string | False |  |  |
| PassThru | switch | False |  |  |
| Record | VM_appliance | True |  |  |
| SessionOpaqueRef | string | False |  |  |
| WhatIf | switch | False |  |  |
### Procedure
None

### Inputs
```
None

```
### Outputs
```
XenAPI.VM_appliance
XenAPI.Task
System.Void

```
### Links
None

### Examples

New-XenVMAppliance -HashTable <hashtable> [-PassThru] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [-Async] [<CommonParameters>]

New-XenVMAppliance -Record <VM_appliance> [-PassThru] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [-Async] [<CommonParameters>]

New-XenVMAppliance [-PassThru] [-NameLabel <string>] [-NameDescription <string>] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [-Async] [<CommonParameters>]


## New-XenVMPP

### Synopsis
None

### Description
None

### Syntax
```
New-XenVMPP [-HashTable] <hashtable> [[-PassThru]] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]] [[-Async]] [-Record] <VMPP> [[-PassThru]] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]] [[-Async]] [[-PassThru]] [[-NameLabel] <string>] [[-NameDescription] <string>] [[-IsPolicyEnabled] <bool>] [[-BackupType] <vmpp_backup_type>] [[-BackupRetentionValue] <long>] [[-BackupFrequency] <vmpp_backup_frequency>] [[-BackupSchedule] <hashtable>] [[-ArchiveTargetType] <vmpp_archive_target_type>] [[-ArchiveTargetConfig] <hashtable>] [[-ArchiveFrequency] <vmpp_archive_frequency>] [[-ArchiveSchedule] <hashtable>] [[-IsAlarmEnabled] <bool>] [[-AlarmConfig] <hashtable>] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]] [[-Async]]
```
### Parameters
| Name | Type | Required | Default Value | Description |
| :--- | :--- | :------- | :------------ | :---------- |
| AlarmConfig | hashtable | False |  |  |
| ArchiveFrequency | vmpp_archive_frequency | False |  |  |
| ArchiveSchedule | hashtable | False |  |  |
| ArchiveTargetConfig | hashtable | False |  |  |
| ArchiveTargetType | vmpp_archive_target_type | False |  |  |
| Async | switch | False |  |  |
| BackupFrequency | vmpp_backup_frequency | False |  |  |
| BackupRetentionValue | long | False |  |  |
| BackupSchedule | hashtable | False |  |  |
| BackupType | vmpp_backup_type | False |  |  |
| BestEffort | switch | False |  |  |
| Confirm | switch | False |  |  |
| HashTable | hashtable | True |  |  |
| IsAlarmEnabled | bool | False |  |  |
| IsPolicyEnabled | bool | False |  |  |
| NameDescription | string | False |  |  |
| NameLabel | string | False |  |  |
| PassThru | switch | False |  |  |
| Record | VMPP | True |  |  |
| SessionOpaqueRef | string | False |  |  |
| WhatIf | switch | False |  |  |
### Procedure
None

### Inputs
```
None

```
### Outputs
```
XenAPI.VMPP
XenAPI.Task
System.Void

```
### Links
None

### Examples

New-XenVMPP -HashTable <hashtable> [-PassThru] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [-Async] [<CommonParameters>]

New-XenVMPP -Record <VMPP> [-PassThru] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [-Async] [<CommonParameters>]

New-XenVMPP [-PassThru] [-NameLabel <string>] [-NameDescription <string>] [-IsPolicyEnabled <bool>] [-BackupType <vmpp_backup_type>] [-BackupRetentionValue <long>] [-BackupFrequency <vmpp_backup_frequency>] [-BackupSchedule <hashtable>] [-ArchiveTargetType <vmpp_archive_target_type>] [-ArchiveTargetConfig <hashtable>] [-ArchiveFrequency <vmpp_archive_frequency>] [-ArchiveSchedule <hashtable>] [-IsAlarmEnabled <bool>] [-AlarmConfig <hashtable>] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [-Async] [<CommonParameters>]


## New-XenVMSS

### Synopsis
None

### Description
None

### Syntax
```
New-XenVMSS [-HashTable] <hashtable> [[-PassThru]] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]] [[-Async]] [-Record] <VMSS> [[-PassThru]] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]] [[-Async]] [[-PassThru]] [[-NameLabel] <string>] [[-NameDescription] <string>] [[-Enabled] <bool>] [[-Type] <vmss_type>] [[-RetainedSnapshots] <long>] [[-Frequency] <vmss_frequency>] [[-Schedule] <hashtable>] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]] [[-Async]]
```
### Parameters
| Name | Type | Required | Default Value | Description |
| :--- | :--- | :------- | :------------ | :---------- |
| Async | switch | False |  |  |
| BestEffort | switch | False |  |  |
| Confirm | switch | False |  |  |
| Enabled | bool | False |  |  |
| Frequency | vmss_frequency | False |  |  |
| HashTable | hashtable | True |  |  |
| NameDescription | string | False |  |  |
| NameLabel | string | False |  |  |
| PassThru | switch | False |  |  |
| Record | VMSS | True |  |  |
| RetainedSnapshots | long | False |  |  |
| Schedule | hashtable | False |  |  |
| SessionOpaqueRef | string | False |  |  |
| Type | vmss_type | False |  |  |
| WhatIf | switch | False |  |  |
### Procedure
None

### Inputs
```
None

```
### Outputs
```
XenAPI.VMSS
XenAPI.Task
System.Void

```
### Links
None

### Examples

New-XenVMSS -HashTable <hashtable> [-PassThru] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [-Async] [<CommonParameters>]

New-XenVMSS -Record <VMSS> [-PassThru] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [-Async] [<CommonParameters>]

New-XenVMSS [-PassThru] [-NameLabel <string>] [-NameDescription <string>] [-Enabled <bool>] [-Type <vmss_type>] [-RetainedSnapshots <long>] [-Frequency <vmss_frequency>] [-Schedule <hashtable>] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [-Async] [<CommonParameters>]


## New-XenVTPM

### Synopsis
None

### Description
None

### Syntax
```
New-XenVTPM [-HashTable] <hashtable> [[-PassThru]] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]] [[-Async]] [-Record] <VTPM> [[-PassThru]] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]] [[-Async]] [[-PassThru]] [[-VM] <XenRef[VM]>] [[-Backend] <XenRef[VM]>] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]] [[-Async]]
```
### Parameters
| Name | Type | Required | Default Value | Description |
| :--- | :--- | :------- | :------------ | :---------- |
| Async | switch | False |  |  |
| Backend | XenRef[VM] | False |  |  |
| BestEffort | switch | False |  |  |
| Confirm | switch | False |  |  |
| HashTable | hashtable | True |  |  |
| PassThru | switch | False |  |  |
| Record | VTPM | True |  |  |
| SessionOpaqueRef | string | False |  |  |
| VM | XenRef[VM] | False |  |  |
| WhatIf | switch | False |  |  |
### Procedure
None

### Inputs
```
None

```
### Outputs
```
XenAPI.VTPM
XenAPI.Task
System.Void

```
### Links
None

### Examples

New-XenVTPM -HashTable <hashtable> [-PassThru] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [-Async] [<CommonParameters>]

New-XenVTPM -Record <VTPM> [-PassThru] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [-Async] [<CommonParameters>]

New-XenVTPM [-PassThru] [-VM <XenRef[VM]>] [-Backend <XenRef[VM]>] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [-Async] [<CommonParameters>]


## New-XenVUSB

### Synopsis
None

### Description
None

### Syntax
```
New-XenVUSB [-HashTable] <hashtable> [[-PassThru]] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]] [[-Async]] [-Record] <VUSB> [[-PassThru]] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]] [[-Async]] [[-PassThru]] [[-VM] <XenRef[VM]>] [[-USBGroup] <XenRef[USB_group]>] [[-OtherConfig] <hashtable>] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]] [[-Async]]
```
### Parameters
| Name | Type | Required | Default Value | Description |
| :--- | :--- | :------- | :------------ | :---------- |
| Async | switch | False |  |  |
| BestEffort | switch | False |  |  |
| Confirm | switch | False |  |  |
| HashTable | hashtable | True |  |  |
| OtherConfig | hashtable | False |  |  |
| PassThru | switch | False |  |  |
| Record | VUSB | True |  |  |
| SessionOpaqueRef | string | False |  |  |
| USBGroup | XenRef[USB_group] | False |  |  |
| VM | XenRef[VM] | False |  |  |
| WhatIf | switch | False |  |  |
### Procedure
None

### Inputs
```
None

```
### Outputs
```
XenAPI.VUSB
XenAPI.Task
System.Void

```
### Links
None

### Examples

New-XenVUSB -HashTable <hashtable> [-PassThru] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [-Async] [<CommonParameters>]

New-XenVUSB -Record <VUSB> [-PassThru] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [-Async] [<CommonParameters>]

New-XenVUSB [-PassThru] [-VM <XenRef[VM]>] [-USBGroup <XenRef[USB_group]>] [-OtherConfig <hashtable>] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [-Async] [<CommonParameters>]


## Receive-XenAuditLog

### Synopsis
None

### Description
None

### Syntax
```
Receive-XenAuditLog [-XenHost] <string> [-Path] <string> [[-DataCopiedDelegate] <HTTP+DataCopiedDelegate>] [[-CancellingDelegate] <HTTP+FuncBool>] [[-TimeoutMs] <int>] [[-Proxy] <IWebProxy>] [[-TaskRef] <string>] [[-BestEffort]] [[-SessionOpaqueRef] <string>]
```
### Parameters
| Name | Type | Required | Default Value | Description |
| :--- | :--- | :------- | :------------ | :---------- |
| BestEffort | switch | False |  |  |
| CancellingDelegate | HTTP+FuncBool | False |  |  |
| DataCopiedDelegate | HTTP+DataCopiedDelegate | False |  |  |
| Path | string | True |  |  |
| Proxy | IWebProxy | False |  |  |
| SessionOpaqueRef | string | False |  |  |
| TaskRef | string | False |  |  |
| TimeoutMs | int | False |  |  |
| XenHost | string | True |  |  |
### Procedure
None

### Inputs
```
None

```
### Outputs
```
System.Void

```
### Links
None

### Examples

Receive-XenAuditLog -XenHost <string> -Path <string> [-DataCopiedDelegate <HTTP+DataCopiedDelegate>] [-CancellingDelegate <HTTP+FuncBool>] [-TimeoutMs <int>] [-Proxy <IWebProxy>] [-TaskRef <string>] [-BestEffort] [-SessionOpaqueRef <string>] [<CommonParameters>]


## Receive-XenHostBackup

### Synopsis
None

### Description
None

### Syntax
```
Receive-XenHostBackup [-XenHost] <string> [-Path] <string> [[-DataCopiedDelegate] <HTTP+DataCopiedDelegate>] [[-CancellingDelegate] <HTTP+FuncBool>] [[-TimeoutMs] <int>] [[-Proxy] <IWebProxy>] [[-TaskRef] <string>] [[-BestEffort]] [[-SessionOpaqueRef] <string>]
```
### Parameters
| Name | Type | Required | Default Value | Description |
| :--- | :--- | :------- | :------------ | :---------- |
| BestEffort | switch | False |  |  |
| CancellingDelegate | HTTP+FuncBool | False |  |  |
| DataCopiedDelegate | HTTP+DataCopiedDelegate | False |  |  |
| Path | string | True |  |  |
| Proxy | IWebProxy | False |  |  |
| SessionOpaqueRef | string | False |  |  |
| TaskRef | string | False |  |  |
| TimeoutMs | int | False |  |  |
| XenHost | string | True |  |  |
### Procedure
None

### Inputs
```
None

```
### Outputs
```
System.Void

```
### Links
None

### Examples

Receive-XenHostBackup -XenHost <string> -Path <string> [-DataCopiedDelegate <HTTP+DataCopiedDelegate>] [-CancellingDelegate <HTTP+FuncBool>] [-TimeoutMs <int>] [-Proxy <IWebProxy>] [-TaskRef <string>] [-BestEffort] [-SessionOpaqueRef <string>] [<CommonParameters>]


## Receive-XenHostLogs

### Synopsis
None

### Description
None

### Syntax
```
Receive-XenHostLogs [-XenHost] <string> [-Path] <string> [[-DataCopiedDelegate] <HTTP+DataCopiedDelegate>] [[-CancellingDelegate] <HTTP+FuncBool>] [[-TimeoutMs] <int>] [[-Proxy] <IWebProxy>] [[-TaskRef] <string>] [[-BestEffort]] [[-SessionOpaqueRef] <string>]
```
### Parameters
| Name | Type | Required | Default Value | Description |
| :--- | :--- | :------- | :------------ | :---------- |
| BestEffort | switch | False |  |  |
| CancellingDelegate | HTTP+FuncBool | False |  |  |
| DataCopiedDelegate | HTTP+DataCopiedDelegate | False |  |  |
| Path | string | True |  |  |
| Proxy | IWebProxy | False |  |  |
| SessionOpaqueRef | string | False |  |  |
| TaskRef | string | False |  |  |
| TimeoutMs | int | False |  |  |
| XenHost | string | True |  |  |
### Procedure
None

### Inputs
```
None

```
### Outputs
```
System.Void

```
### Links
None

### Examples

Receive-XenHostLogs -XenHost <string> -Path <string> [-DataCopiedDelegate <HTTP+DataCopiedDelegate>] [-CancellingDelegate <HTTP+FuncBool>] [-TimeoutMs <int>] [-Proxy <IWebProxy>] [-TaskRef <string>] [-BestEffort] [-SessionOpaqueRef <string>] [<CommonParameters>]


## Receive-XenHostRrd

### Synopsis
None

### Description
None

### Syntax
```
Receive-XenHostRrd [-XenHost] <string> [-Path] <string> [[-DataCopiedDelegate] <HTTP+DataCopiedDelegate>] [[-Json] <bool>] [[-CancellingDelegate] <HTTP+FuncBool>] [[-TimeoutMs] <int>] [[-Proxy] <IWebProxy>] [[-TaskRef] <string>] [[-BestEffort]] [[-SessionOpaqueRef] <string>]
```
### Parameters
| Name | Type | Required | Default Value | Description |
| :--- | :--- | :------- | :------------ | :---------- |
| BestEffort | switch | False |  |  |
| CancellingDelegate | HTTP+FuncBool | False |  |  |
| DataCopiedDelegate | HTTP+DataCopiedDelegate | False |  |  |
| Json | bool | False |  |  |
| Path | string | True |  |  |
| Proxy | IWebProxy | False |  |  |
| SessionOpaqueRef | string | False |  |  |
| TaskRef | string | False |  |  |
| TimeoutMs | int | False |  |  |
| XenHost | string | True |  |  |
### Procedure
None

### Inputs
```
None

```
### Outputs
```
System.Void

```
### Links
None

### Examples

Receive-XenHostRrd -XenHost <string> -Path <string> [-DataCopiedDelegate <HTTP+DataCopiedDelegate>] [-Json <bool>] [-CancellingDelegate <HTTP+FuncBool>] [-TimeoutMs <int>] [-Proxy <IWebProxy>] [-TaskRef <string>] [-BestEffort] [-SessionOpaqueRef <string>] [<CommonParameters>]


## Receive-XenPoolPatch

### Synopsis
None

### Description
None

### Syntax
```
Receive-XenPoolPatch [-XenHost] <string> [-Path] <string> [[-DataCopiedDelegate] <HTTP+DataCopiedDelegate>] [[-Uuid] <string>] [[-CancellingDelegate] <HTTP+FuncBool>] [[-TimeoutMs] <int>] [[-Proxy] <IWebProxy>] [[-TaskRef] <string>] [[-BestEffort]] [[-SessionOpaqueRef] <string>]
```
### Parameters
| Name | Type | Required | Default Value | Description |
| :--- | :--- | :------- | :------------ | :---------- |
| BestEffort | switch | False |  |  |
| CancellingDelegate | HTTP+FuncBool | False |  |  |
| DataCopiedDelegate | HTTP+DataCopiedDelegate | False |  |  |
| Path | string | True |  |  |
| Proxy | IWebProxy | False |  |  |
| SessionOpaqueRef | string | False |  |  |
| TaskRef | string | False |  |  |
| TimeoutMs | int | False |  |  |
| Uuid | string | False |  |  |
| XenHost | string | True |  |  |
### Procedure
None

### Inputs
```
System.String

```
### Outputs
```
System.Void

```
### Links
None

### Examples

Receive-XenPoolPatch -XenHost <string> -Path <string> [-DataCopiedDelegate <HTTP+DataCopiedDelegate>] [-Uuid <string>] [-CancellingDelegate <HTTP+FuncBool>] [-TimeoutMs <int>] [-Proxy <IWebProxy>] [-TaskRef <string>] [-BestEffort] [-SessionOpaqueRef <string>] [<CommonParameters>]


## Receive-XenPoolXmlDbSync

### Synopsis
None

### Description
None

### Syntax
```
Receive-XenPoolXmlDbSync [-XenHost] <string> [-Path] <string> [[-DataCopiedDelegate] <HTTP+DataCopiedDelegate>] [[-CancellingDelegate] <HTTP+FuncBool>] [[-TimeoutMs] <int>] [[-Proxy] <IWebProxy>] [[-TaskRef] <string>] [[-BestEffort]] [[-SessionOpaqueRef] <string>]
```
### Parameters
| Name | Type | Required | Default Value | Description |
| :--- | :--- | :------- | :------------ | :---------- |
| BestEffort | switch | False |  |  |
| CancellingDelegate | HTTP+FuncBool | False |  |  |
| DataCopiedDelegate | HTTP+DataCopiedDelegate | False |  |  |
| Path | string | True |  |  |
| Proxy | IWebProxy | False |  |  |
| SessionOpaqueRef | string | False |  |  |
| TaskRef | string | False |  |  |
| TimeoutMs | int | False |  |  |
| XenHost | string | True |  |  |
### Procedure
None

### Inputs
```
None

```
### Outputs
```
System.Void

```
### Links
None

### Examples

Receive-XenPoolXmlDbSync -XenHost <string> -Path <string> [-DataCopiedDelegate <HTTP+DataCopiedDelegate>] [-CancellingDelegate <HTTP+FuncBool>] [-TimeoutMs <int>] [-Proxy <IWebProxy>] [-TaskRef <string>] [-BestEffort] [-SessionOpaqueRef <string>] [<CommonParameters>]


## Receive-XenRrdUpdates

### Synopsis
None

### Description
None

### Syntax
```
Receive-XenRrdUpdates [-XenHost] <string> [-Path] <string> [[-DataCopiedDelegate] <HTTP+DataCopiedDelegate>] [[-Start] <long>] [[-Cf] <string>] [[-Interval] <long>] [[-IsHost] <bool>] [[-Uuid] <string>] [[-Json] <bool>] [[-CancellingDelegate] <HTTP+FuncBool>] [[-TimeoutMs] <int>] [[-Proxy] <IWebProxy>] [[-TaskRef] <string>] [[-BestEffort]] [[-SessionOpaqueRef] <string>]
```
### Parameters
| Name | Type | Required | Default Value | Description |
| :--- | :--- | :------- | :------------ | :---------- |
| BestEffort | switch | False |  |  |
| CancellingDelegate | HTTP+FuncBool | False |  |  |
| Cf | string | False |  |  |
| DataCopiedDelegate | HTTP+DataCopiedDelegate | False |  |  |
| Interval | long | False |  |  |
| IsHost | bool | False |  |  |
| Json | bool | False |  |  |
| Path | string | True |  |  |
| Proxy | IWebProxy | False |  |  |
| SessionOpaqueRef | string | False |  |  |
| Start | long | False |  |  |
| TaskRef | string | False |  |  |
| TimeoutMs | int | False |  |  |
| Uuid | string | False |  |  |
| XenHost | string | True |  |  |
### Procedure
None

### Inputs
```
System.String

```
### Outputs
```
System.Void

```
### Links
None

### Examples

Receive-XenRrdUpdates -XenHost <string> -Path <string> [-DataCopiedDelegate <HTTP+DataCopiedDelegate>] [-Start <long>] [-Cf <string>] [-Interval <long>] [-IsHost <bool>] [-Uuid <string>] [-Json <bool>] [-CancellingDelegate <HTTP+FuncBool>] [-TimeoutMs <int>] [-Proxy <IWebProxy>] [-TaskRef <string>] [-BestEffort] [-SessionOpaqueRef <string>] [<CommonParameters>]


## Receive-XenServices

### Synopsis
None

### Description
None

### Syntax
```
Receive-XenServices [-XenHost] <string> [-Path] <string> [[-DataCopiedDelegate] <HTTP+DataCopiedDelegate>] [[-CancellingDelegate] <HTTP+FuncBool>] [[-TimeoutMs] <int>] [[-Proxy] <IWebProxy>] [[-TaskRef] <string>] [[-BestEffort]] [[-SessionOpaqueRef] <string>]
```
### Parameters
| Name | Type | Required | Default Value | Description |
| :--- | :--- | :------- | :------------ | :---------- |
| BestEffort | switch | False |  |  |
| CancellingDelegate | HTTP+FuncBool | False |  |  |
| DataCopiedDelegate | HTTP+DataCopiedDelegate | False |  |  |
| Path | string | True |  |  |
| Proxy | IWebProxy | False |  |  |
| SessionOpaqueRef | string | False |  |  |
| TaskRef | string | False |  |  |
| TimeoutMs | int | False |  |  |
| XenHost | string | True |  |  |
### Procedure
None

### Inputs
```
None

```
### Outputs
```
System.Void

```
### Links
None

### Examples

Receive-XenServices -XenHost <string> -Path <string> [-DataCopiedDelegate <HTTP+DataCopiedDelegate>] [-CancellingDelegate <HTTP+FuncBool>] [-TimeoutMs <int>] [-Proxy <IWebProxy>] [-TaskRef <string>] [-BestEffort] [-SessionOpaqueRef <string>] [<CommonParameters>]


## Receive-XenSrRrd

### Synopsis
None

### Description
None

### Syntax
```
Receive-XenSrRrd [-XenHost] <string> [-Path] <string> [[-DataCopiedDelegate] <HTTP+DataCopiedDelegate>] [[-Uuid] <string>] [[-CancellingDelegate] <HTTP+FuncBool>] [[-TimeoutMs] <int>] [[-Proxy] <IWebProxy>] [[-TaskRef] <string>] [[-BestEffort]] [[-SessionOpaqueRef] <string>]
```
### Parameters
| Name | Type | Required | Default Value | Description |
| :--- | :--- | :------- | :------------ | :---------- |
| BestEffort | switch | False |  |  |
| CancellingDelegate | HTTP+FuncBool | False |  |  |
| DataCopiedDelegate | HTTP+DataCopiedDelegate | False |  |  |
| Path | string | True |  |  |
| Proxy | IWebProxy | False |  |  |
| SessionOpaqueRef | string | False |  |  |
| TaskRef | string | False |  |  |
| TimeoutMs | int | False |  |  |
| Uuid | string | False |  |  |
| XenHost | string | True |  |  |
### Procedure
None

### Inputs
```
System.String

```
### Outputs
```
System.Void

```
### Links
None

### Examples

Receive-XenSrRrd -XenHost <string> -Path <string> [-DataCopiedDelegate <HTTP+DataCopiedDelegate>] [-Uuid <string>] [-CancellingDelegate <HTTP+FuncBool>] [-TimeoutMs <int>] [-Proxy <IWebProxy>] [-TaskRef <string>] [-BestEffort] [-SessionOpaqueRef <string>] [<CommonParameters>]


## Receive-XenSystemStatus

### Synopsis
None

### Description
None

### Syntax
```
Receive-XenSystemStatus [-XenHost] <string> [-Path] <string> [[-DataCopiedDelegate] <HTTP+DataCopiedDelegate>] [[-Entries] <string>] [[-Output] <string>] [[-CancellingDelegate] <HTTP+FuncBool>] [[-TimeoutMs] <int>] [[-Proxy] <IWebProxy>] [[-TaskRef] <string>] [[-BestEffort]] [[-SessionOpaqueRef] <string>]
```
### Parameters
| Name | Type | Required | Default Value | Description |
| :--- | :--- | :------- | :------------ | :---------- |
| BestEffort | switch | False |  |  |
| CancellingDelegate | HTTP+FuncBool | False |  |  |
| DataCopiedDelegate | HTTP+DataCopiedDelegate | False |  |  |
| Entries | string | False |  |  |
| Output | string | False |  |  |
| Path | string | True |  |  |
| Proxy | IWebProxy | False |  |  |
| SessionOpaqueRef | string | False |  |  |
| TaskRef | string | False |  |  |
| TimeoutMs | int | False |  |  |
| XenHost | string | True |  |  |
### Procedure
None

### Inputs
```
None

```
### Outputs
```
System.Void

```
### Links
None

### Examples

Receive-XenSystemStatus -XenHost <string> -Path <string> [-DataCopiedDelegate <HTTP+DataCopiedDelegate>] [-Entries <string>] [-Output <string>] [-CancellingDelegate <HTTP+FuncBool>] [-TimeoutMs <int>] [-Proxy <IWebProxy>] [-TaskRef <string>] [-BestEffort] [-SessionOpaqueRef <string>] [<CommonParameters>]


## Receive-XenVmRrd

### Synopsis
None

### Description
None

### Syntax
```
Receive-XenVmRrd [-XenHost] <string> [-Path] <string> [[-DataCopiedDelegate] <HTTP+DataCopiedDelegate>] [[-Uuid] <string>] [[-CancellingDelegate] <HTTP+FuncBool>] [[-TimeoutMs] <int>] [[-Proxy] <IWebProxy>] [[-TaskRef] <string>] [[-BestEffort]] [[-SessionOpaqueRef] <string>]
```
### Parameters
| Name | Type | Required | Default Value | Description |
| :--- | :--- | :------- | :------------ | :---------- |
| BestEffort | switch | False |  |  |
| CancellingDelegate | HTTP+FuncBool | False |  |  |
| DataCopiedDelegate | HTTP+DataCopiedDelegate | False |  |  |
| Path | string | True |  |  |
| Proxy | IWebProxy | False |  |  |
| SessionOpaqueRef | string | False |  |  |
| TaskRef | string | False |  |  |
| TimeoutMs | int | False |  |  |
| Uuid | string | False |  |  |
| XenHost | string | True |  |  |
### Procedure
None

### Inputs
```
System.String

```
### Outputs
```
System.Void

```
### Links
None

### Examples

Receive-XenVmRrd -XenHost <string> -Path <string> [-DataCopiedDelegate <HTTP+DataCopiedDelegate>] [-Uuid <string>] [-CancellingDelegate <HTTP+FuncBool>] [-TimeoutMs <int>] [-Proxy <IWebProxy>] [-TaskRef <string>] [-BestEffort] [-SessionOpaqueRef <string>] [<CommonParameters>]


## Receive-XenVncsnapshot

### Synopsis
None

### Description
None

### Syntax
```
Receive-XenVncsnapshot [-XenHost] <string> [-Path] <string> [[-DataCopiedDelegate] <HTTP+DataCopiedDelegate>] [[-Uuid] <string>] [[-CancellingDelegate] <HTTP+FuncBool>] [[-TimeoutMs] <int>] [[-Proxy] <IWebProxy>] [[-TaskRef] <string>] [[-BestEffort]] [[-SessionOpaqueRef] <string>]
```
### Parameters
| Name | Type | Required | Default Value | Description |
| :--- | :--- | :------- | :------------ | :---------- |
| BestEffort | switch | False |  |  |
| CancellingDelegate | HTTP+FuncBool | False |  |  |
| DataCopiedDelegate | HTTP+DataCopiedDelegate | False |  |  |
| Path | string | True |  |  |
| Proxy | IWebProxy | False |  |  |
| SessionOpaqueRef | string | False |  |  |
| TaskRef | string | False |  |  |
| TimeoutMs | int | False |  |  |
| Uuid | string | False |  |  |
| XenHost | string | True |  |  |
### Procedure
None

### Inputs
```
System.String

```
### Outputs
```
System.Void

```
### Links
None

### Examples

Receive-XenVncsnapshot -XenHost <string> -Path <string> [-DataCopiedDelegate <HTTP+DataCopiedDelegate>] [-Uuid <string>] [-CancellingDelegate <HTTP+FuncBool>] [-TimeoutMs <int>] [-Proxy <IWebProxy>] [-TaskRef <string>] [-BestEffort] [-SessionOpaqueRef <string>] [<CommonParameters>]


## Receive-XenWlbDiagnostics

### Synopsis
None

### Description
None

### Syntax
```
Receive-XenWlbDiagnostics [-XenHost] <string> [-Path] <string> [[-DataCopiedDelegate] <HTTP+DataCopiedDelegate>] [[-CancellingDelegate] <HTTP+FuncBool>] [[-TimeoutMs] <int>] [[-Proxy] <IWebProxy>] [[-TaskRef] <string>] [[-BestEffort]] [[-SessionOpaqueRef] <string>]
```
### Parameters
| Name | Type | Required | Default Value | Description |
| :--- | :--- | :------- | :------------ | :---------- |
| BestEffort | switch | False |  |  |
| CancellingDelegate | HTTP+FuncBool | False |  |  |
| DataCopiedDelegate | HTTP+DataCopiedDelegate | False |  |  |
| Path | string | True |  |  |
| Proxy | IWebProxy | False |  |  |
| SessionOpaqueRef | string | False |  |  |
| TaskRef | string | False |  |  |
| TimeoutMs | int | False |  |  |
| XenHost | string | True |  |  |
### Procedure
None

### Inputs
```
None

```
### Outputs
```
System.Void

```
### Links
None

### Examples

Receive-XenWlbDiagnostics -XenHost <string> -Path <string> [-DataCopiedDelegate <HTTP+DataCopiedDelegate>] [-CancellingDelegate <HTTP+FuncBool>] [-TimeoutMs <int>] [-Proxy <IWebProxy>] [-TaskRef <string>] [-BestEffort] [-SessionOpaqueRef <string>] [<CommonParameters>]


## Receive-XenWlbReport

### Synopsis
None

### Description
None

### Syntax
```
Receive-XenWlbReport [-XenHost] <string> [-Path] <string> [[-DataCopiedDelegate] <HTTP+DataCopiedDelegate>] [[-Report] <string>] [[-Args] <string[]>] [[-CancellingDelegate] <HTTP+FuncBool>] [[-TimeoutMs] <int>] [[-Proxy] <IWebProxy>] [[-TaskRef] <string>] [[-BestEffort]] [[-SessionOpaqueRef] <string>]
```
### Parameters
| Name | Type | Required | Default Value | Description |
| :--- | :--- | :------- | :------------ | :---------- |
| Args | string[] | False |  |  |
| BestEffort | switch | False |  |  |
| CancellingDelegate | HTTP+FuncBool | False |  |  |
| DataCopiedDelegate | HTTP+DataCopiedDelegate | False |  |  |
| Path | string | True |  |  |
| Proxy | IWebProxy | False |  |  |
| Report | string | False |  |  |
| SessionOpaqueRef | string | False |  |  |
| TaskRef | string | False |  |  |
| TimeoutMs | int | False |  |  |
| XenHost | string | True |  |  |
### Procedure
None

### Inputs
```
None

```
### Outputs
```
System.Void

```
### Links
None

### Examples

Receive-XenWlbReport -XenHost <string> -Path <string> [-DataCopiedDelegate <HTTP+DataCopiedDelegate>] [-Report <string>] [-Args <string[]>] [-CancellingDelegate <HTTP+FuncBool>] [-TimeoutMs <int>] [-Proxy <IWebProxy>] [-TaskRef <string>] [-BestEffort] [-SessionOpaqueRef <string>] [<CommonParameters>]


## Remove-XenBond

### Synopsis
None

### Description
None

### Syntax
```
Remove-XenBond [-Bond] <Bond> [[-PassThru]] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]] [[-Async]] [-Ref] <XenRef[Bond]> [[-PassThru]] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]] [[-Async]] [-Uuid] <guid> [[-PassThru]] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]] [[-Async]]
```
### Parameters
| Name | Type | Required | Default Value | Description |
| :--- | :--- | :------- | :------------ | :---------- |
| Async | switch | False |  |  |
| BestEffort | switch | False |  |  |
| Bond | Bond | True |  |  |
| Confirm | switch | False |  |  |
| PassThru | switch | False |  |  |
| Ref | XenRef[Bond] | True |  |  |
| SessionOpaqueRef | string | False |  |  |
| Uuid | guid | True |  |  |
| WhatIf | switch | False |  |  |
### Procedure
None

### Inputs
```
XenAPI.Bond
XenAPI.XenRef`1[[XenAPI.Bond, XenServer, Version=8.2.3.0, Culture=neutral, PublicKeyToken=d247b8b0ac7959e9]]
System.Guid

```
### Outputs
```
XenAPI.Bond
XenAPI.Task
System.Void

```
### Links
None

### Examples

Remove-XenBond [-Bond] <Bond> [-PassThru] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [-Async] [<CommonParameters>]

Remove-XenBond [-Ref] <XenRef[Bond]> [-PassThru] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [-Async] [<CommonParameters>]

Remove-XenBond [-Uuid] <guid> [-PassThru] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [-Async] [<CommonParameters>]


## Remove-XenBondProperty

### Synopsis
None

### Description
None

### Syntax
```
Remove-XenBondProperty [-Bond] <Bond> [[-PassThru]] [[-OtherConfig] <string>] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]] [-Ref] <XenRef[Bond]> [[-PassThru]] [[-OtherConfig] <string>] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]] [-Uuid] <guid> [[-PassThru]] [[-OtherConfig] <string>] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]]
```
### Parameters
| Name | Type | Required | Default Value | Description |
| :--- | :--- | :------- | :------------ | :---------- |
| BestEffort | switch | False |  |  |
| Bond | Bond | True |  |  |
| Confirm | switch | False |  |  |
| OtherConfig | string | False |  |  |
| PassThru | switch | False |  |  |
| Ref | XenRef[Bond] | True |  |  |
| SessionOpaqueRef | string | False |  |  |
| Uuid | guid | True |  |  |
| WhatIf | switch | False |  |  |
### Procedure
None

### Inputs
```
XenAPI.Bond
XenAPI.XenRef`1[[XenAPI.Bond, XenServer, Version=8.2.3.0, Culture=neutral, PublicKeyToken=d247b8b0ac7959e9]]
System.Guid

```
### Outputs
```
XenAPI.Bond

```
### Links
None

### Examples

Remove-XenBondProperty [-Bond] <Bond> [-PassThru] [-OtherConfig <string>] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [<CommonParameters>]

Remove-XenBondProperty [-Ref] <XenRef[Bond]> [-PassThru] [-OtherConfig <string>] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [<CommonParameters>]

Remove-XenBondProperty [-Uuid] <guid> [-PassThru] [-OtherConfig <string>] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [<CommonParameters>]


## Remove-XenCluster

### Synopsis
None

### Description
None

### Syntax
```
Remove-XenCluster [-Cluster] <Cluster> [[-PassThru]] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]] [[-Async]] [-Ref] <XenRef[Cluster]> [[-PassThru]] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]] [[-Async]] [-Uuid] <guid> [[-PassThru]] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]] [[-Async]]
```
### Parameters
| Name | Type | Required | Default Value | Description |
| :--- | :--- | :------- | :------------ | :---------- |
| Async | switch | False |  |  |
| BestEffort | switch | False |  |  |
| Cluster | Cluster | True |  |  |
| Confirm | switch | False |  |  |
| PassThru | switch | False |  |  |
| Ref | XenRef[Cluster] | True |  |  |
| SessionOpaqueRef | string | False |  |  |
| Uuid | guid | True |  |  |
| WhatIf | switch | False |  |  |
### Procedure
None

### Inputs
```
XenAPI.Cluster
XenAPI.XenRef`1[[XenAPI.Cluster, XenServer, Version=8.2.3.0, Culture=neutral, PublicKeyToken=d247b8b0ac7959e9]]
System.Guid

```
### Outputs
```
XenAPI.Cluster
XenAPI.Task
System.Void

```
### Links
None

### Examples

Remove-XenCluster [-Cluster] <Cluster> [-PassThru] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [-Async] [<CommonParameters>]

Remove-XenCluster [-Ref] <XenRef[Cluster]> [-PassThru] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [-Async] [<CommonParameters>]

Remove-XenCluster [-Uuid] <guid> [-PassThru] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [-Async] [<CommonParameters>]


## Remove-XenClusterHost

### Synopsis
None

### Description
None

### Syntax
```
Remove-XenClusterHost [-ClusterHost] <Cluster_host> [[-PassThru]] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]] [[-Async]] [-Ref] <XenRef[Cluster_host]> [[-PassThru]] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]] [[-Async]] [-Uuid] <guid> [[-PassThru]] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]] [[-Async]]
```
### Parameters
| Name | Type | Required | Default Value | Description |
| :--- | :--- | :------- | :------------ | :---------- |
| Async | switch | False |  |  |
| BestEffort | switch | False |  |  |
| ClusterHost | Cluster_host | True |  |  |
| Confirm | switch | False |  |  |
| PassThru | switch | False |  |  |
| Ref | XenRef[Cluster_host] | True |  |  |
| SessionOpaqueRef | string | False |  |  |
| Uuid | guid | True |  |  |
| WhatIf | switch | False |  |  |
### Procedure
None

### Inputs
```
XenAPI.Cluster_host
XenAPI.XenRef`1[[XenAPI.Cluster_host, XenServer, Version=8.2.3.0, Culture=neutral, PublicKeyToken=d247b8b0ac7959e9]]
System.Guid

```
### Outputs
```
XenAPI.Cluster_host
XenAPI.Task
System.Void

```
### Links
None

### Examples

Remove-XenClusterHost [-ClusterHost] <Cluster_host> [-PassThru] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [-Async] [<CommonParameters>]

Remove-XenClusterHost [-Ref] <XenRef[Cluster_host]> [-PassThru] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [-Async] [<CommonParameters>]

Remove-XenClusterHost [-Uuid] <guid> [-PassThru] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [-Async] [<CommonParameters>]


## Remove-XenClusterProperty

### Synopsis
None

### Description
None

### Syntax
```
Remove-XenClusterProperty [-Cluster] <Cluster> [[-PassThru]] [[-OtherConfig] <string>] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]] [-Ref] <XenRef[Cluster]> [[-PassThru]] [[-OtherConfig] <string>] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]] [-Uuid] <guid> [[-PassThru]] [[-OtherConfig] <string>] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]]
```
### Parameters
| Name | Type | Required | Default Value | Description |
| :--- | :--- | :------- | :------------ | :---------- |
| BestEffort | switch | False |  |  |
| Cluster | Cluster | True |  |  |
| Confirm | switch | False |  |  |
| OtherConfig | string | False |  |  |
| PassThru | switch | False |  |  |
| Ref | XenRef[Cluster] | True |  |  |
| SessionOpaqueRef | string | False |  |  |
| Uuid | guid | True |  |  |
| WhatIf | switch | False |  |  |
### Procedure
None

### Inputs
```
XenAPI.Cluster
XenAPI.XenRef`1[[XenAPI.Cluster, XenServer, Version=8.2.3.0, Culture=neutral, PublicKeyToken=d247b8b0ac7959e9]]
System.Guid

```
### Outputs
```
XenAPI.Cluster

```
### Links
None

### Examples

Remove-XenClusterProperty [-Cluster] <Cluster> [-PassThru] [-OtherConfig <string>] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [<CommonParameters>]

Remove-XenClusterProperty [-Ref] <XenRef[Cluster]> [-PassThru] [-OtherConfig <string>] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [<CommonParameters>]

Remove-XenClusterProperty [-Uuid] <guid> [-PassThru] [-OtherConfig <string>] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [<CommonParameters>]


## Remove-XenConsole

### Synopsis
None

### Description
None

### Syntax
```
Remove-XenConsole [-Console] <Console> [[-PassThru]] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]] [[-Async]] [-Ref] <XenRef[Console]> [[-PassThru]] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]] [[-Async]] [-Uuid] <guid> [[-PassThru]] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]] [[-Async]]
```
### Parameters
| Name | Type | Required | Default Value | Description |
| :--- | :--- | :------- | :------------ | :---------- |
| Async | switch | False |  |  |
| BestEffort | switch | False |  |  |
| Confirm | switch | False |  |  |
| Console | Console | True |  |  |
| PassThru | switch | False |  |  |
| Ref | XenRef[Console] | True |  |  |
| SessionOpaqueRef | string | False |  |  |
| Uuid | guid | True |  |  |
| WhatIf | switch | False |  |  |
### Procedure
None

### Inputs
```
XenAPI.Console
XenAPI.XenRef`1[[XenAPI.Console, XenServer, Version=8.2.3.0, Culture=neutral, PublicKeyToken=d247b8b0ac7959e9]]
System.Guid

```
### Outputs
```
XenAPI.Console
XenAPI.Task
System.Void

```
### Links
None

### Examples

Remove-XenConsole [-Console] <Console> [-PassThru] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [-Async] [<CommonParameters>]

Remove-XenConsole [-Ref] <XenRef[Console]> [-PassThru] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [-Async] [<CommonParameters>]

Remove-XenConsole [-Uuid] <guid> [-PassThru] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [-Async] [<CommonParameters>]


## Remove-XenConsoleProperty

### Synopsis
None

### Description
None

### Syntax
```
Remove-XenConsoleProperty [-Console] <Console> [[-PassThru]] [[-OtherConfig] <string>] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]] [-Ref] <XenRef[Console]> [[-PassThru]] [[-OtherConfig] <string>] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]] [-Uuid] <guid> [[-PassThru]] [[-OtherConfig] <string>] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]]
```
### Parameters
| Name | Type | Required | Default Value | Description |
| :--- | :--- | :------- | :------------ | :---------- |
| BestEffort | switch | False |  |  |
| Confirm | switch | False |  |  |
| Console | Console | True |  |  |
| OtherConfig | string | False |  |  |
| PassThru | switch | False |  |  |
| Ref | XenRef[Console] | True |  |  |
| SessionOpaqueRef | string | False |  |  |
| Uuid | guid | True |  |  |
| WhatIf | switch | False |  |  |
### Procedure
None

### Inputs
```
XenAPI.Console
XenAPI.XenRef`1[[XenAPI.Console, XenServer, Version=8.2.3.0, Culture=neutral, PublicKeyToken=d247b8b0ac7959e9]]
System.Guid

```
### Outputs
```
XenAPI.Console

```
### Links
None

### Examples

Remove-XenConsoleProperty [-Console] <Console> [-PassThru] [-OtherConfig <string>] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [<CommonParameters>]

Remove-XenConsoleProperty [-Ref] <XenRef[Console]> [-PassThru] [-OtherConfig <string>] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [<CommonParameters>]

Remove-XenConsoleProperty [-Uuid] <guid> [-PassThru] [-OtherConfig <string>] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [<CommonParameters>]


## Remove-XenCrashdump

### Synopsis
None

### Description
None

### Syntax
```
Remove-XenCrashdump [-Crashdump] <Crashdump> [[-PassThru]] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]] [[-Async]] [-Ref] <XenRef[Crashdump]> [[-PassThru]] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]] [[-Async]] [-Uuid] <guid> [[-PassThru]] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]] [[-Async]]
```
### Parameters
| Name | Type | Required | Default Value | Description |
| :--- | :--- | :------- | :------------ | :---------- |
| Async | switch | False |  |  |
| BestEffort | switch | False |  |  |
| Confirm | switch | False |  |  |
| Crashdump | Crashdump | True |  |  |
| PassThru | switch | False |  |  |
| Ref | XenRef[Crashdump] | True |  |  |
| SessionOpaqueRef | string | False |  |  |
| Uuid | guid | True |  |  |
| WhatIf | switch | False |  |  |
### Procedure
None

### Inputs
```
XenAPI.Crashdump
XenAPI.XenRef`1[[XenAPI.Crashdump, XenServer, Version=8.2.3.0, Culture=neutral, PublicKeyToken=d247b8b0ac7959e9]]
System.Guid

```
### Outputs
```
XenAPI.Crashdump
XenAPI.Task
System.Void

```
### Links
None

### Examples

Remove-XenCrashdump [-Crashdump] <Crashdump> [-PassThru] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [-Async] [<CommonParameters>]

Remove-XenCrashdump [-Ref] <XenRef[Crashdump]> [-PassThru] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [-Async] [<CommonParameters>]

Remove-XenCrashdump [-Uuid] <guid> [-PassThru] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [-Async] [<CommonParameters>]


## Remove-XenCrashdumpProperty

### Synopsis
None

### Description
None

### Syntax
```
Remove-XenCrashdumpProperty [-Crashdump] <Crashdump> [[-PassThru]] [[-OtherConfig] <string>] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]] [-Ref] <XenRef[Crashdump]> [[-PassThru]] [[-OtherConfig] <string>] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]] [-Uuid] <guid> [[-PassThru]] [[-OtherConfig] <string>] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]]
```
### Parameters
| Name | Type | Required | Default Value | Description |
| :--- | :--- | :------- | :------------ | :---------- |
| BestEffort | switch | False |  |  |
| Confirm | switch | False |  |  |
| Crashdump | Crashdump | True |  |  |
| OtherConfig | string | False |  |  |
| PassThru | switch | False |  |  |
| Ref | XenRef[Crashdump] | True |  |  |
| SessionOpaqueRef | string | False |  |  |
| Uuid | guid | True |  |  |
| WhatIf | switch | False |  |  |
### Procedure
None

### Inputs
```
XenAPI.Crashdump
XenAPI.XenRef`1[[XenAPI.Crashdump, XenServer, Version=8.2.3.0, Culture=neutral, PublicKeyToken=d247b8b0ac7959e9]]
System.Guid

```
### Outputs
```
XenAPI.Crashdump

```
### Links
None

### Examples

Remove-XenCrashdumpProperty [-Crashdump] <Crashdump> [-PassThru] [-OtherConfig <string>] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [<CommonParameters>]

Remove-XenCrashdumpProperty [-Ref] <XenRef[Crashdump]> [-PassThru] [-OtherConfig <string>] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [<CommonParameters>]

Remove-XenCrashdumpProperty [-Uuid] <guid> [-PassThru] [-OtherConfig <string>] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [<CommonParameters>]


## Remove-XenDRTask

### Synopsis
None

### Description
None

### Syntax
```
Remove-XenDRTask [-DRTask] <DR_task> [[-PassThru]] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]] [[-Async]] [-Ref] <XenRef[DR_task]> [[-PassThru]] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]] [[-Async]] [-Uuid] <guid> [[-PassThru]] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]] [[-Async]]
```
### Parameters
| Name | Type | Required | Default Value | Description |
| :--- | :--- | :------- | :------------ | :---------- |
| Async | switch | False |  |  |
| BestEffort | switch | False |  |  |
| Confirm | switch | False |  |  |
| DRTask | DR_task | True |  |  |
| PassThru | switch | False |  |  |
| Ref | XenRef[DR_task] | True |  |  |
| SessionOpaqueRef | string | False |  |  |
| Uuid | guid | True |  |  |
| WhatIf | switch | False |  |  |
### Procedure
None

### Inputs
```
XenAPI.DR_task
XenAPI.XenRef`1[[XenAPI.DR_task, XenServer, Version=8.2.3.0, Culture=neutral, PublicKeyToken=d247b8b0ac7959e9]]
System.Guid

```
### Outputs
```
XenAPI.DR_task
XenAPI.Task
System.Void

```
### Links
None

### Examples

Remove-XenDRTask [-DRTask] <DR_task> [-PassThru] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [-Async] [<CommonParameters>]

Remove-XenDRTask [-Ref] <XenRef[DR_task]> [-PassThru] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [-Async] [<CommonParameters>]

Remove-XenDRTask [-Uuid] <guid> [-PassThru] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [-Async] [<CommonParameters>]


## Remove-XenGPUGroup

### Synopsis
None

### Description
None

### Syntax
```
Remove-XenGPUGroup [-GPUGroup] <GPU_group> [[-PassThru]] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]] [[-Async]] [-Ref] <XenRef[GPU_group]> [[-PassThru]] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]] [[-Async]] [-Uuid] <guid> [[-PassThru]] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]] [[-Async]] [-Name] <string> [[-PassThru]] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]] [[-Async]]
```
### Parameters
| Name | Type | Required | Default Value | Description |
| :--- | :--- | :------- | :------------ | :---------- |
| Async | switch | False |  |  |
| BestEffort | switch | False |  |  |
| Confirm | switch | False |  |  |
| GPUGroup | GPU_group | True |  |  |
| Name | string | True |  |  |
| PassThru | switch | False |  |  |
| Ref | XenRef[GPU_group] | True |  |  |
| SessionOpaqueRef | string | False |  |  |
| Uuid | guid | True |  |  |
| WhatIf | switch | False |  |  |
### Procedure
None

### Inputs
```
XenAPI.GPU_group
XenAPI.XenRef`1[[XenAPI.GPU_group, XenServer, Version=8.2.3.0, Culture=neutral, PublicKeyToken=d247b8b0ac7959e9]]
System.Guid
System.String

```
### Outputs
```
XenAPI.GPU_group
XenAPI.Task
System.Void

```
### Links
None

### Examples

Remove-XenGPUGroup [-GPUGroup] <GPU_group> [-PassThru] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [-Async] [<CommonParameters>]

Remove-XenGPUGroup [-Ref] <XenRef[GPU_group]> [-PassThru] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [-Async] [<CommonParameters>]

Remove-XenGPUGroup [-Uuid] <guid> [-PassThru] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [-Async] [<CommonParameters>]

Remove-XenGPUGroup [-Name] <string> [-PassThru] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [-Async] [<CommonParameters>]


## Remove-XenGPUGroupProperty

### Synopsis
None

### Description
None

### Syntax
```
Remove-XenGPUGroupProperty [-GPUGroup] <GPU_group> [[-PassThru]] [[-OtherConfig] <string>] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]] [-Ref] <XenRef[GPU_group]> [[-PassThru]] [[-OtherConfig] <string>] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]] [-Uuid] <guid> [[-PassThru]] [[-OtherConfig] <string>] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]] [-Name] <string> [[-PassThru]] [[-OtherConfig] <string>] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]]
```
### Parameters
| Name | Type | Required | Default Value | Description |
| :--- | :--- | :------- | :------------ | :---------- |
| BestEffort | switch | False |  |  |
| Confirm | switch | False |  |  |
| GPUGroup | GPU_group | True |  |  |
| Name | string | True |  |  |
| OtherConfig | string | False |  |  |
| PassThru | switch | False |  |  |
| Ref | XenRef[GPU_group] | True |  |  |
| SessionOpaqueRef | string | False |  |  |
| Uuid | guid | True |  |  |
| WhatIf | switch | False |  |  |
### Procedure
None

### Inputs
```
XenAPI.GPU_group
XenAPI.XenRef`1[[XenAPI.GPU_group, XenServer, Version=8.2.3.0, Culture=neutral, PublicKeyToken=d247b8b0ac7959e9]]
System.Guid
System.String

```
### Outputs
```
XenAPI.GPU_group

```
### Links
None

### Examples

Remove-XenGPUGroupProperty [-GPUGroup] <GPU_group> [-PassThru] [-OtherConfig <string>] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [<CommonParameters>]

Remove-XenGPUGroupProperty [-Ref] <XenRef[GPU_group]> [-PassThru] [-OtherConfig <string>] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [<CommonParameters>]

Remove-XenGPUGroupProperty [-Uuid] <guid> [-PassThru] [-OtherConfig <string>] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [<CommonParameters>]

Remove-XenGPUGroupProperty [-Name] <string> [-PassThru] [-OtherConfig <string>] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [<CommonParameters>]


## Remove-XenHost

### Synopsis
None

### Description
None

### Syntax
```
Remove-XenHost [-XenHost] <Host> [[-PassThru]] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]] [[-Async]] [-Ref] <XenRef[Host]> [[-PassThru]] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]] [[-Async]] [-Uuid] <guid> [[-PassThru]] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]] [[-Async]] [-Name] <string> [[-PassThru]] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]] [[-Async]]
```
### Parameters
| Name | Type | Required | Default Value | Description |
| :--- | :--- | :------- | :------------ | :---------- |
| Async | switch | False |  |  |
| BestEffort | switch | False |  |  |
| Confirm | switch | False |  |  |
| Name | string | True |  |  |
| PassThru | switch | False |  |  |
| Ref | XenRef[Host] | True |  |  |
| SessionOpaqueRef | string | False |  |  |
| Uuid | guid | True |  |  |
| WhatIf | switch | False |  |  |
| XenHost | Host | True |  |  |
### Procedure
None

### Inputs
```
XenAPI.Host
XenAPI.XenRef`1[[XenAPI.Host, XenServer, Version=8.2.3.0, Culture=neutral, PublicKeyToken=d247b8b0ac7959e9]]
System.Guid
System.String

```
### Outputs
```
XenAPI.Host
XenAPI.Task
System.Void

```
### Links
None

### Examples

Remove-XenHost [-XenHost] <Host> [-PassThru] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [-Async] [<CommonParameters>]

Remove-XenHost [-Ref] <XenRef[Host]> [-PassThru] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [-Async] [<CommonParameters>]

Remove-XenHost [-Uuid] <guid> [-PassThru] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [-Async] [<CommonParameters>]

Remove-XenHost [-Name] <string> [-PassThru] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [-Async] [<CommonParameters>]


## Remove-XenHostCpuProperty

### Synopsis
None

### Description
None

### Syntax
```
Remove-XenHostCpuProperty [-HostCpu] <Host_cpu> [[-PassThru]] [[-OtherConfig] <string>] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]] [-Ref] <XenRef[Host_cpu]> [[-PassThru]] [[-OtherConfig] <string>] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]] [-Uuid] <guid> [[-PassThru]] [[-OtherConfig] <string>] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]]
```
### Parameters
| Name | Type | Required | Default Value | Description |
| :--- | :--- | :------- | :------------ | :---------- |
| BestEffort | switch | False |  |  |
| Confirm | switch | False |  |  |
| HostCpu | Host_cpu | True |  |  |
| OtherConfig | string | False |  |  |
| PassThru | switch | False |  |  |
| Ref | XenRef[Host_cpu] | True |  |  |
| SessionOpaqueRef | string | False |  |  |
| Uuid | guid | True |  |  |
| WhatIf | switch | False |  |  |
### Procedure
None

### Inputs
```
XenAPI.Host_cpu
XenAPI.XenRef`1[[XenAPI.Host_cpu, XenServer, Version=8.2.3.0, Culture=neutral, PublicKeyToken=d247b8b0ac7959e9]]
System.Guid

```
### Outputs
```
XenAPI.Host_cpu

```
### Links
None

### Examples

Remove-XenHostCpuProperty [-HostCpu] <Host_cpu> [-PassThru] [-OtherConfig <string>] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [<CommonParameters>]

Remove-XenHostCpuProperty [-Ref] <XenRef[Host_cpu]> [-PassThru] [-OtherConfig <string>] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [<CommonParameters>]

Remove-XenHostCpuProperty [-Uuid] <guid> [-PassThru] [-OtherConfig <string>] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [<CommonParameters>]


## Remove-XenHostCrashdump

### Synopsis
None

### Description
None

### Syntax
```
Remove-XenHostCrashdump [-HostCrashdump] <Host_crashdump> [[-PassThru]] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]] [[-Async]] [-Ref] <XenRef[Host_crashdump]> [[-PassThru]] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]] [[-Async]] [-Uuid] <guid> [[-PassThru]] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]] [[-Async]]
```
### Parameters
| Name | Type | Required | Default Value | Description |
| :--- | :--- | :------- | :------------ | :---------- |
| Async | switch | False |  |  |
| BestEffort | switch | False |  |  |
| Confirm | switch | False |  |  |
| HostCrashdump | Host_crashdump | True |  |  |
| PassThru | switch | False |  |  |
| Ref | XenRef[Host_crashdump] | True |  |  |
| SessionOpaqueRef | string | False |  |  |
| Uuid | guid | True |  |  |
| WhatIf | switch | False |  |  |
### Procedure
None

### Inputs
```
XenAPI.Host_crashdump
XenAPI.XenRef`1[[XenAPI.Host_crashdump, XenServer, Version=8.2.3.0, Culture=neutral, PublicKeyToken=d247b8b0ac7959e9]]
System.Guid

```
### Outputs
```
XenAPI.Host_crashdump
XenAPI.Task
System.Void

```
### Links
None

### Examples

Remove-XenHostCrashdump [-HostCrashdump] <Host_crashdump> [-PassThru] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [-Async] [<CommonParameters>]

Remove-XenHostCrashdump [-Ref] <XenRef[Host_crashdump]> [-PassThru] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [-Async] [<CommonParameters>]

Remove-XenHostCrashdump [-Uuid] <guid> [-PassThru] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [-Async] [<CommonParameters>]


## Remove-XenHostCrashdumpProperty

### Synopsis
None

### Description
None

### Syntax
```
Remove-XenHostCrashdumpProperty [-HostCrashdump] <Host_crashdump> [[-PassThru]] [[-OtherConfig] <string>] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]] [-Ref] <XenRef[Host_crashdump]> [[-PassThru]] [[-OtherConfig] <string>] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]] [-Uuid] <guid> [[-PassThru]] [[-OtherConfig] <string>] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]]
```
### Parameters
| Name | Type | Required | Default Value | Description |
| :--- | :--- | :------- | :------------ | :---------- |
| BestEffort | switch | False |  |  |
| Confirm | switch | False |  |  |
| HostCrashdump | Host_crashdump | True |  |  |
| OtherConfig | string | False |  |  |
| PassThru | switch | False |  |  |
| Ref | XenRef[Host_crashdump] | True |  |  |
| SessionOpaqueRef | string | False |  |  |
| Uuid | guid | True |  |  |
| WhatIf | switch | False |  |  |
### Procedure
None

### Inputs
```
XenAPI.Host_crashdump
XenAPI.XenRef`1[[XenAPI.Host_crashdump, XenServer, Version=8.2.3.0, Culture=neutral, PublicKeyToken=d247b8b0ac7959e9]]
System.Guid

```
### Outputs
```
XenAPI.Host_crashdump

```
### Links
None

### Examples

Remove-XenHostCrashdumpProperty [-HostCrashdump] <Host_crashdump> [-PassThru] [-OtherConfig <string>] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [<CommonParameters>]

Remove-XenHostCrashdumpProperty [-Ref] <XenRef[Host_crashdump]> [-PassThru] [-OtherConfig <string>] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [<CommonParameters>]

Remove-XenHostCrashdumpProperty [-Uuid] <guid> [-PassThru] [-OtherConfig <string>] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [<CommonParameters>]


## Remove-XenHostMetricsProperty

### Synopsis
None

### Description
None

### Syntax
```
Remove-XenHostMetricsProperty [-HostMetrics] <Host_metrics> [[-PassThru]] [[-OtherConfig] <string>] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]] [-Ref] <XenRef[Host_metrics]> [[-PassThru]] [[-OtherConfig] <string>] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]] [-Uuid] <guid> [[-PassThru]] [[-OtherConfig] <string>] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]]
```
### Parameters
| Name | Type | Required | Default Value | Description |
| :--- | :--- | :------- | :------------ | :---------- |
| BestEffort | switch | False |  |  |
| Confirm | switch | False |  |  |
| HostMetrics | Host_metrics | True |  |  |
| OtherConfig | string | False |  |  |
| PassThru | switch | False |  |  |
| Ref | XenRef[Host_metrics] | True |  |  |
| SessionOpaqueRef | string | False |  |  |
| Uuid | guid | True |  |  |
| WhatIf | switch | False |  |  |
### Procedure
None

### Inputs
```
XenAPI.Host_metrics
XenAPI.XenRef`1[[XenAPI.Host_metrics, XenServer, Version=8.2.3.0, Culture=neutral, PublicKeyToken=d247b8b0ac7959e9]]
System.Guid

```
### Outputs
```
XenAPI.Host_metrics

```
### Links
None

### Examples

Remove-XenHostMetricsProperty [-HostMetrics] <Host_metrics> [-PassThru] [-OtherConfig <string>] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [<CommonParameters>]

Remove-XenHostMetricsProperty [-Ref] <XenRef[Host_metrics]> [-PassThru] [-OtherConfig <string>] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [<CommonParameters>]

Remove-XenHostMetricsProperty [-Uuid] <guid> [-PassThru] [-OtherConfig <string>] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [<CommonParameters>]


## Remove-XenHostPatch

### Synopsis
None

### Description
None

### Syntax
```
Remove-XenHostPatch [-HostPatch] <Host_patch> [[-PassThru]] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]] [[-Async]] [-Ref] <XenRef[Host_patch]> [[-PassThru]] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]] [[-Async]] [-Uuid] <guid> [[-PassThru]] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]] [[-Async]] [-Name] <string> [[-PassThru]] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]] [[-Async]]
```
### Parameters
| Name | Type | Required | Default Value | Description |
| :--- | :--- | :------- | :------------ | :---------- |
| Async | switch | False |  |  |
| BestEffort | switch | False |  |  |
| Confirm | switch | False |  |  |
| HostPatch | Host_patch | True |  |  |
| Name | string | True |  |  |
| PassThru | switch | False |  |  |
| Ref | XenRef[Host_patch] | True |  |  |
| SessionOpaqueRef | string | False |  |  |
| Uuid | guid | True |  |  |
| WhatIf | switch | False |  |  |
### Procedure
None

### Inputs
```
XenAPI.Host_patch
XenAPI.XenRef`1[[XenAPI.Host_patch, XenServer, Version=8.2.3.0, Culture=neutral, PublicKeyToken=d247b8b0ac7959e9]]
System.Guid
System.String

```
### Outputs
```
XenAPI.Host_patch
XenAPI.Task
System.Void

```
### Links
None

### Examples

Remove-XenHostPatch [-HostPatch] <Host_patch> [-PassThru] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [-Async] [<CommonParameters>]

Remove-XenHostPatch [-Ref] <XenRef[Host_patch]> [-PassThru] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [-Async] [<CommonParameters>]

Remove-XenHostPatch [-Uuid] <guid> [-PassThru] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [-Async] [<CommonParameters>]

Remove-XenHostPatch [-Name] <string> [-PassThru] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [-Async] [<CommonParameters>]


## Remove-XenHostPatchProperty

### Synopsis
None

### Description
None

### Syntax
```
Remove-XenHostPatchProperty [-HostPatch] <Host_patch> [[-PassThru]] [[-OtherConfig] <string>] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]] [-Ref] <XenRef[Host_patch]> [[-PassThru]] [[-OtherConfig] <string>] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]] [-Uuid] <guid> [[-PassThru]] [[-OtherConfig] <string>] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]] [-Name] <string> [[-PassThru]] [[-OtherConfig] <string>] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]]
```
### Parameters
| Name | Type | Required | Default Value | Description |
| :--- | :--- | :------- | :------------ | :---------- |
| BestEffort | switch | False |  |  |
| Confirm | switch | False |  |  |
| HostPatch | Host_patch | True |  |  |
| Name | string | True |  |  |
| OtherConfig | string | False |  |  |
| PassThru | switch | False |  |  |
| Ref | XenRef[Host_patch] | True |  |  |
| SessionOpaqueRef | string | False |  |  |
| Uuid | guid | True |  |  |
| WhatIf | switch | False |  |  |
### Procedure
None

### Inputs
```
XenAPI.Host_patch
XenAPI.XenRef`1[[XenAPI.Host_patch, XenServer, Version=8.2.3.0, Culture=neutral, PublicKeyToken=d247b8b0ac7959e9]]
System.Guid
System.String

```
### Outputs
```
XenAPI.Host_patch

```
### Links
None

### Examples

Remove-XenHostPatchProperty [-HostPatch] <Host_patch> [-PassThru] [-OtherConfig <string>] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [<CommonParameters>]

Remove-XenHostPatchProperty [-Ref] <XenRef[Host_patch]> [-PassThru] [-OtherConfig <string>] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [<CommonParameters>]

Remove-XenHostPatchProperty [-Uuid] <guid> [-PassThru] [-OtherConfig <string>] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [<CommonParameters>]

Remove-XenHostPatchProperty [-Name] <string> [-PassThru] [-OtherConfig <string>] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [<CommonParameters>]


## Remove-XenHostProperty

### Synopsis
None

### Description
None

### Syntax
```
Remove-XenHostProperty [-XenHost] <Host> [[-PassThru]] [[-OtherConfig] <string>] [[-Logging] <string>] [[-Tags] <string>] [[-LicenseServer] <string>] [[-GuestVCPUsParams] <string>] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]] [-Ref] <XenRef[Host]> [[-PassThru]] [[-OtherConfig] <string>] [[-Logging] <string>] [[-Tags] <string>] [[-LicenseServer] <string>] [[-GuestVCPUsParams] <string>] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]] [-Uuid] <guid> [[-PassThru]] [[-OtherConfig] <string>] [[-Logging] <string>] [[-Tags] <string>] [[-LicenseServer] <string>] [[-GuestVCPUsParams] <string>] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]] [-Name] <string> [[-PassThru]] [[-OtherConfig] <string>] [[-Logging] <string>] [[-Tags] <string>] [[-LicenseServer] <string>] [[-GuestVCPUsParams] <string>] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]]
```
### Parameters
| Name | Type | Required | Default Value | Description |
| :--- | :--- | :------- | :------------ | :---------- |
| BestEffort | switch | False |  |  |
| Confirm | switch | False |  |  |
| GuestVCPUsParams | string | False |  |  |
| LicenseServer | string | False |  |  |
| Logging | string | False |  |  |
| Name | string | True |  |  |
| OtherConfig | string | False |  |  |
| PassThru | switch | False |  |  |
| Ref | XenRef[Host] | True |  |  |
| SessionOpaqueRef | string | False |  |  |
| Tags | string | False |  |  |
| Uuid | guid | True |  |  |
| WhatIf | switch | False |  |  |
| XenHost | Host | True |  |  |
### Procedure
None

### Inputs
```
XenAPI.Host
XenAPI.XenRef`1[[XenAPI.Host, XenServer, Version=8.2.3.0, Culture=neutral, PublicKeyToken=d247b8b0ac7959e9]]
System.Guid
System.String

```
### Outputs
```
XenAPI.Host

```
### Links
None

### Examples

Remove-XenHostProperty [-XenHost] <Host> [-PassThru] [-OtherConfig <string>] [-Logging <string>] [-Tags <string>] [-LicenseServer <string>] [-GuestVCPUsParams <string>] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [<CommonParameters>]

Remove-XenHostProperty [-Ref] <XenRef[Host]> [-PassThru] [-OtherConfig <string>] [-Logging <string>] [-Tags <string>] [-LicenseServer <string>] [-GuestVCPUsParams <string>] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [<CommonParameters>]

Remove-XenHostProperty [-Uuid] <guid> [-PassThru] [-OtherConfig <string>] [-Logging <string>] [-Tags <string>] [-LicenseServer <string>] [-GuestVCPUsParams <string>] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [<CommonParameters>]

Remove-XenHostProperty [-Name] <string> [-PassThru] [-OtherConfig <string>] [-Logging <string>] [-Tags <string>] [-LicenseServer <string>] [-GuestVCPUsParams <string>] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [<CommonParameters>]


## Remove-XenMessage

### Synopsis
None

### Description
None

### Syntax
```
Remove-XenMessage [-Message] <Message> [[-PassThru]] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]] [-Ref] <XenRef[Message]> [[-PassThru]] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]] [-Uuid] <guid> [[-PassThru]] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]]
```
### Parameters
| Name | Type | Required | Default Value | Description |
| :--- | :--- | :------- | :------------ | :---------- |
| BestEffort | switch | False |  |  |
| Confirm | switch | False |  |  |
| Message | Message | True |  |  |
| PassThru | switch | False |  |  |
| Ref | XenRef[Message] | True |  |  |
| SessionOpaqueRef | string | False |  |  |
| Uuid | guid | True |  |  |
| WhatIf | switch | False |  |  |
### Procedure
None

### Inputs
```
XenAPI.Message
XenAPI.XenRef`1[[XenAPI.Message, XenServer, Version=8.2.3.0, Culture=neutral, PublicKeyToken=d247b8b0ac7959e9]]
System.Guid

```
### Outputs
```
XenAPI.Message
System.Void

```
### Links
None

### Examples

Remove-XenMessage [-Message] <Message> [-PassThru] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [<CommonParameters>]

Remove-XenMessage [-Ref] <XenRef[Message]> [-PassThru] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [<CommonParameters>]

Remove-XenMessage [-Uuid] <guid> [-PassThru] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [<CommonParameters>]


## Remove-XenNetwork

### Synopsis
None

### Description
None

### Syntax
```
Remove-XenNetwork [-Network] <Network> [[-PassThru]] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]] [[-Async]] [-Ref] <XenRef[Network]> [[-PassThru]] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]] [[-Async]] [-Uuid] <guid> [[-PassThru]] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]] [[-Async]] [-Name] <string> [[-PassThru]] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]] [[-Async]]
```
### Parameters
| Name | Type | Required | Default Value | Description |
| :--- | :--- | :------- | :------------ | :---------- |
| Async | switch | False |  |  |
| BestEffort | switch | False |  |  |
| Confirm | switch | False |  |  |
| Name | string | True |  |  |
| Network | Network | True |  |  |
| PassThru | switch | False |  |  |
| Ref | XenRef[Network] | True |  |  |
| SessionOpaqueRef | string | False |  |  |
| Uuid | guid | True |  |  |
| WhatIf | switch | False |  |  |
### Procedure
None

### Inputs
```
XenAPI.Network
XenAPI.XenRef`1[[XenAPI.Network, XenServer, Version=8.2.3.0, Culture=neutral, PublicKeyToken=d247b8b0ac7959e9]]
System.Guid
System.String

```
### Outputs
```
XenAPI.Network
XenAPI.Task
System.Void

```
### Links
None

### Examples

Remove-XenNetwork [-Network] <Network> [-PassThru] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [-Async] [<CommonParameters>]

Remove-XenNetwork [-Ref] <XenRef[Network]> [-PassThru] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [-Async] [<CommonParameters>]

Remove-XenNetwork [-Uuid] <guid> [-PassThru] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [-Async] [<CommonParameters>]

Remove-XenNetwork [-Name] <string> [-PassThru] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [-Async] [<CommonParameters>]


## Remove-XenNetworkProperty

### Synopsis
None

### Description
None

### Syntax
```
Remove-XenNetworkProperty [-Network] <Network> [[-PassThru]] [[-OtherConfig] <string>] [[-Tags] <string>] [[-Purpose] <network_purpose>] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]] [-Ref] <XenRef[Network]> [[-PassThru]] [[-OtherConfig] <string>] [[-Tags] <string>] [[-Purpose] <network_purpose>] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]] [-Uuid] <guid> [[-PassThru]] [[-OtherConfig] <string>] [[-Tags] <string>] [[-Purpose] <network_purpose>] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]] [-Name] <string> [[-PassThru]] [[-OtherConfig] <string>] [[-Tags] <string>] [[-Purpose] <network_purpose>] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]]
```
### Parameters
| Name | Type | Required | Default Value | Description |
| :--- | :--- | :------- | :------------ | :---------- |
| BestEffort | switch | False |  |  |
| Confirm | switch | False |  |  |
| Name | string | True |  |  |
| Network | Network | True |  |  |
| OtherConfig | string | False |  |  |
| PassThru | switch | False |  |  |
| Purpose | network_purpose | False |  |  |
| Ref | XenRef[Network] | True |  |  |
| SessionOpaqueRef | string | False |  |  |
| Tags | string | False |  |  |
| Uuid | guid | True |  |  |
| WhatIf | switch | False |  |  |
### Procedure
None

### Inputs
```
XenAPI.Network
XenAPI.XenRef`1[[XenAPI.Network, XenServer, Version=8.2.3.0, Culture=neutral, PublicKeyToken=d247b8b0ac7959e9]]
System.Guid
System.String

```
### Outputs
```
XenAPI.Network
XenAPI.Task

```
### Links
None

### Examples

Remove-XenNetworkProperty [-Network] <Network> [-PassThru] [-OtherConfig <string>] [-Tags <string>] [-Purpose <network_purpose>] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [<CommonParameters>]

Remove-XenNetworkProperty [-Ref] <XenRef[Network]> [-PassThru] [-OtherConfig <string>] [-Tags <string>] [-Purpose <network_purpose>] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [<CommonParameters>]

Remove-XenNetworkProperty [-Uuid] <guid> [-PassThru] [-OtherConfig <string>] [-Tags <string>] [-Purpose <network_purpose>] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [<CommonParameters>]

Remove-XenNetworkProperty [-Name] <string> [-PassThru] [-OtherConfig <string>] [-Tags <string>] [-Purpose <network_purpose>] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [<CommonParameters>]


## Remove-XenNetworkSriov

### Synopsis
None

### Description
None

### Syntax
```
Remove-XenNetworkSriov [-NetworkSriov] <Network_sriov> [[-PassThru]] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]] [[-Async]] [-Ref] <XenRef[Network_sriov]> [[-PassThru]] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]] [[-Async]] [-Uuid] <guid> [[-PassThru]] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]] [[-Async]]
```
### Parameters
| Name | Type | Required | Default Value | Description |
| :--- | :--- | :------- | :------------ | :---------- |
| Async | switch | False |  |  |
| BestEffort | switch | False |  |  |
| Confirm | switch | False |  |  |
| NetworkSriov | Network_sriov | True |  |  |
| PassThru | switch | False |  |  |
| Ref | XenRef[Network_sriov] | True |  |  |
| SessionOpaqueRef | string | False |  |  |
| Uuid | guid | True |  |  |
| WhatIf | switch | False |  |  |
### Procedure
None

### Inputs
```
XenAPI.Network_sriov
XenAPI.XenRef`1[[XenAPI.Network_sriov, XenServer, Version=8.2.3.0, Culture=neutral, PublicKeyToken=d247b8b0ac7959e9]]
System.Guid

```
### Outputs
```
XenAPI.Network_sriov
XenAPI.Task
System.Void

```
### Links
None

### Examples

Remove-XenNetworkSriov [-NetworkSriov] <Network_sriov> [-PassThru] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [-Async] [<CommonParameters>]

Remove-XenNetworkSriov [-Ref] <XenRef[Network_sriov]> [-PassThru] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [-Async] [<CommonParameters>]

Remove-XenNetworkSriov [-Uuid] <guid> [-PassThru] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [-Async] [<CommonParameters>]


## Remove-XenPBD

### Synopsis
None

### Description
None

### Syntax
```
Remove-XenPBD [-PBD] <PBD> [[-PassThru]] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]] [[-Async]] [-Ref] <XenRef[PBD]> [[-PassThru]] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]] [[-Async]] [-Uuid] <guid> [[-PassThru]] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]] [[-Async]]
```
### Parameters
| Name | Type | Required | Default Value | Description |
| :--- | :--- | :------- | :------------ | :---------- |
| Async | switch | False |  |  |
| BestEffort | switch | False |  |  |
| Confirm | switch | False |  |  |
| PBD | PBD | True |  |  |
| PassThru | switch | False |  |  |
| Ref | XenRef[PBD] | True |  |  |
| SessionOpaqueRef | string | False |  |  |
| Uuid | guid | True |  |  |
| WhatIf | switch | False |  |  |
### Procedure
None

### Inputs
```
XenAPI.PBD
XenAPI.XenRef`1[[XenAPI.PBD, XenServer, Version=8.2.3.0, Culture=neutral, PublicKeyToken=d247b8b0ac7959e9]]
System.Guid

```
### Outputs
```
XenAPI.PBD
XenAPI.Task
System.Void

```
### Links
None

### Examples

Remove-XenPBD [-PBD] <PBD> [-PassThru] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [-Async] [<CommonParameters>]

Remove-XenPBD [-Ref] <XenRef[PBD]> [-PassThru] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [-Async] [<CommonParameters>]

Remove-XenPBD [-Uuid] <guid> [-PassThru] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [-Async] [<CommonParameters>]


## Remove-XenPBDProperty

### Synopsis
None

### Description
None

### Syntax
```
Remove-XenPBDProperty [-PBD] <PBD> [[-PassThru]] [[-OtherConfig] <string>] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]] [-Ref] <XenRef[PBD]> [[-PassThru]] [[-OtherConfig] <string>] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]] [-Uuid] <guid> [[-PassThru]] [[-OtherConfig] <string>] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]]
```
### Parameters
| Name | Type | Required | Default Value | Description |
| :--- | :--- | :------- | :------------ | :---------- |
| BestEffort | switch | False |  |  |
| Confirm | switch | False |  |  |
| OtherConfig | string | False |  |  |
| PBD | PBD | True |  |  |
| PassThru | switch | False |  |  |
| Ref | XenRef[PBD] | True |  |  |
| SessionOpaqueRef | string | False |  |  |
| Uuid | guid | True |  |  |
| WhatIf | switch | False |  |  |
### Procedure
None

### Inputs
```
XenAPI.PBD
XenAPI.XenRef`1[[XenAPI.PBD, XenServer, Version=8.2.3.0, Culture=neutral, PublicKeyToken=d247b8b0ac7959e9]]
System.Guid

```
### Outputs
```
XenAPI.PBD

```
### Links
None

### Examples

Remove-XenPBDProperty [-PBD] <PBD> [-PassThru] [-OtherConfig <string>] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [<CommonParameters>]

Remove-XenPBDProperty [-Ref] <XenRef[PBD]> [-PassThru] [-OtherConfig <string>] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [<CommonParameters>]

Remove-XenPBDProperty [-Uuid] <guid> [-PassThru] [-OtherConfig <string>] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [<CommonParameters>]


## Remove-XenPCIProperty

### Synopsis
None

### Description
None

### Syntax
```
Remove-XenPCIProperty [-PCI] <PCI> [[-PassThru]] [[-OtherConfig] <string>] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]] [-Ref] <XenRef[PCI]> [[-PassThru]] [[-OtherConfig] <string>] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]] [-Uuid] <guid> [[-PassThru]] [[-OtherConfig] <string>] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]]
```
### Parameters
| Name | Type | Required | Default Value | Description |
| :--- | :--- | :------- | :------------ | :---------- |
| BestEffort | switch | False |  |  |
| Confirm | switch | False |  |  |
| OtherConfig | string | False |  |  |
| PCI | PCI | True |  |  |
| PassThru | switch | False |  |  |
| Ref | XenRef[PCI] | True |  |  |
| SessionOpaqueRef | string | False |  |  |
| Uuid | guid | True |  |  |
| WhatIf | switch | False |  |  |
### Procedure
None

### Inputs
```
XenAPI.PCI
XenAPI.XenRef`1[[XenAPI.PCI, XenServer, Version=8.2.3.0, Culture=neutral, PublicKeyToken=d247b8b0ac7959e9]]
System.Guid

```
### Outputs
```
XenAPI.PCI

```
### Links
None

### Examples

Remove-XenPCIProperty [-PCI] <PCI> [-PassThru] [-OtherConfig <string>] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [<CommonParameters>]

Remove-XenPCIProperty [-Ref] <XenRef[PCI]> [-PassThru] [-OtherConfig <string>] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [<CommonParameters>]

Remove-XenPCIProperty [-Uuid] <guid> [-PassThru] [-OtherConfig <string>] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [<CommonParameters>]


## Remove-XenPGPUProperty

### Synopsis
None

### Description
None

### Syntax
```
Remove-XenPGPUProperty [-PGPU] <PGPU> [[-PassThru]] [[-OtherConfig] <string>] [[-EnabledVGPUTypes] <XenRef[VGPU_type]>] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]] [-Ref] <XenRef[PGPU]> [[-PassThru]] [[-OtherConfig] <string>] [[-EnabledVGPUTypes] <XenRef[VGPU_type]>] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]] [-Uuid] <guid> [[-PassThru]] [[-OtherConfig] <string>] [[-EnabledVGPUTypes] <XenRef[VGPU_type]>] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]]
```
### Parameters
| Name | Type | Required | Default Value | Description |
| :--- | :--- | :------- | :------------ | :---------- |
| BestEffort | switch | False |  |  |
| Confirm | switch | False |  |  |
| EnabledVGPUTypes | XenRef[VGPU_type] | False |  |  |
| OtherConfig | string | False |  |  |
| PGPU | PGPU | True |  |  |
| PassThru | switch | False |  |  |
| Ref | XenRef[PGPU] | True |  |  |
| SessionOpaqueRef | string | False |  |  |
| Uuid | guid | True |  |  |
| WhatIf | switch | False |  |  |
### Procedure
None

### Inputs
```
XenAPI.PGPU
XenAPI.XenRef`1[[XenAPI.PGPU, XenServer, Version=8.2.3.0, Culture=neutral, PublicKeyToken=d247b8b0ac7959e9]]
System.Guid

```
### Outputs
```
XenAPI.PGPU
XenAPI.Task

```
### Links
None

### Examples

Remove-XenPGPUProperty [-PGPU] <PGPU> [-PassThru] [-OtherConfig <string>] [-EnabledVGPUTypes <XenRef[VGPU_type]>] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [<CommonParameters>]

Remove-XenPGPUProperty [-Ref] <XenRef[PGPU]> [-PassThru] [-OtherConfig <string>] [-EnabledVGPUTypes <XenRef[VGPU_type]>] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [<CommonParameters>]

Remove-XenPGPUProperty [-Uuid] <guid> [-PassThru] [-OtherConfig <string>] [-EnabledVGPUTypes <XenRef[VGPU_type]>] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [<CommonParameters>]


## Remove-XenPIF

### Synopsis
None

### Description
None

### Syntax
```
Remove-XenPIF [-PIF] <PIF> [[-PassThru]] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]] [[-Async]] [-Ref] <XenRef[PIF]> [[-PassThru]] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]] [[-Async]] [-Uuid] <guid> [[-PassThru]] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]] [[-Async]]
```
### Parameters
| Name | Type | Required | Default Value | Description |
| :--- | :--- | :------- | :------------ | :---------- |
| Async | switch | False |  |  |
| BestEffort | switch | False |  |  |
| Confirm | switch | False |  |  |
| PIF | PIF | True |  |  |
| PassThru | switch | False |  |  |
| Ref | XenRef[PIF] | True |  |  |
| SessionOpaqueRef | string | False |  |  |
| Uuid | guid | True |  |  |
| WhatIf | switch | False |  |  |
### Procedure
None

### Inputs
```
XenAPI.PIF
XenAPI.XenRef`1[[XenAPI.PIF, XenServer, Version=8.2.3.0, Culture=neutral, PublicKeyToken=d247b8b0ac7959e9]]
System.Guid

```
### Outputs
```
XenAPI.PIF
XenAPI.Task
System.Void

```
### Links
None

### Examples

Remove-XenPIF [-PIF] <PIF> [-PassThru] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [-Async] [<CommonParameters>]

Remove-XenPIF [-Ref] <XenRef[PIF]> [-PassThru] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [-Async] [<CommonParameters>]

Remove-XenPIF [-Uuid] <guid> [-PassThru] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [-Async] [<CommonParameters>]


## Remove-XenPIFMetricsProperty

### Synopsis
None

### Description
None

### Syntax
```
Remove-XenPIFMetricsProperty [-PIFMetrics] <PIF_metrics> [[-PassThru]] [[-OtherConfig] <string>] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]] [-Ref] <XenRef[PIF_metrics]> [[-PassThru]] [[-OtherConfig] <string>] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]] [-Uuid] <guid> [[-PassThru]] [[-OtherConfig] <string>] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]]
```
### Parameters
| Name | Type | Required | Default Value | Description |
| :--- | :--- | :------- | :------------ | :---------- |
| BestEffort | switch | False |  |  |
| Confirm | switch | False |  |  |
| OtherConfig | string | False |  |  |
| PIFMetrics | PIF_metrics | True |  |  |
| PassThru | switch | False |  |  |
| Ref | XenRef[PIF_metrics] | True |  |  |
| SessionOpaqueRef | string | False |  |  |
| Uuid | guid | True |  |  |
| WhatIf | switch | False |  |  |
### Procedure
None

### Inputs
```
XenAPI.PIF_metrics
XenAPI.XenRef`1[[XenAPI.PIF_metrics, XenServer, Version=8.2.3.0, Culture=neutral, PublicKeyToken=d247b8b0ac7959e9]]
System.Guid

```
### Outputs
```
XenAPI.PIF_metrics

```
### Links
None

### Examples

Remove-XenPIFMetricsProperty [-PIFMetrics] <PIF_metrics> [-PassThru] [-OtherConfig <string>] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [<CommonParameters>]

Remove-XenPIFMetricsProperty [-Ref] <XenRef[PIF_metrics]> [-PassThru] [-OtherConfig <string>] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [<CommonParameters>]

Remove-XenPIFMetricsProperty [-Uuid] <guid> [-PassThru] [-OtherConfig <string>] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [<CommonParameters>]


## Remove-XenPIFProperty

### Synopsis
None

### Description
None

### Syntax
```
Remove-XenPIFProperty [-PIF] <PIF> [[-PassThru]] [[-OtherConfig] <string>] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]] [-Ref] <XenRef[PIF]> [[-PassThru]] [[-OtherConfig] <string>] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]] [-Uuid] <guid> [[-PassThru]] [[-OtherConfig] <string>] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]]
```
### Parameters
| Name | Type | Required | Default Value | Description |
| :--- | :--- | :------- | :------------ | :---------- |
| BestEffort | switch | False |  |  |
| Confirm | switch | False |  |  |
| OtherConfig | string | False |  |  |
| PIF | PIF | True |  |  |
| PassThru | switch | False |  |  |
| Ref | XenRef[PIF] | True |  |  |
| SessionOpaqueRef | string | False |  |  |
| Uuid | guid | True |  |  |
| WhatIf | switch | False |  |  |
### Procedure
None

### Inputs
```
XenAPI.PIF
XenAPI.XenRef`1[[XenAPI.PIF, XenServer, Version=8.2.3.0, Culture=neutral, PublicKeyToken=d247b8b0ac7959e9]]
System.Guid

```
### Outputs
```
XenAPI.PIF

```
### Links
None

### Examples

Remove-XenPIFProperty [-PIF] <PIF> [-PassThru] [-OtherConfig <string>] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [<CommonParameters>]

Remove-XenPIFProperty [-Ref] <XenRef[PIF]> [-PassThru] [-OtherConfig <string>] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [<CommonParameters>]

Remove-XenPIFProperty [-Uuid] <guid> [-PassThru] [-OtherConfig <string>] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [<CommonParameters>]


## Remove-XenPoolPatch

### Synopsis
None

### Description
None

### Syntax
```
Remove-XenPoolPatch [-PoolPatch] <Pool_patch> [[-PassThru]] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]] [[-Async]] [-Ref] <XenRef[Pool_patch]> [[-PassThru]] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]] [[-Async]] [-Uuid] <guid> [[-PassThru]] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]] [[-Async]] [-Name] <string> [[-PassThru]] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]] [[-Async]]
```
### Parameters
| Name | Type | Required | Default Value | Description |
| :--- | :--- | :------- | :------------ | :---------- |
| Async | switch | False |  |  |
| BestEffort | switch | False |  |  |
| Confirm | switch | False |  |  |
| Name | string | True |  |  |
| PassThru | switch | False |  |  |
| PoolPatch | Pool_patch | True |  |  |
| Ref | XenRef[Pool_patch] | True |  |  |
| SessionOpaqueRef | string | False |  |  |
| Uuid | guid | True |  |  |
| WhatIf | switch | False |  |  |
### Procedure
None

### Inputs
```
XenAPI.Pool_patch
XenAPI.XenRef`1[[XenAPI.Pool_patch, XenServer, Version=8.2.3.0, Culture=neutral, PublicKeyToken=d247b8b0ac7959e9]]
System.Guid
System.String

```
### Outputs
```
XenAPI.Pool_patch
XenAPI.Task
System.Void

```
### Links
None

### Examples

Remove-XenPoolPatch [-PoolPatch] <Pool_patch> [-PassThru] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [-Async] [<CommonParameters>]

Remove-XenPoolPatch [-Ref] <XenRef[Pool_patch]> [-PassThru] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [-Async] [<CommonParameters>]

Remove-XenPoolPatch [-Uuid] <guid> [-PassThru] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [-Async] [<CommonParameters>]

Remove-XenPoolPatch [-Name] <string> [-PassThru] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [-Async] [<CommonParameters>]


## Remove-XenPoolPatchProperty

### Synopsis
None

### Description
None

### Syntax
```
Remove-XenPoolPatchProperty [-PoolPatch] <Pool_patch> [[-PassThru]] [[-OtherConfig] <string>] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]] [-Ref] <XenRef[Pool_patch]> [[-PassThru]] [[-OtherConfig] <string>] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]] [-Uuid] <guid> [[-PassThru]] [[-OtherConfig] <string>] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]] [-Name] <string> [[-PassThru]] [[-OtherConfig] <string>] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]]
```
### Parameters
| Name | Type | Required | Default Value | Description |
| :--- | :--- | :------- | :------------ | :---------- |
| BestEffort | switch | False |  |  |
| Confirm | switch | False |  |  |
| Name | string | True |  |  |
| OtherConfig | string | False |  |  |
| PassThru | switch | False |  |  |
| PoolPatch | Pool_patch | True |  |  |
| Ref | XenRef[Pool_patch] | True |  |  |
| SessionOpaqueRef | string | False |  |  |
| Uuid | guid | True |  |  |
| WhatIf | switch | False |  |  |
### Procedure
None

### Inputs
```
XenAPI.Pool_patch
XenAPI.XenRef`1[[XenAPI.Pool_patch, XenServer, Version=8.2.3.0, Culture=neutral, PublicKeyToken=d247b8b0ac7959e9]]
System.Guid
System.String

```
### Outputs
```
XenAPI.Pool_patch

```
### Links
None

### Examples

Remove-XenPoolPatchProperty [-PoolPatch] <Pool_patch> [-PassThru] [-OtherConfig <string>] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [<CommonParameters>]

Remove-XenPoolPatchProperty [-Ref] <XenRef[Pool_patch]> [-PassThru] [-OtherConfig <string>] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [<CommonParameters>]

Remove-XenPoolPatchProperty [-Uuid] <guid> [-PassThru] [-OtherConfig <string>] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [<CommonParameters>]

Remove-XenPoolPatchProperty [-Name] <string> [-PassThru] [-OtherConfig <string>] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [<CommonParameters>]


## Remove-XenPoolProperty

### Synopsis
None

### Description
None

### Syntax
```
Remove-XenPoolProperty [-Pool] <Pool> [[-PassThru]] [[-OtherConfig] <string>] [[-Tags] <string>] [[-GuiConfig] <string>] [[-HealthCheckConfig] <string>] [[-GuestAgentConfig] <string>] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]] [-Ref] <XenRef[Pool]> [[-PassThru]] [[-OtherConfig] <string>] [[-Tags] <string>] [[-GuiConfig] <string>] [[-HealthCheckConfig] <string>] [[-GuestAgentConfig] <string>] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]] [-Uuid] <guid> [[-PassThru]] [[-OtherConfig] <string>] [[-Tags] <string>] [[-GuiConfig] <string>] [[-HealthCheckConfig] <string>] [[-GuestAgentConfig] <string>] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]]
```
### Parameters
| Name | Type | Required | Default Value | Description |
| :--- | :--- | :------- | :------------ | :---------- |
| BestEffort | switch | False |  |  |
| Confirm | switch | False |  |  |
| GuestAgentConfig | string | False |  |  |
| GuiConfig | string | False |  |  |
| HealthCheckConfig | string | False |  |  |
| OtherConfig | string | False |  |  |
| PassThru | switch | False |  |  |
| Pool | Pool | True |  |  |
| Ref | XenRef[Pool] | True |  |  |
| SessionOpaqueRef | string | False |  |  |
| Tags | string | False |  |  |
| Uuid | guid | True |  |  |
| WhatIf | switch | False |  |  |
### Procedure
None

### Inputs
```
XenAPI.Pool
XenAPI.XenRef`1[[XenAPI.Pool, XenServer, Version=8.2.3.0, Culture=neutral, PublicKeyToken=d247b8b0ac7959e9]]
System.Guid

```
### Outputs
```
XenAPI.Pool
XenAPI.Task

```
### Links
None

### Examples

Remove-XenPoolProperty [-Pool] <Pool> [-PassThru] [-OtherConfig <string>] [-Tags <string>] [-GuiConfig <string>] [-HealthCheckConfig <string>] [-GuestAgentConfig <string>] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [<CommonParameters>]

Remove-XenPoolProperty [-Ref] <XenRef[Pool]> [-PassThru] [-OtherConfig <string>] [-Tags <string>] [-GuiConfig <string>] [-HealthCheckConfig <string>] [-GuestAgentConfig <string>] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [<CommonParameters>]

Remove-XenPoolProperty [-Uuid] <guid> [-PassThru] [-OtherConfig <string>] [-Tags <string>] [-GuiConfig <string>] [-HealthCheckConfig <string>] [-GuestAgentConfig <string>] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [<CommonParameters>]


## Remove-XenPoolUpdate

### Synopsis
None

### Description
None

### Syntax
```
Remove-XenPoolUpdate [-PoolUpdate] <Pool_update> [[-PassThru]] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]] [[-Async]] [-Ref] <XenRef[Pool_update]> [[-PassThru]] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]] [[-Async]] [-Uuid] <guid> [[-PassThru]] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]] [[-Async]] [-Name] <string> [[-PassThru]] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]] [[-Async]]
```
### Parameters
| Name | Type | Required | Default Value | Description |
| :--- | :--- | :------- | :------------ | :---------- |
| Async | switch | False |  |  |
| BestEffort | switch | False |  |  |
| Confirm | switch | False |  |  |
| Name | string | True |  |  |
| PassThru | switch | False |  |  |
| PoolUpdate | Pool_update | True |  |  |
| Ref | XenRef[Pool_update] | True |  |  |
| SessionOpaqueRef | string | False |  |  |
| Uuid | guid | True |  |  |
| WhatIf | switch | False |  |  |
### Procedure
None

### Inputs
```
XenAPI.Pool_update
XenAPI.XenRef`1[[XenAPI.Pool_update, XenServer, Version=8.2.3.0, Culture=neutral, PublicKeyToken=d247b8b0ac7959e9]]
System.Guid
System.String

```
### Outputs
```
XenAPI.Pool_update
XenAPI.Task
System.Void

```
### Links
None

### Examples

Remove-XenPoolUpdate [-PoolUpdate] <Pool_update> [-PassThru] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [-Async] [<CommonParameters>]

Remove-XenPoolUpdate [-Ref] <XenRef[Pool_update]> [-PassThru] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [-Async] [<CommonParameters>]

Remove-XenPoolUpdate [-Uuid] <guid> [-PassThru] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [-Async] [<CommonParameters>]

Remove-XenPoolUpdate [-Name] <string> [-PassThru] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [-Async] [<CommonParameters>]


## Remove-XenPoolUpdateProperty

### Synopsis
None

### Description
None

### Syntax
```
Remove-XenPoolUpdateProperty [-PoolUpdate] <Pool_update> [[-PassThru]] [[-OtherConfig] <string>] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]] [-Ref] <XenRef[Pool_update]> [[-PassThru]] [[-OtherConfig] <string>] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]] [-Uuid] <guid> [[-PassThru]] [[-OtherConfig] <string>] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]] [-Name] <string> [[-PassThru]] [[-OtherConfig] <string>] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]]
```
### Parameters
| Name | Type | Required | Default Value | Description |
| :--- | :--- | :------- | :------------ | :---------- |
| BestEffort | switch | False |  |  |
| Confirm | switch | False |  |  |
| Name | string | True |  |  |
| OtherConfig | string | False |  |  |
| PassThru | switch | False |  |  |
| PoolUpdate | Pool_update | True |  |  |
| Ref | XenRef[Pool_update] | True |  |  |
| SessionOpaqueRef | string | False |  |  |
| Uuid | guid | True |  |  |
| WhatIf | switch | False |  |  |
### Procedure
None

### Inputs
```
XenAPI.Pool_update
XenAPI.XenRef`1[[XenAPI.Pool_update, XenServer, Version=8.2.3.0, Culture=neutral, PublicKeyToken=d247b8b0ac7959e9]]
System.Guid
System.String

```
### Outputs
```
XenAPI.Pool_update

```
### Links
None

### Examples

Remove-XenPoolUpdateProperty [-PoolUpdate] <Pool_update> [-PassThru] [-OtherConfig <string>] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [<CommonParameters>]

Remove-XenPoolUpdateProperty [-Ref] <XenRef[Pool_update]> [-PassThru] [-OtherConfig <string>] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [<CommonParameters>]

Remove-XenPoolUpdateProperty [-Uuid] <guid> [-PassThru] [-OtherConfig <string>] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [<CommonParameters>]

Remove-XenPoolUpdateProperty [-Name] <string> [-PassThru] [-OtherConfig <string>] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [<CommonParameters>]


## Remove-XenPUSBProperty

### Synopsis
None

### Description
None

### Syntax
```
Remove-XenPUSBProperty [-PUSB] <PUSB> [[-PassThru]] [[-OtherConfig] <string>] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]] [-Ref] <XenRef[PUSB]> [[-PassThru]] [[-OtherConfig] <string>] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]] [-Uuid] <guid> [[-PassThru]] [[-OtherConfig] <string>] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]]
```
### Parameters
| Name | Type | Required | Default Value | Description |
| :--- | :--- | :------- | :------------ | :---------- |
| BestEffort | switch | False |  |  |
| Confirm | switch | False |  |  |
| OtherConfig | string | False |  |  |
| PUSB | PUSB | True |  |  |
| PassThru | switch | False |  |  |
| Ref | XenRef[PUSB] | True |  |  |
| SessionOpaqueRef | string | False |  |  |
| Uuid | guid | True |  |  |
| WhatIf | switch | False |  |  |
### Procedure
None

### Inputs
```
XenAPI.PUSB
XenAPI.XenRef`1[[XenAPI.PUSB, XenServer, Version=8.2.3.0, Culture=neutral, PublicKeyToken=d247b8b0ac7959e9]]
System.Guid

```
### Outputs
```
XenAPI.PUSB

```
### Links
None

### Examples

Remove-XenPUSBProperty [-PUSB] <PUSB> [-PassThru] [-OtherConfig <string>] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [<CommonParameters>]

Remove-XenPUSBProperty [-Ref] <XenRef[PUSB]> [-PassThru] [-OtherConfig <string>] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [<CommonParameters>]

Remove-XenPUSBProperty [-Uuid] <guid> [-PassThru] [-OtherConfig <string>] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [<CommonParameters>]


## Remove-XenPVSCacheStorage

### Synopsis
None

### Description
None

### Syntax
```
Remove-XenPVSCacheStorage [-PVSCacheStorage] <PVS_cache_storage> [[-PassThru]] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]] [[-Async]] [-Ref] <XenRef[PVS_cache_storage]> [[-PassThru]] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]] [[-Async]] [-Uuid] <guid> [[-PassThru]] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]] [[-Async]]
```
### Parameters
| Name | Type | Required | Default Value | Description |
| :--- | :--- | :------- | :------------ | :---------- |
| Async | switch | False |  |  |
| BestEffort | switch | False |  |  |
| Confirm | switch | False |  |  |
| PVSCacheStorage | PVS_cache_storage | True |  |  |
| PassThru | switch | False |  |  |
| Ref | XenRef[PVS_cache_storage] | True |  |  |
| SessionOpaqueRef | string | False |  |  |
| Uuid | guid | True |  |  |
| WhatIf | switch | False |  |  |
### Procedure
None

### Inputs
```
XenAPI.PVS_cache_storage
XenAPI.XenRef`1[[XenAPI.PVS_cache_storage, XenServer, Version=8.2.3.0, Culture=neutral, PublicKeyToken=d247b8b0ac7959e9]]
System.Guid

```
### Outputs
```
XenAPI.PVS_cache_storage
XenAPI.Task
System.Void

```
### Links
None

### Examples

Remove-XenPVSCacheStorage [-PVSCacheStorage] <PVS_cache_storage> [-PassThru] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [-Async] [<CommonParameters>]

Remove-XenPVSCacheStorage [-Ref] <XenRef[PVS_cache_storage]> [-PassThru] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [-Async] [<CommonParameters>]

Remove-XenPVSCacheStorage [-Uuid] <guid> [-PassThru] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [-Async] [<CommonParameters>]


## Remove-XenPVSProxy

### Synopsis
None

### Description
None

### Syntax
```
Remove-XenPVSProxy [-PVSProxy] <PVS_proxy> [[-PassThru]] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]] [[-Async]] [-Ref] <XenRef[PVS_proxy]> [[-PassThru]] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]] [[-Async]] [-Uuid] <guid> [[-PassThru]] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]] [[-Async]]
```
### Parameters
| Name | Type | Required | Default Value | Description |
| :--- | :--- | :------- | :------------ | :---------- |
| Async | switch | False |  |  |
| BestEffort | switch | False |  |  |
| Confirm | switch | False |  |  |
| PVSProxy | PVS_proxy | True |  |  |
| PassThru | switch | False |  |  |
| Ref | XenRef[PVS_proxy] | True |  |  |
| SessionOpaqueRef | string | False |  |  |
| Uuid | guid | True |  |  |
| WhatIf | switch | False |  |  |
### Procedure
None

### Inputs
```
XenAPI.PVS_proxy
XenAPI.XenRef`1[[XenAPI.PVS_proxy, XenServer, Version=8.2.3.0, Culture=neutral, PublicKeyToken=d247b8b0ac7959e9]]
System.Guid

```
### Outputs
```
XenAPI.PVS_proxy
XenAPI.Task
System.Void

```
### Links
None

### Examples

Remove-XenPVSProxy [-PVSProxy] <PVS_proxy> [-PassThru] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [-Async] [<CommonParameters>]

Remove-XenPVSProxy [-Ref] <XenRef[PVS_proxy]> [-PassThru] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [-Async] [<CommonParameters>]

Remove-XenPVSProxy [-Uuid] <guid> [-PassThru] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [-Async] [<CommonParameters>]


## Remove-XenSecret

### Synopsis
None

### Description
None

### Syntax
```
Remove-XenSecret [-Secret] <Secret> [[-PassThru]] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]] [[-Async]] [-Ref] <XenRef[Secret]> [[-PassThru]] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]] [[-Async]] [-Uuid] <guid> [[-PassThru]] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]] [[-Async]]
```
### Parameters
| Name | Type | Required | Default Value | Description |
| :--- | :--- | :------- | :------------ | :---------- |
| Async | switch | False |  |  |
| BestEffort | switch | False |  |  |
| Confirm | switch | False |  |  |
| PassThru | switch | False |  |  |
| Ref | XenRef[Secret] | True |  |  |
| Secret | Secret | True |  |  |
| SessionOpaqueRef | string | False |  |  |
| Uuid | guid | True |  |  |
| WhatIf | switch | False |  |  |
### Procedure
None

### Inputs
```
XenAPI.Secret
XenAPI.XenRef`1[[XenAPI.Secret, XenServer, Version=8.2.3.0, Culture=neutral, PublicKeyToken=d247b8b0ac7959e9]]
System.Guid

```
### Outputs
```
XenAPI.Secret
XenAPI.Task
System.Void

```
### Links
None

### Examples

Remove-XenSecret [-Secret] <Secret> [-PassThru] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [-Async] [<CommonParameters>]

Remove-XenSecret [-Ref] <XenRef[Secret]> [-PassThru] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [-Async] [<CommonParameters>]

Remove-XenSecret [-Uuid] <guid> [-PassThru] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [-Async] [<CommonParameters>]


## Remove-XenSecretProperty

### Synopsis
None

### Description
None

### Syntax
```
Remove-XenSecretProperty [-Secret] <Secret> [[-PassThru]] [[-OtherConfig] <string>] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]] [-Ref] <XenRef[Secret]> [[-PassThru]] [[-OtherConfig] <string>] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]] [-Uuid] <guid> [[-PassThru]] [[-OtherConfig] <string>] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]]
```
### Parameters
| Name | Type | Required | Default Value | Description |
| :--- | :--- | :------- | :------------ | :---------- |
| BestEffort | switch | False |  |  |
| Confirm | switch | False |  |  |
| OtherConfig | string | False |  |  |
| PassThru | switch | False |  |  |
| Ref | XenRef[Secret] | True |  |  |
| Secret | Secret | True |  |  |
| SessionOpaqueRef | string | False |  |  |
| Uuid | guid | True |  |  |
| WhatIf | switch | False |  |  |
### Procedure
None

### Inputs
```
XenAPI.Secret
XenAPI.XenRef`1[[XenAPI.Secret, XenServer, Version=8.2.3.0, Culture=neutral, PublicKeyToken=d247b8b0ac7959e9]]
System.Guid

```
### Outputs
```
XenAPI.Secret

```
### Links
None

### Examples

Remove-XenSecretProperty [-Secret] <Secret> [-PassThru] [-OtherConfig <string>] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [<CommonParameters>]

Remove-XenSecretProperty [-Ref] <XenRef[Secret]> [-PassThru] [-OtherConfig <string>] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [<CommonParameters>]

Remove-XenSecretProperty [-Uuid] <guid> [-PassThru] [-OtherConfig <string>] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [<CommonParameters>]


## Remove-XenSMProperty

### Synopsis
None

### Description
None

### Syntax
```
Remove-XenSMProperty [-SM] <SM> [[-PassThru]] [[-OtherConfig] <string>] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]] [-Ref] <XenRef[SM]> [[-PassThru]] [[-OtherConfig] <string>] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]] [-Uuid] <guid> [[-PassThru]] [[-OtherConfig] <string>] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]] [-Name] <string> [[-PassThru]] [[-OtherConfig] <string>] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]]
```
### Parameters
| Name | Type | Required | Default Value | Description |
| :--- | :--- | :------- | :------------ | :---------- |
| BestEffort | switch | False |  |  |
| Confirm | switch | False |  |  |
| Name | string | True |  |  |
| OtherConfig | string | False |  |  |
| PassThru | switch | False |  |  |
| Ref | XenRef[SM] | True |  |  |
| SM | SM | True |  |  |
| SessionOpaqueRef | string | False |  |  |
| Uuid | guid | True |  |  |
| WhatIf | switch | False |  |  |
### Procedure
None

### Inputs
```
XenAPI.SM
XenAPI.XenRef`1[[XenAPI.SM, XenServer, Version=8.2.3.0, Culture=neutral, PublicKeyToken=d247b8b0ac7959e9]]
System.Guid
System.String

```
### Outputs
```
XenAPI.SM

```
### Links
None

### Examples

Remove-XenSMProperty [-SM] <SM> [-PassThru] [-OtherConfig <string>] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [<CommonParameters>]

Remove-XenSMProperty [-Ref] <XenRef[SM]> [-PassThru] [-OtherConfig <string>] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [<CommonParameters>]

Remove-XenSMProperty [-Uuid] <guid> [-PassThru] [-OtherConfig <string>] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [<CommonParameters>]

Remove-XenSMProperty [-Name] <string> [-PassThru] [-OtherConfig <string>] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [<CommonParameters>]


## Remove-XenSR

### Synopsis
None

### Description
None

### Syntax
```
Remove-XenSR [-SR] <SR> [[-PassThru]] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]] [[-Async]] [-Ref] <XenRef[SR]> [[-PassThru]] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]] [[-Async]] [-Uuid] <guid> [[-PassThru]] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]] [[-Async]] [-Name] <string> [[-PassThru]] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]] [[-Async]]
```
### Parameters
| Name | Type | Required | Default Value | Description |
| :--- | :--- | :------- | :------------ | :---------- |
| Async | switch | False |  |  |
| BestEffort | switch | False |  |  |
| Confirm | switch | False |  |  |
| Name | string | True |  |  |
| PassThru | switch | False |  |  |
| Ref | XenRef[SR] | True |  |  |
| SR | SR | True |  |  |
| SessionOpaqueRef | string | False |  |  |
| Uuid | guid | True |  |  |
| WhatIf | switch | False |  |  |
### Procedure
None

### Inputs
```
XenAPI.SR
XenAPI.XenRef`1[[XenAPI.SR, XenServer, Version=8.2.3.0, Culture=neutral, PublicKeyToken=d247b8b0ac7959e9]]
System.Guid
System.String

```
### Outputs
```
XenAPI.SR
XenAPI.Task
System.Void

```
### Links
None

### Examples

Remove-XenSR [-SR] <SR> [-PassThru] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [-Async] [<CommonParameters>]

Remove-XenSR [-Ref] <XenRef[SR]> [-PassThru] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [-Async] [<CommonParameters>]

Remove-XenSR [-Uuid] <guid> [-PassThru] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [-Async] [<CommonParameters>]

Remove-XenSR [-Name] <string> [-PassThru] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [-Async] [<CommonParameters>]


## Remove-XenSRProperty

### Synopsis
None

### Description
None

### Syntax
```
Remove-XenSRProperty [-SR] <SR> [[-PassThru]] [[-OtherConfig] <string>] [[-Tags] <string>] [[-SmConfig] <string>] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]] [-Ref] <XenRef[SR]> [[-PassThru]] [[-OtherConfig] <string>] [[-Tags] <string>] [[-SmConfig] <string>] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]] [-Uuid] <guid> [[-PassThru]] [[-OtherConfig] <string>] [[-Tags] <string>] [[-SmConfig] <string>] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]] [-Name] <string> [[-PassThru]] [[-OtherConfig] <string>] [[-Tags] <string>] [[-SmConfig] <string>] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]]
```
### Parameters
| Name | Type | Required | Default Value | Description |
| :--- | :--- | :------- | :------------ | :---------- |
| BestEffort | switch | False |  |  |
| Confirm | switch | False |  |  |
| Name | string | True |  |  |
| OtherConfig | string | False |  |  |
| PassThru | switch | False |  |  |
| Ref | XenRef[SR] | True |  |  |
| SR | SR | True |  |  |
| SessionOpaqueRef | string | False |  |  |
| SmConfig | string | False |  |  |
| Tags | string | False |  |  |
| Uuid | guid | True |  |  |
| WhatIf | switch | False |  |  |
### Procedure
None

### Inputs
```
XenAPI.SR
XenAPI.XenRef`1[[XenAPI.SR, XenServer, Version=8.2.3.0, Culture=neutral, PublicKeyToken=d247b8b0ac7959e9]]
System.Guid
System.String

```
### Outputs
```
XenAPI.SR

```
### Links
None

### Examples

Remove-XenSRProperty [-SR] <SR> [-PassThru] [-OtherConfig <string>] [-Tags <string>] [-SmConfig <string>] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [<CommonParameters>]

Remove-XenSRProperty [-Ref] <XenRef[SR]> [-PassThru] [-OtherConfig <string>] [-Tags <string>] [-SmConfig <string>] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [<CommonParameters>]

Remove-XenSRProperty [-Uuid] <guid> [-PassThru] [-OtherConfig <string>] [-Tags <string>] [-SmConfig <string>] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [<CommonParameters>]

Remove-XenSRProperty [-Name] <string> [-PassThru] [-OtherConfig <string>] [-Tags <string>] [-SmConfig <string>] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [<CommonParameters>]


## Remove-XenSubject

### Synopsis
None

### Description
None

### Syntax
```
Remove-XenSubject [-Subject] <Subject> [[-PassThru]] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]] [[-Async]] [-Ref] <XenRef[Subject]> [[-PassThru]] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]] [[-Async]] [-Uuid] <guid> [[-PassThru]] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]] [[-Async]]
```
### Parameters
| Name | Type | Required | Default Value | Description |
| :--- | :--- | :------- | :------------ | :---------- |
| Async | switch | False |  |  |
| BestEffort | switch | False |  |  |
| Confirm | switch | False |  |  |
| PassThru | switch | False |  |  |
| Ref | XenRef[Subject] | True |  |  |
| SessionOpaqueRef | string | False |  |  |
| Subject | Subject | True |  |  |
| Uuid | guid | True |  |  |
| WhatIf | switch | False |  |  |
### Procedure
None

### Inputs
```
XenAPI.Subject
XenAPI.XenRef`1[[XenAPI.Subject, XenServer, Version=8.2.3.0, Culture=neutral, PublicKeyToken=d247b8b0ac7959e9]]
System.Guid

```
### Outputs
```
XenAPI.Subject
XenAPI.Task
System.Void

```
### Links
None

### Examples

Remove-XenSubject [-Subject] <Subject> [-PassThru] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [-Async] [<CommonParameters>]

Remove-XenSubject [-Ref] <XenRef[Subject]> [-PassThru] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [-Async] [<CommonParameters>]

Remove-XenSubject [-Uuid] <guid> [-PassThru] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [-Async] [<CommonParameters>]


## Remove-XenSubjectProperty

### Synopsis
None

### Description
None

### Syntax
```
Remove-XenSubjectProperty [-Subject] <Subject> [[-PassThru]] [[-Roles] <XenRef[Role]>] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]] [-Ref] <XenRef[Subject]> [[-PassThru]] [[-Roles] <XenRef[Role]>] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]] [-Uuid] <guid> [[-PassThru]] [[-Roles] <XenRef[Role]>] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]]
```
### Parameters
| Name | Type | Required | Default Value | Description |
| :--- | :--- | :------- | :------------ | :---------- |
| BestEffort | switch | False |  |  |
| Confirm | switch | False |  |  |
| PassThru | switch | False |  |  |
| Ref | XenRef[Subject] | True |  |  |
| Roles | XenRef[Role] | False |  |  |
| SessionOpaqueRef | string | False |  |  |
| Subject | Subject | True |  |  |
| Uuid | guid | True |  |  |
| WhatIf | switch | False |  |  |
### Procedure
None

### Inputs
```
XenAPI.Subject
XenAPI.XenRef`1[[XenAPI.Subject, XenServer, Version=8.2.3.0, Culture=neutral, PublicKeyToken=d247b8b0ac7959e9]]
System.Guid

```
### Outputs
```
XenAPI.Subject

```
### Links
None

### Examples

Remove-XenSubjectProperty [-Subject] <Subject> [-PassThru] [-Roles <XenRef[Role]>] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [<CommonParameters>]

Remove-XenSubjectProperty [-Ref] <XenRef[Subject]> [-PassThru] [-Roles <XenRef[Role]>] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [<CommonParameters>]

Remove-XenSubjectProperty [-Uuid] <guid> [-PassThru] [-Roles <XenRef[Role]>] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [<CommonParameters>]


## Remove-XenTask

### Synopsis
None

### Description
None

### Syntax
```
Remove-XenTask [-Task] <Task> [[-PassThru]] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]] [-Ref] <XenRef[Task]> [[-PassThru]] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]] [-Uuid] <guid> [[-PassThru]] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]] [-Name] <string> [[-PassThru]] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]]
```
### Parameters
| Name | Type | Required | Default Value | Description |
| :--- | :--- | :------- | :------------ | :---------- |
| BestEffort | switch | False |  |  |
| Confirm | switch | False |  |  |
| Name | string | True |  |  |
| PassThru | switch | False |  |  |
| Ref | XenRef[Task] | True |  |  |
| SessionOpaqueRef | string | False |  |  |
| Task | Task | True |  |  |
| Uuid | guid | True |  |  |
| WhatIf | switch | False |  |  |
### Procedure
None

### Inputs
```
XenAPI.Task
XenAPI.XenRef`1[[XenAPI.Task, XenServer, Version=8.2.3.0, Culture=neutral, PublicKeyToken=d247b8b0ac7959e9]]
System.Guid
System.String

```
### Outputs
```
XenAPI.Task
System.Void

```
### Links
None

### Examples

Remove-XenTask [-Task] <Task> [-PassThru] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [<CommonParameters>]

Remove-XenTask [-Ref] <XenRef[Task]> [-PassThru] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [<CommonParameters>]

Remove-XenTask [-Uuid] <guid> [-PassThru] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [<CommonParameters>]

Remove-XenTask [-Name] <string> [-PassThru] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [<CommonParameters>]


## Remove-XenTaskProperty

### Synopsis
None

### Description
None

### Syntax
```
Remove-XenTaskProperty [-Task] <Task> [[-PassThru]] [[-OtherConfig] <string>] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]] [-Ref] <XenRef[Task]> [[-PassThru]] [[-OtherConfig] <string>] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]] [-Uuid] <guid> [[-PassThru]] [[-OtherConfig] <string>] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]] [-Name] <string> [[-PassThru]] [[-OtherConfig] <string>] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]]
```
### Parameters
| Name | Type | Required | Default Value | Description |
| :--- | :--- | :------- | :------------ | :---------- |
| BestEffort | switch | False |  |  |
| Confirm | switch | False |  |  |
| Name | string | True |  |  |
| OtherConfig | string | False |  |  |
| PassThru | switch | False |  |  |
| Ref | XenRef[Task] | True |  |  |
| SessionOpaqueRef | string | False |  |  |
| Task | Task | True |  |  |
| Uuid | guid | True |  |  |
| WhatIf | switch | False |  |  |
### Procedure
None

### Inputs
```
XenAPI.Task
XenAPI.XenRef`1[[XenAPI.Task, XenServer, Version=8.2.3.0, Culture=neutral, PublicKeyToken=d247b8b0ac7959e9]]
System.Guid
System.String

```
### Outputs
```
XenAPI.Task

```
### Links
None

### Examples

Remove-XenTaskProperty [-Task] <Task> [-PassThru] [-OtherConfig <string>] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [<CommonParameters>]

Remove-XenTaskProperty [-Ref] <XenRef[Task]> [-PassThru] [-OtherConfig <string>] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [<CommonParameters>]

Remove-XenTaskProperty [-Uuid] <guid> [-PassThru] [-OtherConfig <string>] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [<CommonParameters>]

Remove-XenTaskProperty [-Name] <string> [-PassThru] [-OtherConfig <string>] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [<CommonParameters>]


## Remove-XenTunnel

### Synopsis
None

### Description
None

### Syntax
```
Remove-XenTunnel [-Tunnel] <Tunnel> [[-PassThru]] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]] [[-Async]] [-Ref] <XenRef[Tunnel]> [[-PassThru]] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]] [[-Async]] [-Uuid] <guid> [[-PassThru]] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]] [[-Async]]
```
### Parameters
| Name | Type | Required | Default Value | Description |
| :--- | :--- | :------- | :------------ | :---------- |
| Async | switch | False |  |  |
| BestEffort | switch | False |  |  |
| Confirm | switch | False |  |  |
| PassThru | switch | False |  |  |
| Ref | XenRef[Tunnel] | True |  |  |
| SessionOpaqueRef | string | False |  |  |
| Tunnel | Tunnel | True |  |  |
| Uuid | guid | True |  |  |
| WhatIf | switch | False |  |  |
### Procedure
None

### Inputs
```
XenAPI.Tunnel
XenAPI.XenRef`1[[XenAPI.Tunnel, XenServer, Version=8.2.3.0, Culture=neutral, PublicKeyToken=d247b8b0ac7959e9]]
System.Guid

```
### Outputs
```
XenAPI.Tunnel
XenAPI.Task
System.Void

```
### Links
None

### Examples

Remove-XenTunnel [-Tunnel] <Tunnel> [-PassThru] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [-Async] [<CommonParameters>]

Remove-XenTunnel [-Ref] <XenRef[Tunnel]> [-PassThru] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [-Async] [<CommonParameters>]

Remove-XenTunnel [-Uuid] <guid> [-PassThru] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [-Async] [<CommonParameters>]


## Remove-XenTunnelProperty

### Synopsis
None

### Description
None

### Syntax
```
Remove-XenTunnelProperty [-Tunnel] <Tunnel> [[-PassThru]] [[-Status] <string>] [[-OtherConfig] <string>] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]] [-Ref] <XenRef[Tunnel]> [[-PassThru]] [[-Status] <string>] [[-OtherConfig] <string>] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]] [-Uuid] <guid> [[-PassThru]] [[-Status] <string>] [[-OtherConfig] <string>] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]]
```
### Parameters
| Name | Type | Required | Default Value | Description |
| :--- | :--- | :------- | :------------ | :---------- |
| BestEffort | switch | False |  |  |
| Confirm | switch | False |  |  |
| OtherConfig | string | False |  |  |
| PassThru | switch | False |  |  |
| Ref | XenRef[Tunnel] | True |  |  |
| SessionOpaqueRef | string | False |  |  |
| Status | string | False |  |  |
| Tunnel | Tunnel | True |  |  |
| Uuid | guid | True |  |  |
| WhatIf | switch | False |  |  |
### Procedure
None

### Inputs
```
XenAPI.Tunnel
XenAPI.XenRef`1[[XenAPI.Tunnel, XenServer, Version=8.2.3.0, Culture=neutral, PublicKeyToken=d247b8b0ac7959e9]]
System.Guid

```
### Outputs
```
XenAPI.Tunnel

```
### Links
None

### Examples

Remove-XenTunnelProperty [-Tunnel] <Tunnel> [-PassThru] [-Status <string>] [-OtherConfig <string>] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [<CommonParameters>]

Remove-XenTunnelProperty [-Ref] <XenRef[Tunnel]> [-PassThru] [-Status <string>] [-OtherConfig <string>] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [<CommonParameters>]

Remove-XenTunnelProperty [-Uuid] <guid> [-PassThru] [-Status <string>] [-OtherConfig <string>] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [<CommonParameters>]


## Remove-XenUSBGroup

### Synopsis
None

### Description
None

### Syntax
```
Remove-XenUSBGroup [-USBGroup] <USB_group> [[-PassThru]] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]] [[-Async]] [-Ref] <XenRef[USB_group]> [[-PassThru]] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]] [[-Async]] [-Uuid] <guid> [[-PassThru]] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]] [[-Async]] [-Name] <string> [[-PassThru]] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]] [[-Async]]
```
### Parameters
| Name | Type | Required | Default Value | Description |
| :--- | :--- | :------- | :------------ | :---------- |
| Async | switch | False |  |  |
| BestEffort | switch | False |  |  |
| Confirm | switch | False |  |  |
| Name | string | True |  |  |
| PassThru | switch | False |  |  |
| Ref | XenRef[USB_group] | True |  |  |
| SessionOpaqueRef | string | False |  |  |
| USBGroup | USB_group | True |  |  |
| Uuid | guid | True |  |  |
| WhatIf | switch | False |  |  |
### Procedure
None

### Inputs
```
XenAPI.USB_group
XenAPI.XenRef`1[[XenAPI.USB_group, XenServer, Version=8.2.3.0, Culture=neutral, PublicKeyToken=d247b8b0ac7959e9]]
System.Guid
System.String

```
### Outputs
```
XenAPI.USB_group
XenAPI.Task
System.Void

```
### Links
None

### Examples

Remove-XenUSBGroup [-USBGroup] <USB_group> [-PassThru] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [-Async] [<CommonParameters>]

Remove-XenUSBGroup [-Ref] <XenRef[USB_group]> [-PassThru] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [-Async] [<CommonParameters>]

Remove-XenUSBGroup [-Uuid] <guid> [-PassThru] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [-Async] [<CommonParameters>]

Remove-XenUSBGroup [-Name] <string> [-PassThru] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [-Async] [<CommonParameters>]


## Remove-XenUSBGroupProperty

### Synopsis
None

### Description
None

### Syntax
```
Remove-XenUSBGroupProperty [-USBGroup] <USB_group> [[-PassThru]] [[-OtherConfig] <string>] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]] [-Ref] <XenRef[USB_group]> [[-PassThru]] [[-OtherConfig] <string>] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]] [-Uuid] <guid> [[-PassThru]] [[-OtherConfig] <string>] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]] [-Name] <string> [[-PassThru]] [[-OtherConfig] <string>] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]]
```
### Parameters
| Name | Type | Required | Default Value | Description |
| :--- | :--- | :------- | :------------ | :---------- |
| BestEffort | switch | False |  |  |
| Confirm | switch | False |  |  |
| Name | string | True |  |  |
| OtherConfig | string | False |  |  |
| PassThru | switch | False |  |  |
| Ref | XenRef[USB_group] | True |  |  |
| SessionOpaqueRef | string | False |  |  |
| USBGroup | USB_group | True |  |  |
| Uuid | guid | True |  |  |
| WhatIf | switch | False |  |  |
### Procedure
None

### Inputs
```
XenAPI.USB_group
XenAPI.XenRef`1[[XenAPI.USB_group, XenServer, Version=8.2.3.0, Culture=neutral, PublicKeyToken=d247b8b0ac7959e9]]
System.Guid
System.String

```
### Outputs
```
XenAPI.USB_group

```
### Links
None

### Examples

Remove-XenUSBGroupProperty [-USBGroup] <USB_group> [-PassThru] [-OtherConfig <string>] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [<CommonParameters>]

Remove-XenUSBGroupProperty [-Ref] <XenRef[USB_group]> [-PassThru] [-OtherConfig <string>] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [<CommonParameters>]

Remove-XenUSBGroupProperty [-Uuid] <guid> [-PassThru] [-OtherConfig <string>] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [<CommonParameters>]

Remove-XenUSBGroupProperty [-Name] <string> [-PassThru] [-OtherConfig <string>] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [<CommonParameters>]


## Remove-XenUser

### Synopsis
None

### Description
None

### Syntax
```
Remove-XenUser [-User] <User> [[-PassThru]] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]] [[-Async]] [-Ref] <XenRef[User]> [[-PassThru]] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]] [[-Async]] [-Uuid] <guid> [[-PassThru]] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]] [[-Async]]
```
### Parameters
| Name | Type | Required | Default Value | Description |
| :--- | :--- | :------- | :------------ | :---------- |
| Async | switch | False |  |  |
| BestEffort | switch | False |  |  |
| Confirm | switch | False |  |  |
| PassThru | switch | False |  |  |
| Ref | XenRef[User] | True |  |  |
| SessionOpaqueRef | string | False |  |  |
| User | User | True |  |  |
| Uuid | guid | True |  |  |
| WhatIf | switch | False |  |  |
### Procedure
None

### Inputs
```
XenAPI.User
XenAPI.XenRef`1[[XenAPI.User, XenServer, Version=8.2.3.0, Culture=neutral, PublicKeyToken=d247b8b0ac7959e9]]
System.Guid

```
### Outputs
```
XenAPI.User
XenAPI.Task
System.Void

```
### Links
None

### Examples

Remove-XenUser [-User] <User> [-PassThru] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [-Async] [<CommonParameters>]

Remove-XenUser [-Ref] <XenRef[User]> [-PassThru] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [-Async] [<CommonParameters>]

Remove-XenUser [-Uuid] <guid> [-PassThru] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [-Async] [<CommonParameters>]


## Remove-XenUserProperty

### Synopsis
None

### Description
None

### Syntax
```
Remove-XenUserProperty [-User] <User> [[-PassThru]] [[-OtherConfig] <string>] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]] [-Ref] <XenRef[User]> [[-PassThru]] [[-OtherConfig] <string>] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]] [-Uuid] <guid> [[-PassThru]] [[-OtherConfig] <string>] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]]
```
### Parameters
| Name | Type | Required | Default Value | Description |
| :--- | :--- | :------- | :------------ | :---------- |
| BestEffort | switch | False |  |  |
| Confirm | switch | False |  |  |
| OtherConfig | string | False |  |  |
| PassThru | switch | False |  |  |
| Ref | XenRef[User] | True |  |  |
| SessionOpaqueRef | string | False |  |  |
| User | User | True |  |  |
| Uuid | guid | True |  |  |
| WhatIf | switch | False |  |  |
### Procedure
None

### Inputs
```
XenAPI.User
XenAPI.XenRef`1[[XenAPI.User, XenServer, Version=8.2.3.0, Culture=neutral, PublicKeyToken=d247b8b0ac7959e9]]
System.Guid

```
### Outputs
```
XenAPI.User

```
### Links
None

### Examples

Remove-XenUserProperty [-User] <User> [-PassThru] [-OtherConfig <string>] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [<CommonParameters>]

Remove-XenUserProperty [-Ref] <XenRef[User]> [-PassThru] [-OtherConfig <string>] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [<CommonParameters>]

Remove-XenUserProperty [-Uuid] <guid> [-PassThru] [-OtherConfig <string>] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [<CommonParameters>]


## Remove-XenVBD

### Synopsis
None

### Description
None

### Syntax
```
Remove-XenVBD [-VBD] <VBD> [[-PassThru]] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]] [[-Async]] [-Ref] <XenRef[VBD]> [[-PassThru]] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]] [[-Async]] [-Uuid] <guid> [[-PassThru]] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]] [[-Async]]
```
### Parameters
| Name | Type | Required | Default Value | Description |
| :--- | :--- | :------- | :------------ | :---------- |
| Async | switch | False |  |  |
| BestEffort | switch | False |  |  |
| Confirm | switch | False |  |  |
| PassThru | switch | False |  |  |
| Ref | XenRef[VBD] | True |  |  |
| SessionOpaqueRef | string | False |  |  |
| Uuid | guid | True |  |  |
| VBD | VBD | True |  |  |
| WhatIf | switch | False |  |  |
### Procedure
None

### Inputs
```
XenAPI.VBD
XenAPI.XenRef`1[[XenAPI.VBD, XenServer, Version=8.2.3.0, Culture=neutral, PublicKeyToken=d247b8b0ac7959e9]]
System.Guid

```
### Outputs
```
XenAPI.VBD
XenAPI.Task
System.Void

```
### Links
None

### Examples

Remove-XenVBD [-VBD] <VBD> [-PassThru] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [-Async] [<CommonParameters>]

Remove-XenVBD [-Ref] <XenRef[VBD]> [-PassThru] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [-Async] [<CommonParameters>]

Remove-XenVBD [-Uuid] <guid> [-PassThru] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [-Async] [<CommonParameters>]


## Remove-XenVBDMetricsProperty

### Synopsis
None

### Description
None

### Syntax
```
Remove-XenVBDMetricsProperty [-VBDMetrics] <VBD_metrics> [[-PassThru]] [[-OtherConfig] <string>] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]] [-Ref] <XenRef[VBD_metrics]> [[-PassThru]] [[-OtherConfig] <string>] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]] [-Uuid] <guid> [[-PassThru]] [[-OtherConfig] <string>] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]]
```
### Parameters
| Name | Type | Required | Default Value | Description |
| :--- | :--- | :------- | :------------ | :---------- |
| BestEffort | switch | False |  |  |
| Confirm | switch | False |  |  |
| OtherConfig | string | False |  |  |
| PassThru | switch | False |  |  |
| Ref | XenRef[VBD_metrics] | True |  |  |
| SessionOpaqueRef | string | False |  |  |
| Uuid | guid | True |  |  |
| VBDMetrics | VBD_metrics | True |  |  |
| WhatIf | switch | False |  |  |
### Procedure
None

### Inputs
```
XenAPI.VBD_metrics
XenAPI.XenRef`1[[XenAPI.VBD_metrics, XenServer, Version=8.2.3.0, Culture=neutral, PublicKeyToken=d247b8b0ac7959e9]]
System.Guid

```
### Outputs
```
XenAPI.VBD_metrics

```
### Links
None

### Examples

Remove-XenVBDMetricsProperty [-VBDMetrics] <VBD_metrics> [-PassThru] [-OtherConfig <string>] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [<CommonParameters>]

Remove-XenVBDMetricsProperty [-Ref] <XenRef[VBD_metrics]> [-PassThru] [-OtherConfig <string>] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [<CommonParameters>]

Remove-XenVBDMetricsProperty [-Uuid] <guid> [-PassThru] [-OtherConfig <string>] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [<CommonParameters>]


## Remove-XenVBDProperty

### Synopsis
None

### Description
None

### Syntax
```
Remove-XenVBDProperty [-VBD] <VBD> [[-PassThru]] [[-OtherConfig] <string>] [[-QosAlgorithmParams] <string>] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]] [-Ref] <XenRef[VBD]> [[-PassThru]] [[-OtherConfig] <string>] [[-QosAlgorithmParams] <string>] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]] [-Uuid] <guid> [[-PassThru]] [[-OtherConfig] <string>] [[-QosAlgorithmParams] <string>] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]]
```
### Parameters
| Name | Type | Required | Default Value | Description |
| :--- | :--- | :------- | :------------ | :---------- |
| BestEffort | switch | False |  |  |
| Confirm | switch | False |  |  |
| OtherConfig | string | False |  |  |
| PassThru | switch | False |  |  |
| QosAlgorithmParams | string | False |  |  |
| Ref | XenRef[VBD] | True |  |  |
| SessionOpaqueRef | string | False |  |  |
| Uuid | guid | True |  |  |
| VBD | VBD | True |  |  |
| WhatIf | switch | False |  |  |
### Procedure
None

### Inputs
```
XenAPI.VBD
XenAPI.XenRef`1[[XenAPI.VBD, XenServer, Version=8.2.3.0, Culture=neutral, PublicKeyToken=d247b8b0ac7959e9]]
System.Guid

```
### Outputs
```
XenAPI.VBD

```
### Links
None

### Examples

Remove-XenVBDProperty [-VBD] <VBD> [-PassThru] [-OtherConfig <string>] [-QosAlgorithmParams <string>] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [<CommonParameters>]

Remove-XenVBDProperty [-Ref] <XenRef[VBD]> [-PassThru] [-OtherConfig <string>] [-QosAlgorithmParams <string>] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [<CommonParameters>]

Remove-XenVBDProperty [-Uuid] <guid> [-PassThru] [-OtherConfig <string>] [-QosAlgorithmParams <string>] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [<CommonParameters>]


## Remove-XenVDI

### Synopsis
None

### Description
None

### Syntax
```
Remove-XenVDI [-VDI] <VDI> [[-PassThru]] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]] [[-Async]] [-Ref] <XenRef[VDI]> [[-PassThru]] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]] [[-Async]] [-Uuid] <guid> [[-PassThru]] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]] [[-Async]] [-Name] <string> [[-PassThru]] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]] [[-Async]]
```
### Parameters
| Name | Type | Required | Default Value | Description |
| :--- | :--- | :------- | :------------ | :---------- |
| Async | switch | False |  |  |
| BestEffort | switch | False |  |  |
| Confirm | switch | False |  |  |
| Name | string | True |  |  |
| PassThru | switch | False |  |  |
| Ref | XenRef[VDI] | True |  |  |
| SessionOpaqueRef | string | False |  |  |
| Uuid | guid | True |  |  |
| VDI | VDI | True |  |  |
| WhatIf | switch | False |  |  |
### Procedure
None

### Inputs
```
XenAPI.VDI
XenAPI.XenRef`1[[XenAPI.VDI, XenServer, Version=8.2.3.0, Culture=neutral, PublicKeyToken=d247b8b0ac7959e9]]
System.Guid
System.String

```
### Outputs
```
XenAPI.VDI
XenAPI.Task
System.Void

```
### Links
None

### Examples

Remove-XenVDI [-VDI] <VDI> [-PassThru] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [-Async] [<CommonParameters>]

Remove-XenVDI [-Ref] <XenRef[VDI]> [-PassThru] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [-Async] [<CommonParameters>]

Remove-XenVDI [-Uuid] <guid> [-PassThru] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [-Async] [<CommonParameters>]

Remove-XenVDI [-Name] <string> [-PassThru] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [-Async] [<CommonParameters>]


## Remove-XenVDIProperty

### Synopsis
None

### Description
None

### Syntax
```
Remove-XenVDIProperty [-VDI] <VDI> [[-PassThru]] [[-OtherConfig] <string>] [[-XenstoreData] <string>] [[-SmConfig] <string>] [[-Tags] <string>] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]] [-Ref] <XenRef[VDI]> [[-PassThru]] [[-OtherConfig] <string>] [[-XenstoreData] <string>] [[-SmConfig] <string>] [[-Tags] <string>] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]] [-Uuid] <guid> [[-PassThru]] [[-OtherConfig] <string>] [[-XenstoreData] <string>] [[-SmConfig] <string>] [[-Tags] <string>] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]] [-Name] <string> [[-PassThru]] [[-OtherConfig] <string>] [[-XenstoreData] <string>] [[-SmConfig] <string>] [[-Tags] <string>] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]]
```
### Parameters
| Name | Type | Required | Default Value | Description |
| :--- | :--- | :------- | :------------ | :---------- |
| BestEffort | switch | False |  |  |
| Confirm | switch | False |  |  |
| Name | string | True |  |  |
| OtherConfig | string | False |  |  |
| PassThru | switch | False |  |  |
| Ref | XenRef[VDI] | True |  |  |
| SessionOpaqueRef | string | False |  |  |
| SmConfig | string | False |  |  |
| Tags | string | False |  |  |
| Uuid | guid | True |  |  |
| VDI | VDI | True |  |  |
| WhatIf | switch | False |  |  |
| XenstoreData | string | False |  |  |
### Procedure
None

### Inputs
```
XenAPI.VDI
XenAPI.XenRef`1[[XenAPI.VDI, XenServer, Version=8.2.3.0, Culture=neutral, PublicKeyToken=d247b8b0ac7959e9]]
System.Guid
System.String

```
### Outputs
```
XenAPI.VDI

```
### Links
None

### Examples

Remove-XenVDIProperty [-VDI] <VDI> [-PassThru] [-OtherConfig <string>] [-XenstoreData <string>] [-SmConfig <string>] [-Tags <string>] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [<CommonParameters>]

Remove-XenVDIProperty [-Ref] <XenRef[VDI]> [-PassThru] [-OtherConfig <string>] [-XenstoreData <string>] [-SmConfig <string>] [-Tags <string>] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [<CommonParameters>]

Remove-XenVDIProperty [-Uuid] <guid> [-PassThru] [-OtherConfig <string>] [-XenstoreData <string>] [-SmConfig <string>] [-Tags <string>] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [<CommonParameters>]

Remove-XenVDIProperty [-Name] <string> [-PassThru] [-OtherConfig <string>] [-XenstoreData <string>] [-SmConfig <string>] [-Tags <string>] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [<CommonParameters>]


## Remove-XenVGPU

### Synopsis
None

### Description
None

### Syntax
```
Remove-XenVGPU [-VGPU] <VGPU> [[-PassThru]] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]] [[-Async]] [-Ref] <XenRef[VGPU]> [[-PassThru]] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]] [[-Async]] [-Uuid] <guid> [[-PassThru]] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]] [[-Async]]
```
### Parameters
| Name | Type | Required | Default Value | Description |
| :--- | :--- | :------- | :------------ | :---------- |
| Async | switch | False |  |  |
| BestEffort | switch | False |  |  |
| Confirm | switch | False |  |  |
| PassThru | switch | False |  |  |
| Ref | XenRef[VGPU] | True |  |  |
| SessionOpaqueRef | string | False |  |  |
| Uuid | guid | True |  |  |
| VGPU | VGPU | True |  |  |
| WhatIf | switch | False |  |  |
### Procedure
None

### Inputs
```
XenAPI.VGPU
XenAPI.XenRef`1[[XenAPI.VGPU, XenServer, Version=8.2.3.0, Culture=neutral, PublicKeyToken=d247b8b0ac7959e9]]
System.Guid

```
### Outputs
```
XenAPI.VGPU
XenAPI.Task
System.Void

```
### Links
None

### Examples

Remove-XenVGPU [-VGPU] <VGPU> [-PassThru] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [-Async] [<CommonParameters>]

Remove-XenVGPU [-Ref] <XenRef[VGPU]> [-PassThru] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [-Async] [<CommonParameters>]

Remove-XenVGPU [-Uuid] <guid> [-PassThru] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [-Async] [<CommonParameters>]


## Remove-XenVGPUProperty

### Synopsis
None

### Description
None

### Syntax
```
Remove-XenVGPUProperty [-VGPU] <VGPU> [[-PassThru]] [[-OtherConfig] <string>] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]] [-Ref] <XenRef[VGPU]> [[-PassThru]] [[-OtherConfig] <string>] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]] [-Uuid] <guid> [[-PassThru]] [[-OtherConfig] <string>] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]]
```
### Parameters
| Name | Type | Required | Default Value | Description |
| :--- | :--- | :------- | :------------ | :---------- |
| BestEffort | switch | False |  |  |
| Confirm | switch | False |  |  |
| OtherConfig | string | False |  |  |
| PassThru | switch | False |  |  |
| Ref | XenRef[VGPU] | True |  |  |
| SessionOpaqueRef | string | False |  |  |
| Uuid | guid | True |  |  |
| VGPU | VGPU | True |  |  |
| WhatIf | switch | False |  |  |
### Procedure
None

### Inputs
```
XenAPI.VGPU
XenAPI.XenRef`1[[XenAPI.VGPU, XenServer, Version=8.2.3.0, Culture=neutral, PublicKeyToken=d247b8b0ac7959e9]]
System.Guid

```
### Outputs
```
XenAPI.VGPU

```
### Links
None

### Examples

Remove-XenVGPUProperty [-VGPU] <VGPU> [-PassThru] [-OtherConfig <string>] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [<CommonParameters>]

Remove-XenVGPUProperty [-Ref] <XenRef[VGPU]> [-PassThru] [-OtherConfig <string>] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [<CommonParameters>]

Remove-XenVGPUProperty [-Uuid] <guid> [-PassThru] [-OtherConfig <string>] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [<CommonParameters>]


## Remove-XenVIF

### Synopsis
None

### Description
None

### Syntax
```
Remove-XenVIF [-VIF] <VIF> [[-PassThru]] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]] [[-Async]] [-Ref] <XenRef[VIF]> [[-PassThru]] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]] [[-Async]] [-Uuid] <guid> [[-PassThru]] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]] [[-Async]]
```
### Parameters
| Name | Type | Required | Default Value | Description |
| :--- | :--- | :------- | :------------ | :---------- |
| Async | switch | False |  |  |
| BestEffort | switch | False |  |  |
| Confirm | switch | False |  |  |
| PassThru | switch | False |  |  |
| Ref | XenRef[VIF] | True |  |  |
| SessionOpaqueRef | string | False |  |  |
| Uuid | guid | True |  |  |
| VIF | VIF | True |  |  |
| WhatIf | switch | False |  |  |
### Procedure
None

### Inputs
```
XenAPI.VIF
XenAPI.XenRef`1[[XenAPI.VIF, XenServer, Version=8.2.3.0, Culture=neutral, PublicKeyToken=d247b8b0ac7959e9]]
System.Guid

```
### Outputs
```
XenAPI.VIF
XenAPI.Task
System.Void

```
### Links
None

### Examples

Remove-XenVIF [-VIF] <VIF> [-PassThru] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [-Async] [<CommonParameters>]

Remove-XenVIF [-Ref] <XenRef[VIF]> [-PassThru] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [-Async] [<CommonParameters>]

Remove-XenVIF [-Uuid] <guid> [-PassThru] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [-Async] [<CommonParameters>]


## Remove-XenVIFMetricsProperty

### Synopsis
None

### Description
None

### Syntax
```
Remove-XenVIFMetricsProperty [-VIFMetrics] <VIF_metrics> [[-PassThru]] [[-OtherConfig] <string>] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]] [-Ref] <XenRef[VIF_metrics]> [[-PassThru]] [[-OtherConfig] <string>] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]] [-Uuid] <guid> [[-PassThru]] [[-OtherConfig] <string>] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]]
```
### Parameters
| Name | Type | Required | Default Value | Description |
| :--- | :--- | :------- | :------------ | :---------- |
| BestEffort | switch | False |  |  |
| Confirm | switch | False |  |  |
| OtherConfig | string | False |  |  |
| PassThru | switch | False |  |  |
| Ref | XenRef[VIF_metrics] | True |  |  |
| SessionOpaqueRef | string | False |  |  |
| Uuid | guid | True |  |  |
| VIFMetrics | VIF_metrics | True |  |  |
| WhatIf | switch | False |  |  |
### Procedure
None

### Inputs
```
XenAPI.VIF_metrics
XenAPI.XenRef`1[[XenAPI.VIF_metrics, XenServer, Version=8.2.3.0, Culture=neutral, PublicKeyToken=d247b8b0ac7959e9]]
System.Guid

```
### Outputs
```
XenAPI.VIF_metrics

```
### Links
None

### Examples

Remove-XenVIFMetricsProperty [-VIFMetrics] <VIF_metrics> [-PassThru] [-OtherConfig <string>] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [<CommonParameters>]

Remove-XenVIFMetricsProperty [-Ref] <XenRef[VIF_metrics]> [-PassThru] [-OtherConfig <string>] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [<CommonParameters>]

Remove-XenVIFMetricsProperty [-Uuid] <guid> [-PassThru] [-OtherConfig <string>] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [<CommonParameters>]


## Remove-XenVIFProperty

### Synopsis
None

### Description
None

### Syntax
```
Remove-XenVIFProperty [-VIF] <VIF> [[-PassThru]] [[-OtherConfig] <string>] [[-QosAlgorithmParams] <string>] [[-Ipv4Allowed] <string>] [[-Ipv6Allowed] <string>] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]] [-Ref] <XenRef[VIF]> [[-PassThru]] [[-OtherConfig] <string>] [[-QosAlgorithmParams] <string>] [[-Ipv4Allowed] <string>] [[-Ipv6Allowed] <string>] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]] [-Uuid] <guid> [[-PassThru]] [[-OtherConfig] <string>] [[-QosAlgorithmParams] <string>] [[-Ipv4Allowed] <string>] [[-Ipv6Allowed] <string>] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]]
```
### Parameters
| Name | Type | Required | Default Value | Description |
| :--- | :--- | :------- | :------------ | :---------- |
| BestEffort | switch | False |  |  |
| Confirm | switch | False |  |  |
| Ipv4Allowed | string | False |  |  |
| Ipv6Allowed | string | False |  |  |
| OtherConfig | string | False |  |  |
| PassThru | switch | False |  |  |
| QosAlgorithmParams | string | False |  |  |
| Ref | XenRef[VIF] | True |  |  |
| SessionOpaqueRef | string | False |  |  |
| Uuid | guid | True |  |  |
| VIF | VIF | True |  |  |
| WhatIf | switch | False |  |  |
### Procedure
None

### Inputs
```
XenAPI.VIF
XenAPI.XenRef`1[[XenAPI.VIF, XenServer, Version=8.2.3.0, Culture=neutral, PublicKeyToken=d247b8b0ac7959e9]]
System.Guid

```
### Outputs
```
XenAPI.VIF
XenAPI.Task

```
### Links
None

### Examples

Remove-XenVIFProperty [-VIF] <VIF> [-PassThru] [-OtherConfig <string>] [-QosAlgorithmParams <string>] [-Ipv4Allowed <string>] [-Ipv6Allowed <string>] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [<CommonParameters>]

Remove-XenVIFProperty [-Ref] <XenRef[VIF]> [-PassThru] [-OtherConfig <string>] [-QosAlgorithmParams <string>] [-Ipv4Allowed <string>] [-Ipv6Allowed <string>] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [<CommonParameters>]

Remove-XenVIFProperty [-Uuid] <guid> [-PassThru] [-OtherConfig <string>] [-QosAlgorithmParams <string>] [-Ipv4Allowed <string>] [-Ipv6Allowed <string>] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [<CommonParameters>]


## Remove-XenVLAN

### Synopsis
None

### Description
None

### Syntax
```
Remove-XenVLAN [-VLAN] <VLAN> [[-PassThru]] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]] [[-Async]] [-Ref] <XenRef[VLAN]> [[-PassThru]] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]] [[-Async]] [-Uuid] <guid> [[-PassThru]] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]] [[-Async]]
```
### Parameters
| Name | Type | Required | Default Value | Description |
| :--- | :--- | :------- | :------------ | :---------- |
| Async | switch | False |  |  |
| BestEffort | switch | False |  |  |
| Confirm | switch | False |  |  |
| PassThru | switch | False |  |  |
| Ref | XenRef[VLAN] | True |  |  |
| SessionOpaqueRef | string | False |  |  |
| Uuid | guid | True |  |  |
| VLAN | VLAN | True |  |  |
| WhatIf | switch | False |  |  |
### Procedure
None

### Inputs
```
XenAPI.VLAN
XenAPI.XenRef`1[[XenAPI.VLAN, XenServer, Version=8.2.3.0, Culture=neutral, PublicKeyToken=d247b8b0ac7959e9]]
System.Guid

```
### Outputs
```
XenAPI.VLAN
XenAPI.Task
System.Void

```
### Links
None

### Examples

Remove-XenVLAN [-VLAN] <VLAN> [-PassThru] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [-Async] [<CommonParameters>]

Remove-XenVLAN [-Ref] <XenRef[VLAN]> [-PassThru] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [-Async] [<CommonParameters>]

Remove-XenVLAN [-Uuid] <guid> [-PassThru] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [-Async] [<CommonParameters>]


## Remove-XenVLANProperty

### Synopsis
None

### Description
None

### Syntax
```
Remove-XenVLANProperty [-VLAN] <VLAN> [[-PassThru]] [[-OtherConfig] <string>] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]] [-Ref] <XenRef[VLAN]> [[-PassThru]] [[-OtherConfig] <string>] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]] [-Uuid] <guid> [[-PassThru]] [[-OtherConfig] <string>] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]]
```
### Parameters
| Name | Type | Required | Default Value | Description |
| :--- | :--- | :------- | :------------ | :---------- |
| BestEffort | switch | False |  |  |
| Confirm | switch | False |  |  |
| OtherConfig | string | False |  |  |
| PassThru | switch | False |  |  |
| Ref | XenRef[VLAN] | True |  |  |
| SessionOpaqueRef | string | False |  |  |
| Uuid | guid | True |  |  |
| VLAN | VLAN | True |  |  |
| WhatIf | switch | False |  |  |
### Procedure
None

### Inputs
```
XenAPI.VLAN
XenAPI.XenRef`1[[XenAPI.VLAN, XenServer, Version=8.2.3.0, Culture=neutral, PublicKeyToken=d247b8b0ac7959e9]]
System.Guid

```
### Outputs
```
XenAPI.VLAN

```
### Links
None

### Examples

Remove-XenVLANProperty [-VLAN] <VLAN> [-PassThru] [-OtherConfig <string>] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [<CommonParameters>]

Remove-XenVLANProperty [-Ref] <XenRef[VLAN]> [-PassThru] [-OtherConfig <string>] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [<CommonParameters>]

Remove-XenVLANProperty [-Uuid] <guid> [-PassThru] [-OtherConfig <string>] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [<CommonParameters>]


## Remove-XenVM

### Synopsis
None

### Description
None

### Syntax
```
Remove-XenVM [-VM] <VM> [[-PassThru]] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]] [[-Async]] [-Ref] <XenRef[VM]> [[-PassThru]] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]] [[-Async]] [-Uuid] <guid> [[-PassThru]] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]] [[-Async]] [-Name] <string> [[-PassThru]] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]] [[-Async]]
```
### Parameters
| Name | Type | Required | Default Value | Description |
| :--- | :--- | :------- | :------------ | :---------- |
| Async | switch | False |  |  |
| BestEffort | switch | False |  |  |
| Confirm | switch | False |  |  |
| Name | string | True |  |  |
| PassThru | switch | False |  |  |
| Ref | XenRef[VM] | True |  |  |
| SessionOpaqueRef | string | False |  |  |
| Uuid | guid | True |  |  |
| VM | VM | True |  |  |
| WhatIf | switch | False |  |  |
### Procedure
None

### Inputs
```
XenAPI.VM
XenAPI.XenRef`1[[XenAPI.VM, XenServer, Version=8.2.3.0, Culture=neutral, PublicKeyToken=d247b8b0ac7959e9]]
System.Guid
System.String

```
### Outputs
```
XenAPI.VM
XenAPI.Task
System.Void

```
### Links
None

### Examples

Remove-XenVM [-VM] <VM> [-PassThru] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [-Async] [<CommonParameters>]

Remove-XenVM [-Ref] <XenRef[VM]> [-PassThru] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [-Async] [<CommonParameters>]

Remove-XenVM [-Uuid] <guid> [-PassThru] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [-Async] [<CommonParameters>]

Remove-XenVM [-Name] <string> [-PassThru] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [-Async] [<CommonParameters>]


## Remove-XenVMAppliance

### Synopsis
None

### Description
None

### Syntax
```
Remove-XenVMAppliance [-VMAppliance] <VM_appliance> [[-PassThru]] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]] [[-Async]] [-Ref] <XenRef[VM_appliance]> [[-PassThru]] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]] [[-Async]] [-Uuid] <guid> [[-PassThru]] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]] [[-Async]] [-Name] <string> [[-PassThru]] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]] [[-Async]]
```
### Parameters
| Name | Type | Required | Default Value | Description |
| :--- | :--- | :------- | :------------ | :---------- |
| Async | switch | False |  |  |
| BestEffort | switch | False |  |  |
| Confirm | switch | False |  |  |
| Name | string | True |  |  |
| PassThru | switch | False |  |  |
| Ref | XenRef[VM_appliance] | True |  |  |
| SessionOpaqueRef | string | False |  |  |
| Uuid | guid | True |  |  |
| VMAppliance | VM_appliance | True |  |  |
| WhatIf | switch | False |  |  |
### Procedure
None

### Inputs
```
XenAPI.VM_appliance
XenAPI.XenRef`1[[XenAPI.VM_appliance, XenServer, Version=8.2.3.0, Culture=neutral, PublicKeyToken=d247b8b0ac7959e9]]
System.Guid
System.String

```
### Outputs
```
XenAPI.VM_appliance
XenAPI.Task
System.Void

```
### Links
None

### Examples

Remove-XenVMAppliance [-VMAppliance] <VM_appliance> [-PassThru] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [-Async] [<CommonParameters>]

Remove-XenVMAppliance [-Ref] <XenRef[VM_appliance]> [-PassThru] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [-Async] [<CommonParameters>]

Remove-XenVMAppliance [-Uuid] <guid> [-PassThru] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [-Async] [<CommonParameters>]

Remove-XenVMAppliance [-Name] <string> [-PassThru] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [-Async] [<CommonParameters>]


## Remove-XenVMGuestMetricsProperty

### Synopsis
None

### Description
None

### Syntax
```
Remove-XenVMGuestMetricsProperty [-VMGuestMetrics] <VM_guest_metrics> [[-PassThru]] [[-OtherConfig] <string>] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]] [-Ref] <XenRef[VM_guest_metrics]> [[-PassThru]] [[-OtherConfig] <string>] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]] [-Uuid] <guid> [[-PassThru]] [[-OtherConfig] <string>] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]]
```
### Parameters
| Name | Type | Required | Default Value | Description |
| :--- | :--- | :------- | :------------ | :---------- |
| BestEffort | switch | False |  |  |
| Confirm | switch | False |  |  |
| OtherConfig | string | False |  |  |
| PassThru | switch | False |  |  |
| Ref | XenRef[VM_guest_metrics] | True |  |  |
| SessionOpaqueRef | string | False |  |  |
| Uuid | guid | True |  |  |
| VMGuestMetrics | VM_guest_metrics | True |  |  |
| WhatIf | switch | False |  |  |
### Procedure
None

### Inputs
```
XenAPI.VM_guest_metrics
XenAPI.XenRef`1[[XenAPI.VM_guest_metrics, XenServer, Version=8.2.3.0, Culture=neutral, PublicKeyToken=d247b8b0ac7959e9]]
System.Guid

```
### Outputs
```
XenAPI.VM_guest_metrics

```
### Links
None

### Examples

Remove-XenVMGuestMetricsProperty [-VMGuestMetrics] <VM_guest_metrics> [-PassThru] [-OtherConfig <string>] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [<CommonParameters>]

Remove-XenVMGuestMetricsProperty [-Ref] <XenRef[VM_guest_metrics]> [-PassThru] [-OtherConfig <string>] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [<CommonParameters>]

Remove-XenVMGuestMetricsProperty [-Uuid] <guid> [-PassThru] [-OtherConfig <string>] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [<CommonParameters>]


## Remove-XenVMMetricsProperty

### Synopsis
None

### Description
None

### Syntax
```
Remove-XenVMMetricsProperty [-VMMetrics] <VM_metrics> [[-PassThru]] [[-OtherConfig] <string>] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]] [-Ref] <XenRef[VM_metrics]> [[-PassThru]] [[-OtherConfig] <string>] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]] [-Uuid] <guid> [[-PassThru]] [[-OtherConfig] <string>] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]]
```
### Parameters
| Name | Type | Required | Default Value | Description |
| :--- | :--- | :------- | :------------ | :---------- |
| BestEffort | switch | False |  |  |
| Confirm | switch | False |  |  |
| OtherConfig | string | False |  |  |
| PassThru | switch | False |  |  |
| Ref | XenRef[VM_metrics] | True |  |  |
| SessionOpaqueRef | string | False |  |  |
| Uuid | guid | True |  |  |
| VMMetrics | VM_metrics | True |  |  |
| WhatIf | switch | False |  |  |
### Procedure
None

### Inputs
```
XenAPI.VM_metrics
XenAPI.XenRef`1[[XenAPI.VM_metrics, XenServer, Version=8.2.3.0, Culture=neutral, PublicKeyToken=d247b8b0ac7959e9]]
System.Guid

```
### Outputs
```
XenAPI.VM_metrics

```
### Links
None

### Examples

Remove-XenVMMetricsProperty [-VMMetrics] <VM_metrics> [-PassThru] [-OtherConfig <string>] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [<CommonParameters>]

Remove-XenVMMetricsProperty [-Ref] <XenRef[VM_metrics]> [-PassThru] [-OtherConfig <string>] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [<CommonParameters>]

Remove-XenVMMetricsProperty [-Uuid] <guid> [-PassThru] [-OtherConfig <string>] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [<CommonParameters>]


## Remove-XenVMPP

### Synopsis
None

### Description
None

### Syntax
```
Remove-XenVMPP [-VMPP] <VMPP> [[-PassThru]] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]] [[-Async]] [-Ref] <XenRef[VMPP]> [[-PassThru]] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]] [[-Async]] [-Uuid] <guid> [[-PassThru]] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]] [[-Async]] [-Name] <string> [[-PassThru]] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]] [[-Async]]
```
### Parameters
| Name | Type | Required | Default Value | Description |
| :--- | :--- | :------- | :------------ | :---------- |
| Async | switch | False |  |  |
| BestEffort | switch | False |  |  |
| Confirm | switch | False |  |  |
| Name | string | True |  |  |
| PassThru | switch | False |  |  |
| Ref | XenRef[VMPP] | True |  |  |
| SessionOpaqueRef | string | False |  |  |
| Uuid | guid | True |  |  |
| VMPP | VMPP | True |  |  |
| WhatIf | switch | False |  |  |
### Procedure
None

### Inputs
```
XenAPI.VMPP
XenAPI.XenRef`1[[XenAPI.VMPP, XenServer, Version=8.2.3.0, Culture=neutral, PublicKeyToken=d247b8b0ac7959e9]]
System.Guid
System.String

```
### Outputs
```
XenAPI.VMPP
XenAPI.Task
System.Void

```
### Links
None

### Examples

Remove-XenVMPP [-VMPP] <VMPP> [-PassThru] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [-Async] [<CommonParameters>]

Remove-XenVMPP [-Ref] <XenRef[VMPP]> [-PassThru] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [-Async] [<CommonParameters>]

Remove-XenVMPP [-Uuid] <guid> [-PassThru] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [-Async] [<CommonParameters>]

Remove-XenVMPP [-Name] <string> [-PassThru] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [-Async] [<CommonParameters>]


## Remove-XenVMPPProperty

### Synopsis
None

### Description
None

### Syntax
```
Remove-XenVMPPProperty [-VMPP] <VMPP> [[-PassThru]] [[-BackupSchedule] <string>] [[-ArchiveTargetConfig] <string>] [[-ArchiveSchedule] <string>] [[-AlarmConfig] <string>] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]] [-Ref] <XenRef[VMPP]> [[-PassThru]] [[-BackupSchedule] <string>] [[-ArchiveTargetConfig] <string>] [[-ArchiveSchedule] <string>] [[-AlarmConfig] <string>] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]] [-Uuid] <guid> [[-PassThru]] [[-BackupSchedule] <string>] [[-ArchiveTargetConfig] <string>] [[-ArchiveSchedule] <string>] [[-AlarmConfig] <string>] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]] [-Name] <string> [[-PassThru]] [[-BackupSchedule] <string>] [[-ArchiveTargetConfig] <string>] [[-ArchiveSchedule] <string>] [[-AlarmConfig] <string>] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]]
```
### Parameters
| Name | Type | Required | Default Value | Description |
| :--- | :--- | :------- | :------------ | :---------- |
| AlarmConfig | string | False |  |  |
| ArchiveSchedule | string | False |  |  |
| ArchiveTargetConfig | string | False |  |  |
| BackupSchedule | string | False |  |  |
| BestEffort | switch | False |  |  |
| Confirm | switch | False |  |  |
| Name | string | True |  |  |
| PassThru | switch | False |  |  |
| Ref | XenRef[VMPP] | True |  |  |
| SessionOpaqueRef | string | False |  |  |
| Uuid | guid | True |  |  |
| VMPP | VMPP | True |  |  |
| WhatIf | switch | False |  |  |
### Procedure
None

### Inputs
```
XenAPI.VMPP
XenAPI.XenRef`1[[XenAPI.VMPP, XenServer, Version=8.2.3.0, Culture=neutral, PublicKeyToken=d247b8b0ac7959e9]]
System.Guid
System.String

```
### Outputs
```
XenAPI.VMPP

```
### Links
None

### Examples

Remove-XenVMPPProperty [-VMPP] <VMPP> [-PassThru] [-BackupSchedule <string>] [-ArchiveTargetConfig <string>] [-ArchiveSchedule <string>] [-AlarmConfig <string>] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [<CommonParameters>]

Remove-XenVMPPProperty [-Ref] <XenRef[VMPP]> [-PassThru] [-BackupSchedule <string>] [-ArchiveTargetConfig <string>] [-ArchiveSchedule <string>] [-AlarmConfig <string>] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [<CommonParameters>]

Remove-XenVMPPProperty [-Uuid] <guid> [-PassThru] [-BackupSchedule <string>] [-ArchiveTargetConfig <string>] [-ArchiveSchedule <string>] [-AlarmConfig <string>] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [<CommonParameters>]

Remove-XenVMPPProperty [-Name] <string> [-PassThru] [-BackupSchedule <string>] [-ArchiveTargetConfig <string>] [-ArchiveSchedule <string>] [-AlarmConfig <string>] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [<CommonParameters>]


## Remove-XenVMProperty

### Synopsis
None

### Description
None

### Syntax
```
Remove-XenVMProperty [-VM] <VM> [[-PassThru]] [[-VCPUsParams] <string>] [[-HVMBootParams] <string>] [[-Platform] <string>] [[-OtherConfig] <string>] [[-XenstoreData] <string>] [[-Tags] <string>] [[-BlockedOperations] <vm_operations>] [[-NVRAM] <string>] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]] [-Ref] <XenRef[VM]> [[-PassThru]] [[-VCPUsParams] <string>] [[-HVMBootParams] <string>] [[-Platform] <string>] [[-OtherConfig] <string>] [[-XenstoreData] <string>] [[-Tags] <string>] [[-BlockedOperations] <vm_operations>] [[-NVRAM] <string>] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]] [-Uuid] <guid> [[-PassThru]] [[-VCPUsParams] <string>] [[-HVMBootParams] <string>] [[-Platform] <string>] [[-OtherConfig] <string>] [[-XenstoreData] <string>] [[-Tags] <string>] [[-BlockedOperations] <vm_operations>] [[-NVRAM] <string>] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]] [-Name] <string> [[-PassThru]] [[-VCPUsParams] <string>] [[-HVMBootParams] <string>] [[-Platform] <string>] [[-OtherConfig] <string>] [[-XenstoreData] <string>] [[-Tags] <string>] [[-BlockedOperations] <vm_operations>] [[-NVRAM] <string>] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]]
```
### Parameters
| Name | Type | Required | Default Value | Description |
| :--- | :--- | :------- | :------------ | :---------- |
| BestEffort | switch | False |  |  |
| BlockedOperations | vm_operations | False |  |  |
| Confirm | switch | False |  |  |
| HVMBootParams | string | False |  |  |
| NVRAM | string | False |  |  |
| Name | string | True |  |  |
| OtherConfig | string | False |  |  |
| PassThru | switch | False |  |  |
| Platform | string | False |  |  |
| Ref | XenRef[VM] | True |  |  |
| SessionOpaqueRef | string | False |  |  |
| Tags | string | False |  |  |
| Uuid | guid | True |  |  |
| VCPUsParams | string | False |  |  |
| VM | VM | True |  |  |
| WhatIf | switch | False |  |  |
| XenstoreData | string | False |  |  |
### Procedure
None

### Inputs
```
XenAPI.VM
XenAPI.XenRef`1[[XenAPI.VM, XenServer, Version=8.2.3.0, Culture=neutral, PublicKeyToken=d247b8b0ac7959e9]]
System.Guid
System.String

```
### Outputs
```
XenAPI.VM

```
### Links
None

### Examples

Remove-XenVMProperty [-VM] <VM> [-PassThru] [-VCPUsParams <string>] [-HVMBootParams <string>] [-Platform <string>] [-OtherConfig <string>] [-XenstoreData <string>] [-Tags <string>] [-BlockedOperations <vm_operations>] [-NVRAM <string>] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [<CommonParameters>]

Remove-XenVMProperty [-Ref] <XenRef[VM]> [-PassThru] [-VCPUsParams <string>] [-HVMBootParams <string>] [-Platform <string>] [-OtherConfig <string>] [-XenstoreData <string>] [-Tags <string>] [-BlockedOperations <vm_operations>] [-NVRAM <string>] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [<CommonParameters>]

Remove-XenVMProperty [-Uuid] <guid> [-PassThru] [-VCPUsParams <string>] [-HVMBootParams <string>] [-Platform <string>] [-OtherConfig <string>] [-XenstoreData <string>] [-Tags <string>] [-BlockedOperations <vm_operations>] [-NVRAM <string>] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [<CommonParameters>]

Remove-XenVMProperty [-Name] <string> [-PassThru] [-VCPUsParams <string>] [-HVMBootParams <string>] [-Platform <string>] [-OtherConfig <string>] [-XenstoreData <string>] [-Tags <string>] [-BlockedOperations <vm_operations>] [-NVRAM <string>] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [<CommonParameters>]


## Remove-XenVMSS

### Synopsis
None

### Description
None

### Syntax
```
Remove-XenVMSS [-VMSS] <VMSS> [[-PassThru]] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]] [[-Async]] [-Ref] <XenRef[VMSS]> [[-PassThru]] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]] [[-Async]] [-Uuid] <guid> [[-PassThru]] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]] [[-Async]] [-Name] <string> [[-PassThru]] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]] [[-Async]]
```
### Parameters
| Name | Type | Required | Default Value | Description |
| :--- | :--- | :------- | :------------ | :---------- |
| Async | switch | False |  |  |
| BestEffort | switch | False |  |  |
| Confirm | switch | False |  |  |
| Name | string | True |  |  |
| PassThru | switch | False |  |  |
| Ref | XenRef[VMSS] | True |  |  |
| SessionOpaqueRef | string | False |  |  |
| Uuid | guid | True |  |  |
| VMSS | VMSS | True |  |  |
| WhatIf | switch | False |  |  |
### Procedure
None

### Inputs
```
XenAPI.VMSS
XenAPI.XenRef`1[[XenAPI.VMSS, XenServer, Version=8.2.3.0, Culture=neutral, PublicKeyToken=d247b8b0ac7959e9]]
System.Guid
System.String

```
### Outputs
```
XenAPI.VMSS
XenAPI.Task
System.Void

```
### Links
None

### Examples

Remove-XenVMSS [-VMSS] <VMSS> [-PassThru] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [-Async] [<CommonParameters>]

Remove-XenVMSS [-Ref] <XenRef[VMSS]> [-PassThru] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [-Async] [<CommonParameters>]

Remove-XenVMSS [-Uuid] <guid> [-PassThru] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [-Async] [<CommonParameters>]

Remove-XenVMSS [-Name] <string> [-PassThru] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [-Async] [<CommonParameters>]


## Remove-XenVMSSProperty

### Synopsis
None

### Description
None

### Syntax
```
Remove-XenVMSSProperty [-VMSS] <VMSS> [[-PassThru]] [[-Schedule] <string>] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]] [-Ref] <XenRef[VMSS]> [[-PassThru]] [[-Schedule] <string>] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]] [-Uuid] <guid> [[-PassThru]] [[-Schedule] <string>] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]] [-Name] <string> [[-PassThru]] [[-Schedule] <string>] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]]
```
### Parameters
| Name | Type | Required | Default Value | Description |
| :--- | :--- | :------- | :------------ | :---------- |
| BestEffort | switch | False |  |  |
| Confirm | switch | False |  |  |
| Name | string | True |  |  |
| PassThru | switch | False |  |  |
| Ref | XenRef[VMSS] | True |  |  |
| Schedule | string | False |  |  |
| SessionOpaqueRef | string | False |  |  |
| Uuid | guid | True |  |  |
| VMSS | VMSS | True |  |  |
| WhatIf | switch | False |  |  |
### Procedure
None

### Inputs
```
XenAPI.VMSS
XenAPI.XenRef`1[[XenAPI.VMSS, XenServer, Version=8.2.3.0, Culture=neutral, PublicKeyToken=d247b8b0ac7959e9]]
System.Guid
System.String

```
### Outputs
```
XenAPI.VMSS

```
### Links
None

### Examples

Remove-XenVMSSProperty [-VMSS] <VMSS> [-PassThru] [-Schedule <string>] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [<CommonParameters>]

Remove-XenVMSSProperty [-Ref] <XenRef[VMSS]> [-PassThru] [-Schedule <string>] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [<CommonParameters>]

Remove-XenVMSSProperty [-Uuid] <guid> [-PassThru] [-Schedule <string>] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [<CommonParameters>]

Remove-XenVMSSProperty [-Name] <string> [-PassThru] [-Schedule <string>] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [<CommonParameters>]


## Remove-XenVTPM

### Synopsis
None

### Description
None

### Syntax
```
Remove-XenVTPM [-VTPM] <VTPM> [[-PassThru]] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]] [[-Async]] [-Ref] <XenRef[VTPM]> [[-PassThru]] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]] [[-Async]] [-Uuid] <guid> [[-PassThru]] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]] [[-Async]]
```
### Parameters
| Name | Type | Required | Default Value | Description |
| :--- | :--- | :------- | :------------ | :---------- |
| Async | switch | False |  |  |
| BestEffort | switch | False |  |  |
| Confirm | switch | False |  |  |
| PassThru | switch | False |  |  |
| Ref | XenRef[VTPM] | True |  |  |
| SessionOpaqueRef | string | False |  |  |
| Uuid | guid | True |  |  |
| VTPM | VTPM | True |  |  |
| WhatIf | switch | False |  |  |
### Procedure
None

### Inputs
```
XenAPI.VTPM
XenAPI.XenRef`1[[XenAPI.VTPM, XenServer, Version=8.2.3.0, Culture=neutral, PublicKeyToken=d247b8b0ac7959e9]]
System.Guid

```
### Outputs
```
XenAPI.VTPM
XenAPI.Task
System.Void

```
### Links
None

### Examples

Remove-XenVTPM [-VTPM] <VTPM> [-PassThru] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [-Async] [<CommonParameters>]

Remove-XenVTPM [-Ref] <XenRef[VTPM]> [-PassThru] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [-Async] [<CommonParameters>]

Remove-XenVTPM [-Uuid] <guid> [-PassThru] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [-Async] [<CommonParameters>]


## Remove-XenVUSB

### Synopsis
None

### Description
None

### Syntax
```
Remove-XenVUSB [-VUSB] <VUSB> [[-PassThru]] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]] [[-Async]] [-Ref] <XenRef[VUSB]> [[-PassThru]] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]] [[-Async]] [-Uuid] <guid> [[-PassThru]] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]] [[-Async]]
```
### Parameters
| Name | Type | Required | Default Value | Description |
| :--- | :--- | :------- | :------------ | :---------- |
| Async | switch | False |  |  |
| BestEffort | switch | False |  |  |
| Confirm | switch | False |  |  |
| PassThru | switch | False |  |  |
| Ref | XenRef[VUSB] | True |  |  |
| SessionOpaqueRef | string | False |  |  |
| Uuid | guid | True |  |  |
| VUSB | VUSB | True |  |  |
| WhatIf | switch | False |  |  |
### Procedure
None

### Inputs
```
XenAPI.VUSB
XenAPI.XenRef`1[[XenAPI.VUSB, XenServer, Version=8.2.3.0, Culture=neutral, PublicKeyToken=d247b8b0ac7959e9]]
System.Guid

```
### Outputs
```
XenAPI.VUSB
XenAPI.Task
System.Void

```
### Links
None

### Examples

Remove-XenVUSB [-VUSB] <VUSB> [-PassThru] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [-Async] [<CommonParameters>]

Remove-XenVUSB [-Ref] <XenRef[VUSB]> [-PassThru] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [-Async] [<CommonParameters>]

Remove-XenVUSB [-Uuid] <guid> [-PassThru] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [-Async] [<CommonParameters>]


## Remove-XenVUSBProperty

### Synopsis
None

### Description
None

### Syntax
```
Remove-XenVUSBProperty [-VUSB] <VUSB> [[-PassThru]] [[-OtherConfig] <string>] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]] [-Ref] <XenRef[VUSB]> [[-PassThru]] [[-OtherConfig] <string>] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]] [-Uuid] <guid> [[-PassThru]] [[-OtherConfig] <string>] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]]
```
### Parameters
| Name | Type | Required | Default Value | Description |
| :--- | :--- | :------- | :------------ | :---------- |
| BestEffort | switch | False |  |  |
| Confirm | switch | False |  |  |
| OtherConfig | string | False |  |  |
| PassThru | switch | False |  |  |
| Ref | XenRef[VUSB] | True |  |  |
| SessionOpaqueRef | string | False |  |  |
| Uuid | guid | True |  |  |
| VUSB | VUSB | True |  |  |
| WhatIf | switch | False |  |  |
### Procedure
None

### Inputs
```
XenAPI.VUSB
XenAPI.XenRef`1[[XenAPI.VUSB, XenServer, Version=8.2.3.0, Culture=neutral, PublicKeyToken=d247b8b0ac7959e9]]
System.Guid

```
### Outputs
```
XenAPI.VUSB

```
### Links
None

### Examples

Remove-XenVUSBProperty [-VUSB] <VUSB> [-PassThru] [-OtherConfig <string>] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [<CommonParameters>]

Remove-XenVUSBProperty [-Ref] <XenRef[VUSB]> [-PassThru] [-OtherConfig <string>] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [<CommonParameters>]

Remove-XenVUSBProperty [-Uuid] <guid> [-PassThru] [-OtherConfig <string>] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [<CommonParameters>]


## Send-XenBlob

### Synopsis
None

### Description
None

### Syntax
```
Send-XenBlob [-XenHost] <string> [-Path] <string> [[-ProgressDelegate] <HTTP+UpdateProgressDelegate>] [[-Ref] <string>] [[-CancellingDelegate] <HTTP+FuncBool>] [[-TimeoutMs] <int>] [[-Proxy] <IWebProxy>] [[-TaskRef] <string>] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]]
```
### Parameters
| Name | Type | Required | Default Value | Description |
| :--- | :--- | :------- | :------------ | :---------- |
| BestEffort | switch | False |  |  |
| CancellingDelegate | HTTP+FuncBool | False |  |  |
| Confirm | switch | False |  |  |
| Path | string | True |  |  |
| ProgressDelegate | HTTP+UpdateProgressDelegate | False |  |  |
| Proxy | IWebProxy | False |  |  |
| Ref | string | False |  |  |
| SessionOpaqueRef | string | False |  |  |
| TaskRef | string | False |  |  |
| TimeoutMs | int | False |  |  |
| WhatIf | switch | False |  |  |
| XenHost | string | True |  |  |
### Procedure
None

### Inputs
```
None

```
### Outputs
```
System.Void

```
### Links
None

### Examples

Send-XenBlob -XenHost <string> -Path <string> [-ProgressDelegate <HTTP+UpdateProgressDelegate>] [-Ref <string>] [-CancellingDelegate <HTTP+FuncBool>] [-TimeoutMs <int>] [-Proxy <IWebProxy>] [-TaskRef <string>] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [<CommonParameters>]


## Send-XenHostRestore

### Synopsis
None

### Description
None

### Syntax
```
Send-XenHostRestore [-XenHost] <string> [-Path] <string> [[-ProgressDelegate] <HTTP+UpdateProgressDelegate>] [[-CancellingDelegate] <HTTP+FuncBool>] [[-TimeoutMs] <int>] [[-Proxy] <IWebProxy>] [[-TaskRef] <string>] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]]
```
### Parameters
| Name | Type | Required | Default Value | Description |
| :--- | :--- | :------- | :------------ | :---------- |
| BestEffort | switch | False |  |  |
| CancellingDelegate | HTTP+FuncBool | False |  |  |
| Confirm | switch | False |  |  |
| Path | string | True |  |  |
| ProgressDelegate | HTTP+UpdateProgressDelegate | False |  |  |
| Proxy | IWebProxy | False |  |  |
| SessionOpaqueRef | string | False |  |  |
| TaskRef | string | False |  |  |
| TimeoutMs | int | False |  |  |
| WhatIf | switch | False |  |  |
| XenHost | string | True |  |  |
### Procedure
None

### Inputs
```
None

```
### Outputs
```
System.Void

```
### Links
None

### Examples

Send-XenHostRestore -XenHost <string> -Path <string> [-ProgressDelegate <HTTP+UpdateProgressDelegate>] [-CancellingDelegate <HTTP+FuncBool>] [-TimeoutMs <int>] [-Proxy <IWebProxy>] [-TaskRef <string>] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [<CommonParameters>]


## Send-XenOemPatchStream

### Synopsis
None

### Description
None

### Syntax
```
Send-XenOemPatchStream [-XenHost] <string> [-Path] <string> [[-ProgressDelegate] <HTTP+UpdateProgressDelegate>] [[-CancellingDelegate] <HTTP+FuncBool>] [[-TimeoutMs] <int>] [[-Proxy] <IWebProxy>] [[-TaskRef] <string>] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]]
```
### Parameters
| Name | Type | Required | Default Value | Description |
| :--- | :--- | :------- | :------------ | :---------- |
| BestEffort | switch | False |  |  |
| CancellingDelegate | HTTP+FuncBool | False |  |  |
| Confirm | switch | False |  |  |
| Path | string | True |  |  |
| ProgressDelegate | HTTP+UpdateProgressDelegate | False |  |  |
| Proxy | IWebProxy | False |  |  |
| SessionOpaqueRef | string | False |  |  |
| TaskRef | string | False |  |  |
| TimeoutMs | int | False |  |  |
| WhatIf | switch | False |  |  |
| XenHost | string | True |  |  |
### Procedure
None

### Inputs
```
None

```
### Outputs
```
System.Void

```
### Links
None

### Examples

Send-XenOemPatchStream -XenHost <string> -Path <string> [-ProgressDelegate <HTTP+UpdateProgressDelegate>] [-CancellingDelegate <HTTP+FuncBool>] [-TimeoutMs <int>] [-Proxy <IWebProxy>] [-TaskRef <string>] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [<CommonParameters>]


## Send-XenPoolPatch

### Synopsis
None

### Description
None

### Syntax
```
Send-XenPoolPatch [-XenHost] <string> [-Path] <string> [[-ProgressDelegate] <HTTP+UpdateProgressDelegate>] [[-CancellingDelegate] <HTTP+FuncBool>] [[-TimeoutMs] <int>] [[-Proxy] <IWebProxy>] [[-TaskRef] <string>] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]]
```
### Parameters
| Name | Type | Required | Default Value | Description |
| :--- | :--- | :------- | :------------ | :---------- |
| BestEffort | switch | False |  |  |
| CancellingDelegate | HTTP+FuncBool | False |  |  |
| Confirm | switch | False |  |  |
| Path | string | True |  |  |
| ProgressDelegate | HTTP+UpdateProgressDelegate | False |  |  |
| Proxy | IWebProxy | False |  |  |
| SessionOpaqueRef | string | False |  |  |
| TaskRef | string | False |  |  |
| TimeoutMs | int | False |  |  |
| WhatIf | switch | False |  |  |
| XenHost | string | True |  |  |
### Procedure
None

### Inputs
```
None

```
### Outputs
```
System.Void

```
### Links
None

### Examples

Send-XenPoolPatch -XenHost <string> -Path <string> [-ProgressDelegate <HTTP+UpdateProgressDelegate>] [-CancellingDelegate <HTTP+FuncBool>] [-TimeoutMs <int>] [-Proxy <IWebProxy>] [-TaskRef <string>] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [<CommonParameters>]


## Set-XenBond

### Synopsis
None

### Description
None

### Syntax
```
Set-XenBond [-Bond] <Bond> [[-PassThru]] [[-OtherConfig] <hashtable>] [[-Mode] <bond_mode>] [[-Property] <string[]>] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]] [-Ref] <XenRef[Bond]> [[-PassThru]] [[-OtherConfig] <hashtable>] [[-Mode] <bond_mode>] [[-Property] <string[]>] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]] [-Uuid] <guid> [[-PassThru]] [[-OtherConfig] <hashtable>] [[-Mode] <bond_mode>] [[-Property] <string[]>] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]]
```
### Parameters
| Name | Type | Required | Default Value | Description |
| :--- | :--- | :------- | :------------ | :---------- |
| BestEffort | switch | False |  |  |
| Bond | Bond | True |  |  |
| Confirm | switch | False |  |  |
| Mode | bond_mode | False |  |  |
| OtherConfig | hashtable | False |  |  |
| PassThru | switch | False |  |  |
| Property | string[] | False |  |  |
| Ref | XenRef[Bond] | True |  |  |
| SessionOpaqueRef | string | False |  |  |
| Uuid | guid | True |  |  |
| WhatIf | switch | False |  |  |
### Procedure
None

### Inputs
```
XenAPI.Bond
XenAPI.XenRef`1[[XenAPI.Bond, XenServer, Version=8.2.3.0, Culture=neutral, PublicKeyToken=d247b8b0ac7959e9]]
System.Guid

```
### Outputs
```
XenAPI.Bond
XenAPI.Task
System.Void

```
### Links
None

### Examples

Set-XenBond [-Bond] <Bond> [-PassThru] [-OtherConfig <hashtable>] [-Mode <bond_mode>] [-Property <string[]>] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [<CommonParameters>]

Set-XenBond [-Ref] <XenRef[Bond]> [-PassThru] [-OtherConfig <hashtable>] [-Mode <bond_mode>] [-Property <string[]>] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [<CommonParameters>]

Set-XenBond [-Uuid] <guid> [-PassThru] [-OtherConfig <hashtable>] [-Mode <bond_mode>] [-Property <string[]>] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [<CommonParameters>]


## Set-XenCluster

### Synopsis
None

### Description
None

### Syntax
```
Set-XenCluster [-Cluster] <Cluster> [[-PassThru]] [[-OtherConfig] <hashtable>] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]] [-Ref] <XenRef[Cluster]> [[-PassThru]] [[-OtherConfig] <hashtable>] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]] [-Uuid] <guid> [[-PassThru]] [[-OtherConfig] <hashtable>] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]]
```
### Parameters
| Name | Type | Required | Default Value | Description |
| :--- | :--- | :------- | :------------ | :---------- |
| BestEffort | switch | False |  |  |
| Cluster | Cluster | True |  |  |
| Confirm | switch | False |  |  |
| OtherConfig | hashtable | False |  |  |
| PassThru | switch | False |  |  |
| Ref | XenRef[Cluster] | True |  |  |
| SessionOpaqueRef | string | False |  |  |
| Uuid | guid | True |  |  |
| WhatIf | switch | False |  |  |
### Procedure
None

### Inputs
```
XenAPI.Cluster
XenAPI.XenRef`1[[XenAPI.Cluster, XenServer, Version=8.2.3.0, Culture=neutral, PublicKeyToken=d247b8b0ac7959e9]]
System.Guid

```
### Outputs
```
XenAPI.Cluster
System.Void

```
### Links
None

### Examples

Set-XenCluster [-Cluster] <Cluster> [-PassThru] [-OtherConfig <hashtable>] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [<CommonParameters>]

Set-XenCluster [-Ref] <XenRef[Cluster]> [-PassThru] [-OtherConfig <hashtable>] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [<CommonParameters>]

Set-XenCluster [-Uuid] <guid> [-PassThru] [-OtherConfig <hashtable>] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [<CommonParameters>]


## Set-XenConsole

### Synopsis
None

### Description
None

### Syntax
```
Set-XenConsole [-Console] <Console> [[-PassThru]] [[-OtherConfig] <hashtable>] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]] [-Ref] <XenRef[Console]> [[-PassThru]] [[-OtherConfig] <hashtable>] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]] [-Uuid] <guid> [[-PassThru]] [[-OtherConfig] <hashtable>] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]]
```
### Parameters
| Name | Type | Required | Default Value | Description |
| :--- | :--- | :------- | :------------ | :---------- |
| BestEffort | switch | False |  |  |
| Confirm | switch | False |  |  |
| Console | Console | True |  |  |
| OtherConfig | hashtable | False |  |  |
| PassThru | switch | False |  |  |
| Ref | XenRef[Console] | True |  |  |
| SessionOpaqueRef | string | False |  |  |
| Uuid | guid | True |  |  |
| WhatIf | switch | False |  |  |
### Procedure
None

### Inputs
```
XenAPI.Console
XenAPI.XenRef`1[[XenAPI.Console, XenServer, Version=8.2.3.0, Culture=neutral, PublicKeyToken=d247b8b0ac7959e9]]
System.Guid

```
### Outputs
```
XenAPI.Console
System.Void

```
### Links
None

### Examples

Set-XenConsole [-Console] <Console> [-PassThru] [-OtherConfig <hashtable>] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [<CommonParameters>]

Set-XenConsole [-Ref] <XenRef[Console]> [-PassThru] [-OtherConfig <hashtable>] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [<CommonParameters>]

Set-XenConsole [-Uuid] <guid> [-PassThru] [-OtherConfig <hashtable>] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [<CommonParameters>]


## Set-XenCrashdump

### Synopsis
None

### Description
None

### Syntax
```
Set-XenCrashdump [-Crashdump] <Crashdump> [[-PassThru]] [[-OtherConfig] <hashtable>] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]] [-Ref] <XenRef[Crashdump]> [[-PassThru]] [[-OtherConfig] <hashtable>] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]] [-Uuid] <guid> [[-PassThru]] [[-OtherConfig] <hashtable>] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]]
```
### Parameters
| Name | Type | Required | Default Value | Description |
| :--- | :--- | :------- | :------------ | :---------- |
| BestEffort | switch | False |  |  |
| Confirm | switch | False |  |  |
| Crashdump | Crashdump | True |  |  |
| OtherConfig | hashtable | False |  |  |
| PassThru | switch | False |  |  |
| Ref | XenRef[Crashdump] | True |  |  |
| SessionOpaqueRef | string | False |  |  |
| Uuid | guid | True |  |  |
| WhatIf | switch | False |  |  |
### Procedure
None

### Inputs
```
XenAPI.Crashdump
XenAPI.XenRef`1[[XenAPI.Crashdump, XenServer, Version=8.2.3.0, Culture=neutral, PublicKeyToken=d247b8b0ac7959e9]]
System.Guid

```
### Outputs
```
XenAPI.Crashdump
System.Void

```
### Links
None

### Examples

Set-XenCrashdump [-Crashdump] <Crashdump> [-PassThru] [-OtherConfig <hashtable>] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [<CommonParameters>]

Set-XenCrashdump [-Ref] <XenRef[Crashdump]> [-PassThru] [-OtherConfig <hashtable>] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [<CommonParameters>]

Set-XenCrashdump [-Uuid] <guid> [-PassThru] [-OtherConfig <hashtable>] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [<CommonParameters>]


## Set-XenGPUGroup

### Synopsis
None

### Description
None

### Syntax
```
Set-XenGPUGroup [-GPUGroup] <GPU_group> [[-PassThru]] [[-NameLabel] <string>] [[-NameDescription] <string>] [[-OtherConfig] <hashtable>] [[-AllocationAlgorithm] <allocation_algorithm>] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]] [-Ref] <XenRef[GPU_group]> [[-PassThru]] [[-NameLabel] <string>] [[-NameDescription] <string>] [[-OtherConfig] <hashtable>] [[-AllocationAlgorithm] <allocation_algorithm>] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]] [-Uuid] <guid> [[-PassThru]] [[-NameLabel] <string>] [[-NameDescription] <string>] [[-OtherConfig] <hashtable>] [[-AllocationAlgorithm] <allocation_algorithm>] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]] [-Name] <string> [[-PassThru]] [[-NameLabel] <string>] [[-NameDescription] <string>] [[-OtherConfig] <hashtable>] [[-AllocationAlgorithm] <allocation_algorithm>] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]]
```
### Parameters
| Name | Type | Required | Default Value | Description |
| :--- | :--- | :------- | :------------ | :---------- |
| AllocationAlgorithm | allocation_algorithm | False |  |  |
| BestEffort | switch | False |  |  |
| Confirm | switch | False |  |  |
| GPUGroup | GPU_group | True |  |  |
| Name | string | True |  |  |
| NameDescription | string | False |  |  |
| NameLabel | string | False |  |  |
| OtherConfig | hashtable | False |  |  |
| PassThru | switch | False |  |  |
| Ref | XenRef[GPU_group] | True |  |  |
| SessionOpaqueRef | string | False |  |  |
| Uuid | guid | True |  |  |
| WhatIf | switch | False |  |  |
### Procedure
None

### Inputs
```
XenAPI.GPU_group
XenAPI.XenRef`1[[XenAPI.GPU_group, XenServer, Version=8.2.3.0, Culture=neutral, PublicKeyToken=d247b8b0ac7959e9]]
System.Guid
System.String

```
### Outputs
```
XenAPI.GPU_group
System.Void

```
### Links
None

### Examples

Set-XenGPUGroup [-GPUGroup] <GPU_group> [-PassThru] [-NameLabel <string>] [-NameDescription <string>] [-OtherConfig <hashtable>] [-AllocationAlgorithm <allocation_algorithm>] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [<CommonParameters>]

Set-XenGPUGroup [-Ref] <XenRef[GPU_group]> [-PassThru] [-NameLabel <string>] [-NameDescription <string>] [-OtherConfig <hashtable>] [-AllocationAlgorithm <allocation_algorithm>] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [<CommonParameters>]

Set-XenGPUGroup [-Uuid] <guid> [-PassThru] [-NameLabel <string>] [-NameDescription <string>] [-OtherConfig <hashtable>] [-AllocationAlgorithm <allocation_algorithm>] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [<CommonParameters>]

Set-XenGPUGroup [-Name] <string> [-PassThru] [-NameLabel <string>] [-NameDescription <string>] [-OtherConfig <hashtable>] [-AllocationAlgorithm <allocation_algorithm>] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [<CommonParameters>]


## Set-XenHost

### Synopsis
None

### Description
None

### Syntax
```
Set-XenHost [-XenHost] <Host> [[-PassThru]] [[-NameLabel] <string>] [[-NameDescription] <string>] [[-OtherConfig] <hashtable>] [[-Logging] <hashtable>] [[-SuspendImageSr] <XenRef[SR]>] [[-CrashDumpSr] <XenRef[SR]>] [[-Hostname] <string>] [[-Address] <string>] [[-Tags] <string[]>] [[-LicenseServer] <hashtable>] [[-GuestVCPUsParams] <hashtable>] [[-Display] <host_display>] [[-HostnameLive] <string>] [[-PowerOnMode] <KeyValuePair[string,hashtable]>] [[-CpuFeatures] <string>] [[-SslLegacy] <bool>] [[-IscsiIqn] <string>] [[-Multipathing] <bool>] [[-UefiCertificates] <string>] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]] [-Ref] <XenRef[Host]> [[-PassThru]] [[-NameLabel] <string>] [[-NameDescription] <string>] [[-OtherConfig] <hashtable>] [[-Logging] <hashtable>] [[-SuspendImageSr] <XenRef[SR]>] [[-CrashDumpSr] <XenRef[SR]>] [[-Hostname] <string>] [[-Address] <string>] [[-Tags] <string[]>] [[-LicenseServer] <hashtable>] [[-GuestVCPUsParams] <hashtable>] [[-Display] <host_display>] [[-HostnameLive] <string>] [[-PowerOnMode] <KeyValuePair[string,hashtable]>] [[-CpuFeatures] <string>] [[-SslLegacy] <bool>] [[-IscsiIqn] <string>] [[-Multipathing] <bool>] [[-UefiCertificates] <string>] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]] [-Uuid] <guid> [[-PassThru]] [[-NameLabel] <string>] [[-NameDescription] <string>] [[-OtherConfig] <hashtable>] [[-Logging] <hashtable>] [[-SuspendImageSr] <XenRef[SR]>] [[-CrashDumpSr] <XenRef[SR]>] [[-Hostname] <string>] [[-Address] <string>] [[-Tags] <string[]>] [[-LicenseServer] <hashtable>] [[-GuestVCPUsParams] <hashtable>] [[-Display] <host_display>] [[-HostnameLive] <string>] [[-PowerOnMode] <KeyValuePair[string,hashtable]>] [[-CpuFeatures] <string>] [[-SslLegacy] <bool>] [[-IscsiIqn] <string>] [[-Multipathing] <bool>] [[-UefiCertificates] <string>] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]] [-Name] <string> [[-PassThru]] [[-NameLabel] <string>] [[-NameDescription] <string>] [[-OtherConfig] <hashtable>] [[-Logging] <hashtable>] [[-SuspendImageSr] <XenRef[SR]>] [[-CrashDumpSr] <XenRef[SR]>] [[-Hostname] <string>] [[-Address] <string>] [[-Tags] <string[]>] [[-LicenseServer] <hashtable>] [[-GuestVCPUsParams] <hashtable>] [[-Display] <host_display>] [[-HostnameLive] <string>] [[-PowerOnMode] <KeyValuePair[string,hashtable]>] [[-CpuFeatures] <string>] [[-SslLegacy] <bool>] [[-IscsiIqn] <string>] [[-Multipathing] <bool>] [[-UefiCertificates] <string>] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]]
```
### Parameters
| Name | Type | Required | Default Value | Description |
| :--- | :--- | :------- | :------------ | :---------- |
| Address | string | False |  |  |
| BestEffort | switch | False |  |  |
| Confirm | switch | False |  |  |
| CpuFeatures | string | False |  |  |
| CrashDumpSr | XenRef[SR] | False |  |  |
| Display | host_display | False |  |  |
| GuestVCPUsParams | hashtable | False |  |  |
| Hostname | string | False |  |  |
| HostnameLive | string | False |  |  |
| IscsiIqn | string | False |  |  |
| LicenseServer | hashtable | False |  |  |
| Logging | hashtable | False |  |  |
| Multipathing | bool | False |  |  |
| Name | string | True |  |  |
| NameDescription | string | False |  |  |
| NameLabel | string | False |  |  |
| OtherConfig | hashtable | False |  |  |
| PassThru | switch | False |  |  |
| PowerOnMode | KeyValuePair[string,hashtable] | False |  |  |
| Ref | XenRef[Host] | True |  |  |
| SessionOpaqueRef | string | False |  |  |
| SslLegacy | bool | False |  |  |
| SuspendImageSr | XenRef[SR] | False |  |  |
| Tags | string[] | False |  |  |
| UefiCertificates | string | False |  |  |
| Uuid | guid | True |  |  |
| WhatIf | switch | False |  |  |
| XenHost | Host | True |  |  |
### Procedure
None

### Inputs
```
XenAPI.Host
XenAPI.XenRef`1[[XenAPI.Host, XenServer, Version=8.2.3.0, Culture=neutral, PublicKeyToken=d247b8b0ac7959e9]]
System.Guid
System.String

```
### Outputs
```
XenAPI.Host
XenAPI.Task
System.Void

```
### Links
None

### Examples

Set-XenHost [-XenHost] <Host> [-PassThru] [-NameLabel <string>] [-NameDescription <string>] [-OtherConfig <hashtable>] [-Logging <hashtable>] [-SuspendImageSr <XenRef[SR]>] [-CrashDumpSr <XenRef[SR]>] [-Hostname <string>] [-Address <string>] [-Tags <string[]>] [-LicenseServer <hashtable>] [-GuestVCPUsParams <hashtable>] [-Display <host_display>] [-HostnameLive <string>] [-PowerOnMode <KeyValuePair[string,hashtable]>] [-CpuFeatures <string>] [-SslLegacy <bool>] [-IscsiIqn <string>] [-Multipathing <bool>] [-UefiCertificates <string>] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [<CommonParameters>]

Set-XenHost [-Ref] <XenRef[Host]> [-PassThru] [-NameLabel <string>] [-NameDescription <string>] [-OtherConfig <hashtable>] [-Logging <hashtable>] [-SuspendImageSr <XenRef[SR]>] [-CrashDumpSr <XenRef[SR]>] [-Hostname <string>] [-Address <string>] [-Tags <string[]>] [-LicenseServer <hashtable>] [-GuestVCPUsParams <hashtable>] [-Display <host_display>] [-HostnameLive <string>] [-PowerOnMode <KeyValuePair[string,hashtable]>] [-CpuFeatures <string>] [-SslLegacy <bool>] [-IscsiIqn <string>] [-Multipathing <bool>] [-UefiCertificates <string>] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [<CommonParameters>]

Set-XenHost [-Uuid] <guid> [-PassThru] [-NameLabel <string>] [-NameDescription <string>] [-OtherConfig <hashtable>] [-Logging <hashtable>] [-SuspendImageSr <XenRef[SR]>] [-CrashDumpSr <XenRef[SR]>] [-Hostname <string>] [-Address <string>] [-Tags <string[]>] [-LicenseServer <hashtable>] [-GuestVCPUsParams <hashtable>] [-Display <host_display>] [-HostnameLive <string>] [-PowerOnMode <KeyValuePair[string,hashtable]>] [-CpuFeatures <string>] [-SslLegacy <bool>] [-IscsiIqn <string>] [-Multipathing <bool>] [-UefiCertificates <string>] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [<CommonParameters>]

Set-XenHost [-Name] <string> [-PassThru] [-NameLabel <string>] [-NameDescription <string>] [-OtherConfig <hashtable>] [-Logging <hashtable>] [-SuspendImageSr <XenRef[SR]>] [-CrashDumpSr <XenRef[SR]>] [-Hostname <string>] [-Address <string>] [-Tags <string[]>] [-LicenseServer <hashtable>] [-GuestVCPUsParams <hashtable>] [-Display <host_display>] [-HostnameLive <string>] [-PowerOnMode <KeyValuePair[string,hashtable]>] [-CpuFeatures <string>] [-SslLegacy <bool>] [-IscsiIqn <string>] [-Multipathing <bool>] [-UefiCertificates <string>] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [<CommonParameters>]


## Set-XenHostCpu

### Synopsis
None

### Description
None

### Syntax
```
Set-XenHostCpu [-HostCpu] <Host_cpu> [[-PassThru]] [[-OtherConfig] <hashtable>] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]] [-Ref] <XenRef[Host_cpu]> [[-PassThru]] [[-OtherConfig] <hashtable>] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]] [-Uuid] <guid> [[-PassThru]] [[-OtherConfig] <hashtable>] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]]
```
### Parameters
| Name | Type | Required | Default Value | Description |
| :--- | :--- | :------- | :------------ | :---------- |
| BestEffort | switch | False |  |  |
| Confirm | switch | False |  |  |
| HostCpu | Host_cpu | True |  |  |
| OtherConfig | hashtable | False |  |  |
| PassThru | switch | False |  |  |
| Ref | XenRef[Host_cpu] | True |  |  |
| SessionOpaqueRef | string | False |  |  |
| Uuid | guid | True |  |  |
| WhatIf | switch | False |  |  |
### Procedure
None

### Inputs
```
XenAPI.Host_cpu
XenAPI.XenRef`1[[XenAPI.Host_cpu, XenServer, Version=8.2.3.0, Culture=neutral, PublicKeyToken=d247b8b0ac7959e9]]
System.Guid

```
### Outputs
```
XenAPI.Host_cpu
System.Void

```
### Links
None

### Examples

Set-XenHostCpu [-HostCpu] <Host_cpu> [-PassThru] [-OtherConfig <hashtable>] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [<CommonParameters>]

Set-XenHostCpu [-Ref] <XenRef[Host_cpu]> [-PassThru] [-OtherConfig <hashtable>] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [<CommonParameters>]

Set-XenHostCpu [-Uuid] <guid> [-PassThru] [-OtherConfig <hashtable>] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [<CommonParameters>]


## Set-XenHostCrashdump

### Synopsis
None

### Description
None

### Syntax
```
Set-XenHostCrashdump [-HostCrashdump] <Host_crashdump> [[-PassThru]] [[-OtherConfig] <hashtable>] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]] [-Ref] <XenRef[Host_crashdump]> [[-PassThru]] [[-OtherConfig] <hashtable>] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]] [-Uuid] <guid> [[-PassThru]] [[-OtherConfig] <hashtable>] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]]
```
### Parameters
| Name | Type | Required | Default Value | Description |
| :--- | :--- | :------- | :------------ | :---------- |
| BestEffort | switch | False |  |  |
| Confirm | switch | False |  |  |
| HostCrashdump | Host_crashdump | True |  |  |
| OtherConfig | hashtable | False |  |  |
| PassThru | switch | False |  |  |
| Ref | XenRef[Host_crashdump] | True |  |  |
| SessionOpaqueRef | string | False |  |  |
| Uuid | guid | True |  |  |
| WhatIf | switch | False |  |  |
### Procedure
None

### Inputs
```
XenAPI.Host_crashdump
XenAPI.XenRef`1[[XenAPI.Host_crashdump, XenServer, Version=8.2.3.0, Culture=neutral, PublicKeyToken=d247b8b0ac7959e9]]
System.Guid

```
### Outputs
```
XenAPI.Host_crashdump
System.Void

```
### Links
None

### Examples

Set-XenHostCrashdump [-HostCrashdump] <Host_crashdump> [-PassThru] [-OtherConfig <hashtable>] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [<CommonParameters>]

Set-XenHostCrashdump [-Ref] <XenRef[Host_crashdump]> [-PassThru] [-OtherConfig <hashtable>] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [<CommonParameters>]

Set-XenHostCrashdump [-Uuid] <guid> [-PassThru] [-OtherConfig <hashtable>] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [<CommonParameters>]


## Set-XenHostMetrics

### Synopsis
None

### Description
None

### Syntax
```
Set-XenHostMetrics [-HostMetrics] <Host_metrics> [[-PassThru]] [[-OtherConfig] <hashtable>] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]] [-Ref] <XenRef[Host_metrics]> [[-PassThru]] [[-OtherConfig] <hashtable>] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]] [-Uuid] <guid> [[-PassThru]] [[-OtherConfig] <hashtable>] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]]
```
### Parameters
| Name | Type | Required | Default Value | Description |
| :--- | :--- | :------- | :------------ | :---------- |
| BestEffort | switch | False |  |  |
| Confirm | switch | False |  |  |
| HostMetrics | Host_metrics | True |  |  |
| OtherConfig | hashtable | False |  |  |
| PassThru | switch | False |  |  |
| Ref | XenRef[Host_metrics] | True |  |  |
| SessionOpaqueRef | string | False |  |  |
| Uuid | guid | True |  |  |
| WhatIf | switch | False |  |  |
### Procedure
None

### Inputs
```
XenAPI.Host_metrics
XenAPI.XenRef`1[[XenAPI.Host_metrics, XenServer, Version=8.2.3.0, Culture=neutral, PublicKeyToken=d247b8b0ac7959e9]]
System.Guid

```
### Outputs
```
XenAPI.Host_metrics
System.Void

```
### Links
None

### Examples

Set-XenHostMetrics [-HostMetrics] <Host_metrics> [-PassThru] [-OtherConfig <hashtable>] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [<CommonParameters>]

Set-XenHostMetrics [-Ref] <XenRef[Host_metrics]> [-PassThru] [-OtherConfig <hashtable>] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [<CommonParameters>]

Set-XenHostMetrics [-Uuid] <guid> [-PassThru] [-OtherConfig <hashtable>] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [<CommonParameters>]


## Set-XenHostPatch

### Synopsis
None

### Description
None

### Syntax
```
Set-XenHostPatch [-HostPatch] <Host_patch> [[-PassThru]] [[-OtherConfig] <hashtable>] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]] [-Ref] <XenRef[Host_patch]> [[-PassThru]] [[-OtherConfig] <hashtable>] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]] [-Uuid] <guid> [[-PassThru]] [[-OtherConfig] <hashtable>] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]] [-Name] <string> [[-PassThru]] [[-OtherConfig] <hashtable>] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]]
```
### Parameters
| Name | Type | Required | Default Value | Description |
| :--- | :--- | :------- | :------------ | :---------- |
| BestEffort | switch | False |  |  |
| Confirm | switch | False |  |  |
| HostPatch | Host_patch | True |  |  |
| Name | string | True |  |  |
| OtherConfig | hashtable | False |  |  |
| PassThru | switch | False |  |  |
| Ref | XenRef[Host_patch] | True |  |  |
| SessionOpaqueRef | string | False |  |  |
| Uuid | guid | True |  |  |
| WhatIf | switch | False |  |  |
### Procedure
None

### Inputs
```
XenAPI.Host_patch
XenAPI.XenRef`1[[XenAPI.Host_patch, XenServer, Version=8.2.3.0, Culture=neutral, PublicKeyToken=d247b8b0ac7959e9]]
System.Guid
System.String

```
### Outputs
```
XenAPI.Host_patch
System.Void

```
### Links
None

### Examples

Set-XenHostPatch [-HostPatch] <Host_patch> [-PassThru] [-OtherConfig <hashtable>] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [<CommonParameters>]

Set-XenHostPatch [-Ref] <XenRef[Host_patch]> [-PassThru] [-OtherConfig <hashtable>] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [<CommonParameters>]

Set-XenHostPatch [-Uuid] <guid> [-PassThru] [-OtherConfig <hashtable>] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [<CommonParameters>]

Set-XenHostPatch [-Name] <string> [-PassThru] [-OtherConfig <hashtable>] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [<CommonParameters>]


## Set-XenNetwork

### Synopsis
None

### Description
None

### Syntax
```
Set-XenNetwork [-Network] <Network> [[-PassThru]] [[-NameLabel] <string>] [[-NameDescription] <string>] [[-MTU] <long>] [[-OtherConfig] <hashtable>] [[-Tags] <string[]>] [[-DefaultLockingMode] <network_default_locking_mode>] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]] [-Ref] <XenRef[Network]> [[-PassThru]] [[-NameLabel] <string>] [[-NameDescription] <string>] [[-MTU] <long>] [[-OtherConfig] <hashtable>] [[-Tags] <string[]>] [[-DefaultLockingMode] <network_default_locking_mode>] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]] [-Uuid] <guid> [[-PassThru]] [[-NameLabel] <string>] [[-NameDescription] <string>] [[-MTU] <long>] [[-OtherConfig] <hashtable>] [[-Tags] <string[]>] [[-DefaultLockingMode] <network_default_locking_mode>] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]] [-Name] <string> [[-PassThru]] [[-NameLabel] <string>] [[-NameDescription] <string>] [[-MTU] <long>] [[-OtherConfig] <hashtable>] [[-Tags] <string[]>] [[-DefaultLockingMode] <network_default_locking_mode>] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]]
```
### Parameters
| Name | Type | Required | Default Value | Description |
| :--- | :--- | :------- | :------------ | :---------- |
| BestEffort | switch | False |  |  |
| Confirm | switch | False |  |  |
| DefaultLockingMode | network_default_locking_mode | False |  |  |
| MTU | long | False |  |  |
| Name | string | True |  |  |
| NameDescription | string | False |  |  |
| NameLabel | string | False |  |  |
| Network | Network | True |  |  |
| OtherConfig | hashtable | False |  |  |
| PassThru | switch | False |  |  |
| Ref | XenRef[Network] | True |  |  |
| SessionOpaqueRef | string | False |  |  |
| Tags | string[] | False |  |  |
| Uuid | guid | True |  |  |
| WhatIf | switch | False |  |  |
### Procedure
None

### Inputs
```
XenAPI.Network
XenAPI.XenRef`1[[XenAPI.Network, XenServer, Version=8.2.3.0, Culture=neutral, PublicKeyToken=d247b8b0ac7959e9]]
System.Guid
System.String

```
### Outputs
```
XenAPI.Network
XenAPI.Task
System.Void

```
### Links
None

### Examples

Set-XenNetwork [-Network] <Network> [-PassThru] [-NameLabel <string>] [-NameDescription <string>] [-MTU <long>] [-OtherConfig <hashtable>] [-Tags <string[]>] [-DefaultLockingMode <network_default_locking_mode>] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [<CommonParameters>]

Set-XenNetwork [-Ref] <XenRef[Network]> [-PassThru] [-NameLabel <string>] [-NameDescription <string>] [-MTU <long>] [-OtherConfig <hashtable>] [-Tags <string[]>] [-DefaultLockingMode <network_default_locking_mode>] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [<CommonParameters>]

Set-XenNetwork [-Uuid] <guid> [-PassThru] [-NameLabel <string>] [-NameDescription <string>] [-MTU <long>] [-OtherConfig <hashtable>] [-Tags <string[]>] [-DefaultLockingMode <network_default_locking_mode>] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [<CommonParameters>]

Set-XenNetwork [-Name] <string> [-PassThru] [-NameLabel <string>] [-NameDescription <string>] [-MTU <long>] [-OtherConfig <hashtable>] [-Tags <string[]>] [-DefaultLockingMode <network_default_locking_mode>] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [<CommonParameters>]


## Set-XenPBD

### Synopsis
None

### Description
None

### Syntax
```
Set-XenPBD [-PBD] <PBD> [[-PassThru]] [[-OtherConfig] <hashtable>] [[-DeviceConfig] <hashtable>] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]] [-Ref] <XenRef[PBD]> [[-PassThru]] [[-OtherConfig] <hashtable>] [[-DeviceConfig] <hashtable>] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]] [-Uuid] <guid> [[-PassThru]] [[-OtherConfig] <hashtable>] [[-DeviceConfig] <hashtable>] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]]
```
### Parameters
| Name | Type | Required | Default Value | Description |
| :--- | :--- | :------- | :------------ | :---------- |
| BestEffort | switch | False |  |  |
| Confirm | switch | False |  |  |
| DeviceConfig | hashtable | False |  |  |
| OtherConfig | hashtable | False |  |  |
| PBD | PBD | True |  |  |
| PassThru | switch | False |  |  |
| Ref | XenRef[PBD] | True |  |  |
| SessionOpaqueRef | string | False |  |  |
| Uuid | guid | True |  |  |
| WhatIf | switch | False |  |  |
### Procedure
None

### Inputs
```
XenAPI.PBD
XenAPI.XenRef`1[[XenAPI.PBD, XenServer, Version=8.2.3.0, Culture=neutral, PublicKeyToken=d247b8b0ac7959e9]]
System.Guid

```
### Outputs
```
XenAPI.PBD
XenAPI.Task
System.Void

```
### Links
None

### Examples

Set-XenPBD [-PBD] <PBD> [-PassThru] [-OtherConfig <hashtable>] [-DeviceConfig <hashtable>] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [<CommonParameters>]

Set-XenPBD [-Ref] <XenRef[PBD]> [-PassThru] [-OtherConfig <hashtable>] [-DeviceConfig <hashtable>] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [<CommonParameters>]

Set-XenPBD [-Uuid] <guid> [-PassThru] [-OtherConfig <hashtable>] [-DeviceConfig <hashtable>] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [<CommonParameters>]


## Set-XenPCI

### Synopsis
None

### Description
None

### Syntax
```
Set-XenPCI [-PCI] <PCI> [[-PassThru]] [[-OtherConfig] <hashtable>] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]] [-Ref] <XenRef[PCI]> [[-PassThru]] [[-OtherConfig] <hashtable>] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]] [-Uuid] <guid> [[-PassThru]] [[-OtherConfig] <hashtable>] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]]
```
### Parameters
| Name | Type | Required | Default Value | Description |
| :--- | :--- | :------- | :------------ | :---------- |
| BestEffort | switch | False |  |  |
| Confirm | switch | False |  |  |
| OtherConfig | hashtable | False |  |  |
| PCI | PCI | True |  |  |
| PassThru | switch | False |  |  |
| Ref | XenRef[PCI] | True |  |  |
| SessionOpaqueRef | string | False |  |  |
| Uuid | guid | True |  |  |
| WhatIf | switch | False |  |  |
### Procedure
None

### Inputs
```
XenAPI.PCI
XenAPI.XenRef`1[[XenAPI.PCI, XenServer, Version=8.2.3.0, Culture=neutral, PublicKeyToken=d247b8b0ac7959e9]]
System.Guid

```
### Outputs
```
XenAPI.PCI
System.Void

```
### Links
None

### Examples

Set-XenPCI [-PCI] <PCI> [-PassThru] [-OtherConfig <hashtable>] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [<CommonParameters>]

Set-XenPCI [-Ref] <XenRef[PCI]> [-PassThru] [-OtherConfig <hashtable>] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [<CommonParameters>]

Set-XenPCI [-Uuid] <guid> [-PassThru] [-OtherConfig <hashtable>] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [<CommonParameters>]


## Set-XenPGPU

### Synopsis
None

### Description
None

### Syntax
```
Set-XenPGPU [-PGPU] <PGPU> [[-PassThru]] [[-OtherConfig] <hashtable>] [[-EnabledVGPUTypes] <List[XenRef[VGPU_type]]>] [[-GPUGroup] <XenRef[GPU_group]>] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]] [-Ref] <XenRef[PGPU]> [[-PassThru]] [[-OtherConfig] <hashtable>] [[-EnabledVGPUTypes] <List[XenRef[VGPU_type]]>] [[-GPUGroup] <XenRef[GPU_group]>] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]] [-Uuid] <guid> [[-PassThru]] [[-OtherConfig] <hashtable>] [[-EnabledVGPUTypes] <List[XenRef[VGPU_type]]>] [[-GPUGroup] <XenRef[GPU_group]>] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]]
```
### Parameters
| Name | Type | Required | Default Value | Description |
| :--- | :--- | :------- | :------------ | :---------- |
| BestEffort | switch | False |  |  |
| Confirm | switch | False |  |  |
| EnabledVGPUTypes | List[XenRef[VGPU_type]] | False |  |  |
| GPUGroup | XenRef[GPU_group] | False |  |  |
| OtherConfig | hashtable | False |  |  |
| PGPU | PGPU | True |  |  |
| PassThru | switch | False |  |  |
| Ref | XenRef[PGPU] | True |  |  |
| SessionOpaqueRef | string | False |  |  |
| Uuid | guid | True |  |  |
| WhatIf | switch | False |  |  |
### Procedure
None

### Inputs
```
XenAPI.PGPU
XenAPI.XenRef`1[[XenAPI.PGPU, XenServer, Version=8.2.3.0, Culture=neutral, PublicKeyToken=d247b8b0ac7959e9]]
System.Guid

```
### Outputs
```
XenAPI.PGPU
XenAPI.Task
System.Void

```
### Links
None

### Examples

Set-XenPGPU [-PGPU] <PGPU> [-PassThru] [-OtherConfig <hashtable>] [-EnabledVGPUTypes <List[XenRef[VGPU_type]]>] [-GPUGroup <XenRef[GPU_group]>] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [<CommonParameters>]

Set-XenPGPU [-Ref] <XenRef[PGPU]> [-PassThru] [-OtherConfig <hashtable>] [-EnabledVGPUTypes <List[XenRef[VGPU_type]]>] [-GPUGroup <XenRef[GPU_group]>] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [<CommonParameters>]

Set-XenPGPU [-Uuid] <guid> [-PassThru] [-OtherConfig <hashtable>] [-EnabledVGPUTypes <List[XenRef[VGPU_type]]>] [-GPUGroup <XenRef[GPU_group]>] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [<CommonParameters>]


## Set-XenPIF

### Synopsis
None

### Description
None

### Syntax
```
Set-XenPIF [-PIF] <PIF> [[-PassThru]] [[-OtherConfig] <hashtable>] [[-PrimaryAddressType] <primary_address_type>] [[-DisallowUnplug] <bool>] [[-Property] <string[]>] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]] [-Ref] <XenRef[PIF]> [[-PassThru]] [[-OtherConfig] <hashtable>] [[-PrimaryAddressType] <primary_address_type>] [[-DisallowUnplug] <bool>] [[-Property] <string[]>] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]] [-Uuid] <guid> [[-PassThru]] [[-OtherConfig] <hashtable>] [[-PrimaryAddressType] <primary_address_type>] [[-DisallowUnplug] <bool>] [[-Property] <string[]>] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]]
```
### Parameters
| Name | Type | Required | Default Value | Description |
| :--- | :--- | :------- | :------------ | :---------- |
| BestEffort | switch | False |  |  |
| Confirm | switch | False |  |  |
| DisallowUnplug | bool | False |  |  |
| OtherConfig | hashtable | False |  |  |
| PIF | PIF | True |  |  |
| PassThru | switch | False |  |  |
| PrimaryAddressType | primary_address_type | False |  |  |
| Property | string[] | False |  |  |
| Ref | XenRef[PIF] | True |  |  |
| SessionOpaqueRef | string | False |  |  |
| Uuid | guid | True |  |  |
| WhatIf | switch | False |  |  |
### Procedure
None

### Inputs
```
XenAPI.PIF
XenAPI.XenRef`1[[XenAPI.PIF, XenServer, Version=8.2.3.0, Culture=neutral, PublicKeyToken=d247b8b0ac7959e9]]
System.Guid

```
### Outputs
```
XenAPI.PIF
XenAPI.Task
System.Void

```
### Links
None

### Examples

Set-XenPIF [-PIF] <PIF> [-PassThru] [-OtherConfig <hashtable>] [-PrimaryAddressType <primary_address_type>] [-DisallowUnplug <bool>] [-Property <string[]>] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [<CommonParameters>]

Set-XenPIF [-Ref] <XenRef[PIF]> [-PassThru] [-OtherConfig <hashtable>] [-PrimaryAddressType <primary_address_type>] [-DisallowUnplug <bool>] [-Property <string[]>] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [<CommonParameters>]

Set-XenPIF [-Uuid] <guid> [-PassThru] [-OtherConfig <hashtable>] [-PrimaryAddressType <primary_address_type>] [-DisallowUnplug <bool>] [-Property <string[]>] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [<CommonParameters>]


## Set-XenPIFMetrics

### Synopsis
None

### Description
None

### Syntax
```
Set-XenPIFMetrics [-PIFMetrics] <PIF_metrics> [[-PassThru]] [[-OtherConfig] <hashtable>] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]] [-Ref] <XenRef[PIF_metrics]> [[-PassThru]] [[-OtherConfig] <hashtable>] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]] [-Uuid] <guid> [[-PassThru]] [[-OtherConfig] <hashtable>] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]]
```
### Parameters
| Name | Type | Required | Default Value | Description |
| :--- | :--- | :------- | :------------ | :---------- |
| BestEffort | switch | False |  |  |
| Confirm | switch | False |  |  |
| OtherConfig | hashtable | False |  |  |
| PIFMetrics | PIF_metrics | True |  |  |
| PassThru | switch | False |  |  |
| Ref | XenRef[PIF_metrics] | True |  |  |
| SessionOpaqueRef | string | False |  |  |
| Uuid | guid | True |  |  |
| WhatIf | switch | False |  |  |
### Procedure
None

### Inputs
```
XenAPI.PIF_metrics
XenAPI.XenRef`1[[XenAPI.PIF_metrics, XenServer, Version=8.2.3.0, Culture=neutral, PublicKeyToken=d247b8b0ac7959e9]]
System.Guid

```
### Outputs
```
XenAPI.PIF_metrics
System.Void

```
### Links
None

### Examples

Set-XenPIFMetrics [-PIFMetrics] <PIF_metrics> [-PassThru] [-OtherConfig <hashtable>] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [<CommonParameters>]

Set-XenPIFMetrics [-Ref] <XenRef[PIF_metrics]> [-PassThru] [-OtherConfig <hashtable>] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [<CommonParameters>]

Set-XenPIFMetrics [-Uuid] <guid> [-PassThru] [-OtherConfig <hashtable>] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [<CommonParameters>]


## Set-XenPool

### Synopsis
None

### Description
None

### Syntax
```
Set-XenPool [-Pool] <Pool> [[-PassThru]] [[-NameLabel] <string>] [[-NameDescription] <string>] [[-DefaultSR] <XenRef[SR]>] [[-SuspendImageSR] <XenRef[SR]>] [[-CrashDumpSR] <XenRef[SR]>] [[-OtherConfig] <hashtable>] [[-HaAllowOvercommit] <bool>] [[-Tags] <string[]>] [[-GuiConfig] <hashtable>] [[-HealthCheckConfig] <hashtable>] [[-WlbEnabled] <bool>] [[-WlbVerifyCert] <bool>] [[-PolicyNoVendorDevice] <bool>] [[-LivePatchingDisabled] <bool>] [[-UefiCertificates] <string>] [[-IsPsrPending] <bool>] [[-HaHostFailuresToTolerate] <long>] [[-VswitchController] <string>] [[-IgmpSnoopingEnabled] <bool>] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]] [-Ref] <XenRef[Pool]> [[-PassThru]] [[-NameLabel] <string>] [[-NameDescription] <string>] [[-DefaultSR] <XenRef[SR]>] [[-SuspendImageSR] <XenRef[SR]>] [[-CrashDumpSR] <XenRef[SR]>] [[-OtherConfig] <hashtable>] [[-HaAllowOvercommit] <bool>] [[-Tags] <string[]>] [[-GuiConfig] <hashtable>] [[-HealthCheckConfig] <hashtable>] [[-WlbEnabled] <bool>] [[-WlbVerifyCert] <bool>] [[-PolicyNoVendorDevice] <bool>] [[-LivePatchingDisabled] <bool>] [[-UefiCertificates] <string>] [[-IsPsrPending] <bool>] [[-HaHostFailuresToTolerate] <long>] [[-VswitchController] <string>] [[-IgmpSnoopingEnabled] <bool>] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]] [-Uuid] <guid> [[-PassThru]] [[-NameLabel] <string>] [[-NameDescription] <string>] [[-DefaultSR] <XenRef[SR]>] [[-SuspendImageSR] <XenRef[SR]>] [[-CrashDumpSR] <XenRef[SR]>] [[-OtherConfig] <hashtable>] [[-HaAllowOvercommit] <bool>] [[-Tags] <string[]>] [[-GuiConfig] <hashtable>] [[-HealthCheckConfig] <hashtable>] [[-WlbEnabled] <bool>] [[-WlbVerifyCert] <bool>] [[-PolicyNoVendorDevice] <bool>] [[-LivePatchingDisabled] <bool>] [[-UefiCertificates] <string>] [[-IsPsrPending] <bool>] [[-HaHostFailuresToTolerate] <long>] [[-VswitchController] <string>] [[-IgmpSnoopingEnabled] <bool>] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]]
```
### Parameters
| Name | Type | Required | Default Value | Description |
| :--- | :--- | :------- | :------------ | :---------- |
| BestEffort | switch | False |  |  |
| Confirm | switch | False |  |  |
| CrashDumpSR | XenRef[SR] | False |  |  |
| DefaultSR | XenRef[SR] | False |  |  |
| GuiConfig | hashtable | False |  |  |
| HaAllowOvercommit | bool | False |  |  |
| HaHostFailuresToTolerate | long | False |  |  |
| HealthCheckConfig | hashtable | False |  |  |
| IgmpSnoopingEnabled | bool | False |  |  |
| IsPsrPending | bool | False |  |  |
| LivePatchingDisabled | bool | False |  |  |
| NameDescription | string | False |  |  |
| NameLabel | string | False |  |  |
| OtherConfig | hashtable | False |  |  |
| PassThru | switch | False |  |  |
| PolicyNoVendorDevice | bool | False |  |  |
| Pool | Pool | True |  |  |
| Ref | XenRef[Pool] | True |  |  |
| SessionOpaqueRef | string | False |  |  |
| SuspendImageSR | XenRef[SR] | False |  |  |
| Tags | string[] | False |  |  |
| UefiCertificates | string | False |  |  |
| Uuid | guid | True |  |  |
| VswitchController | string | False |  |  |
| WhatIf | switch | False |  |  |
| WlbEnabled | bool | False |  |  |
| WlbVerifyCert | bool | False |  |  |
### Procedure
None

### Inputs
```
XenAPI.Pool
XenAPI.XenRef`1[[XenAPI.Pool, XenServer, Version=8.2.3.0, Culture=neutral, PublicKeyToken=d247b8b0ac7959e9]]
System.Guid

```
### Outputs
```
XenAPI.Pool
XenAPI.Task
System.Void

```
### Links
None

### Examples

Set-XenPool [-Pool] <Pool> [-PassThru] [-NameLabel <string>] [-NameDescription <string>] [-DefaultSR <XenRef[SR]>] [-SuspendImageSR <XenRef[SR]>] [-CrashDumpSR <XenRef[SR]>] [-OtherConfig <hashtable>] [-HaAllowOvercommit <bool>] [-Tags <string[]>] [-GuiConfig <hashtable>] [-HealthCheckConfig <hashtable>] [-WlbEnabled <bool>] [-WlbVerifyCert <bool>] [-PolicyNoVendorDevice <bool>] [-LivePatchingDisabled <bool>] [-UefiCertificates <string>] [-IsPsrPending <bool>] [-HaHostFailuresToTolerate <long>] [-VswitchController <string>] [-IgmpSnoopingEnabled <bool>] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [<CommonParameters>]

Set-XenPool [-Ref] <XenRef[Pool]> [-PassThru] [-NameLabel <string>] [-NameDescription <string>] [-DefaultSR <XenRef[SR]>] [-SuspendImageSR <XenRef[SR]>] [-CrashDumpSR <XenRef[SR]>] [-OtherConfig <hashtable>] [-HaAllowOvercommit <bool>] [-Tags <string[]>] [-GuiConfig <hashtable>] [-HealthCheckConfig <hashtable>] [-WlbEnabled <bool>] [-WlbVerifyCert <bool>] [-PolicyNoVendorDevice <bool>] [-LivePatchingDisabled <bool>] [-UefiCertificates <string>] [-IsPsrPending <bool>] [-HaHostFailuresToTolerate <long>] [-VswitchController <string>] [-IgmpSnoopingEnabled <bool>] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [<CommonParameters>]

Set-XenPool [-Uuid] <guid> [-PassThru] [-NameLabel <string>] [-NameDescription <string>] [-DefaultSR <XenRef[SR]>] [-SuspendImageSR <XenRef[SR]>] [-CrashDumpSR <XenRef[SR]>] [-OtherConfig <hashtable>] [-HaAllowOvercommit <bool>] [-Tags <string[]>] [-GuiConfig <hashtable>] [-HealthCheckConfig <hashtable>] [-WlbEnabled <bool>] [-WlbVerifyCert <bool>] [-PolicyNoVendorDevice <bool>] [-LivePatchingDisabled <bool>] [-UefiCertificates <string>] [-IsPsrPending <bool>] [-HaHostFailuresToTolerate <long>] [-VswitchController <string>] [-IgmpSnoopingEnabled <bool>] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [<CommonParameters>]


## Set-XenPoolPatch

### Synopsis
None

### Description
None

### Syntax
```
Set-XenPoolPatch [-PoolPatch] <Pool_patch> [[-PassThru]] [[-OtherConfig] <hashtable>] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]] [-Ref] <XenRef[Pool_patch]> [[-PassThru]] [[-OtherConfig] <hashtable>] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]] [-Uuid] <guid> [[-PassThru]] [[-OtherConfig] <hashtable>] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]] [-Name] <string> [[-PassThru]] [[-OtherConfig] <hashtable>] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]]
```
### Parameters
| Name | Type | Required | Default Value | Description |
| :--- | :--- | :------- | :------------ | :---------- |
| BestEffort | switch | False |  |  |
| Confirm | switch | False |  |  |
| Name | string | True |  |  |
| OtherConfig | hashtable | False |  |  |
| PassThru | switch | False |  |  |
| PoolPatch | Pool_patch | True |  |  |
| Ref | XenRef[Pool_patch] | True |  |  |
| SessionOpaqueRef | string | False |  |  |
| Uuid | guid | True |  |  |
| WhatIf | switch | False |  |  |
### Procedure
None

### Inputs
```
XenAPI.Pool_patch
XenAPI.XenRef`1[[XenAPI.Pool_patch, XenServer, Version=8.2.3.0, Culture=neutral, PublicKeyToken=d247b8b0ac7959e9]]
System.Guid
System.String

```
### Outputs
```
XenAPI.Pool_patch
System.Void

```
### Links
None

### Examples

Set-XenPoolPatch [-PoolPatch] <Pool_patch> [-PassThru] [-OtherConfig <hashtable>] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [<CommonParameters>]

Set-XenPoolPatch [-Ref] <XenRef[Pool_patch]> [-PassThru] [-OtherConfig <hashtable>] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [<CommonParameters>]

Set-XenPoolPatch [-Uuid] <guid> [-PassThru] [-OtherConfig <hashtable>] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [<CommonParameters>]

Set-XenPoolPatch [-Name] <string> [-PassThru] [-OtherConfig <hashtable>] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [<CommonParameters>]


## Set-XenPoolUpdate

### Synopsis
None

### Description
None

### Syntax
```
Set-XenPoolUpdate [-PoolUpdate] <Pool_update> [[-PassThru]] [[-OtherConfig] <hashtable>] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]] [-Ref] <XenRef[Pool_update]> [[-PassThru]] [[-OtherConfig] <hashtable>] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]] [-Uuid] <guid> [[-PassThru]] [[-OtherConfig] <hashtable>] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]] [-Name] <string> [[-PassThru]] [[-OtherConfig] <hashtable>] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]]
```
### Parameters
| Name | Type | Required | Default Value | Description |
| :--- | :--- | :------- | :------------ | :---------- |
| BestEffort | switch | False |  |  |
| Confirm | switch | False |  |  |
| Name | string | True |  |  |
| OtherConfig | hashtable | False |  |  |
| PassThru | switch | False |  |  |
| PoolUpdate | Pool_update | True |  |  |
| Ref | XenRef[Pool_update] | True |  |  |
| SessionOpaqueRef | string | False |  |  |
| Uuid | guid | True |  |  |
| WhatIf | switch | False |  |  |
### Procedure
None

### Inputs
```
XenAPI.Pool_update
XenAPI.XenRef`1[[XenAPI.Pool_update, XenServer, Version=8.2.3.0, Culture=neutral, PublicKeyToken=d247b8b0ac7959e9]]
System.Guid
System.String

```
### Outputs
```
XenAPI.Pool_update
System.Void

```
### Links
None

### Examples

Set-XenPoolUpdate [-PoolUpdate] <Pool_update> [-PassThru] [-OtherConfig <hashtable>] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [<CommonParameters>]

Set-XenPoolUpdate [-Ref] <XenRef[Pool_update]> [-PassThru] [-OtherConfig <hashtable>] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [<CommonParameters>]

Set-XenPoolUpdate [-Uuid] <guid> [-PassThru] [-OtherConfig <hashtable>] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [<CommonParameters>]

Set-XenPoolUpdate [-Name] <string> [-PassThru] [-OtherConfig <hashtable>] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [<CommonParameters>]


## Set-XenPUSB

### Synopsis
None

### Description
None

### Syntax
```
Set-XenPUSB [-PUSB] <PUSB> [[-PassThru]] [[-OtherConfig] <hashtable>] [[-PassthroughEnabled] <bool>] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]] [-Ref] <XenRef[PUSB]> [[-PassThru]] [[-OtherConfig] <hashtable>] [[-PassthroughEnabled] <bool>] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]] [-Uuid] <guid> [[-PassThru]] [[-OtherConfig] <hashtable>] [[-PassthroughEnabled] <bool>] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]]
```
### Parameters
| Name | Type | Required | Default Value | Description |
| :--- | :--- | :------- | :------------ | :---------- |
| BestEffort | switch | False |  |  |
| Confirm | switch | False |  |  |
| OtherConfig | hashtable | False |  |  |
| PUSB | PUSB | True |  |  |
| PassThru | switch | False |  |  |
| PassthroughEnabled | bool | False |  |  |
| Ref | XenRef[PUSB] | True |  |  |
| SessionOpaqueRef | string | False |  |  |
| Uuid | guid | True |  |  |
| WhatIf | switch | False |  |  |
### Procedure
None

### Inputs
```
XenAPI.PUSB
XenAPI.XenRef`1[[XenAPI.PUSB, XenServer, Version=8.2.3.0, Culture=neutral, PublicKeyToken=d247b8b0ac7959e9]]
System.Guid

```
### Outputs
```
XenAPI.PUSB
XenAPI.Task
System.Void

```
### Links
None

### Examples

Set-XenPUSB [-PUSB] <PUSB> [-PassThru] [-OtherConfig <hashtable>] [-PassthroughEnabled <bool>] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [<CommonParameters>]

Set-XenPUSB [-Ref] <XenRef[PUSB]> [-PassThru] [-OtherConfig <hashtable>] [-PassthroughEnabled <bool>] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [<CommonParameters>]

Set-XenPUSB [-Uuid] <guid> [-PassThru] [-OtherConfig <hashtable>] [-PassthroughEnabled <bool>] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [<CommonParameters>]


## Set-XenPVSSite

### Synopsis
None

### Description
None

### Syntax
```
Set-XenPVSSite [-PVSSite] <PVS_site> [[-PassThru]] [[-NameLabel] <string>] [[-NameDescription] <string>] [[-PVSUuid] <string>] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]] [-Ref] <XenRef[PVS_site]> [[-PassThru]] [[-NameLabel] <string>] [[-NameDescription] <string>] [[-PVSUuid] <string>] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]] [-Uuid] <guid> [[-PassThru]] [[-NameLabel] <string>] [[-NameDescription] <string>] [[-PVSUuid] <string>] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]] [-Name] <string> [[-PassThru]] [[-NameLabel] <string>] [[-NameDescription] <string>] [[-PVSUuid] <string>] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]]
```
### Parameters
| Name | Type | Required | Default Value | Description |
| :--- | :--- | :------- | :------------ | :---------- |
| BestEffort | switch | False |  |  |
| Confirm | switch | False |  |  |
| Name | string | True |  |  |
| NameDescription | string | False |  |  |
| NameLabel | string | False |  |  |
| PVSSite | PVS_site | True |  |  |
| PVSUuid | string | False |  |  |
| PassThru | switch | False |  |  |
| Ref | XenRef[PVS_site] | True |  |  |
| SessionOpaqueRef | string | False |  |  |
| Uuid | guid | True |  |  |
| WhatIf | switch | False |  |  |
### Procedure
None

### Inputs
```
XenAPI.PVS_site
XenAPI.XenRef`1[[XenAPI.PVS_site, XenServer, Version=8.2.3.0, Culture=neutral, PublicKeyToken=d247b8b0ac7959e9]]
System.Guid
System.String

```
### Outputs
```
XenAPI.PVS_site
XenAPI.Task
System.Void

```
### Links
None

### Examples

Set-XenPVSSite [-PVSSite] <PVS_site> [-PassThru] [-NameLabel <string>] [-NameDescription <string>] [-PVSUuid <string>] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [<CommonParameters>]

Set-XenPVSSite [-Ref] <XenRef[PVS_site]> [-PassThru] [-NameLabel <string>] [-NameDescription <string>] [-PVSUuid <string>] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [<CommonParameters>]

Set-XenPVSSite [-Uuid] <guid> [-PassThru] [-NameLabel <string>] [-NameDescription <string>] [-PVSUuid <string>] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [<CommonParameters>]

Set-XenPVSSite [-Name] <string> [-PassThru] [-NameLabel <string>] [-NameDescription <string>] [-PVSUuid <string>] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [<CommonParameters>]


## Set-XenSecret

### Synopsis
None

### Description
None

### Syntax
```
Set-XenSecret [-Secret] <Secret> [[-PassThru]] [[-Value] <string>] [[-OtherConfig] <hashtable>] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]] [-Ref] <XenRef[Secret]> [[-PassThru]] [[-Value] <string>] [[-OtherConfig] <hashtable>] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]] [-Uuid] <guid> [[-PassThru]] [[-Value] <string>] [[-OtherConfig] <hashtable>] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]]
```
### Parameters
| Name | Type | Required | Default Value | Description |
| :--- | :--- | :------- | :------------ | :---------- |
| BestEffort | switch | False |  |  |
| Confirm | switch | False |  |  |
| OtherConfig | hashtable | False |  |  |
| PassThru | switch | False |  |  |
| Ref | XenRef[Secret] | True |  |  |
| Secret | Secret | True |  |  |
| SessionOpaqueRef | string | False |  |  |
| Uuid | guid | True |  |  |
| Value | string | False |  |  |
| WhatIf | switch | False |  |  |
### Procedure
None

### Inputs
```
XenAPI.Secret
XenAPI.XenRef`1[[XenAPI.Secret, XenServer, Version=8.2.3.0, Culture=neutral, PublicKeyToken=d247b8b0ac7959e9]]
System.Guid

```
### Outputs
```
XenAPI.Secret
System.Void

```
### Links
None

### Examples

Set-XenSecret [-Secret] <Secret> [-PassThru] [-Value <string>] [-OtherConfig <hashtable>] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [<CommonParameters>]

Set-XenSecret [-Ref] <XenRef[Secret]> [-PassThru] [-Value <string>] [-OtherConfig <hashtable>] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [<CommonParameters>]

Set-XenSecret [-Uuid] <guid> [-PassThru] [-Value <string>] [-OtherConfig <hashtable>] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [<CommonParameters>]


## Set-XenSM

### Synopsis
None

### Description
None

### Syntax
```
Set-XenSM [-SM] <SM> [[-PassThru]] [[-OtherConfig] <hashtable>] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]] [-Ref] <XenRef[SM]> [[-PassThru]] [[-OtherConfig] <hashtable>] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]] [-Uuid] <guid> [[-PassThru]] [[-OtherConfig] <hashtable>] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]] [-Name] <string> [[-PassThru]] [[-OtherConfig] <hashtable>] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]]
```
### Parameters
| Name | Type | Required | Default Value | Description |
| :--- | :--- | :------- | :------------ | :---------- |
| BestEffort | switch | False |  |  |
| Confirm | switch | False |  |  |
| Name | string | True |  |  |
| OtherConfig | hashtable | False |  |  |
| PassThru | switch | False |  |  |
| Ref | XenRef[SM] | True |  |  |
| SM | SM | True |  |  |
| SessionOpaqueRef | string | False |  |  |
| Uuid | guid | True |  |  |
| WhatIf | switch | False |  |  |
### Procedure
None

### Inputs
```
XenAPI.SM
XenAPI.XenRef`1[[XenAPI.SM, XenServer, Version=8.2.3.0, Culture=neutral, PublicKeyToken=d247b8b0ac7959e9]]
System.Guid
System.String

```
### Outputs
```
XenAPI.SM
System.Void

```
### Links
None

### Examples

Set-XenSM [-SM] <SM> [-PassThru] [-OtherConfig <hashtable>] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [<CommonParameters>]

Set-XenSM [-Ref] <XenRef[SM]> [-PassThru] [-OtherConfig <hashtable>] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [<CommonParameters>]

Set-XenSM [-Uuid] <guid> [-PassThru] [-OtherConfig <hashtable>] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [<CommonParameters>]

Set-XenSM [-Name] <string> [-PassThru] [-OtherConfig <hashtable>] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [<CommonParameters>]


## Set-XenSR

### Synopsis
None

### Description
None

### Syntax
```
Set-XenSR [-SR] <SR> [[-PassThru]] [[-OtherConfig] <hashtable>] [[-Tags] <string[]>] [[-SmConfig] <hashtable>] [[-Shared] <bool>] [[-NameLabel] <string>] [[-NameDescription] <string>] [[-PhysicalSize] <long>] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]] [-Ref] <XenRef[SR]> [[-PassThru]] [[-OtherConfig] <hashtable>] [[-Tags] <string[]>] [[-SmConfig] <hashtable>] [[-Shared] <bool>] [[-NameLabel] <string>] [[-NameDescription] <string>] [[-PhysicalSize] <long>] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]] [-Uuid] <guid> [[-PassThru]] [[-OtherConfig] <hashtable>] [[-Tags] <string[]>] [[-SmConfig] <hashtable>] [[-Shared] <bool>] [[-NameLabel] <string>] [[-NameDescription] <string>] [[-PhysicalSize] <long>] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]] [-Name] <string> [[-PassThru]] [[-OtherConfig] <hashtable>] [[-Tags] <string[]>] [[-SmConfig] <hashtable>] [[-Shared] <bool>] [[-NameLabel] <string>] [[-NameDescription] <string>] [[-PhysicalSize] <long>] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]]
```
### Parameters
| Name | Type | Required | Default Value | Description |
| :--- | :--- | :------- | :------------ | :---------- |
| BestEffort | switch | False |  |  |
| Confirm | switch | False |  |  |
| Name | string | True |  |  |
| NameDescription | string | False |  |  |
| NameLabel | string | False |  |  |
| OtherConfig | hashtable | False |  |  |
| PassThru | switch | False |  |  |
| PhysicalSize | long | False |  |  |
| Ref | XenRef[SR] | True |  |  |
| SR | SR | True |  |  |
| SessionOpaqueRef | string | False |  |  |
| Shared | bool | False |  |  |
| SmConfig | hashtable | False |  |  |
| Tags | string[] | False |  |  |
| Uuid | guid | True |  |  |
| WhatIf | switch | False |  |  |
### Procedure
None

### Inputs
```
XenAPI.SR
XenAPI.XenRef`1[[XenAPI.SR, XenServer, Version=8.2.3.0, Culture=neutral, PublicKeyToken=d247b8b0ac7959e9]]
System.Guid
System.String

```
### Outputs
```
XenAPI.SR
XenAPI.Task
System.Void

```
### Links
None

### Examples

Set-XenSR [-SR] <SR> [-PassThru] [-OtherConfig <hashtable>] [-Tags <string[]>] [-SmConfig <hashtable>] [-Shared <bool>] [-NameLabel <string>] [-NameDescription <string>] [-PhysicalSize <long>] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [<CommonParameters>]

Set-XenSR [-Ref] <XenRef[SR]> [-PassThru] [-OtherConfig <hashtable>] [-Tags <string[]>] [-SmConfig <hashtable>] [-Shared <bool>] [-NameLabel <string>] [-NameDescription <string>] [-PhysicalSize <long>] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [<CommonParameters>]

Set-XenSR [-Uuid] <guid> [-PassThru] [-OtherConfig <hashtable>] [-Tags <string[]>] [-SmConfig <hashtable>] [-Shared <bool>] [-NameLabel <string>] [-NameDescription <string>] [-PhysicalSize <long>] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [<CommonParameters>]

Set-XenSR [-Name] <string> [-PassThru] [-OtherConfig <hashtable>] [-Tags <string[]>] [-SmConfig <hashtable>] [-Shared <bool>] [-NameLabel <string>] [-NameDescription <string>] [-PhysicalSize <long>] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [<CommonParameters>]


## Set-XenTask

### Synopsis
None

### Description
None

### Syntax
```
Set-XenTask [-Task] <Task> [[-PassThru]] [[-OtherConfig] <hashtable>] [[-Status] <task_status_type>] [[-Progress] <double>] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]] [-Ref] <XenRef[Task]> [[-PassThru]] [[-OtherConfig] <hashtable>] [[-Status] <task_status_type>] [[-Progress] <double>] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]] [-Uuid] <guid> [[-PassThru]] [[-OtherConfig] <hashtable>] [[-Status] <task_status_type>] [[-Progress] <double>] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]] [-Name] <string> [[-PassThru]] [[-OtherConfig] <hashtable>] [[-Status] <task_status_type>] [[-Progress] <double>] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]]
```
### Parameters
| Name | Type | Required | Default Value | Description |
| :--- | :--- | :------- | :------------ | :---------- |
| BestEffort | switch | False |  |  |
| Confirm | switch | False |  |  |
| Name | string | True |  |  |
| OtherConfig | hashtable | False |  |  |
| PassThru | switch | False |  |  |
| Progress | double | False |  |  |
| Ref | XenRef[Task] | True |  |  |
| SessionOpaqueRef | string | False |  |  |
| Status | task_status_type | False |  |  |
| Task | Task | True |  |  |
| Uuid | guid | True |  |  |
| WhatIf | switch | False |  |  |
### Procedure
None

### Inputs
```
XenAPI.Task
XenAPI.XenRef`1[[XenAPI.Task, XenServer, Version=8.2.3.0, Culture=neutral, PublicKeyToken=d247b8b0ac7959e9]]
System.Guid
System.String

```
### Outputs
```
XenAPI.Task
System.Void

```
### Links
None

### Examples

Set-XenTask [-Task] <Task> [-PassThru] [-OtherConfig <hashtable>] [-Status <task_status_type>] [-Progress <double>] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [<CommonParameters>]

Set-XenTask [-Ref] <XenRef[Task]> [-PassThru] [-OtherConfig <hashtable>] [-Status <task_status_type>] [-Progress <double>] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [<CommonParameters>]

Set-XenTask [-Uuid] <guid> [-PassThru] [-OtherConfig <hashtable>] [-Status <task_status_type>] [-Progress <double>] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [<CommonParameters>]

Set-XenTask [-Name] <string> [-PassThru] [-OtherConfig <hashtable>] [-Status <task_status_type>] [-Progress <double>] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [<CommonParameters>]


## Set-XenTunnel

### Synopsis
None

### Description
None

### Syntax
```
Set-XenTunnel [-Tunnel] <Tunnel> [[-PassThru]] [[-Status] <hashtable>] [[-OtherConfig] <hashtable>] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]] [-Ref] <XenRef[Tunnel]> [[-PassThru]] [[-Status] <hashtable>] [[-OtherConfig] <hashtable>] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]] [-Uuid] <guid> [[-PassThru]] [[-Status] <hashtable>] [[-OtherConfig] <hashtable>] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]]
```
### Parameters
| Name | Type | Required | Default Value | Description |
| :--- | :--- | :------- | :------------ | :---------- |
| BestEffort | switch | False |  |  |
| Confirm | switch | False |  |  |
| OtherConfig | hashtable | False |  |  |
| PassThru | switch | False |  |  |
| Ref | XenRef[Tunnel] | True |  |  |
| SessionOpaqueRef | string | False |  |  |
| Status | hashtable | False |  |  |
| Tunnel | Tunnel | True |  |  |
| Uuid | guid | True |  |  |
| WhatIf | switch | False |  |  |
### Procedure
None

### Inputs
```
XenAPI.Tunnel
XenAPI.XenRef`1[[XenAPI.Tunnel, XenServer, Version=8.2.3.0, Culture=neutral, PublicKeyToken=d247b8b0ac7959e9]]
System.Guid

```
### Outputs
```
XenAPI.Tunnel
System.Void

```
### Links
None

### Examples

Set-XenTunnel [-Tunnel] <Tunnel> [-PassThru] [-Status <hashtable>] [-OtherConfig <hashtable>] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [<CommonParameters>]

Set-XenTunnel [-Ref] <XenRef[Tunnel]> [-PassThru] [-Status <hashtable>] [-OtherConfig <hashtable>] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [<CommonParameters>]

Set-XenTunnel [-Uuid] <guid> [-PassThru] [-Status <hashtable>] [-OtherConfig <hashtable>] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [<CommonParameters>]


## Set-XenUSBGroup

### Synopsis
None

### Description
None

### Syntax
```
Set-XenUSBGroup [-USBGroup] <USB_group> [[-PassThru]] [[-NameLabel] <string>] [[-NameDescription] <string>] [[-OtherConfig] <hashtable>] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]] [-Ref] <XenRef[USB_group]> [[-PassThru]] [[-NameLabel] <string>] [[-NameDescription] <string>] [[-OtherConfig] <hashtable>] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]] [-Uuid] <guid> [[-PassThru]] [[-NameLabel] <string>] [[-NameDescription] <string>] [[-OtherConfig] <hashtable>] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]] [-Name] <string> [[-PassThru]] [[-NameLabel] <string>] [[-NameDescription] <string>] [[-OtherConfig] <hashtable>] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]]
```
### Parameters
| Name | Type | Required | Default Value | Description |
| :--- | :--- | :------- | :------------ | :---------- |
| BestEffort | switch | False |  |  |
| Confirm | switch | False |  |  |
| Name | string | True |  |  |
| NameDescription | string | False |  |  |
| NameLabel | string | False |  |  |
| OtherConfig | hashtable | False |  |  |
| PassThru | switch | False |  |  |
| Ref | XenRef[USB_group] | True |  |  |
| SessionOpaqueRef | string | False |  |  |
| USBGroup | USB_group | True |  |  |
| Uuid | guid | True |  |  |
| WhatIf | switch | False |  |  |
### Procedure
None

### Inputs
```
XenAPI.USB_group
XenAPI.XenRef`1[[XenAPI.USB_group, XenServer, Version=8.2.3.0, Culture=neutral, PublicKeyToken=d247b8b0ac7959e9]]
System.Guid
System.String

```
### Outputs
```
XenAPI.USB_group
System.Void

```
### Links
None

### Examples

Set-XenUSBGroup [-USBGroup] <USB_group> [-PassThru] [-NameLabel <string>] [-NameDescription <string>] [-OtherConfig <hashtable>] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [<CommonParameters>]

Set-XenUSBGroup [-Ref] <XenRef[USB_group]> [-PassThru] [-NameLabel <string>] [-NameDescription <string>] [-OtherConfig <hashtable>] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [<CommonParameters>]

Set-XenUSBGroup [-Uuid] <guid> [-PassThru] [-NameLabel <string>] [-NameDescription <string>] [-OtherConfig <hashtable>] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [<CommonParameters>]

Set-XenUSBGroup [-Name] <string> [-PassThru] [-NameLabel <string>] [-NameDescription <string>] [-OtherConfig <hashtable>] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [<CommonParameters>]


## Set-XenUser

### Synopsis
None

### Description
None

### Syntax
```
Set-XenUser [-User] <User> [[-PassThru]] [[-Fullname] <string>] [[-OtherConfig] <hashtable>] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]] [-Ref] <XenRef[User]> [[-PassThru]] [[-Fullname] <string>] [[-OtherConfig] <hashtable>] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]] [-Uuid] <guid> [[-PassThru]] [[-Fullname] <string>] [[-OtherConfig] <hashtable>] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]]
```
### Parameters
| Name | Type | Required | Default Value | Description |
| :--- | :--- | :------- | :------------ | :---------- |
| BestEffort | switch | False |  |  |
| Confirm | switch | False |  |  |
| Fullname | string | False |  |  |
| OtherConfig | hashtable | False |  |  |
| PassThru | switch | False |  |  |
| Ref | XenRef[User] | True |  |  |
| SessionOpaqueRef | string | False |  |  |
| User | User | True |  |  |
| Uuid | guid | True |  |  |
| WhatIf | switch | False |  |  |
### Procedure
None

### Inputs
```
XenAPI.User
XenAPI.XenRef`1[[XenAPI.User, XenServer, Version=8.2.3.0, Culture=neutral, PublicKeyToken=d247b8b0ac7959e9]]
System.Guid

```
### Outputs
```
XenAPI.User
System.Void

```
### Links
None

### Examples

Set-XenUser [-User] <User> [-PassThru] [-Fullname <string>] [-OtherConfig <hashtable>] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [<CommonParameters>]

Set-XenUser [-Ref] <XenRef[User]> [-PassThru] [-Fullname <string>] [-OtherConfig <hashtable>] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [<CommonParameters>]

Set-XenUser [-Uuid] <guid> [-PassThru] [-Fullname <string>] [-OtherConfig <hashtable>] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [<CommonParameters>]


## Set-XenVBD

### Synopsis
None

### Description
None

### Syntax
```
Set-XenVBD [-VBD] <VBD> [[-PassThru]] [[-Userdevice] <string>] [[-Bootable] <bool>] [[-Type] <vbd_type>] [[-Unpluggable] <bool>] [[-OtherConfig] <hashtable>] [[-QosAlgorithmType] <string>] [[-QosAlgorithmParams] <hashtable>] [[-Mode] <vbd_mode>] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]] [-Ref] <XenRef[VBD]> [[-PassThru]] [[-Userdevice] <string>] [[-Bootable] <bool>] [[-Type] <vbd_type>] [[-Unpluggable] <bool>] [[-OtherConfig] <hashtable>] [[-QosAlgorithmType] <string>] [[-QosAlgorithmParams] <hashtable>] [[-Mode] <vbd_mode>] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]] [-Uuid] <guid> [[-PassThru]] [[-Userdevice] <string>] [[-Bootable] <bool>] [[-Type] <vbd_type>] [[-Unpluggable] <bool>] [[-OtherConfig] <hashtable>] [[-QosAlgorithmType] <string>] [[-QosAlgorithmParams] <hashtable>] [[-Mode] <vbd_mode>] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]]
```
### Parameters
| Name | Type | Required | Default Value | Description |
| :--- | :--- | :------- | :------------ | :---------- |
| BestEffort | switch | False |  |  |
| Bootable | bool | False |  |  |
| Confirm | switch | False |  |  |
| Mode | vbd_mode | False |  |  |
| OtherConfig | hashtable | False |  |  |
| PassThru | switch | False |  |  |
| QosAlgorithmParams | hashtable | False |  |  |
| QosAlgorithmType | string | False |  |  |
| Ref | XenRef[VBD] | True |  |  |
| SessionOpaqueRef | string | False |  |  |
| Type | vbd_type | False |  |  |
| Unpluggable | bool | False |  |  |
| Userdevice | string | False |  |  |
| Uuid | guid | True |  |  |
| VBD | VBD | True |  |  |
| WhatIf | switch | False |  |  |
### Procedure
None

### Inputs
```
XenAPI.VBD
XenAPI.XenRef`1[[XenAPI.VBD, XenServer, Version=8.2.3.0, Culture=neutral, PublicKeyToken=d247b8b0ac7959e9]]
System.Guid

```
### Outputs
```
XenAPI.VBD
XenAPI.Task
System.Void

```
### Links
None

### Examples

Set-XenVBD [-VBD] <VBD> [-PassThru] [-Userdevice <string>] [-Bootable <bool>] [-Type <vbd_type>] [-Unpluggable <bool>] [-OtherConfig <hashtable>] [-QosAlgorithmType <string>] [-QosAlgorithmParams <hashtable>] [-Mode <vbd_mode>] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [<CommonParameters>]

Set-XenVBD [-Ref] <XenRef[VBD]> [-PassThru] [-Userdevice <string>] [-Bootable <bool>] [-Type <vbd_type>] [-Unpluggable <bool>] [-OtherConfig <hashtable>] [-QosAlgorithmType <string>] [-QosAlgorithmParams <hashtable>] [-Mode <vbd_mode>] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [<CommonParameters>]

Set-XenVBD [-Uuid] <guid> [-PassThru] [-Userdevice <string>] [-Bootable <bool>] [-Type <vbd_type>] [-Unpluggable <bool>] [-OtherConfig <hashtable>] [-QosAlgorithmType <string>] [-QosAlgorithmParams <hashtable>] [-Mode <vbd_mode>] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [<CommonParameters>]


## Set-XenVBDMetrics

### Synopsis
None

### Description
None

### Syntax
```
Set-XenVBDMetrics [-VBDMetrics] <VBD_metrics> [[-PassThru]] [[-OtherConfig] <hashtable>] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]] [-Ref] <XenRef[VBD_metrics]> [[-PassThru]] [[-OtherConfig] <hashtable>] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]] [-Uuid] <guid> [[-PassThru]] [[-OtherConfig] <hashtable>] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]]
```
### Parameters
| Name | Type | Required | Default Value | Description |
| :--- | :--- | :------- | :------------ | :---------- |
| BestEffort | switch | False |  |  |
| Confirm | switch | False |  |  |
| OtherConfig | hashtable | False |  |  |
| PassThru | switch | False |  |  |
| Ref | XenRef[VBD_metrics] | True |  |  |
| SessionOpaqueRef | string | False |  |  |
| Uuid | guid | True |  |  |
| VBDMetrics | VBD_metrics | True |  |  |
| WhatIf | switch | False |  |  |
### Procedure
None

### Inputs
```
XenAPI.VBD_metrics
XenAPI.XenRef`1[[XenAPI.VBD_metrics, XenServer, Version=8.2.3.0, Culture=neutral, PublicKeyToken=d247b8b0ac7959e9]]
System.Guid

```
### Outputs
```
XenAPI.VBD_metrics
System.Void

```
### Links
None

### Examples

Set-XenVBDMetrics [-VBDMetrics] <VBD_metrics> [-PassThru] [-OtherConfig <hashtable>] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [<CommonParameters>]

Set-XenVBDMetrics [-Ref] <XenRef[VBD_metrics]> [-PassThru] [-OtherConfig <hashtable>] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [<CommonParameters>]

Set-XenVBDMetrics [-Uuid] <guid> [-PassThru] [-OtherConfig <hashtable>] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [<CommonParameters>]


## Set-XenVDI

### Synopsis
None

### Description
None

### Syntax
```
Set-XenVDI [-VDI] <VDI> [[-PassThru]] [[-OtherConfig] <hashtable>] [[-XenstoreData] <hashtable>] [[-SmConfig] <hashtable>] [[-Tags] <string[]>] [[-Sharable] <bool>] [[-ReadOnly] <bool>] [[-NameLabel] <string>] [[-NameDescription] <string>] [[-OnBoot] <on_boot>] [[-AllowCaching] <bool>] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]] [-Ref] <XenRef[VDI]> [[-PassThru]] [[-OtherConfig] <hashtable>] [[-XenstoreData] <hashtable>] [[-SmConfig] <hashtable>] [[-Tags] <string[]>] [[-Sharable] <bool>] [[-ReadOnly] <bool>] [[-NameLabel] <string>] [[-NameDescription] <string>] [[-OnBoot] <on_boot>] [[-AllowCaching] <bool>] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]] [-Uuid] <guid> [[-PassThru]] [[-OtherConfig] <hashtable>] [[-XenstoreData] <hashtable>] [[-SmConfig] <hashtable>] [[-Tags] <string[]>] [[-Sharable] <bool>] [[-ReadOnly] <bool>] [[-NameLabel] <string>] [[-NameDescription] <string>] [[-OnBoot] <on_boot>] [[-AllowCaching] <bool>] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]] [-Name] <string> [[-PassThru]] [[-OtherConfig] <hashtable>] [[-XenstoreData] <hashtable>] [[-SmConfig] <hashtable>] [[-Tags] <string[]>] [[-Sharable] <bool>] [[-ReadOnly] <bool>] [[-NameLabel] <string>] [[-NameDescription] <string>] [[-OnBoot] <on_boot>] [[-AllowCaching] <bool>] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]]
```
### Parameters
| Name | Type | Required | Default Value | Description |
| :--- | :--- | :------- | :------------ | :---------- |
| AllowCaching | bool | False |  |  |
| BestEffort | switch | False |  |  |
| Confirm | switch | False |  |  |
| Name | string | True |  |  |
| NameDescription | string | False |  |  |
| NameLabel | string | False |  |  |
| OnBoot | on_boot | False |  |  |
| OtherConfig | hashtable | False |  |  |
| PassThru | switch | False |  |  |
| ReadOnly | bool | False |  |  |
| Ref | XenRef[VDI] | True |  |  |
| SessionOpaqueRef | string | False |  |  |
| Sharable | bool | False |  |  |
| SmConfig | hashtable | False |  |  |
| Tags | string[] | False |  |  |
| Uuid | guid | True |  |  |
| VDI | VDI | True |  |  |
| WhatIf | switch | False |  |  |
| XenstoreData | hashtable | False |  |  |
### Procedure
None

### Inputs
```
XenAPI.VDI
XenAPI.XenRef`1[[XenAPI.VDI, XenServer, Version=8.2.3.0, Culture=neutral, PublicKeyToken=d247b8b0ac7959e9]]
System.Guid
System.String

```
### Outputs
```
XenAPI.VDI
XenAPI.Task
System.Void

```
### Links
None

### Examples

Set-XenVDI [-VDI] <VDI> [-PassThru] [-OtherConfig <hashtable>] [-XenstoreData <hashtable>] [-SmConfig <hashtable>] [-Tags <string[]>] [-Sharable <bool>] [-ReadOnly <bool>] [-NameLabel <string>] [-NameDescription <string>] [-OnBoot <on_boot>] [-AllowCaching <bool>] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [<CommonParameters>]

Set-XenVDI [-Ref] <XenRef[VDI]> [-PassThru] [-OtherConfig <hashtable>] [-XenstoreData <hashtable>] [-SmConfig <hashtable>] [-Tags <string[]>] [-Sharable <bool>] [-ReadOnly <bool>] [-NameLabel <string>] [-NameDescription <string>] [-OnBoot <on_boot>] [-AllowCaching <bool>] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [<CommonParameters>]

Set-XenVDI [-Uuid] <guid> [-PassThru] [-OtherConfig <hashtable>] [-XenstoreData <hashtable>] [-SmConfig <hashtable>] [-Tags <string[]>] [-Sharable <bool>] [-ReadOnly <bool>] [-NameLabel <string>] [-NameDescription <string>] [-OnBoot <on_boot>] [-AllowCaching <bool>] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [<CommonParameters>]

Set-XenVDI [-Name] <string> [-PassThru] [-OtherConfig <hashtable>] [-XenstoreData <hashtable>] [-SmConfig <hashtable>] [-Tags <string[]>] [-Sharable <bool>] [-ReadOnly <bool>] [-NameLabel <string>] [-NameDescription <string>] [-OnBoot <on_boot>] [-AllowCaching <bool>] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [<CommonParameters>]


## Set-XenVGPU

### Synopsis
None

### Description
None

### Syntax
```
Set-XenVGPU [-VGPU] <VGPU> [[-PassThru]] [[-OtherConfig] <hashtable>] [[-ExtraArgs] <string>] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]] [-Ref] <XenRef[VGPU]> [[-PassThru]] [[-OtherConfig] <hashtable>] [[-ExtraArgs] <string>] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]] [-Uuid] <guid> [[-PassThru]] [[-OtherConfig] <hashtable>] [[-ExtraArgs] <string>] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]]
```
### Parameters
| Name | Type | Required | Default Value | Description |
| :--- | :--- | :------- | :------------ | :---------- |
| BestEffort | switch | False |  |  |
| Confirm | switch | False |  |  |
| ExtraArgs | string | False |  |  |
| OtherConfig | hashtable | False |  |  |
| PassThru | switch | False |  |  |
| Ref | XenRef[VGPU] | True |  |  |
| SessionOpaqueRef | string | False |  |  |
| Uuid | guid | True |  |  |
| VGPU | VGPU | True |  |  |
| WhatIf | switch | False |  |  |
### Procedure
None

### Inputs
```
XenAPI.VGPU
XenAPI.XenRef`1[[XenAPI.VGPU, XenServer, Version=8.2.3.0, Culture=neutral, PublicKeyToken=d247b8b0ac7959e9]]
System.Guid

```
### Outputs
```
XenAPI.VGPU
System.Void

```
### Links
None

### Examples

Set-XenVGPU [-VGPU] <VGPU> [-PassThru] [-OtherConfig <hashtable>] [-ExtraArgs <string>] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [<CommonParameters>]

Set-XenVGPU [-Ref] <XenRef[VGPU]> [-PassThru] [-OtherConfig <hashtable>] [-ExtraArgs <string>] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [<CommonParameters>]

Set-XenVGPU [-Uuid] <guid> [-PassThru] [-OtherConfig <hashtable>] [-ExtraArgs <string>] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [<CommonParameters>]


## Set-XenVIF

### Synopsis
None

### Description
None

### Syntax
```
Set-XenVIF [-VIF] <VIF> [[-PassThru]] [[-OtherConfig] <hashtable>] [[-QosAlgorithmType] <string>] [[-QosAlgorithmParams] <hashtable>] [[-LockingMode] <vif_locking_mode>] [[-Ipv4Allowed] <string[]>] [[-Ipv6Allowed] <string[]>] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]] [-Ref] <XenRef[VIF]> [[-PassThru]] [[-OtherConfig] <hashtable>] [[-QosAlgorithmType] <string>] [[-QosAlgorithmParams] <hashtable>] [[-LockingMode] <vif_locking_mode>] [[-Ipv4Allowed] <string[]>] [[-Ipv6Allowed] <string[]>] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]] [-Uuid] <guid> [[-PassThru]] [[-OtherConfig] <hashtable>] [[-QosAlgorithmType] <string>] [[-QosAlgorithmParams] <hashtable>] [[-LockingMode] <vif_locking_mode>] [[-Ipv4Allowed] <string[]>] [[-Ipv6Allowed] <string[]>] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]]
```
### Parameters
| Name | Type | Required | Default Value | Description |
| :--- | :--- | :------- | :------------ | :---------- |
| BestEffort | switch | False |  |  |
| Confirm | switch | False |  |  |
| Ipv4Allowed | string[] | False |  |  |
| Ipv6Allowed | string[] | False |  |  |
| LockingMode | vif_locking_mode | False |  |  |
| OtherConfig | hashtable | False |  |  |
| PassThru | switch | False |  |  |
| QosAlgorithmParams | hashtable | False |  |  |
| QosAlgorithmType | string | False |  |  |
| Ref | XenRef[VIF] | True |  |  |
| SessionOpaqueRef | string | False |  |  |
| Uuid | guid | True |  |  |
| VIF | VIF | True |  |  |
| WhatIf | switch | False |  |  |
### Procedure
None

### Inputs
```
XenAPI.VIF
XenAPI.XenRef`1[[XenAPI.VIF, XenServer, Version=8.2.3.0, Culture=neutral, PublicKeyToken=d247b8b0ac7959e9]]
System.Guid

```
### Outputs
```
XenAPI.VIF
XenAPI.Task
System.Void

```
### Links
None

### Examples

Set-XenVIF [-VIF] <VIF> [-PassThru] [-OtherConfig <hashtable>] [-QosAlgorithmType <string>] [-QosAlgorithmParams <hashtable>] [-LockingMode <vif_locking_mode>] [-Ipv4Allowed <string[]>] [-Ipv6Allowed <string[]>] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [<CommonParameters>]

Set-XenVIF [-Ref] <XenRef[VIF]> [-PassThru] [-OtherConfig <hashtable>] [-QosAlgorithmType <string>] [-QosAlgorithmParams <hashtable>] [-LockingMode <vif_locking_mode>] [-Ipv4Allowed <string[]>] [-Ipv6Allowed <string[]>] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [<CommonParameters>]

Set-XenVIF [-Uuid] <guid> [-PassThru] [-OtherConfig <hashtable>] [-QosAlgorithmType <string>] [-QosAlgorithmParams <hashtable>] [-LockingMode <vif_locking_mode>] [-Ipv4Allowed <string[]>] [-Ipv6Allowed <string[]>] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [<CommonParameters>]


## Set-XenVIFMetrics

### Synopsis
None

### Description
None

### Syntax
```
Set-XenVIFMetrics [-VIFMetrics] <VIF_metrics> [[-PassThru]] [[-OtherConfig] <hashtable>] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]] [-Ref] <XenRef[VIF_metrics]> [[-PassThru]] [[-OtherConfig] <hashtable>] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]] [-Uuid] <guid> [[-PassThru]] [[-OtherConfig] <hashtable>] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]]
```
### Parameters
| Name | Type | Required | Default Value | Description |
| :--- | :--- | :------- | :------------ | :---------- |
| BestEffort | switch | False |  |  |
| Confirm | switch | False |  |  |
| OtherConfig | hashtable | False |  |  |
| PassThru | switch | False |  |  |
| Ref | XenRef[VIF_metrics] | True |  |  |
| SessionOpaqueRef | string | False |  |  |
| Uuid | guid | True |  |  |
| VIFMetrics | VIF_metrics | True |  |  |
| WhatIf | switch | False |  |  |
### Procedure
None

### Inputs
```
XenAPI.VIF_metrics
XenAPI.XenRef`1[[XenAPI.VIF_metrics, XenServer, Version=8.2.3.0, Culture=neutral, PublicKeyToken=d247b8b0ac7959e9]]
System.Guid

```
### Outputs
```
XenAPI.VIF_metrics
System.Void

```
### Links
None

### Examples

Set-XenVIFMetrics [-VIFMetrics] <VIF_metrics> [-PassThru] [-OtherConfig <hashtable>] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [<CommonParameters>]

Set-XenVIFMetrics [-Ref] <XenRef[VIF_metrics]> [-PassThru] [-OtherConfig <hashtable>] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [<CommonParameters>]

Set-XenVIFMetrics [-Uuid] <guid> [-PassThru] [-OtherConfig <hashtable>] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [<CommonParameters>]


## Set-XenVLAN

### Synopsis
None

### Description
None

### Syntax
```
Set-XenVLAN [-VLAN] <VLAN> [[-PassThru]] [[-OtherConfig] <hashtable>] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]] [-Ref] <XenRef[VLAN]> [[-PassThru]] [[-OtherConfig] <hashtable>] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]] [-Uuid] <guid> [[-PassThru]] [[-OtherConfig] <hashtable>] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]]
```
### Parameters
| Name | Type | Required | Default Value | Description |
| :--- | :--- | :------- | :------------ | :---------- |
| BestEffort | switch | False |  |  |
| Confirm | switch | False |  |  |
| OtherConfig | hashtable | False |  |  |
| PassThru | switch | False |  |  |
| Ref | XenRef[VLAN] | True |  |  |
| SessionOpaqueRef | string | False |  |  |
| Uuid | guid | True |  |  |
| VLAN | VLAN | True |  |  |
| WhatIf | switch | False |  |  |
### Procedure
None

### Inputs
```
XenAPI.VLAN
XenAPI.XenRef`1[[XenAPI.VLAN, XenServer, Version=8.2.3.0, Culture=neutral, PublicKeyToken=d247b8b0ac7959e9]]
System.Guid

```
### Outputs
```
XenAPI.VLAN
System.Void

```
### Links
None

### Examples

Set-XenVLAN [-VLAN] <VLAN> [-PassThru] [-OtherConfig <hashtable>] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [<CommonParameters>]

Set-XenVLAN [-Ref] <XenRef[VLAN]> [-PassThru] [-OtherConfig <hashtable>] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [<CommonParameters>]

Set-XenVLAN [-Uuid] <guid> [-PassThru] [-OtherConfig <hashtable>] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [<CommonParameters>]


## Set-XenVM

### Synopsis
None

### Description
None

### Syntax
```
Set-XenVM [-VM] <VM> [[-PassThru]] [[-NameLabel] <string>] [[-NameDescription] <string>] [[-UserVersion] <long>] [[-IsATemplate] <bool>] [[-Affinity] <XenRef[Host]>] [[-VCPUsParams] <hashtable>] [[-ActionsAfterShutdown] <on_normal_exit>] [[-ActionsAfterReboot] <on_normal_exit>] [[-PVBootloader] <string>] [[-PVKernel] <string>] [[-PVRamdisk] <string>] [[-PVArgs] <string>] [[-PVBootloaderArgs] <string>] [[-PVLegacyArgs] <string>] [[-HVMBootParams] <hashtable>] [[-Platform] <hashtable>] [[-PCIBus] <string>] [[-OtherConfig] <hashtable>] [[-Recommendations] <string>] [[-XenstoreData] <hashtable>] [[-Tags] <string[]>] [[-BlockedOperations] <hashtable>] [[-SuspendSR] <XenRef[SR]>] [[-HardwarePlatformVersion] <long>] [[-VCPUsNumberLive] <long>] [[-NVRAM] <hashtable>] [[-HaRestartPriority] <string>] [[-HaAlwaysRun] <bool>] [[-MemoryDynamicMax] <long>] [[-MemoryDynamicMin] <long>] [[-MemoryDynamicRange] <long[]>] [[-MemoryStaticMax] <long>] [[-MemoryStaticMin] <long>] [[-MemoryStaticRange] <long[]>] [[-MemoryLimits] <long[]>] [[-Memory] <long>] [[-MemoryTargetLive] <long>] [[-HVMShadowMultiplier] <double>] [[-ShadowMultiplierLive] <double>] [[-VCPUsMax] <long>] [[-VCPUsAtStartup] <long>] [[-BiosStrings] <hashtable>] [[-ProtectionPolicy] <XenRef[VMPP]>] [[-SnapshotSchedule] <XenRef[VMSS]>] [[-StartDelay] <long>] [[-ShutdownDelay] <long>] [[-Order] <long>] [[-SuspendVDI] <XenRef[VDI]>] [[-Appliance] <XenRef[VM_appliance]>] [[-HasVendorDevice] <bool>] [[-ActionsAfterCrash] <on_crash_behaviour>] [[-DomainType] <domain_type>] [[-HVMBootPolicy] <string>] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]] [-Ref] <XenRef[VM]> [[-PassThru]] [[-NameLabel] <string>] [[-NameDescription] <string>] [[-UserVersion] <long>] [[-IsATemplate] <bool>] [[-Affinity] <XenRef[Host]>] [[-VCPUsParams] <hashtable>] [[-ActionsAfterShutdown] <on_normal_exit>] [[-ActionsAfterReboot] <on_normal_exit>] [[-PVBootloader] <string>] [[-PVKernel] <string>] [[-PVRamdisk] <string>] [[-PVArgs] <string>] [[-PVBootloaderArgs] <string>] [[-PVLegacyArgs] <string>] [[-HVMBootParams] <hashtable>] [[-Platform] <hashtable>] [[-PCIBus] <string>] [[-OtherConfig] <hashtable>] [[-Recommendations] <string>] [[-XenstoreData] <hashtable>] [[-Tags] <string[]>] [[-BlockedOperations] <hashtable>] [[-SuspendSR] <XenRef[SR]>] [[-HardwarePlatformVersion] <long>] [[-VCPUsNumberLive] <long>] [[-NVRAM] <hashtable>] [[-HaRestartPriority] <string>] [[-HaAlwaysRun] <bool>] [[-MemoryDynamicMax] <long>] [[-MemoryDynamicMin] <long>] [[-MemoryDynamicRange] <long[]>] [[-MemoryStaticMax] <long>] [[-MemoryStaticMin] <long>] [[-MemoryStaticRange] <long[]>] [[-MemoryLimits] <long[]>] [[-Memory] <long>] [[-MemoryTargetLive] <long>] [[-HVMShadowMultiplier] <double>] [[-ShadowMultiplierLive] <double>] [[-VCPUsMax] <long>] [[-VCPUsAtStartup] <long>] [[-BiosStrings] <hashtable>] [[-ProtectionPolicy] <XenRef[VMPP]>] [[-SnapshotSchedule] <XenRef[VMSS]>] [[-StartDelay] <long>] [[-ShutdownDelay] <long>] [[-Order] <long>] [[-SuspendVDI] <XenRef[VDI]>] [[-Appliance] <XenRef[VM_appliance]>] [[-HasVendorDevice] <bool>] [[-ActionsAfterCrash] <on_crash_behaviour>] [[-DomainType] <domain_type>] [[-HVMBootPolicy] <string>] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]] [-Uuid] <guid> [[-PassThru]] [[-NameLabel] <string>] [[-NameDescription] <string>] [[-UserVersion] <long>] [[-IsATemplate] <bool>] [[-Affinity] <XenRef[Host]>] [[-VCPUsParams] <hashtable>] [[-ActionsAfterShutdown] <on_normal_exit>] [[-ActionsAfterReboot] <on_normal_exit>] [[-PVBootloader] <string>] [[-PVKernel] <string>] [[-PVRamdisk] <string>] [[-PVArgs] <string>] [[-PVBootloaderArgs] <string>] [[-PVLegacyArgs] <string>] [[-HVMBootParams] <hashtable>] [[-Platform] <hashtable>] [[-PCIBus] <string>] [[-OtherConfig] <hashtable>] [[-Recommendations] <string>] [[-XenstoreData] <hashtable>] [[-Tags] <string[]>] [[-BlockedOperations] <hashtable>] [[-SuspendSR] <XenRef[SR]>] [[-HardwarePlatformVersion] <long>] [[-VCPUsNumberLive] <long>] [[-NVRAM] <hashtable>] [[-HaRestartPriority] <string>] [[-HaAlwaysRun] <bool>] [[-MemoryDynamicMax] <long>] [[-MemoryDynamicMin] <long>] [[-MemoryDynamicRange] <long[]>] [[-MemoryStaticMax] <long>] [[-MemoryStaticMin] <long>] [[-MemoryStaticRange] <long[]>] [[-MemoryLimits] <long[]>] [[-Memory] <long>] [[-MemoryTargetLive] <long>] [[-HVMShadowMultiplier] <double>] [[-ShadowMultiplierLive] <double>] [[-VCPUsMax] <long>] [[-VCPUsAtStartup] <long>] [[-BiosStrings] <hashtable>] [[-ProtectionPolicy] <XenRef[VMPP]>] [[-SnapshotSchedule] <XenRef[VMSS]>] [[-StartDelay] <long>] [[-ShutdownDelay] <long>] [[-Order] <long>] [[-SuspendVDI] <XenRef[VDI]>] [[-Appliance] <XenRef[VM_appliance]>] [[-HasVendorDevice] <bool>] [[-ActionsAfterCrash] <on_crash_behaviour>] [[-DomainType] <domain_type>] [[-HVMBootPolicy] <string>] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]] [-Name] <string> [[-PassThru]] [[-NameLabel] <string>] [[-NameDescription] <string>] [[-UserVersion] <long>] [[-IsATemplate] <bool>] [[-Affinity] <XenRef[Host]>] [[-VCPUsParams] <hashtable>] [[-ActionsAfterShutdown] <on_normal_exit>] [[-ActionsAfterReboot] <on_normal_exit>] [[-PVBootloader] <string>] [[-PVKernel] <string>] [[-PVRamdisk] <string>] [[-PVArgs] <string>] [[-PVBootloaderArgs] <string>] [[-PVLegacyArgs] <string>] [[-HVMBootParams] <hashtable>] [[-Platform] <hashtable>] [[-PCIBus] <string>] [[-OtherConfig] <hashtable>] [[-Recommendations] <string>] [[-XenstoreData] <hashtable>] [[-Tags] <string[]>] [[-BlockedOperations] <hashtable>] [[-SuspendSR] <XenRef[SR]>] [[-HardwarePlatformVersion] <long>] [[-VCPUsNumberLive] <long>] [[-NVRAM] <hashtable>] [[-HaRestartPriority] <string>] [[-HaAlwaysRun] <bool>] [[-MemoryDynamicMax] <long>] [[-MemoryDynamicMin] <long>] [[-MemoryDynamicRange] <long[]>] [[-MemoryStaticMax] <long>] [[-MemoryStaticMin] <long>] [[-MemoryStaticRange] <long[]>] [[-MemoryLimits] <long[]>] [[-Memory] <long>] [[-MemoryTargetLive] <long>] [[-HVMShadowMultiplier] <double>] [[-ShadowMultiplierLive] <double>] [[-VCPUsMax] <long>] [[-VCPUsAtStartup] <long>] [[-BiosStrings] <hashtable>] [[-ProtectionPolicy] <XenRef[VMPP]>] [[-SnapshotSchedule] <XenRef[VMSS]>] [[-StartDelay] <long>] [[-ShutdownDelay] <long>] [[-Order] <long>] [[-SuspendVDI] <XenRef[VDI]>] [[-Appliance] <XenRef[VM_appliance]>] [[-HasVendorDevice] <bool>] [[-ActionsAfterCrash] <on_crash_behaviour>] [[-DomainType] <domain_type>] [[-HVMBootPolicy] <string>] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]]
```
### Parameters
| Name | Type | Required | Default Value | Description |
| :--- | :--- | :------- | :------------ | :---------- |
| ActionsAfterCrash | on_crash_behaviour | False |  |  |
| ActionsAfterReboot | on_normal_exit | False |  |  |
| ActionsAfterShutdown | on_normal_exit | False |  |  |
| Affinity | XenRef[Host] | False |  |  |
| Appliance | XenRef[VM_appliance] | False |  |  |
| BestEffort | switch | False |  |  |
| BiosStrings | hashtable | False |  |  |
| BlockedOperations | hashtable | False |  |  |
| Confirm | switch | False |  |  |
| DomainType | domain_type | False |  |  |
| HVMBootParams | hashtable | False |  |  |
| HVMBootPolicy | string | False |  |  |
| HVMShadowMultiplier | double | False |  |  |
| HaAlwaysRun | bool | False |  |  |
| HaRestartPriority | string | False |  |  |
| HardwarePlatformVersion | long | False |  |  |
| HasVendorDevice | bool | False |  |  |
| IsATemplate | bool | False |  |  |
| Memory | long | False |  |  |
| MemoryDynamicMax | long | False |  |  |
| MemoryDynamicMin | long | False |  |  |
| MemoryDynamicRange | long[] | False |  |  |
| MemoryLimits | long[] | False |  |  |
| MemoryStaticMax | long | False |  |  |
| MemoryStaticMin | long | False |  |  |
| MemoryStaticRange | long[] | False |  |  |
| MemoryTargetLive | long | False |  |  |
| NVRAM | hashtable | False |  |  |
| Name | string | True |  |  |
| NameDescription | string | False |  |  |
| NameLabel | string | False |  |  |
| Order | long | False |  |  |
| OtherConfig | hashtable | False |  |  |
| PCIBus | string | False |  |  |
| PVArgs | string | False |  |  |
| PVBootloader | string | False |  |  |
| PVBootloaderArgs | string | False |  |  |
| PVKernel | string | False |  |  |
| PVLegacyArgs | string | False |  |  |
| PVRamdisk | string | False |  |  |
| PassThru | switch | False |  |  |
| Platform | hashtable | False |  |  |
| ProtectionPolicy | XenRef[VMPP] | False |  |  |
| Recommendations | string | False |  |  |
| Ref | XenRef[VM] | True |  |  |
| SessionOpaqueRef | string | False |  |  |
| ShadowMultiplierLive | double | False |  |  |
| ShutdownDelay | long | False |  |  |
| SnapshotSchedule | XenRef[VMSS] | False |  |  |
| StartDelay | long | False |  |  |
| SuspendSR | XenRef[SR] | False |  |  |
| SuspendVDI | XenRef[VDI] | False |  |  |
| Tags | string[] | False |  |  |
| UserVersion | long | False |  |  |
| Uuid | guid | True |  |  |
| VCPUsAtStartup | long | False |  |  |
| VCPUsMax | long | False |  |  |
| VCPUsNumberLive | long | False |  |  |
| VCPUsParams | hashtable | False |  |  |
| VM | VM | True |  |  |
| WhatIf | switch | False |  |  |
| XenstoreData | hashtable | False |  |  |
### Procedure
None

### Inputs
```
XenAPI.VM
XenAPI.XenRef`1[[XenAPI.VM, XenServer, Version=8.2.3.0, Culture=neutral, PublicKeyToken=d247b8b0ac7959e9]]
System.Guid
System.String

```
### Outputs
```
XenAPI.VM
XenAPI.Task
System.Void

```
### Links
None

### Examples

Set-XenVM [-VM] <VM> [-PassThru] [-NameLabel <string>] [-NameDescription <string>] [-UserVersion <long>] [-IsATemplate <bool>] [-Affinity <XenRef[Host]>] [-VCPUsParams <hashtable>] [-ActionsAfterShutdown <on_normal_exit>] [-ActionsAfterReboot <on_normal_exit>] [-PVBootloader <string>] [-PVKernel <string>] [-PVRamdisk <string>] [-PVArgs <string>] [-PVBootloaderArgs <string>] [-PVLegacyArgs <string>] [-HVMBootParams <hashtable>] [-Platform <hashtable>] [-PCIBus <string>] [-OtherConfig <hashtable>] [-Recommendations <string>] [-XenstoreData <hashtable>] [-Tags <string[]>] [-BlockedOperations <hashtable>] [-SuspendSR <XenRef[SR]>] [-HardwarePlatformVersion <long>] [-VCPUsNumberLive <long>] [-NVRAM <hashtable>] [-HaRestartPriority <string>] [-HaAlwaysRun <bool>] [-MemoryDynamicMax <long>] [-MemoryDynamicMin <long>] [-MemoryDynamicRange <long[]>] [-MemoryStaticMax <long>] [-MemoryStaticMin <long>] [-MemoryStaticRange <long[]>] [-MemoryLimits <long[]>] [-Memory <long>] [-MemoryTargetLive <long>] [-HVMShadowMultiplier <double>] [-ShadowMultiplierLive <double>] [-VCPUsMax <long>] [-VCPUsAtStartup <long>] [-BiosStrings <hashtable>] [-ProtectionPolicy <XenRef[VMPP]>] [-SnapshotSchedule <XenRef[VMSS]>] [-StartDelay <long>] [-ShutdownDelay <long>] [-Order <long>] [-SuspendVDI <XenRef[VDI]>] [-Appliance <XenRef[VM_appliance]>] [-HasVendorDevice <bool>] [-ActionsAfterCrash <on_crash_behaviour>] [-DomainType <domain_type>] [-HVMBootPolicy <string>] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [<CommonParameters>]

Set-XenVM [-Ref] <XenRef[VM]> [-PassThru] [-NameLabel <string>] [-NameDescription <string>] [-UserVersion <long>] [-IsATemplate <bool>] [-Affinity <XenRef[Host]>] [-VCPUsParams <hashtable>] [-ActionsAfterShutdown <on_normal_exit>] [-ActionsAfterReboot <on_normal_exit>] [-PVBootloader <string>] [-PVKernel <string>] [-PVRamdisk <string>] [-PVArgs <string>] [-PVBootloaderArgs <string>] [-PVLegacyArgs <string>] [-HVMBootParams <hashtable>] [-Platform <hashtable>] [-PCIBus <string>] [-OtherConfig <hashtable>] [-Recommendations <string>] [-XenstoreData <hashtable>] [-Tags <string[]>] [-BlockedOperations <hashtable>] [-SuspendSR <XenRef[SR]>] [-HardwarePlatformVersion <long>] [-VCPUsNumberLive <long>] [-NVRAM <hashtable>] [-HaRestartPriority <string>] [-HaAlwaysRun <bool>] [-MemoryDynamicMax <long>] [-MemoryDynamicMin <long>] [-MemoryDynamicRange <long[]>] [-MemoryStaticMax <long>] [-MemoryStaticMin <long>] [-MemoryStaticRange <long[]>] [-MemoryLimits <long[]>] [-Memory <long>] [-MemoryTargetLive <long>] [-HVMShadowMultiplier <double>] [-ShadowMultiplierLive <double>] [-VCPUsMax <long>] [-VCPUsAtStartup <long>] [-BiosStrings <hashtable>] [-ProtectionPolicy <XenRef[VMPP]>] [-SnapshotSchedule <XenRef[VMSS]>] [-StartDelay <long>] [-ShutdownDelay <long>] [-Order <long>] [-SuspendVDI <XenRef[VDI]>] [-Appliance <XenRef[VM_appliance]>] [-HasVendorDevice <bool>] [-ActionsAfterCrash <on_crash_behaviour>] [-DomainType <domain_type>] [-HVMBootPolicy <string>] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [<CommonParameters>]

Set-XenVM [-Uuid] <guid> [-PassThru] [-NameLabel <string>] [-NameDescription <string>] [-UserVersion <long>] [-IsATemplate <bool>] [-Affinity <XenRef[Host]>] [-VCPUsParams <hashtable>] [-ActionsAfterShutdown <on_normal_exit>] [-ActionsAfterReboot <on_normal_exit>] [-PVBootloader <string>] [-PVKernel <string>] [-PVRamdisk <string>] [-PVArgs <string>] [-PVBootloaderArgs <string>] [-PVLegacyArgs <string>] [-HVMBootParams <hashtable>] [-Platform <hashtable>] [-PCIBus <string>] [-OtherConfig <hashtable>] [-Recommendations <string>] [-XenstoreData <hashtable>] [-Tags <string[]>] [-BlockedOperations <hashtable>] [-SuspendSR <XenRef[SR]>] [-HardwarePlatformVersion <long>] [-VCPUsNumberLive <long>] [-NVRAM <hashtable>] [-HaRestartPriority <string>] [-HaAlwaysRun <bool>] [-MemoryDynamicMax <long>] [-MemoryDynamicMin <long>] [-MemoryDynamicRange <long[]>] [-MemoryStaticMax <long>] [-MemoryStaticMin <long>] [-MemoryStaticRange <long[]>] [-MemoryLimits <long[]>] [-Memory <long>] [-MemoryTargetLive <long>] [-HVMShadowMultiplier <double>] [-ShadowMultiplierLive <double>] [-VCPUsMax <long>] [-VCPUsAtStartup <long>] [-BiosStrings <hashtable>] [-ProtectionPolicy <XenRef[VMPP]>] [-SnapshotSchedule <XenRef[VMSS]>] [-StartDelay <long>] [-ShutdownDelay <long>] [-Order <long>] [-SuspendVDI <XenRef[VDI]>] [-Appliance <XenRef[VM_appliance]>] [-HasVendorDevice <bool>] [-ActionsAfterCrash <on_crash_behaviour>] [-DomainType <domain_type>] [-HVMBootPolicy <string>] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [<CommonParameters>]

Set-XenVM [-Name] <string> [-PassThru] [-NameLabel <string>] [-NameDescription <string>] [-UserVersion <long>] [-IsATemplate <bool>] [-Affinity <XenRef[Host]>] [-VCPUsParams <hashtable>] [-ActionsAfterShutdown <on_normal_exit>] [-ActionsAfterReboot <on_normal_exit>] [-PVBootloader <string>] [-PVKernel <string>] [-PVRamdisk <string>] [-PVArgs <string>] [-PVBootloaderArgs <string>] [-PVLegacyArgs <string>] [-HVMBootParams <hashtable>] [-Platform <hashtable>] [-PCIBus <string>] [-OtherConfig <hashtable>] [-Recommendations <string>] [-XenstoreData <hashtable>] [-Tags <string[]>] [-BlockedOperations <hashtable>] [-SuspendSR <XenRef[SR]>] [-HardwarePlatformVersion <long>] [-VCPUsNumberLive <long>] [-NVRAM <hashtable>] [-HaRestartPriority <string>] [-HaAlwaysRun <bool>] [-MemoryDynamicMax <long>] [-MemoryDynamicMin <long>] [-MemoryDynamicRange <long[]>] [-MemoryStaticMax <long>] [-MemoryStaticMin <long>] [-MemoryStaticRange <long[]>] [-MemoryLimits <long[]>] [-Memory <long>] [-MemoryTargetLive <long>] [-HVMShadowMultiplier <double>] [-ShadowMultiplierLive <double>] [-VCPUsMax <long>] [-VCPUsAtStartup <long>] [-BiosStrings <hashtable>] [-ProtectionPolicy <XenRef[VMPP]>] [-SnapshotSchedule <XenRef[VMSS]>] [-StartDelay <long>] [-ShutdownDelay <long>] [-Order <long>] [-SuspendVDI <XenRef[VDI]>] [-Appliance <XenRef[VM_appliance]>] [-HasVendorDevice <bool>] [-ActionsAfterCrash <on_crash_behaviour>] [-DomainType <domain_type>] [-HVMBootPolicy <string>] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [<CommonParameters>]


## Set-XenVMAppliance

### Synopsis
None

### Description
None

### Syntax
```
Set-XenVMAppliance [-VMAppliance] <VM_appliance> [[-PassThru]] [[-NameLabel] <string>] [[-NameDescription] <string>] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]] [-Ref] <XenRef[VM_appliance]> [[-PassThru]] [[-NameLabel] <string>] [[-NameDescription] <string>] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]] [-Uuid] <guid> [[-PassThru]] [[-NameLabel] <string>] [[-NameDescription] <string>] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]] [-Name] <string> [[-PassThru]] [[-NameLabel] <string>] [[-NameDescription] <string>] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]]
```
### Parameters
| Name | Type | Required | Default Value | Description |
| :--- | :--- | :------- | :------------ | :---------- |
| BestEffort | switch | False |  |  |
| Confirm | switch | False |  |  |
| Name | string | True |  |  |
| NameDescription | string | False |  |  |
| NameLabel | string | False |  |  |
| PassThru | switch | False |  |  |
| Ref | XenRef[VM_appliance] | True |  |  |
| SessionOpaqueRef | string | False |  |  |
| Uuid | guid | True |  |  |
| VMAppliance | VM_appliance | True |  |  |
| WhatIf | switch | False |  |  |
### Procedure
None

### Inputs
```
XenAPI.VM_appliance
XenAPI.XenRef`1[[XenAPI.VM_appliance, XenServer, Version=8.2.3.0, Culture=neutral, PublicKeyToken=d247b8b0ac7959e9]]
System.Guid
System.String

```
### Outputs
```
XenAPI.VM_appliance
System.Void

```
### Links
None

### Examples

Set-XenVMAppliance [-VMAppliance] <VM_appliance> [-PassThru] [-NameLabel <string>] [-NameDescription <string>] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [<CommonParameters>]

Set-XenVMAppliance [-Ref] <XenRef[VM_appliance]> [-PassThru] [-NameLabel <string>] [-NameDescription <string>] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [<CommonParameters>]

Set-XenVMAppliance [-Uuid] <guid> [-PassThru] [-NameLabel <string>] [-NameDescription <string>] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [<CommonParameters>]

Set-XenVMAppliance [-Name] <string> [-PassThru] [-NameLabel <string>] [-NameDescription <string>] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [<CommonParameters>]


## Set-XenVMGuestMetrics

### Synopsis
None

### Description
None

### Syntax
```
Set-XenVMGuestMetrics [-VMGuestMetrics] <VM_guest_metrics> [[-PassThru]] [[-OtherConfig] <hashtable>] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]] [-Ref] <XenRef[VM_guest_metrics]> [[-PassThru]] [[-OtherConfig] <hashtable>] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]] [-Uuid] <guid> [[-PassThru]] [[-OtherConfig] <hashtable>] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]]
```
### Parameters
| Name | Type | Required | Default Value | Description |
| :--- | :--- | :------- | :------------ | :---------- |
| BestEffort | switch | False |  |  |
| Confirm | switch | False |  |  |
| OtherConfig | hashtable | False |  |  |
| PassThru | switch | False |  |  |
| Ref | XenRef[VM_guest_metrics] | True |  |  |
| SessionOpaqueRef | string | False |  |  |
| Uuid | guid | True |  |  |
| VMGuestMetrics | VM_guest_metrics | True |  |  |
| WhatIf | switch | False |  |  |
### Procedure
None

### Inputs
```
XenAPI.VM_guest_metrics
XenAPI.XenRef`1[[XenAPI.VM_guest_metrics, XenServer, Version=8.2.3.0, Culture=neutral, PublicKeyToken=d247b8b0ac7959e9]]
System.Guid

```
### Outputs
```
XenAPI.VM_guest_metrics
System.Void

```
### Links
None

### Examples

Set-XenVMGuestMetrics [-VMGuestMetrics] <VM_guest_metrics> [-PassThru] [-OtherConfig <hashtable>] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [<CommonParameters>]

Set-XenVMGuestMetrics [-Ref] <XenRef[VM_guest_metrics]> [-PassThru] [-OtherConfig <hashtable>] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [<CommonParameters>]

Set-XenVMGuestMetrics [-Uuid] <guid> [-PassThru] [-OtherConfig <hashtable>] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [<CommonParameters>]


## Set-XenVMMetrics

### Synopsis
None

### Description
None

### Syntax
```
Set-XenVMMetrics [-VMMetrics] <VM_metrics> [[-PassThru]] [[-OtherConfig] <hashtable>] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]] [-Ref] <XenRef[VM_metrics]> [[-PassThru]] [[-OtherConfig] <hashtable>] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]] [-Uuid] <guid> [[-PassThru]] [[-OtherConfig] <hashtable>] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]]
```
### Parameters
| Name | Type | Required | Default Value | Description |
| :--- | :--- | :------- | :------------ | :---------- |
| BestEffort | switch | False |  |  |
| Confirm | switch | False |  |  |
| OtherConfig | hashtable | False |  |  |
| PassThru | switch | False |  |  |
| Ref | XenRef[VM_metrics] | True |  |  |
| SessionOpaqueRef | string | False |  |  |
| Uuid | guid | True |  |  |
| VMMetrics | VM_metrics | True |  |  |
| WhatIf | switch | False |  |  |
### Procedure
None

### Inputs
```
XenAPI.VM_metrics
XenAPI.XenRef`1[[XenAPI.VM_metrics, XenServer, Version=8.2.3.0, Culture=neutral, PublicKeyToken=d247b8b0ac7959e9]]
System.Guid

```
### Outputs
```
XenAPI.VM_metrics
System.Void

```
### Links
None

### Examples

Set-XenVMMetrics [-VMMetrics] <VM_metrics> [-PassThru] [-OtherConfig <hashtable>] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [<CommonParameters>]

Set-XenVMMetrics [-Ref] <XenRef[VM_metrics]> [-PassThru] [-OtherConfig <hashtable>] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [<CommonParameters>]

Set-XenVMMetrics [-Uuid] <guid> [-PassThru] [-OtherConfig <hashtable>] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [<CommonParameters>]


## Set-XenVMPP

### Synopsis
None

### Description
None

### Syntax
```
Set-XenVMPP [-VMPP] <VMPP> [[-PassThru]] [[-NameLabel] <string>] [[-NameDescription] <string>] [[-IsPolicyEnabled] <bool>] [[-BackupType] <vmpp_backup_type>] [[-BackupRetentionValue] <long>] [[-BackupFrequency] <vmpp_backup_frequency>] [[-BackupSchedule] <hashtable>] [[-ArchiveFrequency] <vmpp_archive_frequency>] [[-ArchiveSchedule] <hashtable>] [[-ArchiveTargetType] <vmpp_archive_target_type>] [[-ArchiveTargetConfig] <hashtable>] [[-IsAlarmEnabled] <bool>] [[-AlarmConfig] <hashtable>] [[-BackupLastRunTime] <datetime>] [[-ArchiveLastRunTime] <datetime>] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]] [-Ref] <XenRef[VMPP]> [[-PassThru]] [[-NameLabel] <string>] [[-NameDescription] <string>] [[-IsPolicyEnabled] <bool>] [[-BackupType] <vmpp_backup_type>] [[-BackupRetentionValue] <long>] [[-BackupFrequency] <vmpp_backup_frequency>] [[-BackupSchedule] <hashtable>] [[-ArchiveFrequency] <vmpp_archive_frequency>] [[-ArchiveSchedule] <hashtable>] [[-ArchiveTargetType] <vmpp_archive_target_type>] [[-ArchiveTargetConfig] <hashtable>] [[-IsAlarmEnabled] <bool>] [[-AlarmConfig] <hashtable>] [[-BackupLastRunTime] <datetime>] [[-ArchiveLastRunTime] <datetime>] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]] [-Uuid] <guid> [[-PassThru]] [[-NameLabel] <string>] [[-NameDescription] <string>] [[-IsPolicyEnabled] <bool>] [[-BackupType] <vmpp_backup_type>] [[-BackupRetentionValue] <long>] [[-BackupFrequency] <vmpp_backup_frequency>] [[-BackupSchedule] <hashtable>] [[-ArchiveFrequency] <vmpp_archive_frequency>] [[-ArchiveSchedule] <hashtable>] [[-ArchiveTargetType] <vmpp_archive_target_type>] [[-ArchiveTargetConfig] <hashtable>] [[-IsAlarmEnabled] <bool>] [[-AlarmConfig] <hashtable>] [[-BackupLastRunTime] <datetime>] [[-ArchiveLastRunTime] <datetime>] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]] [-Name] <string> [[-PassThru]] [[-NameLabel] <string>] [[-NameDescription] <string>] [[-IsPolicyEnabled] <bool>] [[-BackupType] <vmpp_backup_type>] [[-BackupRetentionValue] <long>] [[-BackupFrequency] <vmpp_backup_frequency>] [[-BackupSchedule] <hashtable>] [[-ArchiveFrequency] <vmpp_archive_frequency>] [[-ArchiveSchedule] <hashtable>] [[-ArchiveTargetType] <vmpp_archive_target_type>] [[-ArchiveTargetConfig] <hashtable>] [[-IsAlarmEnabled] <bool>] [[-AlarmConfig] <hashtable>] [[-BackupLastRunTime] <datetime>] [[-ArchiveLastRunTime] <datetime>] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]]
```
### Parameters
| Name | Type | Required | Default Value | Description |
| :--- | :--- | :------- | :------------ | :---------- |
| AlarmConfig | hashtable | False |  |  |
| ArchiveFrequency | vmpp_archive_frequency | False |  |  |
| ArchiveLastRunTime | datetime | False |  |  |
| ArchiveSchedule | hashtable | False |  |  |
| ArchiveTargetConfig | hashtable | False |  |  |
| ArchiveTargetType | vmpp_archive_target_type | False |  |  |
| BackupFrequency | vmpp_backup_frequency | False |  |  |
| BackupLastRunTime | datetime | False |  |  |
| BackupRetentionValue | long | False |  |  |
| BackupSchedule | hashtable | False |  |  |
| BackupType | vmpp_backup_type | False |  |  |
| BestEffort | switch | False |  |  |
| Confirm | switch | False |  |  |
| IsAlarmEnabled | bool | False |  |  |
| IsPolicyEnabled | bool | False |  |  |
| Name | string | True |  |  |
| NameDescription | string | False |  |  |
| NameLabel | string | False |  |  |
| PassThru | switch | False |  |  |
| Ref | XenRef[VMPP] | True |  |  |
| SessionOpaqueRef | string | False |  |  |
| Uuid | guid | True |  |  |
| VMPP | VMPP | True |  |  |
| WhatIf | switch | False |  |  |
### Procedure
None

### Inputs
```
XenAPI.VMPP
XenAPI.XenRef`1[[XenAPI.VMPP, XenServer, Version=8.2.3.0, Culture=neutral, PublicKeyToken=d247b8b0ac7959e9]]
System.Guid
System.String

```
### Outputs
```
XenAPI.VMPP
System.Void

```
### Links
None

### Examples

Set-XenVMPP [-VMPP] <VMPP> [-PassThru] [-NameLabel <string>] [-NameDescription <string>] [-IsPolicyEnabled <bool>] [-BackupType <vmpp_backup_type>] [-BackupRetentionValue <long>] [-BackupFrequency <vmpp_backup_frequency>] [-BackupSchedule <hashtable>] [-ArchiveFrequency <vmpp_archive_frequency>] [-ArchiveSchedule <hashtable>] [-ArchiveTargetType <vmpp_archive_target_type>] [-ArchiveTargetConfig <hashtable>] [-IsAlarmEnabled <bool>] [-AlarmConfig <hashtable>] [-BackupLastRunTime <datetime>] [-ArchiveLastRunTime <datetime>] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [<CommonParameters>]

Set-XenVMPP [-Ref] <XenRef[VMPP]> [-PassThru] [-NameLabel <string>] [-NameDescription <string>] [-IsPolicyEnabled <bool>] [-BackupType <vmpp_backup_type>] [-BackupRetentionValue <long>] [-BackupFrequency <vmpp_backup_frequency>] [-BackupSchedule <hashtable>] [-ArchiveFrequency <vmpp_archive_frequency>] [-ArchiveSchedule <hashtable>] [-ArchiveTargetType <vmpp_archive_target_type>] [-ArchiveTargetConfig <hashtable>] [-IsAlarmEnabled <bool>] [-AlarmConfig <hashtable>] [-BackupLastRunTime <datetime>] [-ArchiveLastRunTime <datetime>] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [<CommonParameters>]

Set-XenVMPP [-Uuid] <guid> [-PassThru] [-NameLabel <string>] [-NameDescription <string>] [-IsPolicyEnabled <bool>] [-BackupType <vmpp_backup_type>] [-BackupRetentionValue <long>] [-BackupFrequency <vmpp_backup_frequency>] [-BackupSchedule <hashtable>] [-ArchiveFrequency <vmpp_archive_frequency>] [-ArchiveSchedule <hashtable>] [-ArchiveTargetType <vmpp_archive_target_type>] [-ArchiveTargetConfig <hashtable>] [-IsAlarmEnabled <bool>] [-AlarmConfig <hashtable>] [-BackupLastRunTime <datetime>] [-ArchiveLastRunTime <datetime>] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [<CommonParameters>]

Set-XenVMPP [-Name] <string> [-PassThru] [-NameLabel <string>] [-NameDescription <string>] [-IsPolicyEnabled <bool>] [-BackupType <vmpp_backup_type>] [-BackupRetentionValue <long>] [-BackupFrequency <vmpp_backup_frequency>] [-BackupSchedule <hashtable>] [-ArchiveFrequency <vmpp_archive_frequency>] [-ArchiveSchedule <hashtable>] [-ArchiveTargetType <vmpp_archive_target_type>] [-ArchiveTargetConfig <hashtable>] [-IsAlarmEnabled <bool>] [-AlarmConfig <hashtable>] [-BackupLastRunTime <datetime>] [-ArchiveLastRunTime <datetime>] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [<CommonParameters>]


## Set-XenVMSS

### Synopsis
None

### Description
None

### Syntax
```
Set-XenVMSS [-VMSS] <VMSS> [[-PassThru]] [[-NameLabel] <string>] [[-NameDescription] <string>] [[-Enabled] <bool>] [[-RetainedSnapshots] <long>] [[-Frequency] <vmss_frequency>] [[-Schedule] <hashtable>] [[-LastRunTime] <datetime>] [[-Type] <vmss_type>] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]] [-Ref] <XenRef[VMSS]> [[-PassThru]] [[-NameLabel] <string>] [[-NameDescription] <string>] [[-Enabled] <bool>] [[-RetainedSnapshots] <long>] [[-Frequency] <vmss_frequency>] [[-Schedule] <hashtable>] [[-LastRunTime] <datetime>] [[-Type] <vmss_type>] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]] [-Uuid] <guid> [[-PassThru]] [[-NameLabel] <string>] [[-NameDescription] <string>] [[-Enabled] <bool>] [[-RetainedSnapshots] <long>] [[-Frequency] <vmss_frequency>] [[-Schedule] <hashtable>] [[-LastRunTime] <datetime>] [[-Type] <vmss_type>] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]] [-Name] <string> [[-PassThru]] [[-NameLabel] <string>] [[-NameDescription] <string>] [[-Enabled] <bool>] [[-RetainedSnapshots] <long>] [[-Frequency] <vmss_frequency>] [[-Schedule] <hashtable>] [[-LastRunTime] <datetime>] [[-Type] <vmss_type>] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]]
```
### Parameters
| Name | Type | Required | Default Value | Description |
| :--- | :--- | :------- | :------------ | :---------- |
| BestEffort | switch | False |  |  |
| Confirm | switch | False |  |  |
| Enabled | bool | False |  |  |
| Frequency | vmss_frequency | False |  |  |
| LastRunTime | datetime | False |  |  |
| Name | string | True |  |  |
| NameDescription | string | False |  |  |
| NameLabel | string | False |  |  |
| PassThru | switch | False |  |  |
| Ref | XenRef[VMSS] | True |  |  |
| RetainedSnapshots | long | False |  |  |
| Schedule | hashtable | False |  |  |
| SessionOpaqueRef | string | False |  |  |
| Type | vmss_type | False |  |  |
| Uuid | guid | True |  |  |
| VMSS | VMSS | True |  |  |
| WhatIf | switch | False |  |  |
### Procedure
None

### Inputs
```
XenAPI.VMSS
XenAPI.XenRef`1[[XenAPI.VMSS, XenServer, Version=8.2.3.0, Culture=neutral, PublicKeyToken=d247b8b0ac7959e9]]
System.Guid
System.String

```
### Outputs
```
XenAPI.VMSS
System.Void

```
### Links
None

### Examples

Set-XenVMSS [-VMSS] <VMSS> [-PassThru] [-NameLabel <string>] [-NameDescription <string>] [-Enabled <bool>] [-RetainedSnapshots <long>] [-Frequency <vmss_frequency>] [-Schedule <hashtable>] [-LastRunTime <datetime>] [-Type <vmss_type>] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [<CommonParameters>]

Set-XenVMSS [-Ref] <XenRef[VMSS]> [-PassThru] [-NameLabel <string>] [-NameDescription <string>] [-Enabled <bool>] [-RetainedSnapshots <long>] [-Frequency <vmss_frequency>] [-Schedule <hashtable>] [-LastRunTime <datetime>] [-Type <vmss_type>] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [<CommonParameters>]

Set-XenVMSS [-Uuid] <guid> [-PassThru] [-NameLabel <string>] [-NameDescription <string>] [-Enabled <bool>] [-RetainedSnapshots <long>] [-Frequency <vmss_frequency>] [-Schedule <hashtable>] [-LastRunTime <datetime>] [-Type <vmss_type>] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [<CommonParameters>]

Set-XenVMSS [-Name] <string> [-PassThru] [-NameLabel <string>] [-NameDescription <string>] [-Enabled <bool>] [-RetainedSnapshots <long>] [-Frequency <vmss_frequency>] [-Schedule <hashtable>] [-LastRunTime <datetime>] [-Type <vmss_type>] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [<CommonParameters>]


## Set-XenVUSB

### Synopsis
None

### Description
None

### Syntax
```
Set-XenVUSB [-VUSB] <VUSB> [[-PassThru]] [[-OtherConfig] <hashtable>] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]] [-Ref] <XenRef[VUSB]> [[-PassThru]] [[-OtherConfig] <hashtable>] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]] [-Uuid] <guid> [[-PassThru]] [[-OtherConfig] <hashtable>] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [[-WhatIf]] [[-Confirm]]
```
### Parameters
| Name | Type | Required | Default Value | Description |
| :--- | :--- | :------- | :------------ | :---------- |
| BestEffort | switch | False |  |  |
| Confirm | switch | False |  |  |
| OtherConfig | hashtable | False |  |  |
| PassThru | switch | False |  |  |
| Ref | XenRef[VUSB] | True |  |  |
| SessionOpaqueRef | string | False |  |  |
| Uuid | guid | True |  |  |
| VUSB | VUSB | True |  |  |
| WhatIf | switch | False |  |  |
### Procedure
None

### Inputs
```
XenAPI.VUSB
XenAPI.XenRef`1[[XenAPI.VUSB, XenServer, Version=8.2.3.0, Culture=neutral, PublicKeyToken=d247b8b0ac7959e9]]
System.Guid

```
### Outputs
```
XenAPI.VUSB
System.Void

```
### Links
None

### Examples

Set-XenVUSB [-VUSB] <VUSB> [-PassThru] [-OtherConfig <hashtable>] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [<CommonParameters>]

Set-XenVUSB [-Ref] <XenRef[VUSB]> [-PassThru] [-OtherConfig <hashtable>] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [<CommonParameters>]

Set-XenVUSB [-Uuid] <guid> [-PassThru] [-OtherConfig <hashtable>] [-BestEffort] [-SessionOpaqueRef <string>] [-WhatIf] [-Confirm] [<CommonParameters>]


## Wait-XenTask

### Synopsis
None

### Description
None

### Syntax
```
Wait-XenTask [-Task] <Task> [[-PassThru]] [[-ShowProgress]] [[-Progressbar] <ProgressBar>] [[-Min] <int>] [[-Max] <int>] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [-Ref] <XenRef[Task]> [[-PassThru]] [[-ShowProgress]] [[-Progressbar] <ProgressBar>] [[-Min] <int>] [[-Max] <int>] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [-Uuid] <guid> [[-PassThru]] [[-ShowProgress]] [[-Progressbar] <ProgressBar>] [[-Min] <int>] [[-Max] <int>] [[-BestEffort]] [[-SessionOpaqueRef] <string>] [-Name] <string> [[-PassThru]] [[-ShowProgress]] [[-Progressbar] <ProgressBar>] [[-Min] <int>] [[-Max] <int>] [[-BestEffort]] [[-SessionOpaqueRef] <string>]
```
### Parameters
| Name | Type | Required | Default Value | Description |
| :--- | :--- | :------- | :------------ | :---------- |
| BestEffort | switch | False |  |  |
| Max | int | False |  |  |
| Min | int | False |  |  |
| Name | string | True |  |  |
| PassThru | switch | False |  |  |
| Progressbar | ProgressBar | False |  |  |
| Ref | XenRef[Task] | True |  |  |
| SessionOpaqueRef | string | False |  |  |
| ShowProgress | switch | False |  |  |
| Task | Task | True |  |  |
| Uuid | guid | True |  |  |
### Procedure
None

### Inputs
```
XenAPI.Task
XenAPI.XenRef`1[[XenAPI.Task, XenServer, Version=8.2.3.0, Culture=neutral, PublicKeyToken=d247b8b0ac7959e9]]
System.Guid
System.String

```
### Outputs
```
System.Object
```
### Links
None

### Examples

Wait-XenTask [-Task] <Task> [-PassThru] [-ShowProgress] [-Progressbar <ProgressBar>] [-Min <int>] [-Max <int>] [-BestEffort] [-SessionOpaqueRef <string>] [<CommonParameters>]

Wait-XenTask [-Ref] <XenRef[Task]> [-PassThru] [-ShowProgress] [-Progressbar <ProgressBar>] [-Min <int>] [-Max <int>] [-BestEffort] [-SessionOpaqueRef <string>] [<CommonParameters>]

Wait-XenTask [-Uuid] <guid> [-PassThru] [-ShowProgress] [-Progressbar <ProgressBar>] [-Min <int>] [-Max <int>] [-BestEffort] [-SessionOpaqueRef <string>] [<CommonParameters>]

Wait-XenTask [-Name] <string> [-PassThru] [-ShowProgress] [-Progressbar <ProgressBar>] [-Min <int>] [-Max <int>] [-BestEffort] [-SessionOpaqueRef <string>] [<CommonParameters>]
