# On-Demand Snapshot

## Overview

Create a On-Demand Snapshot of a vSphere VM.

## Syntax

`on-demand-snapshot.sh [-c <IP_ADDRESS>] [-u <USERNAME>] [optional -p <PASSWORD> ] [-v <VM_NAME>]`

## Requirements

[jq - a lightweight and flexible command-line JSON processor.](https://stedolan.github.io/jq/download/)

[openssl - create the Base64 encoding of username:password used for authentication](https://www.openssl.org/)

[curl - call the Rubrik CDM RESTful API ](https://curl.haxx.se/)

## Example Output

```
Rubrik On-Demand Snapshot

Snapshot Progress:

16.12%
19.35%
19.35%
19.35%
61.29%

Snapshot successfully completed.
```
